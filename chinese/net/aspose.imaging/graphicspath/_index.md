---
title: GraphicsPath
second_title: Aspose.Imaging for .NET API 参考
description: 表示一系列相连的直线和曲线这个类不能被继承
type: docs
weight: 9370
url: /zh/net/aspose.imaging/graphicspath/
---
## GraphicsPath class

表示一系列相连的直线和曲线。这个类不能被继承。

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [GraphicsPath](graphicspath#constructor)() | 初始化[`GraphicsPath`](../graphicspath)类. |
| [GraphicsPath](graphicspath#constructor_1)(Figure[]) | 初始化[`GraphicsPath`](../graphicspath)类. |
| [GraphicsPath](graphicspath#constructor_3)(FillMode) | 初始化[`GraphicsPath`](../graphicspath)类. |
| [GraphicsPath](graphicspath#constructor_2)(Figure[], FillMode) | 初始化[`GraphicsPath`](../graphicspath)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.imaging/graphicspath/bounds) { get; } | 获取或设置对象的边界。 |
| [Figures](../../aspose.imaging/graphicspath/figures) { get; } | 获取路径数字。 |
| [FillMode](../../aspose.imaging/graphicspath/fillmode) { get; set; } | 获取或设置一个[`FillMode`](../fillmode)枚举，它决定了这个形状的内部如何[`GraphicsPath`](../graphicspath)已满。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddFigure](../../aspose.imaging/graphicspath/addfigure)(Figure) | 添加一个新人物。 |
| [AddFigures](../../aspose.imaging/graphicspath/addfigures)(Figure[]) | 添加新人物。 |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath)(GraphicsPath) | 附加指定的[`GraphicsPath`](../graphicspath)到这条路。 |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath_1)(GraphicsPath, bool) | 附加指定的[`GraphicsPath`](../graphicspath)到这条路。 |
| [DeepClone](../../aspose.imaging/graphicspath/deepclone)() | 执行此图形路径的深度克隆。 |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten)() | 将此路径中的每条曲线转换为一系列相连的线段。 |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_1)(Matrix) | 应用指定的变换，然后转换此曲线中的每条曲线[`GraphicsPath`](../graphicspath)成一系列连接的线段。 |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_2)(Matrix, float) | 转换此曲线中的每条曲线[`GraphicsPath`](../graphicspath)成一系列连接的线段。 |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible)(Point, Pen) | 表示指定点是否包含在（下）此轮廓的范围内[`GraphicsPath`](../graphicspath)绘制时指定[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_2)(PointF, Pen) | 表示指定点是否包含在（下）此轮廓的范围内[`GraphicsPath`](../graphicspath)绘制时指定[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_6)(float, float, Pen) | 表示指定点是否包含在（下）此轮廓的范围内[`GraphicsPath`](../graphicspath)绘制时指定[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_4)(int, int, Pen) | 表示指定点是否包含在（下）此轮廓的范围内[`GraphicsPath`](../graphicspath)绘制时指定[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_1)(Point, Pen, Graphics) | 表示指定点是否包含在（下）此轮廓的范围内[`GraphicsPath`](../graphicspath)绘制时指定[`Pen`](../pen)并使用指定的[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_3)(PointF, Pen, Graphics) | 表示指定点是否包含在（下）此轮廓的范围内[`GraphicsPath`](../graphicspath)绘制时指定[`Pen`](../pen)并使用指定的[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_7)(float, float, Pen, Graphics) | 表示指定点是否包含在（下）此轮廓的范围内[`GraphicsPath`](../graphicspath)绘制时指定[`Pen`](../pen)并使用指定的[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_5)(int, int, Pen, Graphics) | 表示指定点是否包含在（下）此轮廓的范围内[`GraphicsPath`](../graphicspath)绘制时指定[`Pen`](../pen)并使用指定的[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible)(Point) | 表示指定的点是否包含在这个范围内[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_2)(PointF) | 表示指定的点是否包含在这个范围内[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_6)(float, float) | 表示指定的点是否包含在这个范围内[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_4)(int, int) | 表示指定的点是否包含在这个范围内[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_1)(Point, Graphics) | 表示指定的点是否包含在这个范围内[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_3)(PointF, Graphics) | 表示指定的点是否包含在这个范围内[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_7)(float, float, Graphics) | 表示指定的点是否包含在这个范围内[`GraphicsPath`](../graphicspath)在指定的可见剪辑区域中[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_5)(int, int, Graphics) | 表示指定的点是否包含在这个范围内[`GraphicsPath`](../graphicspath) , 使用指定的[`Graphics`](../graphics) . |
| [RemoveFigure](../../aspose.imaging/graphicspath/removefigure)(Figure) | 删除图形。 |
| [RemoveFigures](../../aspose.imaging/graphicspath/removefigures)(Figure[]) | 删除人物。 |
| [Reset](../../aspose.imaging/graphicspath/reset)() | 清空图形路径并设置[`FillMode`](../fillmode)至Alternate . |
| [Reverse](../../aspose.imaging/graphicspath/reverse)() | 颠倒每个形状中的图形、形状和点的顺序[`GraphicsPath`](../graphicspath) . |
| override [Transform](../../aspose.imaging/graphicspath/transform)(Matrix) | 将指定的变换应用于形状。 |
| [Warp](../../aspose.imaging/graphicspath/warp#warp)(PointF[], RectangleF) | 将由矩形和平行四边形定义的扭曲变换应用于此[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_1)(PointF[], RectangleF, Matrix) | 将由矩形和平行四边形定义的扭曲变换应用于此[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | 将由矩形和平行四边形定义的扭曲变换应用于此[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | 将由矩形和平行四边形定义的扭曲变换应用于此[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen)(Pen) | 为路径添加额外的轮廓。 |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_1)(Pen, Matrix) | 为[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_2)(Pen, Matrix, float) | 替换这个[`GraphicsPath`](../graphicspath)当用指定的笔绘制此路径时，带有包围填充区域的曲线。 |

### 例子

此示例使用 GraphicsPath 和 Graphics 类在图像表面上创建和操作图形。示例在 GraphicsPath 类的帮助下创建一个新图像（Tiff 类型），清除表面并绘制路径。最后调用 Graphics 类公开的 DrawPath 方法来渲染表面上的路径。

```csharp
[C#]

//创建一个FileStream实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //创建一个TiffOptions实例并设置它的各种属性
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //设置ImageOptions实例的来源
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建一个Image实例 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //创建并初始化一个Graphics类的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除图形表面
        graphics.Clear(Color.Wheat);

        //创建GraphicsPath类的实例
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //创建一个Figure类的实例
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //将形状添加到图形对象
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //将Figure对象添加到GraphicsPath
        graphicspath.AddFigure(figure);

        //使用颜色为黑色的 Pen 对象绘制路径
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // 保存所有更改。
        image.Save();
    }
}
```

### 也可以看看

* class [ObjectWithBounds](../objectwithbounds)
* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
