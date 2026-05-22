---
title: "类 PolygonShape"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Shapes.PolygonShape 类。表示多边形形状"
type: docs
weight: 11590
url: /zh/net/aspose.imaging.shapes/polygonshape/
---
## PolygonShape class

表示多边形形状。

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PolygonShape](polygonshape/#constructor)() | 初始化 `PolygonShape` 类的新实例。 |
| [PolygonShape](polygonshape/#constructor_1)(PointF[]) | 初始化 `PolygonShape` 类的新实例。 |
| [PolygonShape](polygonshape/#constructor_2)(PointF[], bool) | 初始化 `PolygonShape` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/polygonshape/bounds/) { get; } | 获取对象的边界。 |
| override [Center](../../aspose.imaging.shapes/polygonshape/center/) { get; } | 获取形状的中心。 |
| virtual [EndPoint](../../aspose.imaging.shapes/polygonshape/endpoint/) { get; } | 获取结束形状点。 |
| override [HasSegments](../../aspose.imaging.shapes/polygonshape/hassegments/) { get; } | 获取一个值，指示形状是否具有段。 |
| [IsClosed](../../aspose.imaging.shapes/polygonshape/isclosed/) { get; set; } | 获取或设置一个值，指示形状是否闭合。 |
| [Points](../../aspose.imaging.shapes/polygonshape/points/) { get; set; } | 获取或设置曲线点。 |
| override [Segments](../../aspose.imaging.shapes/polygonshape/segments/) { get; } | 获取形状的段。 |
| virtual [StartPoint](../../aspose.imaging.shapes/polygonshape/startpoint/) { get; } | 获取起始形状点。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.imaging.shapes/polygonshape/equals/)(object) | 确定指定的对象是否等于当前对象。 |
| override [GetBounds](../../aspose.imaging.shapes/polygonshape/getbounds/#getbounds)(Matrix) | 获取对象的边界。 |
| override [GetBounds](../../aspose.imaging.shapes/polygonshape/getbounds/#getbounds_1)(Matrix, Pen) | 获取对象的边界。 |
| override [GetHashCode](../../aspose.imaging.shapes/polygonshape/gethashcode/)() | 作为默认的哈希函数。 |
| [Reverse](../../aspose.imaging.shapes/polygonshape/reverse/)() | 反转此形状的点顺序。 |
| override [Transform](../../aspose.imaging.shapes/polygonshape/transform/)(Matrix) | 对形状应用指定的变换。 |

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

* class [Shape](../../aspose.imaging/shape/)
* interface [IOrderedShape](../../aspose.imaging/iorderedshape/)
* namespace [Aspose.Imaging.Shapes](../../aspose.imaging.shapes/)
* assembly [Aspose.Imaging](../../)


