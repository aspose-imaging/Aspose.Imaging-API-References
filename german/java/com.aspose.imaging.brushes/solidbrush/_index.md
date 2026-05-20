---
title: "SolidBrush"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Ein Vollpinsel ist zum kontinuierlichen Zeichnen mit einer bestimmten Farbe gedacht."
type: docs
weight: 17
url: /de/java/com.aspose.imaging.brushes/solidbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class SolidBrush extends Brush
```

SolidBrush ist für das kontinuierliche Zeichnen mit einer bestimmten Farbe vorgesehen. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | Initialisiert eine neue Instanz der `SolidBrush`-Klasse. |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.imaging.Color-) | Initialisiert eine neue Instanz der `SolidBrush`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColor()](#getColor--) | Liest oder setzt die Pinsel­farbe. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Liest oder setzt die Pinsel­farbe. |
| [hashCode()](#hashCode--) |  |
| [equals(Object object)](#equals-java.lang.Object-) |  |

## Example: This example uses Graphics class to create primitive shapes on the Image surface.
Dieses Beispiel verwendet die Graphics‑Klasse, um primitive Formen auf der Bildoberfläche zu erstellen. Um die Funktionsweise zu demonstrieren, erstellt das Beispiel ein neues Bild im PNG‑Format und zeichnet primitive Formen auf der Bildoberfläche mithilfe der von der Graphics‑Klasse bereitgestellten Draw‑Methoden.
``` java
// Erstellt eine Instanz von FileStream.
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Erstelle eine Instanz von PngOptions und setze deren verschiedene Eigenschaften.
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Lege die Quelle für PngOptions fest.
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Erstelle eine Instanz von Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Erstelle und initialisiere eine Instanz der Klasse Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Leere die Graphics-Oberfläche
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Zeichne einen Bogen, indem du das Pen‑Objekt mit der schwarzen com.aspose.imaging.Color angibst,
        // ein Rechteck, das den Bogen umgibt, Startwinkel und Sweep‑Winkel
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Zeichne eine Bézierkurve, indem du das Pen‑Objekt mit der blauen com.aspose.imaging.Color und den Koordinatenpunkten angibst.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Zeichne eine Kurve, indem du das Pen‑Objekt mit der grünen com.aspose.imaging.Color und einem Array von Punkten angibst.
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Zeichne eine Ellipse mit dem Pen‑Objekt und einem umgebenden Rechteck.
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Zeichne eine Linie.
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Zeichne ein Kuchenstück.
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Zeichne ein Polygon, indem du das Pen‑Objekt mit der roten com.aspose.imaging.Color und einem Array von Punkten angibst.
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Zeichne ein Rechteck.
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Erstelle ein SolidBrush‑Objekt und setze dessen verschiedene Eigenschaften.
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Zeichne einen String mit dem SolidBrush‑Objekt und einer Schriftart an einem bestimmten Punkt.
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Speichere alle Änderungen.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


Initialisiert eine neue Instanz der `SolidBrush`-Klasse.

### SolidBrush(Color color) {#SolidBrush-com.aspose.imaging.Color-}
```
public SolidBrush(Color color)
```


Initialisiert eine neue Instanz der `SolidBrush`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Die Farbe des SolidBrush. |

### getColor() {#getColor--}
```
public Color getColor()
```


Liest oder setzt die Pinsel­farbe.

Wert: Die Pinsel­farbe.

**Returns:**
[Color](../../com.aspose.imaging/color)

**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
Dieses Beispiel verwendet die Graphics‑Klasse, um primitive Formen auf der Bildoberfläche zu erstellen. Um die Funktionsweise zu demonstrieren, erstellt das Beispiel ein neues Bild im PNG‑Format und zeichnet primitive Formen auf der Bildoberfläche mithilfe der von der Graphics‑Klasse bereitgestellten Draw‑Methoden.
``` java
// Erstellt eine Instanz von FileStream.
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Erstelle eine Instanz von PngOptions und setze deren verschiedene Eigenschaften.
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Lege die Quelle für PngOptions fest.
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Erstelle eine Instanz von Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Erstelle und initialisiere eine Instanz der Klasse Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Leere die Graphics-Oberfläche
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Zeichne einen Bogen, indem du das Pen‑Objekt mit der schwarzen com.aspose.imaging.Color angibst,
        // ein Rechteck, das den Bogen umgibt, Startwinkel und Sweep‑Winkel
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Zeichne eine Bézierkurve, indem du das Pen‑Objekt mit der blauen com.aspose.imaging.Color und den Koordinatenpunkten angibst.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Zeichne eine Kurve, indem du das Pen‑Objekt mit der grünen com.aspose.imaging.Color und einem Array von Punkten angibst.
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Zeichne eine Ellipse mit dem Pen‑Objekt und einem umgebenden Rechteck.
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Zeichne eine Linie.
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Zeichne ein Kuchenstück.
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Zeichne ein Polygon, indem du das Pen‑Objekt mit der roten com.aspose.imaging.Color und einem Array von Punkten angibst.
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Zeichne ein Rechteck.
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Erstelle ein SolidBrush‑Objekt und setze dessen verschiedene Eigenschaften.
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Zeichne einen String mit dem SolidBrush‑Objekt und einer Schriftart an einem bestimmten Punkt.
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Speichere alle Änderungen.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Liest oder setzt die Pinsel­farbe.

Wert: Die Pinsel­farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode des aktuellen Objekts zurück.

**Returns:**
int
### equals(Object object) {#equals-java.lang.Object-}
```
public boolean equals(Object object)
```


Überprüft, ob Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Objekt | java.lang.Object |  |

**Returns:**
boolean
