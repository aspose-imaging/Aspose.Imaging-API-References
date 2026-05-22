---
title: "ContentAwareFillWatermarkOptions.MaxPaintingAttempts"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ContentAwareFillWatermarkOptions 属性。获取或设置最大绘制尝试次数。算法将选择最佳变体"
type: docs
weight: 30
url: /zh/net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/maxpaintingattempts/
---
## ContentAwareFillWatermarkOptions.MaxPaintingAttempts property

获取或设置最大绘制尝试次数。算法将选择最佳变体。

```csharp
public int MaxPaintingAttempts { get; set; }
```

### Property Value

最大绘制尝试次数。

## 示例

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

* class [ContentAwareFillWatermarkOptions](../)
* namespace [Aspose.Imaging.Watermark.Options](../../contentawarefillwatermarkoptions/)
* assembly [Aspose.Imaging](../../../)


