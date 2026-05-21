---
title: "JpegOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Créez facilement des images JPEG de haute qualité avec notre API offrant des niveaux de compression réglables pour optimiser la taille de stockage sans compromettre la qualité de l'image."
type: docs
weight: 26
url: /fr/java/com.aspose.imaging.imageoptions/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public class JpegOptions extends ImageOptionsBase implements IHasJpegExifData
```

Créez facilement des images JPEG de haute qualité avec notre API, offrant des niveaux de compression réglables pour optimiser la taille de stockage sans compromettre la qualité de l'image. Profitez de la prise en charge de divers types de compression, du codage quasi sans perte, des profils de couleur RVB et CMJN, ainsi que des données d'image EXIF, JFIF et des conteneurs XMP, garantissant des options polyvalentes et personnalisables pour vos besoins de création d'images.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Initialise une nouvelle instance de la classe `JpegOptions`. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-) | Initialise une nouvelle instance de la classe `JpegOptions`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Obtient la limite d'allocation mémoire par défaut. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Définit la limite d'allocation mémoire par défaut. |
| [getJfif()](#getJfif--) | Obtient le jfif. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Définit le jfif. |
| [getComment()](#getComment--) | Obtient le commentaire du fichier jpeg. |
| [setComment(String value)](#setComment-java.lang.String-) | Définit le commentaire du fichier jpeg. |
| [getExifData()](#getExifData--) | Obtient le conteneur de données Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Définit les données Exif. |
| [getJpegExifData()](#getJpegExifData--) | Obtenir le conteneur de données Exif. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Obtenir ou définir le conteneur de données exif |
| [getCompressionType()](#getCompressionType--) | Obtient le type de compression. |
| [setCompressionType(int value)](#setCompressionType-int-) | Définit le type de compression. |
| [getColorType()](#getColorType--) | Obtient le type de couleur pour l'image jpeg. |
| [setColorType(int value)](#setColorType-int-) | Définit le type de couleur pour l'image jpeg. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Obtient les bits par canal pour l'image jpeg sans perte. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Définit les bits par canal pour l'image jpeg sans perte. |
| [getQuality()](#getQuality--) | Obtient la qualité de l'image. |
| [setQuality(int value)](#setQuality-int-) | Définit la qualité de l'image. |
| [getScaledQuality()](#getScaledQuality--) | La qualité mise à l'échelle. |
| [getRdOptSettings()](#getRdOptSettings--) | Obtient les paramètres de l'optimiseur RD. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-) | Définit les paramètres de l'optimiseur RD. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Le profil couleur RGB de destination pour les images jpeg CMYK. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | Le profil couleur RGB de destination pour les images jpeg CMYK. |
| [getCmykColorProfile()](#getCmykColorProfile--) | Le profil couleur CMYK de destination pour les images jpeg CMYK. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | Le profil couleur CMYK de destination pour les images jpeg CMYK. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Obtient la limite de différence JPEG-LS pour le codage quasi-sans perte (paramètre NEAR de la spécification JPEG-LS). |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Définit la limite de différence JPEG-LS pour le codage quasi-sans perte (paramètre NEAR de la spécification JPEG-LS). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Obtient le mode d'entrelacement JPEG-LS. |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Définit le mode d'entrelacement JPEG-LS. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Obtient les paramètres prédéfinis JPEG-LS. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-) | Définit les paramètres prédéfinis du JPEG-LS. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Obtient les sous‑échantillonnages horizontaux pour chaque composant. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Définit les sous‑échantillonnages horizontaux pour chaque composant. |
| [getVerticalSampling()](#getVerticalSampling--) | Obtient les sous‑échantillonnages verticaux pour chaque composant. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Définit les sous‑échantillonnages verticaux pour chaque composant. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Obtient le mode d'arrondi d'échantillon pour adapter une valeur 8 bits à une valeur n bits. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Définit le mode d'arrondi d'échantillon pour adapter une valeur 8 bits à une valeur n bits. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Obtient une valeur indiquant si les composants rouge, vert et bleu doivent être mélangés avec une couleur d'arrière‑plan, si le canal alpha est présent. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Définit une valeur indiquant si les composants rouge, vert et bleu doivent être mélangés avec une couleur d'arrière‑plan, si le canal alpha est présent. |
| [getResolutionUnit()](#getResolutionUnit--) | Obtient l'unité de résolution. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Définit l'unité de résolution. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Cet exemple montre l'utilisation de différentes classes du namespace SaveOptions à des fins d'exportation. Une image de type Gif est chargée dans une instance de Image, puis exportée vers plusieurs formats.
``` java
String dir = "c:\\temp\\";

