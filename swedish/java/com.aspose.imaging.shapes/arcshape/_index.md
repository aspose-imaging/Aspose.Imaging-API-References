---
title: "ArcShape"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en bågform."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.shapes/arcshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape), [com.aspose.imaging.shapes.EllipseShape](../../com.aspose.imaging.shapes/ellipseshape), [com.aspose.imaging.shapes.PieShape](../../com.aspose.imaging/shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Representerar en bågform.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ArcShape()](#ArcShape--) | Initierar en ny instans av klassen `ArcShape`. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.imaging.RectangleF-float-float-) | Initierar en ny instans av klassen `ArcShape`. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.imaging.RectangleF-float-float-boolean-) | Initierar en ny instans av klassen `ArcShape`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSegments()](#getSegments--) | Hämtar formens segment. |
| [getStartPoint()](#getStartPoint--) | Hämtar startpunkten för formen. |
| [getEndPoint()](#getEndPoint--) | Hämtar slutpunkten för formen. |
| [isClosed()](#isClosed--) | Hämtar eller anger ett värde som indikerar om den ordnade formen är sluten. |
| [setClosed(boolean value)](#setClosed-boolean-) | Hämtar eller anger ett värde som indikerar om den ordnade formen är sluten. |
| [reverse()](#reverse--) | Vänder på ordningen av punkter för denna form. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Hämtar objektets gränser. |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
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

### ArcShape() {#ArcShape--}
```
public ArcShape()
```


Initierar en ny instans av klassen `ArcShape`.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.imaging.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Initierar en ny instans av klassen `ArcShape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Rektangeln. |
| startAngle | float | Startvinkeln. |
| sweepAngle | float | Svepvinkeln. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.imaging.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


Initierar en ny instans av klassen `ArcShape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Rektangeln. |
| startAngle | float | Startvinkeln. |
| sweepAngle | float | Svepvinkeln. |
| isClosed | boolean | Om den är satt till `true` är bågen sluten. Den slutna bågen degenererar i själva verket till en ellips. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Hämtar formens segment.

Värde: Formens segment.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Hämtar startpunkten för formen.

Värde: Formens startpunkt.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Hämtar slutpunkten för formen.

Värde: Formens slutpunkt.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Hämtar eller anger ett värde som indikerar om den ordnade formen är sluten. Vid bearbetning av en sluten ordnad form har start- och slutpunkterna ingen betydelse.

Värde: `True` om denna ordnade form är sluten; annars `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Hämtar eller anger ett värde som indikerar om den ordnade formen är sluten. Vid bearbetning av en sluten ordnad form har start- och slutpunkterna ingen betydelse.

Värde: `True` om denna ordnade form är sluten; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### reverse() {#reverse--}
```
public void reverse()
```


Vänder på ordningen av punkter för denna form.

### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Matriser att tillämpa innan gränser beräknas. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det andra objektet. |

**Returns:**
boolean - Resultatet av likhetsjämförelsen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int - Hashkoden.
