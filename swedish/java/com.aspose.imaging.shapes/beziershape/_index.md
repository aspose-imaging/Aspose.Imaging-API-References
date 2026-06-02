---
title: "BezierShape"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en bezier-spline."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.shapes/beziershape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class BezierShape extends PolygonShape
```

Representerar en bezier-spline.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BezierShape()](#BezierShape--) | Initierar en ny instans av klassen `BezierShape`. |
| [BezierShape(PointF[] points)](#BezierShape-com.aspose.imaging.PointF---) | Initierar en ny instans av klassen `BezierShape`. |
| [BezierShape(PointF[] points, boolean isClosed)](#BezierShape-com.aspose.imaging.PointF---boolean-) | Initierar en ny instans av klassen `BezierShape`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar objektets gränser. |
| [getCenter()](#getCenter--) | Hämtar formens centrum. |
| [getSegments()](#getSegments--) | Hämtar formens segment. |
| [hasSegments()](#hasSegments--) | Hämtar ett värde som indikerar om formen har segment. |
| [getEndPoint()](#getEndPoint--) | Hämtar slutpunkten för formen. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Hämtar objektets gränser. |
### BezierShape() {#BezierShape--}
```
public BezierShape()
```


Initierar en ny instans av klassen `BezierShape`.

### BezierShape(PointF[] points) {#BezierShape-com.aspose.imaging.PointF---}
```
public BezierShape(PointF[] points)
```


Initierar en ny instans av klassen `BezierShape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Punktarrayen. |

### BezierShape(PointF[] points, boolean isClosed) {#BezierShape-com.aspose.imaging.PointF---boolean-}
```
public BezierShape(PointF[] points, boolean isClosed)
```


Initierar en ny instans av klassen `BezierShape`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Punktarrayen. |
| isClosed | boolean | Om den är satt till `true` är bezier-splinen sluten. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Hämtar objektets gränser.

Värde: Objektets gränser.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Hämtar formens centrum.

Värde: Formens centrum.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Hämtar formens segment.

Värde: Formens segment.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Hämtar ett värde som indikerar om formen har segment.

Värde: `True` om formen har segment; annars `false`.

**Returns:**
boolean
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Hämtar slutpunkten för formen.

Värde: Formens slutpunkt.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Hämtar objektets gränser.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Matriser att tillämpa innan gränser beräknas. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
