---
title: "SvgGraphics2D"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt Zeichenbefehle bereit, um ein Svg-Bild zusammenzusetzen."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---
**Inheritance:**
java.lang.Object
```
public class SvgGraphics2D
```

Stellt Zeichenbefehle bereit, um ein Svg-Bild zusammenzusetzen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SvgGraphics2D(int width, int height, int dpi)](#SvgGraphics2D-int-int-int-) | Initialisiert eine neue Instanz der Klasse [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
| [SvgGraphics2D(SvgImage image)](#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-) | Initialisiert eine neue Instanz der Klasse [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [drawImage(RasterImage image, Point origin)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Zeichnet das angegebene Bild am angegebenen Ort. |
| [drawImage(RasterImage image, Point origin, Size size)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Zeichnet das angegebene Bild in der angegebenen Größe am angegebenen Ort. |
| [drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)](#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-) | Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und in der angegebenen Größe. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine Rechteckstruktur angegeben ist. |
| [fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)](#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Füllt einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine Rechteckstruktur angegeben ist. |
| [drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Zeichnet die kubische Bézierkurve. |
| [drawString(Font font, String text, Point origin, Color textColor)](#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-) | Zeichnet die Textzeichenfolge. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Zeichnet die Linie. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Zeichnet den Pfad. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Füllt den Pfad. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Zeichnet das Rechteck. |
| [fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-) | Füllt das Rechteck. |
| [endRecording()](#endRecording--) | Ruft das endgültige Svg-Bild ab, das alle über das Objekt [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) ausgeführten Zeichenbefehle enthält. |

## Example: This example shows how to create an SVG image of the specified size and draw different shapes on it using SvgGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D graphics = new com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Zeichne ein schwarzes Rechteck entlang der Bildränder mit einem 1 Pixel breiten schwarzen Stift.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// Fülle ein Rechteck mit der Farbe white-smoke.
graphics.fillRectangle(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getWhiteSmoke(), 1),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()), 10, 10, 580, 380);

// Zeichne zwei diagonale Linien mit einem 1 Pixel breiten darkgreen Stift.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// Zeichne einen Bogen innerhalb des Rechtecks {0, 0, 200, 200} mit einem 2 Pixel breiten blauen Stift.
graphics.drawArc(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
        new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Fülle einen Bogen
graphics.fillArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getLightCoral(), 10),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Zeichne einen kubischen Bezier mit einem 2 Pixel breiten roten Stift.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.PointF(0, 0),
        new com.aspose.imaging.PointF(200, 133),
        new com.aspose.imaging.PointF(400, 166),
        new com.aspose.imaging.PointF(600, 400));

// Zeichne ein Rasterbild der angegebenen Größe am angegebenen Ort.
// Das Bild wird skaliert, um in das gewünschte Rechteck zu passen.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw, new com.aspose.imaging.Point(400, 200), new com.aspose.imaging.Size(100, 50));
} finally {
    imageToDraw.dispose();
}

// Zeichne eine Textzeichenfolge
graphics.drawString(
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        "Hello World!",
        new com.aspose.imaging.Point(200, 300),
        com.aspose.imaging.Color.getDarkRed());

// Erstelle einen Pfad zum Füllen
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

// Fülle den Pfad mit einem gelben Pinsel und einem grünen Stift für die Kontur.
graphics.fillPath(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getYellow()), pathToFill);

// Erstelle einen Pfad zum Zeichnen
com.aspose.imaging.GraphicsPath pathToDraw = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figureToDraw = new com.aspose.imaging.Figure();
pathToDraw.addFigure(figureToDraw);

figureToDraw.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(200, 200, 200, 200), 0, 360),
        });

// Zeichne den Pfad mit einem 5 Pixel breiten orangefarbenen Stift.
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// Erhalte das endgültige SVG-Bild, das alle Zeichenbefehle enthält.
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


