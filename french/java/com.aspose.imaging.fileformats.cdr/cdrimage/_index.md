---
title: "CdrImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API de prise en charge du format d'image vectorielle CorelDRAW CDR constitue une boîte à outils essentielle pour les développeurs travaillant avec les graphiques vectoriels."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.cdr/cdrimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImage extends VectorMultipageImage implements ICdrImage
```

L'API de prise en charge du format d'image vectorielle CorelDRAW CDR est une boîte à outils essentielle pour les développeurs travaillant avec les graphiques vectoriels. Cette API permet le traitement fluide des fichiers CDR, permettant le stockage et la manipulation d'éléments divers tels que le texte, les lignes, les formes, les images, les couleurs et les effets. Grâce à ses capacités complètes, les développeurs peuvent travailler efficacement avec les représentations vectorielles du contenu des images, garantissant précision et flexibilité lors de la création et de la modification programmatique des graphiques vectoriels CorelDRAW.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CdrImage(InputStream stream, LoadOptions loadOptions)](#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Commencez à travailler avec la classe [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) sans effort en initialisant une nouvelle instance avec les paramètres stream et loadOptions. |
| [CdrImage(System.IO.Stream stream, LoadOptions loadOptions)](#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Commencez à travailler avec la classe [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) sans effort en initialisant une nouvelle instance avec les paramètres stream et loadOptions. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Récupérez la page par défaut de l'image facilement en utilisant cette propriété conviviale. |
| [isCached()](#isCached--) | Déterminez sans effort si les données de l'objet sont actuellement en cache, éliminant ainsi le besoin de lecture des données. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Récupérez la profondeur de couleur de l'image sans effort grâce à cette propriété conviviale. |
| [getPageCount()](#getPageCount--) | Récupérez ou mettez à jour sans effort le nombre total de pages de l'image avec cette propriété intuitive. |
| [getPages()](#getPages--) | Récupérez les pages de l'image de manière fluide grâce à cette propriété intuitive. |
| [getCdrDocument()](#getCdrDocument--) | Récupérez ou mettez à jour sans effort le document CDR en utilisant cette propriété intuitive. |
| [getFileFormat()](#getFileFormat--) | Récupérez le format de fichier de l'image sans effort avec cette propriété intuitive. |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image. |
| [cacheData()](#cacheData--) | Mettez en cache les données sans effort pour éviter tout chargement supplémentaire depuis la source sous-jacente avec cette méthode conviviale. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Personnalisez la palette de couleurs de l'image avec cette méthode intuitive. |

## Example: The following example shows how to cache all pages of a CDR image.

``` java
String dir = "c:\\temp\\";

// Chargez une image à partir d'un fichier CDR.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Cet appel met en cache uniquement la page par défaut.
    image.cacheData();

    // Mettez en cache toutes les pages afin qu'aucun chargement de données supplémentaire ne soit effectué depuis le flux de données sous-jacent.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CdrImage(InputStream stream, LoadOptions loadOptions) {#CdrImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(InputStream stream, LoadOptions loadOptions)
```


Commencez à travailler avec la classe [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) sans effort en initialisant une nouvelle instance avec les paramètres stream et loadOptions. Idéal pour les développeurs recherchant un moyen pratique de charger des images CDR à partir de diverses sources de données tout en personnalisant le processus de chargement selon les besoins.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

### CdrImage(System.IO.Stream stream, LoadOptions loadOptions) {#CdrImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public CdrImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Commencez à travailler avec la classe [CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) sans effort en initialisant une nouvelle instance avec les paramètres stream et loadOptions. Idéal pour les développeurs recherchant un moyen pratique de charger des images CDR à partir de diverses sources de données tout en personnalisant le processus de chargement selon les besoins.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | com.aspose.ms.System.IO.Stream | Le flux. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Récupérez la page par défaut de l'image facilement en utilisant cette propriété conviviale. Parfait pour les développeurs cherchant un accès rapide à la page principale de leur image, garantissant une navigation et une gestion efficaces.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Déterminez sans effort si les données de l'objet sont actuellement en cache, éliminant le besoin de lecture des données. Idéal pour les développeurs souhaitant optimiser les performances en exploitant efficacement les données en cache, assurant un accès plus rapide aux informations de l'objet.

**Returns:**
booléen - `true` si les données de l'objet sont en cache ; sinon, `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Récupérez la profondeur de couleur de l'image sans effort grâce à cette propriété conviviale. Idéal pour les développeurs souhaitant déterminer le niveau de détail ou la profondeur de couleur présent dans leurs images, assurant un traitement et une manipulation précis.

