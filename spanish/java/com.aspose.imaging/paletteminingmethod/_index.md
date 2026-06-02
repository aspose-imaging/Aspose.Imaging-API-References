---
title: "PaletteMiningMethod"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El método de minería de la paleta de imágenes"
type: docs
weight: 79
url: /es/java/com.aspose.imaging/paletteminingmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PaletteMiningMethod extends System.Enum
```

El método de minería de la paleta de imágenes
## Campos

| Campo | Descripción |
| --- | --- |
| [UseCurrentPalette](#UseCurrentPalette) | Usar la paleta existente de la imagen |
| [ColorClustering](#ColorClustering) | El método de agrupación de colores |
| [Histogram](#Histogram) | El método del histograma |

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

### UseCurrentPalette {#UseCurrentPalette}
```
public static final int UseCurrentPalette
```


Usar la paleta existente de la imagen

### ColorClustering {#ColorClustering}
```
public static final int ColorClustering
```


El método de agrupación de colores

### Histogram {#Histogram}
```
public static final int Histogram
```


El método del histograma

