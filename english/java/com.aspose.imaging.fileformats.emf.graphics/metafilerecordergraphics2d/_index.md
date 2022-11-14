---
title: MetafileRecorderGraphics2D
second_title: Aspose.Imaging for Java API Reference
description: The metafiles recorder graphics
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
**Inheritance:**
java.lang.Object
```
public abstract class MetafileRecorderGraphics2D
```

The metafiles recorder graphics
## Constructors

| Constructor | Description |
| --- | --- |
| [MetafileRecorderGraphics2D()](#MetafileRecorderGraphics2D--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getClip()](#getClip--) | Gets or sets a Region that limits the drawing region of this Graphics |
| [setClip(Region value)](#setClip-com.aspose.imaging.Region-) | Gets or sets a Region that limits the drawing region of this Graphics |
| [getClipBounds()](#getClipBounds--) | Gets the clip bounds. |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the color of the background. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Sets the color of the background. |
| [clear()](#clear--) | Clears the state of the graphics object |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Draws an arc representing a portion of an ellipse specified by a Rectangle structure. |
| [drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Draws the cubic bezier. |
| [drawPolyCubicBezier(Pen pen, Point[] points)](#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Draws the poly cubic bezier. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Draws the ellipse. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Fills the ellipse. |
| [drawImage(RasterImage image, Point location)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Draws the specified Image, using its original physical size, at the specified location. |
| [drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)](#drawImage-byte---com.aspose.imaging.Rectangle-int-) | Draws the image. |
| [drawImage(InputStream stream, Rectangle destRect, int srcUnit)](#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-) | Draws the image. |
| [drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-) | Draws the specified portion of the specified Image at the specified location and with the specified size. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Draws the line. |
| [drawLine(Pen pen, Point pt1, Point pt2)](#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Draws the line. |
| [drawPolyline(Pen pen, Point[] points)](#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Draws the polyline. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Draws the path. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Fills the path. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Draws the pie. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Fills the pie. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Draws the polygon. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---) | Fills the polygon. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-) | Fills the polygon. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Draws the rectangle. |
| [drawRectangle(Pen pen, Rectangle rectangle)](#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Draws the rectangle. |
| [fillRectangle(Brush brush, Rectangle rectangle)](#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Fills the rectangle. |
| [drawString(String string, Font font, Color color, int x, int y)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-) | Draws the string. |
| [drawString(String string, Font font, Color color, int x, int y, float angle)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-) | Draws the string. |
| [excludeClip(Rectangle rect)](#excludeClip-com.aspose.imaging.Rectangle-) | Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure. |
| [excludeClip(Region region)](#excludeClip-com.aspose.imaging.Region-) | Updates the clip region of this Graphics to exclude the area specified by a Region. |
| [intersectClip(RectangleF rect)](#intersectClip-com.aspose.imaging.RectangleF-) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure. |
| [intersectClip(Region region)](#intersectClip-com.aspose.imaging.Region-) | Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region. |
| [resetClip()](#resetClip--) | Resets the clip. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multiplies the world transformation of this Graphics and specified the Matrix. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multiplies the world transformation of this Graphics and specified the Matrix in the specified order. |
| [translateTransform(float x, float y)](#translateTransform-float-float-) | Changes the origin of the coordinate system by prepending the specified translation to the transformation matrix of this Graphics. |
| [translateTransform(float x, float y, int order)](#translateTransform-float-float-int-) | Changes the origin of the coordinate system by applying the specified translation to the transformation matrix of this Graphics in the specified order. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Applies the specified rotation to the transformation matrix of this Graphics. |
| [rotateTransform(float angle, PointF center, int order)](#rotateTransform-float-com.aspose.imaging.PointF-int-) | Applies the specified rotation to the transformation matrix of this Graphics in the specified order. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Applies the specified scaling operation to the transformation matrix of this Graphics by prepending it to the object's transformation matrix. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Applies the specified scaling operation to the transformation matrix of this Graphics in the specified order. |
| [getTransform()](#getTransform--) | Gets the world transform. |
| [setTransform(Matrix transform)](#setTransform-com.aspose.imaging.Matrix-) | Sets the transform. |

## Example
This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D.
``` java
String dir = "c:\\temp\\";

// The image size in pixels
int deviceWidth = 600;
int deviceHeight = 400;

// The image size in millimeters
int deviceWidthMm = (int) (deviceWidth / 100f);
int deviceHeightMm = (int) (deviceHeight / 100f);

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Create a EMF image.
com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D(
                frame,
                new com.aspose.imaging.Size(deviceWidth, deviceHeight),
                new com.aspose.imaging.Size(deviceWidthMm, deviceHeightMm));

// Draw a black rectangle along the image borders using a 1-pixel-wide black pen.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, deviceWidth, deviceHeight);

// Fill a rectangle with the color of white-smoke.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// Draw two diagonal lines using a 1-pixel-wide darkgreen pen.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, deviceWidth, deviceHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, deviceHeight, deviceWidth, 0);

// Draw an arc within the rectangle {0, 0, 200, 200} using a 2-pixel-wide blue pen.
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Fill an arc
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Draw a cubic bezier using a 2-pixel-wide red pen.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// Draw a raster image of the specified size at the specified location.
// The image is scaled to fit the desired rectangle.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
} finally {
    imageToDraw.dispose();
}

// Draw a text string
graphics.drawString("Hello World!",
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        com.aspose.imaging.Color.getDarkRed(), 200, 300);

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
                new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
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

// In order to rasterize SVG we need to specify rasterization options.
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// Get the final WMF image which includes all drawing commands
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


Gets or sets a Region that limits the drawing region of this Graphics

**Returns:**
[Region](../../com.aspose.imaging/region) - The clip region.
### setClip(Region value) {#setClip-com.aspose.imaging.Region-}
```
public void setClip(Region value)
```


Gets or sets a Region that limits the drawing region of this Graphics

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Region](../../com.aspose.imaging/region) | The clip region. |

### getClipBounds() {#getClipBounds--}
```
public RectangleF getClipBounds()
```


Gets the clip bounds.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The clip bounds.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets the color of the background.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of the background.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Sets the color of the background.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | The color of the background. |

### clear() {#clear--}
```
public void clear()
```


Clears the state of the graphics object

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Draws an arc representing a portion of an ellipse specified by a Rectangle structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The boundaries of the ellipse. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| arcAngle | float | Angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Draws the cubic bezier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| pt1 | [Point](../../com.aspose.imaging/point) | The starting point of the curve. |
| pt2 | [Point](../../com.aspose.imaging/point) | The first control point for the curve. |
| pt3 | [Point](../../com.aspose.imaging/point) | The second control point for the curve. |
| pt4 | [Point](../../com.aspose.imaging/point) | The ending point of the curve. |

### drawPolyCubicBezier(Pen pen, Point[] points) {#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyCubicBezier(Pen pen, Point[] points)
```


Draws the poly cubic bezier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| points | [Point\[\]](../../com.aspose.imaging/point) | The points. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Draws the ellipse.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The boundaries of the ellipse. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Fills the ellipse.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Brush that determines the characteristics of the fill. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The boundaries of the ellipse. |

### drawImage(RasterImage image, Point location) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public void drawImage(RasterImage image, Point location)
```


Draws the specified Image, using its original physical size, at the specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | The image to draw. |
| location | [Point](../../com.aspose.imaging/point) | The location of the upper-left corner of the drawn image. |

### drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit) {#drawImage-byte---com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)
```


Draws the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageBytes | byte[] | The image bytes. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | The dest rect. |
| srcUnit | int | The source unit. |

### drawImage(InputStream stream, Rectangle destRect, int srcUnit) {#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(InputStream stream, Rectangle destRect, int srcUnit)
```


Draws the image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | The dest rect. |
| srcUnit | int | The source unit. |

### drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-}
```
public void drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)
```


Draws the specified portion of the specified Image at the specified location and with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | The image to draw. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Rectangle structure that specifies the location and size of the drawn image. The image is scaled to fit the rectangle. |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | Rectangle structure that specifies the portion of the image object to draw. |
| srcUnit | int | The units of measure used by the srcRect parameter. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Draws the line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| x1 | int | The x-coordinate of the first point. |
| y1 | int | The y-coordinate of the first point. |
| x2 | int | The x-coordinate of the second point. |
| y2 | int | The y-coordinate of the second point. |

### drawLine(Pen pen, Point pt1, Point pt2) {#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawLine(Pen pen, Point pt1, Point pt2)
```


Draws the line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| pt1 | [Point](../../com.aspose.imaging/point) | The first point. |
| pt2 | [Point](../../com.aspose.imaging/point) | The second point. |

### drawPolyline(Pen pen, Point[] points) {#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyline(Pen pen, Point[] points)
```


Draws the polyline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| points | [Point\[\]](../../com.aspose.imaging/point) | The points. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Draws the path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The path to draw. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Fills the path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| brush | [Brush](../../com.aspose.imaging/brush) | Brush that determines the characteristics of the fill. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | The path to fill. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Draws the pie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The boundaries of the ellipse. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | float | Angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Fills the pie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Brush that determines the characteristics of the fill. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The boundaries of the ellipse. |
| startAngle | float | Angle in degrees measured clockwise from the x-axis to the starting point of the arc. |
| sweepAngle | float | Angle in degrees measured clockwise from the startAngle parameter to ending point of the arc. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Draws the polygon.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| points | [Point\[\]](../../com.aspose.imaging/point) | The points. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Fills the polygon.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Brush that determines the characteristics of the fill. |
| points | [Point\[\]](../../com.aspose.imaging/point) | The points. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Fills the polygon.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Brush that determines the characteristics of the fill. |
| points | [Point\[\]](../../com.aspose.imaging/point) | The points. |
| fillMode | int | The fill mode. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Draws the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| x | int | The x-coordinate of the upper-left corner of the rectangle to draw. |
| y | int | The y-coordinate of the upper-left corner of the rectangle to draw. |
| width | int | The width of the rectangle to draw. |
| height | int | The height of the rectangle to draw. |

### drawRectangle(Pen pen, Rectangle rectangle) {#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rectangle)
```


Draws the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Pen that determines the color, width, and style of the figure. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle to draw. |

### fillRectangle(Brush brush, Rectangle rectangle) {#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rectangle)
```


Fills the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Brush that determines the characteristics of the fill. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle to fill. |

### drawString(String string, Font font, Color color, int x, int y) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-}
```
public void drawString(String string, Font font, Color color, int x, int y)
```


Draws the string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| string | java.lang.String | The string. |
| font | [Font](../../com.aspose.imaging/font) | Font that defines the text format of the string. |
| color | [Color](../../com.aspose.imaging/color) | The text color. |
| x | int | The x-coordinate of the upper-left corner of the drawn text. |
| y | int | The y-coordinate of the upper-left corner of the drawn text. |


**Example:**
This example shows how to load a EMF image from a file and draw a text string over it.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // First, get the image size
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // Second, calculate a transformation to put a text string along the main diagonal of the image -
    // from the upper-left to the bootom-right corner.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Then, set the transform.
    graphics.setTransform(transform);

    // Finally, put a watermark (text string of pink color) along the main diagonal.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Save the image with watermark to another EMF file.
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


Draws the string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| string | java.lang.String | The string. |
| font | [Font](../../com.aspose.imaging/font) | Font that defines the text format of the string. |
| color | [Color](../../com.aspose.imaging/color) | The text color. |
| x | int | The x-coordinate of the upper-left corner of the drawn text. |
| y | int | The y-coordinate of the upper-left corner of the drawn text. |
| angle | float | The angle in degrees, between the escapement vector and the x-axis of the device. The escapement vector is parallel to the baseline of a row of text. |

### excludeClip(Rectangle rect) {#excludeClip-com.aspose.imaging.Rectangle-}
```
public void excludeClip(Rectangle rect)
```


Updates the clip region of this Graphics to exclude the area specified by a Rectangle structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Rectangle structure that specifies the rectangle to exclude from the clip region. |

### excludeClip(Region region) {#excludeClip-com.aspose.imaging.Region-}
```
public void excludeClip(Region region)
```


Updates the clip region of this Graphics to exclude the area specified by a Region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Region that specifies the region to exclude from the clip region. |

### intersectClip(RectangleF rect) {#intersectClip-com.aspose.imaging.RectangleF-}
```
public void intersectClip(RectangleF rect)
```


Updates the clip region of this Graphics to the intersection of the current clip region and the specified Rectangle structure.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Rectangle structure to intersect with the current clip region. |

### intersectClip(Region region) {#intersectClip-com.aspose.imaging.Region-}
```
public void intersectClip(Region region)
```


Updates the clip region of this Graphics to the intersection of the current clip region and the specified Region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Region to intersect with the current region. |

### resetClip() {#resetClip--}
```
public void resetClip()
```


Resets the clip.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplies the world transformation of this Graphics and specified the Matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The matrix that multiplies the world transformation. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplies the world transformation of this Graphics and specified the Matrix in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The matrix that multiplies the world transformation. |
| order | int | The order of the multiplication. |

### translateTransform(float x, float y) {#translateTransform-float-float-}
```
public void translateTransform(float x, float y)
```


Changes the origin of the coordinate system by prepending the specified translation to the transformation matrix of this Graphics.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the translation. |
| y | float | The y-coordinate of the translation. |

### translateTransform(float x, float y, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float x, float y, int order)
```


Changes the origin of the coordinate system by applying the specified translation to the transformation matrix of this Graphics in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | The x-coordinate of the translation. |
| y | float | The y-coordinate of the translation. |
| order | int | Specifies whether the translation is prepended or appended to the transformation matrix. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Applies the specified rotation to the transformation matrix of this Graphics.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | Angle of rotation in degrees. |

### rotateTransform(float angle, PointF center, int order) {#rotateTransform-float-com.aspose.imaging.PointF-int-}
```
public void rotateTransform(float angle, PointF center, int order)
```


Applies the specified rotation to the transformation matrix of this Graphics in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| angle | float | Angle of rotation in degrees. |
| center | [PointF](../../com.aspose.imaging/pointf) | The rotating center. |
| order | int | Specifies whether the rotation is appended or prepended to the matrix transformation. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Applies the specified scaling operation to the transformation matrix of this Graphics by prepending it to the object's transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | Scale factor in the x direction. |
| sy | float | Scale factor in the y direction. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Applies the specified scaling operation to the transformation matrix of this Graphics in the specified order.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sx | float | Scale factor in the x direction. |
| sy | float | Scale factor in the y direction. |
| order | int | Specifies whether the scaling operation is prepended or appended to the transformation matrix. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Gets the world transform.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - The transform matrix.
### setTransform(Matrix transform) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix transform)
```


Sets the transform.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | The new transform matrix. |


**Example:**
This example shows how to load a EMF image from a file and draw a text string over it.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // First, get the image size
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // Second, calculate a transformation to put a text string along the main diagonal of the image -
    // from the upper-left to the bootom-right corner.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Then, set the transform.
    graphics.setTransform(transform);

    // Finally, put a watermark (text string of pink color) along the main diagonal.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Save the image with watermark to another EMF file.
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

