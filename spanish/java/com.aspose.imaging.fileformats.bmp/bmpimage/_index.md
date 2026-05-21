---
title: "BmpImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Puedes manejar sin esfuerzo archivos Bitmap BMP y Device Independent Bitmap DIB, facilitando la manipulación y el procesamiento eficientes de imágenes raster."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.fileformats.bmp/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class BmpImage extends RasterCachedImage
```

Puedes manejar sin esfuerzo archivos Bitmap (BMP) y Device Independent Bitmap (DIB), facilitando la manipulación y el procesamiento eficientes de imágenes raster. Al realizar diversas operaciones sobre imágenes, esta API simplifica el flujo de trabajo, ofreciendo a los desarrolladores un conjunto de herramientas confiable para trabajar con los formatos BMP y DIB en sus aplicaciones de software.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BmpImage(String path)](#BmpImage-java.lang.String-) | Comienza a usar la clase BmpImage sin esfuerzo con este constructor que inicializa una nueva instancia. |
| [BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.lang.String-int-long-double-double-) | Crea sin esfuerzo una nueva instancia de la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) con este constructor, usando parámetros especificados como ruta, bitsPerPixel y compresión. |
| [BmpImage(InputStream stream)](#BmpImage-java.io.InputStream-) | Comienza a usar la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sin esfuerzo inicializando una nueva instancia con este constructor, usando un flujo como entrada. |
| [BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.io.InputStream-int-long-double-double-) | Empieza a trabajar con la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sin problemas creando una nueva instancia usando un flujo, junto con parámetros especificados como bitsPerPixel y compresión. |
| [BmpImage(RasterImage rasterImage)](#BmpImage-com.aspose.imaging.RasterImage-) | Crea sin esfuerzo una nueva instancia de la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) inicializándola con un objeto RasterImage. |
| [BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-) | Empieza a trabajar con la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sin problemas creando una nueva instancia usando un rasterImage junto con parámetros especificados como bitsPerPixel y compresión. |
| [BmpImage(int width, int height)](#BmpImage-int-int-) | Comienza a usar la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sin esfuerzo creando una nueva instancia con los parámetros de ancho y altura especificados. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-) | Comienza a usar la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sin problemas inicializando una nueva instancia con parámetros como ancho, altura, profundidad de bits y paleta. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-) | Cree sin esfuerzo una nueva instancia de la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) con este constructor, especificando parámetros como ancho, alto, bitsPerPixel y paleta. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBitmapInfoHeader()](#getBitmapInfoHeader--) | Acceda rápidamente a los detalles esenciales de su imagen bitmap con esta función sencilla. |
| [getFileFormat()](#getFileFormat--) | Recupere fácilmente el valor del formato de archivo con esta propiedad fácil de usar. |
| [getRawDataFormat()](#getRawDataFormat--) | Obtenga fácilmente el formato de sus datos sin procesar con esta función fácil de usar. |
| [getRawLineSize()](#getRawLineSize--) | Acceda rápidamente al tamaño de cada línea sin procesar en bytes con esta propiedad sencilla. |
| [getCompression()](#getCompression--) | Recupere sin esfuerzo el tipo de compresión utilizado para la imagen con esta propiedad. |
| [getWidth()](#getWidth--) | Acceda fácilmente al ancho de la imagen con esta propiedad. |
| [getHeight()](#getHeight--) | Recupere sin esfuerzo la altura de la imagen con esta propiedad. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Acceda con facilidad al número de bits por píxel de la imagen usando esta propiedad. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Esta propiedad le permite obtener o establecer fácilmente la resolución horizontal, medida en píxeles por pulgada, del objeto [RasterImage](../../com.aspose.imaging/rasterimage). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Esta propiedad le permite obtener o establecer fácilmente la resolución horizontal, medida en píxeles por pulgada, del objeto [RasterImage](../../com.aspose.imaging/rasterimage). |
| [getVerticalResolution()](#getVerticalResolution--) | Recupere o establezca fácilmente la resolución vertical, medida en píxeles por pulgada, de este objeto [RasterImage](../../com.aspose.imaging/rasterimage) con esta propiedad. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Recupere o establezca fácilmente la resolución vertical, medida en píxeles por pulgada, de este objeto [RasterImage](../../com.aspose.imaging/rasterimage) con esta propiedad. |
| [hasAlpha()](#hasAlpha--) | Obtiene un valor que indica si esta instancia tiene alfa. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Ajuste sin esfuerzo la resolución de su [RasterImage](../../com.aspose.imaging/rasterimage) con este método fácil de usar. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Recupere sin esfuerzo las opciones predeterminadas con este método sencillo. |

## Example: The following example shows how to create a BMP image of the specified size.

``` java
String dir = "c:\\temp\\";

