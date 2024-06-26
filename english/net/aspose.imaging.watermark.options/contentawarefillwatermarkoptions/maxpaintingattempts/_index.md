---
title: ContentAwareFillWatermarkOptions.MaxPaintingAttempts
second_title: Aspose.Imaging for .NET API Reference
description: ContentAwareFillWatermarkOptions property. Gets or sets the maximum number of painting attempts. The algorithm will chose the best variant
type: docs
weight: 30
url: /net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/maxpaintingattempts/
---
## ContentAwareFillWatermarkOptions.MaxPaintingAttempts property

Gets or sets the maximum number of painting attempts. The algorithm will chose the best variant.

```csharp
public int MaxPaintingAttempts { get; set; }
```

### Property Value

The maximum number of painting attempts.

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

* class [ContentAwareFillWatermarkOptions](../)
* namespace [Aspose.Imaging.Watermark.Options](../../contentawarefillwatermarkoptions/)
* assembly [Aspose.Imaging](../../../)