**Returns:**
int - Le nombre de bits par pixel de l'image.
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Récupérez ou mettez à jour sans effort le nombre total de pages de l'image avec cette propriété intuitive. Idéal pour les développeurs cherchant à gérer dynamiquement les images multipages, assurant une navigation et une manipulation efficaces du contenu de l'image.

**Returns:**
int - le nombre de pages.
### getPages() {#getPages--}
```
public final Image[] getPages()
```


Récupérez les pages de l'image de manière fluide avec cette propriété intuitive. Idéal pour les développeurs souhaitant accéder et manipuler les pages individuelles d'images multipages, garantissant une navigation et un traitement efficaces.

**Returns:**
com.aspose.imaging.Image[] - les pages.

**Example: The following example shows how to export a single page of CDR document to PDF.**

``` java
int pageNumber = 0;
String dir = "c:\\aspose.imaging\\java\\issues\\1445'\\";
String inputCdrFileName = dir + "tiger.cdr";
String outputPdfFileName = dir + "tiger.cdr.page" + pageNumber + ".pdf";

com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(inputCdrFileName);
try {
    com.aspose.imaging.Image imagePage = image.getPages()[pageNumber];

    com.aspose.imaging.imageoptions.PdfOptions pdfOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    com.aspose.imaging.imageoptions.CdrRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.CdrRasterizationOptions();
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    rasterizationOptions.setPageWidth(image.getWidth());
    rasterizationOptions.setPageHeight(image.getHeight());

    pdfOptions.setVectorRasterizationOptions(rasterizationOptions);

    imagePage.save(outputPdfFileName, pdfOptions);
}
finally {
    image.close();
}
```

### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Récupérez ou mettez à jour sans effort le document CDR en utilisant cette propriété intuitive. Idéal pour les développeurs souhaitant accéder ou modifier le document CDR, garantissant flexibilité et efficacité dans leurs applications.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupérez le format de fichier de l'image sans effort avec cette propriété intuitive. Idéal pour les développeurs cherchant à déterminer dynamiquement le format de leurs images, assurant compatibilité et traitement précis dans leurs applications.

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de l'image.

Valeur : la largeur de l'image.

**Returns:**
int - la largeur de l'image.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur de l'image.

Valeur : la hauteur de l'image.

**Returns:**
int - la hauteur de l'image.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cachez les données sans effort pour éviter tout chargement supplémentaire depuis la source sous-jacente avec cette méthode conviviale. Idéal pour les développeurs cherchant à optimiser les performances en préchargeant les données, assurant un accès plus rapide et un fonctionnement plus fluide dans leurs applications. `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)/[DataStreamSupporter.setDataStreamContainer\_internalized(StreamContainer)](../../com.aspose.imaging/datastreamsupporter\#setDataStreamContainer-internalized-StreamContainer-)).


**Example: The following example shows how to cache all pages of a CDR image.**

``` java
String dir = "c:\\temp\\";

// Chargez une image à partir d'un fichier CDR.
com.aspose.imaging.fileformats.cdr.CdrImage image = (com.aspose.imaging.fileformats.cdr.CdrImage) com.aspose.imaging.Image.load(dir + "sample.cdr");
try {
    // Cet appel met en cache uniquement la page par défaut.
    image.cacheData();

    // Mettez en cache toutes les pages afin qu'aucun chargement de données supplémentaire ne soit effectué depuis le flux de données sous-jacent.
    for (com.aspose.imaging.fileformats.cdr.CdrImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Personnalisez la palette de couleurs de l'image avec cette méthode intuitive. Idéal pour les développeurs souhaitant appliquer des schémas de couleurs ou des ajustements spécifiques de manière dynamique, garantissant un contrôle précis de l'apparence visuelle de leurs images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette à définir. |
| updateColors | boolean | si défini sur `true`, les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

