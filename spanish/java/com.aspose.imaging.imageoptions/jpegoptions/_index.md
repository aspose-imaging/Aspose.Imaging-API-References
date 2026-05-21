---
title: "JpegOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Crea imágenes JPEG de alta calidad sin esfuerzo con nuestra API que ofrece niveles ajustables de compresión para optimizar el tamaño de almacenamiento sin comprometer la calidad de la imagen."
type: docs
weight: 26
url: /es/java/com.aspose.imaging.imageoptions/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public class JpegOptions extends ImageOptionsBase implements IHasJpegExifData
```

Crea imágenes JPEG de alta calidad sin esfuerzo con nuestra API, ofreciendo niveles ajustables de compresión para optimizar el tamaño de almacenamiento sin comprometer la calidad de la imagen. Benefíciate del soporte para varios tipos de compresión, codificación casi sin pérdida, perfiles de color RGB y CMYK, así como datos de imagen EXIF, JFIF y contenedores XMP, garantizando opciones versátiles y personalizables para tus necesidades de creación de imágenes.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Inicializa una nueva instancia de la clase `JpegOptions`. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-) | Inicializa una nueva instancia de la clase `JpegOptions`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Obtiene el límite predeterminado de asignación de memoria. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Establece el límite de asignación de memoria predeterminado. |
| [getJfif()](#getJfif--) | Obtiene el jfif. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Establece el jfif. |
| [getComment()](#getComment--) | Obtiene el comentario del archivo jpeg. |
| [setComment(String value)](#setComment-java.lang.String-) | Establece el comentario del archivo jpeg. |
| [getExifData()](#getExifData--) | Obtiene el contenedor de datos Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Establece los datos Exif. |
| [getJpegExifData()](#getJpegExifData--) | Obtener el contenedor de datos Exif. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Obtener o establecer el contenedor de datos exif |
| [getCompressionType()](#getCompressionType--) | Obtiene el tipo de compresión. |
| [setCompressionType(int value)](#setCompressionType-int-) | Establece el tipo de compresión. |
| [getColorType()](#getColorType--) | Obtiene el tipo de color para la imagen jpeg. |
| [setColorType(int value)](#setColorType-int-) | Establece el tipo de color para la imagen jpeg. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Obtiene bits por canal para la imagen jpeg sin pérdida. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Establece bits por canal para la imagen jpeg sin pérdida. |
| [getQuality()](#getQuality--) | Obtiene la calidad de la imagen. |
| [setQuality(int value)](#setQuality-int-) | Establece la calidad de la imagen. |
| [getScaledQuality()](#getScaledQuality--) | La calidad escalada. |
| [getRdOptSettings()](#getRdOptSettings--) | Obtiene la configuración del optimizador RD. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-) | Establece la configuración del optimizador RD. |
| [getRgbColorProfile()](#getRgbColorProfile--) | El perfil de color RGB de destino para imágenes jpeg CMYK. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | El perfil de color RGB de destino para imágenes jpeg CMYK. |
| [getCmykColorProfile()](#getCmykColorProfile--) | El perfil de color CMYK de destino para imágenes jpeg CMYK. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | El perfil de color CMYK de destino para imágenes jpeg CMYK. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Obtiene el límite de diferencia JPEG-LS para codificación casi sin pérdida (parámetro NEAR de la especificación JPEG-LS). |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Establece el límite de diferencia JPEG-LS para codificación casi sin pérdida (parámetro NEAR de la especificación JPEG-LS). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Obtiene el modo de intercalado JPEG-LS. |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Establece el modo de intercalado JPEG-LS. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Obtiene los parámetros preestablecidos JPEG-LS. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-) | Establece los parámetros predefinidos de JPEG-LS. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Obtiene los submuestreos horizontales de cada componente. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Establece los submuestreos horizontales de cada componente. |
| [getVerticalSampling()](#getVerticalSampling--) | Obtiene los submuestreos verticales de cada componente. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Establece los submuestreos verticales de cada componente. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Obtiene el modo de redondeo de muestra para ajustar un valor de 8 bits a un valor de n bits. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Establece el modo de redondeo de muestra para ajustar un valor de 8 bits a un valor de n bits. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Obtiene un valor que indica si los componentes rojo, verde y azul deben mezclarse con un color de fondo, si está presente el canal alfa. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Establece un valor que indica si los componentes rojo, verde y azul deben mezclarse con un color de fondo, si está presente el canal alfa. |
| [getResolutionUnit()](#getResolutionUnit--) | Obtiene la unidad de resolución. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Establece la unidad de resolución. |

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


## Example: The following example shows how to convert a multipage vector image to JPEG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.jpeg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.JpegOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exporta solo las dos primeras páginas. De hecho, solo se rasterizará una página porque JPEG no es un formato multipágina.
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


Inicializa una nueva instancia de la clase `JpegOptions`.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Inicializa una nueva instancia de la clase `JpegOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | Las opciones de JPEG. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Obtiene el límite predeterminado de asignación de memoria.

