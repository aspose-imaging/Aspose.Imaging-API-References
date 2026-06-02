---
title: "Figure"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Abbildung."
type: docs
weight: 44
url: /de/java/com.aspose.imaging/figure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

Die Figur. Ein Container für Formen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Figure()](#Figure--) | Initialisiert eine neue [Figure](../../com.aspose.imaging/figure)-Instanz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShapes()](#getShapes--) | Ruft die Formen der Figur ab. |
| [getBounds()](#getBounds--) | Ruft die Begrenzungen des Objekts ab oder setzt sie. |
| [isClosed()](#isClosed--) | Ruft einen Wert ab, der angibt, ob diese Figur geschlossen ist. |
| [setClosed(boolean value)](#setClosed-boolean-) | Setzt einen Wert, der angibt, ob diese Figur geschlossen ist. |
| [getSegments()](#getSegments--) | Ruft die gesamten Segmente der Figur ab. |
| [addShape(Shape shape)](#addShape-com.aspose.imaging.Shape-) | Fügt der Figur eine Form hinzu. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.imaging.Shape---) | Fügt der Figur einen Bereich von Formen hinzu. |
| [removeShape(Shape shape)](#removeShape-com.aspose.imaging.Shape-) | Entfernt eine Form aus der Figur. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.imaging.Shape---) | Entfernt einen Bereich von Formen aus der Figur. |
| [reverse()](#reverse--) | Kehrt die Reihenfolge der Formen dieser Figur sowie die Punktreihenfolge der Formen um. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ruft die Begrenzungen des Objekts ab. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ruft die Begrenzungen des Objekts ab. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Wendet die angegebene Transformation auf die Form an. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist. |
| [hashCode()](#hashCode--) | Dient als Standard-Hashfunktion. |

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

### Figure() {#Figure--}
```
public Figure()
```


Initialisiert eine neue [Figure](../../com.aspose.imaging/figure)-Instanz. Ein Konstruktor, der für die JSON-Deserialisierung erforderlich ist.

### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Ruft die Formen der Figur ab.

**Returns:**
com.aspose.imaging.Shape[] - Die Formen der Figure.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ruft die Begrenzungen des Objekts ab oder setzt sie.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Gibt einen Wert zurück, der angibt, ob diese Figure geschlossen ist. Eine geschlossene Figure macht nur einen Unterschied, wenn die ersten und letzten Formen der Figure kontinuierliche Formen sind. In einem solchen Fall wird der erste Punkt der ersten Form durch eine gerade Linie mit dem letzten Punkt der letzten Form verbunden.

**Returns:**
boolean - `True`, wenn diese Figure geschlossen ist; andernfalls `false`.
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Setzt einen Wert, der angibt, ob diese Figure geschlossen ist. Eine geschlossene Figure macht nur einen Unterschied, wenn die ersten und letzten Formen der Figure kontinuierliche Formen sind. In einem solchen Fall wird der erste Punkt der ersten Form durch eine gerade Linie mit dem letzten Punkt der letzten Form verbunden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `True`, wenn diese Figure geschlossen ist; andernfalls `false`. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Ruft die gesamten Segmente der Figur ab.

**Returns:**
com.aspose.imaging.ShapeSegment[] - Die Segmente der Figure.
### addShape(Shape shape) {#addShape-com.aspose.imaging.Shape-}
```
public void addShape(Shape shape)
```


Fügt der Figur eine Form hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | Die hinzuzufügende Shape. |


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

### addShapes(Shape[] shapes) {#addShapes-com.aspose.imaging.Shape---}
```
public void addShapes(Shape[] shapes)
```


Fügt der Figur einen Bereich von Formen hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | Die hinzuzufügenden Shapes. |

### removeShape(Shape shape) {#removeShape-com.aspose.imaging.Shape-}
```
public void removeShape(Shape shape)
```


Entfernt eine Form aus der Figur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | Die zu entfernende Shape. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.imaging.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Entfernt einen Bereich von Formen aus der Figur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | Der zu entfernende Shapes-Bereich. |

### reverse() {#reverse--}
```
public void reverse()
```


Kehrt die Reihenfolge der Formen dieser Figur sowie die Punktreihenfolge der Formen um.

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
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Wendet die angegebene Transformation auf die Form an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Die anzuwendende Transformation. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das verglichene Objekt. |

**Returns:**
boolean - Das Ergebnis von equals
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Standard-Hashfunktion.

**Returns:**
int - Ein Hashcode für das aktuelle Objekt.
