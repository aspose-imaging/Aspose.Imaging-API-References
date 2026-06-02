---
title: "GraphicsPath.AddFigures"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GraphicsPath 方法。添加新图形"
type: docs
weight: 60
url: /zh/net/aspose.imaging/graphicspath/addfigures/
---
## GraphicsPath.AddFigures method

添加新图形。

```csharp
public void AddFigures(Figure[] figures)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图形 | Figure[] | 要添加的图形。 |

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

* class [Figure](../../figure/)
* class [GraphicsPath](../)
* namespace [Aspose.Imaging](../../graphicspath/)
* assembly [Aspose.Imaging](../../../)


