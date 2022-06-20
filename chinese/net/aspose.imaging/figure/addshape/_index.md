---
title: AddShape
second_title: Aspose.Imaging for .NET API 参考
description: 向图形添加形状
type: docs
weight: 60
url: /zh/net/aspose.imaging/figure/addshape/
---
## Figure.AddShape method

向图形添加形状。

```csharp
public void AddShape(Shape shape)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| shape | Shape | 要添加的形状。 |

### 例子

此示例使用 GraphicsPath 和 Graphics 类在图像表面上创建和操作图形。示例在 GraphicsPath 类的帮助下创建一个新图像（Tiff 类型），清除表面并绘制路径。最后调用 Graphics 类公开的 DrawPath 方法来渲染表面上的路径。

```csharp
[C#]

//创建一个BmpOptions实例并设置它的各种属性
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

    //创建一个FileCreateSource的实例并将其分配为BmpOptions
实例的Source
    //第二个布尔参数决定要创建的文件是IsTemporal还是not
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//创建一个Image
的实例
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //创建并初始化一个Graphics class
的实例
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //清除图形surface
    graphics.Clear(Color.Wheat);

    //创建GraphicsPath class
的实例
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //创建Figure class
的实例
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

           //将形状添加到图形 object
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //创建Figure class
的实例
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

           //将形状添加到图形 object
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

        //将图形对象添加到GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

        //用颜色为Black
的Pen对象绘制路径
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // 保存所有更改。
    image.Save();
}
```

此示例创建一个新图像并在图像表面上使用图形和图形路径绘制各种形状

```csharp
[C#]

//创建一个BmpOptions实例并设置它的各种属性
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

    //创建一个FileCreateSource的实例并将其分配为BmpOptions
实例的Source
    //第二个布尔参数决定要创建的文件是IsTemporal还是not
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

//创建一个Image
的实例
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //创建并初始化一个Graphics class
的实例
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //清除图形surface
    graphics.Clear(Color.Wheat);

    //创建GraphicsPath class
的实例
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //创建Figure class
的实例
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

           //将形状添加到图形 object
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //创建Figure class
的实例
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

           //将形状添加到图形 object
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

        //将图形对象添加到GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

        //用颜色为Black
的Pen对象绘制路径
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

    // 保存所有更改。
    image.Save();
}
```

### 也可以看看

* class [Shape](../../shape)
* class [Figure](../../figure)
* 命名空间 [Aspose.Imaging](../../figure)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->