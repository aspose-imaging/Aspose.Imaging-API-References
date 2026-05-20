---
title: "SvgGraphics2D"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "提供用于构建 Svg 图像的绘图命令。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---
**Inheritance:**
java.lang.Object
```
public class SvgGraphics2D
```

提供用于构建 Svg 图像的绘图命令。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SvgGraphics2D(int width, int height, int dpi)](#SvgGraphics2D-int-int-int-) | 初始化一个新的 [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) 类的实例。 |
| [SvgGraphics2D(SvgImage image)](#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-) | 初始化一个新的 [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [drawImage(RasterImage image, Point origin)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | 在指定位置绘制指定的图像。 |
| [drawImage(RasterImage image, Point origin, Size size)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-) | 在指定位置绘制指定大小的指定图像。 |
| [drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)](#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-) | 在指定位置以指定大小绘制指定图像的指定部分。 |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | 绘制由 Rectangle 结构指定的椭圆的一部分弧线。 |
| [fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)](#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | 填充由 Rectangle 结构指定的椭圆的一段弧。 |
| [drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | 绘制三次贝塞尔曲线。 |
| [drawString(Font font, String text, Point origin, Color textColor)](#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-) | 绘制文本字符串。 |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | 绘制直线。 |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | 绘制路径。 |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | 填充路径。 |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | 绘制矩形。 |
| [fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-) | 填充矩形。 |
| [endRecording()](#endRecording--) | 获取最终的 Svg 图像，其中包括通过 [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) 对象执行的所有绘图命令。 |

## Example: This example shows how to create an SVG image of the specified size and draw different shapes on it using SvgGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D graphics = new com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// 使用 1 像素宽的黑色笔在图像边框上绘制一个黑色矩形。
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// 使用白烟色填充矩形。
graphics.fillRectangle(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getWhiteSmoke(), 1),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()), 10, 10, 580, 380);

// 使用 1 像素宽的深绿色笔绘制两条对角线。
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// 使用 2 像素宽的蓝色笔在矩形 {0, 0, 200, 200} 内绘制弧线。
graphics.drawArc(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
        new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// 填充弧线
graphics.fillArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getLightCoral(), 10),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// 使用 2 像素宽的红色笔绘制三次贝塞尔曲线。
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.PointF(0, 0),
        new com.aspose.imaging.PointF(200, 133),
        new com.aspose.imaging.PointF(400, 166),
        new com.aspose.imaging.PointF(600, 400));

// 在指定位置绘制指定尺寸的光栅图像。
// 图像已缩放以适应所需的矩形。
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw, new com.aspose.imaging.Point(400, 200), new com.aspose.imaging.Size(100, 50));
} finally {
    imageToDraw.dispose();
}

// 绘制文本字符串
graphics.drawString(
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        "Hello World!",
        new com.aspose.imaging.Point(200, 300),
        com.aspose.imaging.Color.getDarkRed());

// 创建用于填充的路径
com.aspose.imaging.Figure figureToFill = new com.aspose.imaging.Figure();
figureToFill.setClosed(true);

com.aspose.imaging.GraphicsPath pathToFill = new com.aspose.imaging.GraphicsPath();
pathToFill.addFigure(figureToFill);

figureToFill.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(400, 0, 200, 100), 45, 300),
                new com.aspose.imaging.shapes.BezierShape(
                        new com.aspose.imaging.PointF[]
                                {
                                        new com.aspose.imaging.PointF(300, 200),
                                        new com.aspose.imaging.PointF(400, 200),
                                        new com.aspose.imaging.PointF(500, 100),
                                        new com.aspose.imaging.PointF(600, 200),
                                }),
                new com.aspose.imaging.shapes.PolygonShape(
                        new com.aspose.imaging.PointF[]
                                {
                                        new com.aspose.imaging.PointF(300, 100),
                                }),
                new com.aspose.imaging.shapes.RectangleShape(
                        new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
        });

// 使用黄色画刷填充路径，并使用绿色笔绘制轮廓
graphics.fillPath(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getYellow()), pathToFill);

// 创建用于绘制的路径
com.aspose.imaging.GraphicsPath pathToDraw = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figureToDraw = new com.aspose.imaging.Figure();
pathToDraw.addFigure(figureToDraw);

figureToDraw.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(200, 200, 200, 200), 0, 360),
        });

// 使用 5 像素宽的橙色笔绘制路径。
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// 获取包含所有绘图命令的最终 SVG 图像
com.aspose.imaging.fileformats.svg.SvgImage svgImage = graphics.endRecording();
try {
    svgImage.save(dir + "test.output.svg");
} finally {
    svgImage.dispose();
}
```

### SvgGraphics2D(int width, int height, int dpi) {#SvgGraphics2D-int-int-int-}
```
public SvgGraphics2D(int width, int height, int dpi)
```


初始化一个新的 [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 输出 Svg 图像的宽度。 |
| 高度 | int | 输出 Svg 图像的宽度。 |
| dpi | int | 设备分辨率，例如每英寸 96 点。 |

### SvgGraphics2D(SvgImage image) {#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-}
```
public SvgGraphics2D(SvgImage image)
```


初始化一个新的 [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) | 用于执行绘图操作的图像。 |

### drawImage(RasterImage image, Point origin) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public final void drawImage(RasterImage image, Point origin)
```