// Crea una imagen BMP de 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Rellene la imagen con un simple degradado lineal rojo-negro.
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
// Cargar una imagen PNG desde un archivo.
try (Image pngImage = Image.load(sourcePath))
{
    // La imagen BMP se guarda con soporte de transparencia de forma predeterminada.
    // Si deseas especificar explícitamente dicho modo, la propiedad Compression de BmpOptions debe establecerse en BitmapCompression.Bitfields.
    // El método de compresión BitmapCompression.Bitfields es el método de compresión predeterminado en BmpOptions.
    // Por lo tanto, el mismo resultado de exportar una imagen Bmp con transparencia se puede lograr mediante cualquiera de las siguientes formas.
    // Con opciones predeterminadas implícitas:
    pngImage.save(outputPathPng);
    // Con opciones predeterminadas explícitas:
    pngImage.save(outputPathBmp, new BmpOptions());
    // Especificando el método de compresión BitmapCompression.Bitfields:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Cargar una imagen PNG desde un archivo.
try (Image pngImage = Image.load(sourcePath))
{
    // La imagen BMP se guarda con soporte de transparencia de forma predeterminada, lo cual se logra utilizando el método de compresión BitmapCompression.Bitfields.
    // Para guardar una imagen BMP con el método de compresión Rgb, se debe especificar BmpOptions con la propiedad Compression establecida en BitmapCompression.Rgb.
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


Comience a usar la clase BmpImage sin esfuerzo con este constructor que inicializa una nueva instancia. Perfecto para desarrolladores que desean comenzar rápidamente con objetos [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) de forma rápida y eficiente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta desde la cual cargar la imagen e inicializar los datos de píxeles y paleta. |

### BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.lang.String-int-long-double-double-}
```
public BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Cree sin esfuerzo una nueva instancia de la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) con este constructor, usando parámetros especificados como ruta, bitsPerPixel y compresión. Ideal para desarrolladores que buscan inicializar objetos BmpImage de forma rápida y eficiente, con control preciso sobre las características de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta desde la cual cargar la imagen e inicializar los datos de píxeles y paleta. |
| bitsPerPixel | int | Los bits por píxel. |
| compresión | long | La compresión a usar. |
| horizontalResolution | double | La resolución horizontal. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |
| verticalResolution | double | La resolución vertical. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |

### BmpImage(InputStream stream) {#BmpImage-java.io.InputStream-}
```
public BmpImage(InputStream stream)
```


Comience a usar la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sin esfuerzo inicializando una nueva instancia con este constructor, usando un flujo como entrada. Perfecto para desarrolladores que buscan una forma conveniente de trabajar con objetos BmpImage de diversas fuentes de datos, garantizando flexibilidad y facilidad de integración.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo desde el cual cargar la imagen e inicializar los datos de píxeles y paleta. |

### BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.io.InputStream-int-long-double-double-}
```
public BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Comience a trabajar con la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sin problemas creando una nueva instancia usando un flujo, junto con parámetros especificados como bitsPerPixel y compresión. Perfecto para desarrolladores que buscan una forma directa de manejar objetos BmpImage, asegurando flexibilidad y eficiencia en sus proyectos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo desde el cual cargar la imagen e inicializar los datos de píxeles y paleta. |
| bitsPerPixel | int | Los bits por píxel. |
| compresión | long | La compresión a usar. |
| horizontalResolution | double | La resolución horizontal. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |
| verticalResolution | double | La resolución vertical. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |

### BmpImage(RasterImage rasterImage) {#BmpImage-com.aspose.imaging.RasterImage-}
```
public BmpImage(RasterImage rasterImage)
```


Cree sin esfuerzo una nueva instancia de la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) inicializándola con un objeto RasterImage. Perfecto para desarrolladores que desean convertir sin problemas imágenes raster existentes al formato BmpImage, garantizando compatibilidad y facilidad de integración en sus proyectos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen con la que se inicializan los datos de píxeles y paleta. |

### BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-}
```
public BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Comience a trabajar con la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sin problemas creando una nueva instancia usando un rasterImage junto con parámetros especificados como bitsPerPixel y compresión. Perfecto para desarrolladores que buscan una forma directa de manejar objetos BmpImage, asegurando flexibilidad y eficiencia en sus proyectos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen con la que se inicializan los datos de píxeles y paleta. |
| bitsPerPixel | int | Los bits por píxel. |
| compresión | long | La compresión a usar. |
| horizontalResolution | double | La resolución horizontal. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |
| verticalResolution | double | La resolución vertical. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |

### BmpImage(int width, int height) {#BmpImage-int-int-}
```
public BmpImage(int width, int height)
```


Comience a usar la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sin esfuerzo creando una nueva instancia con parámetros de ancho y alto especificados. Ideal para desarrolladores que buscan una forma conveniente de generar objetos BmpImage con dimensiones personalizadas, garantizando flexibilidad y facilidad de integración en sus proyectos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen. |
| height | int | La altura de la imagen. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)
```


Comience a usar la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sin problemas inicializando una nueva instancia con parámetros como ancho, altura, profundidad de bits y paleta. Perfecto para desarrolladores que buscan una forma sencilla de crear objetos BmpImage con dimensiones y configuraciones de color personalizadas, garantizando flexibilidad y eficiencia en sus proyectos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen. |
| height | int | La altura de la imagen. |
| bitsPerPixel | int | Los bits por píxel. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta de colores. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)
```


Cree sin esfuerzo una nueva instancia de la clase [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) con este constructor, especificando parámetros como ancho, altura, bitsPerPixel y paleta. Perfecto para desarrolladores que buscan una manera conveniente de generar objetos BmpImage con dimensiones y configuraciones de color personalizadas, garantizando flexibilidad y facilidad de integración en sus proyectos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen. |
| height | int | La altura de la imagen. |
| bitsPerPixel | int | Los bits por píxel. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta de colores. |
| compresión | long | La compresión a usar. |
| horizontalResolution | double | La resolución horizontal. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |
| verticalResolution | double | La resolución vertical. Nota: debido al redondeo, la resolución resultante puede diferir ligeramente de la proporcionada. |

### getBitmapInfoHeader() {#getBitmapInfoHeader--}
```
public BitmapInfoHeader getBitmapInfoHeader()
```


Acceda rápidamente a los detalles esenciales de su imagen bitmap con esta función sencilla. Perfecto para desarrolladores que necesitan obtener la información del encabezado de sus imágenes.

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

//La salida puede verse así:
//El número de colores de la paleta que se requieren para mostrar el bitmap: 0
//El número de colores de la paleta utilizados en el bitmap: 0
//La compresión del bitmap: 0
//La altura del bitmap: 100
//El ancho del bitmap: 100
//El tamaño de los datos sin procesar del bitmap en bytes: 40000
//El número de planos: 1
//La resolución horizontal del bitmap, en píxeles por metro: 0
//La resolución vertical del bitmap, en píxeles por metro: 0
//El número de bits por píxel: 32
//Las máscaras de bits extra: null
//El tamaño del encabezado en bytes: 40
```

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupere fácilmente el valor del formato de archivo con esta propiedad fácil de usar. Ideal para desarrolladores que buscan acceso rápido a la información sobre el formato de archivo.

