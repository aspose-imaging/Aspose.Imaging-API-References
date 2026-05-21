---
title: "GraphicsPath"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt eine Reihe von verbundenen Linien und Kurven dar."
type: docs
weight: 52
url: /de/java/com.aspose.imaging/graphicspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Stellt eine Reihe von verbundenen Linien und Kurven dar. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Initialisiert eine neue Instanz der `GraphicsPath`-Klasse. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.imaging.Figure---) | Initialisiert eine neue Instanz der `GraphicsPath`-Klasse. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.imaging.Figure---int-) | Initialisiert eine neue Instanz der `GraphicsPath`-Klasse. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Initialisiert eine neue Instanz der `GraphicsPath`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFillMode()](#getFillMode--) | Gibt eine `com.aspose.imaging.FillMode`-Aufzählung zurück, die bestimmt, wie die Innenbereiche von Formen in diesem `com.aspose.imaging.GraphicsPath` gefüllt werden. |
| [setFillMode(int value)](#setFillMode-int-) | Legt eine `com.aspose.imaging.FillMode`-Aufzählung fest, die bestimmt, wie die Innenbereiche von Formen in diesem `com.aspose.imaging.GraphicsPath` gefüllt werden. |
| [getFigures()](#getFigures--) | Liefert die Pfadfiguren. |
| [getBounds()](#getBounds--) | Ruft die Begrenzungen des Objekts ab oder setzt sie. |
| [reset()](#reset--) | Leert den Grafikpfad und setzt die `com.aspose.imaging.FillMode` auf `F:com.aspose.imaging.fillMode.alternate`. |
| [reverse()](#reverse--) | Kehrt die Reihenfolge von Figuren, Formen und Punkten in jeder Form dieses `com.aspose.imaging.graphicsPath` um. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.graphicsPath` liegt. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.graphicsPath` liegt. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.graphicsPath` liegt. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.graphicsPath` liegt. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.GraphicsPath` im sichtbaren Clip‑Bereich des angegebenen `com.aspose.imaging.graphics` liegt. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.graphicsPath` liegt. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.GraphicsPath` liegt, wobei das angegebene `com.aspose.imaging.graphics` verwendet wird. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.graphicsPath` liegt. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.pen` gezeichnet wird. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.pen` gezeichnet wird. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet und das angegebene `com.aspose.imaging.graphics` verwendet wird. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet und das angegebene `com.aspose.imaging.graphics` verwendet wird. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.pen` gezeichnet wird. |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.pen` gezeichnet wird. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet und das angegebene `com.aspose.imaging.graphics` verwendet wird. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet und das angegebene `com.aspose.imaging.graphics` verwendet wird. |
| [flatten()](#flatten--) | Konvertiert jede Kurve in diesem Pfad in eine Sequenz verbundener Liniensegmente. |
| [flatten(Matrix matrix)](#flatten-com.aspose.imaging.Matrix-) | Wendet die angegebene Transformation an und konvertiert anschließend jede Kurve in diesem `com.aspose.imaging.GraphicsPath` in eine Sequenz verbundener Liniensegmente. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.imaging.Matrix-float-) | Konvertiert jede Kurve in diesem `com.aspose.imaging.GraphicsPath` in eine Sequenz verbundener Liniensegmente. |
| [widen(Pen pen)](#widen-com.aspose.imaging.Pen-) | Fügt dem Pfad eine zusätzliche Kontur hinzu. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-) | Fügt dem `com.aspose.imaging.graphicsPath` eine zusätzliche Kontur hinzu. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-) | Ersetzt dieses `com.aspose.imaging.GraphicsPath` durch Kurven, die den Bereich umschließen, der gefüllt wird, wenn dieser Pfad mit dem angegebenen Stift gezeichnet wird. |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-) | Wendet eine Verzerrungs‑Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen `com.aspose.imaging.graphicsPath` an. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-) | Wendet eine Verzerrungs‑Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen `com.aspose.imaging.graphicsPath` an. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-) | Wendet eine Verzerrungs‑Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen `com.aspose.imaging.graphicsPath` an. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-) | Wendet eine Verzerrungs‑Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen `com.aspose.imaging.graphicsPath` an. |
| [addFigure(Figure figure)](#addFigure-com.aspose.imaging.Figure-) | Fügt eine neue Figur hinzu. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.imaging.Figure---) | Fügt neue Figuren hinzu. |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.imaging.Figure-) | Entfernt eine Figur. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.imaging.Figure---) | Entfernt Figuren. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.imaging.GraphicsPath-) | Fügt den angegebenen `com.aspose.imaging.GraphicsPath` an diesen Pfad an. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.imaging.GraphicsPath-boolean-) | Fügt den angegebenen `com.aspose.imaging.GraphicsPath` an diesen Pfad an. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ruft die Begrenzungen des Objekts ab. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ruft die Begrenzungen des Objekts ab. |
| [deepClone()](#deepClone--) | Führt eine tiefe Kopie dieses Grafikpfads aus. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Wendet die angegebene Transformation auf die Form an. |
| [equals(Object o)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
| [hashCode()](#hashCode--) | Gibt den Hashcode des aktuellen Objekts zurück. |

## Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.
Dieses Beispiel verwendet die Klassen GraphicsPath und Graphics, um Figuren auf einer Image-Oberfläche zu erstellen und zu manipulieren. Das Beispiel erstellt ein neues Image (vom Typ Tiff) und zeichnet Pfade mit Hilfe der Klasse GraphicsPath. Am Ende wird die von der Klasse Graphics bereitgestellte Methode DrawPath aufgerufen, um die Pfade auf der Oberfläche zu rendern.
``` java
// Erstelle eine Instanz von FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Erstelle eine Instanz von TiffOptions und setze deren verschiedene Eigenschaften
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Lege die Quelle für die Instanz von ImageOptions fest
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Erstelle eine Instanz von Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Erstelle und initialisiere eine Instanz der Klasse Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Leere die Graphics-Oberfläche
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Erstelle eine Instanz der Klasse GraphicsPath
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Erstelle eine Instanz der Klasse Figure
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Füge Shapes zum Figure-Objekt hinzu
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Füge das Figure-Objekt zu GraphicsPath hinzu
        graphicspath.addFigure(figure);

        // Zeichne den Pfad mit einem Pen-Objekt der Farbe Black
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Speichere alle Änderungen.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Initialisiert eine neue Instanz der `GraphicsPath`-Klasse.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.imaging.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Initialisiert eine neue Instanz der `GraphicsPath`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Die Figuren, von denen initialisiert werden soll. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.imaging.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Initialisiert eine neue Instanz der `GraphicsPath`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Die Figuren, von denen initialisiert werden soll. |
| fillMode | int | Der Füllmodus. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Initialisiert eine neue Instanz der `GraphicsPath`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillMode | int | Der Füllmodus. |

### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Gibt eine `com.aspose.imaging.FillMode`-Aufzählung zurück, die bestimmt, wie die Innenbereiche von Formen in diesem `com.aspose.imaging.GraphicsPath` gefüllt werden.

**Returns:**
int - Der Füllmodus. Eine `com.aspose.imaging.FillMode`-Aufzählung, die angibt, wie die Innenbereiche von Formen in diesem `com.aspose.imaging.GraphicsPath` gefüllt werden.
### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Legt eine `com.aspose.imaging.FillMode`-Aufzählung fest, die bestimmt, wie die Innenbereiche von Formen in diesem `com.aspose.imaging.GraphicsPath` gefüllt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Füllmodus. |

### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Liefert die Pfadfiguren.

**Returns:**
com.aspose.imaging.Figure[] - Die Pfadfiguren.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ruft die Begrenzungen des Objekts ab oder setzt sie.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### reset() {#reset--}
```
public void reset()
```


Leert den Grafikpfad und setzt die `com.aspose.imaging.FillMode` auf `F:com.aspose.imaging.fillMode.alternate`.

### reverse() {#reverse--}
```
public void reverse()
```


Kehrt die Reihenfolge von Figuren, Formen und Punkten in jeder Form dieses `com.aspose.imaging.graphicsPath` um.

### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.graphicsPath` liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses `com.aspose.imaging.GraphicsPath` liegt; andernfalls false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.graphicsPath` liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Ein `com.aspose.imaging.PointF`, das den zu testenden Punkt darstellt. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses `com.aspose.imaging.GraphicsPath` liegt; andernfalls false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.graphicsPath` liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses `com.aspose.imaging.GraphicsPath` liegt; andernfalls false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.graphicsPath` liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Ein `com.aspose.imaging.Point`, das den zu testenden Punkt darstellt. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses `com.aspose.imaging.GraphicsPath` liegt; andernfalls false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.GraphicsPath` im sichtbaren Clip‑Bereich des angegebenen `com.aspose.imaging.graphics` liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Das `com.aspose.imaging.Graphics`, für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses `com.aspose.imaging.GraphicsPath` liegt; andernfalls false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.graphicsPath` liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Ein `com.aspose.imaging.PointF`, das den zu testenden Punkt darstellt. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Das `com.aspose.imaging.Graphics`, für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses liegt; andernfalls false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.GraphicsPath` liegt, wobei das angegebene `com.aspose.imaging.graphics` verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Das `com.aspose.imaging.Graphics`, für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses `com.aspose.imaging.GraphicsPath` liegt; andernfalls false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb dieses `com.aspose.imaging.graphicsPath` liegt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Ein `com.aspose.imaging.Point`, das den zu testenden Punkt darstellt. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Das `com.aspose.imaging.Graphics`, für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb dieses `com.aspose.imaging.GraphicsPath` liegt; andernfalls false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.pen` gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](../../com.aspose.imaging/pen) | Der `com.aspose.imaging.Pen` zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet wird; andernfalls false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.pen` gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Ein `com.aspose.imaging.PointF`, das den zu testenden Ort angibt. |
| pen | [Pen](../../com.aspose.imaging/pen) | Der `com.aspose.imaging.Pen` zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet wird; andernfalls false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet und das angegebene `com.aspose.imaging.graphics` verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](../../com.aspose.imaging/pen) | Der `com.aspose.imaging.Pen` zum Testen. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Das `com.aspose.imaging.Graphics`, für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wie mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet; andernfalls false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet und das angegebene `com.aspose.imaging.graphics` verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Ein `com.aspose.imaging.PointF`, das den zu testenden Ort angibt. |
| pen | [Pen](../../com.aspose.imaging/pen) | Der `com.aspose.imaging.Pen` zum Testen. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Das `com.aspose.imaging.Graphics`, für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wie mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet; andernfalls false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.pen` gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](../../com.aspose.imaging/pen) | Der `com.aspose.imaging.Pen` zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet wird; andernfalls false.
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.pen` gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Ein `com.aspose.imaging.Point`, das den zu testenden Ort angibt. |
| pen | [Pen](../../com.aspose.imaging/pen) | Der `com.aspose.imaging.Pen` zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet wird; andernfalls false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet und das angegebene `com.aspose.imaging.graphics` verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |
| pen | [Pen](../../com.aspose.imaging/pen) | Der `com.aspose.imaging.Pen` zum Testen. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Das `com.aspose.imaging.Graphics`, für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wie mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet; andernfalls false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Gibt an, ob der angegebene Punkt innerhalb (unter) der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wenn er mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet und das angegebene `com.aspose.imaging.graphics` verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Ein `com.aspose.imaging.Point`, das den zu testenden Ort angibt. |
| pen | [Pen](../../com.aspose.imaging/pen) | Der `com.aspose.imaging.Pen` zum Testen. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | Das `com.aspose.imaging.Graphics`, für das die Sichtbarkeit getestet werden soll. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der angegebene Punkt innerhalb der Kontur dieses `com.aspose.imaging.GraphicsPath` liegt, wie mit dem angegebenen `com.aspose.imaging.Pen` gezeichnet; andernfalls false.
### flatten() {#flatten--}
```
public void flatten()
```


Konvertiert jede Kurve in diesem Pfad in eine Sequenz verbundener Liniensegmente.

### flatten(Matrix matrix) {#flatten-com.aspose.imaging.Matrix-}
```
public void flatten(Matrix matrix)
```


Wendet die angegebene Transformation an und konvertiert anschließend jede Kurve in diesem `com.aspose.imaging.GraphicsPath` in eine Sequenz verbundener Liniensegmente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Eine `com.aspose.imaging.Matrix`, mit der dieses `com.aspose.imaging.GraphicsPath` vor dem Abflachen transformiert wird. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.imaging.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Konvertiert jede Kurve in diesem `com.aspose.imaging.GraphicsPath` in eine Sequenz verbundener Liniensegmente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Eine `com.aspose.imaging.Matrix`, mit der dieses `com.aspose.imaging.GraphicsPath` vor dem Abflachen transformiert wird. |
| Flachheit | float | Gibt den maximal zulässigen Fehler zwischen der Kurve und ihrer abgeflachten Annäherung an. Ein Wert von 0,25 ist der Standard. Das Reduzieren des Flachheitswertes erhöht die Anzahl der Liniensegmente in der Annäherung. |

### widen(Pen pen) {#widen-com.aspose.imaging.Pen-}
```
public void widen(Pen pen)
```


Fügt dem Pfad eine zusätzliche Kontur hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Ein `com.aspose.imaging.Pen`, der die Breite zwischen der ursprünglichen Kontur des Pfads und der neuen Kontur, die diese Methode erzeugt, angibt. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Fügt dem `com.aspose.imaging.graphicsPath` eine zusätzliche Kontur hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Ein `com.aspose.imaging.Pen`, der die Breite zwischen der ursprünglichen Kontur des Pfads und der neuen Kontur, die diese Methode erzeugt, angibt. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Eine `com.aspose.imaging.Matrix`, die eine Transformation angibt, die vor dem Verbreitern auf den Pfad angewendet wird. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Ersetzt dieses `com.aspose.imaging.GraphicsPath` durch Kurven, die den Bereich umschließen, der gefüllt wird, wenn dieser Pfad mit dem angegebenen Stift gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Ein `com.aspose.imaging.Pen`, der die Breite zwischen der ursprünglichen Kontur des Pfads und der neuen Kontur, die diese Methode erzeugt, angibt. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Eine `com.aspose.imaging.Matrix`, die eine Transformation angibt, die vor dem Verbreitern auf den Pfad angewendet wird. |
| Flachheit | float | Ein Wert, der die Flachheit für Kurven angibt. |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Wendet eine Verzerrungs‑Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen `com.aspose.imaging.graphicsPath` an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Ein Array von `com.aspose.imaging.PointF`-Strukturen, das ein Parallelogramm definiert, zu dem das durch `srcRect` definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Ein `com.aspose.imaging.RectangleF`, das das Rechteck darstellt, das in das durch `destPoints` definierte Parallelogramm transformiert wird. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Wendet eine Verzerrungs‑Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen `com.aspose.imaging.graphicsPath` an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Ein Array von `com.aspose.imaging.PointF`-Strukturen, das ein Parallelogramm definiert, zu dem das durch `srcRect` definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Ein `com.aspose.imaging.RectangleF`, das das Rechteck darstellt, das in das durch `destPoints` definierte Parallelogramm transformiert wird. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Eine `com.aspose.imaging.Matrix`, die eine geometrische Transformation angibt, die auf den Pfad angewendet wird. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Wendet eine Verzerrungs‑Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen `com.aspose.imaging.graphicsPath` an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Ein Array von `com.aspose.imaging.PointF`-Strukturen, das ein Parallelogramm definiert, zu dem das durch `srcRect` definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Ein `com.aspose.imaging.RectangleF`, das das Rechteck darstellt, das in das durch `destPoints` definierte Parallelogramm transformiert wird. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Eine `com.aspose.imaging.Matrix`, die eine geometrische Transformation angibt, die auf den Pfad angewendet wird. |
| warpMode | int | Eine `com.aspose.imaging.WarpMode`-Aufzählung, die angibt, ob diese Verzerrungsoperation perspektivisch oder bilinear arbeitet. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Wendet eine Verzerrungs‑Transformation, definiert durch ein Rechteck und ein Parallelogramm, auf diesen `com.aspose.imaging.graphicsPath` an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Ein Array von `com.aspose.imaging.PointF`-Strukturen, das ein Parallelogramm definiert, zu dem das durch `srcRect` definierte Rechteck transformiert wird. Das Array kann drei oder vier Elemente enthalten. Enthält das Array drei Elemente, wird die rechte untere Ecke des Parallelogramms durch die ersten drei Punkte impliziert. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | Ein `com.aspose.imaging.RectangleF`, das das Rechteck darstellt, das in das durch `destPoints` definierte Parallelogramm transformiert wird. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Eine `com.aspose.imaging.Matrix`, die eine geometrische Transformation angibt, die auf den Pfad angewendet wird. |
| warpMode | int | Eine `com.aspose.imaging.WarpMode`-Aufzählung, die angibt, ob diese Verzerrungsoperation perspektivisch oder bilinear arbeitet. |
| Flachheit | float | Ein Wert von 0 bis 1, der angibt, wie flach der resultierende Pfad ist. Weitere Informationen finden Sie in den Methoden `com.aspose.imaging.GraphicsPath.flatten`. |

### addFigure(Figure figure) {#addFigure-com.aspose.imaging.Figure-}
```
public void addFigure(Figure figure)
```


Fügt eine neue Figur hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | Die hinzuzufügende Figur. |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
Dieses Beispiel verwendet die Klassen GraphicsPath und Graphics, um Figuren auf einer Image-Oberfläche zu erstellen und zu manipulieren. Das Beispiel erstellt ein neues Image (vom Typ Tiff) und zeichnet Pfade mit Hilfe der Klasse GraphicsPath. Am Ende wird die von der Klasse Graphics bereitgestellte Methode DrawPath aufgerufen, um die Pfade auf der Oberfläche zu rendern.
``` java
// Erstelle eine Instanz von FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Erstelle eine Instanz von TiffOptions und setze deren verschiedene Eigenschaften
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Lege die Quelle für die Instanz von ImageOptions fest
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Erstelle eine Instanz von Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Erstelle und initialisiere eine Instanz der Klasse Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Leere die Graphics-Oberfläche
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Erstelle eine Instanz der Klasse GraphicsPath
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Erstelle eine Instanz der Klasse Figure
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Füge Shapes zum Figure-Objekt hinzu
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Füge das Figure-Objekt zu GraphicsPath hinzu
        graphicspath.addFigure(figure);

        // Zeichne den Pfad mit einem Pen-Objekt der Farbe Black
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Speichere alle Änderungen.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### addFigures(Figure[] figures) {#addFigures-com.aspose.imaging.Figure---}
```
public void addFigures(Figure[] figures)
```


Fügt neue Figuren hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Die hinzuzufügenden Figuren. |


**Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...**
Dieses Beispiel erstellt ein neues Image und zeichnet eine Vielzahl von Formen mithilfe von Figures und GraphicsPath auf der Image-Oberfläche
``` java
//Erstellt eine Instanz von BmpOptions und setzt deren verschiedene Eigenschaften
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von BmpOptions zu
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei IsTemporal ist oder nicht
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//Erstelle eine Instanz von Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Erstelle und initialisiere eine Instanz der Klasse Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Leere die Graphics-Oberfläche
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Erstelle eine Instanz der Klasse GraphicsPath
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //Erstelle eine Instanz der Klasse Figure
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //Shape zum Figure-Objekt hinzufügen
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //Erstelle eine Instanz der Klasse Figure
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //Shape zum Figure-Objekt hinzufügen
    figure2.addShape(new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.addShape(new com.aspose.imaging.shapes.PolygonShape(
            new com.aspose.imaging.PointF[]
                    {
                            new com.aspose.imaging.PointF(150, 10),
                            new com.aspose.imaging.PointF(150, 200),
                            new com.aspose.imaging.PointF(250, 300),
                            new com.aspose.imaging.PointF(350, 400)}, true));
    figure2.addShape(new com.aspose.imaging.shapes.RectangleShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(250, 250),
                    new com.aspose.imaging.SizeF(200, 200))));

    //Füge das Figure-Objekt zu GraphicsPath hinzu
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //Zeichne den Pfad mit einem Pen-Objekt der Farbe Black
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // Alle Änderungen speichern.
    image.save();
} finally {
    image.dispose();
}
```

### removeFigure(Figure figure) {#removeFigure-com.aspose.imaging.Figure-}
```
public void removeFigure(Figure figure)
```


Entfernt eine Figur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | Die zu entfernende Figur. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.imaging.Figure---}
```
public void removeFigures(Figure[] figures)
```


Entfernt Figuren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Die zu entfernenden Figuren. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.imaging.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Fügt den angegebenen `com.aspose.imaging.GraphicsPath` an diesen Pfad an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Das `com.aspose.imaging.GraphicsPath` zum Hinzufügen. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.imaging.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Fügt den angegebenen `com.aspose.imaging.GraphicsPath` an diesen Pfad an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Das `com.aspose.imaging.GraphicsPath` zum Hinzufügen. |
| verbinden | boolean | Ein boolescher Wert, der angibt, ob die erste Figur im hinzugefügten Pfad Teil der letzten Figur in diesem Pfad ist. Der Wert true gibt an, dass die erste Figur im hinzugefügten Pfad Teil der letzten Figur in diesem Pfad ist. Der Wert false gibt an, dass die erste Figur im hinzugefügten Pfad von der letzten Figur in diesem Pfad getrennt ist. |

### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Ruft die Begrenzungen des Objekts ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Ruft die Begrenzungen des Objekts ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |
| pen | [Pen](../../com.aspose.imaging/pen) | Der Stift, der für das Objekt verwendet wird. Dies kann die Größe der Objektgrenzen beeinflussen. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Führt eine tiefe Kopie dieses Grafikpfads aus.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - A deep clone of the graphics path.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Wendet die angegebene Transformation auf die Form an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Die anzuwendende Transformation. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Überprüft, ob Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | java.lang.Object | Das andere Objekt. |

**Returns:**
boolean - Das Ergebnis des Gleichheitsvergleichs.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode des aktuellen Objekts zurück.

**Returns:**
int - Der Hashcode.
