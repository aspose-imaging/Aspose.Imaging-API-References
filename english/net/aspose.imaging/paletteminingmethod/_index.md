---
title: Enum PaletteMiningMethod
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.PaletteMiningMethod enum. The image palette mining method
type: docs
weight: 11230
url: /net/aspose.imaging/paletteminingmethod/
---
## PaletteMiningMethod enumeration

The image palette mining method

```csharp
public enum PaletteMiningMethod
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| UseCurrentPalette | `0` | Use exisiting palette of the image |
| ColorClustering | `1` | The color clustering method |
| Histogram | `2` | The histogram method |

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

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


