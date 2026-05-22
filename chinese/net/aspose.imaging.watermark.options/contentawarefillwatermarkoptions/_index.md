---
title: "类 ContentAwareFillWatermarkOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Watermark.Options.ContentAwareFillWatermarkOptions 类。通用内容感知填充算法选项"
type: docs
weight: 11830
url: /zh/net/aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---
## ContentAwareFillWatermarkOptions class

通用内容感知填充算法选项。

```csharp
public class ContentAwareFillWatermarkOptions : WatermarkOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ContentAwareFillWatermarkOptions](contentawarefillwatermarkoptions/#constructor)(GraphicsPath) | 初始化 `ContentAwareFillWatermarkOptions` 类的新实例。 |
| [ContentAwareFillWatermarkOptions](contentawarefillwatermarkoptions/#constructor_1)(Point[]) | 初始化 `ContentAwareFillWatermarkOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [GraphicsPathMask](../../aspose.imaging.watermark.options/watermarkoptions/graphicspathmask/) { get; set; } | 获取或设置掩码。 |
| [InterestArea](../../aspose.imaging.watermark.options/contentawarefillwatermarkoptions/interestarea/) { get; set; } | 获取或设置用于获取补丁的区域。 |
| [Mask](../../aspose.imaging.watermark.options/watermarkoptions/mask/) { get; set; } | 获取或设置掩码。 |
| [MaxPaintingAttempts](../../aspose.imaging.watermark.options/contentawarefillwatermarkoptions/maxpaintingattempts/) { get; set; } | 获取或设置最大绘制尝试次数。算法将选择最佳变体。 |
| [PatchSize](../../aspose.imaging.watermark.options/contentawarefillwatermarkoptions/patchsize/) { get; set; } | 获取或设置补丁大小（应为奇数）。 |
| [PrecalculationProgressEventHandler](../../aspose.imaging.watermark.options/watermarkoptions/precalculationprogresseventhandler/) { get; set; } | 获取或设置默认点预计算过程进度事件处理程序。 |

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

* class [WatermarkOptions](../watermarkoptions/)
* namespace [Aspose.Imaging.Watermark.Options](../../aspose.imaging.watermark.options/)
* assembly [Aspose.Imaging](../../)


