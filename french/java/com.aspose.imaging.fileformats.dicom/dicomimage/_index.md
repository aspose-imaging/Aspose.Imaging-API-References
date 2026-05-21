---
title: "DicomImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Cette classe implémente le support du format d'image raster DICOM (Digital Imaging and Communications in Medicine) et offre une solution complète pour le traitement des images DICOM avec précision et flexibilité."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.fileformats.dicom/dicomimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class DicomImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Cette classe implémente le support du format d'image raster DICOM (Digital Imaging and Communications in Medicine) et offre une solution complète pour le traitement des images DICOM avec précision et flexibilité. Vous pouvez manipuler les pages d'image de manière fluide, y compris les opérations d'obtention, d'ajout ou de suppression de pages, et contrôler les pages par défaut et actives. Avec des capacités de gestion des canaux alpha, d'intégration des métadonnées XMP, de redimensionnement, de rotation, de recadrage, de binarisation, d'ajustement, d'application de filtres et de conversion vers d'autres formats raster. Cette API permet aux développeurs de gérer efficacement les images DICOM tout en répondant à des exigences d'application diverses dans les contextes d'imagerie médicale.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DicomImage(DicomOptions dicomOptions, int width, int height)](#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-) | Initialisez facilement une nouvelle instance de la classe DicomImage avec ce constructeur, en utilisant les paramètres dicomOptions. |
| [DicomImage(InputStream stream, LoadOptions loadOptions)](#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Initialisez une nouvelle instance de la classe DicomImage en douceur en utilisant les paramètres stream et loadOptions dans ce constructeur. |
| [DicomImage(InputStream stream)](#DicomImage-java.io.InputStream-) | Créez une nouvelle instance de la classe DicomImage en utilisant un paramètre stream dans ce constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPageCount()](#getPageCount--) | Récupérez le nombre total de pages de l'image grâce à cette propriété intuitive. |
| [getPages()](#getPages--) | Accédez aux pages de l'image avec cette propriété intuitive. |
| [getFileInfo()](#getFileInfo--) | Récupérez facilement les informations d'en-tête précieuses du fichier DICOM avec cette propriété intuitive. |
| [getDicomPages()](#getDicomPages--) | Accédez aux pages de l'image avec cette propriété intuitive. |
| [getActivePage()](#getActivePage--) | Accédez à la page active de l'image avec cette propriété intuitive. |
| [setActivePage(DicomPage value)](#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-) | Gérez la page active de l'image avec cette propriété intuitive. |
| [getActivePageIndex()](#getActivePageIndex--) | Récupérez facilement l'index de la page active avec cette propriété intuitive. |
| [getFileFormat()](#getFileFormat--) | Récupérez facilement la valeur du format de fichier avec cette propriété intuitive. |
| [hasAlpha()](#hasAlpha--) | Récupérez facilement si l'image possède un canal alpha avec cette propriété intuitive. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Élargissez votre collection d'images en ajoutant une nouvelle page avec cette méthode intuitive. |
| [saveAll(String filePath, ImageOptionsBase options)](#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | Conservez les données de l'objet en les enregistrant à l'emplacement du fichier désigné (indexeur + nom de fichier) avec le format de fichier et les options spécifiés. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Ajustez la résolution de ce [RasterImage](../../com.aspose.imaging/rasterimage) avec précision en utilisant cette méthode simple. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Redimensionnez l'image tout en conservant son ratio d'aspect avec cette méthode pratique. |
| [addPage()](#addPage--) | Ajoutez une nouvelle page à la fin de la liste de pages de l'image avec cette méthode simple. |
| [insertPage(int pageIndex)](#insertPage-int-) | Insérez une nouvelle page dans la liste de pages de l'image à un index spécifié avec cette méthode intuitive. |
| [removePage(int pageIndex)](#removePage-int-) | Supprimez la page à l'index spécifié de la liste de pages avec cette méthode pratique. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Faites pivoter l'image autour de son centre avec cette méthode pratique. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ajustez la taille de l'image avec cette méthode simple. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ajustez la largeur de l'image tout en conservant son ratio d'aspect avec cette méthode pratique. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ajustez la hauteur de l'image tout en conservant son ratio d'aspect avec cette méthode conviviale. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Manipulez facilement le cadre actif en le faisant pivoter, le retournant, ou en effectuant les deux actions simultanément avec cette méthode simple. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Améliorez l'image actuelle en appliquant des effets de tramage avec cette méthode simple. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadrez l'image pour supprimer les zones indésirables et vous concentrer sur le contenu essentiel avec cette méthode simple. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Ajustez la zone de recadrage de l'image en appliquant des déplacements avec cette méthode polyvalente. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Convertissez facilement l'image en format binaire en utilisant un seuil prédéfini avec cette méthode simple. |
| [binarizeOtsu()](#binarizeOtsu--) | Appliquez le seuillage d'Otsu pour binariser l'image, en déterminant automatiquement la valeur de seuil optimale basée sur l'histogramme de l'image. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisez les images avec l'algorithme de seuillage adaptatif de Bradley, en exploitant le seuillage par image intégrale pour améliorer les performances. |
| [grayscale()](#grayscale--) | Transformez facilement les images en leur représentation en niveaux de gris, simplifiant l'analyse visuelle et les tâches de traitement. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Améliorez la qualité de l'image et ajustez‑la avec la correction gamma, une technique puissante pour affiner l'apparence visuelle. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Obtenez des ajustements de couleur précis en appliquant la correction gamma indépendamment aux composantes rouge, verte et bleue d'une image. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Améliorez la luminance de l'image avec le réglage de `brightness`, une méthode paramétrée qui permet aux développeurs d'ajuster finement la luminosité des images. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Améliorez le contraste de [Image](../../com.aspose.imaging/image) avec cette méthode conviviale, qui ajuste la disparité entre les zones claires et sombres. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Améliorez sans effort des zones spécifiques de votre image en appliquant des filtres à des rectangles désignés. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ajustez la taille de votre image avec cette méthode de redimensionnement simple. |
| [cacheData()](#cacheData--) | Cette méthode met en cache les données de manière efficace, optimisant les performances et assurant un accès rapide lorsque nécessaire. |

## Example: This example demonstrates the loading and exporting of dicom file.

``` java

String dir = "c:\\temp\\";

// Charger une image
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load("sample.dicom");
try {
    image.adjustBrightness(50);
    image.save(dir + "sample.dicom.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Dessinez quelque chose en utilisant des graphiques vectoriels.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Enregistrez les pixels de l'image dessinée. Ils se trouvent maintenant sur la première page de l'image Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Ajoutez quelques pages après, les rendant plus sombres.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Ajoutez quelques pages avant la page principale, les rendant plus claires.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Enregistrez l'image multipage créée dans le fichier de sortie.
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomImage(DicomOptions dicomOptions, int width, int height) {#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-}
```
public DicomImage(DicomOptions dicomOptions, int width, int height)
```


Initialisez une nouvelle instance de la classe DicomImage sans effort avec ce constructeur, en utilisant les paramètres dicomOptions. Parfait pour les développeurs souhaitant plonger rapidement et efficacement dans les objets [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) dans leurs projets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dicomOptions | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) | Les options dicom (ignorées pour l'instant). |
| width | int | La largeur. |
| height | int | La hauteur. |

### DicomImage(InputStream stream, LoadOptions loadOptions) {#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DicomImage(InputStream stream, LoadOptions loadOptions)
```


Initiez une nouvelle instance de la classe DicomImage en douceur en utilisant un flux et les paramètres loadOptions dans ce constructeur. Idéal pour les développeurs désireux de commencer à travailler avec les objets [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) rapidement et efficacement dans leurs projets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

### DicomImage(InputStream stream) {#DicomImage-java.io.InputStream-}
```
public DicomImage(InputStream stream)
```


Créez une nouvelle instance de la classe DicomImage en utilisant un paramètre de flux dans ce constructeur. Parfait pour les développeurs recherchant une façon simplifiée d'initialiser les objets [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) à partir de flux de données existants dans leurs projets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Récupérez le nombre total de pages de l'image avec cette propriété intuitive. Idéal pour les développeurs cherchant un accès rapide au nombre de pages d'une image, assurant une navigation et une gestion efficaces.

**Returns:**
int - le nombre de pages.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accédez aux pages de l'image avec cette propriété intuitive. Idéal pour les développeurs souhaitant interagir avec les pages individuelles de l'image, garantissant une navigation et une manipulation fluides.

**Returns:**
com.aspose.imaging.Image[] - les pages.
### getFileInfo() {#getFileInfo--}
```
public DicomImageInfo getFileInfo()
```


Récupérez facilement les informations d'en-tête précieuses du fichier DICOM avec cette propriété intuitive. Idéal pour les développeurs cherchant un accès rapide aux détails essentiels encapsulés dans le fichier DICOM, assurant une extraction et une analyse de données efficaces.

**Returns:**
[DicomImageInfo](../../com.aspose.imaging.fileformats.dicom/dicomimageinfo) - a value, which contains info header the DICOM file
### getDicomPages() {#getDicomPages--}
```
public DicomPage[] getDicomPages()
```


Accédez aux pages de l'image avec cette propriété intuitive. Idéal pour les développeurs souhaitant interagir avec les pages individuelles de l'image, garantissant une navigation et une manipulation fluides.

**Returns:**
com.aspose.imaging.fileformats.dicom.DicomPage[] - les pages.
### getActivePage() {#getActivePage--}
```
public DicomPage getActivePage()
```


Accédez à la page active de l'image avec cette propriété intuitive. Idéal pour les développeurs souhaitant basculer dynamiquement entre les pages d'images multipages, assurant une navigation et un traitement efficaces.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - the active page.
### setActivePage(DicomPage value) {#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-}
```
public void setActivePage(DicomPage value)
```


Gérez la page active de l'image avec cette propriété intuitive. Idéal pour les développeurs souhaitant basculer dynamiquement entre les pages d'images multipages, assurant une navigation et un traitement efficaces.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) | la page active. |

### getActivePageIndex() {#getActivePageIndex--}
```
public int getActivePageIndex()
```


Récupérez l'index de la page active sans effort avec cette propriété intuitive. Idéal pour les développeurs cherchant un accès rapide à l'index de la page courante dans les images multipages, assurant une navigation et un traitement efficaces.

**Returns:**
int - l'index de la page active.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupérez la valeur du format de fichier sans effort avec cette propriété intuitive. Idéal pour les développeurs cherchant un accès rapide au format du fichier image, assurant une gestion et un traitement efficaces en fonction du type de fichier.

**Returns:**
long - une valeur du format de fichier [FileFormat](../../com.aspose.imaging/fileformat).
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Récupérez facilement si l'image possède un canal alpha grâce à cette propriété intuitive. Idéal pour les développeurs souhaitant déterminer si l'image contient des informations de transparence, garantissant une gestion précise des données du canal alpha dans les tâches de traitement d'images.

**Returns:**
boolean - vrai si l'image possède un canal alpha.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Étendez votre collection d'images en ajoutant une nouvelle page avec cette méthode intuitive. Idéal pour les développeurs souhaitant ajouter dynamiquement des pages à des images multipages, assurant une expansion fluide et une organisation du contenu image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La page à ajouter. |

### saveAll(String filePath, ImageOptionsBase options) {#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void saveAll(String filePath, ImageOptionsBase options)
```


Conservez les données de l'objet en les enregistrant à l'emplacement du fichier désigné (indexeur + nom de fichier) avec le format de fichier et les options spécifiés. Idéal pour les développeurs souhaitant stocker en toute sécurité des données dans divers formats tout en conservant flexibilité et contrôle sur les paramètres d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Les options. |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Ajustez la résolution de ce [RasterImage](../../com.aspose.imaging/rasterimage) avec précision en utilisant cette méthode simple. Idéal pour les développeurs cherchant à adapter la résolution de l'image à des exigences spécifiques, garantissant une qualité d'affichage optimale et une gestion de la taille du fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dpiX | double | La résolution horizontale, en points par pouce, du [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | La résolution verticale, en points par pouce, du [RasterImage](../../com.aspose.imaging/rasterimage). |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Redimensionnez l'image tout en conservant son ratio d'aspect avec cette méthode pratique. Idéal pour les développeurs souhaitant ajuster les dimensions de l'image proportionnellement, assurant la cohérence et préservant les proportions du contenu original. Le redimensionnement proportionnel redimensionnera chaque trame selon le rapport `newWidth`/width et `newHeight`/height.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |

### addPage() {#addPage--}
```
public DicomPage addPage()
```


Ajoutez une nouvelle page à la fin de la liste des pages de l'image avec cette méthode simple. Idéal pour les développeurs souhaitant étendre dynamiquement les images multipages, assurant une intégration fluide et une organisation du contenu image.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).
### insertPage(int pageIndex) {#insertPage-int-}
```
public DicomPage insertPage(int pageIndex)
```


Insérez une nouvelle page dans la liste des pages de l'image à un indice spécifié avec cette méthode intuitive. Idéal pour les développeurs recherchant un contrôle précis sur l'agencement des pages dans les images multipages, assurant une organisation fluide et une personnalisation du contenu image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageIndex | int | Indice de la page. |

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).

**Example: Create a multi-page Dicom image.**

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Dessinez quelque chose en utilisant des graphiques vectoriels.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Enregistrez les pixels de l'image dessinée. Ils se trouvent maintenant sur la première page de l'image Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Ajoutez quelques pages après, les rendant plus sombres.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Ajoutez quelques pages avant la page principale, les rendant plus claires.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Enregistrez l'image multipage créée dans le fichier de sortie.
        image.save("MultiPage.dcm");
    }
}
```

### removePage(int pageIndex) {#removePage-int-}
```
public void removePage(int pageIndex)
```


Supprimez la page à l'indice spécifié de la liste des pages avec cette méthode pratique. Idéal pour les développeurs recherchant un contrôle précis sur la gestion des images multipages, assurant une organisation fluide et une personnalisation du contenu image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageIndex | int | Indice de la page. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Faites pivoter l'image autour de son centre avec cette méthode pratique. Idéal pour les développeurs souhaitant ajuster l'orientation de l'image de manière dynamique, garantissant une présentation optimale et un alignement dans leurs applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |
| resizeProportionally | boolean | si défini sur `true` vous verrez la taille de votre image modifiée selon les projections du rectangle tourné (points d'angle) ; dans le cas contraire, les dimensions restent inchangées et seul `` le contenu de l'image est tourné. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Couleur de l'arrière-plan. |


**Example: This example shows how to rotate all pages of a DICOM image and save them all to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Chargez une image DICOM à partir d'un flux de fichier.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "multiframe.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = new com.aspose.imaging.fileformats.dicom.DicomImage(stream);
    try {
        // Faites pivoter l'image autour du centre de 60 degrés dans le sens horaire.
        // Utilisez le gris comme couleur d'arrière-plan.
        dicomImage.rotate(60, true, com.aspose.imaging.Color.getGray());

        com.aspose.imaging.imageoptions.TiffOptions createOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Notez que si l'image est colorée, elle sera automatiquement convertie au format niveaux de gris selon les options ci-dessous
        createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
        createOptions.setBitsPerSample(new int[]{8});

        // Créez un tableau de trames TIFF.
        // Le nombre de trames est égal au nombre de pages DJVU.
        com.aspose.imaging.fileformats.dicom.DicomPage[] pages = dicomImage.getDicomPages();
        com.aspose.imaging.fileformats.tiff.TiffFrame[] tiffFrames = new com.aspose.imaging.fileformats.tiff.TiffFrame[pages.length];

        // Enregistrez chaque page comme une trame TIFF individuelle.
        for (com.aspose.imaging.fileformats.dicom.DicomPage dicomPage : pages) {
            // Créez une trame TIFF basée sur la page DICOM.
            tiffFrames[dicomPage.getIndex()] = new com.aspose.imaging.fileformats.tiff.TiffFrame(dicomPage, createOptions);
        }

        // Composez une image TIFF à partir des trames.
        com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(tiffFrames);
        try {
            // Enregistrer dans un fichier.
            tiffImage.save(dir + "multiframe.tif");
        } finally {
            tiffImage.dispose();
        }
    } finally {
        dicomImage.dispose();
    }
} finally {
    stream.close();
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ajustez la taille de l'image avec cette méthode simple. Idéal pour les développeurs cherchant à redimensionner dynamiquement les images, garantissant qu'elles s'intègrent parfaitement dans divers contextes et mises en page au sein de leurs applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |


**Example: This example loads a DICOM image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrer au format PNG avec les options par défaut.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


Ajustez la largeur de l'image tout en conservant son ratio d'aspect avec cette méthode pratique. Idéal pour les développeurs souhaitant redimensionner les images proportionnellement, assurant des résultats cohérents et visuellement attrayants dans différents environnements d'affichage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| resizeType | int | Type de redimensionnement. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
Cet exemple charge une image DICOM et la redimensionne proportionnellement en utilisant diverses méthodes de redimensionnement. Seule la largeur est spécifiée, la hauteur est calculée automatiquement.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


Ajustez la hauteur de l'image tout en conservant son ratio d'aspect avec cette méthode conviviale. Idéal pour les développeurs qui souhaitent redimensionner dynamiquement les images tout en préservant leurs proportions, garantissant un affichage optimal et une utilisation efficace dans leurs applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Type de redimensionnement. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
Cet exemple charge une image DICOM et la redimensionne proportionnellement en utilisant diverses méthodes de redimensionnement. Seule la hauteur est spécifiée, la largeur est calculée automatiquement.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Réduire de 2 fois en utilisant le rééchantillonnage au plus proche voisin.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Agrandir de 2 fois en utilisant le rééchantillonnage bilinéaire.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Enregistrez au format PNG avec les options par défaut.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


Manipulez facilement la trame active en la faisant pivoter, la retournant, ou en effectuant les deux actions simultanément avec cette méthode simple. Idéal pour les développeurs qui doivent ajuster dynamiquement l'orientation de trames spécifiques au sein de leurs séquences d'images, garantissant une présentation et un alignement optimaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Le type de retournement rotatif. |


**Example: This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

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
    com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


Améliorez l'image actuelle en appliquant des effets de tramage avec cette méthode simple. Idéal pour les développeurs qui souhaitent ajouter de la texture et de la profondeur aux images, améliorant leur qualité visuelle et leur attrait global.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | La méthode de tramage. |
| bitsCount | int | Le nombre final de bits pour le tramage. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personnalisée pour le tramage. |


**Example: The following example loads a DICOM image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Effectuer un dithering par seuil en utilisant une palette de couleurs 4 bits contenant 16 couleurs.
    // Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
    // Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Effectuer un dithering Floyd en utilisant une palette de couleurs 1 bit contenant uniquement 2 couleurs - noir et blanc.
    // Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
    // Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recadrez l'image pour supprimer les zones indésirables et vous concentrer sur le contenu essentiel avec cette méthode simple. Idéal pour les développeurs qui souhaitent personnaliser la composition visuelle des images, garantissant qu'elles transmettent le message souhaité de manière efficace.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |


**Example: The following example crops a DICOM image.**
L'exemple suivant recadre une image DICOM. La zone de recadrage est spécifiée via Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Recadrez l'image. La zone de recadrage est la zone centrale rectangulaire de l'image.
    com.aspose.imaging.Rectangle area =
            new com.aspose.imaging.Rectangle(
                    dicomImage.getWidth() / 4, dicomImage.getHeight() / 4, dicomImage.getWidth() / 2, dicomImage.getHeight() / 2);
    dicomImage.crop(area);

    // Enregistrez l'image recadrée au format PNG
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Ajustez la zone de recadrage de l'image en appliquant des déplacements avec cette méthode polyvalente. Idéal pour les développeurs qui ont besoin d'un contrôle précis du processus de recadrage, garantissant que les détails importants sont conservés tout en éliminant les éléments superflus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| leftShift | int | Le décalage gauche. |
| rightShift | int | Le décalage droit. |
| topShift | int | Le décalage supérieur. |
| bottomShift | int | Le décalage inférieur. |


**Example: The following example crops a DICOM image.**
L'exemple suivant recadre une image DICOM. La zone de recadrage est spécifiée via Left, Top, Right, Bottom margins.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Recadrez à nouveau. Définissez une marge de 10 % de la taille de l'image.
    int horizontalMargin = dicomImage.getWidth() / 10;
    int verticalMargin = dicomImage.getHeight() / 10;
    dicomImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Enregistrez l'image recadrée au format PNG.
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Convertissez facilement l'image en format binaire en utilisant un seuil prédéfini avec cette méthode simple. Idéal pour les développeurs qui souhaitent simplifier les tâches de traitement d'image en segmentant l'image en composants premier plan et arrière-plan selon des niveaux d'intensité spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | byte | Valeur du seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de 255 lui sera attribuée, sinon 0. |


**Example: The following example binarizes a DICOM image with the predefined threshold.**
L'exemple suivant binarise une image DICOM avec le seuil prédéfini. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binarisez l'image avec une valeur de seuil de 127.
    // Si la valeur de gris correspondante d'un pixel est supérieure à 127, une valeur de 255 lui sera attribuée, sinon 0.
    dicomImage.binarizeFixed((byte) 127);
    dicomImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Appliquez le seuillage d'Otsu pour binariser l'image, déterminant automatiquement la valeur de seuil optimale basée sur l'histogramme de l'image. Idéal pour les développeurs qui recherchent une méthode fiable pour segmenter les images en régions premier plan et arrière-plan avec une intervention manuelle minimale.


**Example: The following example binarizes a DICOM image with Otsu thresholding.**
L'exemple suivant binarise une image DICOM avec le seuillage d'Otsu. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binarisez l'image avec le seuillage d'Otsu.
    dicomImage.binarizeOtsu();
    dicomImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarisez les images avec l'algorithme de seuillage adaptatif de Bradley, en exploitant le seuillage d'image intégrale pour améliorer les performances. Idéal pour les développeurs qui souhaitent segmenter automatiquement les images en fonction des variations locales de luminosité, garantissant une détection et une extraction d'objets précises dans des conditions d'éclairage variables.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s × s pixels centrée sur ce pixel. |
| windowSize | int | La taille de la fenêtre de s × s pixels centrée sur ce pixel |


**Example: The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size.**
L'exemple suivant binarise une image DICOM avec l'algorithme de seuillage adaptatif de Bradley avec la taille de fenêtre spécifiée. Les images binarisées ne contiennent que 2 couleurs - noir et blanc.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Binarisez l'image avec une différence de luminosité de 5. La luminosité est une différence entre un pixel et la moyenne d'une fenêtre de 10 x 10 pixels centrée sur ce pixel.
    dicomImage.binarizeBradley(5, 10);
    dicomImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformez facilement les images en leur représentation en niveaux de gris, simplifiant l'analyse visuelle et les tâches de traitement. Idéal pour les développeurs qui souhaitent améliorer la clarté des images, réduire la complexité et faciliter des algorithmes efficaces basés sur les niveaux de gris pour diverses applications.


**Example: The following example transforms a colored DICOM image to its grayscale representation.**
L'exemple suivant transforme une image DICOM en couleur en sa représentation en niveaux de gris. Les images en niveaux de gris sont composées exclusivement de nuances de gris et ne contiennent que des informations d'intensité.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    dicomImage.grayscale();
    dicomImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Améliorez la qualité de l'image et ajustez-la avec la correction gamma, une technique puissante pour affiner l'apparence visuelle. Idéal pour les développeurs qui souhaitent optimiser la présentation des images, ajuster la balance des couleurs et garantir un rendu cohérent sur différents appareils et environnements.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gamma | float | Coefficient gamma pour les canaux rouge, vert et bleu |


**Example: The following example performs gamma-correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Définir le coefficient gamma pour les canaux rouge, vert et bleu.
    dicomImage.adjustGamma(2.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Obtenez des ajustements de couleur précis en appliquant la correction gamma indépendamment aux composants rouge, vert et bleu d'une image. Cette méthode assure une balance des couleurs exacte et un rendu visuel optimal, répondant aux besoins des développeurs qui recherchent un contrôle granulaire sur le rendu et la précision des couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gammaRed | float | Coefficient gamma pour le canal rouge |
| gammaGreen | float | Coefficient gamma pour le canal vert |
| gammaBlue | float | Gamma pour le coefficient du canal bleu |


**Example: The following example performs gamma-correction of a DICOM image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Définir les coefficients gamma individuels pour les canaux rouge, vert et bleu.
    dicomImage.adjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Améliorez la luminance de l'image avec le réglage de `brightness`, une méthode paramétrée qui permet aux développeurs d'ajuster finement la luminosité des images. Cette fonction conviviale permet aux développeurs de manipuler sans effort la luminosité de l'image, offrant flexibilité et contrôle sur l'esthétique visuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | int | Valeur de luminosité. |


**Example: The following example performs brightness correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Définissez la valeur de luminosité. Les valeurs acceptées de luminosité sont dans la plage [-255, 255].
    dicomImage.adjustBrightness(50);
    dicomImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Améliorez le contraste de [Image](../../com.aspose.imaging/image) avec cette méthode conviviale, qui ajuste la différence entre les zones claires et sombres. Améliorez la clarté et la définition visuelles sans effort, offrant aux développeurs un contrôle intuitif du contraste de l'image pour un rendu optimal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| contrast | float | Valeur de contraste (dans la plage [-100 ; 100]) |


**Example: The following example performs contrast correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Définissez la valeur de contraste. Les valeurs acceptées de contraste sont dans la plage [-100f, 100f].
    dicomImage.adjustContrast(50f);
    dicomImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Améliorez sans effort des zones spécifiques de votre image en appliquant des filtres à des rectangles désignés. Cette méthode offre aux développeurs un contrôle précis sur la manipulation d'image, permettant des ajustements ciblés pour obtenir les effets visuels souhaités facilement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Les options. |


**Example: The following example applies various types of filters to a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Appliquez un filtre médian avec une taille de rectangle de 5 à l'ensemble de l'image.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    dicomImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Appliquez un filtre de lissage bilatéral avec une taille de noyau de 5 à l'ensemble de l'image.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    dicomImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Appliquez un filtre de flou gaussien avec un rayon de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Appliquez un filtre Gauss-Wiener avec un rayon de 5 et une valeur de lissage de 4,0 à l'ensemble de l'image.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Appliquez un filtre wiener de mouvement avec une longueur de 5, une valeur de lissage de 4,0 et un angle de 90,0 degrés à l'ensemble de l'image.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    dicomImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Appliquez un filtre d'accentuation avec une taille de noyau de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ajustez la taille de votre image avec cette méthode de redimensionnement simple. Que vous ayez besoin de réduire ou d'agrandir votre image, cette fonction garantit que vos besoins de redimensionnement sont satisfaits de manière efficace et précise, ce qui en fait le choix idéal pour les développeurs recherchant des ajustements de taille d'image rapides et faciles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Les paramètres de redimensionnement. |


**Example: This example loads a DICOM image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Réduisez de 2 fois en utilisant le rééchantillonnage adaptatif.
    dicomImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Enregistrer au format PNG
    dicomImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Cette méthode met en cache les données de manière efficace, optimisant les performances et assurant un accès rapide lorsque nécessaire. Idéal pour les développeurs qui souhaitent améliorer la vitesse et l'efficacité de leurs applications en gérant intelligemment les ressources de données.


**Example: The following example shows how to cache all pages of a DICOM image.**

``` java
String dir = "c:\\temp\\";

// Chargez une image à partir d'un fichier DICOM.
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Cet appel met en cache toutes les pages afin qu'aucun chargement de données supplémentaire ne soit effectué à partir du flux de données sous-jacent.
    image.cacheData();

    // Ou vous pouvez mettre en cache les pages individuellement.
    for (com.aspose.imaging.fileformats.dicom.DicomPage page : image.getDicomPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

