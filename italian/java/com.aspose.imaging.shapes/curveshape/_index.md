---
title: "CurveShape"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una forma spline curva."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.shapes/curveshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class CurveShape extends PolygonShape
```

Rappresenta una forma spline curva.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CurveShape()](#CurveShape--) | Inizializza una nuova istanza della classe `CurveShape`. |
| [CurveShape(PointF[] points)](#CurveShape-com.aspose.imaging.PointF---) | Inizializza una nuova istanza della classe `CurveShape`. |
| [CurveShape(PointF[] points, boolean isClosed)](#CurveShape-com.aspose.imaging.PointF---boolean-) | Inizializza una nuova istanza della classe `CurveShape`. |
| [CurveShape(PointF[] points, float tension)](#CurveShape-com.aspose.imaging.PointF---float-) | Inizializza una nuova istanza della classe `CurveShape`. |
| [CurveShape(PointF[] points, float tension, boolean isClosed)](#CurveShape-com.aspose.imaging.PointF---float-boolean-) | Inizializza una nuova istanza della classe `CurveShape`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTension()](#getTension--) | Ottiene o imposta la tensione della curva. |
| [setTension(float value)](#setTension-float-) | Ottiene o imposta la tensione della curva. |
| [getBounds()](#getBounds--) | Ottiene i limiti dell'oggetto. |
| [getCenter()](#getCenter--) | Ottiene il centro della forma. |
| [getSegments()](#getSegments--) | Ottiene i segmenti della forma. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Ottiene i limiti dell'oggetto. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Ottiene i limiti dell'oggetto. |
| [equals(Object o)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
| [hashCode()](#hashCode--) | Ottieni il codice hash dell'oggetto corrente. |
### CurveShape() {#CurveShape--}
```
public CurveShape()
```


Inizializza una nuova istanza della classe `CurveShape`.

### CurveShape(PointF[] points) {#CurveShape-com.aspose.imaging.PointF---}
```
public CurveShape(PointF[] points)
```


Inizializza una nuova istanza della classe `CurveShape`. Viene utilizzata la tensione predefinita di 0.5.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | L'array dei punti. |

### CurveShape(PointF[] points, boolean isClosed) {#CurveShape-com.aspose.imaging.PointF---boolean-}
```
public CurveShape(PointF[] points, boolean isClosed)
```


Inizializza una nuova istanza della classe `CurveShape`. Viene utilizzata la tensione predefinita di 0.5.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | L'array dei punti. |
| isClosed | boolean |  |

### CurveShape(PointF[] points, float tension) {#CurveShape-com.aspose.imaging.PointF---float-}
```
public CurveShape(PointF[] points, float tension)
```


Inizializza una nuova istanza della classe `CurveShape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | L'array dei punti. |
| tensione | float | La tensione della curva. |

### CurveShape(PointF[] points, float tension, boolean isClosed) {#CurveShape-com.aspose.imaging.PointF---float-boolean-}
```
public CurveShape(PointF[] points, float tension, boolean isClosed)
```


Inizializza una nuova istanza della classe `CurveShape`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | L'array dei punti. |
| tensione | float | La tensione della curva. |
| isClosed | boolean | se impostato su `true` la curva è chiusa. |

### getTension() {#getTension--}
```
public float getTension()
```


Ottiene o imposta la tensione della curva.

Valore: La tensione della curva.

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Ottiene o imposta la tensione della curva.

Valore: La tensione della curva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

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
