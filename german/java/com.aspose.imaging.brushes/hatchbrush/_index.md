---
title: "HatchBrush"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Definiert einen rechteckigen Pinsel mit einem Schraffurstil, einer Vordergrundfarbe und einer Hintergrundfarbe."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.brushes/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class HatchBrush extends Brush
```

Definiert einen rechteckigen Pinsel mit einem Schraffurstil, einer Vordergrundfarbe und einer Hintergrundfarbe. Diese Klasse kann nicht abgeleitet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getForegroundColor()](#getForegroundColor--) | Gibt die Farbe der Schraffurlinien zurück. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.imaging.Color-) | Setzt die Farbe der Schraffurlinien. |
| [getBackgroundColor()](#getBackgroundColor--) | Gibt die Farbe der Zwischenräume zwischen den Schraffurlinien zurück. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Setzt die Farbe der Zwischenräume zwischen den Schraffurlinien. |
| [getHatchStyle()](#getHatchStyle--) | Gibt den Schraffurstil dieses Pinsels zurück. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Legt den Schraffurstil dieses Pinsels fest. |

## Example: This example shows the creation and usage Pen objects.
Dieses Beispiel zeigt die Erstellung und Verwendung von Pen-Objekten. Das Beispiel erstellt ein neues Image und zeichnet Rechtecke auf der Image-Oberfläche.
``` java

// Erstellen Sie eine Instanz von BmpOptions und setzen Sie deren verschiedene Eigenschaften
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von BmpOptions zu
// Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei IsTemporal ist oder nicht
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Erstelle eine Instanz von Image am angegebenen Pfad
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Erstelle eine Instanz von Graphics und initialisiere sie mit dem Image-Objekt
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Leere die Graphics-Oberfläche mit weißer Farbe
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Erstelle eine Instanz von Pen mit der Farbe Rot und einer Breite von 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Erstelle eine Instanz von HatchBrush und setze deren Eigenschaften
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Erstelle eine Instanz von Pen und initialisiere sie mit dem HatchBrush-Objekt und einer Breite
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Zeichne Rechtecke, indem du das Pen-Objekt angibst
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Zeichne Rechtecke, indem du das Pen-Objekt angibst
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Speichere alle Änderungen.
    image.save();
} finally {
    image.dispose();
}
```

### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Gibt die Farbe der Schraffurlinien zurück.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of hatch lines.
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.imaging.Color-}
```
public void setForegroundColor(Color value)
```


Setzt die Farbe der Schraffurlinien.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Die Farbe der Schraffurlinien. |


**Example: This example shows the creation and usage Pen objects.**
Dieses Beispiel zeigt die Erstellung und Verwendung von Pen-Objekten. Das Beispiel erstellt ein neues Image und zeichnet Rechtecke auf der Image-Oberfläche.
``` java

// Erstellen Sie eine Instanz von BmpOptions und setzen Sie deren verschiedene Eigenschaften
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von BmpOptions zu
// Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei IsTemporal ist oder nicht
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Erstelle eine Instanz von Image am angegebenen Pfad
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Erstelle eine Instanz von Graphics und initialisiere sie mit dem Image-Objekt
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Leere die Graphics-Oberfläche mit weißer Farbe
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Erstelle eine Instanz von Pen mit der Farbe Rot und einer Breite von 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Erstelle eine Instanz von HatchBrush und setze deren Eigenschaften
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Erstelle eine Instanz von Pen und initialisiere sie mit dem HatchBrush-Objekt und einer Breite
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Zeichne Rechtecke, indem du das Pen-Objekt angibst
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Zeichne Rechtecke, indem du das Pen-Objekt angibst
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Speichere alle Änderungen.
    image.save();
} finally {
    image.dispose();
}
```

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gibt die Farbe der Zwischenräume zwischen den Schraffurlinien zurück.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of spaces between the hatch lines.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Setzt die Farbe der Zwischenräume zwischen den Schraffurlinien.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Die Farbe der Zwischenräume zwischen den Schraffurlinien. |


**Example: This example shows the creation and usage Pen objects.**
Dieses Beispiel zeigt die Erstellung und Verwendung von Pen-Objekten. Das Beispiel erstellt ein neues Image und zeichnet Rechtecke auf der Image-Oberfläche.
``` java

// Erstellen Sie eine Instanz von BmpOptions und setzen Sie deren verschiedene Eigenschaften
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von BmpOptions zu
// Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei IsTemporal ist oder nicht
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Erstelle eine Instanz von Image am angegebenen Pfad
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Erstelle eine Instanz von Graphics und initialisiere sie mit dem Image-Objekt
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Leere die Graphics-Oberfläche mit weißer Farbe
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Erstelle eine Instanz von Pen mit der Farbe Rot und einer Breite von 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Erstelle eine Instanz von HatchBrush und setze deren Eigenschaften
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Erstelle eine Instanz von Pen und initialisiere sie mit dem HatchBrush-Objekt und einer Breite
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Zeichne Rechtecke, indem du das Pen-Objekt angibst
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Zeichne Rechtecke, indem du das Pen-Objekt angibst
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Speichere alle Änderungen.
    image.save();
} finally {
    image.dispose();
}
```

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Gibt den Schraffurstil dieses Pinsels zurück.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Legt den Schraffurstil dieses Pinsels fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

