---
title: "类 SolidBrush"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Brushes.SolidBrush 类。实心画刷用于使用特定颜色连续绘图。此类不可被继承。"
type: docs
weight: 210
url: /zh/net/aspose.imaging.brushes/solidbrush/
---
## SolidBrush class

实心画笔用于使用特定颜色连续绘制。此类不可被继承。

```csharp
public sealed class SolidBrush : Brush
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SolidBrush](solidbrush/#constructor)() | 初始化 `SolidBrush` 类的新实例。 |
| [SolidBrush](solidbrush/#constructor_1)(Color) | 初始化 `SolidBrush` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Color](../../aspose.imaging.brushes/solidbrush/color/) { get; set; } | 获取或设置画笔颜色。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [Opacity](../../aspose.imaging/brush/opacity/) { get; set; } | 获取或设置画笔的不透明度。该值应在 0 到 1 之间。0 表示画笔完全透明，1 表示画笔完全不透明。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone/)() | 创建当前 [`Brush`](../../aspose.imaging/brush/) 的深度克隆副本。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| override [Equals](../../aspose.imaging/brush/equals/)(object) | 检查对象是否相等。 |
| override [GetHashCode](../../aspose.imaging/brush/gethashcode/)() | 获取当前对象的哈希码。 |

## 示例

此示例使用 Graphics 类在 Image 表面创建基本形状。为了演示操作，示例创建一个 PNG 格式的新 Image，并使用 Graphics 类提供的 Draw 方法在 Image 表面绘制基本形状。

```csharp
[C#]

//创建 FileStream 的实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //创建 PngOptions 的实例并设置其各种属性
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //为 PngOptions 设置 Source
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建 Image 的实例
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //创建并初始化 Graphics 类的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除 Graphics 表面
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //通过指定具有黑色的 Pen 对象绘制弧线，
        //一个围绕弧线的 Rectangle、起始角度和扫掠角度
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //通过指定具有蓝色的 Pen 对象和坐标点绘制贝塞尔曲线。
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //通过指定具有绿色的 Pen 对象和点数组绘制曲线
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //使用 Pen 对象和围绕的 Rectangle 绘制椭圆
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //绘制直线
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //绘制饼图扇形
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //通过指定具有红色的 Pen 对象和点数组绘制多边形
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //绘制矩形
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //创建 SolidBrush 对象并设置其各种属性
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //使用 SolidBrush 对象和 Font 在特定点绘制字符串
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // 保存所有更改。
        image.Save();
    }
}
```

### 另请参见

* class [Brush](../../aspose.imaging/brush/)
* namespace [Aspose.Imaging.Brushes](../../aspose.imaging.brushes/)
* assembly [Aspose.Imaging](../../)


