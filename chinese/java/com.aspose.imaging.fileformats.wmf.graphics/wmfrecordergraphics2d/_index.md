---
title: "WmfRecorderGraphics2D"
second_title: "Aspose.Imaging for Java API 参考"
description: "Wmf 记录器。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.graphics.MetafileRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d)
```
public final class WmfRecorderGraphics2D extends MetafileRecorderGraphics2D
```

Wmf 记录器。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfRecorderGraphics2D(Rectangle frame, int inch)](#WmfRecorderGraphics2D-com.aspose.imaging.Rectangle-int-) | 初始化 `WmfRecorderGraphics2D` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | 获取或设置背景模式。 |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | 获取或设置背景模式。 |
| [endRecording()](#endRecording--) | 结束录制。 |
| [fromWmfImage(WmfImage wmfImage)](#fromWmfImage-com.aspose.imaging.fileformats.wmf.WmfImage-) | 获取现有 Wmf 图像的 Wmf 记录器实例。 |

## Example: This example shows how to create a WMF image and draw some geometric shapes using WmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// 这是默认的屏幕分辨率。
int dpi = 96;

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, imageWidth, imageHeight);

// 创建 WMF 图像。
com.aspose.imaging.fileformats.wmf.graphics.WmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.wmf.graphics.WmfRecorderGraphics2D(frame, dpi);

// 使用 1 像素宽的黑色笔在图像边框上绘制黑色矩形。
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// 使用 white-smoke 颜色填充矩形。
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// 使用 1 像素宽的 darkgreen 笔绘制两条对角线。
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

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
{
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, imageWidth, imageHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
}

// 绘制文本字符串
graphics.drawString("Hello World!", new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular), com.aspose.imaging.Color.getDarkRed(), 200, 300);

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
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = graphics.endRecording();
try {
    wmfImage.save(dir + "test.output.wmf");
} finally {
    wmfImage.dispose();
}
```

### WmfRecorderGraphics2D(Rectangle frame, int inch) {#WmfRecorderGraphics2D-com.aspose.imaging.Rectangle-int-}
```
public WmfRecorderGraphics2D(Rectangle frame, int inch)
```


初始化 `WmfRecorderGraphics2D` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| frame | [Rectangle](../../com.aspose.imaging/rectangle) | 用于显示元文件的目标矩形，单位为 twip。 |
| 英寸 | int | 每英寸的像素数。 |

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


获取或设置背景模式。

值：背景模式。

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


获取或设置背景模式。

值：背景模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### endRecording() {#endRecording--}
```
public WmfImage endRecording()
```


结束录制。

**Returns:**
[WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) - The result image.
### fromWmfImage(WmfImage wmfImage) {#fromWmfImage-com.aspose.imaging.fileformats.wmf.WmfImage-}
```
public static WmfRecorderGraphics2D fromWmfImage(WmfImage wmfImage)
```


获取现有 Wmf 图像的 Wmf 记录器实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| wmfImage | [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) | 用于获取记录器的 Wmf 图像。 |

**Returns:**
[WmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d) - An instance of the [WmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d) class.
