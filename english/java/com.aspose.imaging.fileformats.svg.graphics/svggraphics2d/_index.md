---
title: SvgGraphics2D
second_title: Aspose.Imaging for Java API Reference
description: Provides drawing commands to compose an Svg image.
type: docs
weight: 10
url: /java/com.aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---
**Inheritance:**
java.lang.Object
```
public class SvgGraphics2D
```

Provides drawing commands to compose an Svg image.
## Constructors

| Constructor | Description |
| --- | --- |
| [SvgGraphics2D(int width, int height, int dpi)](#SvgGraphics2D-int-int-int-) | Initializes a new instance of the [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) class. |
| [SvgGraphics2D(SvgImage image)](#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-) | Initializes a new instance of the [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) class. |
## Methods

| Method | Description |
| --- | --- |
| [drawImage(RasterImage image, Point origin)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Draws the specified image at the specified location. |
| [drawImage(RasterImage image, Point origin, Size size)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Draws the specified image of the specified size at the specified location. |
| [drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)](#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-) | Draws the specified portion of the specified image at the specified location and with the specified size. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Draws an arc representing a portion of an ellipse specified by a Rectangle structure. |
| [fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)](#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Fills an arc representing a portion of an ellipse specified by a Rectangle structure. |
| [drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Draws the cubic bezier. |
| [drawString(Font font, String text, Point origin, Color textColor)](#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-) | Draws the text string. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Draws the line. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Draws the path. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Fills the path. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Draws the rectangle. |
| [fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-) | Fills the rectangle. |
| [endRecording()](#endRecording--) | Gets the final Svg image which includes all drawing commands performed via [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) object. |

## Example: This example shows how to create an SVG image of the specified size and draw different shapes on it using SvgGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D graphics = new com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Draw a black rectangle along the image borders using a 1-pixel-wide black pen.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// Fill a rectangle with the color of white-smoke.
graphics.fillRectangle(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getWhiteSmoke(), 1),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()), 10, 10, 580, 380);

// Draw two diagonal lines using a 1-pixel-wide darkgreen pen.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// Draw an arc within the rectangle {0, 0, 200, 200} using a 2-pixel-wide blue pen.
graphics.drawArc(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
        new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Fill an arc
graphics.fillArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getLightCoral(), 10),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Draw a cubic bezier using a 2-pixel-wide red pen.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.PointF(0, 0),
        new com.aspose.imaging.PointF(200, 133),
        new com.aspose.imaging.PointF(400, 166),
        new com.aspose.imaging.PointF(600, 400));

// Draw a raster image of the specified size at the specified location.
// The image is scaled to fit the desired rectangle.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw, new com.aspose.imaging.Point(400, 200), new com.aspose.imaging.Size(100, 50));
} finally {
    imageToDraw.dispose();
}

// Draw a text string
graphics.drawString(
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        "Hello World!",
        new com.aspose.imaging.Point(200, 300),
        com.aspose.imaging.Color.getDarkRed());

// Create a path to fill
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

// Fill the path using a yellow brush and a green pen to draw outline
graphics.fillPath(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getYellow()), pathToFill);

// Create a path to draw
com.aspose.imaging.GraphicsPath pathToDraw = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figureToDraw = new com.aspose.imaging.Figure();
pathToDraw.addFigure(figureToDraw);

figureToDraw.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(200, 200, 200, 200), 0, 360),
        });

// Draw the path using a 5-pixel-wide orange pen.
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// Get the final SVG image which includes all drawing commands
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


Initializes a new instance of the [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The width of the output Svg image. |
| height | int | The width of the output Svg image. |
| dpi | int | The device resolution, e.g. 96 dots per inch. |

### SvgGraphics2D(SvgImage image) {#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-}
```
public SvgGraphics2D(SvgImage image)
```


Initializes a new instance of the [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) | The image to perform drawing operations on. |

### drawImage(RasterImage image, Point origin) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public final void drawImage(RasterImage image, Point origin)
```


Draws the specified image at the specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | The drawn image. |
| origin | [Point](../../com.aspose.imaging/point) | The location of the drawn image. |

### drawImage(RasterImage image, Point origin, Size size) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public final void drawImage(RasterImage image, Point origin, Size size)
```


Draws the specified image of the specified size at the specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | The drawn image. |
| origin | [Point](../../com.aspose.imaging/point) | The location of the drawn image. |
| size | [Size](../../com.aspose.imaging/size) | The desired size of the drawn image. |

### drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image) {#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-}
```
public final void drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```


Draws the specified portion of the specified image at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | The portion of the image object to draw. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | The location and size of the drawn image. The image is scaled to fit the rectangle. |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | The image to draw. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public final void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Draws an arc representing a portion of an ellipse specified by a Rectangle structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | The pen to draw the outline of the figure. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The boundaries of the ellipse. |
| startAngle | float | The angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| arcAngle | float | The angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle) {#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public final void fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)
```


Fills an arc representing a portion of an ellipse specified by a Rectangle structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | The pen to draw the outline of the figure. |
| brush | [Brush](../../com.aspose.imaging/brush) | The brush to fill the interior of the figure. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The boundaries of the ellipse. |
| startAngle | float | The angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| arcAngle | float | The angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public final void drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Draws the cubic bezier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | The pen that determines the color, width, and style of the figure. |
| pt1 | [PointF](../../com.aspose.imaging/pointf) | The starting point of the curve. |
| pt2 | [PointF](../../com.aspose.imaging/pointf) | The first control point for the curve. |
| pt3 | [PointF](../../com.aspose.imaging/pointf) | The second control point for the curve. |
| pt4 | [PointF](../../com.aspose.imaging/pointf) | The ending point of the curve. |

### drawString(Font font, String text, Point origin, Color textColor) {#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-}
```
public final void drawString(Font font, String text, Point origin, Color textColor)
```


Draws the text string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | The font used to render text. |
| text | java.lang.String | The unicode text string. |
| origin | [Point](../../com.aspose.imaging/point) | The top-left corner of the text run. |
| textColor | [Color](../../com.aspose.imaging/color) | The text color. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Draws the line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | The pen that determines the color, width, and style of the figure. |
| x1 | int | The x-coordinate of the first point. |
| y1 | int | The y-coordinate of the first point. |
| x2 | int | The x-coordinate of the second point. |
| y2 | int | The y-coordinate of the second point. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public final void drawPath(Pen pen, GraphicsPath path)
```


Draws the path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | The pen to draw the outline of the figure. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The path to draw. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public final void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Fills the path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | The pen to draw the outline of the figure. |
| brush | [Brush](../../com.aspose.imaging/brush) | The brush to fill the interior of the figure. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The path to draw. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Draws the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | The pen to draw the outline of the figure. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | The width of the rectangle to draw. |
| height | int | The height of the rectangle to draw. |

### fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-}
```
public final void fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)
```


Fills the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | The pen to draw the outline of the figure. |
| brush | [Brush](../../com.aspose.imaging/brush) | The brush to fill the interior of the figure. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | The width of the rectangle to draw. |
| height | int | The height of the rectangle to draw. |

### endRecording() {#endRecording--}
```
public final SvgImage endRecording()
```


Gets the final Svg image which includes all drawing commands performed via [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) object.

**Returns:**
[SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) - The final Svg image.
