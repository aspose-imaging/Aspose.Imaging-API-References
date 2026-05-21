---
title: "PngOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Crea imágenes raster PNG Portable Network Graphics de alta calidad sin esfuerzo con nuestra API, que ofrece opciones personalizables para niveles de compresión, bits por píxel, profundidades y bits alfa."
type: docs
weight: 38
url: /es/java/com.aspose.imaging.imageoptions/pngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

Crea imágenes raster Portable Network Graphics (PNG) de alta calidad sin esfuerzo con nuestra API, que ofrece opciones personalizables para niveles de compresión, profundidades de bits por píxel y bits alfa. Procesa sin problemas los contenedores de metadatos XMP, garantizando una gestión integral de los metadatos de la imagen, y te permite adaptar las imágenes PNG a tus especificaciones exactas con facilidad.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PngOptions()](#PngOptions--) | Inicializa una nueva instancia de la clase `PngOptions`. |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.imaging.imageoptions.PngOptions-) | Inicializa una nueva instancia de la clase `PngOptions`. |
## Campos

| Campo | Descripción |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | El nivel de compresión predeterminado. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getColorType()](#getColorType--) | Obtiene el tipo del color. |
| [setColorType(int value)](#setColorType-int-) | Establece el tipo del color. |
| [getProgressive()](#getProgressive--) | Obtiene un valor que indica si un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) es progresivo. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | Establece un valor que indica si un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) es progresivo. |
| [getFilterType()](#getFilterType--) | Obtiene el tipo de filtro utilizado durante el proceso de guardado del archivo png. |
| [setFilterType(int value)](#setFilterType-int-) | Establece el tipo de filtro utilizado durante el proceso de guardado del archivo png. |
| [getCompressionLevel()](#getCompressionLevel--) | Obtiene el nivel de compresión del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Establece el nivel de compresión del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [getPngCompressionLevel()](#getPngCompressionLevel--) | Obtiene el nivel de compresión del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [setPngCompressionLevel(int value)](#setPngCompressionLevel-int-) | Establece el nivel de compresión del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [getBitDepth()](#getBitDepth--) | Obtiene los valores de profundidad de bits en el rango de 1, 2, 4, 8, 16. |
| [setBitDepth(byte value)](#setBitDepth-byte-) | Establece los valores de profundidad de bits en el rango de 1, 2, 4, 8, 16. |

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


## Example: The following example shows how to convert a multipage vector image to PNG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.png");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PngOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exporta solo las dos primeras páginas. De hecho, solo se rasterizará una página porque PNG no es un formato multipágina.
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

### PngOptions() {#PngOptions--}
```
public PngOptions()
```


Inicializa una nueva instancia de la clase `PngOptions`.

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.imaging.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


Inicializa una nueva instancia de la clase `PngOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | Las opciones PNG. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


El nivel de compresión predeterminado.

### getColorType() {#getColorType--}
```
public final int getColorType()
```


Obtiene el tipo del color.

Valor: El tipo de color.

**Returns:**
int - el tipo del color.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


Establece el tipo del color.

Valor: El tipo de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el tipo del color. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Carga la imagen png        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Usar tipo de color indexado
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Usar compresión máxima
    options.setCompressionLevel(9);
    // Obtén la paleta de colores de 8 bits más cercana que cubra la mayor cantidad posible de píxeles, de modo que una imagen paletizada
    // sea casi visualmente indistinguible de una que no está paletizada.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// El tamaño del archivo de salida debería reducirse significativamente
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
// También puedes cargar una imagen de cualquier formato compatible desde un archivo o un flujo.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Rellena la imagen con el degradado azul-transparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Utiliza carga progresiva.
    saveOptions.setProgressive(true);

    // Establece la resolución horizontal y vertical a 96 píxeles por pulgada.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Cada píxel es una triple (rojo, verde, azul) seguida de alfa.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Establece el nivel máximo de compresión.
    saveOptions.setCompressionLevel(9);

    // Esta es la mejor compresión, pero el tiempo de ejecución más lento.
    // El filtrado adaptativo significa que el proceso de guardado elegirá el filtro más adecuado para cada fila de datos.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // El número de bits por canal.
    saveOptions.setBitDepth((byte) 8);

    // Guardar en un archivo.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getProgressive() {#getProgressive--}
```
public final boolean getProgressive()
```


Obtiene un valor que indica si un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) es progresivo.

Valor: `` si es progresivo; de lo contrario, ``.

**Returns:**
boolean - un valor que indica si un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) es progresivo.
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public final void setProgressive(boolean value)
```


Establece un valor que indica si un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) es progresivo.

Valor: `` si es progresivo; de lo contrario, ``.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | un valor que indica si un [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) es progresivo. |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Carga la imagen png        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Usar tipo de color indexado
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Usar compresión máxima
    options.setCompressionLevel(9);
    // Obtén la paleta de colores de 8 bits más cercana que cubra la mayor cantidad posible de píxeles, de modo que una imagen paletizada
    // sea casi visualmente indistinguible de una que no está paletizada.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// El tamaño del archivo de salida debería reducirse significativamente
```


**Example: This example shows how to create a PNG image with the specified options, fill it with a linear gradient colors and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();

// El número de bits por canal de color
createOptions.setBitDepth((byte) 8);

// Cada píxel es una triple (rojo, verde, azul) seguida del componente alfa.
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

// El nivel máximo de compresión.
createOptions.setCompressionLevel(9);

// El uso de filtros permite comprimir imágenes tonales continuas de manera más eficaz.
createOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Sub);

// Utilizar carga progresiva
createOptions.setProgressive(true);

// Crear una imagen PNG con parámetros personalizados.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(createOptions, 100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Rellenar la imagen con un degradado semitransparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // Guardar en un archivo.
    pngImage.save(dir + "output.explicitoptions.png");
} finally {
    pngImage.dispose();
}
```

### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


Obtiene el tipo de filtro utilizado durante el proceso de guardado del archivo png.

**Returns:**
int - el tipo de filtro utilizado durante el proceso de guardado del archivo png.
### setFilterType(int value) {#setFilterType-int-}
```
public final void setFilterType(int value)
```


Establece el tipo de filtro utilizado durante el proceso de guardado del archivo png.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el tipo de filtro utilizado durante el proceso de guardado del archivo png. |


**Example: The following example shows how different filter types affect the size of the output PNG image.**

``` java

// Clase auxiliar
class Utils {
    public String getPngFilterTypeString(int filterType) {
        switch (filterType) {
            case com.aspose.imaging.fileformats.png.PngFilterType.None:
                return "None";

            case com.aspose.imaging.fileformats.png.PngFilterType.Up:
                return "Up";

            case com.aspose.imaging.fileformats.png.PngFilterType.Sub:
                return "Sub";

            case com.aspose.imaging.fileformats.png.PngFilterType.Paeth:
                return "Paeth";

            case com.aspose.imaging.fileformats.png.PngFilterType.Avg:
                return "Avg";

            case com.aspose.imaging.fileformats.png.PngFilterType.Adaptive:
                return "Adaptive";

            default:
                throw new IllegalArgumentException("filterType");
        }
    }
}

// Aquí está el ejemplo principal
Utils utils = new Utils();

int[] filterTypes = new int[]
        {
                com.aspose.imaging.fileformats.png.PngFilterType.None,
                com.aspose.imaging.fileformats.png.PngFilterType.Up,
                com.aspose.imaging.fileformats.png.PngFilterType.Sub,
                com.aspose.imaging.fileformats.png.PngFilterType.Paeth,
                com.aspose.imaging.fileformats.png.PngFilterType.Avg,
                com.aspose.imaging.fileformats.png.PngFilterType.Adaptive,
        };

for (int filterType : filterTypes) {
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
    try {
        // Establecer un tipo de filtro
        options.setFilterType(filterType);

        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            image.save(stream, options);
            System.out.printf("The filter type is %s, the output image size is %s bytes.", utils.getPngFilterTypeString(filterType), stream.size());
        } finally {
            stream.close();
        }
    } finally {
        image.dispose();
    }
}

//La salida puede verse así:
//El tipo de filtro es None, el tamaño de la imagen de salida es 116845 bytes.
//El tipo de filtro es Up, el tamaño de la imagen de salida es 86360 bytes.
//El tipo de filtro es Sub, el tamaño de la imagen de salida es 94907 bytes.
//El tipo de filtro es Paeth, el tamaño de la imagen de salida es 86403 bytes.
//El tipo de filtro es Avg, el tamaño de la imagen de salida es 89956 bytes.
//El tipo de filtro es Adaptive, el tamaño de la imagen de salida es 97248 bytes.
```

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Obtiene el nivel de compresión del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Returns:**
int - el nivel de compresión del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Establece el nivel de compresión del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | el nivel de compresión del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |


**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// Carga la imagen png        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Usar tipo de color indexado
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Usar compresión máxima
    options.setCompressionLevel(9);
    // Obtén la paleta de colores de 8 bits más cercana que cubra la mayor cantidad posible de píxeles, de modo que una imagen paletizada
    // sea casi visualmente indistinguible de una que no está paletizada.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// El tamaño del archivo de salida debería reducirse significativamente
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
// También puedes cargar una imagen de cualquier formato compatible desde un archivo o un flujo.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Rellena la imagen con el degradado azul-transparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Utiliza carga progresiva.
    saveOptions.setProgressive(true);

    // Establece la resolución horizontal y vertical a 96 píxeles por pulgada.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Cada píxel es una triple (rojo, verde, azul) seguida de alfa.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Establece el nivel máximo de compresión.
    saveOptions.setCompressionLevel(9);

    // Esta es la mejor compresión, pero el tiempo de ejecución más lento.
    // El filtrado adaptativo significa que el proceso de guardado elegirá el filtro más adecuado para cada fila de datos.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // El número de bits por canal.
    saveOptions.setBitDepth((byte) 8);

    // Guardar en un archivo.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getPngCompressionLevel() {#getPngCompressionLevel--}
```
public final int getPngCompressionLevel()
```


Obtiene el nivel de compresión del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Returns:**
int - el nivel de compresión del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).
### setPngCompressionLevel(int value) {#setPngCompressionLevel-int-}
```
public final void setPngCompressionLevel(int value)
```


Establece el nivel de compresión del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | el nivel de compresión del [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |

### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Obtiene los valores de profundidad de bits en el rango de 1, 2, 4, 8, 16.

Tenga en cuenta los siguientes límites:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Returns:**
byte - los valores de profundidad de bits en el rango de 1, 2, 4, 8, 16.
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public final void setBitDepth(byte value)
```


Establece los valores de profundidad de bits en el rango de 1, 2, 4, 8, 16.

Tenga en cuenta los siguientes límites:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | los valores de profundidad de bits en el rango de 1, 2, 4, 8, 16. |


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// Crea una imagen PNG de 100x100 px.
// También puedes cargar una imagen de cualquier formato compatible desde un archivo o un flujo.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Rellena la imagen con el degradado azul-transparente.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Utiliza carga progresiva.
    saveOptions.setProgressive(true);

    // Establece la resolución horizontal y vertical a 96 píxeles por pulgada.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // Cada píxel es una triple (rojo, verde, azul) seguida de alfa.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // Establece el nivel máximo de compresión.
    saveOptions.setCompressionLevel(9);

    // Esta es la mejor compresión, pero el tiempo de ejecución más lento.
    // El filtrado adaptativo significa que el proceso de guardado elegirá el filtro más adecuado para cada fila de datos.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // El número de bits por canal.
    saveOptions.setBitDepth((byte) 8);

    // Guardar en un archivo.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

