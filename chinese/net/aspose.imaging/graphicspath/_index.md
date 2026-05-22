---
title: "类 GraphicsPath"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.GraphicsPath 类。表示一系列相连的直线和曲线。此类不可被继承"
type: docs
weight: 9550
url: /zh/net/aspose.imaging/graphicspath/
---
## GraphicsPath class

表示一系列相连的直线和曲线。此类不可被继承。

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GraphicsPath](graphicspath/#constructor)() | 初始化 `GraphicsPath` 类的新实例。 |
| [GraphicsPath](graphicspath/#constructor_1)(Figure[]) | 初始化 `GraphicsPath` 类的新实例。 |
| [GraphicsPath](graphicspath/#constructor_3)(FillMode) | 初始化 `GraphicsPath` 类的新实例。 |
| [GraphicsPath](graphicspath/#constructor_2)(Figure[], FillMode) | 初始化 `GraphicsPath` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.imaging/graphicspath/bounds/) { get; } | 获取或设置对象的边界。 |
| [Figures](../../aspose.imaging/graphicspath/figures/) { get; } | 获取路径图形。 |
| [FillMode](../../aspose.imaging/graphicspath/fillmode/) { get; set; } | 获取或设置一个 [`FillMode`](../fillmode/) 枚举，用于确定此 `GraphicsPath` 中形状内部的填充方式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddFigure](../../aspose.imaging/graphicspath/addfigure/)(Figure) | 添加一个新图形。 |
| [AddFigures](../../aspose.imaging/graphicspath/addfigures/)(Figure[]) | 添加新图形。 |
| [AddPath](../../aspose.imaging/graphicspath/addpath/#addpath)(GraphicsPath) | 将指定的 `GraphicsPath` 附加到此路径。 |
| [AddPath](../../aspose.imaging/graphicspath/addpath/#addpath_1)(GraphicsPath, bool) | 将指定的 `GraphicsPath` 附加到此路径。 |
| [DeepClone](../../aspose.imaging/graphicspath/deepclone/)() | 执行此图形路径的深度克隆。 |
| override [Equals](../../aspose.imaging/graphicspath/equals/)(object) | 检查对象是否相等。 |
| [Flatten](../../aspose.imaging/graphicspath/flatten/#flatten)() | 将此路径中的每条曲线转换为一系列相连的线段。 |
| [Flatten](../../aspose.imaging/graphicspath/flatten/#flatten_1)(Matrix) | 应用指定的变换，然后将此 `GraphicsPath` 中的每条曲线转换为一系列相连的线段。 |
| [Flatten](../../aspose.imaging/graphicspath/flatten/#flatten_2)(Matrix, float) | 将此 `GraphicsPath` 中的每条曲线转换为一系列相连的线段。 |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| override [GetHashCode](../../aspose.imaging/graphicspath/gethashcode/)() | 获取当前对象的哈希码。 |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible)(Point, Pen) | 指示在使用指定的 [`Pen`](../pen/) 绘制时，指定的点是否位于此 `GraphicsPath` 的轮廓内（下方）。 |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_2)(PointF, Pen) | 指示在使用指定的 [`Pen`](../pen/) 绘制时，指定的点是否位于此 `GraphicsPath` 的轮廓内（下方）。 |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_6)(float, float, Pen) | 指示在使用指定的 [`Pen`](../pen/) 绘制时，指定的点是否位于此 `GraphicsPath` 的轮廓内（下方）。 |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_4)(int, int, Pen) | 指示在使用指定的 [`Pen`](../pen/) 绘制时，指定的点是否位于此 `GraphicsPath` 的轮廓内（下方）。 |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_1)(Point, Pen, Graphics) | 指示在使用指定的 [`Pen`](../pen/) 并使用指定的 [`Graphics`](../graphics/) 绘制时，指定的点是否位于此 `GraphicsPath` 的轮廓内（下方）。 |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_3)(PointF, Pen, Graphics) | 指示在使用指定的 [`Pen`](../pen/) 并使用指定的 [`Graphics`](../graphics/) 绘制时，指定的点是否位于此 `GraphicsPath` 的轮廓内（下方）。 |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_7)(float, float, Pen, Graphics) | 指示在使用指定的 [`Pen`](../pen/) 并使用指定的 [`Graphics`](../graphics/) 绘制时，指定的点是否位于此 `GraphicsPath` 的轮廓内（下方）。 |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible/#isoutlinevisible_5)(int, int, Pen, Graphics) | 指示在使用指定的 [`Pen`](../pen/) 并使用指定的 [`Graphics`](../graphics/) 绘制时，指定的点是否位于此 `GraphicsPath` 的轮廓内（下方）。 |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible)(Point) | 指示指定的点是否位于此 `GraphicsPath` 内部。 |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_2)(PointF) | 指示指定的点是否位于此 `GraphicsPath` 内部。 |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_6)(float, float) | 指示指定的点是否位于此 `GraphicsPath` 内部。 |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_4)(int, int) | 指示指定的点是否位于此 `GraphicsPath` 内部。 |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_1)(Point, Graphics) | 指示指定的点是否位于此 `GraphicsPath` 内部。 |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_3)(PointF, Graphics) | 指示指定的点是否位于此 `GraphicsPath` 内部。 |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_7)(float, float, Graphics) | 指示指定的点是否位于此 `GraphicsPath` 在指定的 [`Graphics`](../graphics/) 可见裁剪区域内。 |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible/#isvisible_5)(int, int, Graphics) | 指示在使用指定的 [`Graphics`](../graphics/) 时，指定的点是否位于此 `GraphicsPath` 内部。 |
| [RemoveFigure](../../aspose.imaging/graphicspath/removefigure/)(Figure) | 删除一个图形。 |
| [RemoveFigures](../../aspose.imaging/graphicspath/removefigures/)(Figure[]) | 删除图形。 |
| [Reset](../../aspose.imaging/graphicspath/reset/)() | 清空图形路径并将 [`FillMode`](../fillmode/) 设置为 Alternate。 |
| [Reverse](../../aspose.imaging/graphicspath/reverse/)() | 反转此 `GraphicsPath` 中每个形状的图形、形状和点的顺序。 |
| override [Transform](../../aspose.imaging/graphicspath/transform/)(Matrix) | 对形状应用指定的变换。 |
| [Warp](../../aspose.imaging/graphicspath/warp/#warp)(PointF[], RectangleF) | 对该 `GraphicsPath` 应用由矩形和平行四边形定义的扭曲变换。 |
| [Warp](../../aspose.imaging/graphicspath/warp/#warp_1)(PointF[], RectangleF, Matrix) | 对该 `GraphicsPath` 应用由矩形和平行四边形定义的扭曲变换。 |
| [Warp](../../aspose.imaging/graphicspath/warp/#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | 对该 `GraphicsPath` 应用由矩形和平行四边形定义的扭曲变换。 |
| [Warp](../../aspose.imaging/graphicspath/warp/#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | 对该 `GraphicsPath` 应用由矩形和平行四边形定义的扭曲变换。 |
| [Widen](../../aspose.imaging/graphicspath/widen/#widen)(Pen) | 向路径添加额外的轮廓。 |
| [Widen](../../aspose.imaging/graphicspath/widen/#widen_1)(Pen, Matrix) | 向 `GraphicsPath` 添加额外的轮廓。 |
| [Widen](../../aspose.imaging/graphicspath/widen/#widen_2)(Pen, Matrix, float) | 将此 `GraphicsPath` 替换为在使用指定笔绘制此路径时填充的区域所包围的曲线。 |

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


