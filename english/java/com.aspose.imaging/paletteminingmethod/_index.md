---
title: PaletteMiningMethod
second_title: Aspose.Imaging for Java API Reference
description: The image palette mining method
type: docs
weight: 80
url: /java/com.aspose.imaging/paletteminingmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PaletteMiningMethod extends System.Enum
```

The image palette mining method
## Fields

| Field | Description |
| --- | --- |
| [UseCurrentPalette](#UseCurrentPalette) | Use exisiting palette of the image |
| [ColorClustering](#ColorClustering) | The color clustering method |
| [Histogram](#Histogram) | The histogram method |

## Example: The following example shows how to compress a PNG image, using indexed color with best fit palette

``` java

// Loads png image        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // Use indexed color type
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // Use maximal compression
    options.setCompressionLevel(9);
    // Get the closest 8-bit color palette which covers as many pixels as possible, so that a palettized image
    // is almost visually indistinguishable from a non-palletized one.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// The output file size should be significantly reduced
```

### UseCurrentPalette {#UseCurrentPalette}
```
public static final int UseCurrentPalette
```


Use exisiting palette of the image

### ColorClustering {#ColorClustering}
```
public static final int ColorClustering
```


The color clustering method

### Histogram {#Histogram}
```
public static final int Histogram
```


The histogram method

