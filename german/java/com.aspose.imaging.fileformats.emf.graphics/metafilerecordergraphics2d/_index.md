---
title: "MetafileRecorderGraphics2D"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Metadatei-Aufzeichnergrafiken"
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
**Inheritance:**
java.lang.Object
```
public abstract class MetafileRecorderGraphics2D
```

Die Metadatei-Aufzeichnergrafiken
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MetafileRecorderGraphics2D()](#MetafileRecorderGraphics2D--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getClip()](#getClip--) | Liest oder setzt eine Region, die den Zeichenbereich dieser Graphics einschränkt |
| [setClip(Region value)](#setClip-com.aspose.imaging.Region-) | Liest oder setzt eine Region, die den Zeichenbereich dieser Graphics einschränkt |
| [getClipBounds()](#getClipBounds--) | Liest die Clip-Grenzen. |
| [getBackgroundColor()](#getBackgroundColor--) | Liest die Farbe des Hintergrunds. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Setzt die Farbe des Hintergrunds. |
| [clear()](#clear--) | Löscht den Zustand des Graphics-Objekts |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine Rechteckstruktur angegeben ist. |
| [drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Zeichnet die kubische Bézierkurve. |
| [drawPolyCubicBezier(Pen pen, Point[] points)](#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Zeichnet die polykubische Bézierkurve. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Zeichnet die Ellipse. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Füllt die Ellipse. |
| [drawImage(RasterImage image, Point location)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Zeichnet das angegebene Bild, verwendet seine ursprüngliche physische Größe, am angegebenen Ort. |
| [drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)](#drawImage-byte---com.aspose.imaging.Rectangle-int-) | Zeichnet das Bild. |
| [drawImage(InputStream stream, Rectangle destRect, int srcUnit)](#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-) | Zeichnet das Bild. |
| [drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-) | Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Zeichnet die Linie. |
| [drawLine(Pen pen, Point pt1, Point pt2)](#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Zeichnet die Linie. |
| [drawPolyline(Pen pen, Point[] points)](#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Zeichnet die Polylinie. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Zeichnet den Pfad. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Füllt den Pfad. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Zeichnet das Kuchenstück. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Füllt das Kuchenstück. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Zeichnet das Polygon. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---) | Füllt das Polygon. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-) | Füllt das Polygon. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Zeichnet das Rechteck. |
| [drawRectangle(Pen pen, Rectangle rectangle)](#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Zeichnet das Rechteck. |
| [fillRectangle(Brush brush, Rectangle rectangle)](#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Füllt das Rechteck. |
| [drawString(String string, Font font, Color color, int x, int y)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-) | Zeichnet die Zeichenkette. |
| [drawString(String string, Font font, Color color, int x, int y, float angle)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-) | Zeichnet die Zeichenkette. |
| [excludeClip(Rectangle rect)](#excludeClip-com.aspose.imaging.Rectangle-) | Aktualisiert den Clip-Bereich dieses Graphics, um den durch eine Rechteckstruktur angegebenen Bereich auszuschließen. |
| [excludeClip(Region region)](#excludeClip-com.aspose.imaging.Region-) | Aktualisiert den Clip-Bereich dieses Graphics, um den durch eine Region angegebenen Bereich auszuschließen. |
| [intersectClip(RectangleF rect)](#intersectClip-com.aspose.imaging.RectangleF-) | Aktualisiert den Clip-Bereich dieses Graphics auf die Schnittmenge des aktuellen Clip-Bereichs und der angegebenen Rechteckstruktur. |
| [intersectClip(Region region)](#intersectClip-com.aspose.imaging.Region-) | Aktualisiert den Clip-Bereich dieses Graphics auf die Schnittmenge des aktuellen Clip-Bereichs und der angegebenen Region. |
| [resetClip()](#resetClip--) | Setzt den Clip zurück. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Multipliziert die Welttransformation dieses Graphics mit der angegebenen Matrix. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Multipliziert die Welttransformation dieses Graphics mit der angegebenen Matrix in der angegebenen Reihenfolge. |
| [translateTransform(float x, float y)](#translateTransform-float-float-) | Ändert den Ursprung des Koordinatensystems, indem die angegebene Verschiebung vor die Transformationsmatrix dieses Graphics gestellt wird. |
| [translateTransform(float x, float y, int order)](#translateTransform-float-float-int-) | Ändert den Ursprung des Koordinatensystems, indem die angegebene Verschiebung in der angegebenen Reihenfolge auf die Transformationsmatrix dieses Graphics angewendet wird. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Wendet die angegebene Drehung auf die Transformationsmatrix dieses Graphics an. |
| [rotateTransform(float angle, PointF center, int order)](#rotateTransform-float-com.aspose.imaging.PointF-int-) | Wendet die angegebene Drehung in der angegebenen Reihenfolge auf die Transformationsmatrix dieses Graphics an. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Wendet die angegebene Skalierungsoperation auf die Transformationsmatrix dieses Graphics an, indem sie vor die Transformationsmatrix des Objekts gestellt wird. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Wendet die angegebene Skalierungsoperation in der angegebenen Reihenfolge auf die Transformationsmatrix dieses Graphics an. |
| [getTransform()](#getTransform--) | Liefert die Welttransformation. |
| [setTransform(Matrix transform)](#setTransform-com.aspose.imaging.Matrix-) | Setzt die Transformation. |

## Example: This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

// Die Bildgröße in Pixeln
int deviceWidth = 600;
int deviceHeight = 400;

// Die Bildgröße in Millimetern
int deviceWidthMm = (int) (deviceWidth / 100f);
int deviceHeightMm = (int) (deviceHeight / 100f);

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Erstelle ein EMF-Bild.
com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D(
                frame,
                new com.aspose.imaging.Size(deviceWidth, deviceHeight),
                new com.aspose.imaging.Size(deviceWidthMm, deviceHeightMm));

// Zeichne ein schwarzes Rechteck entlang der Bildränder mit einem 1 Pixel breiten schwarzen Stift.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, deviceWidth, deviceHeight);

// Fülle ein Rechteck mit der Farbe white-smoke.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// Zeichne zwei diagonale Linien mit einem 1 Pixel breiten darkgreen Stift.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, deviceWidth, deviceHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, deviceHeight, deviceWidth, 0);

// Zeichne einen Bogen innerhalb des Rechtecks {0, 0, 200, 200} mit einem 2 Pixel breiten blauen Stift.
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Fülle einen Bogen
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Zeichne einen kubischen Bezier mit einem 2 Pixel breiten roten Stift.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// Zeichne ein Rasterbild der angegebenen Größe am angegebenen Ort.
// Das Bild wird skaliert, um in das gewünschte Rechteck zu passen.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
} finally {
    imageToDraw.dispose();
}

// Zeichne eine Textzeichenfolge
graphics.drawString("Hello World!",
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        com.aspose.imaging.Color.getDarkRed(), 200, 300);

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
                new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
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

// Um SVG zu rasterisieren, müssen wir Rasterisierungsoptionen angeben.
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// Erhalte das endgültige WMF-Bild, das alle Zeichenbefehle enthält.
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


Liest oder setzt eine Region, die den Zeichenbereich dieser Graphics einschränkt

**Returns:**
[Region](../../com.aspose.imaging/region) - The clip region.
### setClip(Region value) {#setClip-com.aspose.imaging.Region-}
```
public void setClip(Region value)
```


Liest oder setzt eine Region, die den Zeichenbereich dieser Graphics einschränkt

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Region](../../com.aspose.imaging/region) | Der Clip-Bereich. |

### getClipBounds() {#getClipBounds--}
```
public RectangleF getClipBounds()
```


Liest die Clip-Grenzen.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The clip bounds.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Liest die Farbe des Hintergrunds.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of the background.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Setzt die Farbe des Hintergrunds.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Die Hintergrundfarbe. |

### clear() {#clear--}
```
public void clear()
```


Löscht den Zustand des Graphics-Objekts

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Zeichnet einen Bogen, der einen Teil einer Ellipse darstellt, die durch eine Rechteckstruktur angegeben ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die Grenzen der Ellipse. |
| startAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| arcAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle bis zum Endpunkt des Bogens. |

### drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Zeichnet die kubische Bézierkurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| pt1 | [Point](../../com.aspose.imaging/point) | Der Startpunkt der Kurve. |
| pt2 | [Point](../../com.aspose.imaging/point) | Der erste Kontrollpunkt für die Kurve. |
| pt3 | [Point](../../com.aspose.imaging/point) | Der zweite Kontrollpunkt für die Kurve. |
| pt4 | [Point](../../com.aspose.imaging/point) | Der Endpunkt der Kurve. |

### drawPolyCubicBezier(Pen pen, Point[] points) {#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyCubicBezier(Pen pen, Point[] points)
```


Zeichnet die polykubische Bézierkurve.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Die Punkte. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Zeichnet die Ellipse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die Grenzen der Ellipse. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Füllt die Ellipse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pinsel, der die Eigenschaften der Füllung bestimmt. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die Grenzen der Ellipse. |

### drawImage(RasterImage image, Point location) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public void drawImage(RasterImage image, Point location)
```


Zeichnet das angegebene Bild, verwendet seine ursprüngliche physische Größe, am angegebenen Ort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das zu zeichnende Bild. |
| location | [Point](../../com.aspose.imaging/point) | Der Ort der oberen linken Ecke des gezeichneten Bildes. |

### drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit) {#drawImage-byte---com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)
```


Zeichnet das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageBytes | byte[] | Die Bildbytes. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Das Zielrechteck. |
| srcUnit | int | Die Quelleneinheit. |

### drawImage(InputStream stream, Rectangle destRect, int srcUnit) {#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(InputStream stream, Rectangle destRect, int srcUnit)
```


Zeichnet das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Das Zielrechteck. |
| srcUnit | int | Die Quelleneinheit. |

### drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-}
```
public void drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)
```


Zeichnet den angegebenen Teil des angegebenen Bildes am angegebenen Ort und mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Das zu zeichnende Bild. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Rechteckstruktur, die den Ort und die Größe des gezeichneten Bildes angibt. Das Bild wird skaliert, um in das Rechteck zu passen. |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | Rechteckstruktur, die den Teil des Bildobjekts angibt, der gezeichnet werden soll. |
| srcUnit | int | Die Maßeinheiten, die vom Parameter srcRect verwendet werden. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Zeichnet die Linie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| x1 | int | Die x-Koordinate des ersten Punktes. |
| y1 | int | Die y-Koordinate des ersten Punktes. |
| x2 | int | Die x-Koordinate des zweiten Punktes. |
| y2 | int | Die y-Koordinate des zweiten Punktes. |

### drawLine(Pen pen, Point pt1, Point pt2) {#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawLine(Pen pen, Point pt1, Point pt2)
```


Zeichnet die Linie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| pt1 | [Point](../../com.aspose.imaging/point) | Der erste Punkt. |
| pt2 | [Point](../../com.aspose.imaging/point) | Der zweite Punkt. |

### drawPolyline(Pen pen, Point[] points) {#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyline(Pen pen, Point[] points)
```


Zeichnet die Polylinie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Die Punkte. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Zeichnet den Pfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Der Pfad zum Zeichnen. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Füllt den Pfad.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| brush | [Brush](../../com.aspose.imaging/brush) | Pinsel, der die Eigenschaften der Füllung bestimmt. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Der Pfad zum Füllen. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Zeichnet das Kuchenstück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die Grenzen der Ellipse. |
| startAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweepAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle bis zum Endpunkt des Bogens. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Füllt das Kuchenstück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pinsel, der die Eigenschaften der Füllung bestimmt. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Die Grenzen der Ellipse. |
| startAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zum Startpunkt des Bogens. |
| sweepAngle | float | Winkel in Grad, gemessen im Uhrzeigersinn vom Parameter startAngle bis zum Endpunkt des Bogens. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Zeichnet das Polygon.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Die Punkte. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Füllt das Polygon.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pinsel, der die Eigenschaften der Füllung bestimmt. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Die Punkte. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Füllt das Polygon.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pinsel, der die Eigenschaften der Füllung bestimmt. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Die Punkte. |
| fillMode | int | Der Füllmodus. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Zeichnet das Rechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| x | int | Die x-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| y | int | Die y-Koordinate der oberen linken Ecke des zu zeichnenden Rechtecks. |
| Breite | int | Die Breite des zu zeichnenden Rechtecks. |
| Höhe | int | Die Höhe des zu zeichnenden Rechtecks. |

### drawRectangle(Pen pen, Rectangle rectangle) {#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rectangle)
```


Zeichnet das Rechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Stift, der die Farbe, Breite und den Stil der Figur bestimmt. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das zu zeichnende Rechteck. |

### fillRectangle(Brush brush, Rectangle rectangle) {#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rectangle)
```


Füllt das Rechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Pinsel, der die Eigenschaften der Füllung bestimmt. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das zu füllende Rechteck. |

### drawString(String string, Font font, Color color, int x, int y) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-}
```
public void drawString(String string, Font font, Color color, int x, int y)
```


Zeichnet die Zeichenkette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeichenkette | java.lang.String | Die Zeichenkette. |
| font | [Font](../../com.aspose.imaging/font) | Schriftart, die das Textformat der Zeichenkette definiert. |
| color | [Color](../../com.aspose.imaging/color) | Die Textfarbe. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // Erstens, die Bildgröße ermitteln
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // Zweitens, berechne eine Transformation, um einen Textstring entlang der Hauptdiagonalen des Bildes zu platzieren -
    // von der oberen linken bis zur unteren rechten Ecke.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Dann die Transformation festlegen.
    graphics.setTransform(transform);

    // Schließlich ein Wasserzeichen (Textstring in rosa Farbe) entlang der Hauptdiagonalen platzieren.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Speichere das Bild mit dem Wasserzeichen in einer anderen EMF-Datei.
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


Zeichnet die Zeichenkette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeichenkette | java.lang.String | Die Zeichenkette. |
| font | [Font](../../com.aspose.imaging/font) | Schriftart, die das Textformat der Zeichenkette definiert. |
| color | [Color](../../com.aspose.imaging/color) | Die Textfarbe. |
| x | int | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | int | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| angle | float | Der Winkel in Grad zwischen dem Escapement-Vektor und der x-Achse des Geräts. Der Escapement-Vektor ist parallel zur Grundlinie einer Textzeile. |

### excludeClip(Rectangle rect) {#excludeClip-com.aspose.imaging.Rectangle-}
```
public void excludeClip(Rectangle rect)
```


Aktualisiert den Clip-Bereich dieses Graphics, um den durch eine Rechteckstruktur angegebenen Bereich auszuschließen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Rechteckstruktur, die das vom Clip-Bereich auszuschließende Rechteck angibt. |

### excludeClip(Region region) {#excludeClip-com.aspose.imaging.Region-}
```
public void excludeClip(Region region)
```


Aktualisiert den Clip-Bereich dieses Graphics, um den durch eine Region angegebenen Bereich auszuschließen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Region, die den vom Clip-Bereich auszuschließenden Bereich angibt. |

### intersectClip(RectangleF rect) {#intersectClip-com.aspose.imaging.RectangleF-}
```
public void intersectClip(RectangleF rect)
```


Aktualisiert den Clip-Bereich dieses Graphics auf die Schnittmenge des aktuellen Clip-Bereichs und der angegebenen Rechteckstruktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Rechteckstruktur, die mit dem aktuellen Clip-Bereich geschnitten wird. |

### intersectClip(Region region) {#intersectClip-com.aspose.imaging.Region-}
```
public void intersectClip(Region region)
```


Aktualisiert den Clip-Bereich dieses Graphics auf die Schnittmenge des aktuellen Clip-Bereichs und der angegebenen Region.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Region, die mit dem aktuellen Bereich geschnitten wird. |

### resetClip() {#resetClip--}
```
public void resetClip()
```


Setzt den Clip zurück.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Multipliziert die Welttransformation dieses Graphics mit der angegebenen Matrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Die Matrix, die die Welttransformation multipliziert. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Multipliziert die Welttransformation dieses Graphics mit der angegebenen Matrix in der angegebenen Reihenfolge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Die Matrix, die die Welttransformation multipliziert. |
| order | int | Die Reihenfolge der Multiplikation. |

### translateTransform(float x, float y) {#translateTransform-float-float-}
```
public void translateTransform(float x, float y)
```


Ändert den Ursprung des Koordinatensystems, indem die angegebene Verschiebung vor die Transformationsmatrix dieses Graphics gestellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate der Translation. |
| y | float | Die y-Koordinate der Translation. |

### translateTransform(float x, float y, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float x, float y, int order)
```


Ändert den Ursprung des Koordinatensystems, indem die angegebene Verschiebung in der angegebenen Reihenfolge auf die Transformationsmatrix dieses Graphics angewendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate der Translation. |
| y | float | Die y-Koordinate der Translation. |
| order | int | Gibt an, ob die Translation vorangestellt oder angehängt an die Transformationsmatrix ist. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Wendet die angegebene Drehung auf die Transformationsmatrix dieses Graphics an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Drehwinkel in Grad. |

### rotateTransform(float angle, PointF center, int order) {#rotateTransform-float-com.aspose.imaging.PointF-int-}
```
public void rotateTransform(float angle, PointF center, int order)
```


Wendet die angegebene Drehung in der angegebenen Reihenfolge auf die Transformationsmatrix dieses Graphics an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Drehwinkel in Grad. |
| center | [PointF](../../com.aspose.imaging/pointf) | Das Rotationszentrum. |
| order | int | Gibt an, ob die Rotation an die Matrixtransformation angehängt oder vorangestellt wird. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Wendet die angegebene Skalierungsoperation auf die Transformationsmatrix dieses Graphics an, indem sie vor die Transformationsmatrix des Objekts gestellt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Skalierungsfaktor in x-Richtung. |
| sy | float | Skalierungsfaktor in y-Richtung. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Wendet die angegebene Skalierungsoperation in der angegebenen Reihenfolge auf die Transformationsmatrix dieses Graphics an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sx | float | Skalierungsfaktor in x-Richtung. |
| sy | float | Skalierungsfaktor in y-Richtung. |
| order | int | Gibt an, ob die Skalierungsoperation vorangestellt oder angehängt an die Transformationsmatrix ist. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Liefert die Welttransformation.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - The transform matrix.
### setTransform(Matrix transform) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix transform)
```


Setzt die Transformation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Die neue Transformationsmatrix. |


**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // Erstens, die Bildgröße ermitteln
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // Zweitens, berechne eine Transformation, um einen Textstring entlang der Hauptdiagonalen des Bildes zu platzieren -
    // von der oberen linken bis zur unteren rechten Ecke.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Dann die Transformation festlegen.
    graphics.setTransform(transform);

    // Schließlich ein Wasserzeichen (Textstring in rosa Farbe) entlang der Hauptdiagonalen platzieren.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Speichere das Bild mit dem Wasserzeichen in einer anderen EMF-Datei.
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

