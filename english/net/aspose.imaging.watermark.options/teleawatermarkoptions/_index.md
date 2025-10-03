---
title: Class TeleaWatermarkOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Watermark.Options.TeleaWatermarkOptions class. The common Telea Algorithm options
type: docs
weight: 11750
url: /net/aspose.imaging.watermark.options/teleawatermarkoptions/
---
## TeleaWatermarkOptions class

The common Telea Algorithm options.

```csharp
public class TeleaWatermarkOptions : WatermarkOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TeleaWatermarkOptions](teleawatermarkoptions/#constructor)(GraphicsPath) | Initializes a new instance of the `TeleaWatermarkOptions` class. |
| [TeleaWatermarkOptions](teleawatermarkoptions/#constructor_1)(Point[]) | Initializes a new instance of the `TeleaWatermarkOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [GraphicsPathMask](../../aspose.imaging.watermark.options/watermarkoptions/graphicspathmask/) { get; set; } | Gets or sets the mask. |
| [HalfPatchSize](../../aspose.imaging.watermark.options/teleawatermarkoptions/halfpatchsize/) { get; set; } | Gets or sets the half patch size. |
| [Mask](../../aspose.imaging.watermark.options/watermarkoptions/mask/) { get; set; } | Gets or sets the mask. |
| [PrecalculationProgressEventHandler](../../aspose.imaging.watermark.options/watermarkoptions/precalculationprogresseventhandler/) { get; set; } | Gets or sets the default points pre-calculation process progress event handler. |

## Examples

The example shows how to remove any object from the image using Graphics Path with Telea algorithm.

```csharp
[C#]

var imageFilePath = "ball.png"; 
using (var image = Image.Load(imageFilePath))
{
    var pngImage = (PngImage)image;

    var mask = new GraphicsPath();
    var firstFigure = new Figure();
    firstFigure.AddShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.AddFigure(firstFigure);

    var options = new TeleaWatermarkOptions(mask);

    var result = WatermarkRemover.PaintOver(pngImage, options);

    result.Save(outputPath);
}
```

### See Also

* class [WatermarkOptions](../watermarkoptions/)
* namespace [Aspose.Imaging.Watermark.Options](../../aspose.imaging.watermark.options/)
* assembly [Aspose.Imaging](../../)


