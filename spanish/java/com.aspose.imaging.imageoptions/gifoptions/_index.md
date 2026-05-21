---
title: "GifOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La API para la creación de archivos de imagen raster GIF del Formato de Intercambio Gráfico ofrece a los desarrolladores opciones integrales para generar imágenes GIF con control preciso."
type: docs
weight: 22
url: /es/java/com.aspose.imaging.imageoptions/gifoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

La API para la creación de archivos de imagen raster del Formato de Intercambio Gráfico (GIF) ofrece a los desarrolladores opciones integrales para generar imágenes GIF con control preciso. Con funciones para establecer el color de fondo, la paleta de colores, la resolución, el tipo entrelazado, el color transparente, el contenedor de metadatos XMP y la compresión de imágenes, esta API garantiza flexibilidad y eficiencia al crear GIFs optimizados y visualmente atractivos adaptados a los requisitos específicos de la aplicación.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GifOptions()](#GifOptions--) | Inicializa una nueva instancia de la clase `GifOptions`. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.imaging.imageoptions.GifOptions-) | Inicializa una nueva instancia de la clase `GifOptions`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
| [getLoopsCount()](#getLoopsCount--) | Obtiene el recuento de bucles (Predeterminado 1 bucle) |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Establece el recuento de bucles (Predeterminado 1 bucle) |
| [getColorResolution()](#getColorResolution--) | Obtiene o establece la resolución de color GIF. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | Obtiene o establece la resolución de color GIF. |
| [isPaletteSorted()](#isPaletteSorted--) | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Obtiene o establece la relación de aspecto de píxel GIF. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Obtiene o establece la relación de aspecto de píxel GIF. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Obtiene o establece el índice de color de fondo GIF. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Obtiene o establece el índice de color de fondo GIF. |
| [hasTrailer()](#hasTrailer--) | Obtiene o establece un valor que indica si el GIF tiene tráiler. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Obtiene o establece un valor que indica si el GIF tiene tráiler. |
| [getInterlaced()](#getInterlaced--) | Verdadero si la imagen debe estar entrelazada. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Verdadero si la imagen debe estar entrelazada. |
| [getMaxDiff()](#getMaxDiff--) | Obtiene o establece la diferencia máxima de píxel permitida. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | Obtiene o establece la diferencia máxima de píxel permitida. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene el color de fondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Establece el color de fondo. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtiene un valor que indica si una imagen GIF tiene color transparente. |
| [setTransparentColor(Boolean value)](#setTransparentColor-java.lang.Boolean-) | Establece un valor que indica si una imagen GIF tiene color transparente. |

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


## Example: The following example shows how to convert a multipage vector image to GIF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.gif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.GifOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exporta solo las dos primeras páginas. Estas páginas se presentarán como fotogramas animados en el GIF de salida.
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

### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Inicializa una nueva instancia de la clase `GifOptions`.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.imaging.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


Inicializa una nueva instancia de la clase `GifOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.imaging.imageoptions/gifoptions) | Las opciones de GIF. |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Obtiene o establece un valor que indica si se aplica la corrección de paleta.

**Returns:**
booleano - `true` si se aplica la corrección de paleta; de lo contrario, `false`.

La corrección de paleta significa que siempre que una imagen se exporta a GIF, los colores de la imagen original serán analizados para crear la paleta que mejor coincida (en caso de que la Paleta de la imagen no exista o no esté especificada en las opciones). El proceso de análisis lleva algo de tiempo, sin embargo la imagen resultante tendrá la paleta de colores que mejor coincida y el resultado será visualmente mejor.
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Obtiene o establece un valor que indica si se aplica la corrección de paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | `true` si se aplica la corrección de paleta; de lo contrario, `false`. |

La corrección de paleta significa que siempre que una imagen se exporta a GIF, los colores de la imagen original serán analizados para crear la paleta que mejor coincida (en caso de que la Paleta de la imagen no exista o no esté especificada en las opciones). El proceso de análisis lleva algo de tiempo, sin embargo la imagen resultante tendrá la paleta de colores que mejor coincida y el resultado será visualmente mejor. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Rellena toda la imagen con el degradado azul‑amarillo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // El número de bits necesarios para almacenar un color, menos 1.
    saveOptions.setColorResolution((byte) 7);

    // La corrección de paleta significa que siempre que una imagen se exporta a GIF, los colores de la imagen original serán analizados
    // para crear la paleta que mejor coincida (en caso de que la Paleta de la imagen no exista o no esté especificada en las opciones)
    saveOptions.setDoPaletteCorrection(true);

    // Carga una imagen GIF de forma progresiva.
    // Un GIF entrelazado no muestra sus líneas de escaneo linealmente de arriba a abajo, sino que las reordena
    // de modo que el contenido del GIF se vuelve visible incluso antes de que termine de cargarse.
    saveOptions.setInterlaced(true);

    // Guardar como un GIF sin pérdida.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Establece la diferencia máxima de píxeles permitida. Si es mayor que cero, se utilizará compresión con pérdida.
    // El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada.
    saveOptions.setMaxDiff(80);

    // Guardar como un GIF con pérdida.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//La salida puede verse así:
//El tamaño del GIF sin pérdida: 212816 bytes.
//El tamaño del GIF con pérdida: 89726 bytes.
```

### getLoopsCount() {#getLoopsCount--}
```
public final int getLoopsCount()
```


Obtiene el recuento de bucles (Predeterminado 1 bucle)

Valor: El recuento de bucles.

**Returns:**
int - el recuento de bucles (Predeterminado 1 bucle)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public final void setLoopsCount(int value)
```


Establece el recuento de bucles (Predeterminado 1 bucle)

Valor: El recuento de bucles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el recuento de bucles (Predeterminado 1 bucle) |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


Obtiene o establece la resolución de color GIF.

**Returns:**
byte - La resolución de color.

Resolución de color - Número de bits por color primario disponible en la imagen original, menos 1. Este valor representa el tamaño de toda la paleta de la que se seleccionaron los colores del gráfico, no el número de colores realmente usados en el gráfico. Por ejemplo, si el valor en este campo es 3, entonces la paleta de la imagen original tenía 4 bits por color primario disponibles para crear la imagen. Este valor debe establecerse para indicar la riqueza de la paleta original, incluso si no todos los colores de la paleta completa están disponibles en la máquina fuente.
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


Obtiene o establece la resolución de color GIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | byte | La resolución de color. |

Resolución de color - Número de bits por color primario disponible en la imagen original, menos 1. Este valor representa el tamaño de toda la paleta de la que se seleccionaron los colores del gráfico, no el número de colores realmente usados en el gráfico. Por ejemplo, si el valor en este campo es 3, entonces la paleta de la imagen original tenía 4 bits por color primario disponibles para crear la imagen. Este valor debe establecerse para indicar la riqueza de la paleta original, incluso si no todos los colores de la paleta completa están disponibles en la máquina fuente. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Rellena toda la imagen con el degradado azul‑amarillo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // El número de bits necesarios para almacenar un color, menos 1.
    saveOptions.setColorResolution((byte) 7);

    // La corrección de paleta significa que siempre que una imagen se exporta a GIF, los colores de la imagen original serán analizados
    // para crear la paleta que mejor coincida (en caso de que la Paleta de la imagen no exista o no esté especificada en las opciones)
    saveOptions.setDoPaletteCorrection(true);

    // Carga una imagen GIF de forma progresiva.
    // Un GIF entrelazado no muestra sus líneas de escaneo linealmente de arriba a abajo, sino que las reordena
    // de modo que el contenido del GIF se vuelve visible incluso antes de que termine de cargarse.
    saveOptions.setInterlaced(true);

    // Guardar como un GIF sin pérdida.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Establece la diferencia máxima de píxeles permitida. Si es mayor que cero, se utilizará compresión con pérdida.
    // El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada.
    saveOptions.setMaxDiff(80);

    // Guardar como un GIF con pérdida.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//La salida puede verse así:
//El tamaño del GIF sin pérdida: 212816 bytes.
//El tamaño del GIF con pérdida: 89726 bytes.
```

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas.

**Returns:**
boolean - `true` si las entradas de la paleta están ordenadas; de lo contrario, `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si las entradas de la paleta están ordenadas; de lo contrario, `false`. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Obtiene o establece la relación de aspecto de píxel GIF.

Relación de aspecto del píxel - Factor utilizado para calcular una aproximación de la relación de aspecto del píxel en la imagen original. Si el valor del campo no es 0, esta aproximación de la relación de aspecto se calcula según la fórmula: Relación de aspecto = (Relación de aspecto del píxel + 15) / 64 La Relación de aspecto del píxel se define como el cociente del ancho del píxel sobre su altura. El rango de valores en este campo permite especificar el píxel más ancho de 4:1 hasta el píxel más alto de 1:4 en incrementos de 1/64. Valores: 0 - No se proporciona información de relación de aspecto. 1..255 - Valor usado en el cálculo.

**Returns:**
byte - La relación de aspecto del píxel GIF.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Obtiene o establece la relación de aspecto de píxel GIF.

Relación de aspecto del píxel - Factor utilizado para calcular una aproximación de la relación de aspecto del píxel en la imagen original. Si el valor del campo no es 0, esta aproximación de la relación de aspecto se calcula según la fórmula: Relación de aspecto = (Relación de aspecto del píxel + 15) / 64 La Relación de aspecto del píxel se define como el cociente del ancho del píxel sobre su altura. El rango de valores en este campo permite especificar el píxel más ancho de 4:1 hasta el píxel más alto de 1:4 en incrementos de 1/64. Valores: 0 - No se proporciona información de relación de aspecto. 1..255 - Valor usado en el cálculo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | La relación de aspecto del píxel GIF. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Obtiene o establece el índice de color de fondo GIF.

**Returns:**
byte - El índice de color de fondo GIF.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Obtiene o establece el índice de color de fondo GIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | El índice de color de fondo GIF. |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Obtiene o establece un valor que indica si el GIF tiene tráiler.

**Returns:**
boolean - `true` si el GIF tiene tráiler; de lo contrario, `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Obtiene o establece un valor que indica si el GIF tiene tráiler.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si el GIF tiene tráiler; de lo contrario, `false`. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Verdadero si la imagen debe estar entrelazada.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Verdadero si la imagen debe estar entrelazada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Rellena toda la imagen con el degradado azul‑amarillo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // El número de bits necesarios para almacenar un color, menos 1.
    saveOptions.setColorResolution((byte) 7);

    // La corrección de paleta significa que siempre que una imagen se exporta a GIF, los colores de la imagen original serán analizados
    // para crear la paleta que mejor coincida (en caso de que la Paleta de la imagen no exista o no esté especificada en las opciones)
    saveOptions.setDoPaletteCorrection(true);

    // Carga una imagen GIF de forma progresiva.
    // Un GIF entrelazado no muestra sus líneas de escaneo linealmente de arriba a abajo, sino que las reordena
    // de modo que el contenido del GIF se vuelve visible incluso antes de que termine de cargarse.
    saveOptions.setInterlaced(true);

    // Guardar como un GIF sin pérdida.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Establece la diferencia máxima de píxeles permitida. Si es mayor que cero, se utilizará compresión con pérdida.
    // El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada.
    saveOptions.setMaxDiff(80);

    // Guardar como un GIF con pérdida.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//La salida puede verse así:
//El tamaño del GIF sin pérdida: 212816 bytes.
//El tamaño del GIF con pérdida: 89726 bytes.
```

### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Obtiene o establece la diferencia máxima de píxeles permitida. Si es mayor que cero, se utilizará compresión con pérdida. El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada. Funciona mejor cuando solo se introduce poca pérdida, y debido a la limitación del algoritmo de compresión, niveles de pérdida muy altos no proporcionarán tanto beneficio. El rango de valores permitidos es [0, 1000].

**Returns:**
int - El rango de valores permitidos.
### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Obtiene o establece la diferencia máxima de píxeles permitida. Si es mayor que cero, se utilizará compresión con pérdida. El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada. Funciona mejor cuando solo se introduce poca pérdida, y debido a la limitación del algoritmo de compresión, niveles de pérdida muy altos no proporcionarán tanto beneficio. El rango de valores permitidos es [0, 1000].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El rango de valores permitidos. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Rellena toda la imagen con el degradado azul‑amarillo.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // El número de bits necesarios para almacenar un color, menos 1.
    saveOptions.setColorResolution((byte) 7);

    // La corrección de paleta significa que siempre que una imagen se exporta a GIF, los colores de la imagen original serán analizados
    // para crear la paleta que mejor coincida (en caso de que la Paleta de la imagen no exista o no esté especificada en las opciones)
    saveOptions.setDoPaletteCorrection(true);

    // Carga una imagen GIF de forma progresiva.
    // Un GIF entrelazado no muestra sus líneas de escaneo linealmente de arriba a abajo, sino que las reordena
    // de modo que el contenido del GIF se vuelve visible incluso antes de que termine de cargarse.
    saveOptions.setInterlaced(true);

    // Guardar como un GIF sin pérdida.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // Establece la diferencia máxima de píxeles permitida. Si es mayor que cero, se utilizará compresión con pérdida.
    // El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada.
    saveOptions.setMaxDiff(80);

    // Guardar como un GIF con pérdida.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//La salida puede verse así:
//El tamaño del GIF sin pérdida: 212816 bytes.
//El tamaño del GIF con pérdida: 89726 bytes.
```

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Obtiene el color de fondo.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public final void setBackgroundColor(Color value)
```


Establece el color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | el color de fondo. |

### hasTransparentColor() {#hasTransparentColor--}
```
public final Boolean hasTransparentColor()
```


Obtiene un valor que indica si una imagen GIF tiene color transparente. Si el valor de retorno es `null`, esta propiedad es sobrescrita por el contexto de la imagen fuente.

**Returns:**
java.lang.Boolean - un valor que indica si una imagen GIF tiene color transparente.
### setTransparentColor(Boolean value) {#setTransparentColor-java.lang.Boolean-}
```
public final void setTransparentColor(Boolean value)
```


Establece un valor que indica si una imagen GIF tiene color transparente. Si el valor de retorno es `null`, esta propiedad es sobrescrita por el contexto de la imagen fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Boolean | un valor que indica si una imagen GIF tiene color transparente. |

