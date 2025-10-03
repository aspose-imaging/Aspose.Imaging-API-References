---
title: Class FeatheringSettings
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.MagicWand.ImageMasks.FeatheringSettings class. A feathering settings class
type: docs
weight: 10760
url: /net/aspose.imaging.magicwand.imagemasks/featheringsettings/
---
## FeatheringSettings class

A feathering settings class.

```csharp
public class FeatheringSettings
```

## Constructors

| Name | Description |
| --- | --- |
| [FeatheringSettings](featheringsettings/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Mode](../../aspose.imaging.magicwand.imagemasks/featheringsettings/mode/) { get; set; } | Gets or sets the feathering algorithm mode. |
| [Size](../../aspose.imaging.magicwand.imagemasks/featheringsettings/size/) { get; set; } | Gets or sets the feathering size. |

## Examples

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

* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../aspose.imaging.magicwand.imagemasks/)
* assembly [Aspose.Imaging](../../)


