---
title: Class MagicWandTool
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.MagicWand.MagicWandTool class. The class for magic wand algorithm main logic
type: docs
weight: 10860
url: /net/aspose.imaging.magicwand/magicwandtool/
---
## MagicWandTool class

The class for magic wand algorithm main logic.

```csharp
public class MagicWandTool : IPartialArgb32PixelLoader
```

## Methods

| Name | Description |
| --- | --- |
| [Process](../../aspose.imaging.magicwand/magicwandtool/process/)(Rectangle, int[], Point, Point) | Processes the loaded pixels . |
| static [Select](../../aspose.imaging.magicwand/magicwandtool/select/)(RasterImage, MagicWandSettings) | Creates a new [`ImageBitMask`](../../aspose.imaging.magicwand.imagemasks/imagebitmask/) based on [`MagicWandSettings`](../magicwandsettings/) and source [`RasterImage`](../../aspose.imaging/rasterimage/). |

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

The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, substract).

```csharp
[C#]

var imageFilePath = "input.png"; 
using (RasterImage image = (RasterImage)Image.Load(inputFilePath))
{
    // Create a new mask using magic wand tool based on tone and color of pixel (845, 128)
    MagicWandTool.Select(image, new MagicWandSettings(845, 128))
        // Union the existing mask with the specified one created by magic wand tool
        .Union(new MagicWandSettings(416, 387))
        // Invert the existing mask
        .Invert()
        // Subtract the specified mask created by magic wand tool with specified threshold from the existing one 
        .Subtract(new MagicWandSettings(1482, 346) { Threshold = 69 })
        // Subtract four specified rectangle masks from the existing mask one by one
        .Subtract(new RectangleMask(0, 0, 800, 150))
        .Subtract(new RectangleMask(0, 380, 600, 220))
        .Subtract(new RectangleMask(930, 520, 110, 40))
        .Subtract(new RectangleMask(1370, 400, 120, 200))
        // Feather mask with specified settings
        .GetFeathered(new FeatheringSettings() { Size = 3 })
        // Apply mask to the image
        .Apply();
        
    // Save image
    image.Save(outputFilePath);
}
```

### See Also

* interface [IPartialArgb32PixelLoader](../../aspose.imaging/ipartialargb32pixelloader/)
* namespace [Aspose.Imaging.MagicWand](../../aspose.imaging.magicwand/)
* assembly [Aspose.Imaging](../../)


