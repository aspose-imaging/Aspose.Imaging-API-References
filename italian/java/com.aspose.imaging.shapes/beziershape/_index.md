---
title: "BezierShape"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una spline Bézier."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.shapes/beziershape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class BezierShape extends PolygonShape
```

Rappresenta una spline Bézier.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BezierShape()](#BezierShape--) | Inizializza una nuova istanza della classe `BezierShape`. |
| [BezierShape(PointF[] points)](#BezierShape-com.aspose.imaging.PointF---) | Inizializza una nuova istanza della classe `BezierShape`. |
| [BezierShape(PointF[] points, boolean isClosed)](#BezierShape-com.aspose.imaging.PointF---boolean-) | Inizializza una nuova istanza della classe `BezierShape`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene i limiti dell'oggetto. |
| [getCenter()](#getCenter--) | Ottiene il centro della forma. |
| [getSegments()](#getSegments--) | Ottiene i segmenti della forma. |
| [hasSegments()](#hasSegments--) | Ottiene un valore che indica se la forma ha segmenti. |
| [getEndPoint()](#getEndPoint--) | Ottiene il punto finale della forma. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ottiene i limiti dell'oggetto. |
### BezierShape() {#BezierShape--}
```
public BezierShape()
```


Inizializza una nuova istanza della classe `BezierShape`.

### BezierShape(PointF[] points) {#BezierShape-com.aspose.imaging.PointF---}
```
public BezierShape(PointF[] points)
```


Inizializza una nuova istanza della classe `BezierShape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | L'array dei punti. |

### BezierShape(PointF[] points, boolean isClosed) {#BezierShape-com.aspose.imaging.PointF---boolean-}
```
public BezierShape(PointF[] points, boolean isClosed)
```


Inizializza una nuova istanza della classe `BezierShape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | L'array dei punti. |
| isClosed | boolean | Se impostato su `true` la spline bezier è chiusa. |

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
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Ottiene il punto finale della forma.

Valore: Il punto finale della forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
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
