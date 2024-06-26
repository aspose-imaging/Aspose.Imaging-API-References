---
title: ImageMask.Apply
second_title: Aspose.Imaging for .NET API Reference
description: ImageMask method. Applies current mask to the RasterImage source if exists
type: docs
weight: 70
url: /net/aspose.imaging.magicwand.imagemasks/imagemask/apply/
---
## ImageMask.Apply method

Applies current mask to the [`RasterImage`](../../../aspose.imaging/rasterimage/) source, if exists.

```csharp
public void Apply()
```

### Exceptions

| exception | condition |
| --- | --- |
| NullReferenceException | Thrown when the source image is not defined. |

## Examples

The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

```csharp
[C#]

var imageFilePath = "input.png"; 
using (RasterImage image = (RasterImage)Image.Load(inputFilePath))
{
    // Create a new mask using magic wand tool based on tone and color of pixel (120, 100) with custom threshold equal to 150
    MagicWandTool
        .Select(image, new MagicWandSettings(120, 100) { Threshold = 150 })
        // Apply mask to the image
        .Apply();

    // Save image with forced transparency color type option
    image.Save(outputFilePath, new ImageOptions.PngOptions()
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### See Also

* class [ImageMask](../)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../imagemask/)
* assembly [Aspose.Imaging](../../../)