**Returns:**
long

**Example: The following example shows how to extract information about raw data format and alpha channel from a BMP image.**

``` java

// La clase auxiliar utilizada en el ejemplo principal a continuación.
class Utils {
    // El método auxiliar para obtener una representación en cadena del formato de archivo.
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

// Aquí está el ejemplo principal
Utils utils = new Utils();

// Cree una imagen BMP de 32 bpp de 100 x 100 px.
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

// Cree una imagen BMP de 24 bpp de 100 x 100 px.
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

// En la mayoría de los casos BMP no admite canal alfa, por lo que la salida probablemente se verá así:
// FileFormat=BMP, RawDataFormat=Rgb32Bpp, canales usados: 8,8,8,8, HasAlpha=false
// FileFormat=BMP, RawDataFormat=Rgb24Bpp, canales usados: 8,8,8, HasAlpha=false
```

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Obtenga fácilmente el formato de sus datos sin procesar con esta función fácil de usar. Perfecto para desarrolladores que buscan acceder rápidamente a información crucial sobre el formato de sus datos.

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
        // Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La salida puede verse así:
//El formato de píxel: Rgb24Bpp, canales usados: 8,8,8
//El tamaño de la línea sin procesar en bytes: 1500
//La compresión del bitmap: 0
//El ancho del bitmap: 500
//El alto del bitmap: 500
//El número de bits por píxel: 24
//La resolución horizontal, en píxeles por pulgada: 96.012
//La resolución vertical, en píxeles por pulgada: 96.012
//Establecer los valores de resolución a 96 dpi
//La resolución horizontal, en píxeles por pulgada: 96.012
//La resolución vertical, en píxeles por pulgada: 96.012
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Acceda rápidamente al tamaño de cada línea cruda en bytes con esta propiedad sencilla. Ideal para desarrolladores que necesiten manejar eficientemente datos de imagen crudos.

