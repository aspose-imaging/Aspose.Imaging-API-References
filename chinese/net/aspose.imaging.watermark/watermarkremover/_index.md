---
title: "WatermarkRemover 类"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Watermark.WatermarkRemover 类。此类用于操作水印"
type: docs
weight: 11860
url: /zh/net/aspose.imaging.watermark/watermarkremover/
---
## WatermarkRemover class

用于操作 Watermark 的类。

```csharp
public static class WatermarkRemover
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [PaintOver](../../aspose.imaging.watermark/watermarkremover/paintover/)(RasterImage, WatermarkOptions) | 从光栅图像中移除水印。 |

## 示例

示例展示了如何使用带 Telea 算法的 Graphics Path 从图像中移除任意对象。

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

示例展示了如何使用带 Content Aware fill 算法的 Graphics Path 从图像中移除任意对象。

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

### 另请参见

* namespace [Aspose.Imaging.Watermark](../../aspose.imaging.watermark/)
* assembly [Aspose.Imaging](../../)


