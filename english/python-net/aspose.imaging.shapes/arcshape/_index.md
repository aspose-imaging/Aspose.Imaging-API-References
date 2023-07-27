---
title: ArcShape Class
type: docs
weight: 10
url: /python-net/aspose.imaging.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

**Aspose.Imaging Version:** 23.6

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Initializes a new instance of the [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) class. |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Initializes a new instance of the [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) class. |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Initializes a new instance of the [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | r | Gets the object's bounds. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the shape's center. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the ending shape point. |
| has_segments | bool | r | Gets a value indicating whether shape has segments. |
| is_closed | bool | r/w | Gets or sets a value indicating whether ordered shape is closed. When processing closed ordered shape the starting and ending points have no meaning. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the left bottom rectangle point. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the left top rectangle point. |
| rectangle_height | double | r | Gets the rectangle height. |
| rectangle_width | double | r | Gets the rectangle width. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the right bottom rectangle point. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the right top rectangle point. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment) | r | Gets the shape segments. |
| start_angle | float | r/w | Gets or sets the start angle. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the starting shape point. |
| sweep_angle | float | r/w | Gets or sets the sweep angle. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Gets the object's bounds. |
| reverse() | Reverses the order of points for this shape. |
| [transform(transform)](#transform_transform_3) | Applies the specified transformation to the shape. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Initializes a new instance of the [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) class.

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Initializes a new instance of the [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The rectangle. |
| start_angle | float | The start angle. |
| sweep_angle | float | The sweep angle. |

### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Initializes a new instance of the [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The rectangle. |
| start_angle | float | The start angle. |
| sweep_angle | float | The sweep angle. |
| is_closed | bool | If set to <c>true</c> the arc is closed. The closed arc is actually degenereates to an ellipse. |

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

