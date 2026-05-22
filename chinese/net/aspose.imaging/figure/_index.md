---
title: "类 Figure"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Figure 类。该图形。形状的容器"
type: docs
weight: 1320
url: /zh/net/aspose.imaging/figure/
---
## Figure class

图形。形状的容器。

```csharp
public class Figure : ObjectWithBounds
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Figure](figure/)() | 初始化一个新的 `Figure` 实例。用于 JSON 反序列化的构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.imaging/figure/bounds/) { get; } | 获取或设置对象的边界。 |
| [IsClosed](../../aspose.imaging/figure/isclosed/) { get; set; } | 获取或设置一个值，以指示此图形是否闭合。闭合图形仅在首个和最后一个图形的形状是连续形状的情况下才会产生差异。在这种情况下，首个形状的起点将通过一条直线与最后一个形状的终点相连。 |
| [Segments](../../aspose.imaging/figure/segments/) { get; } | 获取整个图形的段。 |
| [Shapes](../../aspose.imaging/figure/shapes/) { get; } | 获取形状。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddShape](../../aspose.imaging/figure/addshape/)(Shape) | 向图形添加形状。 |
| [AddShapes](../../aspose.imaging/figure/addshapes/)(Shape[]) | 向图形添加一系列形状。 |
| override [Equals](../../aspose.imaging/figure/equals/)(object) | 确定指定的对象是否等于当前对象。 |
| override [GetBounds](../../aspose.imaging/figure/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.imaging/figure/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| override [GetHashCode](../../aspose.imaging/figure/gethashcode/)() | 作为默认的哈希函数。 |
| [RemoveShape](../../aspose.imaging/figure/removeshape/)(Shape) | 从图形中移除形状。 |
| [RemoveShapes](../../aspose.imaging/figure/removeshapes/)(Shape[]) | 从图形中移除一系列形状。 |
| [Reverse](../../aspose.imaging/figure/reverse/)() | 反转此图形的形状顺序和形状点顺序。 |
| override [Transform](../../aspose.imaging/figure/transform/)(Matrix) | 对形状应用指定的变换。 |

## 示例

此示例使用 GraphicsPath 和 Graphics 类在图像表面上创建和操作图形。示例创建一个新的 Image（Tiff 类型），清除表面并借助 GraphicsPath 类绘制路径。最后调用 Graphics 类公开的 DrawPath 方法在表面上渲染这些路径。

```csharp
[C#]

//创建 FileStream 的实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //创建 TiffOptions 的实例并设置其各种属性
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //为 ImageOptions 实例设置源
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建 Image 的实例
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //创建并初始化 Graphics 类的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除 Graphics 表面
        graphics.Clear(Color.Wheat);

        //创建 GraphicsPath 类的实例
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //创建 Figure 类的实例
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //向 Figure 对象添加形状
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //将 Figure 对象添加到 GraphicsPath
        graphicspath.AddFigure(figure);

        //使用颜色为 Black 的 Pen 对象绘制路径
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // 保存所有更改。
        image.Save();
    }
}
```

### 另请参见

* class [ObjectWithBounds](../objectwithbounds/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


