---
title: "SolidBrush"
second_title: "Aspose.Imaging för Java API-referens"
description: "Solid pensel är avsedd för kontinuerlig ritning med en specifik färg."
type: docs
weight: 17
url: /sv/java/com.aspose.imaging.brushes/solidbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class SolidBrush extends Brush
```

Solid brush är avsedd för att rita kontinuerligt med en specifik färg. Denna klass kan inte ärvas.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | Initierar en ny instans av klassen `SolidBrush`. |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.imaging.Color-) | Initierar en ny instans av klassen `SolidBrush`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColor()](#getColor--) | Hämtar eller anger penselfärgen. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Hämtar eller anger penselfärgen. |
| [hashCode()](#hashCode--) |  |
| [equals(Object object)](#equals-java.lang.Object-) |  |

## Example: This example uses Graphics class to create primitive shapes on the Image surface.
Detta exempel använder Graphics-klassen för att skapa primitiva former på bildytan. För att demonstrera operationen skapar exemplet en ny bild i PNG-format och ritar primitiva former på bildytan med Draw-metoder som exponeras av Graphics-klassen.
``` java
// Skapar en instans av FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Skapa en instans av PngOptions och ange dess olika egenskaper
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Ange källan för PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Skapa en instans av Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Skapa och initiera en instans av Graphics-klassen
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Rensa Graphics-ytan
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Rita en båge genom att ange Pen-objektet med svart com.aspose.imaging.Color,
        // en rektangel som omger bågen, startvinkel och svepvinkel
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Rita en Bezier genom att ange Pen-objektet med blått com.aspose.imaging.Color och koordinatpunkter.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Rita en kurva genom att ange Pen-objektet med grönt com.aspose.imaging.Color och en array av punkter
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Rita en ellips med Pen-objektet och en omgivande rektangel
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Rita en linje
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Rita ett pajsegment
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Rita en polygon genom att ange Pen-objektet med rött com.aspose.imaging.Color och en array av punkter
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Rita en rektangel
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Skapa ett SolidBrush-objekt och ange dess olika egenskaper
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Rita en sträng med SolidBrush-objektet och Font, vid en specifik punkt
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Spara alla ändringar.
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


Initierar en ny instans av klassen `SolidBrush`.

### SolidBrush(Color color) {#SolidBrush-com.aspose.imaging.Color-}
```
public SolidBrush(Color color)
```


Initierar en ny instans av klassen `SolidBrush`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Färgen på solid brush. |

### getColor() {#getColor--}
```
public Color getColor()
```


Hämtar eller anger penselfärgen.

Värde: Penselfärgen.

**Returns:**
[Color](../../com.aspose.imaging/color)

**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
Detta exempel använder Graphics-klassen för att skapa primitiva former på bildytan. För att demonstrera operationen skapar exemplet en ny bild i PNG-format och ritar primitiva former på bildytan med Draw-metoder som exponeras av Graphics-klassen.
``` java
// Skapar en instans av FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Skapa en instans av PngOptions och ange dess olika egenskaper
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Ange källan för PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Skapa en instans av Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Skapa och initiera en instans av Graphics-klassen
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Rensa Graphics-ytan
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Rita en båge genom att ange Pen-objektet med svart com.aspose.imaging.Color,
        // en rektangel som omger bågen, startvinkel och svepvinkel
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Rita en Bezier genom att ange Pen-objektet med blått com.aspose.imaging.Color och koordinatpunkter.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Rita en kurva genom att ange Pen-objektet med grönt com.aspose.imaging.Color och en array av punkter
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Rita en ellips med Pen-objektet och en omgivande rektangel
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Rita en linje
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Rita ett pajsegment
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Rita en polygon genom att ange Pen-objektet med rött com.aspose.imaging.Color och en array av punkter
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Rita en rektangel
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Skapa ett SolidBrush-objekt och ange dess olika egenskaper
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Rita en sträng med SolidBrush-objektet och Font, vid en specifik punkt
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Spara alla ändringar.
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


Hämtar eller anger penselfärgen.

Värde: Penselfärgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int
### equals(Object object) {#equals-java.lang.Object-}
```
public boolean equals(Object object)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | java.lang.Object |  |

**Returns:**
boolean
