---
title: BezierShape Class
type: docs
weight: 20
url: /python-net/aspose.imaging.shapes/beziershape/
---

Represents a bezier spline.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.Imaging Version:** 23.6

The BezierShape type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [BezierShape()](#BezierShape__0) | Initializes a new instance of the [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) class. |
| [BezierShape(points)](#BezierShape_points_1) | Initializes a new instance of the [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) class. |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_2) | Initializes a new instance of the [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | r | Gets the object's bounds. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the shape's center. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment) | r | Gets the shape segments. |
| has_segments | bool | r | Gets a value indicating whether shape has segments. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | r/w | Gets or sets the curve points. |
| is_closed | bool | r/w | Gets or sets a value indicating whether shape is closed. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the starting shape point. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the ending shape point. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Gets the object's bounds. |
| [transform(transform)](#transform_transform_5) | Applies the specified transformation to the shape. |
| reverse() | Reverses the order of points for this shape. |

### BezierShape() {#BezierShape__0}


```
 BezierShape() 
```

Initializes a new instance of the [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) class.

### BezierShape(points) {#BezierShape_points_1}


```
 BezierShape(points) 
```

Initializes a new instance of the [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | The points array. |

### BezierShape(points, is_closed) {#BezierShape_points_is_closed_2}


```
 BezierShape(points, is_closed) 
```

Initializes a new instance of the [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | The points array. |
| is_closed | bool | If set to <c>true</c> the bezier spline is closed. |

### get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Gets the object's bounds.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The matrix to apply before bounds will be calculated. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The estimated object's bounds. |


### get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Gets the object's bounds.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The matrix to apply before bounds will be calculated. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen) | The pen to use for object. This can influence the object's bounds size. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The estimated object's bounds. |


### transform(transform) {#transform_transform_5}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The transformation to apply. |

