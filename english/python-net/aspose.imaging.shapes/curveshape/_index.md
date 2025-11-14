---
title: CurveShape Class
type: docs
weight: 30
url: /python-net/aspose.imaging.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. |
| [CurveShape(points)](#CurveShape_points_2) | Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. The default tension of 0.5 is used. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. The default tension of 0.5 is used. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Gets the object's bounds. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the shape's center. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the ending shape point. |
| has_segments | bool | r | Gets a value indicating whether shape has segments. |
| is_closed | bool | r/w | Gets or sets a value indicating whether shape is closed. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets the curve points. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Gets the shape segments. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the starting shape point. |
| tension | float | r/w | Gets or sets the curve tension. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_point_fs_closed(points, is_closed)](#create_with_point_fs_closed_points_is_closed_1) | Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. The default tension of 0.5 is used. |
| [create_with_point_fs_tension(points, tension)](#create_with_point_fs_tension_points_tension_2) | Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Gets the object's bounds. |
| reverse() | Reverses the order of points for this shape. |
| [transform(transform)](#transform_transform_5) | Applies the specified transformation to the shape. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class.

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. The default tension of 0.5 is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | The points array. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. The default tension of 0.5 is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | The points array. |
| is_closed | bool | if set to <c>true</c> the curve is closed. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | The points array. |
| tension | float | The curve tension. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | The points array. |
| tension | float | The curve tension. |
| is_closed | bool | if set to <c>true</c> the curve is closed. |

### Method: create_with_point_fs_closed(points, is_closed)  [static] {#create_with_point_fs_closed_points_is_closed_1}


```
 create_with_point_fs_closed(points, is_closed) 
```

Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. The default tension of 0.5 is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | The points array. |
| is_closed | bool | if set to <c>true</c> the curve is closed. |

**Returns**

| Type | Description |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: create_with_point_fs_tension(points, tension)  [static] {#create_with_point_fs_tension_points_tension_2}


```
 create_with_point_fs_tension(points, tension) 
```

Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | The points array. |
| tension | float | The curve tension. |

**Returns**

| Type | Description |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Gets the object's bounds.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The matrix to apply before bounds will be calculated. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The estimated object's bounds. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Gets the object's bounds.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The matrix to apply before bounds will be calculated. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | The pen to use for object. This can influence the object's bounds size. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The estimated object's bounds. |


### Method: transform(transform) {#transform_transform_5}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The transformation to apply. |

