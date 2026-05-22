---
title: "Graphics.Clear"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Graphics 方法。使用指定的颜色清除图形表面。"
type: docs
weight: 160
url: /zh/net/aspose.imaging/graphics/clear/
---
## Graphics.Clear method

使用指定的颜色清除图形表面。

```csharp
public void Clear(Color color)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 颜色 | 颜色 | 用于清除图形表面的颜色。 |

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

此示例使用 Graphics 类在 Image 表面创建基本形状。为了演示操作，示例创建一个 PNG 格式的新 Image，并使用 Graphics 类提供的 Draw 方法在 Image 表面绘制基本形状。

```csharp
[C#]

//创建 FileStream 的实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //创建 PngOptions 的实例并设置其各种属性
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //为 PngOptions 设置 Source
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建 Image 的实例
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //创建并初始化 Graphics 类的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除 Graphics 表面
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //通过指定具有黑色的 Pen 对象绘制弧线，
        //一个围绕弧线的 Rectangle、起始角度和扫掠角度
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //通过指定具有蓝色的 Pen 对象和坐标点绘制贝塞尔曲线。
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //通过指定具有绿色的 Pen 对象和点数组绘制曲线
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //使用 Pen 对象和围绕的 Rectangle 绘制椭圆
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //绘制直线
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //绘制饼图扇形
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //通过指定具有红色的 Pen 对象和点数组绘制多边形
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //绘制矩形
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //创建 SolidBrush 对象并设置其各种属性
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //使用 SolidBrush 对象和 Font 在特定点绘制字符串
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // 保存所有更改。
        image.Save();
    }
}
```

### 另请参见

* struct [Color](../../color/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


