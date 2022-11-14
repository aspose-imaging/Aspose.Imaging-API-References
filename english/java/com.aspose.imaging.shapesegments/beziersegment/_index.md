---
title: BezierSegment
second_title: Aspose.Imaging for Java API Reference
description: The bezier segment going from one point to the next point and using two control points.
type: docs
weight: 10
url: /java/com.aspose.imaging.shapesegments/beziersegment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ShapeSegment](../../com.aspose.imaging/shapesegment), [com.aspose.imaging.shapesegments.LineSegment](../../com.aspose.imaging.shapesegments/linesegment)
```
public final class BezierSegment extends LineSegment
```

The bezier segment going from one point to the next point and using two control points.
## Constructors

| Constructor | Description |
| --- | --- |
| [BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)](#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Initializes a new instance of the `BezierSegment` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFirstControlPoint()](#getFirstControlPoint--) | Gets the first control point of a bezier spline. |
| [getSecondControlPoint()](#getSecondControlPoint--) | Gets the second control point of a bezier spline. |
### BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint) {#BezierSegment-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public BezierSegment(PointF startPoint, PointF firstControlPoint, PointF secondControlPoint, PointF endPoint)
```


Initializes a new instance of the `BezierSegment` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startPoint | [PointF](../../com.aspose.imaging/pointf) | The start point. |
| firstControlPoint | [PointF](../../com.aspose.imaging/pointf) | The first control point. |
| secondControlPoint | [PointF](../../com.aspose.imaging/pointf) | The second control point. |
| endPoint | [PointF](../../com.aspose.imaging/pointf) | The end point. |

### getFirstControlPoint() {#getFirstControlPoint--}
```
public PointF getFirstControlPoint()
```


Gets the first control point of a bezier spline.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The first control point.
### getSecondControlPoint() {#getSecondControlPoint--}
```
public PointF getSecondControlPoint()
```


Gets the second control point of a bezier spline.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The second control point.
