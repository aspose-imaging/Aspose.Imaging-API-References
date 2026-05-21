---
title: "PolygonShape"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt eine Polygonform dar."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.shapes/polygonshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Stellt eine Polygonform dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | Initialisiert eine neue Instanz der Klasse `PolygonShape`. |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.imaging.PointF---) | Initialisiert eine neue Instanz der Klasse `PolygonShape`. |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.imaging.PointF---boolean-) | Initialisiert eine neue Instanz der Klasse `PolygonShape`. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPoints()](#getPoints--) | Ruft die Kurvenpunkte ab oder legt sie fest. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.imaging.PointF---) | Ruft die Kurvenpunkte ab oder legt sie fest. |
| [isClosed()](#isClosed--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Form geschlossen ist. |
| [setClosed(boolean value)](#setClosed-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Form geschlossen ist. |
| [getBounds()](#getBounds--) | Ruft die Begrenzungen des Objekts ab. |
| [getCenter()](#getCenter--) | Liefert das Zentrum der Form. |
| [getSegments()](#getSegments--) | Liefert die Segmente der Form. |
| [hasSegments()](#hasSegments--) | Liefert einen Wert, der angibt, ob die Form Segmente hat. |
| [getStartPoint()](#getStartPoint--) | Ruft den Startpunkt der Form ab. |
| [getEndPoint()](#getEndPoint--) | Ruft den Endpunkt der Form ab. |
| [reverse()](#reverse--) | Kehrt die Reihenfolge der Punkte für diese Form um. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ruft die Begrenzungen des Objekts ab. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ruft die Begrenzungen des Objekts ab. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Wendet die angegebene Transformation auf die Form an. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist. |
| [hashCode()](#hashCode--) | Dient als Standard-Hashfunktion. |

## Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...
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

### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


Initialisiert eine neue Instanz der Klasse `PolygonShape`.

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.imaging.PointF---}
```
public PolygonShape(PointF[] points)
```


Initialisiert eine neue Instanz der Klasse `PolygonShape`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Das Punkte-Array. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.imaging.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


Initialisiert eine neue Instanz der Klasse `PolygonShape`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Das Punkte-Array. |
| isClosed | boolean | Wenn auf `true` gesetzt, ist das Polygon geschlossen. |

### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Ruft die Kurvenpunkte ab oder legt sie fest.

Wert: Die Kurvenpunkte.

**Returns:**
com.aspose.imaging.PointF[]
### setPoints(PointF[] value) {#setPoints-com.aspose.imaging.PointF---}
```
public void setPoints(PointF[] value)
```


Ruft die Kurvenpunkte ab oder legt sie fest.

Wert: Die Kurvenpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Form geschlossen ist.

Wert: `true`, wenn die Form geschlossen ist; andernfalls `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Form geschlossen ist.

Wert: `true`, wenn die Form geschlossen ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ruft die Begrenzungen des Objekts ab.

Wert: Die Begrenzungen des Objekts.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Liefert das Zentrum der Form.

Wert: Der Mittelpunkt der Form.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Liefert die Segmente der Form.

Wert: Die Formsegmente.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Liefert einen Wert, der angibt, ob die Form Segmente hat.

Wert: `True`, wenn die Form Segmente hat; andernfalls `false`.

**Returns:**
boolean
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Ruft den Startpunkt der Form ab.

Wert: Der Startpunkt der Form.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Ruft den Endpunkt der Form ab.

Wert: Der Endpunkt der Form.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### reverse() {#reverse--}
```
public void reverse()
```


Kehrt die Reihenfolge der Punkte für diese Form um.

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
