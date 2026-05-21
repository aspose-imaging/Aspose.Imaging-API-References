---
title: "EllipseShape"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en ellipsform."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.shapes/ellipseshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape)
```
public class EllipseShape extends RectangleShape
```

Representerar en ellipsform.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EllipseShape()](#EllipseShape--) | Initierar en ny instans av klassen `EllipseShape`. |
| [EllipseShape(RectangleF rectangle)](#EllipseShape-com.aspose.imaging.RectangleF-) | Initierar en ny instans av klassen `EllipseShape`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSegments()](#getSegments--) | Hämtar formens segment. |

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

### EllipseShape() {#EllipseShape--}
```
public EllipseShape()
```


Initierar en ny instans av klassen `EllipseShape`.

### EllipseShape(RectangleF rectangle) {#EllipseShape-com.aspose.imaging.RectangleF-}
```
public EllipseShape(RectangleF rectangle)
```


Initierar en ny instans av klassen `EllipseShape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Rektangeln. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Hämtar formens segment.

Värde: Formens segment.

**Returns:**
com.aspose.imaging.ShapeSegment[]
