---
title: Clear
second_title: Aspose.Imaging for .NET API 参考
description: 使用指定颜色清除图形表面
type: docs
weight: 150
url: /zh/net/aspose.imaging/graphics/clear/
---
## Graphics.Clear method

使用指定颜色清除图形表面。

```csharp
public void Clear(Color color)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| color | Color | 清除图形表面的颜色。 |

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

此示例使用 Graphics 类在 Image 表面上创建原始形状。为了演示该操作，该示例创建一个 PNG 格式的新图像，并使用 Graphics 类公开的 Draw 方法在图像表面上绘制原始形状

```csharp
[C#]

//创建一个FileStream实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //创建一个PngOptions实例并设置它的各种属性
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //设置PngOptions的来源
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建一个Image实例 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //创建并初始化一个Graphics类的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除图形表面
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //通过指定具有黑色颜色的Pen对象来绘制弧线， 
        //一个围绕圆弧的矩形，起始角和扫角
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //通过指定具有蓝色和坐标点的 Pen 对象来绘制 Bezier。
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //通过指定具有绿色的 Pen 对象和点数组来绘制曲线
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //使用 Pen 对象和周围的 Rectangle 绘制一个椭圆
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //画一条线 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //画一个饼段
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //通过指定具有红色的 Pen 对象和点数组来绘制多边形
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //画一个矩形
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //创建一个SolidBrush对象并设置它的各种属性
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //使用 SolidBrush 对象和字体在特定点绘制一个字符串
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // 保存所有更改。
        image.Save();
    }
}
```

### 也可以看看

* struct [Color](../../color)
* class [Graphics](../../graphics)
* 命名空间 [Aspose.Imaging](../../graphics)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
