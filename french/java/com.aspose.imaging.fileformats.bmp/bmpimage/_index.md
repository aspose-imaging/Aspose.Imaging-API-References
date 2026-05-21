---
title: "BmpImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Vous pouvez gérer facilement les fichiers Bitmap BMP et Device Independent Bitmap DIB, facilitant la manipulation et le traitement efficaces des images raster."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.fileformats.bmp/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class BmpImage extends RasterCachedImage
```

Vous pouvez gérer facilement les fichiers Bitmap (BMP) et Device Independent Bitmap (DIB), facilitant la manipulation et le traitement efficaces des images raster. En effectuant diverses opérations sur les images, cette API simplifie le flux de travail, offrant aux développeurs une boîte à outils fiable pour travailler avec les formats BMP et DIB dans leurs applications logicielles.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BmpImage(String path)](#BmpImage-java.lang.String-) | Commencez à utiliser la classe BmpImage facilement avec ce constructeur qui initialise une nouvelle instance. |
| [BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.lang.String-int-long-double-double-) | Créez facilement une nouvelle instance de la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) avec ce constructeur, en utilisant les paramètres spécifiés tels que le chemin, bitsPerPixel et la compression. |
| [BmpImage(InputStream stream)](#BmpImage-java.io.InputStream-) | Commencez à utiliser la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) facilement en initialisant une nouvelle instance avec ce constructeur, en utilisant un flux comme entrée. |
| [BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.io.InputStream-int-long-double-double-) | Commencez à travailler avec la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) de manière fluide en créant une nouvelle instance à l'aide d'un flux, ainsi que des paramètres spécifiés tels que bitsPerPixel et la compression. |
| [BmpImage(RasterImage rasterImage)](#BmpImage-com.aspose.imaging.RasterImage-) | Créez facilement une nouvelle instance de la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) en l'initialisant avec un objet RasterImage. |
| [BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-) | Commencez à travailler avec la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) de manière fluide en créant une nouvelle instance à l'aide d'un rasterImage, ainsi que des paramètres spécifiés tels que bitsPerPixel et la compression. |
| [BmpImage(int width, int height)](#BmpImage-int-int-) | Commencez à utiliser la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) facilement en créant une nouvelle instance avec les paramètres de largeur et de hauteur spécifiés. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-) | Commencez à utiliser la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) de manière fluide en initialisant une nouvelle instance avec des paramètres tels que la largeur, la hauteur, la profondeur de bits et la palette. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-) | Créez sans effort une nouvelle instance de la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) avec ce constructeur, en spécifiant des paramètres tels que la largeur, la hauteur, les bits par pixel et la palette. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitmapInfoHeader()](#getBitmapInfoHeader--) | Accédez rapidement aux détails essentiels de votre image bitmap avec cette fonction simple. |
| [getFileFormat()](#getFileFormat--) | Récupérez facilement la valeur du format de fichier avec cette propriété conviviale. |
| [getRawDataFormat()](#getRawDataFormat--) | Obtenez facilement le format de vos données brutes avec cette fonction conviviale. |
| [getRawLineSize()](#getRawLineSize--) | Accédez rapidement à la taille de chaque ligne brute en octets avec cette propriété simple. |
| [getCompression()](#getCompression--) | Récupérez sans effort le type de compression utilisé pour l'image avec cette propriété. |
| [getWidth()](#getWidth--) | Accédez facilement à la largeur de l'image avec cette propriété. |
| [getHeight()](#getHeight--) | Récupérez sans effort la hauteur de l'image avec cette propriété. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Accédez facilement au nombre de bits par pixel de l'image en utilisant cette propriété. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Cette propriété vous permet de récupérer ou de définir facilement la résolution horizontale, mesurée en pixels par pouce, de l'objet [RasterImage](../../com.aspose.imaging/rasterimage). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Cette propriété vous permet de récupérer ou de définir facilement la résolution horizontale, mesurée en pixels par pouce, de l'objet [RasterImage](../../com.aspose.imaging/rasterimage). |
| [getVerticalResolution()](#getVerticalResolution--) | Récupérez ou définissez facilement la résolution verticale, mesurée en pixels par pouce, de cet objet [RasterImage](../../com.aspose.imaging/rasterimage) avec cette propriété. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Récupérez ou définissez facilement la résolution verticale, mesurée en pixels par pouce, de cet objet [RasterImage](../../com.aspose.imaging/rasterimage) avec cette propriété. |
| [hasAlpha()](#hasAlpha--) | Obtient une valeur indiquant si cette instance possède de l'alpha. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Ajustez sans effort la résolution de votre [RasterImage](../../com.aspose.imaging/rasterimage) avec cette méthode conviviale. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Récupérez sans effort les options par défaut avec cette méthode simple. |

## Example: The following example shows how to create a BMP image of the specified size.

``` java
String dir = "c:\\temp\\";

