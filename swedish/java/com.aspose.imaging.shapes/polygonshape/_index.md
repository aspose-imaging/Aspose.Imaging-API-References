---
title: "PolygonShape"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en polygonform."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.shapes/polygonshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Representerar en polygonform.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | Initierar en ny instans av klassen `PolygonShape`. |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.imaging.PointF---) | Initierar en ny instans av klassen `PolygonShape`. |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.imaging.PointF---boolean-) | Initierar en ny instans av klassen `PolygonShape`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPoints()](#getPoints--) | Hämtar eller anger kurvpunkterna. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.imaging.PointF---) | Hämtar eller anger kurvpunkterna. |
| [isClosed()](#isClosed--) | Hämtar eller anger ett värde som indikerar om formen är sluten. |
| [setClosed(boolean value)](#setClosed-boolean-) | Hämtar eller anger ett värde som indikerar om formen är sluten. |
| [getBounds()](#getBounds--) | Hämtar objektets gränser. |
| [getCenter()](#getCenter--) | Hämtar formens centrum. |
| [getSegments()](#getSegments--) | Hämtar formens segment. |
| [hasSegments()](#hasSegments--) | Hämtar ett värde som indikerar om formen har segment. |
| [getStartPoint()](#getStartPoint--) | Hämtar startpunkten för formen. |
| [getEndPoint()](#getEndPoint--) | Hämtar slutpunkten för formen. |
| [reverse()](#reverse--) | Vänder på ordningen av punkter för denna form. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Hämtar objektets gränser. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Hämtar objektets gränser. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Tillämpar den angivna transformationen på formen. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna objektet är lika med det aktuella objektet. |
| [hashCode()](#hashCode--) | Fungerar som standardhashfunktion. |

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

### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


Initierar en ny instans av klassen `PolygonShape`.

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.imaging.PointF---}
```
public PolygonShape(PointF[] points)
```


Initierar en ny instans av klassen `PolygonShape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Punktarrayen. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.imaging.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


Initierar en ny instans av klassen `PolygonShape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Punktarrayen. |
| isClosed | boolean | Om den är satt till `true` är polygonen sluten. |

### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Hämtar eller anger kurvpunkterna.

Värde: Kurvans punkter.

**Returns:**
com.aspose.imaging.PointF[]
### setPoints(PointF[] value) {#setPoints-com.aspose.imaging.PointF---}
```
public void setPoints(PointF[] value)
```


Hämtar eller anger kurvpunkterna.

Värde: Kurvans punkter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Hämtar eller anger ett värde som indikerar om formen är sluten.

Värde: `true` om formen är sluten; annars `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Hämtar eller anger ett värde som indikerar om formen är sluten.

Värde: `true` om formen är sluten; annars `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Hämtar objektets gränser.

Värde: Objektets gränser.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Hämtar formens centrum.

Värde: Formens centrum.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Hämtar formens segment.

Värde: Formens segment.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Hämtar ett värde som indikerar om formen har segment.

Värde: `True` om formen har segment; annars `false`.

**Returns:**
boolean
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
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Matriser att tillämpa innan gränser beräknas. |
| pen | [Pen](../../com.aspose.imaging/pen) | Pennan att använda för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Tillämpar den angivna transformationen på formen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Transformationen att tillämpa. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna objektet är lika med det aktuella objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det jämförda objektet. |

**Returns:**
boolean - Resultatet av equals
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som standardhashfunktion.

**Returns:**
int - En hashkod för det aktuella objektet.
