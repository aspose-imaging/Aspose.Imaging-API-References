---
title: "类 PieShape"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Shapes.PieShape 类。表示一个饼形状"
type: docs
weight: 11580
url: /zh/net/aspose.imaging.shapes/pieshape/
---
## PieShape class

表示饼形。

```csharp
public class PieShape : EllipseShape
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PieShape](pieshape/#constructor)() | 初始化 `PieShape` 类的新实例。 |
| [PieShape](pieshape/#constructor_1)(RectangleF, float, float) | 初始化 `PieShape` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/rectangleprojectedshape/bounds/) { get; } | 获取对象的边界。 |
| override [Center](../../aspose.imaging.shapes/rectangleprojectedshape/center/) { get; } | 获取形状的中心。 |
| override [HasSegments](../../aspose.imaging.shapes/rectangleprojectedshape/hassegments/) { get; } | 获取一个值，指示形状是否具有段。 |
| [LeftBottom](../../aspose.imaging.shapes/rectangleprojectedshape/leftbottom/) { get; } | 获取矩形左下角点。 |
| [LeftTop](../../aspose.imaging.shapes/rectangleprojectedshape/lefttop/) { get; } | 获取矩形左上角点。 |
| [RectangleHeight](../../aspose.imaging.shapes/rectangleprojectedshape/rectangleheight/) { get; } | 获取矩形高度。 |
| [RectangleWidth](../../aspose.imaging.shapes/rectangleprojectedshape/rectanglewidth/) { get; } | 获取矩形宽度。 |
| [RightBottom](../../aspose.imaging.shapes/rectangleprojectedshape/rightbottom/) { get; } | 获取矩形右下角点。 |
| [RightTop](../../aspose.imaging.shapes/rectangleprojectedshape/righttop/) { get; } | 获取矩形右上角点。 |
| override [Segments](../../aspose.imaging.shapes/pieshape/segments/) { get; } | 获取形状的段。 |
| [StartAngle](../../aspose.imaging.shapes/pieshape/startangle/) { get; set; } | 获取或设置起始角度。 |
| [SweepAngle](../../aspose.imaging.shapes/pieshape/sweepangle/) { get; set; } | 获取或设置扫掠角度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.imaging.shapes/pieshape/equals/)(object) | 检查对象是否相等。 |
| override [GetBounds](../../aspose.imaging.shapes/rectangleprojectedshape/getbounds/)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.imaging.shapes/rectangleprojectedshape/getbounds/)(Matrix, Pen) | 获取对象的边界。 |
| override [GetHashCode](../../aspose.imaging.shapes/pieshape/gethashcode/)() | 获取当前对象的哈希码。 |
| override [Transform](../../aspose.imaging.shapes/rectangleprojectedshape/transform/)(Matrix) | 对形状应用指定的变换。 |

## 示例

此示例创建一个新的 Image 并在图像表面使用 Figures 和 GraphicsPath 绘制各种形状。

```csharp
[C#]

//创建 BmpOptions 的实例并设置其各种属性。
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source
//第二个 Boolean 参数决定要创建的文件是否为 IsTemporal
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//创建 Image 的实例
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //创建并初始化 Graphics 类的实例
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //清除 Graphics 表面
    graphics.Clear(Color.Wheat);

    //创建 GraphicsPath 类的实例
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //创建 Figure 类的实例
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

    //向 Figure 对象添加形状。
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //创建 Figure 类的实例
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

    //向 Figure 对象添加形状。
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

    //将 Figure 对象添加到 GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

    //使用颜色为 Black 的 Pen 对象绘制路径
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // 保存所有更改。
    image.Save();
}
```

### 另请参见

* class [EllipseShape](../ellipseshape/)
* namespace [Aspose.Imaging.Shapes](../../aspose.imaging.shapes/)
* assembly [Aspose.Imaging](../../)