// Créer une image BMP de 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Remplissez l'image avec un simple dégradé linéaire rouge-noir.
    int width = bmpImage.getWidth();
    int height = bmpImage.getHeight();
    for (int y = 0; y < height; y++) {
        for (int x = 0; x < width; x++) {
            int hue = (255 * x) / width;
            bmpImage.setPixel(x, y, com.aspose.imaging.Color.fromArgb(255, hue, 0, 0));
        }
    }

    java.io.OutputStream stream = new java.io.FileOutputStream(dir + "output.bmp");
    try {
        bmpImage.save(stream);
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}
```


## Example: Compress BMP image using DXT1 compression algorithm.

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


## Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```


## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

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


## Example: The example shows how to export a BmpImage with the Rgb compression type.

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


## Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### BmpImage(String path) {#BmpImage-java.lang.String-}
```
public BmpImage(String path)
```


Commencez à utiliser la classe BmpImage sans effort avec ce constructeur qui initialise une nouvelle instance. Idéal pour les développeurs qui souhaitent démarrer rapidement avec les objets [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) de manière efficace.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger l'image et initialiser les données de pixels et de palette. |

### BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.lang.String-int-long-double-double-}
```
public BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Créez sans effort une nouvelle instance de la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) avec ce constructeur, en utilisant des paramètres spécifiés tels que le chemin, les bits par pixel et la compression. Idéal pour les développeurs souhaitant initialiser rapidement et efficacement des objets BmpImage, avec un contrôle précis des caractéristiques de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger l'image et initialiser les données de pixels et de palette. |
| bitsPerPixel | int | Les bits par pixel. |
| compression | long | La compression à utiliser. |
| horizontalResolution | double | La résolution horizontale. Notez qu'en raison de l'arrondi, la résolution résultante peut différer légèrement de celle fournie. |
| verticalResolution | double | La résolution verticale. Notez qu'en raison de l'arrondi, la résolution résultante peut différer légèrement de celle fournie. |

### BmpImage(InputStream stream) {#BmpImage-java.io.InputStream-}
```
public BmpImage(InputStream stream)
```


Commencez à utiliser la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sans effort en initialisant une nouvelle instance avec ce constructeur, en utilisant un flux comme entrée. Idéal pour les développeurs recherchant un moyen pratique de travailler avec des objets BmpImage provenant de diverses sources de données, garantissant flexibilité et facilité d'intégration.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger l'image et initialiser les données de pixels et de palette. |

### BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.io.InputStream-int-long-double-double-}
```
public BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Commencez à travailler avec la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) de manière fluide en créant une nouvelle instance à l'aide d'un flux, ainsi que des paramètres spécifiés tels que les bits par pixel et la compression. Idéal pour les développeurs recherchant une méthode simple pour gérer les objets BmpImage, assurant flexibilité et efficacité dans leurs projets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger l'image et initialiser les données de pixels et de palette. |
| bitsPerPixel | int | Les bits par pixel. |
| compression | long | La compression à utiliser. |
| horizontalResolution | double | La résolution horizontale. Notez qu'en raison de l'arrondi, la résolution résultante peut différer légèrement de celle fournie. |
| verticalResolution | double | La résolution verticale. Notez qu'en raison de l'arrondi, la résolution résultante peut différer légèrement de celle fournie. |

### BmpImage(RasterImage rasterImage) {#BmpImage-com.aspose.imaging.RasterImage-}
```
public BmpImage(RasterImage rasterImage)
```


Créez sans effort une nouvelle instance de la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) en l'initialisant avec un objet RasterImage. Idéal pour les développeurs souhaitant convertir facilement des images raster existantes au format BmpImage, garantissant compatibilité et facilité d'intégration dans leurs projets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image avec laquelle initialiser les données de pixels et de palette. |

### BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-}
```
public BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Commencez à travailler avec la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) de manière fluide en créant une nouvelle instance à l'aide d'un rasterImage, ainsi que des paramètres spécifiés tels que les bits par pixel et la compression. Idéal pour les développeurs recherchant une méthode simple pour gérer les objets BmpImage, assurant flexibilité et efficacité dans leurs projets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image avec laquelle initialiser les données de pixels et de palette. |
| bitsPerPixel | int | Les bits par pixel. |
| compression | long | La compression à utiliser. |
| horizontalResolution | double | La résolution horizontale. Notez qu'en raison de l'arrondi, la résolution résultante peut différer légèrement de celle fournie. |
| verticalResolution | double | La résolution verticale. Notez qu'en raison de l'arrondi, la résolution résultante peut différer légèrement de celle fournie. |

### BmpImage(int width, int height) {#BmpImage-int-int-}
```
public BmpImage(int width, int height)
```


Commencez à utiliser la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sans effort en créant une nouvelle instance avec des paramètres de largeur et de hauteur spécifiés. Idéal pour les développeurs recherchant un moyen pratique de générer des objets BmpImage de dimensions personnalisées, assurant flexibilité et facilité d'intégration dans leurs projets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image. |
| height | int | La hauteur de l'image. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)
```


Commencez à utiliser la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) de manière fluide en initialisant une nouvelle instance avec des paramètres tels que la largeur, la hauteur, la profondeur de couleur et la palette. Idéal pour les développeurs cherchant une façon simple de créer des objets BmpImage avec des dimensions et des configurations de couleur personnalisées, garantissant flexibilité et efficacité dans leurs projets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image. |
| height | int | La hauteur de l'image. |
| bitsPerPixel | int | Les bits par pixel. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette de couleurs. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)
```


Créez sans effort une nouvelle instance de la classe [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) avec ce constructeur, en spécifiant des paramètres tels que la largeur, la hauteur, bitsPerPixel et la palette. Idéal pour les développeurs recherchant un moyen pratique de générer des objets BmpImage avec des dimensions et des configurations de couleur personnalisées, assurant flexibilité et facilité d'intégration dans leurs projets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image. |
| height | int | La hauteur de l'image. |
| bitsPerPixel | int | Les bits par pixel. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette de couleurs. |
| compression | long | La compression à utiliser. |
| horizontalResolution | double | La résolution horizontale. Notez qu'en raison de l'arrondi, la résolution résultante peut différer légèrement de celle fournie. |
| verticalResolution | double | La résolution verticale. Notez qu'en raison de l'arrondi, la résolution résultante peut différer légèrement de celle fournie. |

### getBitmapInfoHeader() {#getBitmapInfoHeader--}
```
public BitmapInfoHeader getBitmapInfoHeader()
```


Accédez rapidement aux détails essentiels de votre image bitmap avec cette fonction simple. Idéal pour les développeurs qui doivent récupérer les informations d'en-tête de leurs images.

**Returns:**
[BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader) - The bitmap information header.

**Example: The following example gets the information from the BMP header and prints it to the console.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    com.aspose.imaging.fileformats.bmp.BitmapInfoHeader header = bmpImage.getBitmapInfoHeader();

    System.out.println("The number of palette colors that are required for displaying the bitmap: " + header.getBitmapColorsImportant());
    System.out.println("The number of palette colors used in the bitmap: " + header.getBitmapColorsUsed());
    System.out.println("The bitmap compression: " + header.getBitmapCompression());
    System.out.println("The bitmap height: " + header.getBitmapHeight());
    System.out.println("The bitmap width: " + header.getBitmapWidth());
    System.out.println("The bitmap raw data size in bytes: " + header.getBitmapImageSize());
    System.out.println("The number of planes: " + header.getBitmapPlanes());
    System.out.println("The horizontal resolution of the bitmap, in pixels-per-meter: " + header.getBitmapXPelsPerMeter());
    System.out.println("The vertical resolution of the bitmap, in pixels-per-meter: " + header.getBitmapYPelsPerMeter());
    System.out.println("The number of bits per pixel: " + header.getBitsPerPixel());
    System.out.println("The extra bits masks: " + header.getExtraBitMasks());
    System.out.println("The header size in bytes: " + header.getHeaderSize());
} finally {
    image.dispose();
}

//La sortie peut ressembler à ceci :
//Le nombre de couleurs de palette requis pour afficher le bitmap : 0
//Le nombre de couleurs de palette utilisées dans le bitmap : 0
//La compression du bitmap : 0
//La hauteur du bitmap : 100
//La largeur du bitmap : 100
//La taille des données brutes du bitmap en octets : 40000
//Le nombre de plans : 1
//La résolution horizontale du bitmap, en pixels par mètre : 0
//La résolution verticale du bitmap, en pixels par mètre : 0
//Le nombre de bits par pixel : 32
//Les masques de bits supplémentaires : null
//La taille de l'en-tête en octets : 40
```

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupérez facilement la valeur du format de fichier avec cette propriété conviviale. Idéal pour les développeurs cherchant un accès rapide aux informations sur le format de fichier.

