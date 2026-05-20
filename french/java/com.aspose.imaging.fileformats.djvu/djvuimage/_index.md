---
title: "DjvuImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La classe de document DjVu prend en charge le format de fichier graphique et facilite la gestion fluide des documents numérisés et des livres en intégrant texte, dessins, images et photos dans un format unique."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.djvu/djvuimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)
```
public final class DjvuImage extends RasterCachedMultipageImage
```

La classe de document DjVu prend en charge le format de fichier graphique et facilite la gestion fluide des documents numérisés et des livres, en intégrant texte, dessins, images et photos dans un format unique. En prenant en charge les opérations multipages, vous pouvez accéder efficacement aux identifiants uniques des documents, compter les pages, définir les pages actives et récupérer des pages spécifiques du document. Grâce aux fonctionnalités de redimensionnement, de rotation, de tramage, de recadrage, de transformation en niveaux de gris, de corrections gamma, d'ajustements et d'application de filtres, cette classe permet une manipulation et une amélioration précises des images DjVu pour répondre aux besoins variés des applications avec aisance et précision.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DjvuImage(InputStream stream)](#DjvuImage-java.io.InputStream-) | Commencez à travailler avec les images DjVu en initialisant une nouvelle instance de la classe [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) à l'aide d'un paramètre Stream. |
| [DjvuImage(InputStream stream, LoadOptions loadOptions)](#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Commencez à travailler avec les images DjVu de manière fluide avec ce constructeur, qui initialise une nouvelle instance de la classe [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) à l'aide d'un paramètre Stream et de paramètres LoadOptions. |
| [DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)](#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Commencez à travailler avec les images DjVu de manière fluide avec ce constructeur, qui initialise une nouvelle instance de la classe [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) à l'aide d'un paramètre Stream et de paramètres LoadOptions. |
## Champs

| Champ | Description |
| --- | --- |
| [PropertyChanged](#PropertyChanged) | Se produit lorsqu'une valeur de propriété change. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [loadDocument(InputStream stream)](#loadDocument-java.io.InputStream-) | Chargez votre document DjVu avec cette méthode. |
| [loadDocument(InputStream stream, LoadOptions loadOptions)](#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Charge le document. |
| [getIdentifier()](#getIdentifier--) | Obtient l'identifiant unique du document |
| [getPageCount()](#getPageCount--) | Récupérez le nombre total de pages de votre collection d'images DjVu avec cette propriété. |
| [getPages()](#getPages--) | Accédez aux pages individuelles de votre collection d'images DjVu avec cette propriété. |
| [getDjvuPages()](#getDjvuPages--) | Récupérez rapidement toutes les pages contenues dans votre document DjVu en utilisant cette propriété. |
| [getActivePage()](#getActivePage--) | Naviguez dans votre document DjVu en accédant ou en définissant la page actuellement active à l'aide de cette propriété. |
| [setActivePage(DjvuPage value)](#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Naviguez dans votre document DjVu en accédant ou en définissant la page actuellement active à l'aide de cette propriété. |
| [getFirstPage()](#getFirstPage--) | Accédez à la première page de votre document DjVu avec cette propriété. |
| [getLastPage()](#getLastPage--) | Récupérez la dernière page de votre document DjVu en utilisant cette propriété. |
| [getNextPage()](#getNextPage--) | Naviguez dans votre document DjVu en accédant à la page suivante avec cette propriété pratique. |
| [getPreviousPage()](#getPreviousPage--) | Déplacez-vous rapidement en arrière dans votre document DjVu lors de la visualisation ou du traitement en accédant à la page précédente avec cette propriété pratique. |
| [getFileFormat()](#getFileFormat--) | Obtenez les informations de format de fichier associées à votre fichier image DjVu. |
| [hasAlpha()](#hasAlpha--) | Déterminez rapidement si votre fichier image DjVu contient un canal alpha. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Faites pivoter l'image autour de son centre avec la méthode Rotate de la classe RasterCachedMultipageImage. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensionnez l'image en utilisant la méthode `Resize`, offrant une façon simple et efficace d'ajuster les dimensions de vos images selon vos besoins. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | La méthode `ResizeWidthProportionally` offre une solution pratique pour ajuster la largeur de votre image tout en conservant son ratio d'aspect. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | La méthode `ResizeHeightProportionally` vous permet d'ajuster la hauteur de votre image tout en préservant son ratio d'aspect. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | La méthode `RotateFlip` offre des options de manipulation polyvalentes pour votre image, vous permettant de faire pivoter, retourner ou d'effectuer les deux opérations sur la trame active de manière indépendante. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | La fonction "Dither" applique un effet de tramage à votre image, améliorant sa qualité visuelle en réduisant les bandes et en améliorant les transitions de couleur. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | "Crop" recadre votre image pour se concentrer sur des détails spécifiques ou supprimer les éléments indésirables, améliorant sa composition et son impact visuel. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Le recadrage avec décalages vous permet d'ajuster précisément la position et les dimensions de la zone recadrée au sein d'une image. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | La binarisation avec un seuil prédéfini simplifie les images complexes en représentations binaires, où les pixels sont classés comme noirs ou blancs en fonction de leur intensité comparée à une valeur de seuil spécifiée. |
| [binarizeOtsu()](#binarizeOtsu--) | La binarisation utilisant le seuillage d'Otsu est une technique qui calcule automatiquement une valeur de seuil optimale basée sur l'histogramme de l'image. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | La binarisation utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage d'image intégrale est une méthode qui calcule un seuil local pour chaque pixel en fonction d'un voisinage local. |
| [grayscale()](#grayscale--) | La transformation en niveaux de gris convertit une image en une représentation noir et blanc, où l'intensité de chaque pixel est représentée par une valeur unique allant du noir au blanc. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | La correction gamma, spécifiquement pour les canaux rouge, vert et bleu, consiste à ajuster la luminosité de chaque composant couleur séparément. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | La correction gamma est appliquée à une image avec des paramètres personnalisables pour les canaux rouge, vert et bleu, permettant un réglage précis de la balance des couleurs et de la luminosité. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajustez la `brightness` d'une image en utilisant un paramètre spécifié, offrant un contrôle sur les niveaux de luminance pour une clarté visuelle optimale. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Améliorez le contraste de [Image](../../com.aspose.imaging/image) pour améliorer la clarté visuelle et mettre en évidence les détails avec cette méthode, qui ajuste la différence de luminosité entre les zones claires et sombres. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Appliquez des filtres à une zone rectangulaire spécifiée dans l'image pour améliorer ou modifier son apparence. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensionnez l'image à la largeur et à la hauteur spécifiées tout en appliquant les paramètres supplémentaires au besoin. |
| [cacheData()](#cacheData--) | Mettez en cache les données de manière privée pour optimiser les performances et réduire le besoin de récupérer à plusieurs reprises les données depuis des sources externes. |

## Example: This example shows how to load a DJVU image from a file stream.

``` java
String dir = "c:\\temp\\";

// Charger une image DJVU à partir d'un flux de fichier.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Enregistrez chaque page en tant qu'image PNG individuelle.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Générez un nom de fichier basé sur le numéro de page.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### DjvuImage(InputStream stream) {#DjvuImage-java.io.InputStream-}
```
public DjvuImage(InputStream stream)
```


Commencez à travailler avec les images DjVu en initialisant une nouvelle instance de la classe [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) en utilisant un paramètre Stream. Idéal pour les développeurs qui souhaitent une intégration transparente du traitement d'images DjVu dans leurs projets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux. |

### DjvuImage(InputStream stream, LoadOptions loadOptions) {#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(InputStream stream, LoadOptions loadOptions)
```


Commencez à travailler avec les images DjVu de manière fluide grâce à ce constructeur, qui initialise une nouvelle instance de la classe [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) en utilisant des paramètres Stream et LoadOptions. Idéal pour les développeurs qui souhaitent un contrôle précis sur les options de chargement d'images DjVu tout en conservant simplicité et efficacité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux depuis lequel charger. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

### DjvuImage(System.IO.Stream stream, LoadOptions loadOptions) {#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Commencez à travailler avec les images DjVu de manière fluide grâce à ce constructeur, qui initialise une nouvelle instance de la classe [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) en utilisant des paramètres Stream et LoadOptions. Idéal pour les développeurs qui souhaitent un contrôle précis sur les options de chargement d'images DjVu tout en conservant simplicité et efficacité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | com.aspose.ms.System.IO.Stream | Le flux depuis lequel charger. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Se produit lorsqu'une valeur de propriété change.

### loadDocument(InputStream stream) {#loadDocument-java.io.InputStream-}
```
public static DjvuImage loadDocument(InputStream stream)
```


Chargez votre document DjVu avec cette méthode. Rationalisez votre processus en accédant rapidement et en important vos fichiers DjVu dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### loadDocument(InputStream stream, LoadOptions loadOptions) {#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static DjvuImage loadDocument(InputStream stream, LoadOptions loadOptions)
```


Charge le document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Obtient l'identifiant unique du document

**Returns:**
int - L'identifiant.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Récupérez le nombre total de pages de votre collection d'images DjVu avec cette propriété. Idéal pour évaluer rapidement l'étendue de votre document ou livre stocké au format DjVu. Améliorez l'efficacité de votre flux de travail grâce à des informations précises sur le nombre de pages.

**Returns:**
int - Le nombre de pages.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accédez aux pages individuelles de votre collection d'images DjVu avec cette propriété. Simplifiez la navigation et la manipulation de votre document ou livre stocké au format DjVu en accédant directement à chaque page. Améliorez l'efficacité de votre flux de travail grâce à une récupération de pages facile.

**Returns:**
com.aspose.imaging.Image[] - Les pages.

**Example: This example shows how to load a DJVU image from a file stream.**

``` java
String dir = "c:\\temp\\";

// Charger une image DJVU à partir d'un flux de fichier.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Enregistrez chaque page en tant qu'image PNG individuelle.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Générez un nom de fichier basé sur le numéro de page.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### getDjvuPages() {#getDjvuPages--}
```
public DjvuPage[] getDjvuPages()
```


Récupérez rapidement toutes les pages contenues dans votre document DjVu à l'aide de cette propriété. Simplifiez votre flux de traitement de documents en accédant facilement et en gérant les pages individuelles de vos fichiers DjVu. Améliorez l'efficacité et rationalisez vos tâches grâce à une récupération de pages pratique.

**Returns:**
com.aspose.imaging.fileformats.djvu.DjvuPage[] - Les pages.
### getActivePage() {#getActivePage--}
```
public DjvuPage getActivePage()
```


Naviguez dans votre document DjVu en accédant ou en définissant la page actuellement active à l'aide de cette propriété. Changez de page de manière fluide pour vous concentrer sur un contenu spécifique et améliorer votre expérience de visualisation du document.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage)

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Charger une image DJVU à partir d'un flux de fichier.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//La sortie peut ressembler à ceci :
//Le nombre total de pages : 2
//Le numéro de page actif :    1
//Le numéro de la première page :     1
//Le numéro de la dernière page :      2
//--------------------------------------------------
//Numéro de page :     1
//Taille de page :       { Width = 2481, Height = 3508}
//Format brut de la page : RgbIndexed1Bpp, canaux utilisés : 1
//--------------------------------------------------
//Numéro de page :     2
//Taille de page :       { Width = 2481, Height = 3508}
//Format brut de la page : RgbIndexed1Bpp, canaux utilisés : 1
```

### setActivePage(DjvuPage value) {#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-}
```
public void setActivePage(DjvuPage value)
```


Naviguez dans votre document DjVu en accédant ou en définissant la page actuellement active à l'aide de cette propriété. Changez de page de manière fluide pour vous concentrer sur un contenu spécifique et améliorer votre expérience de visualisation du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | La page active. |

### getFirstPage() {#getFirstPage--}
```
public DjvuPage getFirstPage()
```


Accédez à la première page de votre document DjVu avec cette propriété. Récupérez rapidement la page initiale pour commencer à visualiser ou traiter votre document efficacement.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The first page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Charger une image DJVU à partir d'un flux de fichier.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//La sortie peut ressembler à ceci :
//Le nombre total de pages : 2
//Le numéro de page actif :    1
//Le numéro de la première page :     1
//Le numéro de la dernière page :      2
//--------------------------------------------------
//Numéro de page :     1
//Taille de page :       { Width = 2481, Height = 3508}
//Format brut de la page : RgbIndexed1Bpp, canaux utilisés : 1
//--------------------------------------------------
//Numéro de page :     2
//Taille de page :       { Width = 2481, Height = 3508}
//Format brut de la page : RgbIndexed1Bpp, canaux utilisés : 1
```

### getLastPage() {#getLastPage--}
```
public DjvuPage getLastPage()
```


Récupérez la dernière page de votre document DjVu à l'aide de cette propriété. Accédez rapidement à la page finale pour la visualisation ou le traitement en toute simplicité.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The last page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Charger une image DJVU à partir d'un flux de fichier.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//La sortie peut ressembler à ceci :
//Le nombre total de pages : 2
//Le numéro de page actif :    1
//Le numéro de la première page :     1
//Le numéro de la dernière page :      2
//--------------------------------------------------
//Numéro de page :     1
//Taille de page :       { Width = 2481, Height = 3508}
//Format brut de la page : RgbIndexed1Bpp, canaux utilisés : 1
//--------------------------------------------------
//Numéro de page :     2
//Taille de page :       { Width = 2481, Height = 3508}
//Format brut de la page : RgbIndexed1Bpp, canaux utilisés : 1
```

### getNextPage() {#getNextPage--}
```
public DjvuPage getNextPage()
```


Naviguez dans votre document DjVu en accédant à la page suivante grâce à cette propriété pratique. Avancez rapidement dans vos tâches de visualisation ou de traitement du document.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The next page.
### getPreviousPage() {#getPreviousPage--}
```
public DjvuPage getPreviousPage()
```


Reculer rapidement dans vos tâches de visualisation ou de traitement du document DjVu en accédant à la page précédente grâce à cette propriété pratique. Naviguez efficacement dans votre document en toute simplicité.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The previous page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtenez les informations de format de fichier associées à votre image DjVu. Déterminez rapidement le format de votre fichier pour une intégration fluide dans votre flux de travail.

**Returns:**
long
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Déterminez rapidement si votre image DjVu contient un canal alpha. Simplifiez votre flux de travail en vérifiant la présence d'informations de transparence dans vos images.

**Returns:**
boolean - Le canal alpha est présent.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Faites pivoter l'image autour de son centre avec la méthode Rotate de la classe RasterCachedMultipageImage. Cette fonctionnalité pratique vous permet d'ajuster facilement l'orientation des images tout en conservant leur position centrale, améliorant ainsi vos capacités de manipulation d'images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens des aiguilles d'une montre. |
| resizeProportionally | boolean | si défini sur `true` vous verrez la taille de votre image modifiée selon les projections du rectangle tourné (points d'angle) ; dans le cas contraire, les dimensions restent inchangées et seul `` le contenu de l'image est tourné. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Couleur de l'arrière-plan. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensionnez l'image en utilisant la méthode \`Resize\`, offrant une manière simple et efficace d'ajuster les dimensions de vos images selon vos besoins. Cette fonctionnalité polyvalente vous permet de mettre à l'échelle facilement les images à la taille souhaitée, améliorant leur utilisabilité sur diverses plateformes et applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |


**Example: This example loads a DJVU image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


La méthode \`ResizeWidthProportionally\` offre une solution pratique pour ajuster la largeur de votre image tout en conservant son ratio d'aspect. En redimensionnant proportionnellement la largeur, vous pouvez garantir que vos images restent visuellement attrayantes et cohérentes sur différents appareils et tailles d'écran, améliorant ainsi leur polyvalence et leur utilisabilité dans divers contextes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| resizeType | int | Type de redimensionnement. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
Cet exemple charge une image DJVU et la redimensionne proportionnellement en utilisant diverses méthodes de redimensionnement. Seule la largeur est spécifiée, la hauteur est calculée automatiquement.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


La méthode \`ResizeHeightProportionally\` vous permet d'ajuster la hauteur de votre image tout en préservant son ratio d'aspect. Cela garantit que votre image conserve ses proportions, évitant les distorsions et préservant son intégrité visuelle. Que vous optimisiez des images pour des pages web, des applications mobiles ou des supports imprimés, cette méthode assure que vos images soient à leur meilleur sur différentes plateformes et appareils.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Type de redimensionnement. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
Cet exemple charge une image DJVU et la redimensionne proportionnellement en utilisant diverses méthodes de redimensionnement. Seule la hauteur est spécifiée, la largeur est calculée automatiquement.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


La méthode \`RotateFlip\` offre des options de manipulation polyvalentes pour votre image, vous permettant de faire pivoter, retourner ou d'effectuer les deux opérations sur la trame active de manière indépendante. Que vous retouchiez des photos, créiez des graphiques ou amélioriez de l'art numérique, cette méthode fournit un contrôle précis sur l'orientation et la composition de vos images, garantissant qu'elles répondent à votre vision créative avec aisance et efficacité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Le type de rotation et retournement. |


**Example: This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Faites pivoter, retournez et enregistrez dans le fichier de sortie.
    com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


La fonction \"Dither\" applique un effet de tramage à votre image, améliorant sa qualité visuelle en réduisant les bandes et en améliorant les transitions de couleur. Que vous travailliez sur de l'art numérique, de la photographie ou des projets de conception graphique, cette fonctionnalité ajoute une touche professionnelle à vos images, les rendant plus lisses et plus raffinées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | La méthode de tramage. |
| bitsCount | int | Le nombre final de bits pour le tramage. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personnalisée pour le tramage. |


**Example: The following example loads a DJVU image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Effectuer un dithering par seuil en utilisant une palette de couleurs 4 bits contenant 16 couleurs.
    // Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
    // Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Effectuer un dithering Floyd en utilisant une palette de couleurs 1 bit contenant uniquement 2 couleurs - noir et blanc.
    // Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
    // Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


\"Crop\" recadre votre image pour mettre en avant des détails spécifiques ou supprimer des éléments indésirables, améliorant ainsi sa composition et son impact visuel. Que vous ajustiez des photos pour les réseaux sociaux, créiez des bannières de site web ou conceviez des supports imprimés, cet outil vous aide à affiner vos images avec précision et clarté.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |


**Example: The following example crops a DJVU image.**
L'exemple suivant recadre une image DJVU. La zone de recadrage est spécifiée via Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Recadrez l'image. La zone de recadrage est la zone centrale rectangulaire de l'image.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            djvuImage.getWidth() / 4, djvuImage.getHeight() / 4, djvuImage.getWidth() / 2, djvuImage.getHeight() / 2);
    djvuImage.crop(area);

    // Enregistrez l'image recadrée au format PNG
    djvuImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Le recadrage avec décalages vous permet d'ajuster précisément la position et les dimensions de la zone recadrée au sein d'une image. Cette fonctionnalité est inestimable pour affiner les compositions, aligner les éléments et mettre en valeur les points focaux de vos visuels. En incorporant des décalages dans le processus de recadrage, vous pouvez obtenir une précision pixel parfaite et affiner le cadrage de vos images avec facilité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| leftShift | int | Le décalage gauche. |
| rightShift | int | Le décalage droit. |
| topShift | int | Le décalage supérieur. |
| bottomShift | int | Le décalage inférieur. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


La binarisation avec un seuil prédéfini simplifie les images complexes en représentations binaires, où les pixels sont classés comme noirs ou blancs en fonction de leur intensité comparée à une valeur de seuil spécifiée. Cette technique est couramment utilisée en traitement d'image pour améliorer la clarté, simplifier l'analyse et préparer les images pour des étapes de traitement ultérieures telles que la reconnaissance optique de caractères (OCR). En appliquant un seuil fixe, vous pouvez rapidement transformer des images en niveaux de gris en forme binaire, les rendant plus faciles à interpréter et à extraire des informations significatives.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | byte | Valeur du seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de 255 lui sera attribuée, sinon 0. |


**Example: The following example binarizes a DJVU image with the predefined threshold.**
L'exemple suivant binarise une image DJVU avec le seuil prédéfini. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarisez l'image avec une valeur de seuil de 127.
    // Si la valeur de gris correspondante d'un pixel est supérieure à 127, une valeur de 255 lui sera attribuée, sinon 0.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


La binarisation utilisant le seuillage d'Otsu est une technique qui calcule automatiquement une valeur de seuil optimale basée sur l'histogramme de l'image. Elle sépare l'image en premier plan et arrière-plan en minimisant la variance intra-classe. La méthode d'Otsu est largement utilisée pour segmenter les images en forme binaire, notamment lorsque la distribution des intensités des pixels est bimodale ou multimodale. Cette approche est bénéfique pour des tâches telles que la détection d'objets, la segmentation d'images et l'extraction de caractéristiques, où une délimitation précise entre le premier plan et l'arrière-plan est cruciale.


**Example: The following example binarizes a DJVU image with Otsu thresholding.**
L'exemple suivant binarise une image DJVU avec le seuillage d'Otsu. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarisez l'image avec le seuillage d'Otsu.
    djvuImage.binarizeOtsu();
    djvuImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


La binarisation utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage d'image intégrale est une méthode qui calcule un seuil local pour chaque pixel en fonction d'un voisinage local. Elle s'adapte aux variations d'éclairage à travers l'image, la rendant adaptée aux images avec des conditions d'éclairage inégales. En calculant le seuil à l'aide d'images intégrales, elle gère efficacement de grands voisinages, ce qui la rend applicable aux applications en temps réel. Cette technique est couramment utilisée dans le traitement de documents, l'OCR (Reconnaissance Optique de Caractères) et les tâches de segmentation d'images où une binarisation précise est essentielle pour l'analyse ultérieure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s × s pixels centrée sur ce pixel. |
| windowSize | int | La taille de la fenêtre de s × s pixels centrée sur ce pixel |


**Example: The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size.**
L'exemple suivant binarise une image DJVU avec l'algorithme de seuillage adaptatif de Bradley avec la taille de fenêtre spécifiée. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarisez l'image avec une différence de luminosité de 5. La luminosité est une différence entre un pixel et la moyenne d'une fenêtre de 10 x 10 pixels centrée sur ce pixel.
    djvuImage.binarizeBradley(5, 10);
    djvuImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


La transformation en niveaux de gris convertit une image en une représentation noir et blanc, où l'intensité de chaque pixel est représentée par une valeur unique allant du noir au blanc. Ce processus supprime les informations de couleur, produisant une image monochrome. Les images en niveaux de gris sont couramment utilisées dans des applications où la couleur est inutile ou où la simplicité est privilégiée, comme la numérisation de documents, l'impression et certains types d'analyse d'image.


**Example: The following example transforms a colored DJVU image to its grayscale representation.**
L'exemple suivant transforme une image DJVU couleur en sa représentation en niveaux de gris. Les images en niveaux de gris sont composées exclusivement de nuances de gris et ne contiennent que des informations d'intensité.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    djvuImage.grayscale();
    djvuImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


La correction gamma, spécifiquement pour les canaux rouge, vert et bleu, consiste à ajuster la luminosité de chaque composant couleur séparément. En appliquant différents coefficients gamma aux canaux RVB, vous pouvez affiner la luminosité et le contraste globaux d'une image. Cette technique assure une représentation précise des couleurs et améliore la qualité visuelle de l'image sur différents dispositifs d'affichage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gamma | float | Coefficient gamma pour les canaux rouge, vert et bleu |


**Example: The following example performs gamma-correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Définir le coefficient gamma pour les canaux rouge, vert et bleu.
    djvuImage.adjustGamma(2.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


La correction gamma est appliquée à une image avec des paramètres personnalisables pour les canaux rouge, vert et bleu, permettant un réglage précis de la balance des couleurs et de la luminosité. Cette méthode améliore la qualité de l'image en affinant la représentation des couleurs, assurant un rendu optimal sur différents dispositifs d'affichage. Ajuster les valeurs gamma pour chaque canal améliore la balance des couleurs et l'attrait visuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gammaRed | float | Coefficient gamma pour le canal rouge |
| gammaGreen | float | Coefficient gamma pour le canal vert |
| gammaBlue | float | Gamma pour le coefficient du canal bleu |


**Example: The following example performs gamma-correction of a DJVU image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Définir les coefficients gamma individuels pour les canaux rouge, vert et bleu.
    djvuImage.adjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajustez la `brightness` d'une image en utilisant un paramètre spécifié, offrant un contrôle sur les niveaux de luminance pour une clarté visuelle optimale. Cette méthode augmente ou diminue la luminosité globale de l'image, permettant des réglages fins pour obtenir les effets d'éclairage souhaités. En modulant la luminosité, les utilisateurs peuvent optimiser la visibilité de l'image et améliorer la reproduction des détails pour une expérience de visualisation améliorée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | int | Valeur de luminosité. |


**Example: The following example performs brightness correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Définissez la valeur de luminosité. Les valeurs acceptées de luminosité sont dans la plage [-255, 255].
    djvuImage.adjustBrightness(50);
    djvuImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Améliorez le contraste de [Image](../../com.aspose.imaging/image) pour améliorer la clarté visuelle et mettre en évidence les détails avec cette méthode, qui ajuste la différence de luminosité entre les zones claires et sombres. En affinant les niveaux de contraste, les utilisateurs peuvent obtenir des images plus vives et percutantes, améliorant la qualité globale de l'image et maximisant la visibilité des détails. Cet ajustement aide à faire ressortir les nuances subtiles de couleur et de texture, produisant des images plus dynamiques et visuellement attrayantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| contrast | float | Valeur de contraste (dans la plage [-100 ; 100]) |


**Example: The following example performs contrast correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Définissez la valeur de contraste. Les valeurs acceptées de contraste sont dans la plage [-100f, 100f].
    djvuImage.adjustContrast(50f);
    djvuImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Appliquez des filtres à une zone rectangulaire spécifiée au sein de l'image pour améliorer ou modifier son apparence. En ciblant des régions spécifiques, cette méthode permet des ajustements précis, tels que le flou, le renforcement ou l'application d'effets artistiques, afin d'obtenir les résultats visuels souhaités. Affiner les filtres sur les zones sélectionnées permet aux utilisateurs de personnaliser l'esthétique de l'image, d'améliorer la clarté et de créer des effets artistiques adaptés à leurs préférences.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Les options. |


**Example: The following example applies various types of filters to a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Appliquez un filtre médian avec une taille de rectangle de 5 à l'ensemble de l'image.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    djvuImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Appliquez un filtre de lissage bilatéral avec une taille de noyau de 5 à l'ensemble de l'image.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    djvuImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Appliquez un filtre de flou gaussien avec un rayon de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Appliquez un filtre Gauss-Wiener avec un rayon de 5 et une valeur de lissage de 4,0 à l'ensemble de l'image.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Appliquez un filtre wiener de mouvement avec une longueur de 5, une valeur de lissage de 4,0 et un angle de 90,0 degrés à l'ensemble de l'image.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    djvuImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Appliquez un filtre d'accentuation avec une taille de noyau de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensionnez l'image à la largeur et à la hauteur spécifiées tout en appliquant les paramètres supplémentaires si nécessaire. Cette méthode permet aux utilisateurs d'ajuster les dimensions de l'image tout en conservant les attributs souhaités tels que le rapport d'aspect, la qualité de l'image et les paramètres de compression. En offrant une flexibilité dans les options de redimensionnement, les utilisateurs peuvent adapter l'image aux exigences spécifiques et optimiser son apparence pour diverses applications et plateformes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Les paramètres de redimensionnement. |


**Example: This example loads a DJVU image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// L'algorithme adaptatif basé sur une fonction rationnelle pondérée et mélangée et l'interpolation lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Le petit filtre rectangulaire
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Le nombre de couleurs dans la palette.
resizeSettings.setEntriesCount(256);

// La quantification des couleurs n'est pas utilisée
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// La méthode euclidienne
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Réduisez de 2 fois en utilisant le rééchantillonnage adaptatif.
    djvuImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Enregistrer au format PNG
    djvuImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Mettez en cache les données de manière privée pour optimiser les performances et réduire le besoin de récupérer à plusieurs reprises les données depuis des sources externes. Cette approche aide également à conserver les ressources, notamment dans les scénarios où l'accès aux données est fréquent ou les ressources sont limitées.


**Example: The following example shows how to cache all pages of a DJVU image.**

``` java
String dir = "c:\\temp\\";

// Chargez une image à partir d'un fichier DJVU.
com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Cet appel met en cache toutes les pages afin qu'aucun chargement de données supplémentaire ne soit effectué à partir du flux de données sous-jacent.
    image.cacheData();

    // Ou vous pouvez mettre en cache les pages individuellement.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

