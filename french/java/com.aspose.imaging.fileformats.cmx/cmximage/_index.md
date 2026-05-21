---
title: "CmxImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API pour le format d'image vectorielle CMX de Corel Metafile Exchange avec prise en charge des descriptions de métadonnées constitue une solution complète pour les développeurs travaillant avec des fichiers CMX."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.cmx/cmximage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImage extends VectorMultipageImage implements ICmxImage
```

L'API pour le format d'image vectorielle Corel Metafile Exchange (CMX) avec prise en charge des descriptions de métadonnées constitue une solution complète pour les développeurs travaillant avec des fichiers CMX. Cette API permet le chargement fluide des images CMX, l'extraction des métadonnées telles que les bits par pixel, les dimensions des objets, et plus encore. Avec des fonctionnalités supplémentaires comme le redimensionnement, la rotation, la définition de palettes et la conversion vers d'autres formats, cette API permet aux développeurs de manipuler et de personnaliser efficacement les images vectorielles CMX afin de répondre à leurs exigences d'application spécifiques.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)](#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Commencez à travailler avec la classe [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) de manière fluide en initialisant une nouvelle instance avec les paramètres streamContainer et loadOptions. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Récupérez le format du fichier image sans effort grâce à cette propriété conviviale. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Récupérez la profondeur de couleur de l'image sans effort grâce à cette propriété conviviale. |
| [getDefaultPage()](#getDefaultPage--) | Récupérez sans effort la page par défaut de l'image grâce à cette propriété intuitive. |
| [isCached()](#isCached--) | Déterminez si les données de l'objet sont actuellement en cache, éliminant ainsi le besoin de lecture des données. |
| [getWidthF()](#getWidthF--) | Récupérez la largeur de l'objet en pouces grâce à cette propriété intuitive. |
| [getHeightF()](#getHeightF--) | Obtenez sans effort la hauteur de l'objet, mesurée en pouces, grâce à cette propriété conviviale. |
| [getDocument()](#getDocument--) | Récupérez le document CMX sans effort grâce à cette propriété intuitive. |
| [getCmxPage()](#getCmxPage--) | Récupérez sans effort la page CMX de l'image grâce à cette propriété intuitive. |
| [getPageCount()](#getPageCount--) | Récupérez le nombre total de pages de l'image grâce à cette propriété intuitive. |
| [getPages()](#getPages--) | Récupérez les pages de l'image de manière fluide grâce à cette propriété intuitive. |
| [cacheData()](#cacheData--) | Mettez en cache les données pour éviter tout chargement supplémentaire depuis la source sous-jacente [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) à l'aide de cette méthode pratique. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Personnalisez la palette de couleurs de l'image avec cette méthode intuitive. |

## Example: The following example shows how to cache all pages of a CMX image.

``` java
String dir = "c:\\temp\\";

// Chargez une image à partir d'un fichier CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Cet appel met en cache uniquement la page par défaut.
    image.cacheData();

    // Mettez en cache toutes les pages afin qu'aucun chargement de données supplémentaire ne soit effectué depuis le flux de données sous-jacent.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### CmxImage(StreamContainer streamContainer, LoadOptions loadOptions) {#CmxImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public CmxImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Commencez à travailler avec la classe [CmxImage](../../com.aspose.imaging.fileformats.cmx/cmximage) de manière fluide en initialisant une nouvelle instance avec les paramètres streamContainer et loadOptions. Idéal pour les développeurs recherchant un moyen pratique de charger des images CMX à partir de diverses sources de données tout en personnalisant le processus de chargement selon les besoins.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupérez le format du fichier image sans effort grâce à cette propriété conviviale. Idéal pour les développeurs souhaitant déterminer dynamiquement le format de leurs images, garantissant la compatibilité et un traitement précis dans leurs applications.

**Returns:**
long - Le format du fichier [FileFormat.Cmx](../../com.aspose.imaging/fileformat\#Cmx)
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Récupérez la profondeur de couleur de l'image sans effort grâce à cette propriété conviviale. Idéal pour les développeurs souhaitant déterminer le niveau de détail ou la profondeur de couleur présent dans leurs images, assurant un traitement et une manipulation précis.

**Returns:**
int - Le nombre de bits par pixel de l'image.
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Récupérez sans effort la page par défaut de l'image grâce à cette propriété intuitive. Idéal pour les développeurs recherchant un accès rapide à la page principale de leur image, garantissant une navigation et une gestion efficaces.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Déterminez si les données de l'objet sont actuellement en cache, éliminant le besoin de lecture des données. Idéal pour les développeurs cherchant à optimiser les performances en exploitant efficacement les données en cache, assurant un accès plus rapide aux informations de l'objet.

**Returns:**
booléen - `true` si les données de l'objet sont en cache ; sinon, `false`.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Récupérez la largeur de l'objet en pouces grâce à cette propriété intuitive. Idéal pour les développeurs recherchant des mesures précises des objets dans leurs applications, garantissant une mise en page et une présentation exactes.

**Returns:**
float - La largeur de l'objet, en pouces.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Obtenez sans effort la hauteur de l'objet, mesurée en pouces, grâce à cette propriété conviviale. Idéal pour les développeurs recherchant des informations dimensionnelles précises pour une mise en page et une présentation efficaces dans leurs applications.

**Returns:**
float - La hauteur de l'objet, en pouces.
### getDocument() {#getDocument--}
```
public final CmxDocument getDocument()
```


Récupérez le document CMX sans effort grâce à cette propriété intuitive. Idéal pour les développeurs souhaitant accéder ou modifier des images CMX, garantissant flexibilité et efficacité dans leurs applications.

**Returns:**
[CmxDocument](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxdocument) - The CMX document.
### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Récupérez sans effort la page CMX de l'image grâce à cette propriété intuitive. Idéal pour les développeurs recherchant un accès rapide aux pages individuelles des images CMX, garantissant une navigation et une gestion efficaces.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - The CMX page.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Récupérez le nombre total de pages de l'image avec cette propriété intuitive. Idéal pour les développeurs cherchant à gérer dynamiquement les images multipages, assurant une navigation efficace et une manipulation du contenu de l'image.

**Returns:**
int - le nombre de pages.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Récupérez les pages de l'image de manière fluide avec cette propriété intuitive. Idéal pour les développeurs souhaitant accéder et manipuler les pages individuelles d'images multipages, garantissant une navigation et un traitement efficaces.

**Returns:**
com.aspose.imaging.Image[] - les pages.

**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Chargez une image à partir d'un fichier CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Cet appel met en cache uniquement la page par défaut.
    image.cacheData();

    // Mettez en cache toutes les pages afin qu'aucun chargement de données supplémentaire ne soit effectué depuis le flux de données sous-jacent.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Mettez en cache les données pour éviter un chargement supplémentaire depuis la source sous-jacente [DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter) avec cette méthode pratique. Idéal pour les développeurs cherchant à optimiser les performances en préchargeant les données, assurant un accès plus rapide et un fonctionnement plus fluide dans leurs applications.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Chargez une image à partir d'un fichier CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Cet appel met en cache uniquement la page par défaut.
    image.cacheData();

    // Mettez en cache toutes les pages afin qu'aucun chargement de données supplémentaire ne soit effectué depuis le flux de données sous-jacent.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
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

