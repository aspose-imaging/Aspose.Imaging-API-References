---
title: "BmpOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La API para opciones de creación de formato de imagen raster BMP y DIB ofrece a los desarrolladores un conjunto de herramientas versátil para generar imágenes Bitmap BMP y Device Independent Bitmap DIB personalizadas."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.imageoptions/bmpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class BmpOptions extends ImageOptionsBase
```

La API para opciones de creación de formato de imagen raster BMP y DIB ofrece a los desarrolladores un conjunto de herramientas versátil para generar imágenes Bitmap (BMP) y Device Independent Bitmap (DIB) personalizadas. Con esta API, puedes definir con precisión las características de la imagen, como bits por píxel, nivel de compresión y tipo de compresión, adaptando la salida a requisitos específicos. Esta API rica en funciones permite a los desarrolladores crear imágenes raster de alta calidad y personalizadas con facilidad y flexibilidad para diversas aplicaciones.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BmpOptions()](#BmpOptions--) | Inicializa una nueva instancia de la clase `BmpOptions`. |
| [BmpOptions(BmpOptions bmpOptions)](#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-) | Inicializa una nueva instancia de la clase `BmpOptions`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene o establece el recuento de bits por píxel de la imagen. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | Obtiene o establece el recuento de bits por píxel de la imagen. |
| [getCompression()](#getCompression--) | Obtiene el tipo de compresión. |
| [setCompression(long value)](#setCompression-long-) | Establece el tipo de compresión. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Este ejemplo muestra el uso de diferentes clases del espacio de nombres SaveOptions para propósitos de exportación. Se carga una imagen de tipo Gif en una instancia de Image y luego se exporta a varios formatos.
``` java
String dir = "c:\\temp\\";

//Cargar una imagen existente (de tipo Gif) en una instancia de la clase Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Exportar al formato de archivo BMP usando las opciones predeterminadas
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Exportar al formato de archivo JPEG usando las opciones predeterminadas
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Exportar al formato de archivo PNG usando las opciones predeterminadas
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Exportar al formato de archivo TIFF usando las opciones predeterminadas
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

    // Exportar solo las dos primeras páginas. De hecho, solo se rasterizará una página porque BMP no es un formato multipágina.
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


Inicializa una nueva instancia de la clase `BmpOptions`.

### BmpOptions(BmpOptions bmpOptions) {#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-}
```
public BmpOptions(BmpOptions bmpOptions)
```


Inicializa una nueva instancia de la clase `BmpOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bmpOptions | [BmpOptions](../../com.aspose.imaging.imageoptions/bmpoptions) | Las opciones BMP. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene o establece el recuento de bits por píxel de la imagen.

**Returns:**
int - El recuento de bits por píxel de la imagen.
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


Obtiene o establece el recuento de bits por píxel de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El recuento de bits por píxel de la imagen. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Crear BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Utiliza 8 bits por píxel para reducir el tamaño de la imagen de salida.
    saveOptions.setBitsPerPixel(8);

    // Establece la paleta de colores de 8 bits más cercana que cubra el número máximo de píxeles de la imagen, de modo que una imagen paletizada
    // sea casi visualmente indistinguible de una que no está paletizada.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Guardar sin compresión.
    // También puedes usar compresión RLE-8 para reducir el tamaño de la imagen de salida.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Establece la resolución horizontal y vertical a 96 dpi.
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


Obtiene el tipo de compresión. El tipo de compresión predeterminado es [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), que permite guardar una [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) con transparencia.

Valor: El tipo de compresión.

**Returns:**
long - el tipo de compresión.

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


Establece el tipo de compresión. El tipo de compresión predeterminado es [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields), que permite guardar una [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) con transparencia.

Valor: El tipo de compresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | el tipo de compresión. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Crear BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Utiliza 8 bits por píxel para reducir el tamaño de la imagen de salida.
    saveOptions.setBitsPerPixel(8);

    // Establece la paleta de colores de 8 bits más cercana que cubra el número máximo de píxeles de la imagen, de modo que una imagen paletizada
    // sea casi visualmente indistinguible de una que no está paletizada.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // Guardar sin compresión.
    // También puedes usar compresión RLE-8 para reducir el tamaño de la imagen de salida.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // Establece la resolución horizontal y vertical a 96 dpi.
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


**Example: The example shows how to export a BmpImage with the Rgb compression type.**

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

