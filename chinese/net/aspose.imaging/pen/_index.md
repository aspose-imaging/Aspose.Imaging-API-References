---
title: "类 Pen"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Pen 类。定义用于绘制线条、曲线和图形的对象"
type: docs
weight: 11260
url: /zh/net/aspose.imaging/pen/
---
## Pen class

定义用于绘制直线、曲线和图形的对象。

```csharp
public class Pen : TransparencySupporter
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Pen](pen/#constructor)(Brush) | 使用指定的 [`Brush`](./brush/) 初始化 `Pen` 类的新实例。 |
| [Pen](pen/#constructor_2)(Color) | 使用指定的颜色初始化 `Pen` 类的新实例。 |
| [Pen](pen/#constructor_1)(Brush, float) | 使用指定的 [`Brush`](./brush/) 和 [`Width`](./width/) 初始化 `Pen` 类的新实例。 |
| [Pen](pen/#constructor_3)(Color, float) | 使用指定的 [`Color`](./color/) 和 [`Width`](./width/) 属性初始化 `Pen` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Alignment](../../aspose.imaging/pen/alignment/) { get; set; } | 获取或设置此 `Pen` 的对齐方式。 |
| [Brush](../../aspose.imaging/pen/brush/) { get; set; } | 获取或设置决定此 `Pen` 属性的 [`Brush`](./brush/)。 |
| [Color](../../aspose.imaging/pen/color/) { get; set; } | 获取或设置此 `Pen` 的颜色。 |
| [CompoundArray](../../aspose.imaging/pen/compoundarray/) { get; set; } | 获取或设置指定复合笔的值数组。复合笔绘制由平行线和间隔组成的复合线。 |
| [CustomEndCap](../../aspose.imaging/pen/customendcap/) { get; set; } | 获取或设置使用于此 `Pen` 绘制的线条末端的自定义帽。 |
| [CustomStartCap](../../aspose.imaging/pen/customstartcap/) { get; set; } | 获取或设置使用于此 `Pen` 绘制的线条起始端的自定义帽。 |
| [DashCap](../../aspose.imaging/pen/dashcap/) { get; set; } | 获取或设置此 `Pen` 绘制的虚线中破折号末端使用的帽样式。 |
| [DashOffset](../../aspose.imaging/pen/dashoffset/) { get; set; } | 获取或设置从线条起点到破折号模式起始的距离。 |
| [DashPattern](../../aspose.imaging/pen/dashpattern/) { get; set; } | 获取或设置自定义破折号和间隔的数组。 |
| [DashStyle](../../aspose.imaging/pen/dashstyle/) { get; set; } | 获取或设置此 `Pen` 绘制的虚线使用的样式。 |
| [EndCap](../../aspose.imaging/pen/endcap/) { get; set; } | 获取或设置此 `Pen` 绘制的线条末端使用的帽样式。 |
| [LineJoin](../../aspose.imaging/pen/linejoin/) { get; set; } | 获取或设置此 `Pen` 绘制的两条连续线条端点的连接样式。 |
| [MiterLimit](../../aspose.imaging/pen/miterlimit/) { get; set; } | 获取或设置斜接角连接处厚度的限制。 |
| [Opacity](../../aspose.imaging/transparencysupporter/opacity/) { get; set; } | 获取或设置对象的不透明度。该值应在 0 到 1 之间。0 表示对象完全可见，1 表示对象完全不透明。 |
| [PenType](../../aspose.imaging/pen/pentype/) { get; } | 获取此 `Pen` 绘制的线条样式。 |
| [StartCap](../../aspose.imaging/pen/startcap/) { get; set; } | 获取或设置此 `Pen` 绘制的线条起始端使用的帽样式。 |
| [Transform](../../aspose.imaging/pen/transform/) { get; set; } | 获取或设置此 `Pen` 的几何变换的副本。 |
| [Width](../../aspose.imaging/pen/width/) { get; set; } | 获取或设置此 `Pen` 的宽度，单位为用于绘图的 Graphics 对象的单位。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.imaging/pen/equals/)(object) | 检查对象是否相等。 |
| override [GetHashCode](../../aspose.imaging/pen/gethashcode/)() | 获取当前对象的哈希码。 |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform/#multiplytransform)(Matrix) | 将此 `Pen` 的变换矩阵乘以指定的 [`Matrix`](../matrix/)。 |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform/#multiplytransform_1)(Matrix, MatrixOrder) | 按指定顺序将此 `Pen` 的变换矩阵乘以指定的 [`Matrix`](../matrix/)。 |
| [ResetTransform](../../aspose.imaging/pen/resettransform/)() | 将此 `Pen` 的几何变换矩阵重置为单位矩阵。 |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform/#rotatetransform)(float) | 按指定角度旋转本地几何变换。此方法将在变换前置旋转。 |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform/#rotatetransform_1)(float, MatrixOrder) | 按指定顺序以指定角度旋转本地几何变换。 |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform/#scaletransform)(float, float) | 按指定因子缩放本地几何变换。此方法将在变换前置缩放矩阵。 |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform/#scaletransform_1)(float, float, MatrixOrder) | 按指定顺序以指定因子缩放本地几何变换。 |
| [SetLineCap](../../aspose.imaging/pen/setlinecap/)(LineCap, LineCap, DashCap) | 设置决定此 `Pen` 绘制的线条结束时使用的帽样式的值。 |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform/#translatetransform)(float, float) | 按指定尺寸平移本地几何变换。此方法将在变换前置平移。 |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform/#translatetransform_1)(float, float, MatrixOrder) | 按指定顺序使用指定的维度平移局部几何变换。 |

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

* class [TransparencySupporter](../transparencysupporter/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


