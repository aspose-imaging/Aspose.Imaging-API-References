---
title: "ArcShape"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt eine Bogenform dar."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.shapes/arcshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape), [com.aspose.imaging.shapes.EllipseShape](../../com.aspose.imaging.shapes/ellipseshape), [com.aspose.imaging.shapes.PieShape](../../com.aspose.imaging.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Stellt eine Bogenform dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ArcShape()](#ArcShape--) | Initialisiert eine neue Instanz der `ArcShape`-Klasse. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.imaging.RectangleF-float-float-) | Initialisiert eine neue Instanz der `ArcShape`-Klasse. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.imaging.RectangleF-float-float-boolean-) | Initialisiert eine neue Instanz der `ArcShape`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSegments()](#getSegments--) | Liefert die Segmente der Form. |
| [getStartPoint()](#getStartPoint--) | Ruft den Startpunkt der Form ab. |
| [getEndPoint()](#getEndPoint--) | Ruft den Endpunkt der Form ab. |
| [isClosed()](#isClosed--) | Liest oder setzt einen Wert, der angibt, ob die geordnete Form geschlossen ist. |
| [setClosed(boolean value)](#setClosed-boolean-) | Liest oder setzt einen Wert, der angibt, ob die geordnete Form geschlossen ist. |
| [reverse()](#reverse--) | Kehrt die Reihenfolge der Punkte für diese Form um. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ruft die Begrenzungen des Objekts ab. |
| [equals(Object obj)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
| [hashCode()](#hashCode--) | Gibt den Hashcode des aktuellen Objekts zurück. |

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

### ArcShape() {#ArcShape--}
```
public ArcShape()
```


Initialisiert eine neue Instanz der `ArcShape`-Klasse.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.imaging.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Initialisiert eine neue Instanz der `ArcShape`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Das Rechteck. |
| startAngle | float | Der Startwinkel. |
| sweepAngle | float | Der Sweep-Winkel. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.imaging.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


Initialisiert eine neue Instanz der `ArcShape`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Das Rechteck. |
| startAngle | float | Der Startwinkel. |
| sweepAngle | float | Der Sweep-Winkel. |
| isClosed | boolean | Wenn auf `true` gesetzt, ist der Bogen geschlossen. Der geschlossene Bogen degeneriert tatsächlich zu einer Ellipse. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Liefert die Segmente der Form.

Wert: Die Formsegmente.

**Returns:**
com.aspose.imaging.ShapeSegment[]
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
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Liest oder setzt einen Wert, der angibt, ob die geordnete Form geschlossen ist. Beim Verarbeiten einer geschlossenen geordneten Form haben die Start- und Endpunkte keine Bedeutung.

Wert: `True`, wenn diese geordnete Form geschlossen ist; andernfalls `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die geordnete Form geschlossen ist. Beim Verarbeiten einer geschlossenen geordneten Form haben die Start- und Endpunkte keine Bedeutung.

Wert: `True`, wenn diese geordnete Form geschlossen ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Überprüft, ob Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das andere Objekt. |

**Returns:**
boolean - Das Ergebnis des Gleichheitsvergleichs.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode des aktuellen Objekts zurück.

**Returns:**
int - Der Hashcode.
