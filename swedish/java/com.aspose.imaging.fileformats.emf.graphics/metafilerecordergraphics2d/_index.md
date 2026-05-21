---
title: "MetafileRecorderGraphics2D"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den metafiler inspelningsgrafik"
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
**Inheritance:**
java.lang.Object
```
public abstract class MetafileRecorderGraphics2D
```

Den metafiler inspelningsgrafik
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MetafileRecorderGraphics2D()](#MetafileRecorderGraphics2D--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getClip()](#getClip--) | Hämtar eller anger en Region som begränsar ritområdet för denna Graphics |
| [setClip(Region value)](#setClip-com.aspose.imaging.Region-) | Hämtar eller anger en Region som begränsar ritområdet för denna Graphics |
| [getClipBounds()](#getClipBounds--) | Hämtar beskärningsgränserna. |
| [getBackgroundColor()](#getBackgroundColor--) | Hämtar bakgrundens färg. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Anger bakgrundens färg. |
| [clear()](#clear--) | Rensar tillståndet för grafikobjektet |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Ritar en båge som representerar en del av en ellips specificerad av en rektangelstruktur. |
| [drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Ritar den kubiska Bézier-kurvan. |
| [drawPolyCubicBezier(Pen pen, Point[] points)](#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Ritar den polygonala kubiska Bézier-kurvan. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Ritar ellipsen. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Fyller ellipsen. |
| [drawImage(RasterImage image, Point location)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Ritar den angivna bilden, med dess ursprungliga fysiska storlek, på den angivna platsen. |
| [drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)](#drawImage-byte---com.aspose.imaging.Rectangle-int-) | Ritar bilden. |
| [drawImage(InputStream stream, Rectangle destRect, int srcUnit)](#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-) | Ritar bilden. |
| [drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-) | Ritar den angivna delen av den angivna bilden på den angivna platsen och med den angivna storleken. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Ritar linjen. |
| [drawLine(Pen pen, Point pt1, Point pt2)](#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Ritar linjen. |
| [drawPolyline(Pen pen, Point[] points)](#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Ritar polylinjen. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Ritar banan. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Fyller banan. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Ritar pajen. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Fyller pajen. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Ritar polygonen. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---) | Fyller polygonen. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-) | Fyller polygonen. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Ritar rektangeln. |
| [drawRectangle(Pen pen, Rectangle rectangle)](#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Ritar rektangeln. |
| [fillRectangle(Brush brush, Rectangle rectangle)](#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Fyller rektangeln. |
| [drawString(String string, Font font, Color color, int x, int y)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-) | Ritar strängen. |
| [drawString(String string, Font font, Color color, int x, int y, float angle)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-) | Ritar strängen. |
| [excludeClip(Rectangle rect)](#excludeClip-com.aspose.imaging.Rectangle-) | Uppdaterar klippområdet för detta Graphics för att utesluta området som anges av en rektangelstruktur. |
| [excludeClip(Region region)](#excludeClip-com.aspose.imaging.Region-) | Uppdaterar klippområdet för detta Graphics för att utesluta området som anges av en region. |
| [intersectClip(RectangleF rect)](#intersectClip-com.aspose.imaging.RectangleF-) | Uppdaterar klippområdet för detta Graphics till skärningspunkten mellan det aktuella klippområdet och den angivna rektangelstrukturen. |
| [intersectClip(Region region)](#intersectClip-com.aspose.imaging.Region-) | Uppdaterar klippområdet för detta Graphics till skärningspunkten mellan det aktuella klippområdet och den angivna regionen. |
| [resetClip()](#resetClip--) | Återställer klippet. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multiplicerar världstransformationen för detta Graphics med den angivna matrisen. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multiplicerar världstransformationen för detta Graphics med den angivna matrisen i angiven ordning. |
| [translateTransform(float x, float y)](#translateTransform-float-float-) | Ändrar ursprunget för koordinatsystemet genom att föregå den angivna förflyttningen till transformationsmatrisen för detta Graphics. |
| [translateTransform(float x, float y, int order)](#translateTransform-float-float-int-) | Ändrar ursprunget för koordinatsystemet genom att applicera den angivna förflyttningen på transformationsmatrisen för detta Graphics i angiven ordning. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Applicerar den angivna rotationen på transformationsmatrisen för detta Graphics. |
| [rotateTransform(float angle, PointF center, int order)](#rotateTransform-float-com.aspose.imaging.PointF-int-) | Applicerar den angivna rotationen på transformationsmatrisen för detta Graphics i angiven ordning. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Applicerar den angivna skalningsoperationen på transformationsmatrisen för detta Graphics genom att föregå den till objektets transformationsmatris. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Applicerar den angivna skalningsoperationen på transformationsmatrisen för detta Graphics i angiven ordning. |
| [getTransform()](#getTransform--) | Hämtar världstransformationen. |
| [setTransform(Matrix transform)](#setTransform-com.aspose.imaging.Matrix-) | Ställer in transformen. |

## Example: This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

// Bildens storlek i pixlar
int deviceWidth = 600;
int deviceHeight = 400;

// Bildens storlek i millimeter
int deviceWidthMm = (int) (deviceWidth / 100f);
int deviceHeightMm = (int) (deviceHeight / 100f);

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Skapa en EMF‑bild.
com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D(
                frame,
                new com.aspose.imaging.Size(deviceWidth, deviceHeight),
                new com.aspose.imaging.Size(deviceWidthMm, deviceHeightMm));

// Rita en svart rektangel längs bildens kanter med en 1‑pixel bred svart penna.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, deviceWidth, deviceHeight);

// Fyll en rektangel med färgen white‑smoke.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// Rita två diagonala linjer med en 1‑pixel bred darkgreen‑penna.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, deviceWidth, deviceHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, deviceHeight, deviceWidth, 0);

// Rita en båge inom rektangeln {0, 0, 200, 200} med en 2‑pixel bred blå penna.
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Fyll en båge
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Rita en kubisk Bézier med en 2‑pixel bred röd penna.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// Rita en rasterbild av angiven storlek på den angivna platsen.
// Bilden skalas för att passa den önskade rektangeln.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
} finally {
    imageToDraw.dispose();
}

// Rita en textsträng
graphics.drawString("Hello World!",
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        com.aspose.imaging.Color.getDarkRed(), 200, 300);

// Skapa en bana för att fylla
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

// Fyll banan med en gul pensel och en grön penna för att rita konturen
graphics.fillPath(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getYellow()), pathToFill);

// Skapa en bana för att rita
com.aspose.imaging.GraphicsPath pathToDraw = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figureToDraw = new com.aspose.imaging.Figure();
pathToDraw.addFigure(figureToDraw);

figureToDraw.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(200, 200, 200, 200), 0, 360),
        });

// Rita banan med en 5‑pixel bred orange penna.
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// För att rasterisera SVG måste vi specificera rasteriseringsalternativ.
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// Hämta den slutgiltiga WMF‑bilden som inkluderar alla ritkommandon
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


Hämtar eller anger en Region som begränsar ritområdet för denna Graphics

**Returns:**
[Region](../../com.aspose.imaging/region) - The clip region.
### setClip(Region value) {#setClip-com.aspose.imaging.Region-}
```
public void setClip(Region value)
```


Hämtar eller anger en Region som begränsar ritområdet för denna Graphics

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Region](../../com.aspose.imaging/region) | Klippområdet. |

### getClipBounds() {#getClipBounds--}
```
public RectangleF getClipBounds()
```


Hämtar beskärningsgränserna.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The clip bounds.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Hämtar bakgrundens färg.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of the background.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Anger bakgrundens färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Bakgrundens färg. |

### clear() {#clear--}
```
public void clear()
```


Rensar tillståndet för grafikobjektet

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Ritar en båge som representerar en del av en ellips specificerad av en rektangelstruktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Ellipsens gränser. |
| startAngle | float | Vinkel i grader mätt medurs från x-axeln till startpunkten för bågen. |
| arcAngle | float | Vinkel i grader mätt medurs från startAngle-parametern till arcens slutpunkt. |

### drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Ritar den kubiska Bézier-kurvan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| pt1 | [Point](../../com.aspose.imaging/point) | Startpunkten för kurvan. |
| pt2 | [Point](../../com.aspose.imaging/point) | Den första kontrollpunkten för kurvan. |
| pt3 | [Point](../../com.aspose.imaging/point) | Den andra kontrollpunkten för kurvan. |
| pt4 | [Point](../../com.aspose.imaging/point) | Slutpunkten för kurvan. |

### drawPolyCubicBezier(Pen pen, Point[] points) {#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyCubicBezier(Pen pen, Point[] points)
```


Ritar den polygonala kubiska Bézier-kurvan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Punkterna. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Ritar ellipsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Ellipsens gränser. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Fyller ellipsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pensel som bestämmer egenskaperna för fyllningen. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Ellipsens gränser. |

### drawImage(RasterImage image, Point location) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public void drawImage(RasterImage image, Point location)
```


Ritar den angivna bilden, med dess ursprungliga fysiska storlek, på den angivna platsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden som ska ritas. |
| location | [Point](../../com.aspose.imaging/point) | Platsen för det övre vänstra hörnet av den ritade bilden. |

### drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit) {#drawImage-byte---com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)
```


Ritar bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageBytes | byte[] | Bildens byte. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Dest-rektangeln. |
| srcUnit | int | Källenheten. |

### drawImage(InputStream stream, Rectangle destRect, int srcUnit) {#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(InputStream stream, Rectangle destRect, int srcUnit)
```


Ritar bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Strömmen. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Dest-rektangeln. |
| srcUnit | int | Källenheten. |

### drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-}
```
public void drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)
```


Ritar den angivna delen av den angivna bilden på den angivna platsen och med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bilden som ska ritas. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangelstruktur som specificerar platsen och storleken på den ritade bilden. Bilden skalas för att passa rektangeln. |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangelstruktur som specificerar den del av bildobjektet som ska ritas. |
| srcUnit | int | Måttenheterna som används av srcRect-parametern. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Ritar linjen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| x1 | int | X-koordinaten för den första punkten. |
| y1 | int | Y-koordinaten för den första punkten. |
| x2 | int | X-koordinaten för den andra punkten. |
| y2 | int | Y-koordinaten för den andra punkten. |

### drawLine(Pen pen, Point pt1, Point pt2) {#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawLine(Pen pen, Point pt1, Point pt2)
```


Ritar linjen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| pt1 | [Point](../../com.aspose.imaging/point) | Den första punkten. |
| pt2 | [Point](../../com.aspose.imaging/point) | Den andra punkten. |

### drawPolyline(Pen pen, Point[] points) {#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyline(Pen pen, Point[] points)
```


Ritar polylinjen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Punkterna. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Ritar banan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Sökvägen att rita. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Fyller banan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| brush | [Brush](../../com.aspose.imaging/brush) | Pensel som bestämmer egenskaperna för fyllningen. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Sökvägen att fylla. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Ritar pajen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Ellipsens gränser. |
| startAngle | float | Vinkel i grader mätt medurs från x-axeln till startpunkten för bågen. |
| sweepAngle | float | Vinkel i grader mätt medurs från startAngle-parametern till arcens slutpunkt. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Fyller pajen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pensel som bestämmer egenskaperna för fyllningen. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Ellipsens gränser. |
| startAngle | float | Vinkel i grader mätt medurs från x-axeln till startpunkten för bågen. |
| sweepAngle | float | Vinkel i grader mätt medurs från startAngle-parametern till arcens slutpunkt. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Ritar polygonen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Punkterna. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Fyller polygonen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pensel som bestämmer egenskaperna för fyllningen. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Punkterna. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Fyller polygonen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pensel som bestämmer egenskaperna för fyllningen. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Punkterna. |
| fillMode | int | Fyllningsläget. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Ritar rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| x | int | X-koordinaten för den övre vänstra hörnet av rektangeln som ska ritas. |
| y | int | Y-koordinaten för den övre vänstra hörnet av rektangeln som ska ritas. |
| bredd | int | Bredden på rektangeln som ska ritas. |
| höjd | int | Höjden på rektangeln som ska ritas. |

### drawRectangle(Pen pen, Rectangle rectangle) {#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rectangle)
```


Ritar rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Penna som bestämmer färg, bredd och stil för figuren. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln som ska ritas. |

### fillRectangle(Brush brush, Rectangle rectangle) {#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rectangle)
```


Fyller rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pensel som bestämmer egenskaperna för fyllningen. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln som ska fyllas. |

### drawString(String string, Font font, Color color, int x, int y) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-}
```
public void drawString(String string, Font font, Color color, int x, int y)
```


Ritar strängen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sträng | java.lang.String | Strängen. |
| font | [Font](../../com.aspose.imaging/font) | Typsnitt som definierar textformatet för strängen. |
| color | [Color](../../com.aspose.imaging/color) | Textfärgen. |
| x | int | X-koordinaten för den övre vänstra hörnet av den ritade texten. |
| y | int | Y-koordinaten för den övre vänstra hörnet av den ritade texten. |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // Först, hämta bildens storlek
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // För det andra, beräkna en transformation för att placera en textsträng längs bildens huvuddiagonal -
    // från övre vänstra till nedre högra hörnet.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Sedan, ställ in transformationen.
    graphics.setTransform(transform);

    // Slutligen, placera ett vattenmärke (textsträng i rosa färg) längs huvuddiagonalen.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Spara bilden med vattenmärke till en annan EMF-fil.
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


Ritar strängen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sträng | java.lang.String | Strängen. |
| font | [Font](../../com.aspose.imaging/font) | Typsnitt som definierar textformatet för strängen. |
| color | [Color](../../com.aspose.imaging/color) | Textfärgen. |
| x | int | X-koordinaten för den övre vänstra hörnet av den ritade texten. |
| y | int | Y-koordinaten för den övre vänstra hörnet av den ritade texten. |
| angle | float | Vinkeln i grader mellan escapementvektorn och enhetens x-axel. Escapementvektorn är parallell med baslinjen för en rad text. |

### excludeClip(Rectangle rect) {#excludeClip-com.aspose.imaging.Rectangle-}
```
public void excludeClip(Rectangle rect)
```


Uppdaterar klippområdet för detta Graphics för att utesluta området som anges av en rektangelstruktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangelstruktur som specificerar rektangeln att utesluta från klippregionen. |

### excludeClip(Region region) {#excludeClip-com.aspose.imaging.Region-}
```
public void excludeClip(Region region)
```


Uppdaterar klippområdet för detta Graphics för att utesluta området som anges av en region.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Region som specificerar regionen att utesluta från klippregionen. |

### intersectClip(RectangleF rect) {#intersectClip-com.aspose.imaging.RectangleF-}
```
public void intersectClip(RectangleF rect)
```


Uppdaterar klippområdet för detta Graphics till skärningspunkten mellan det aktuella klippområdet och den angivna rektangelstrukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Rektangelstruktur för att skära med den aktuella klippregionen. |

### intersectClip(Region region) {#intersectClip-com.aspose.imaging.Region-}
```
public void intersectClip(Region region)
```


Uppdaterar klippområdet för detta Graphics till skärningspunkten mellan det aktuella klippområdet och den angivna regionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Region för att skära med den aktuella regionen. |

### resetClip() {#resetClip--}
```
public void resetClip()
```


Återställer klippet.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multiplicerar världstransformationen för detta Graphics med den angivna matrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Matrisen som multiplicerar världstransformationen. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multiplicerar världstransformationen för detta Graphics med den angivna matrisen i angiven ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Matrisen som multiplicerar världstransformationen. |
| order | int | Multiplikationsordningen. |

### translateTransform(float x, float y) {#translateTransform-float-float-}
```
public void translateTransform(float x, float y)
```


Ändrar ursprunget för koordinatsystemet genom att föregå den angivna förflyttningen till transformationsmatrisen för detta Graphics.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för förflyttningen. |
| y | float | Y-koordinaten för förflyttningen. |

### translateTransform(float x, float y, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float x, float y, int order)
```


Ändrar ursprunget för koordinatsystemet genom att applicera den angivna förflyttningen på transformationsmatrisen för detta Graphics i angiven ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för förflyttningen. |
| y | float | Y-koordinaten för förflyttningen. |
| order | int | Anger om förskjutningen läggs till i början eller i slutet av transformationsmatrisen. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Applicerar den angivna rotationen på transformationsmatrisen för detta Graphics.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkel i grader. |

### rotateTransform(float angle, PointF center, int order) {#rotateTransform-float-com.aspose.imaging.PointF-int-}
```
public void rotateTransform(float angle, PointF center, int order)
```


Applicerar den angivna rotationen på transformationsmatrisen för detta Graphics i angiven ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkel i grader. |
| center | [PointF](../../com.aspose.imaging/pointf) | Rotationscentrum. |
| order | int | Anger om rotationen läggs till i början eller i slutet av matrisomvandlingen. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Applicerar den angivna skalningsoperationen på transformationsmatrisen för detta Graphics genom att föregå den till objektets transformationsmatris.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Skalfaktor i x-riktning. |
| sy | float | Skalfaktor i y-riktning. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Applicerar den angivna skalningsoperationen på transformationsmatrisen för detta Graphics i angiven ordning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sx | float | Skalfaktor i x-riktning. |
| sy | float | Skalfaktor i y-riktning. |
| order | int | Anger om skalningsoperationen läggs till i början eller i slutet av transformationsmatrisen. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Hämtar världstransformationen.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - The transform matrix.
### setTransform(Matrix transform) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix transform)
```


Ställer in transformen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Den nya transformationsmatrisen. |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // Först, hämta bildens storlek
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // För det andra, beräkna en transformation för att placera en textsträng längs bildens huvuddiagonal -
    // från övre vänstra till nedre högra hörnet.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Sedan, ställ in transformationen.
    graphics.setTransform(transform);

    // Slutligen, placera ett vattenmärke (textsträng i rosa färg) längs huvuddiagonalen.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Spara bilden med vattenmärke till en annan EMF-fil.
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

