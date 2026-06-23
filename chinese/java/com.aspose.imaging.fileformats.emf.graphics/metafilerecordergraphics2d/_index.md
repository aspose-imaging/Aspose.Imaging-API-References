---
title: "MetafileRecorderGraphics2D"
second_title: "Aspose.Imaging for Java API 参考"
description: "元文件记录器图形"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
**Inheritance:**
java.lang.Object
```
public abstract class MetafileRecorderGraphics2D
```

元文件记录器图形
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MetafileRecorderGraphics2D()](#MetafileRecorderGraphics2D--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getClip()](#getClip--) | 获取或设置限制此 Graphics 绘图区域的 Region |
| [setClip(Region value)](#setClip-com.aspose.imaging.Region-) | 获取或设置限制此 Graphics 绘图区域的 Region |
| [getClipBounds()](#getClipBounds--) | 获取剪裁边界。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取背景颜色。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | 设置背景颜色。 |
| [clear()](#clear--) | 清除 graphics 对象的状态 |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | 绘制由 Rectangle 结构指定的椭圆部分的弧线。 |
| [drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-) | 绘制三次贝塞尔曲线。 |
| [drawPolyCubicBezier(Pen pen, Point[] points)](#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | 绘制多段三次贝塞尔曲线。 |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | 绘制椭圆。 |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | 填充椭圆。 |
| [drawImage(RasterImage image, Point location)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | 在指定位置绘制指定的图像，使用其原始物理尺寸。 |
| [drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)](#drawImage-byte---com.aspose.imaging.Rectangle-int-) | 绘制图像。 |
| [drawImage(InputStream stream, Rectangle destRect, int srcUnit)](#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-) | 绘制图像。 |
| [drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-) | 在指定位置以指定尺寸绘制指定图像的指定部分。 |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | 绘制直线。 |
| [drawLine(Pen pen, Point pt1, Point pt2)](#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-) | 绘制直线。 |
| [drawPolyline(Pen pen, Point[] points)](#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | 绘制折线。 |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | 绘制路径。 |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | 填充路径。 |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | 绘制饼形。 |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | 填充饼形。 |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | 绘制多边形。 |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---) | 填充多边形。 |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-) | 填充多边形。 |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | 绘制矩形。 |
| [drawRectangle(Pen pen, Rectangle rectangle)](#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | 绘制矩形。 |
| [fillRectangle(Brush brush, Rectangle rectangle)](#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | 填充矩形。 |
| [drawString(String string, Font font, Color color, int x, int y)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-) | 绘制字符串。 |
| [drawString(String string, Font font, Color color, int x, int y, float angle)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-) | 绘制字符串。 |
| [excludeClip(Rectangle rect)](#excludeClip-com.aspose.imaging.Rectangle-) | 更新此 Graphics 的剪裁区域，以排除由 Rectangle 结构指定的区域。 |
| [excludeClip(Region region)](#excludeClip-com.aspose.imaging.Region-) | 更新此 Graphics 的剪裁区域，以排除由 Region 指定的区域。 |
| [intersectClip(RectangleF rect)](#intersectClip-com.aspose.imaging.RectangleF-) | 更新此 Graphics 的剪裁区域，使其为当前剪裁区域与指定的 Rectangle 结构的交集。 |
| [intersectClip(Region region)](#intersectClip-com.aspose.imaging.Region-) | 更新此 Graphics 的剪裁区域，使其为当前剪裁区域与指定的 Region 的交集。 |
| [resetClip()](#resetClip--) | 重置剪裁。 |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | 将此 Graphics 的世界变换与指定的矩阵相乘。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | 按指定顺序将此 Graphics 的世界变换与指定的矩阵相乘。 |
| [translateTransform(float x, float y)](#translateTransform-float-float-) | 通过在此 Graphics 的变换矩阵前置指定的平移来更改坐标系的原点。 |
| [translateTransform(float x, float y, int order)](#translateTransform-float-float-int-) | 按指定顺序将指定的平移应用于此 Graphics 的变换矩阵，以更改坐标系的原点。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | 将指定的旋转应用于此 Graphics 的变换矩阵。 |
| [rotateTransform(float angle, PointF center, int order)](#rotateTransform-float-com.aspose.imaging.PointF-int-) | 按指定顺序将指定的旋转应用于此 Graphics 的变换矩阵。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | 通过将指定的缩放操作前置到对象的变换矩阵中，应用于此 Graphics 的变换矩阵。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | 按照指定顺序，将指定的缩放操作应用于此 Graphics 的变换矩阵。 |
| [getTransform()](#getTransform--) | 获取世界变换。 |
| [setTransform(Matrix transform)](#setTransform-com.aspose.imaging.Matrix-) | 设置变换。 |

## Example: This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

// 图像的像素尺寸
int deviceWidth = 600;
int deviceHeight = 400;

// 图像的毫米尺寸
int deviceWidthMm = (int) (deviceWidth / 100f);
int deviceHeightMm = (int) (deviceHeight / 100f);

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// 创建 EMF 图像。
com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D(
                frame,
                new com.aspose.imaging.Size(deviceWidth, deviceHeight),
                new com.aspose.imaging.Size(deviceWidthMm, deviceHeightMm));

// 使用 1 像素宽的黑色笔在图像边框上绘制黑色矩形。
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, deviceWidth, deviceHeight);

// 使用 white-smoke 颜色填充矩形。
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// 使用 1 像素宽的 darkgreen 笔绘制两条对角线。
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, deviceWidth, deviceHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, deviceHeight, deviceWidth, 0);

// 使用 2 像素宽的 blue 笔在矩形 {0, 0, 200, 200} 内绘制弧线。
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// 填充弧线
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// 使用 2 像素宽的 red 笔绘制三次贝塞尔曲线。
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// 在指定位置绘制指定尺寸的光栅图像。
// 图像已缩放以适应所需的矩形。
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
} finally {
    imageToDraw.dispose();
}

// 绘制文本字符串
graphics.drawString("Hello World!",
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        com.aspose.imaging.Color.getDarkRed(), 200, 300);

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
                new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
        });

// 使用黄色画刷和绿色笔填充路径并绘制轮廓
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

// 为了栅格化 SVG，我们需要指定栅格化选项。
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// 获取包含所有绘图命令的最终 WMF 图像
com.aspose.imaging.fileformats.emf.EmfImage emfImage = graphics.endRecording();
try {
    emfImage.save(dir + "test.output.emf");
} finally {
    emfImage.dispose();
}
```

### MetafileRecorderGraphics2D() {#MetafileRecorderGraphics2D--}
```
public MetafileRecorderGraphics2D()
```


### getClip() {#getClip--}
```
public Region getClip()
```


获取或设置限制此 Graphics 绘图区域的 Region

**Returns:**
[Region](../../com.aspose.imaging/region) - The clip region.
### setClip(Region value) {#setClip-com.aspose.imaging.Region-}
```
public void setClip(Region value)
```


获取或设置限制此 Graphics 绘图区域的 Region

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Region](../../com.aspose.imaging/region) | 剪裁区域。 |

### getClipBounds() {#getClipBounds--}
```
public RectangleF getClipBounds()
```


获取剪裁边界。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The clip bounds.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取背景颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of the background.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


设置背景颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 背景颜色。 |

### clear() {#clear--}
```
public void clear()
```


清除 graphics 对象的状态

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


绘制由 Rectangle 结构指定的椭圆部分的弧线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 椭圆的边界。 |
| startAngle | float | 从 x 轴顺时针测量到弧起始点的角度（度）。 |
| arcAngle | float | 从 startAngle 参数顺时针测量到弧结束点的角度（度）。 |

### drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


绘制三次贝塞尔曲线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| pt1 | [Point](../../com.aspose.imaging/point) | 曲线的起始点。 |
| pt2 | [Point](../../com.aspose.imaging/point) | 曲线的第一个控制点。 |
| pt3 | [Point](../../com.aspose.imaging/point) | 曲线的第二个控制点。 |
| pt4 | [Point](../../com.aspose.imaging/point) | 曲线的结束点。 |

### drawPolyCubicBezier(Pen pen, Point[] points) {#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyCubicBezier(Pen pen, Point[] points)
```


绘制多段三次贝塞尔曲线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| points | [Point\[\]](../../com.aspose.imaging/point) | 这些点。 |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


绘制椭圆。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 椭圆的边界。 |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


填充椭圆。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | 确定填充特性的画刷。 |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 椭圆的边界。 |

### drawImage(RasterImage image, Point location) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public void drawImage(RasterImage image, Point location)
```


在指定位置绘制指定的图像，使用其原始物理尺寸。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 要绘制的图像。 |
| location | [Point](../../com.aspose.imaging/point) | 绘制图像左上角的位置。 |

### drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit) {#drawImage-byte---com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)
```


绘制图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageBytes | byte[] | 图像字节。 |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | 目标矩形。 |
| srcUnit | int | 源单位。 |

### drawImage(InputStream stream, Rectangle destRect, int srcUnit) {#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(InputStream stream, Rectangle destRect, int srcUnit)
```


绘制图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 流。 |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | 目标矩形。 |
| srcUnit | int | 源单位。 |

### drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-}
```
public void drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)
```


在指定位置以指定尺寸绘制指定图像的指定部分。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 要绘制的图像。 |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | 指定绘制图像位置和大小的矩形结构。图像会按比例缩放以适应该矩形。 |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | 指定要绘制的图像对象部分的矩形结构。 |
| srcUnit | int | srcRect 参数使用的度量单位。 |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


绘制直线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| x1 | int | 第一个点的 x 坐标。 |
| y1 | int | 第一个点的 y 坐标。 |
| x2 | int | 第二个点的 x 坐标。 |
| y2 | int | 第二个点的 y 坐标。 |

### drawLine(Pen pen, Point pt1, Point pt2) {#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawLine(Pen pen, Point pt1, Point pt2)
```


绘制直线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| pt1 | [Point](../../com.aspose.imaging/point) | 第一个点。 |
| pt2 | [Point](../../com.aspose.imaging/point) | 第二个点。 |

### drawPolyline(Pen pen, Point[] points) {#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyline(Pen pen, Point[] points)
```


绘制折线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| points | [Point\[\]](../../com.aspose.imaging/point) | 这些点。 |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


绘制路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 要绘制的路径。 |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


填充路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| brush | [Brush](../../com.aspose.imaging/brush) | 确定填充特性的画刷。 |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 要填充的路径。 |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


绘制饼形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 椭圆的边界。 |
| startAngle | float | 从 x 轴顺时针测量到弧起始点的角度（度）。 |
| sweepAngle | float | 从 startAngle 参数顺时针测量到弧结束点的角度（度）。 |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


填充饼形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | 确定填充特性的画刷。 |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 椭圆的边界。 |
| startAngle | float | 从 x 轴顺时针测量到弧起始点的角度（度）。 |
| sweepAngle | float | 从 startAngle 参数顺时针测量到弧结束点的角度（度）。 |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


绘制多边形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| points | [Point\[\]](../../com.aspose.imaging/point) | 这些点。 |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


填充多边形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | 确定填充特性的画刷。 |
| points | [Point\[\]](../../com.aspose.imaging/point) | 这些点。 |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


填充多边形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | 确定填充特性的画刷。 |
| points | [Point\[\]](../../com.aspose.imaging/point) | 这些点。 |
| fillMode | int | 填充模式。 |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


绘制矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| x | int | 要绘制的矩形左上角的 x 坐标。 |
| y | int | 要绘制的矩形左上角的 y 坐标。 |
| width | int | 要绘制的矩形的宽度。 |
| height | int | 要绘制的矩形的高度。 |

### drawRectangle(Pen pen, Rectangle rectangle) {#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rectangle)
```


绘制矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | 确定图形颜色、宽度和样式的笔。 |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 要绘制的矩形。 |

### fillRectangle(Brush brush, Rectangle rectangle) {#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rectangle)
```


填充矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | 确定填充特性的画刷。 |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 要填充的矩形。 |

### drawString(String string, Font font, Color color, int x, int y) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-}
```
public void drawString(String string, Font font, Color color, int x, int y)
```


绘制字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字符串 | java.lang.String | 该字符串。 |
| font | [Font](../../com.aspose.imaging/font) | 定义字符串文本格式的字体。 |
| color | [Color](../../com.aspose.imaging/color) | 文本颜色。 |
| x | int | 已绘制文本左上角的 x 坐标。 |
| y | int | 已绘制文本左上角的 y 坐标。 |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // 首先，获取图像尺寸
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // 其次，计算一个变换，以将文本字符串放置在图像的主对角线上 -
    // 从左上角到右下角。
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // 然后，设置变换。
    graphics.setTransform(transform);

    // 最后，在主对角线上放置水印（粉色文本字符串）。
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // 将带有水印的图像保存到另一个 EMF 文件。
    com.aspose.imaging.fileformats.emf.EmfImage scaledEmfImage = graphics.endRecording();
    try {
        scaledEmfImage.save(dir + "test.scaled.emf");
    } finally {
        scaledEmfImage.dispose();
    }
} finally {
    emfImage.dispose();
}
```

### drawString(String string, Font font, Color color, int x, int y, float angle) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-}
```
public void drawString(String string, Font font, Color color, int x, int y, float angle)
```


绘制字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 字符串 | java.lang.String | 该字符串。 |
| font | [Font](../../com.aspose.imaging/font) | 定义字符串文本格式的字体。 |
| color | [Color](../../com.aspose.imaging/color) | 文本颜色。 |
| x | int | 已绘制文本左上角的 x 坐标。 |
| y | int | 已绘制文本左上角的 y 坐标。 |
| angle | float | 角度（以度为单位），介于倾斜向量与设备的 x 轴之间。倾斜向量与文本行的基线平行。 |

### excludeClip(Rectangle rect) {#excludeClip-com.aspose.imaging.Rectangle-}
```
public void excludeClip(Rectangle rect)
```


更新此 Graphics 的剪裁区域，以排除由 Rectangle 结构指定的区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 指定要从剪裁区域排除的矩形的矩形结构。 |

### excludeClip(Region region) {#excludeClip-com.aspose.imaging.Region-}
```
public void excludeClip(Region region)
```


更新此 Graphics 的剪裁区域，以排除由 Region 指定的区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | 指定要从剪裁区域排除的区域。 |

### intersectClip(RectangleF rect) {#intersectClip-com.aspose.imaging.RectangleF-}
```
public void intersectClip(RectangleF rect)
```


更新此 Graphics 的剪裁区域，使其为当前剪裁区域与指定的 Rectangle 结构的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | 与当前剪裁区域相交的矩形结构。 |

### intersectClip(Region region) {#intersectClip-com.aspose.imaging.Region-}
```
public void intersectClip(Region region)
```


更新此 Graphics 的剪裁区域，使其为当前剪裁区域与指定的 Region 的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | 与当前区域相交的区域。 |

### resetClip() {#resetClip--}
```
public void resetClip()
```


重置剪裁。

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


将此 Graphics 的世界变换与指定的矩阵相乘。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 用于乘以世界变换的矩阵。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


按指定顺序将此 Graphics 的世界变换与指定的矩阵相乘。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | 用于乘以世界变换的矩阵。 |
| order | int | 乘法的顺序。 |

### translateTransform(float x, float y) {#translateTransform-float-float-}
```
public void translateTransform(float x, float y)
```


通过在此 Graphics 的变换矩阵前置指定的平移来更改坐标系的原点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 平移的 X 坐标。 |
| y | float | 平移的 Y 坐标。 |

### translateTransform(float x, float y, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float x, float y, int order)
```


按指定顺序将指定的平移应用于此 Graphics 的变换矩阵，以更改坐标系的原点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 平移的 X 坐标。 |
| y | float | 平移的 Y 坐标。 |
| order | int | 指定平移是预先添加到还是后附加到变换矩阵。 |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


将指定的旋转应用于此 Graphics 的变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 以度为单位的旋转角度。 |

### rotateTransform(float angle, PointF center, int order) {#rotateTransform-float-com.aspose.imaging.PointF-int-}
```
public void rotateTransform(float angle, PointF center, int order)
```


按指定顺序将指定的旋转应用于此 Graphics 的变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | float | 以度为单位的旋转角度。 |
| center | [PointF](../../com.aspose.imaging/pointf) | 旋转中心。 |
| order | int | 指定旋转是后附加到还是预先添加到矩阵变换。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


通过将指定的缩放操作前置到对象的变换矩阵中，应用于此 Graphics 的变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | float | X 方向的缩放因子。 |
| sy | float | Y 方向的缩放因子。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


按照指定顺序，将指定的缩放操作应用于此 Graphics 的变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | float | X 方向的缩放因子。 |
| sy | float | Y 方向的缩放因子。 |
| order | int | 指定缩放操作是预先添加到还是后附加到变换矩阵。 |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


获取世界变换。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - The transform matrix.
### setTransform(Matrix transform) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix transform)
```


设置变换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | 新的变换矩阵。 |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // 首先，获取图像尺寸
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // 其次，计算一个变换，以将文本字符串放置在图像的主对角线上 -
    // 从左上角到右下角。
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // 然后，设置变换。
    graphics.setTransform(transform);

    // 最后，在主对角线上放置水印（粉色文本字符串）。
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // 将带有水印的图像保存到另一个 EMF 文件。
    com.aspose.imaging.fileformats.emf.EmfImage scaledEmfImage = graphics.endRecording();
    try {
        scaledEmfImage.save(dir + "test.scaled.emf");
    } finally {
        scaledEmfImage.dispose();
    }
} finally {
    emfImage.dispose();
}
```

