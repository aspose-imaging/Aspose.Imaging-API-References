---
title: "EmfRecorderGraphics2D"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Emf-Aufzeichnergrafiken"
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.graphics.MetafileRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d)
```
public final class EmfRecorderGraphics2D extends MetafileRecorderGraphics2D
```

Die Emf-Aufzeichnergrafiken
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm)](#EmfRecorderGraphics2D-com.aspose.imaging.Rectangle-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Initialisiert eine neue Instanz der `EmfRecorderGraphics2D`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Liest oder setzt den Hintergrundmodus. |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Liest oder setzt den Hintergrundmodus. |
| [endRecording()](#endRecording--) | Beendet die Aufnahme. |
| [fromEmfImage(EmfImage emfImage)](#fromEmfImage-com.aspose.imaging.fileformats.emf.EmfImage-) | Erhält eine Instanz von [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d), die alle Datensätze aus dem Emf-Bild enthält. |

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

### EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm) {#EmfRecorderGraphics2D-com.aspose.imaging.Rectangle-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm)
```


Initialisiert eine neue Instanz der `EmfRecorderGraphics2D`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| frame | [Rectangle](../../com.aspose.imaging/rectangle) | Der Rahmen. |
| deviceSize | [Size](../../com.aspose.imaging/size) | Größe des Geräts. |
| deviceSizeMm | [Size](../../com.aspose.imaging/size) | Die Gerätegröße in mm. |

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Liest oder setzt den Hintergrundmodus.

**Returns:**
int - Der Hintergrundmodus.
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Liest oder setzt den Hintergrundmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Hintergrundmodus. |

### endRecording() {#endRecording--}
```
public EmfImage endRecording()
```


Beendet die Aufnahme.

**Returns:**
[EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) - The result image.
### fromEmfImage(EmfImage emfImage) {#fromEmfImage-com.aspose.imaging.fileformats.emf.EmfImage-}
```
public static EmfRecorderGraphics2D fromEmfImage(EmfImage emfImage)
```


Erhält eine Instanz von [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d), die alle Datensätze aus dem Emf-Bild enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| emfImage | [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) | Das Emf-Bild, aus dem Datensätze gelesen werden. |

**Returns:**
[EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d) - An instance of the [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d)

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