Initialisiert eine neue Instanz der Klasse [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breite des ausgegebenen Svg-Bildes. |
| Höhe | int | Die Breite des ausgegebenen Svg-Bildes. |
| dpi | int | Die Geräteauflösung, z. B. 96 Punkte pro Zoll. |

### SvgGraphics2D(SvgImage image) {#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-}
```
public SvgGraphics2D(SvgImage image)
```


Initialisiert eine neue Instanz der Klasse [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) | Das Bild, auf dem Zeichenoperationen ausgeführt werden. |

### drawImage(RasterImage image, Point origin) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public final void drawImage(RasterImage image, Point origin)
```


Zeichnet das angegebene Bild am angegebenen Ort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das gezeichnete Bild. |
| origin | [Point](../../com.aspose.imaging/point) | Der Ort des gezeichneten Bildes. |

### drawImage(RasterImage image, Point origin, Size size) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public final void drawImage(RasterImage image, Point origin, Size size)
```


Zeichnet das angegebene Bild in der angegebenen Größe am angegebenen Ort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das gezeichnete Bild. |
| origin | [Point](../../com.aspose.imaging/point) | Der Ort des gezeichneten Bildes. |
| size | [Size](../../com.aspose.imaging/size) | Die gewünschte Größe des gezeichneten Bildes. |

### drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image) {#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-}
```
public final void drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```


Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und in der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | Der zu zeichnende Teil des Bildobjekts. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Der Ort und die Größe des gezeichneten Bildes. Das Bild wird skaliert, um in das Rechteck zu passen. |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das zu zeichnende Bild. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public final void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine Rechteckstruktur angegeben ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Der Stift zum Zeichnen der Kontur der Figur. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die Grenzen der Ellipse. |
| startAngle | float | Der Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| arcAngle | float | Der Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle zum Endpunkt des Bogens. |

### fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle) {#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public final void fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)
```


Füllt einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine Rechteckstruktur angegeben ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Der Stift zum Zeichnen der Kontur der Figur. |
| brush | [Brush](../../com.aspose.imaging/brush) | Der Pinsel zum Füllen des Inneren der Figur. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die Grenzen der Ellipse. |
| startAngle | float | Der Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| arcAngle | float | Der Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle zum Endpunkt des Bogens. |

### drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public final void drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Zeichnet die kubische Bézierkurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Der Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| pt1 | [PointF](../../com.aspose.imaging/pointf) | Der Startpunkt der Kurve. |
| pt2 | [PointF](../../com.aspose.imaging/pointf) | Der erste Kontrollpunkt für die Kurve. |
| pt3 | [PointF](../../com.aspose.imaging/pointf) | Der zweite Kontrollpunkt für die Kurve. |
| pt4 | [PointF](../../com.aspose.imaging/pointf) | Der Endpunkt der Kurve. |

### drawString(Font font, String text, Point origin, Color textColor) {#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-}
```
public final void drawString(Font font, String text, Point origin, Color textColor)
```


Zeichnet die Textzeichenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | Die Schriftart, die zum Rendern von Text verwendet wird. |
| text | java.lang.String | Die Unicode-Textzeichenfolge. |
| origin | [Point](../../com.aspose.imaging/point) | Die obere linke Ecke des Textabschnitts. |
| textColor | [Color](../../com.aspose.imaging/color) | Die Textfarbe. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Zeichnet die Linie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Der Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| x1 | int | Die x-Koordinate des ersten Punktes. |
| y1 | int | Die y-Koordinate des ersten Punktes. |
| x2 | int | Die x-Koordinate des zweiten Punktes. |
| y2 | int | Die y-Koordinate des zweiten Punktes. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public final void drawPath(Pen pen, GraphicsPath path)
```


Zeichnet den Pfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Der Stift zum Zeichnen der Kontur der Figur. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Der Pfad zum Zeichnen. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public final void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Füllt den Pfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Der Stift zum Zeichnen der Kontur der Figur. |
| brush | [Brush](../../com.aspose.imaging/brush) | Der Pinsel zum Füllen des Inneren der Figur. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Der Pfad zum Zeichnen. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Zeichnet das Rechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Der Stift zum Zeichnen der Kontur der Figur. |
| x | int | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| Breite | int | Die Breite des zu zeichnenden Rechtecks. |
| Höhe | int | Die Höhe des zu zeichnenden Rechtecks. |

### fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-}
```
public final void fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)
```


Füllt das Rechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Der Stift zum Zeichnen der Kontur der Figur. |
| brush | [Brush](../../com.aspose.imaging/brush) | Der Pinsel zum Füllen des Inneren der Figur. |
| x | int | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| Breite | int | Die Breite des zu zeichnenden Rechtecks. |
| Höhe | int | Die Höhe des zu zeichnenden Rechtecks. |

### endRecording() {#endRecording--}
```
public final SvgImage endRecording()
```


Ruft das endgültige Svg-Bild ab, das alle über das Objekt [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d) ausgeführten Zeichenbefehle enthält.

**Returns:**
[SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) - The final Svg image.
