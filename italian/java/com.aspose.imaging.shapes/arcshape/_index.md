---
title: "ArcShape"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una forma ad arco."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.shapes/arcshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging.shapes/rectangleshape), [com.aspose.imaging.shapes.EllipseShape](../../com.aspose.imaging.shapes/ellipseshape), [com.aspose.imaging.shapes.PieShape](../../com.aspose.imaging.shapes/pieshape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public final class ArcShape extends PieShape implements IOrderedShape
```

Rappresenta una forma ad arco.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ArcShape()](#ArcShape--) | Inizializza una nuova istanza della classe `ArcShape`. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)](#ArcShape-com.aspose.imaging.RectangleF-float-float-) | Inizializza una nuova istanza della classe `ArcShape`. |
| [ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)](#ArcShape-com.aspose.imaging.RectangleF-float-float-boolean-) | Inizializza una nuova istanza della classe `ArcShape`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSegments()](#getSegments--) | Ottiene i segmenti della forma. |
| [getStartPoint()](#getStartPoint--) | Ottiene il punto iniziale della forma. |
| [getEndPoint()](#getEndPoint--) | Ottiene il punto finale della forma. |
| [isClosed()](#isClosed--) | Ottiene o imposta un valore che indica se la forma ordinata è chiusa. |
| [setClosed(boolean value)](#setClosed-boolean-) | Ottiene o imposta un valore che indica se la forma ordinata è chiusa. |
| [reverse()](#reverse--) | Inverte l'ordine dei punti per questa forma. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ottiene i limiti dell'oggetto. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
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

### ArcShape() {#ArcShape--}
```
public ArcShape()
```


Inizializza una nuova istanza della classe `ArcShape`.

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle) {#ArcShape-com.aspose.imaging.RectangleF-float-float-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Inizializza una nuova istanza della classe `ArcShape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Il rettangolo. |
| startAngle | float | L'angolo di partenza. |
| sweepAngle | float | L'angolo di sweep. |

### ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed) {#ArcShape-com.aspose.imaging.RectangleF-float-float-boolean-}
```
public ArcShape(RectangleF rectangle, float startAngle, float sweepAngle, boolean isClosed)
```


Inizializza una nuova istanza della classe `ArcShape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Il rettangolo. |
| startAngle | float | L'angolo di partenza. |
| sweepAngle | float | L'angolo di sweep. |
| isClosed | boolean | Se impostato su `true` l'arco è chiuso. L'arco chiuso in realtà degenera in un'ellisse. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Ottiene i segmenti della forma.

Valore: I segmenti della forma.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Ottiene il punto iniziale della forma.

Valore: Il punto iniziale della forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Ottiene il punto finale della forma.

Valore: Il punto finale della forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Ottiene o imposta un valore che indica se la forma ordinata è chiusa. Quando si elabora una forma ordinata chiusa, i punti di inizio e fine non hanno significato.

Valore: `True` se questa forma ordinata è chiusa; altrimenti, `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Ottiene o imposta un valore che indica se la forma ordinata è chiusa. Quando si elabora una forma ordinata chiusa, i punti di inizio e fine non hanno significato.

Valore: `True` se questa forma ordinata è chiusa; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### reverse() {#reverse--}
```
public void reverse()
```


Inverte l'ordine dei punti per questa forma.

### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se gli oggetti sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'altro oggetto. |

**Returns:**
boolean - Il risultato del confronto di uguaglianza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottieni il codice hash dell'oggetto corrente.

**Returns:**
int - Il codice hash.
