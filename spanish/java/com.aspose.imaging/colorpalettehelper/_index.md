---
title: "ColorPaletteHelper"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Clase auxiliar para la manipulación de paletas de colores."
type: docs
weight: 29
url: /es/java/com.aspose.imaging/colorpalettehelper/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Clase auxiliar para la manipulación de paletas de colores.
## Métodos

| Método | Descripción |
| --- | --- |
| [createMonochrome()](#createMonochrome--) | Crea una paleta de colores monocromática que contiene solo 2 colores. |
| [create4Bit()](#create4Bit--) | Crea la paleta de colores de 4 bits. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Crea la paleta de escala de grises de 4 bits. |
| [create8Bit()](#create8Bit--) | Crea la paleta de colores de 8 bits. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Crea la paleta de escala de grises de 8 bits. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. |
| [getCloseTransparentImagePalette(RasterImage image, int entriesCount)](#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. |
| [getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.imaging.RasterImage-) | Obtén una paleta de 256 colores uniforme. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.imaging.RasterImage-) | Obtén una paleta de 256 colores, compuesta por los bits superiores de los valores de color de la imagen inicial. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.imaging.IColorPalette-) | Determina si la paleta especificada tiene colores transparentes. |
| [createGrayscale(int bits)](#createGrayscale-int-) | Obtiene la paleta de escala de grises del número de bits especificado. |
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Crea una paleta de colores monocromática que contiene solo 2 colores.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Color palette for monochrome images.
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


Crea la paleta de colores de 4 bits.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Crea la paleta de escala de grises de 4 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| minIsWhite | boolean | si se establece en `true` la paleta comienza con color blanco, de lo contrario comienza con color negro. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Crea la paleta de colores de 8 bits.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Crea la paleta de escala de grises de 8 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| minIsWhite | boolean | si se establece en `true` la paleta comienza con color blanco, de lo contrario comienza con color negro. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8 bit grayscale palette.

**Example: The following example creates a palettized grayscale BMP image and then saves it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.BmpOptions createOptions = new com.aspose.imaging.imageoptions.BmpOptions();

// Guardar en un archivo
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.palette8bit.bmp", false));

// Utiliza 8 bits por píxel para reducir el tamaño de la imagen de salida.
createOptions.setBitsPerPixel(8);

// Establece la paleta de colores de escala de grises estándar de 8 bits que cubre todos los colores de escala de grises.
// Si la imagen procesada contiene solo colores en escala de grises, entonces su versión paletizada
// es visualmente indistinguible de una que no está paletizada.
createOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

// Guardar sin compresión.
// También puedes usar compresión RLE-8 para reducir el tamaño de la imagen de salida.
createOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

// Establece la resolución horizontal y vertical a 96 dpi.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

// Crea una imagen BMP de 100 x 100 px y guárdala en un archivo.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlack(),
            com.aspose.imaging.Color.getWhite());

    // Rellena la imagen con un degradado de escala de grises
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save();
} finally {
    image.dispose();
}
```

### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |
| entriesCount | int | El recuento de entradas deseado. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// Crea una imagen BMP de 100 x 100 px.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // El degradado lineal desde la esquina superior izquierda a la esquina inferior derecha de la imagen.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Rellena toda la imagen con el pincel de degradado lineal.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // Obtén la paleta de colores de 8 bits más cercana que cubra la mayor cantidad posible de píxeles, de modo que una imagen paletizada
    // sea casi visualmente indistinguible de una que no está paletizada.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // La paleta de 8 bits contiene como máximo 256 colores.
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();
    saveOptions.setPalette(palette);
    saveOptions.setBitsPerPixel(8);

    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream, saveOptions);
        System.out.println("The palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }

    stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream);
        System.out.println("The non-palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}

// La salida se ve así:
// El tamaño de la imagen paletizada es 11078 bytes.
// El tamaño de la imagen no paletizada es 40054 bytes.
```

### getCloseTransparentImagePalette(RasterImage image, int entriesCount) {#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseTransparentImagePalette(RasterImage image, int entriesCount)
```


Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |
| entriesCount | int | El recuento de entradas deseado. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)
```


Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. La paleta se optimizará para una mejor calidad de imagen indexada o se tomará "AS IS" cuando se use PaletteMiningMethod.UseCurrentPalette.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |
| entriesCount | int | El recuento de entradas deseado. |
| paletteMiningMethod | int | El método de extracción de paleta. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

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

### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Los límites de la imagen de destino. |
| entriesCount | int | El recuento de entradas deseado. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Los límites de la imagen de destino. |
| entriesCount | int | El recuento de entradas deseado. |
| useImagePalette | boolean | Si está activado, usará su propia paleta de imagen si está disponible |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)
```


Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Los límites de la imagen de destino. |
| entriesCount | int | El recuento de entradas deseado. |
| useImagePalette | boolean | Si está activado, usará su propia paleta de imagen si está disponible |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | El color que debe usarse como color de fondo para el reemplazo de alfa semitransparente. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)
```


Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Los límites de la imagen de destino. |
| entriesCount | int | El recuento de entradas deseado. |
| useImagePalette | boolean | Si está activado, usará su propia paleta de imagen si está disponible |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | El color que debe usarse como color de fondo para el reemplazo de alfa semitransparente. |
| keepTransparency | boolean | Si está activado, considerará los bits del canal alfa de los colores de la imagen. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Obtén una paleta de 256 colores uniforme.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Obtén una paleta de 256 colores, compuesta por los bits superiores de los valores de color de la imagen inicial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.imaging.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Determina si la paleta especificada tiene colores transparentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta. |

**Returns:**
booleano - `true` si la paleta especificada tiene colores transparentes; de lo contrario, `false`.
### createGrayscale(int bits) {#createGrayscale-int-}
```
public static IColorPalette createGrayscale(int bits)
```


Obtiene la paleta en escala de grises del recuento de bits especificado. Los valores de bits permitidos son 1, 2, 4, 8.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bits | int | El recuento de bits. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Grayscale palette.
