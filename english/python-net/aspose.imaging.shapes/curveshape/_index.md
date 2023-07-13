---
title: CurveShape Class
type: docs
weight: 30
url: /python-net/aspose.imaging.shapes/curveshape/
---

Represents a curved spline shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.Imaging Version:** 23.6

The CurveShape type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [CurveShape()](#CurveShape__0) | Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. |
| [CurveShape(points)](#CurveShape_points_1) | Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. The default tension of 0.5 is used. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_2) | Initializes a new instance of the CurveShape class |
| [CurveShape(points, tension)](#CurveShape_points_tension_3) | Initializes a new instance of the CurveShape class |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_4) | Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. |
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
| tension | float | r/w | Gets or sets the curve tension. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_5) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_6) | Gets the object's bounds. |
| [transform(transform)](#transform_transform_7) | Applies the specified transformation to the shape. |
| reverse() | Reverses the order of points for this shape. |
| [create_with_point_fs_closed(points, is_closed)](#create_with_point_fs_closed_points_is_closed_8) | Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. The default tension of 0.5 is used. |
| [create_with_point_fs_tension(points, tension)](#create_with_point_fs_tension_points_tension_9) | Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. |

### CurveShape() {#CurveShape__0}


```
 CurveShape() 
```

Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class.

### CurveShape(points) {#CurveShape_points_1}


```
 CurveShape(points) 
```

Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. The default tension of 0.5 is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | The points array. |

### CurveShape(points, is_closed) {#CurveShape_points_is_closed_2}


```
 CurveShape(points, is_closed) 
```

Initializes a new instance of the CurveShape class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) |  |
| is_closed | bool |  |

### CurveShape(points, tension) {#CurveShape_points_tension_3}


```
 CurveShape(points, tension) 
```

Initializes a new instance of the CurveShape class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) |  |
| tension | float |  |

### CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_4}


```
 CurveShape(points, tension, is_closed) 
```

Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | The points array. |
| tension | float | The curve tension. |
| is_closed | bool | if set to <c>true</c> the curve is closed. |

### get_bounds(matrix) {#get_bounds_matrix_5}


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


### get_bounds(matrix, pen) {#get_bounds_matrix_pen_6}


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


### transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The transformation to apply. |

### create_with_point_fs_closed(points, is_closed)  [static] {#create_with_point_fs_closed_points_is_closed_8}


```
 create_with_point_fs_closed(points, is_closed) 
```

Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class. The default tension of 0.5 is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | The points array. |
| is_closed | bool | if set to <c>true</c> the curve is closed. |

**Returns**

| Type | Description |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape) |  |


### create_with_point_fs_tension(points, tension)  [static] {#create_with_point_fs_tension_points_tension_9}


```
 create_with_point_fs_tension(points, tension) 
```

Initializes a new instance of the [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf) | The points array. |
| tension | float | The curve tension. |

**Returns**

| Type | Description |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape) |  |