//Chargez une image existante (de type Gif) dans une instance de la classe Image.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Exportez au format de fichier BMP en utilisant les options par défaut.
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Exportez au format de fichier JPEG en utilisant les options par défaut.
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Exportez au format de fichier PNG en utilisant les options par défaut.
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Exportez au format de fichier TIFF en utilisant les options par défaut.
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to JPEG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.jpeg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.JpegOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportez uniquement les deux premières pages. En fait, seule une page sera rasterisée car le JPEG n'est pas un format multipage.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Initialise une nouvelle instance de la classe `JpegOptions`.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Initialise une nouvelle instance de la classe `JpegOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | Les options JPEG. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Obtient la limite d'allocation mémoire par défaut.

**Returns:**
int - La limite d'allocation mémoire par défaut.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Définit la limite d'allocation mémoire par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La limite d'allocation mémoire par défaut. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Obtient le jfif.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Définit le jfif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getComment() {#getComment--}
```
public String getComment()
```


Obtient le commentaire du fichier jpeg.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Définit le commentaire du fichier jpeg.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Obtient le conteneur de données Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data container.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public final void setExifData(ExifData value)
```


Définit les données Exif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Données Exif. |

### getJpegExifData() {#getJpegExifData--}
```
public final JpegExifData getJpegExifData()
```


Obtenir le conteneur de données Exif.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data container.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Obtenir ou définir le conteneur de données exif

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Obtient le type de compression.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Définit le type de compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Créez une image JPEG de 100 x 100 px.
// Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Le nombre de bits par canal est de 8, 8, 8 pour les composants Y, Cr, Cb respectivement.
createOptions.setBitsPerChannel((byte) 8);

// Définissez le type de compression progressive.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Définissez la qualité de l'image. C'est une valeur comprise entre 1 et 100.
createOptions.setQuality(100);

// Définissez la résolution horizontale/verticale à 96 points par pouce.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Ceci est une option standard pour les images JPEG.
// Deux composants chroma (Cb et Cr) peuvent être réduits en bande passante, sous‑échantillonnés, compressés.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Remplissez l'image avec un dégradé de gris
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Enregistrer dans un fichier.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getColorType() {#getColorType--}
```
public int getColorType()
```


Obtient le type de couleur pour l'image jpeg.

**Returns:**
int

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Créez une image JPEG de 100 x 100 px.
// Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Le nombre de bits par canal est de 8, 8, 8 pour les composants Y, Cr, Cb respectivement.
createOptions.setBitsPerChannel((byte) 8);

// Définissez le type de compression progressive.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Définissez la qualité de l'image. C'est une valeur comprise entre 1 et 100.
createOptions.setQuality(100);

// Définissez la résolution horizontale/verticale à 96 points par pouce.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Ceci est une option standard pour les images JPEG.
// Deux composants chroma (Cb et Cr) peuvent être réduits en bande passante, sous‑échantillonnés, compressés.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Remplissez l'image avec un dégradé de gris
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Enregistrer dans un fichier.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Définit le type de couleur pour l'image jpeg.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Chargez une image BMP à partir d'un fichier.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Effectuez un traitement d'image.

    // Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Le nombre de bits par canal est de 8.
    // Lorsqu'une palette est utilisée, l'index de couleur est stocké dans les données de l'image au lieu de la couleur elle-même.
    saveOptions.setBitsPerChannel((byte) 8);

    // Définissez le type de compression progressive.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Définissez la qualité de l'image. C'est une valeur comprise entre 1 et 100.
    saveOptions.setQuality(100);

    // Définissez la résolution horizontale/verticale à 96 points par pouce.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Si l'image source est en couleur, elle sera convertie en niveaux de gris.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Utilisez une palette pour réduire la taille de sortie.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Obtient les bits par canal pour une image JPEG sans perte. Nous supportons désormais de 2 à 8 bits par canal.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Définit les bits par canal pour une image JPEG sans perte. Nous supportons désormais de 2 à 8 bits par canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Créez une image JPEG de 100 x 100 px.
// Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Le nombre de bits par canal est de 8, 8, 8 pour les composants Y, Cr, Cb respectivement.
createOptions.setBitsPerChannel((byte) 8);

// Définissez le type de compression progressive.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Définissez la qualité de l'image. C'est une valeur comprise entre 1 et 100.
createOptions.setQuality(100);

// Définissez la résolution horizontale/verticale à 96 points par pouce.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Ceci est une option standard pour les images JPEG.
// Deux composants chroma (Cb et Cr) peuvent être réduits en bande passante, sous‑échantillonnés, compressés.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Remplissez l'image avec un dégradé de gris
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Enregistrer dans un fichier.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getQuality() {#getQuality--}
```
public int getQuality()
```


Obtient la qualité de l'image.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Définit la qualité de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Créez une image JPEG de 100 x 100 px.
// Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Le nombre de bits par canal est de 8, 8, 8 pour les composants Y, Cr, Cb respectivement.
createOptions.setBitsPerChannel((byte) 8);

// Définissez le type de compression progressive.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Définissez la qualité de l'image. C'est une valeur comprise entre 1 et 100.
createOptions.setQuality(100);

// Définissez la résolution horizontale/verticale à 96 points par pouce.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Ceci est une option standard pour les images JPEG.
// Deux composants chroma (Cb et Cr) peuvent être réduits en bande passante, sous‑échantillonnés, compressés.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Remplissez l'image avec un dégradé de gris
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Enregistrer dans un fichier.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


La qualité mise à l'échelle.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Obtient les paramètres de l'optimiseur RD.

**Returns:**
[RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Définit les paramètres de l'optimiseur RD.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) | Les paramètres de l'optimiseur RD. |

### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Le profil couleur RGB de destination pour les images JPEG CMYK. À utiliser lors de l'enregistrement des images. Doit être associé au CMYKColorProfile pour une conversion couleur correcte.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Le profil couleur RGB de destination pour les images JPEG CMYK. À utiliser lors de l'enregistrement des images. Doit être associé au CMYKColorProfile pour une conversion couleur correcte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
L'exemple suivant charge un PNG et l'enregistre au format JPEG CMYK en utilisant un profil ICC personnalisé. Ensuite, il charge le JPEG CMYK et le réenregistre au format PNG. La conversion des couleurs de RGB à CMYK et de CMYK à RGB est effectuée à l'aide de profils ICC personnalisés.
``` java
String dir = "c:\\temp\\";

