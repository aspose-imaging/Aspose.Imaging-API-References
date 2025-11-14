---
title: Class WatermarkRemover
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Watermark.WatermarkRemover class. The class intended for manipulation the watermark
type: docs
weight: 11790
url: /net/aspose.imaging.watermark/watermarkremover/
---
## WatermarkRemover class

The class intended for manipulation the watermark.

```csharp
public static class WatermarkRemover
```

## Methods

| Name | Description |
| --- | --- |
| static [PaintOver](../../aspose.imaging.watermark/watermarkremover/paintover/)(RasterImage, WatermarkOptions) | Remove the watermark from the raster image. |

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

* namespace [Aspose.Imaging.Watermark](../../aspose.imaging.watermark/)
* assembly [Aspose.Imaging](../../)


