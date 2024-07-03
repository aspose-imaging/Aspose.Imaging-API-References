---
title: Class MagicWandSettings
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.MagicWand.MagicWandSettings class. A magic wand selection settings class
type: docs
weight: 10730
url: /net/aspose.imaging.magicwand/magicwandsettings/
---
## MagicWandSettings class

A magic wand selection settings class.

```csharp
public class MagicWandSettings
```

## Constructors

| Name | Description |
| --- | --- |
| [MagicWandSettings](magicwandsettings/#constructor)(Point) | Initializes a new instance of the `MagicWandSettings` class. |
| [MagicWandSettings](magicwandsettings/#constructor_1)(int, int) | Initializes a new instance of the `MagicWandSettings` class. |

## Properties

| Name | Description |
| --- | --- |
| [AreaOfInterest](../../aspose.imaging.magicwand/magicwandsettings/areaofinterest/) { get; set; } | Gets or sets the bounds of the area for algorithm work. |
| [ColorCompareMode](../../aspose.imaging.magicwand/magicwandsettings/colorcomparemode/) { get; set; } | Gets or sets the algorithm how colors are compared. |
| [ColorComparisonDelegate](../../aspose.imaging.magicwand/magicwandsettings/colorcomparisondelegate/) { get; set; } | Gets or sets the custom color comparison algorithm if [`ColorCompareMode`](./colorcomparemode/) is set to Custom. |
| [ContiguousMode](../../aspose.imaging.magicwand/magicwandsettings/contiguousmode/) { get; set; } | Gets or sets a value indicating whether magic wand will define only contiguous pixels. |
| [DirectionalMode](../../aspose.imaging.magicwand/magicwandsettings/directionalmode/) { get; set; } | Gets or sets the mode of flood fill search algorithm: four of eight direction search. |
| [Point](../../aspose.imaging.magicwand/magicwandsettings/point/) { get; } | Gets or sets the reference point for algorithm work. |
| [Threshold](../../aspose.imaging.magicwand/magicwandsettings/threshold/) { get; set; } | Gets or sets the tolerance level for pixels color comparison. |

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

* namespace [Aspose.Imaging.MagicWand](../../aspose.imaging.magicwand/)
* assembly [Aspose.Imaging](../../)


