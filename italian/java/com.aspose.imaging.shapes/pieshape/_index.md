---
title: "PieShape"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una forma a torta."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.shapes/pieshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape), [com.aspose.imaging.shapes.EllipseShape](../../com.aspose.imaging.shapes/ellipseshape)
```
public class PieShape extends EllipseShape
```

Rappresenta una forma a torta.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PieShape()](#PieShape--) | Inizializza una nuova istanza della classe `PieShape`. |
| [PieShape(RectangleF rectangle, float startAngle, float sweepAngle)](#PieShape-com.aspose.imaging.RectangleF-float-float-) | Inizializza una nuova istanza della classe `PieShape`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getStartAngle()](#getStartAngle--) | Ottiene o imposta l'angolo di partenza. |
| [setStartAngle(float value)](#setStartAngle-float-) | Ottiene o imposta l'angolo di partenza. |
| [getSweepAngle()](#getSweepAngle--) | Ottiene o imposta l'angolo di sweep. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Ottiene o imposta l'angolo di sweep. |
| [getSegments()](#getSegments--) | Ottiene i segmenti della forma. |
| [equals(Object o)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
| [hashCode()](#hashCode--) | Ottieni il codice hash dell'oggetto corrente. |

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

### PieShape() {#PieShape--}
```
public PieShape()
```


Inizializza una nuova istanza della classe `PieShape`.

### PieShape(RectangleF rectangle, float startAngle, float sweepAngle) {#PieShape-com.aspose.imaging.RectangleF-float-float-}
```
public PieShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Inizializza una nuova istanza della classe `PieShape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Il rettangolo. |
| startAngle | float | L'angolo di partenza. |
| sweepAngle | float | L'angolo di sweep. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Ottiene o imposta l'angolo di partenza.

Valore: L'angolo di partenza.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Ottiene o imposta l'angolo di partenza.

Valore: L'angolo di partenza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Ottiene o imposta l'angolo di sweep.

Valore: L'angolo di sweep.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Ottiene o imposta l'angolo di sweep.

Valore: L'angolo di sweep.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Ottiene i segmenti della forma.

Valore: I segmenti della forma.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Verifica se gli oggetti sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | java.lang.Object | L'altro oggetto. |

**Returns:**
boolean - Il risultato del confronto di uguaglianza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottieni il codice hash dell'oggetto corrente.

**Returns:**
int - Il codice hash.
