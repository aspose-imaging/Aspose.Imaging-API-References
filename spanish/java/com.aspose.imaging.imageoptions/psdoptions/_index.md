---
title: "PsdOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Crea imágenes PSD de documentos Photoshop con nuestra API, ofreciendo opciones versátiles con diferentes versiones de formato, métodos de compresión, modos de color y recuentos de bits por canal de color."
type: docs
weight: 40
url: /es/java/com.aspose.imaging.imageoptions/psdoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Crea imágenes de documentos Photoshop (PSD) con nuestra API, ofreciendo opciones versátiles con diferentes versiones de formato, métodos de compresión, modos de color y recuentos de bits por canal de color. Maneja sin problemas los contenedores de metadatos XMP, garantizando un procesamiento de imágenes integral con el poder de las características del formato PSD, como capas de imagen, máscaras de capa e información de archivo, para la personalización y creatividad en tus diseños.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Inicializa una nueva instancia de la clase `PsdOptions`. |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-) | Inicializa una nueva instancia de la clase `PsdOptions`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Obtener o establecer el contenedor de datos XMP |
| [getVersion()](#getVersion--) | Obtiene o establece la versión del archivo PSD. |
| [setVersion(int value)](#setVersion-int-) | Obtiene o establece la versión del archivo PSD. |
| [getCompressionMethod()](#getCompressionMethod--) | Obtiene o establece el método de compresión del PSD. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Obtiene o establece el método de compresión del PSD. |
| [getPsdVersion()](#getPsdVersion--) | Obtiene la versión del formato de archivo. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Establece la versión del formato de archivo. |
| [getColorMode()](#getColorMode--) | Obtiene o establece el modo de color del PSD. |
| [setColorMode(short value)](#setColorMode-short-) | Obtiene o establece el modo de color del PSD. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Obtiene o establece el recuento de bits por canal de color. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Obtiene o establece el recuento de bits por canal de color. |
| [getChannelsCount()](#getChannelsCount--) | Obtiene el recuento de canales de color. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Establece el recuento de canales de color. |
| [isRemoveGlobalTextEngineResource()](#isRemoveGlobalTextEngineResource--) | Obtiene un valor que indica si - Eliminar el recurso del motor de texto global - Utilizado para algunos archivos PSD con capas de texto, solo en el caso de que no puedan abrirse en Adobe Photoshop después del procesamiento (principalmente por capas de texto relacionadas con fuentes ausentes). |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Establece un valor que indica si - Eliminar el recurso del motor de texto global - Utilizado para algunos archivos PSD con capas de texto, solo en el caso de que no puedan abrirse en Adobe Photoshop después del procesamiento (principalmente por capas de texto relacionadas con fuentes ausentes). |
| [isRefreshImagePreviewData()](#isRefreshImagePreviewData--) | Obtiene un valor que indica si [refrescar datos de vista previa de la imagen] - opción utilizada para maximizar la compatibilidad con otros visores de imágenes PSD. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Establece un valor que indica si [refrescar datos de vista previa de la imagen] - opción utilizada para maximizar la compatibilidad con otros visores de imágenes PSD. |
| [getVectorizationOptions()](#getVectorizationOptions--) | Obtiene las opciones de vectorización del PSD. |
| [setVectorizationOptions(PsdVectorizationOptions value)](#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-) | Establece las opciones de vectorización PSD. |

## Example: This example demonstrates the use of Aspose.
Este ejemplo demuestra el uso de Aspose.Imaging for Java API para convertir imágenes al formato PSD. Para lograr este objetivo, este ejemplo carga una imagen existente y luego la guarda nuevamente en formato PSD.
``` java

// Crea una instancia de la clase image y inicialízala con un archivo existente mediante la ruta del archivo.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Crea una instancia de la clase PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Establece el CompressionMethod como RLE.
    // Nota: Otro CompressionMethod compatible es CompressionMethod.RAW [Sin compresión].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Establece el ColorMode a GrayScale.
    // Nota: Otros ColorModes compatibles son ColorModes.Bitmap y ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Guarda la imagen en disco con la configuración de PsdOptions proporcionada.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to PSD format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.psd";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PsdOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exporta solo las dos primeras páginas. Estas páginas se presentarán como capas en el PSD de salida.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
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

### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Inicializa una nueva instancia de la clase `PsdOptions`.

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Inicializa una nueva instancia de la clase `PsdOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.imaging.imageoptions/psdoptions) | Las opciones. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Obtener o establecer el contenedor de datos XMP

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtiene o establece la versión del archivo PSD.

Valor: La versión del archivo PSD.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtiene o establece la versión del archivo PSD.

Valor: La versión del archivo PSD.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Define un degradado lineal azul-transparente.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Rellena la imagen PNG con el degradado lineal azul-transparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Las siguientes opciones se usarán para guardar la imagen PNG en formato PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // El número de bits por canal.
    saveOptions.setChannelBitsCount((byte) 8);

    // El número de canales. Un canal para cada componente de color R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // El modo de color
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Sin compresión.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // La versión predeterminada es 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // La compresión RLE permite reducir el tamaño de la imagen de salida.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // La salida puede verse así:
    // El tamaño de la imagen PSD con compresión RAW: 40090.
    // El tamaño de la imagen PSD con compresión RLE: 16185.
} finally {
    pngImage.dispose();
}
```

### getCompressionMethod() {#getCompressionMethod--}
```
public short getCompressionMethod()
```


Obtiene o establece el método de compresión del PSD.

Valor: El método de compresión.

**Returns:**
short
### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public void setCompressionMethod(short value)
```


Obtiene o establece el método de compresión del PSD.

Valor: El método de compresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |


**Example: This example demonstrates the use of Aspose.**
Este ejemplo demuestra el uso de Aspose.Imaging for Java API para convertir imágenes al formato PSD. Para lograr este objetivo, este ejemplo carga una imagen existente y luego la guarda nuevamente en formato PSD.
``` java

// Crea una instancia de la clase image y inicialízala con un archivo existente mediante la ruta del archivo.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Crea una instancia de la clase PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Establece el CompressionMethod como RLE.
    // Nota: Otro CompressionMethod compatible es CompressionMethod.RAW [Sin compresión].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Establece el ColorMode a GrayScale.
    // Nota: Otros ColorModes compatibles son ColorModes.Bitmap y ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Guarda la imagen en disco con la configuración de PsdOptions proporcionada.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Obtiene la versión del formato de archivo. Puede ser PSD o PSB.

Valor: La versión del formato de archivo.

**Returns:**
byte - la versión del formato de archivo.
### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Establece la versión del formato de archivo. Puede ser PSD o PSB.

Valor: La versión del formato de archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | la versión del formato de archivo. |

### getColorMode() {#getColorMode--}
```
public short getColorMode()
```


Obtiene o establece el modo de color del PSD.

Valor: El modo de color.

**Returns:**
short
### setColorMode(short value) {#setColorMode-short-}
```
public void setColorMode(short value)
```


Obtiene o establece el modo de color del PSD.

Valor: El modo de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |


**Example: This example demonstrates the use of Aspose.**
Este ejemplo demuestra el uso de Aspose.Imaging for Java API para convertir imágenes al formato PSD. Para lograr este objetivo, este ejemplo carga una imagen existente y luego la guarda nuevamente en formato PSD.
``` java

// Crea una instancia de la clase image y inicialízala con un archivo existente mediante la ruta del archivo.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Crea una instancia de la clase PsdOptions.
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // Establece el CompressionMethod como RLE.
    // Nota: Otro CompressionMethod compatible es CompressionMethod.RAW [Sin compresión].
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // Establece el ColorMode a GrayScale.
    // Nota: Otros ColorModes compatibles son ColorModes.Bitmap y ColorModes.RGB.
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // Guarda la imagen en disco con la configuración de PsdOptions proporcionada.
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getChannelBitsCount() {#getChannelBitsCount--}
```
public short getChannelBitsCount()
```


Obtiene o establece el recuento de bits por canal de color.

Valor: El recuento de bits por canal de color.

**Returns:**
short
### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public void setChannelBitsCount(short value)
```


Obtiene o establece el recuento de bits por canal de color.

Valor: El recuento de bits por canal de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Define un degradado lineal azul-transparente.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Rellena la imagen PNG con el degradado lineal azul-transparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Las siguientes opciones se usarán para guardar la imagen PNG en formato PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // El número de bits por canal.
    saveOptions.setChannelBitsCount((byte) 8);

    // El número de canales. Un canal para cada componente de color R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // El modo de color
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Sin compresión.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // La versión predeterminada es 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // La compresión RLE permite reducir el tamaño de la imagen de salida.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // La salida puede verse así:
    // El tamaño de la imagen PSD con compresión RAW: 40090.
    // El tamaño de la imagen PSD con compresión RLE: 16185.
} finally {
    pngImage.dispose();
}
```

### getChannelsCount() {#getChannelsCount--}
```
public short getChannelsCount()
```


Obtiene el recuento de canales de color.

**Returns:**
short - El recuento de canales de color.
### setChannelsCount(short value) {#setChannelsCount-short-}
```
public void setChannelsCount(short value)
```


Establece el recuento de canales de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short | El recuento de canales de color. |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // Define un degradado lineal azul-transparente.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Rellena la imagen PNG con el degradado lineal azul-transparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Las siguientes opciones se usarán para guardar la imagen PNG en formato PSD.
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // El número de bits por canal.
    saveOptions.setChannelBitsCount((byte) 8);

    // El número de canales. Un canal para cada componente de color R,G,B,A.
    saveOptions.setChannelsCount((short) 4);

    // El modo de color
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // Sin compresión.
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // La versión predeterminada es 6.
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // La compresión RLE permite reducir el tamaño de la imagen de salida.
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // La salida puede verse así:
    // El tamaño de la imagen PSD con compresión RAW: 40090.
    // El tamaño de la imagen PSD con compresión RLE: 16185.
} finally {
    pngImage.dispose();
}
```

### isRemoveGlobalTextEngineResource() {#isRemoveGlobalTextEngineResource--}
```
public boolean isRemoveGlobalTextEngineResource()
```


Obtiene un valor que indica si - Remove the global text engine resource - Se utiliza para algunos archivos PSD con capas de texto, solo en el caso en que no puedan abrirse en Adobe Photoshop después del procesamiento (principalmente relacionado con capas de texto con fuentes ausentes). Después de usar esta opción, el usuario debe realizar lo siguiente en el archivo abierto en Photoshop: Menú "Text" -> "Process absent fonts". Después de esa operación todo el texto volverá a aparecer. Tenga en cuenta que esta operación puede causar algunos cambios finales en el diseño.

**Returns:**
boolean - `true` si [remove global text engine resource]; de lo contrario, `false`.
### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public void setRemoveGlobalTextEngineResource(boolean value)
```


Establece un valor que indica si - Remove the global text engine resource - Se utiliza para algunos archivos PSD con capas de texto, solo en el caso en que no puedan abrirse en Adobe Photoshop después del procesamiento (principalmente relacionado con capas de texto con fuentes ausentes). Después de usar esta opción, el usuario debe realizar lo siguiente en el archivo abierto en Photoshop: Menú "Text" -> "Process absent fonts". Después de esa operación todo el texto volverá a aparecer. Tenga en cuenta que esta operación puede causar algunos cambios finales en el diseño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si [remove global text engine resource]; de lo contrario, `false`. |

### isRefreshImagePreviewData() {#isRefreshImagePreviewData--}
```
public boolean isRefreshImagePreviewData()
```


Obtiene un valor que indica si [refrescar datos de vista previa de la imagen] - opción utilizada para maximizar la compatibilidad con otros visores de imágenes PSD.

**Returns:**
boolean - `true` si [refresh image preview data]; de lo contrario, `false`.
### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public void setRefreshImagePreviewData(boolean value)
```


Establece un valor que indica si [refrescar datos de vista previa de la imagen] - opción utilizada para maximizar la compatibilidad con otros visores de imágenes PSD.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si [refresh image preview data]; de lo contrario, `false`. |

### getVectorizationOptions() {#getVectorizationOptions--}
```
public final PsdVectorizationOptions getVectorizationOptions()
```


Obtiene las opciones de vectorización del PSD.

**Returns:**
[PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) - the PSD vectorization options.
### setVectorizationOptions(PsdVectorizationOptions value) {#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-}
```
public final void setVectorizationOptions(PsdVectorizationOptions value)
```


Establece las opciones de vectorización PSD.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) | las opciones de vectorización de PSD. |