**Returns:**
int - El límite de asignación de memoria predeterminado.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Establece el límite de asignación de memoria predeterminado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El límite de asignación de memoria predeterminado. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Obtiene el jfif.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Establece el jfif.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getComment() {#getComment--}
```
public String getComment()
```


Obtiene el comentario del archivo jpeg.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Establece el comentario del archivo jpeg.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Obtiene el contenedor de datos Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data container.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public final void setExifData(ExifData value)
```


Establece los datos Exif.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Datos Exif. |

### getJpegExifData() {#getJpegExifData--}
```
public final JpegExifData getJpegExifData()
```


Obtener el contenedor de datos Exif.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data container.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Obtener o establecer el contenedor de datos exif

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Obtiene el tipo de compresión.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Establece el tipo de compresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen JPEG de 100x100 px.
// Utilice opciones adicionales para especificar los parámetros de imagen deseados.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// El número de bits por canal es 8, 8, 8 para los componentes Y, Cr, Cb respectivamente.
createOptions.setBitsPerChannel((byte) 8);

// Establezca el tipo progresivo de compresión.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Establezca la calidad de la imagen. Es un valor entre 1 y 100.
createOptions.setQuality(100);

// Establezca la resolución horizontal/vertical a 96 puntos por pulgada.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Esta es una opción estándar para imágenes JPEG.
// Dos componentes de croma (Cb y Cr) pueden reducirse en ancho de banda, submuestrearse, comprimirse.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Rellena la imagen con un degradado de escala de grises
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Guardar en un archivo.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getColorType() {#getColorType--}
```
public int getColorType()
```


Obtiene el tipo de color para la imagen jpeg.

**Returns:**
int

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen JPEG de 100x100 px.
// Utilice opciones adicionales para especificar los parámetros de imagen deseados.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// El número de bits por canal es 8, 8, 8 para los componentes Y, Cr, Cb respectivamente.
createOptions.setBitsPerChannel((byte) 8);

// Establezca el tipo progresivo de compresión.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Establezca la calidad de la imagen. Es un valor entre 1 y 100.
createOptions.setQuality(100);

// Establezca la resolución horizontal/vertical a 96 puntos por pulgada.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Esta es una opción estándar para imágenes JPEG.
// Dos componentes de croma (Cb y Cr) pueden reducirse en ancho de banda, submuestrearse, comprimirse.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Rellena la imagen con un degradado de escala de grises
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Guardar en un archivo.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Establece el tipo de color para la imagen jpeg.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen BMP desde un archivo.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Realizar algún procesamiento de imagen.

    // Utilice opciones adicionales para especificar los parámetros de imagen deseados.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // El número de bits por canal es 8.
    // Cuando se usa una paleta, el índice de color se almacena en los datos de la imagen en lugar del color mismo.
    saveOptions.setBitsPerChannel((byte) 8);

    // Establezca el tipo progresivo de compresión.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Establezca la calidad de la imagen. Es un valor entre 1 y 100.
    saveOptions.setQuality(100);

    // Establezca la resolución horizontal/vertical a 96 puntos por pulgada.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Si la imagen de origen está coloreada, se convertirá a escala de grises.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Utilice una paleta para reducir el tamaño de salida.
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


Obtiene los bits por canal para una imagen JPEG sin pérdida. Ahora soportamos de 2 a 8 bits por canal.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Establece los bits por canal para una imagen JPEG sin pérdida. Ahora soportamos de 2 a 8 bits por canal.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen JPEG de 100x100 px.
// Utilice opciones adicionales para especificar los parámetros de imagen deseados.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// El número de bits por canal es 8, 8, 8 para los componentes Y, Cr, Cb respectivamente.
createOptions.setBitsPerChannel((byte) 8);

// Establezca el tipo progresivo de compresión.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Establezca la calidad de la imagen. Es un valor entre 1 y 100.
createOptions.setQuality(100);

// Establezca la resolución horizontal/vertical a 96 puntos por pulgada.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Esta es una opción estándar para imágenes JPEG.
// Dos componentes de croma (Cb y Cr) pueden reducirse en ancho de banda, submuestrearse, comprimirse.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Rellena la imagen con un degradado de escala de grises
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Guardar en un archivo.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getQuality() {#getQuality--}
```
public int getQuality()
```


Obtiene la calidad de la imagen.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Establece la calidad de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen JPEG de 100x100 px.
// Utilice opciones adicionales para especificar los parámetros de imagen deseados.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// El número de bits por canal es 8, 8, 8 para los componentes Y, Cr, Cb respectivamente.
createOptions.setBitsPerChannel((byte) 8);

// Establezca el tipo progresivo de compresión.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Establezca la calidad de la imagen. Es un valor entre 1 y 100.
createOptions.setQuality(100);

// Establezca la resolución horizontal/vertical a 96 puntos por pulgada.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Esta es una opción estándar para imágenes JPEG.
// Dos componentes de croma (Cb y Cr) pueden reducirse en ancho de banda, submuestrearse, comprimirse.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Rellena la imagen con un degradado de escala de grises
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Guardar en un archivo.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


La calidad escalada.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Obtiene la configuración del optimizador RD.

**Returns:**
[RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Establece la configuración del optimizador RD.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) | Los ajustes del optimizador RD. |

### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


El perfil de color RGB de destino para imágenes JPEG CMYK. Úselo para guardar imágenes. Debe estar emparejado con CMYKColorProfile para una conversión de color correcta.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


El perfil de color RGB de destino para imágenes JPEG CMYK. Úselo para guardar imágenes. Debe estar emparejado con CMYKColorProfile para una conversión de color correcta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
El siguiente ejemplo carga un PNG y lo guarda como JPEG CMYK usando un perfil ICC personalizado. Luego carga el JPEG CMYK y lo guarda nuevamente como PNG. La conversión de color de RGB a CMYK y de CMYK a RGB se realiza utilizando perfiles ICC personalizados.
``` java
String dir = "c:\\temp\\";

// Cargar PNG y guardarlo como JPEG CMYK
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Usar perfiles ICC personalizados
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

// Cargar JPEG CMYK y guardarlo como PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Usar perfiles ICC personalizados
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


El perfil de color CMYK de destino para imágenes JPEG CMYK. Úselo para guardar imágenes. Debe estar emparejado con RGBColorProfile para una conversión de color correcta.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


El perfil de color CMYK de destino para imágenes JPEG CMYK. Úselo para guardar imágenes. Debe estar emparejado con RGBColorProfile para una conversión de color correcta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
El siguiente ejemplo carga un PNG y lo guarda como JPEG CMYK usando un perfil ICC personalizado. Luego carga el JPEG CMYK y lo guarda nuevamente como PNG. La conversión de color de RGB a CMYK y de CMYK a RGB se realiza utilizando perfiles ICC personalizados.
``` java
String dir = "c:\\temp\\";

// Cargar PNG y guardarlo como JPEG CMYK
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Usar perfiles ICC personalizados
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

// Cargar JPEG CMYK y guardarlo como PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Usar perfiles ICC personalizados
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


Obtiene el límite de diferencia JPEG-LS para codificación casi sin pérdida (parámetro NEAR de la especificación JPEG-LS).

**Returns:**
int
### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Establece el límite de diferencia JPEG-LS para codificación casi sin pérdida (parámetro NEAR de la especificación JPEG-LS).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Obtiene el modo de intercalado JPEG-LS.

**Returns:**
int
### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Establece el modo de intercalado JPEG-LS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Obtiene los parámetros preestablecidos JPEG-LS.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters)
### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Establece los parámetros predefinidos de JPEG-LS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Obtiene los submuestreos horizontales de cada componente.

**Returns:**
byte[]
### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Establece los submuestreos horizontales de cada componente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Obtiene los submuestreos verticales de cada componente.

**Returns:**
byte[]
### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Establece los submuestreos verticales de cada componente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Obtiene el modo de redondeo de muestra para ajustar un valor de 8 bits a un valor de n bits. `P:JpegOptions.BitsPerChannel`

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Establece el modo de redondeo de muestra para ajustar un valor de 8 bits a un valor de n bits. `P:JpegOptions.BitsPerChannel`

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Obtiene un valor que indica si los componentes rojo, verde y azul deben mezclarse con un color de fondo, si está presente el canal alfa.

**Returns:**
boolean
### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Establece un valor que indica si los componentes rojo, verde y azul deben mezclarse con un color de fondo, si está presente el canal alfa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Obtiene la unidad de resolución.

**Returns:**
byte - la unidad de resolución.

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen JPEG de 100x100 px.
// Utilice opciones adicionales para especificar los parámetros de imagen deseados.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// El número de bits por canal es 8, 8, 8 para los componentes Y, Cr, Cb respectivamente.
createOptions.setBitsPerChannel((byte) 8);

// Establezca el tipo progresivo de compresión.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// Establezca la calidad de la imagen. Es un valor entre 1 y 100.
createOptions.setQuality(100);

// Establezca la resolución horizontal/vertical a 96 puntos por pulgada.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// Esta es una opción estándar para imágenes JPEG.
// Dos componentes de croma (Cb y Cr) pueden reducirse en ancho de banda, submuestrearse, comprimirse.
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // Rellena la imagen con un degradado de escala de grises
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // Guardar en un archivo.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Establece la unidad de resolución.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | la unidad de resolución. |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen BMP desde un archivo.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Realizar algún procesamiento de imagen.

    // Utilice opciones adicionales para especificar los parámetros de imagen deseados.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // El número de bits por canal es 8.
    // Cuando se usa una paleta, el índice de color se almacena en los datos de la imagen en lugar del color mismo.
    saveOptions.setBitsPerChannel((byte) 8);

    // Establezca el tipo progresivo de compresión.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // Establezca la calidad de la imagen. Es un valor entre 1 y 100.
    saveOptions.setQuality(100);

    // Establezca la resolución horizontal/vertical a 96 puntos por pulgada.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // Si la imagen de origen está coloreada, se convertirá a escala de grises.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // Utilice una paleta para reducir el tamaño de salida.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

