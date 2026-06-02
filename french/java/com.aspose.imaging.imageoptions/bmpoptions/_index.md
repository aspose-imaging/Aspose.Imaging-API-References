---
title: "BmpOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API des options de création de formats d'image raster BMP et DIB offre aux développeurs un ensemble d'outils polyvalent pour générer des images Bitmap BMP et Device Independent Bitmap DIB personnalisées."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.imageoptions/bmpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class BmpOptions extends ImageOptionsBase
```

L'API des options de création de formats d'image raster BMP et DIB offre aux développeurs un ensemble d'outils polyvalent pour générer des images Bitmap (BMP) et Device Independent Bitmap (DIB) personnalisées. Avec cette API, vous pouvez définir précisément les caractéristiques de l'image telles que le nombre de bits par pixel, le niveau de compression et le type de compression, en adaptant la sortie aux exigences spécifiques. Cette API riche en fonctionnalités permet aux développeurs de créer des images raster personnalisées de haute qualité avec aisance et flexibilité pour diverses applications.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BmpOptions()](#BmpOptions--) | Initialise une nouvelle instance de la classe `BmpOptions`. |
| [BmpOptions(BmpOptions bmpOptions)](#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-) | Initialise une nouvelle instance de la classe `BmpOptions`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient ou définit le nombre de bits par pixel de l'image. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Obtient ou définit le nombre de bits par pixel de l'image. |
| [getCompression()](#getCompression--) | Obtient le type de compression. |
| [setCompression(long value)](#setCompression-long-) | Définit le type de compression. |

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


## Example: The following example shows how to convert a multipage vector image to BMP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.bmp");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.BmpOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportez uniquement les deux premières pages. En fait, seule une page sera rasterisée car le BMP n'est pas un format multi-pages.
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

### BmpOptions() {#BmpOptions--}
```
public BmpOptions()
```


Initialise une nouvelle instance de la classe `BmpOptions`.

### BmpOptions(BmpOptions bmpOptions) {#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-}
```
public BmpOptions(BmpOptions bmpOptions)
```


Initialise une nouvelle instance de la classe `BmpOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bmpOptions | [BmpOptions](../../com.aspose.imaging.imageoptions/bmpoptions) | Les options BMP. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient ou définit le nombre de bits par pixel de l'image.

**Returns:**
int - Le nombre de bits par pixel de l'image.
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Obtient ou définit le nombre de bits par pixel de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le nombre de bits par pixel de l'image. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Créer BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Utilisez 8 bits par pixel pour réduire la taille de l'image de sortie.
    saveOptions.setBitsPerPixel(8);

    // Définissez la palette de couleurs 8 bits la plus proche couvrant le nombre maximal de pixels d'image, afin d'obtenir une image à palette.
    // soit presque visuellement indiscernable d'une image non palettisée.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Enregistrer sans compression.
    // Vous pouvez également utiliser la compression RLE-8 pour réduire la taille de l'image de sortie.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Définissez la résolution horizontale et verticale à 96 dpi.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Obtient le type de compression. Le type de compression par défaut est [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), qui permet d'enregistrer une [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) avec transparence.

Valeur : le type de compression.

**Returns:**
long - le type de compression.

**Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.**

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```

### setCompression(long value) {#setCompression-long-}
```
public void setCompression(long value)
```


Définit le type de compression. Le type de compression par défaut est [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), qui permet d'enregistrer une [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) avec transparence.

Valeur : le type de compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | le type de compression. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Créer BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Utilisez 8 bits par pixel pour réduire la taille de l'image de sortie.
    saveOptions.setBitsPerPixel(8);

    // Définissez la palette de couleurs 8 bits la plus proche couvrant le nombre maximal de pixels d'image, afin d'obtenir une image à palette.
    // soit presque visuellement indiscernable d'une image non palettisée.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Enregistrer sans compression.
    // Vous pouvez également utiliser la compression RLE-8 pour réduire la taille de l'image de sortie.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Définissez la résolution horizontale et verticale à 96 dpi.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```


**Example: Compress BMP image using DXT1 compression algorithm.**

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


**Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.**

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Charger une image PNG depuis un fichier.
try (Image pngImage = Image.load(sourcePath))
{
    // L'image BMP est enregistrée avec prise en charge de la transparence par défaut.
    // Si vous souhaitez spécifier explicitement ce mode, la propriété Compression de BmpOptions doit être définie sur BitmapCompression.Bitfields.
    // La méthode de compression BitmapCompression.Bitfields est la méthode de compression par défaut dans BmpOptions.
    // Ainsi, le même résultat d'exportation d'une image Bmp avec transparence peut être obtenu par l'une des méthodes suivantes.
    // Avec des options par défaut implicites :
    pngImage.save(outputPathPng);
    // Avec des options par défaut explicites :
    pngImage.save(outputPathBmp, new BmpOptions());
    // Spécification de la méthode de compression BitmapCompression.Bitfields :
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


**Example: The example shows how to export a BmpImage with the Rgb compression type.**

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Charger une image PNG depuis un fichier.
try (Image pngImage = Image.load(sourcePath))
{
    // L'image BMP est enregistrée avec prise en charge de la transparence par défaut, ce qui est réalisé en utilisant la méthode de compression BitmapCompression.Bitfields.
    // Pour enregistrer une image BMP avec la méthode de compression Rgb, il faut spécifier les BmpOptions dont la propriété Compression est définie sur BitmapCompression.Rgb.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```

