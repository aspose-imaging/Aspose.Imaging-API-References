---
title: "BezierShape"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa una spline de Bézier."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.shapes/beziershape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class BezierShape extends PolygonShape
```

Representa una spline de Bézier.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BezierShape()](#BezierShape--) | Inicializa una nueva instancia de la clase `BezierShape`. |
| [BezierShape(PointF[] points)](#BezierShape-com.aspose.imaging.PointF---) | Inicializa una nueva instancia de la clase `BezierShape`. |
| [BezierShape(PointF[] points, boolean isClosed)](#BezierShape-com.aspose.imaging.PointF---boolean-) | Inicializa una nueva instancia de la clase `BezierShape`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBounds()](#getBounds--) | Obtiene los límites del objeto. |
| [getCenter()](#getCenter--) | Obtiene el centro de la forma. |
| [getSegments()](#getSegments--) | Obtiene los segmentos de la forma. |
| [hasSegments()](#hasSegments--) | Obtiene un valor que indica si la forma tiene segmentos. |
| [getEndPoint()](#getEndPoint--) | Obtiene el punto final de la forma. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Obtiene los límites del objeto. |
### BezierShape() {#BezierShape--}
```
public BezierShape()
```


Inicializa una nueva instancia de la clase `BezierShape`.

### BezierShape(PointF[] points) {#BezierShape-com.aspose.imaging.PointF---}
```
public BezierShape(PointF[] points)
```


Inicializa una nueva instancia de la clase `BezierShape`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | La matriz de puntos. |

### BezierShape(PointF[] points, boolean isClosed) {#BezierShape-com.aspose.imaging.PointF---boolean-}
```
public BezierShape(PointF[] points, boolean isClosed)
```


Inicializa una nueva instancia de la clase `BezierShape`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | La matriz de puntos. |
| isClosed | boolean | Si se establece en `true`, la spline de Bézier está cerrada. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Obtiene los límites del objeto.

Valor: Los límites del objeto.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Obtiene el centro de la forma.

Valor: El centro de la forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Obtiene los segmentos de la forma.

Valor: Los segmentos de la forma.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Obtiene un valor que indica si la forma tiene segmentos.

Valor: `True` si la forma tiene segmentos; de lo contrario, `false`.

**Returns:**
boolean
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Obtiene el punto final de la forma.

Valor: El punto final de la forma.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Obtiene los límites del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | La matriz a aplicar antes de que se calculen los límites. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
