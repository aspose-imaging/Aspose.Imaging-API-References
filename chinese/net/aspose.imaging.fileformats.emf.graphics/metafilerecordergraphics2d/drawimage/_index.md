---
title: "MetafileRecorderGraphics2D.DrawImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "MetafileRecorderGraphics2D 方法。使用指定的 Image 在指定位置以其原始物理尺寸绘制"
type: docs
weight: 80
url: /zh/net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage/
---
## DrawImage(RasterImage, Point) {#drawimage}

在指定位置绘制指定的图像，使用其原始物理尺寸。

```csharp
public void DrawImage(RasterImage image, Point location)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 要绘制的图像。 |
| 位置 | Point | 绘制图像左上角的位置。 |

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* struct [Point](../../../aspose.imaging/point/)
* class [MetafileRecorderGraphics2D](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(RasterImage, Rectangle, Rectangle, GraphicsUnit) {#drawimage_1}

在指定位置以指定尺寸绘制指定图像的指定部分。

```csharp
public void DrawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, 
    GraphicsUnit srcUnit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 要绘制的图像。 |
| destRect | Rectangle | Rectangle 结构，指定绘制图像的位置和大小。图像会缩放以适应矩形。 |
| srcRect | Rectangle | Rectangle 结构，指定要绘制的图像对象的部分。 |
| srcUnit | GraphicsUnit | srcRect 参数使用的度量单位。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | srcUnit；仅支持像素单位 |

## 示例

此示例展示了如何使用 WmfRecorderGraphics2D 创建 WMF 图像并绘制一些几何形状。

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// 这是默认的屏幕分辨率。
int dpi = 96;

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight);

// 创建 WMF 图像。
Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Wmf.Graphics.WmfRecorderGraphics2D(frame, dpi);

// 使用 1 像素宽的黑色笔在图像边缘绘制一个黑色矩形。
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// 使用 white-smoke 颜色填充矩形。
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// 使用 1 像素宽的 darkgreen 笔绘制两条对角线。
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// 使用 2 像素宽的蓝色笔在矩形 {0, 0, 200, 200} 内绘制弧线。
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// 填充弧线
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// 使用 2 像素宽的红色笔绘制三次贝塞尔曲线。
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// 在指定位置绘制指定大小的光栅图像。
// 图像已缩放以适应所需的矩形。
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, imageWidth, imageHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// 绘制文本字符串
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

// 创建用于填充的路径
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

// 使用黄色画笔填充路径，并使用绿色钢笔绘制轮廓
graphics.FillPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Yellow), pathToFill);

// 创建用于绘制的路径
Aspose.Imaging.GraphicsPath pathToDraw = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figureToDraw = new Aspose.Imaging.Figure();
pathToDraw.AddFigure(figureToDraw);

figureToDraw.AddShapes(new Aspose.Imaging.Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(200, 200, 200, 200), 0, 360),
    });

// 使用宽度为5像素的橙色钢笔绘制路径。
graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 5), pathToDraw);

// 为了光栅化 SVG，我们需要指定光栅化选项。
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// 获取包含所有绘图命令的最终 WMF 图像
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = graphics.EndRecording())
{
    wmfImage.Save(dir + "test.output.wmf");
}
```

此示例展示了如何使用 EmfRecorderGraphics2D 创建 EMF 图像并在其上绘制一些几何形状。

```csharp
[C#]

string dir = "c:\\temp\\";

// 图像的像素大小
int deviceWidth = 600;
int deviceHeight = 400;

// 图像的毫米大小
int deviceWidthMm = (int)(deviceWidth / 100f);
int deviceHeightMm = (int)(deviceHeight / 100f);

Aspose.Imaging.Rectangle frame = new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// 创建一个 EMF 图像。
Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D graphics =
    new Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D(
        frame,
        new Aspose.Imaging.Size(deviceWidth, deviceHeight),
        new Aspose.Imaging.Size(deviceWidthMm, deviceHeightMm));

// 使用 1 像素宽的黑色笔在图像边缘绘制一个黑色矩形。
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, deviceWidth, deviceHeight);

// 使用 white-smoke 颜色填充矩形。
graphics.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), new Aspose.Imaging.Rectangle(10, 10, 580, 380));

// 使用 1 像素宽的 darkgreen 笔绘制两条对角线。
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, deviceWidth, deviceHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, deviceHeight, deviceWidth, 0);

// 使用 2 像素宽的蓝色笔在矩形 {0, 0, 200, 200} 内绘制弧线。
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// 填充弧线
graphics.FillPie(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// 使用 2 像素宽的红色笔绘制三次贝塞尔曲线。
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.Point(0, 0),
    new Aspose.Imaging.Point(200, 133),
    new Aspose.Imaging.Point(400, 166),
    new Aspose.Imaging.Point(600, 400));

// 在指定位置绘制指定大小的光栅图像。
// 图像已缩放以适应所需的矩形。
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw,
        new Aspose.Imaging.Rectangle(400, 200, 100, 50),
        new Aspose.Imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
        Aspose.Imaging.GraphicsUnit.Pixel);
}

// 绘制文本字符串
graphics.DrawString("Hello World!", new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), Aspose.Imaging.Color.DarkRed, 200, 300);

// 创建用于填充的路径
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

// 使用黄色画笔填充路径，并使用绿色钢笔绘制轮廓
graphics.FillPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Yellow), pathToFill);

// 创建用于绘制的路径
Aspose.Imaging.GraphicsPath pathToDraw = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figureToDraw = new Aspose.Imaging.Figure();
pathToDraw.AddFigure(figureToDraw);

figureToDraw.AddShapes(new Aspose.Imaging.Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(200, 200, 200, 200), 0, 360),
    });

// 使用宽度为5像素的橙色钢笔绘制路径。
graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 5), pathToDraw);

// 为了光栅化 SVG，我们需要指定光栅化选项。
Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
saveOptions.VectorRasterizationOptions = rasterizationOptions;

// 获取包含所有绘图命令的最终 WMF 图像
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = graphics.EndRecording())
{
    emfImage.Save(dir + "test.output.emf");
}
```

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* struct [Rectangle](../../../aspose.imaging/rectangle/)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit/)
* class [MetafileRecorderGraphics2D](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(byte[], Rectangle, GraphicsUnit) {#drawimage_2}

绘制图像。

```csharp
public void DrawImage(byte[] imageBytes, Rectangle destRect, GraphicsUnit srcUnit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageBytes | Byte[] | 图像字节。 |
| destRect | Rectangle | 目标矩形。 |
| srcUnit | GraphicsUnit | 源单位。 |

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit/)
* class [MetafileRecorderGraphics2D](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d/)
* assembly [Aspose.Imaging](../../../)

---

## DrawImage(Stream, Rectangle, GraphicsUnit) {#drawimage_3}

绘制图像。

```csharp
public void DrawImage(Stream stream, Rectangle destRect, GraphicsUnit srcUnit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |
| destRect | Rectangle | 目标矩形。 |
| srcUnit | GraphicsUnit | 源单位。 |

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* enum [GraphicsUnit](../../../aspose.imaging/graphicsunit/)
* class [MetafileRecorderGraphics2D](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d/)
* assembly [Aspose.Imaging](../../../)


