---
title: Class ContentAwareFillWatermarkOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Watermark.Options.ContentAwareFillWatermarkOptions class. The common Content Aware Fill Algorithm options
type: docs
weight: 11740
url: /net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---
## ContentAwareFillWatermarkOptions class

The common Content Aware Fill Algorithm options.

```csharp
public class ContentAwareFillWatermarkOptions : WatermarkOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ContentAwareFillWatermarkOptions](contentawarefillwatermarkoptions/#constructor)(GraphicsPath) | Initializes a new instance of the `ContentAwareFillWatermarkOptions` class. |
| [ContentAwareFillWatermarkOptions](contentawarefillwatermarkoptions/#constructor_1)(Point[]) | Initializes a new instance of the `ContentAwareFillWatermarkOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [GraphicsPathMask](../../aspose.imaging.watermark.options/watermarkoptions/graphicspathmask/) { get; set; } | Gets or sets the mask. |
| [InterestArea](../../aspose.imaging.watermark.options/contentawarefillwatermarkoptions/interestarea/) { get; set; } | Gets or sets the area to take patches. |
| [Mask](../../aspose.imaging.watermark.options/watermarkoptions/mask/) { get; set; } | Gets or sets the mask. |
| [MaxPaintingAttempts](../../aspose.imaging.watermark.options/contentawarefillwatermarkoptions/maxpaintingattempts/) { get; set; } | Gets or sets the maximum number of painting attempts. The algorithm will chose the best variant. |
| [PatchSize](../../aspose.imaging.watermark.options/contentawarefillwatermarkoptions/patchsize/) { get; set; } | Gets or sets the patch size (should be odd). |
| [PrecalculationProgressEventHandler](../../aspose.imaging.watermark.options/watermarkoptions/precalculationprogresseventhandler/) { get; set; } | Gets or sets the default points pre-calculation process progress event handler. |

## Examples

The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

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

    var options = new ContentAwareFillWatermarkOptions(mask) 
    { 
        MaxPaintingAttempts = 4
    };

    var result = WatermarkRemover.PaintOver(pngImage, options);

    result.Save(outputPath);
}
```

### See Also

* class [WatermarkOptions](../watermarkoptions/)
* namespace [Aspose.Imaging.Watermark.Options](../../aspose.imaging.watermark.options/)
* assembly [Aspose.Imaging](../../)