**Returns:**
long

**Example: The following example shows how to extract information about raw data format and alpha channel from a BMP image.**

``` java

// La classe d'assistance utilisée dans l'exemple principal ci-dessous.
class Utils {
    // La méthode d'assistance pour obtenir une représentation sous forme de chaîne du format de fichier.
    public String getFileFormatString(long fileFormat) {
        if (fileFormat == com.aspose.imaging.FileFormat.Bmp) {
            return "BMP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Gif) {
            return "GIF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dicom) {
            return "DICOM";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Djvu) {
            return "DJVU";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dng) {
            return "DNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Png) {
            return "PNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg) {
            return "JPEG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg2000) {
            return "JPEG2000";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Psd) {
            return "PSD";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Tiff) {
            return "Tiff";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Webp) {
            return "WEBP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cdr) {
            return "CDR";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cmx) {
            return "CMX";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Emf) {
            return "EMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Wmf) {
            return "WMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Svg) {
            return "SVG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Odg) {
            return "ODG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Eps) {
            return "EPS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Voici l'exemple principal
Utils utils = new Utils();

// Créez une image BMP 32 bpp de 100 × 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 32, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// Créez une image BMP 24 bpp de 100 × 100 px.
bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 24, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// Dans la plupart des cas, le BMP ne prend pas en charge le canal alpha, donc le résultat ressemblera probablement à ceci :
// FileFormat=BMP, RawDataFormat=Rgb32Bpp, canaux utilisés : 8,8,8,8, HasAlpha=false
// FileFormat=BMP, RawDataFormat=Rgb24Bpp, canaux utilisés : 8,8,8, HasAlpha=false
```

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Obtenez facilement le format de vos données brutes avec cette fonction conviviale. Idéal pour les développeurs souhaitant accéder rapidement à des informations essentielles sur le format de leurs données.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La sortie peut ressembler à ceci :
//Le format de pixel : Rgb24Bpp, canaux utilisés : 8,8,8
//La taille de la ligne brute en octets : 1500
//La compression du bitmap : 0
//La largeur du bitmap : 500
//La hauteur du bitmap : 500
//Le nombre de bits par pixel : 24
//La résolution horizontale, en pixels par pouce : 96.012
//La résolution verticale, en pixels par pouce : 96.012
//Définissez les valeurs de résolution à 96 dpi
//La résolution horizontale, en pixels par pouce : 96.012
//La résolution verticale, en pixels par pouce : 96.012
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Accédez rapidement à la taille de chaque ligne brute en octets avec cette propriété simple. Idéal pour les développeurs qui doivent gérer efficacement les données d'image brutes.

**Returns:**
int - La taille brute de la ligne en octets.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La sortie peut ressembler à ceci :
//Le format de pixel : Rgb24Bpp, canaux utilisés : 8,8,8
//La taille de la ligne brute en octets : 1500
//La compression du bitmap : 0
//La largeur du bitmap : 500
//La hauteur du bitmap : 500
//Le nombre de bits par pixel : 24
//La résolution horizontale, en pixels par pouce : 96.012
//La résolution verticale, en pixels par pouce : 96.012
//Définissez les valeurs de résolution à 96 dpi
//La résolution horizontale, en pixels par pouce : 96.012
//La résolution verticale, en pixels par pouce : 96.012
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Récupérez le type de compression utilisé pour l'image sans effort avec cette propriété. Parfait pour les développeurs qui ont besoin d'accéder rapidement aux informations sur la compression d'image.

**Returns:**
long - La compression de l'image [BitmapCompression](../../com.aspose.imaging.fileformats.bmp/bitmapcompression).

**Example: The following example shows how the bitmap compression affects the output image size.**

