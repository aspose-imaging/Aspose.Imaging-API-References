---
title: "类 TeleaWatermarkOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Watermark.Options.TeleaWatermarkOptions 类。通用 Telea 算法选项"
type: docs
weight: 11840
url: /zh/net/aspose.imaging.watermark.options/teleawatermarkoptions/
---
## TeleaWatermarkOptions class

通用 Telea 算法选项。

```csharp
public class TeleaWatermarkOptions : WatermarkOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TeleaWatermarkOptions](teleawatermarkoptions/#constructor)(GraphicsPath) | 初始化 `TeleaWatermarkOptions` 类的新实例。 |
| [TeleaWatermarkOptions](teleawatermarkoptions/#constructor_1)(Point[]) | 初始化 `TeleaWatermarkOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [GraphicsPathMask](../../aspose.imaging.watermark.options/watermarkoptions/graphicspathmask/) { get; set; } | 获取或设置掩码。 |
| [HalfPatchSize](../../aspose.imaging.watermark.options/teleawatermarkoptions/halfpatchsize/) { get; set; } | 获取或设置半补丁大小。 |
| [Mask](../../aspose.imaging.watermark.options/watermarkoptions/mask/) { get; set; } | 获取或设置掩码。 |
| [PrecalculationProgressEventHandler](../../aspose.imaging.watermark.options/watermarkoptions/precalculationprogresseventhandler/) { get; set; } | 获取或设置默认点预计算过程进度事件处理程序。 |

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

### 另请参见

* class [WatermarkOptions](../watermarkoptions/)
* namespace [Aspose.Imaging.Watermark.Options](../../aspose.imaging.watermark.options/)
* assembly [Aspose.Imaging](../../)


