---
title: "RectangleShape"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una forma rettangolare."
type: docs
weight: 17
url: /it/java/com.aspose.imaging.shapes/rectangleshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape)
```
public class RectangleShape extends RectangleProjectedShape
```

Rappresenta una forma rettangolare.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RectangleShape()](#RectangleShape--) | Inizializza una nuova istanza della classe `RectangleShape`. |
| [RectangleShape(RectangleF rectangle)](#RectangleShape-com.aspose.imaging.RectangleF-) | Inizializza una nuova istanza della classe `RectangleShape`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSegments()](#getSegments--) | Ottiene i segmenti della forma. |

## Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...
Questo esempio crea una nuova Image e disegna una varietà di forme usando Figures e GraphicsPath sulla superficie dell'Image.
``` java
//Crea un'istanza di BmpOptions e imposta le sue varie proprietà.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Crea un'istanza di FileCreateSource e assegnala come Source per l'istanza di BmpOptions
//Il secondo parametro Boolean determina se il file da creare è IsTemporal o meno
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//Crea un'istanza di Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Crea e inizializza un'istanza della classe Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Cancella la superficie Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Crea un'istanza della classe GraphicsPath
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //Crea un'istanza della classe Figure
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //Aggiungi Shape all'oggetto Figure.
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //Crea un'istanza della classe Figure
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //Aggiungi Shape all'oggetto Figure.
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

    //Aggiungi l'oggetto Figure a GraphicsPath
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //Disegna il percorso con l'oggetto Pen di colore Nero
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // salva tutte le modifiche.
    image.save();
} finally {
    image.dispose();
}
```

### RectangleShape() {#RectangleShape--}
```
public RectangleShape()
```


Inizializza una nuova istanza della classe `RectangleShape`.

### RectangleShape(RectangleF rectangle) {#RectangleShape-com.aspose.imaging.RectangleF-}
```
public RectangleShape(RectangleF rectangle)
```


Inizializza una nuova istanza della classe `RectangleShape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Il rettangolo. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Ottiene i segmenti della forma.

Valore: I segmenti della forma.

**Returns:**
com.aspose.imaging.ShapeSegment[]
