---
title: RectangleProjectedShape
second_title: Aspose.Imaging for Java API Reference
description: Represents a shape which is projected over rectangle turned to a particular orientation.
type: docs
weight: 16
url: /java/com.aspose.imaging.shapes/rectangleprojectedshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)
```
public abstract class RectangleProjectedShape extends Shape
```

Represents a shape which is projected over rectangle turned to a particular orientation. Specified by four points which can be rotated in space maintaining the same edges length and 90 degrees between adjacent edges.
## Constructors

| Constructor | Description |
| --- | --- |
| [RectangleProjectedShape()](#RectangleProjectedShape--) | Initializes a new instance of the `RectangleProjectedShape` class. |
| [RectangleProjectedShape(RectangleF rectangle)](#RectangleProjectedShape-com.aspose.imaging.RectangleF-) | Initializes a new instance of the `RectangleProjectedShape` class. |
## Methods

| Method | Description |
| --- | --- |
| [getLeftTop()](#getLeftTop--) | Gets the left top rectangle point. |
| [getRightTop()](#getRightTop--) | Gets the right top rectangle point. |
| [getLeftBottom()](#getLeftBottom--) | Gets the left bottom rectangle point. |
| [getRightBottom()](#getRightBottom--) | Gets the right bottom rectangle point. |
| [getCenter()](#getCenter--) | Gets the shape's center. |
| [getBounds()](#getBounds--) | Gets the object's bounds. |
| [getRectangleWidth()](#getRectangleWidth--) | Gets the rectangle width. |
| [getRectangleHeight()](#getRectangleHeight--) | Gets the rectangle height. |
| [hasSegments()](#hasSegments--) | Gets a value indicating whether shape has segments. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Gets the object's bounds. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Gets the object's bounds. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Applies the specified transformation to the shape. |
### RectangleProjectedShape() {#RectangleProjectedShape--}
```
public RectangleProjectedShape()
```


Initializes a new instance of the `RectangleProjectedShape` class.

### RectangleProjectedShape(RectangleF rectangle) {#RectangleProjectedShape-com.aspose.imaging.RectangleF-}
```
public RectangleProjectedShape(RectangleF rectangle)
```


Initializes a new instance of the `RectangleProjectedShape` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | The rectangle to initialize from. |

### getLeftTop() {#getLeftTop--}
```
public PointF getLeftTop()
```


Gets the left top rectangle point.

Value: The left top rectangle point.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightTop() {#getRightTop--}
```
public PointF getRightTop()
```


Gets the right top rectangle point.

Value: The right top rectangle point.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getLeftBottom() {#getLeftBottom--}
```
public PointF getLeftBottom()
```


Gets the left bottom rectangle point.

Value: The left bottom rectangle point.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getRightBottom() {#getRightBottom--}
```
public PointF getRightBottom()
```


Gets the right bottom rectangle point.

Value: The right bottom rectangle point.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Gets the shape's center.

Value: The shape's center.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Gets the object's bounds.

Value: The object's bounds.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getRectangleWidth() {#getRectangleWidth--}
```
public double getRectangleWidth()
```


Gets the rectangle width.

Value: The rectangle width.

**Returns:**
double
### getRectangleHeight() {#getRectangleHeight--}
```
public double getRectangleHeight()
```


Gets the rectangle height.

Value: The rectangle height.

**Returns:**
double
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Gets a value indicating whether shape has segments.

Value: `True` if shape has segments; otherwise, `false`.

**Returns:**
boolean
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
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Applies the specified transformation to the shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | The transformation to apply. |

