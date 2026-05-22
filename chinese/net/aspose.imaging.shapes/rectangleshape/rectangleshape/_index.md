---
title: "RectangleShape.RectangleShape"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RectangleShape 构造函数。初始化 RectangleShape 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.imaging.shapes/rectangleshape/rectangleshape/
---
## RectangleShape() {#constructor}

初始化 [`RectangleShape`](../) 类的新实例。

```csharp
public RectangleShape()
```

### 另请参见

* class [RectangleShape](../)
* namespace [Aspose.Imaging.Shapes](../../rectangleshape/)
* assembly [Aspose.Imaging](../../../)

---

## RectangleShape(RectangleF) {#constructor_1}

初始化 [`RectangleShape`](../) 类的新实例。

```csharp
public RectangleShape(RectangleF rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | RectangleF | 矩形。 |

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

* struct [RectangleF](../../../aspose.imaging/rectanglef/)
* class [RectangleShape](../)
* namespace [Aspose.Imaging.Shapes](../../rectangleshape/)
* assembly [Aspose.Imaging](../../../)


