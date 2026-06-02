---
title: "PolygonShape"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una forma poligonale."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.shapes/polygonshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Rappresenta una forma poligonale.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | Inizializza una nuova istanza della classe `PolygonShape`. |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.imaging.PointF---) | Inizializza una nuova istanza della classe `PolygonShape`. |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.imaging.PointF---boolean-) | Inizializza una nuova istanza della classe `PolygonShape`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPoints()](#getPoints--) | Ottiene o imposta i punti della curva. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.imaging.PointF---) | Ottiene o imposta i punti della curva. |
| [isClosed()](#isClosed--) | Ottiene o imposta un valore che indica se la forma è chiusa. |
| [setClosed(boolean value)](#setClosed-boolean-) | Ottiene o imposta un valore che indica se la forma è chiusa. |
| [getBounds()](#getBounds--) | Ottiene i limiti dell'oggetto. |
| [getCenter()](#getCenter--) | Ottiene il centro della forma. |
| [getSegments()](#getSegments--) | Ottiene i segmenti della forma. |
| [hasSegments()](#hasSegments--) | Ottiene un valore che indica se la forma ha segmenti. |
| [getStartPoint()](#getStartPoint--) | Ottiene il punto iniziale della forma. |
| [getEndPoint()](#getEndPoint--) | Ottiene il punto finale della forma. |
| [reverse()](#reverse--) | Inverte l'ordine dei punti per questa forma. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ottiene i limiti dell'oggetto. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applica la trasformazione specificata alla forma. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'oggetto specificato è uguale all'oggetto corrente. |
| [hashCode()](#hashCode--) | Funziona come funzione hash predefinita. |

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

### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


Inizializza una nuova istanza della classe `PolygonShape`.

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.imaging.PointF---}
```
public PolygonShape(PointF[] points)
```


Inizializza una nuova istanza della classe `PolygonShape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | L'array dei punti. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.imaging.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


Inizializza una nuova istanza della classe `PolygonShape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | L'array dei punti. |
| isClosed | boolean | Se impostato su `true` il poligono è chiuso. |

### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Ottiene o imposta i punti della curva.

Valore: I punti della curva.

**Returns:**
com.aspose.imaging.PointF[]
### setPoints(PointF[] value) {#setPoints-com.aspose.imaging.PointF---}
```
public void setPoints(PointF[] value)
```


Ottiene o imposta i punti della curva.

Valore: I punti della curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Ottiene o imposta un valore che indica se la forma è chiusa.

Valore: `true` se la forma è chiusa; altrimenti, `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Ottiene o imposta un valore che indica se la forma è chiusa.

Valore: `true` se la forma è chiusa; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Ottiene i limiti dell'oggetto.

Valore: I limiti dell'oggetto.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Ottiene il centro della forma.

Valore: Il centro della forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Ottiene i segmenti della forma.

Valore: I segmenti della forma.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Ottiene un valore che indica se la forma ha segmenti.

Valore: `True` se la forma ha segmenti; altrimenti, `false`.

**Returns:**
boolean
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
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Ottiene i limiti dell'oggetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matrice da applicare prima che i limiti vengano calcolati. |
| pen | [Pen](../../com.aspose.imaging/pen) | La penna da usare per l'oggetto. Questo può influenzare le dimensioni dei limiti dell'oggetto. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Applica la trasformazione specificata alla forma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | La trasformazione da applicare. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'oggetto specificato è uguale all'oggetto corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto confrontato. |

**Returns:**
boolean - Il risultato di equals
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funziona come funzione hash predefinita.

**Returns:**
int - Un codice hash per l'oggetto corrente.
