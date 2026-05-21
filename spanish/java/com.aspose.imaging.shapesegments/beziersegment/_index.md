---
title: "BezierSegment"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El segmento Bézier que va de un punto al siguiente punto y utiliza dos puntos de control."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.shapesegments/beziersegment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ShapeSegment](../../com.aspose.imaging/shapesegment), [com.aspose.imaging.shapesegments.LineSegment](../../com.aspose.imaging.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

El segmento Bézier que va de un punto al siguiente punto y utiliza dos puntos de control.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Inicializa una nueva instancia de la clase `BezierSegment`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFirstControlPoint()](#getFirstControlPoint--) | Obtiene el primer punto de control de una spline bezier. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Obtiene el segundo punto de control de una spline bezier. |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si los objetos son iguales. |
| [hashCode()](#hashCode--) | Obtiene el código hash del objeto actual. |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


Inicializa una nueva instancia de la clase `BezierSegment`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.imaging/pointf) | El punto de inicio. |
| firstControlPoint | [PointF](../../com.aspose.imaging/pointf) | El primer punto de control. |
| secondControlPoint | [PointF](../../com.aspose.imaging/pointf) | El segundo punto de control. |
| endPoint | [PointF](../../com.aspose.imaging/pointf) | El punto final. |

### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Obtiene el primer punto de control de una spline bezier.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Obtiene el segundo punto de control de una spline bezier.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The second control point.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Comprueba si los objetos son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El otro objeto. |

**Returns:**
boolean - El resultado de la comparación de igualdad.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtiene el código hash del objeto actual.

**Returns:**
int - El código hash.
