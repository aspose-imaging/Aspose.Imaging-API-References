---
title: PolygonShape Class
type: docs
weight: 60
url: /python-net/aspose.imaging.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

**Aspose.Imaging Version:** 23.6

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Initializes a new instance of the [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) class. |
| [PolygonShape(points)](#PolygonShape_points_2) | Initializes a new instance of the [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) class. |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Initializes a new instance of the [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | r | Gets the object's bounds. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the shape's center. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the ending shape point. |
| has_segments | bool | r | Gets a value indicating whether shape has segments. |
| is_closed | bool | r/w | Gets or sets a value indicating whether shape is closed. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | r/w | Gets or sets the curve points. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment) | r | Gets the shape segments. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the starting shape point. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Gets the object's bounds. |
| reverse() | Reverses the order of points for this shape. |
| [transform(transform)](#transform_transform_3) | Applies the specified transformation to the shape. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Initializes a new instance of the [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) class.

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Initializes a new instance of the [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | The points array. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Initializes a new instance of the [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | The points array. |
| is_closed | bool | If set to <c>true</c> the polygon is closed. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The transformation to apply. |