在指定位置绘制指定的图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 已绘制的图像。 |
| origin | [Point](../../com.aspose.imaging/point) | 已绘制图像的位置。 |

### drawImage(RasterImage image, Point origin, Size size) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public final void drawImage(RasterImage image, Point origin, Size size)
```


在指定位置绘制指定大小的指定图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 已绘制的图像。 |
| origin | [Point](../../com.aspose.imaging/point) | 已绘制图像的位置。 |
| size | [Size](../../com.aspose.imaging/size) | 已绘制图像的期望大小。 |

### drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image) {#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-}
```
public final void drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```


在指定位置以指定大小绘制指定图像的指定部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | 要绘制的图像对象的部分。 |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | 已绘制图像的位置和大小。图像会缩放以适应矩形。 |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 要绘制的图像。 |

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public final void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


绘制由 Rectangle 结构指定的椭圆的一部分弧线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于绘制图形轮廓的笔。 |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 椭圆的边界。 |
| startAngle | float | 以度为单位的角度，从 x 轴顺时针测量到弧的起始点。 |
| arcAngle | float | 以度为单位的角度，从 startAngle 参数顺时针测量到弧的结束点。 |

### fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle) {#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public final void fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)
```


填充由 Rectangle 结构指定的椭圆的一段弧。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于绘制图形轮廓的笔。 |
| brush | [Brush](../../com.aspose.imaging/brush) | 用于填充图形内部的画刷。 |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 椭圆的边界。 |
| startAngle | float | 以度为单位的角度，从 x 轴顺时针测量到弧的起始点。 |
| arcAngle | float | 以度为单位的角度，从 startAngle 参数顺时针测量到弧的结束点。 |

### drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public final void drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


绘制三次贝塞尔曲线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 决定图形颜色、宽度和样式的笔。 |
| pt1 | [PointF](../../com.aspose.imaging/pointf) | 曲线的起始点。 |
| pt2 | [PointF](../../com.aspose.imaging/pointf) | 曲线的第一个控制点。 |
| pt3 | [PointF](../../com.aspose.imaging/pointf) | 曲线的第二个控制点。 |
| pt4 | [PointF](../../com.aspose.imaging/pointf) | 曲线的结束点。 |

### drawString(Font font, String text, Point origin, Color textColor) {#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-}
```
public final void drawString(Font font, String text, Point origin, Color textColor)
```


绘制文本字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | 用于渲染文本的字体。 |
| text | java.lang.String | Unicode 文本字符串。 |
| origin | [Point](../../com.aspose.imaging/point) | 文本运行的左上角。 |
| textColor | [Color](../../com.aspose.imaging/color) | 文本颜色。 |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


绘制直线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 决定图形颜色、宽度和样式的笔。 |
| x1 | int | 第一个点的 x 坐标。 |
| y1 | int | 第一个点的 y 坐标。 |
| x2 | int | 第二个点的 x 坐标。 |
| y2 | int | 第二个点的 y 坐标。 |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public final void drawPath(Pen pen, GraphicsPath path)
```


绘制路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于绘制图形轮廓的笔。 |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 要绘制的路径。 |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public final void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


填充路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于绘制图形轮廓的笔。 |
| brush | [Brush](../../com.aspose.imaging/brush) | 用于填充图形内部的画刷。 |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 要绘制的路径。 |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawRectangle(Pen pen, int x, int y, int width, int height)
```


绘制矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于绘制图形轮廓的笔。 |
| x | int | 要绘制的矩形左上角的 x 坐标。 |
| y | int | 要绘制的矩形左上角的 y 坐标。 |
| 宽度 | int | 要绘制的矩形的宽度。 |
| 高度 | int | 要绘制的矩形的高度。 |

### fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-}
```
public final void fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)
```


填充矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 用于绘制图形轮廓的笔。 |
| brush | [Brush](../../com.aspose.imaging/brush) | 用于填充图形内部的画刷。 |
| x | int | 要绘制的矩形左上角的 x 坐标。 |
| y | int | 要绘制的矩形左上角的 y 坐标。 |
| 宽度 | int | 要绘制的矩形的宽度。 |
| 高度 | int | 要绘制的矩形的高度。 |

### endRecording() {#endRecording--}
```
public final SvgImage endRecording()
```


获取最终的 Svg 图像，其中包括通过 [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) 对象执行的所有绘图命令。

**Returns:**
[SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) - The final Svg image.
