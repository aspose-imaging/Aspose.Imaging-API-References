---
title: PieShape Class
type: docs
weight: 50
url: /python-net/aspose.imaging.shapes/pieshape/
---

Represents a pie shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.PieShape

**Inheritance:** EllipseShape

**Aspose.Imaging Version:** 23.6

The PieShape type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [PieShape()](#PieShape__0) | Initializes a new instance of the [PieShape](/imaging/python-net/aspose.imaging.shapes/pieshape/) class. |
| [PieShape(rectangle, start_angle, sweep_angle)](#PieShape_rectangle_start_angle_sweep_angle_1) | Initializes a new instance of the [PieShape](/imaging/python-net/aspose.imaging.shapes/pieshape/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | r | Gets the object's bounds. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the shape's center. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment) | r | Gets the shape segments. |
| has_segments | bool | r | Gets a value indicating whether shape has segments. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the left top rectangle point. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the right top rectangle point. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the left bottom rectangle point. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the right bottom rectangle point. |
| rectangle_width | double | r | Gets the rectangle width. |
| rectangle_height | double | r | Gets the rectangle height. |
| start_angle | float | r/w | Gets or sets the start angle. |
| sweep_angle | float | r/w | Gets or sets the sweep angle. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_2) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_3) | Gets the object's bounds. |
| [transform(transform)](#transform_transform_4) | Applies the specified transformation to the shape. |

### PieShape() {#PieShape__0}


```
 PieShape() 
```

Initializes a new instance of the [PieShape](/imaging/python-net/aspose.imaging.shapes/pieshape/) class.

### PieShape(rectangle, start_angle, sweep_angle) {#PieShape_rectangle_start_angle_sweep_angle_1}


```
 PieShape(rectangle, start_angle, sweep_angle) 
```

Initializes a new instance of the [PieShape](/imaging/python-net/aspose.imaging.shapes/pieshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The rectangle. |
| start_angle | float | The start angle. |
| sweep_angle | float | The sweep angle. |

### get_bounds(matrix) {#get_bounds_matrix_2}


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


### get_bounds(matrix, pen) {#get_bounds_matrix_pen_3}


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


### transform(transform) {#transform_transform_4}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The transformation to apply. |

