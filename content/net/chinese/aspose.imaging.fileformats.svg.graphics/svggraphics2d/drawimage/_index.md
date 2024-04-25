---
title: DrawImage
second_title: Aspose.Imaging for .NET API 参考
description: 在指定位置绘制指定图像
type: docs
weight: 40
url: /zh/aspose.imaging.fileformats.svg.graphics/svggraphics2d/drawimage/
---
## DrawImage(RasterImage, Point) {#drawimage}

在指定位置绘制指定图像。

```csharp
public void DrawImage(RasterImage image, Point origin)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 绘制的图像。 |
| origin | Point | 绘制图像的位置。 |

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* struct [Point](../../../aspose.imaging/point)
* class [SvgGraphics2D](../../svggraphics2d)
* 命名空间 [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* 部件 [Aspose.Imaging](../../../)

---

## DrawImage(RasterImage, Point, Size) {#drawimage_1}

在指定位置绘制指定大小的指定图像。

```csharp
public void DrawImage(RasterImage image, Point origin, Size size)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 绘制的图像。 |
| origin | Point | 绘制图像的位置。 |
| size | Size | 绘制图像的所需大小。 |

### 例子

此示例说明如何使用 SvgGraphics2D 创建指定大小的 SVG 图像并在其上绘制不同的形状。

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// 使用 1 像素宽的黑色笔沿图像边框绘制一个黑色矩形。
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// 用白色烟雾填充一个矩形。
graphics.FillRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.WhiteSmoke, 1), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), 10, 10, 580, 380);

// 使用 1 像素宽的深绿色笔绘制两条对角线。
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// 使用 2 像素宽的蓝色笔在矩形 {0, 0, 200, 200} 内绘制弧线。
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// 填充圆弧
graphics.FillArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.LightCoral, 10), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// 使用 2 像素宽的红笔绘制三次贝塞尔曲线。
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.PointF(0, 0),
    new Aspose.Imaging.PointF(200, 133),
    new Aspose.Imaging.PointF(400, 166),
    new Aspose.Imaging.PointF(600, 400));

// 在指定位置绘制指定大小的光栅图像。
// 图像被缩放以适合所需的矩形。
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw, new Aspose.Imaging.Point(400, 200), new Aspose.Imaging.Size(100, 50));
}

// 绘制一个文本字符串
graphics.DrawString(new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), "Hello World!", new Aspose.Imaging.Point(200, 300), Aspose.Imaging.Color.DarkRed);

// 创建要填充的路径
Aspose.Imaging.Figure figureToFill = new Aspose.Imaging.Figure();
figureToFill.IsClosed = true;

Aspose.Imaging.GraphicsPath pathToFill = new Aspose.Imaging.GraphicsPath();
pathToFill.AddFigure(figureToFill);

figureToFill.AddShapes(new Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.Rectangle(400, 0, 200, 100), 45, 300),
        new Aspose.Imaging.Shapes.BezierShape(
            new Aspose.Imaging.PointF[]
            {
                new Aspose.Imaging.PointF(300, 200),
                new Aspose.Imaging.PointF(400, 200),
                new Aspose.Imaging.PointF(500, 100),
                new Aspose.Imaging.PointF(600, 200),
            }),
        new Aspose.Imaging.Shapes.PolygonShape(
            new Aspose.Imaging.PointF[]
            {
                new Aspose.Imaging.PointF(300, 100),
            }),
        new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(0, 100, 200, 200)),
    });

// 使用黄色画笔和绿色笔填充路径以绘制轮廓
graphics.FillPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Yellow), pathToFill);

// 创建绘制路径
Aspose.Imaging.GraphicsPath pathToDraw = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figureToDraw = new Aspose.Imaging.Figure();
pathToDraw.AddFigure(figureToDraw);

figureToDraw.AddShapes(new Aspose.Imaging.Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(200, 200, 200, 200), 0, 360),
    });

// 使用 5 像素宽的橙色笔绘制路径。
graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 5), pathToDraw);

// 获取包含所有绘图命令的最终 SVG 图像
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* struct [Point](../../../aspose.imaging/point)
* struct [Size](../../../aspose.imaging/size)
* class [SvgGraphics2D](../../svggraphics2d)
* 命名空间 [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* 部件 [Aspose.Imaging](../../../)

---

## DrawImage(Rectangle, Rectangle, RasterImage) {#drawimage_2}

在指定位置以指定大小绘制指定图像的指定部分。

```csharp
public void DrawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcRect | Rectangle | 要绘制的图像对象部分。 |
| destRect | Rectangle | 绘制图像的位置和大小。图像被缩放以适合矩形。 |
| image | RasterImage | 要绘制的图像。 |

### 也可以看看

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [SvgGraphics2D](../../svggraphics2d)
* 命名空间 [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
