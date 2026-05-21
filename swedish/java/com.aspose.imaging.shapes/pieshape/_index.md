---
title: "PieShape"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en pajform."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.shapes/pieshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape), [com.aspose.imaging.shapes.EllipseShape](../../com.aspose.imaging.shapes/ellipseshape)
```
public class PieShape extends EllipseShape
```

Representerar en pajform.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PieShape()](#PieShape--) | Initierar en ny instans av klassen `PieShape`. |
| [PieShape(RectangleF rectangle, float startAngle, float sweepAngle)](#PieShape-com.aspose.imaging.RectangleF-float-float-) | Initierar en ny instans av klassen `PieShape`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getStartAngle()](#getStartAngle--) | Hämtar eller anger startvinkeln. |
| [setStartAngle(float value)](#setStartAngle-float-) | Hämtar eller anger startvinkeln. |
| [getSweepAngle()](#getSweepAngle--) | Hämtar eller anger svepvinkeln. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Hämtar eller anger svepvinkeln. |
| [getSegments()](#getSegments--) | Hämtar formens segment. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) | Hämta hashkoden för det aktuella objektet. |

## Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...
Detta exempel skapar en ny Image och ritar en mängd olika former med hjälp av Figures och GraphicsPath på Image-ytan.
``` java
//Skapar en instans av BmpOptions och sätter dess olika egenskaper.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Skapa en instans av FileCreateSource och tilldela den som Source för BmpOptions‑instansen.
//Den andra booleska parametern avgör om filen som ska skapas är temporär eller inte.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//Skapa en instans av Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Skapa och initiera en instans av Graphics-klassen
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Rensa Graphics-ytan
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Skapa en instans av GraphicsPath-klassen
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //Skapa en instans av Figure-klassen
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //Lägg till Shape i Figure-objektet.
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //Skapa en instans av Figure-klassen
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //Lägg till Shape i Figure-objektet.
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

    //Lägg till Figure-objektet i GraphicsPath
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //Rita bana med Pen-objekt av färgen Black
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // spara alla ändringar.
    image.save();
} finally {
    image.dispose();
}
```

### PieShape() {#PieShape--}
```
public PieShape()
```


Initierar en ny instans av klassen `PieShape`.

### PieShape(RectangleF rectangle, float startAngle, float sweepAngle) {#PieShape-com.aspose.imaging.RectangleF-float-float-}
```
public PieShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Initierar en ny instans av klassen `PieShape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Rektangeln. |
| startAngle | float | Startvinkeln. |
| sweepAngle | float | Svepvinkeln. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Hämtar eller anger startvinkeln.

Värde: Startvinkeln.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Hämtar eller anger startvinkeln.

Värde: Startvinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Hämtar eller anger svepvinkeln.

Värde: Svepvinkeln.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Hämtar eller anger svepvinkeln.

Värde: Svepvinkeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Hämtar formens segment.

Värde: Formens segment.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Det andra objektet. |

**Returns:**
boolean - Resultatet av likhetsjämförelsen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int - Hashkoden.
