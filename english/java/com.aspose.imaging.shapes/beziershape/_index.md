---
title: BezierShape
second_title: Aspose.Imaging for Java API Reference
description: Represents a bezier spline.
type: docs
weight: 11
url: /java/com.aspose.imaging.shapes/beziershape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.PolygonShape](../../com.aspose.imaging.shapes/polygonshape)
```
public final class BezierShape extends PolygonShape
```

Represents a bezier spline.
## Constructors

| Constructor | Description |
| --- | --- |
| [BezierShape()](#BezierShape--) | Initializes a new instance of the `BezierShape` class. |
| [BezierShape(PointF[] points)](#BezierShape-com.aspose.imaging.PointF---) | Initializes a new instance of the `BezierShape` class. |
| [BezierShape(PointF[] points, boolean isClosed)](#BezierShape-com.aspose.imaging.PointF---boolean-) | Initializes a new instance of the `BezierShape` class. |
## Methods

| Method | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Gets the object's bounds. |
| [getCenter()](#getCenter--) | Gets the shape's center. |
| [getSegments()](#getSegments--) | Gets the shape segments. |
| [hasSegments()](#hasSegments--) | Gets a value indicating whether shape has segments. |
| [getEndPoint()](#getEndPoint--) | Gets the ending shape point. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Gets the object's bounds. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Gets the object's bounds. |
| [equals(Object obj)](#equals-java.lang.Object-) | Check if objects are equal. |
| [hashCode()](#hashCode--) | Get hash code of the current object. |
### BezierShape() {#BezierShape--}
```
public BezierShape()
```


Initializes a new instance of the `BezierShape` class.

### BezierShape(PointF[] points) {#BezierShape-com.aspose.imaging.PointF---}
```
public BezierShape(PointF[] points)
```


Initializes a new instance of the `BezierShape` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | The points array. |

### BezierShape(PointF[] points, boolean isClosed) {#BezierShape-com.aspose.imaging.PointF---boolean-}
```
public BezierShape(PointF[] points, boolean isClosed)
```


Initializes a new instance of the `BezierShape` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | The points array. |
| isClosed | boolean | If set to `true` the bezier spline is closed. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Gets the object's bounds.

Value: The object's bounds.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Gets the shape's center.

Value: The shape's center.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Gets the shape segments.

Value: The shape segments.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Gets a value indicating whether shape has segments.

Value: `True` if shape has segments; otherwise, `false`.

**Returns:**
boolean
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Gets the ending shape point.

Value: The ending shape point.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Gets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The matrix to apply before bounds will be calculated. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Gets the object's bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | The matrix to apply before bounds will be calculated. |
| pen | [Pen](../../com.aspose.imaging/pen) | The pen to use for object. This can influence the object's bounds size. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Check if objects are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The other object. |

**Returns:**
boolean - The equality comparison result.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Get hash code of the current object.

**Returns:**
int - The hash code.