**Returns:**
int - El tamaño de línea sin procesar en bytes.

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
        // Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La salida puede verse así:
//El formato de píxel: Rgb24Bpp, canales usados: 8,8,8
//El tamaño de la línea sin procesar en bytes: 1500
//La compresión del bitmap: 0
//El ancho del bitmap: 500
//El alto del bitmap: 500
//El número de bits por píxel: 24
//La resolución horizontal, en píxeles por pulgada: 96.012
//La resolución vertical, en píxeles por pulgada: 96.012
//Establecer los valores de resolución a 96 dpi
//La resolución horizontal, en píxeles por pulgada: 96.012
//La resolución vertical, en píxeles por pulgada: 96.012
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Recupere el tipo de compresión usado para la imagen sin esfuerzo con esta propiedad. Perfecto para desarrolladores que necesiten acceder rápidamente a información sobre la compresión de imágenes.

**Returns:**
long - La compresión de la imagen [BitmapCompression](../../com.aspose.imaging.fileformats.bmp/bitmapcompression).

**Example: The following example shows how the bitmap compression affects the output image size.**

``` java

// La clase auxiliar utilizada en el ejemplo principal a continuación.
class Utils {
    // El método auxiliar para obtener una representación en cadena del formato de archivo.
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

// Aquí está el ejemplo principal
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

// Cree una paleta monocromática que contenga solo colores rojo y verde.
com.aspose.imaging.IColorPalette palette = new com.aspose.imaging.ColorPalette(paletterColors);

for (long compression : compressions) {
    // Cree una imagen BMP de 8 bpp de 100 x 100 px.
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0);
    try {
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);

        // Rellene toda la imagen de rojo.
        com.aspose.imaging.brushes.SolidBrush redBrush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
        gr.fillRectangle(redBrush, bmpImage.getBounds());

        // Guarde la imagen en un flujo para obtener el tamaño de la imagen de salida.
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

// La salida puede verse así:
// La compresión=RGB
// El número de bits por píxel=8
// Las dimensiones de la imagen=100 x 100
// El tamaño de la línea cruda=100
// El tamaño de salida en bytes=11078
// ---------------------------------------------
// La compresión=RLE8
// El número de bits por píxel=8
// Las dimensiones de la imagen=100 x 100
// El tamaño de la línea cruda=100
// El tamaño de salida en bytes=856
```

### getWidth() {#getWidth--}
```
public int getWidth()
```


Acceda al ancho de la imagen fácilmente con esta propiedad. Ideal para desarrolladores que buscan información rápida sobre las dimensiones de la imagen.

**Returns:**
int - El ancho de la imagen en píxeles.

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
        // Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La salida puede verse así:
//El formato de píxel: Rgb24Bpp, canales usados: 8,8,8
//El tamaño de la línea sin procesar en bytes: 1500
//La compresión del bitmap: 0
//El ancho del bitmap: 500
//El alto del bitmap: 500
//El número de bits por píxel: 24
//La resolución horizontal, en píxeles por pulgada: 96.012
//La resolución vertical, en píxeles por pulgada: 96.012
//Establecer los valores de resolución a 96 dpi
//La resolución horizontal, en píxeles por pulgada: 96.012
//La resolución vertical, en píxeles por pulgada: 96.012
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Recupere la altura de la imagen sin esfuerzo con esta propiedad. Ideal para desarrolladores que necesiten acceso rápido a información sobre las dimensiones de la imagen.

**Returns:**
int - La altura de la imagen en píxeles.

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
        // Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La salida puede verse así:
//El formato de píxel: Rgb24Bpp, canales usados: 8,8,8
//El tamaño de la línea sin procesar en bytes: 1500
//La compresión del bitmap: 0
//El ancho del bitmap: 500
//El alto del bitmap: 500
//El número de bits por píxel: 24
//La resolución horizontal, en píxeles por pulgada: 96.012
//La resolución vertical, en píxeles por pulgada: 96.012
//Establecer los valores de resolución a 96 dpi
//La resolución horizontal, en píxeles por pulgada: 96.012
//La resolución vertical, en píxeles por pulgada: 96.012
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Acceda al número de bits por píxel de la imagen con facilidad usando esta propiedad. Perfecto para desarrolladores que buscan información rápida sobre la calidad y profundidad de la imagen.

