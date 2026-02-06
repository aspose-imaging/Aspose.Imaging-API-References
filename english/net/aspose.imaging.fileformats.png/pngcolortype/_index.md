---
title: Enum PngColorType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Png.PngColorType enum. Represents the PNG image color type
type: docs
weight: 7540
url: /net/aspose.imaging.fileformats.png/pngcolortype/
---
## PngColorType enumeration

Represents the PNG image color type.

```csharp
public enum PngColorType
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Grayscale | `0` | Represents the color type where each pixel is a greyscale sample. |
| Truecolor | `2` | Represents the color type where each pixel is an R,G,B triple. |
| IndexedColor | `3` | Represents the color type where each pixel is a palette index; a PLTE chunk shall appear. |
| GrayscaleWithAlpha | `4` | Represents the color type where each pixel is a greyscale sample followed by an alpha sample. |
| TruecolorWithAlpha | `6` | Represents the color type where each pixel is an R,G,B triple followed by an alpha sample. |

## Examples

The following example shows how to compress a PNG image, using indexed color with best fit palette

```csharp
[C#]

// Loads png image        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Use indexed color type
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Use maximal compression
         CompressionLevel = 9,
      // Get the closest 8-bit color palette which covers as many pixels as possible, so that a palettized image
         // is almost visually indistinguishable from a non-palletized one.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // The output file size should be significantly reduced
```

### See Also

* namespace [Aspose.Imaging.FileFormats.Png](../../aspose.imaging.fileformats.png/)
* assembly [Aspose.Imaging](../../)


