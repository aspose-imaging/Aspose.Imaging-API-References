---
title: "BezierSegment"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il segmento Bézier che va da un punto al punto successivo utilizzando due punti di controllo."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.shapesegments/beziersegment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ShapeSegment](../../com.aspose.imaging/shapesegment), [com.aspose.imaging.shapesegments.LineSegment](../../com.aspose.imaging.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

Il segmento Bézier che va da un punto al punto successivo utilizzando due punti di controllo.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Inizializza una nuova istanza della classe `BezierSegment`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFirstControlPoint()](#getFirstControlPoint--) | Ottiene il primo punto di controllo di una spline bezier. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Ottiene il secondo punto di controllo di una spline bezier. |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
| [hashCode()](#hashCode--) | Ottieni il codice hash dell'oggetto corrente. |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


Inizializza una nuova istanza della classe `BezierSegment`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.imaging/pointf) | Il punto di inizio. |
| firstControlPoint | [PointF](../../com.aspose.imaging/pointf) | Il primo punto di controllo. |
| secondControlPoint | [PointF](../../com.aspose.imaging/pointf) | Il secondo punto di controllo. |
| endPoint | [PointF](../../com.aspose.imaging/pointf) | Il punto finale. |

### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Ottiene il primo punto di controllo di una spline bezier.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Ottiene il secondo punto di controllo di una spline bezier.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The second control point.
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