**Returns:**
int - El recuento de bits por píxel de la imagen.

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
        // Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//La salida puede verse así:
//El formato de píxel: Rgb24Bpp, canales usados: 8,8,8
//El tamaño de la línea sin procesar en bytes: 1500
//La compresión del bitmap: 0
//El ancho del bitmap: 500
//El alto del bitmap: 500
//El número de bits por píxel: 24
//La resolución horizontal, en píxeles por pulgada: 96.012
//La resolución vertical, en píxeles por pulgada: 96.012
//Establecer los valores de resolución a 96 dpi
//La resolución horizontal, en píxeles por pulgada: 96.012
//La resolución vertical, en píxeles por pulgada: 96.012
```

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Esta propiedad le permite obtener o establecer fácilmente la resolución horizontal, medida en píxeles por pulgada, del objeto [RasterImage](../../com.aspose.imaging/rasterimage). Ideal para desarrolladores que necesitan un control preciso sobre la resolución de la imagen en sus aplicaciones.

**Returns:**
double - La resolución horizontal.

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método \#setResolution(double, double).setResolution(double, double) para actualizar ambos valores de resolución en una sola llamada.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Obtener la resolución horizontal y vertical del BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// La resolución horizontal, en píxeles por pulgada: 0.0
// La resolución vertical, en píxeles por pulgada: 0.0
// Establecer los valores de resolución a 96 dpi
// La resolución horizontal, en píxeles por pulgada: 96.012
// La resolución vertical, en píxeles por pulgada: 96.012
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Esta propiedad le permite obtener o establecer fácilmente la resolución horizontal, medida en píxeles por pulgada, del objeto [RasterImage](../../com.aspose.imaging/rasterimage). Ideal para desarrolladores que necesitan un control preciso sobre la resolución de la imagen en sus aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La resolución horizontal. |

--------------------

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método \#setResolution(double, double).setResolution(double, double) para actualizar ambos valores de resolución en una sola llamada. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Recupere o establezca fácilmente la resolución vertical, medida en píxeles por pulgada, de este objeto [RasterImage](../../com.aspose.imaging/rasterimage) con esta propiedad. Perfecto para desarrolladores que requieren un control preciso sobre la resolución de la imagen en sus aplicaciones.

**Returns:**
double - La resolución vertical.

--------------------

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método \#setResolution(double, double).setResolution(double, double) para actualizar ambos valores de resolución en una sola llamada.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Obtener la resolución horizontal y vertical del BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// La resolución horizontal, en píxeles por pulgada: 0.0
// La resolución vertical, en píxeles por pulgada: 0.0
// Establecer los valores de resolución a 96 dpi
// La resolución horizontal, en píxeles por pulgada: 96.012
// La resolución vertical, en píxeles por pulgada: 96.012
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Recupere o establezca fácilmente la resolución vertical, medida en píxeles por pulgada, de este objeto [RasterImage](../../com.aspose.imaging/rasterimage) con esta propiedad. Perfecto para desarrolladores que requieren un control preciso sobre la resolución de la imagen en sus aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La resolución vertical. |

--------------------

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método \#setResolution(double, double).setResolution(double, double) para actualizar ambos valores de resolución en una sola llamada. |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtiene un valor que indica si esta instancia tiene alfa.

**Returns:**
boolean - un valor que indica si esta instancia tiene alfa.
### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Ajuste la resolución de su [RasterImage](../../com.aspose.imaging/rasterimage) sin esfuerzo con este método fácil de usar. Perfecto para desarrolladores que buscan un control preciso sobre la resolución de la imagen en sus aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dpiX | double | La resolución horizontal, en puntos por pulgada, del [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | La resolución vertical, en puntos por pulgada, del [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Obtener la resolución horizontal y vertical del BmpImage
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// La resolución horizontal, en píxeles por pulgada: 0.0
// La resolución vertical, en píxeles por pulgada: 0.0
// Establecer los valores de resolución a 96 dpi
// La resolución horizontal, en píxeles por pulgada: 96.012
// La resolución vertical, en píxeles por pulgada: 96.012
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Recupere las opciones predeterminadas sin esfuerzo con este método sencillo. Ideal para desarrolladores que buscan acceso rápido a la configuración o configuraciones predeterminadas de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | java.lang.Object[] | Los argumentos. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
