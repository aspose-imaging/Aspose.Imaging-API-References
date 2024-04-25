---
title: Pen
second_title: Aspose.Imaging for .NET API 参考
description: 定义用于绘制直线曲线和图形的对象
type: docs
weight: 10690
url: /zh/aspose.imaging/pen/
---
## Pen class

定义用于绘制直线、曲线和图形的对象。

```csharp
public class Pen : TransparencySupporter
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Pen](pen#constructor)(Brush) | 初始化[`Pen`](../pen)具有指定的类[`Brush`](./brush) . |
| [Pen](pen#constructor_2)(Color) | 初始化[`Pen`](../pen)具有指定颜色的类。 |
| [Pen](pen#constructor_1)(Brush, float) | 初始化[`Pen`](../pen)具有指定的类[`Brush`](./brush)和[`Width`](./width) . |
| [Pen](pen#constructor_3)(Color, float) | 初始化[`Pen`](../pen)具有指定的类[`Color`](./color)和[`Width`](./width)属性. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Alignment](../../aspose.imaging/pen/alignment) { get; set; } | 获取或设置此对齐方式[`Pen`](../pen) . |
| [Brush](../../aspose.imaging/pen/brush) { get; set; } | 获取或设置[`Brush`](./brush)决定了这个属性[`Pen`](../pen) . |
| [Color](../../aspose.imaging/pen/color) { get; set; } | 获取或设置此颜色[`Pen`](../pen) . |
| [CompoundArray](../../aspose.imaging/pen/compoundarray) { get; set; } | 获取或设置指定复合笔的值数组。复合笔画出由平行线和空格组成的复合线。 |
| [CustomEndCap](../../aspose.imaging/pen/customendcap) { get; set; } | 获取或设置一个自定义上限以在使用此绘制的线的末尾使用[`Pen`](../pen) . |
| [CustomStartCap](../../aspose.imaging/pen/customstartcap) { get; set; } | 获取或设置一个自定义上限以在使用此绘制的线条的开头使用[`Pen`](../pen) . |
| [DashCap](../../aspose.imaging/pen/dashcap) { get; set; } | 获取或设置在组成虚线的虚线末尾使用的帽子样式[`Pen`](../pen) . |
| [DashOffset](../../aspose.imaging/pen/dashoffset) { get; set; } | 获取或设置从线条开始到虚线图案开始的距离。 |
| [DashPattern](../../aspose.imaging/pen/dashpattern) { get; set; } | 获取或设置自定义破折号和空格的数组。 |
| [DashStyle](../../aspose.imaging/pen/dashstyle) { get; set; } | 获取或设置用于绘制虚线的样式[`Pen`](../pen) . |
| [EndCap](../../aspose.imaging/pen/endcap) { get; set; } | 获取或设置用 this 绘制的线条末端使用的帽子样式[`Pen`](../pen) . |
| [LineJoin](../../aspose.imaging/pen/linejoin) { get; set; } | 获取或设置用 this 绘制的两条连续线的末端的连接样式[`Pen`](../pen) . |
| [MiterLimit](../../aspose.imaging/pen/miterlimit) { get; set; } | 获取或设置斜接角上连接的厚度限制。 |
| [Opacity](../../aspose.imaging/transparencysupporter/opacity) { get; set; } | 获取或设置对象的不透明度。该值应介于 0 和 1 之间。值 0 表示对象完全可见，值 1 表示对象完全不透明。 |
| [PenType](../../aspose.imaging/pen/pentype) { get; } | 获取用这个绘制的线条的样式[`Pen`](../pen) . |
| [StartCap](../../aspose.imaging/pen/startcap) { get; set; } | 获取或设置使用此绘制的线条开头使用的帽子样式[`Pen`](../pen) . |
| [Transform](../../aspose.imaging/pen/transform) { get; set; } | 获取或设置几何变换的副本[`Pen`](../pen) . |
| [Width](../../aspose.imaging/pen/width) { get; set; } | 获取或设置 this 的宽度[`Pen`](../pen) 以用于绘图的 Graphics 对象为单位。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform)(Matrix) | 乘以变换矩阵[`Pen`](../pen)由指定的[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | 乘以变换矩阵[`Pen`](../pen)由指定的[`Matrix`](../matrix)按指定顺序。 |
| [ResetTransform](../../aspose.imaging/pen/resettransform)() | 为此重置几何变换矩阵[`Pen`](../pen)身份. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform)(float) | 将局部几何变换旋转指定角度。此方法将旋转添加到转换中。 |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform_1)(float, MatrixOrder) | 以指定顺序将局部几何变换旋转指定角度。 |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform)(float, float) | 按指定因子缩放局部几何变换。此方法将缩放矩阵添加到转换中。 |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform_1)(float, float, MatrixOrder) | 按指定顺序按指定因子缩放局部几何变换。 |
| [SetLineCap](../../aspose.imaging/pen/setlinecap)(LineCap, LineCap, DashCap) | 设置确定用于结束由此绘制的线条的帽子样式的值[`Pen`](../pen) . |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform)(float, float) | 按指定尺寸平移局部几何变换。此方法将转换添加到转换之前。 |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform_1)(float, float, MatrixOrder) | 按指定顺序按指定尺寸平移局部几何变换。 |

### 例子

这个例子展示了 Pen 对象的创建和使用。该示例创建一个新图像并在图像表面上绘制矩形。

```csharp
[C#]

//创建一个BmpOptions的实例并设置它的各种属性
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//创建一个 FileCreateSource 的实例并将其分配为 BmpOptions 实例的 Source
//第二个布尔参数确定要创建的文件是否为IsTemporal
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//在指定路径创建一个Image实例
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //创建一个Graphics实例并用Image对象初始化
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //用白色清除图形表面
    graphics.Clear(Aspose.Imaging.Color.White);

    //创建一个Pen实例，颜色为红色，宽度为5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //创建一个HatchBrush实例并设置它的属性
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //创建一个Pen实例
    //用 HatchBrush 对象和宽度初始化它
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    //通过指定Pen对象绘制矩形
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    //通过指定Pen对象绘制矩形
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // 保存所有更改。
    image.Save();
}
```

### 也可以看看

* class [TransparencySupporter](../transparencysupporter)
* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
