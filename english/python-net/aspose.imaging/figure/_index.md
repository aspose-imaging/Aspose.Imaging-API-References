---
title: Figure Class
type: docs
weight: 4690
url: /python-net/aspose.imaging/figure/
---

The figure. A container for shapes.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Figure

**Inheritance:** ObjectWithBounds

**Aspose.Imaging Version:** 23.6

The Figure type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [Figure()](#Figure__0) | Initializes a new [Figure](/imaging/python-net/aspose.imaging/figure/) instance.<br/>            A constructor required for a JSON deserialization. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | r | Gets or sets the object's bounds. |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape) | r | Gets or sets the figure shapes. |
| is_closed | bool | r/w | Gets or sets a value indicating whether this figure is closed. A closed figure will make a difference only in case where<br/>            the first and the last figure's shapes are continuous shapes. In such case the first point of the first shape will be<br/>            connected by a straight line from the last point of the last shape. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment) | r | Gets the whole figure segments. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Gets the object's bounds. |
| [transform(transform)](#transform_transform_3) | Applies the specified transformation to the shape. |
| [add_shape(shape)](#add_shape_shape_4) | Adds a shape to the figure. |
| [add_shapes(shapes)](#add_shapes_shapes_5) | Adds a range of shapes to the figure. |
| [remove_shape(shape)](#remove_shape_shape_6) | Removes a shape from the figure. |
| [remove_shapes(shapes)](#remove_shapes_shapes_7) | Removes a range of shapes from the figure. |
| reverse() | Reverses this figure shapes order and shapes point order. |

### Figure() {#Figure__0}


```
 Figure() 
```

Initializes a new [Figure](/imaging/python-net/aspose.imaging/figure/) instance.<br/>            A constructor required for a JSON deserialization.

### get_bounds(matrix) {#get_bounds_matrix_1}


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


### get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The transformation to apply. |

### add_shape(shape) {#add_shape_shape_4}


```
 add_shape(shape) 
```

Adds a shape to the figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape) | The shape to add. |

### add_shapes(shapes) {#add_shapes_shapes_5}


```
 add_shapes(shapes) 
```

Adds a range of shapes to the figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape) | The shapes to add. |

### remove_shape(shape) {#remove_shape_shape_6}


```
 remove_shape(shape) 
```

Removes a shape from the figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape) | The shape to remove. |

### remove_shapes(shapes) {#remove_shapes_shapes_7}


```
 remove_shapes(shapes) 
```

Removes a range of shapes from the figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape) | The shapes range to remove. |

