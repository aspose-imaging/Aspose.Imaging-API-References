---
title: "PieShape"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt eine Kuchenform dar."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.shapes/pieshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape), [com.aspose.imaging.shapes.EllipseShape](../../com.aspose.imaging.shapes/ellipseshape)
```
public class PieShape extends EllipseShape
```

Stellt eine Kuchenform dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PieShape()](#PieShape--) | Initialisiert eine neue Instanz der `PieShape`-Klasse. |
| [PieShape(RectangleF rectangle, float startAngle, float sweepAngle)](#PieShape-com.aspose.imaging.RectangleF-float-float-) | Initialisiert eine neue Instanz der `PieShape`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getStartAngle()](#getStartAngle--) | Liest oder setzt den Startwinkel. |
| [setStartAngle(float value)](#setStartAngle-float-) | Liest oder setzt den Startwinkel. |
| [getSweepAngle()](#getSweepAngle--) | Liest oder setzt den Sweep-Winkel. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Liest oder setzt den Sweep-Winkel. |
| [getSegments()](#getSegments--) | Liefert die Segmente der Form. |
| [equals(Object o)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
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

### PieShape() {#PieShape--}
```
public PieShape()
```


Initialisiert eine neue Instanz der `PieShape`-Klasse.

### PieShape(RectangleF rectangle, float startAngle, float sweepAngle) {#PieShape-com.aspose.imaging.RectangleF-float-float-}
```
public PieShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Initialisiert eine neue Instanz der `PieShape`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Das Rechteck. |
| startAngle | float | Der Startwinkel. |
| sweepAngle | float | Der Sweep-Winkel. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Liest oder setzt den Startwinkel.

Wert: Der Startwinkel.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Liest oder setzt den Startwinkel.

Wert: Der Startwinkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Liest oder setzt den Sweep-Winkel.

Wert: Der Sweep-Winkel.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Liest oder setzt den Sweep-Winkel.

Wert: Der Sweep-Winkel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Liefert die Segmente der Form.

Wert: Die Formsegmente.

**Returns:**
com.aspose.imaging.ShapeSegment[]
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
