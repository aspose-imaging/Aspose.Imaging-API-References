---
title: "类 HatchBrush"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Brushes.HatchBrush 类。定义具有填充样式、前景色和背景色的矩形画刷。此类不可被继承。"
type: docs
weight: 140
url: /zh/net/aspose.imaging.brushes/hatchbrush/
---
## HatchBrush class

定义具有交叉线样式、前景色和背景色的矩形画笔。此类不可被继承。

```csharp
public sealed class HatchBrush : Brush
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HatchBrush](hatchbrush/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.brushes/hatchbrush/backgroundcolor/) { get; set; } | 获取或设置填充线之间空隙的颜色。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ForegroundColor](../../aspose.imaging.brushes/hatchbrush/foregroundcolor/) { get; set; } | 获取或设置填充线的颜色。 |
| [HatchStyle](../../aspose.imaging.brushes/hatchbrush/hatchstyle/) { get; set; } | 获取或设置此画刷的填充样式。 |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | 获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全透明，1 表示画笔完全不透明。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone/)() | 创建当前 [`Brush`](../../aspose.imaging/brush/) 的深度克隆副本。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| override [Equals](../../aspose.imaging/brush/equals/)(object) | 检查对象是否相等。 |
| override [GetHashCode](../../aspose.imaging/brush/gethashcode/)() | 获取当前对象的哈希码。 |

## 示例

此示例展示了 Pen 对象的创建和使用。示例创建了一个新的 Image 并在图像表面绘制矩形。

```csharp
[C#]

//创建 BmpOptions 的实例并设置其各种属性
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source
//第二个 Boolean 参数决定要创建的文件是否为 IsTemporal
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//在指定路径创建 Image 的实例
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //创建 Graphics 的实例并使用 Image 对象进行初始化
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //使用白色清除 Graphics 表面
    graphics.Clear(Aspose.Imaging.Color.White);

    //创建颜色为 Red、宽度为 5 的 Pen 实例
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //创建 HatchBrush 的实例并设置其属性
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //创建 Pen 的实例
    //使用 HatchBrush 对象和宽度进行初始化
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    //通过指定 Pen 对象绘制矩形
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    //通过指定 Pen 对象绘制矩形
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // 保存所有更改。
    image.Save();
}
```

### 另请参见

* class [Brush](../../aspose.imaging/brush/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