``` java

// La classe d'assistance utilisée dans l'exemple principal ci-dessous.
class Utils {
    // La méthode d'assistance pour obtenir une représentation sous forme de chaîne du format de fichier.
    public String getBitmapCompressionString(long bitmapCompression) {
        if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb) {
            return "RGB";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8) {
            return "RLE8";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle4) {
            return "RLE4";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Bitfields) {
            return "BITFIELDS";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Jpeg) {
            return "JPEG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Png) {
            return "PNG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.AlphaBitfields) {
            return "ALPHA_BITFIELDS";
        } else {
            return "UNDEFINED";
        }
    }
}

// Voici l'exemple principal
Utils utils = new Utils();

long[] compressions = new long[]
        {
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb,
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8,
        };

com.aspose.imaging.Color[] paletterColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
        };

// Créez une palette monochrome qui ne contient que les couleurs rouge et verte.
com.aspose.imaging.IColorPalette palette = new com.aspose.imaging.ColorPalette(paletterColors);

for (long compression : compressions) {
    // Créez une image BMP 8-bpp de 100 x 100 px.
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0);
    try {
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);

        // Remplissez toute l'image en rouge.
        com.aspose.imaging.brushes.SolidBrush redBrush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
        gr.fillRectangle(redBrush, bmpImage.getBounds());

        // Enregistrez l'image dans un flux pour obtenir la taille de l'image de sortie.
        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            bmpImage.save(stream);

            System.out.printf("---------------------------------------------\r\n");
            System.out.printf("The compression=%s\r\n", utils.getBitmapCompressionString(bmpImage.getCompression()));
            System.out.printf("The number of bits per pixel=%s\r\n", bmpImage.getBitsPerPixel());
            System.out.printf("The image dimensions=%s x %s\r\n", bmpImage.getWidth(), bmpImage.getHeight());
            System.out.printf("The raw line size=%s\r\n", bmpImage.getRawLineSize());
            System.out.printf("The output size in bytes=%s\r\n", stream.size());
        } finally {
            stream.close();
        }
    } finally {
        bmpImage.dispose();
    }
}

// La sortie peut ressembler à ceci :
// La compression=RGB
// Le nombre de bits par pixel=8
// Les dimensions de l'image=100 x 100
// La taille de la ligne brute=100
// La taille de sortie en octets=11078
// ---------------------------------------------
// La compression=RLE8
// Le nombre de bits par pixel=8
// Les dimensions de l'image=100 x 100
// La taille de la ligne brute=100
// La taille de sortie en octets=856
```

### getWidth() {#getWidth--}
```
public int getWidth()
```


Accédez facilement à la largeur de l'image avec cette propriété. Idéal pour les développeurs recherchant des informations rapides sur les dimensions de l'image.

**Returns:**
int - La largeur de l'image en pixels.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La sortie peut ressembler à ceci :
//Le format de pixel : Rgb24Bpp, canaux utilisés : 8,8,8
//La taille de la ligne brute en octets : 1500
//La compression du bitmap : 0
//La largeur du bitmap : 500
//La hauteur du bitmap : 500
//Le nombre de bits par pixel : 24
//La résolution horizontale, en pixels par pouce : 96.012
//La résolution verticale, en pixels par pouce : 96.012
//Définissez les valeurs de résolution à 96 dpi
//La résolution horizontale, en pixels par pouce : 96.012
//La résolution verticale, en pixels par pouce : 96.012
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Récupérez la hauteur de l'image sans effort avec cette propriété. Idéal pour les développeurs qui ont besoin d'un accès rapide aux informations sur les dimensions de l'image.

**Returns:**
int - La hauteur de l'image en pixels.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La sortie peut ressembler à ceci :
//Le format de pixel : Rgb24Bpp, canaux utilisés : 8,8,8
//La taille de la ligne brute en octets : 1500
//La compression du bitmap : 0
//La largeur du bitmap : 500
//La hauteur du bitmap : 500
//Le nombre de bits par pixel : 24
//La résolution horizontale, en pixels par pouce : 96.012
//La résolution verticale, en pixels par pouce : 96.012
//Définissez les valeurs de résolution à 96 dpi
//La résolution horizontale, en pixels par pouce : 96.012
//La résolution verticale, en pixels par pouce : 96.012
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Accédez facilement au nombre de bits par pixel de l'image en utilisant cette propriété. Parfait pour les développeurs recherchant des informations rapides sur la qualité et la profondeur de l'image.