// Charger le PNG et l'enregistrer au JPEG CMYK
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Utiliser des profils ICC personnalisés
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Charger le JPEG CMYK et l'enregistrer au PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Utiliser des profils ICC personnalisés
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


Le profil couleur CMYK de destination pour les images JPEG CMYK. À utiliser lors de l'enregistrement des images. Doit être associé au RGBColorProfile pour une conversion couleur correcte.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Le profil couleur CMYK de destination pour les images JPEG CMYK. À utiliser lors de l'enregistrement des images. Doit être associé au RGBColorProfile pour une conversion couleur correcte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
L'exemple suivant charge un PNG et l'enregistre au format JPEG CMYK en utilisant un profil ICC personnalisé. Ensuite, il charge le JPEG CMYK et le réenregistre au format PNG. La conversion des couleurs de RGB à CMYK et de CMYK à RGB est effectuée à l'aide de profils ICC personnalisés.
``` java
String dir = "c:\\temp\\";

// Charger le PNG et l'enregistrer au JPEG CMYK
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Utiliser des profils ICC personnalisés
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Charger le JPEG CMYK et l'enregistrer au PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Utiliser des profils ICC personnalisés
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Obtient la limite de différence JPEG-LS pour le codage quasi-sans perte (paramètre NEAR de la spécification JPEG-LS).

**Returns:**
int
### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Définit la limite de différence JPEG-LS pour le codage quasi-sans perte (paramètre NEAR de la spécification JPEG-LS).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Obtient le mode d'entrelacement JPEG-LS.

**Returns:**
int
### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Définit le mode d'entrelacement JPEG-LS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Obtient les paramètres prédéfinis JPEG-LS.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters)
### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Définit les paramètres prédéfinis du JPEG-LS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Obtient les sous‑échantillonnages horizontaux pour chaque composant.

**Returns:**
byte[]
### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Définit les sous‑échantillonnages horizontaux pour chaque composant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Obtient les sous‑échantillonnages verticaux pour chaque composant.

**Returns:**
byte[]
### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Définit les sous‑échantillonnages verticaux pour chaque composant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Obtient le mode d'arrondi d'échantillon pour adapter une valeur de 8 bits à une valeur de n bits. `P:JpegOptions.BitsPerChannel`

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Définit le mode d'arrondi d'échantillon pour adapter une valeur de 8 bits à une valeur de n bits. `P:JpegOptions.BitsPerChannel`

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Obtient une valeur indiquant si les composants rouge, vert et bleu doivent être mélangés avec une couleur d'arrière‑plan, si le canal alpha est présent.

**Returns:**
boolean
### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Définit une valeur indiquant si les composants rouge, vert et bleu doivent être mélangés avec une couleur d'arrière‑plan, si le canal alpha est présent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Obtient l'unité de résolution.

**Returns:**
byte - l'unité de résolution.

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Créez une image JPEG de 100 x 100 px.
// Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// Le nombre de bits par canal est de 8, 8, 8 pour les composants Y, Cr, Cb respectivement.
createOptions.setBitsPerChannel((byte) 8);

// Définissez le type de compression progressive.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Définissez la qualité de l'image. C'est une valeur comprise entre 1 et 100.
createOptions.setQuality(100);

// Définissez la résolution horizontale/verticale à 96 points par pouce.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Ceci est une option standard pour les images JPEG.
// Deux composants chroma (Cb et Cr) peuvent être réduits en bande passante, sous‑échantillonnés, compressés.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Remplissez l'image avec un dégradé de gris
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Enregistrer dans un fichier.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Définit l'unité de résolution.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | l'unité de résolution. |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Chargez une image BMP à partir d'un fichier.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Effectuez un traitement d'image.

    // Utilisez des options supplémentaires pour spécifier les paramètres d'image souhaités.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // Le nombre de bits par canal est de 8.
    // Lorsqu'une palette est utilisée, l'index de couleur est stocké dans les données de l'image au lieu de la couleur elle-même.
    saveOptions.setBitsPerChannel((byte) 8);

    // Définissez le type de compression progressive.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Définissez la qualité de l'image. C'est une valeur comprise entre 1 et 100.
    saveOptions.setQuality(100);

    // Définissez la résolution horizontale/verticale à 96 points par pouce.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Si l'image source est en couleur, elle sera convertie en niveaux de gris.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Utilisez une palette pour réduire la taille de sortie.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

