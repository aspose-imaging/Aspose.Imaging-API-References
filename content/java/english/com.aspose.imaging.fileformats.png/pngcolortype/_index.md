---
title: PngColorType
second_title: Aspose.Imaging for Java API Reference
description: Represents the PNG image color type.
type: docs
weight: 10
url: /com.aspose.imaging.fileformats.png/pngcolortype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PngColorType extends System.Enum
```

Represents the PNG image color type.
## Fields

| Field | Description |
| --- | --- |
| [Grayscale](#Grayscale) | Represents the color type where each pixel is a greyscale sample. |
| [Truecolor](#Truecolor) | Represents the color type where each pixel is an R,G,B triple. |
| [IndexedColor](#IndexedColor) | Represents the color type where each pixel is a palette index; a PLTE chunk shall appear. |
| [GrayscaleWithAlpha](#GrayscaleWithAlpha) | Represents the color type where each pixel is a grayscale sample followed by an alpha sample. |
| [TruecolorWithAlpha](#TruecolorWithAlpha) | Represents the color type where each pixel is an R,G,B triple followed by an alpha sample. |

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

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


Represents the color type where each pixel is a greyscale sample.

### Truecolor {#Truecolor}
```
public static final int Truecolor
```


Represents the color type where each pixel is an R,G,B triple.

### IndexedColor {#IndexedColor}
```
public static final int IndexedColor
```


Represents the color type where each pixel is a palette index; a PLTE chunk shall appear.

### GrayscaleWithAlpha {#GrayscaleWithAlpha}
```
public static final int GrayscaleWithAlpha
```


Represents the color type where each pixel is a grayscale sample followed by an alpha sample.

### TruecolorWithAlpha {#TruecolorWithAlpha}
```
public static final int TruecolorWithAlpha
```


Represents the color type where each pixel is an R,G,B triple followed by an alpha sample.

