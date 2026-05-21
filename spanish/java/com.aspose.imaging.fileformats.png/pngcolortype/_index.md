---
title: "PngColorType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa el tipo de color de la imagen PNG."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.png/pngcolortype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PngColorType extends System.Enum
```

Representa el tipo de color de la imagen PNG.
## Campos

| Campo | Descripción |
| --- | --- |
| [Grayscale](#Grayscale) | Representa el tipo de color donde cada píxel es una muestra en escala de grises. |
| [Truecolor](#Truecolor) | Representa el tipo de color donde cada píxel es una triple R,G,B. |
| [IndexedColor](#IndexedColor) | Representa el tipo de color donde cada píxel es un índice de paleta; debe aparecer un bloque PLTE. |
| [GrayscaleWithAlpha](#GrayscaleWithAlpha) | Representa el tipo de color donde cada píxel es una muestra en escala de grises seguida de una muestra alfa. |
| [TruecolorWithAlpha](#TruecolorWithAlpha) | Representa el tipo de color donde cada píxel es una triple R,G,B seguida de una muestra alfa. |

## Example: The following example shows how to compress a PNG image, using indexed color with best fit palette

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

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Representa el tipo de color donde cada píxel es una muestra en escala de grises.

### Truecolor {#Truecolor}
```
public static final int Truecolor
```


Representa el tipo de color donde cada píxel es una triple R,G,B.

### IndexedColor {#IndexedColor}
```
public static final int IndexedColor
```


Representa el tipo de color donde cada píxel es un índice de paleta; debe aparecer un bloque PLTE.

### GrayscaleWithAlpha {#GrayscaleWithAlpha}
```
public static final int GrayscaleWithAlpha
```


Representa el tipo de color donde cada píxel es una muestra en escala de grises seguida de una muestra alfa.

### TruecolorWithAlpha {#TruecolorWithAlpha}
```
public static final int TruecolorWithAlpha
```


Representa el tipo de color donde cada píxel es una triple R,G,B seguida de una muestra alfa.