**Returns:**
int - Le nombre de bits par pixel de l'image.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La sortie peut ressembler à ceci :
//Le format de pixel : Rgb24Bpp, canaux utilisés : 8,8,8
//La taille de la ligne brute en octets : 1500
//La compression du bitmap : 0
//La largeur du bitmap : 500
//La hauteur du bitmap : 500
//Le nombre de bits par pixel : 24
//La résolution horizontale, en pixels par pouce : 96.012
//La résolution verticale, en pixels par pouce : 96.012
//Définissez les valeurs de résolution à 96 dpi
//La résolution horizontale, en pixels par pouce : 96.012
//La résolution verticale, en pixels par pouce : 96.012
```

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Cette propriété vous permet de récupérer ou de définir facilement la résolution horizontale, mesurée en pixels par pouce, de l'objet [RasterImage](../../com.aspose.imaging/rasterimage). Idéal pour les développeurs qui ont besoin d'un contrôle précis de la résolution d'image dans leurs applications.

**Returns:**
double - La résolution horizontale.

Remarque : par défaut, cette valeur est toujours 96 car les différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode \#setResolution(double, double).setResolution(double, double) pour mettre à jour les deux valeurs de résolution en un seul appel.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Obtenir la résolution horizontale et verticale du BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// La résolution horizontale, en pixels par pouce : 0.0
// La résolution verticale, en pixels par pouce : 0.0
// Définissez les valeurs de résolution à 96 dpi
// La résolution horizontale, en pixels par pouce : 96.012
// La résolution verticale, en pixels par pouce : 96.012
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Cette propriété vous permet de récupérer ou de définir facilement la résolution horizontale, mesurée en pixels par pouce, de l'objet [RasterImage](../../com.aspose.imaging/rasterimage). Idéal pour les développeurs qui ont besoin d'un contrôle précis de la résolution d'image dans leurs applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La résolution horizontale. |

--------------------

Remarque : par défaut, cette valeur est toujours 96 car les différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode \#setResolution(double, double).setResolution(double, double) pour mettre à jour les deux valeurs de résolution en un seul appel. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Récupérez ou définissez facilement la résolution verticale, mesurée en pixels par pouce, de cet objet [RasterImage](../../com.aspose.imaging/rasterimage) à l'aide de cette propriété. Parfait pour les développeurs qui nécessitent un contrôle précis de la résolution d'image dans leurs applications.

**Returns:**
double - La résolution verticale.

--------------------

Remarque : par défaut, cette valeur est toujours 96 car les différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode \#setResolution(double, double).setResolution(double, double) pour mettre à jour les deux valeurs de résolution en un seul appel.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Obtenir la résolution horizontale et verticale du BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// La résolution horizontale, en pixels par pouce : 0.0
// La résolution verticale, en pixels par pouce : 0.0
// Définissez les valeurs de résolution à 96 dpi
// La résolution horizontale, en pixels par pouce : 96.012
// La résolution verticale, en pixels par pouce : 96.012
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Récupérez ou définissez facilement la résolution verticale, mesurée en pixels par pouce, de cet objet [RasterImage](../../com.aspose.imaging/rasterimage) à l'aide de cette propriété. Parfait pour les développeurs qui nécessitent un contrôle précis de la résolution d'image dans leurs applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La résolution verticale. |

--------------------

Remarque : par défaut, cette valeur est toujours 96 car les différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode \#setResolution(double, double).setResolution(double, double) pour mettre à jour les deux valeurs de résolution en un seul appel. |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtient une valeur indiquant si cette instance possède de l'alpha.

**Returns:**
booléen - une valeur indiquant si cette instance possède un canal alpha.
### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Ajustez la résolution de votre [RasterImage](../../com.aspose.imaging/rasterimage) sans effort avec cette méthode conviviale. Idéal pour les développeurs qui recherchent un contrôle précis de la résolution d'image dans leurs applications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dpiX | double | La résolution horizontale, en points par pouce, du [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | La résolution verticale, en points par pouce, du [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Obtenir la résolution horizontale et verticale du BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilisez la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La sortie peut ressembler à ceci :
// La résolution horizontale, en pixels par pouce : 0.0
// La résolution verticale, en pixels par pouce : 0.0
// Définissez les valeurs de résolution à 96 dpi
// La résolution horizontale, en pixels par pouce : 96.012
// La résolution verticale, en pixels par pouce : 96.012
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Récupérez les options par défaut sans effort avec cette méthode simple. Idéal pour les développeurs qui souhaitent un accès rapide aux paramètres ou configurations d'image par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | Les arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
