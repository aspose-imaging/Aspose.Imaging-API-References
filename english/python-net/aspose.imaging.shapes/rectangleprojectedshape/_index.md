---
title: RectangleProjectedShape Class
type: docs
weight: 70
url: /python-net/aspose.imaging.shapes/rectangleprojectedshape/
---

**Summary:** Represents a shape which is projected over rectangle turned to a particular orientation.<br/>            Specified by four points which can be rotated in space maintaining the same edges length and 90 degrees between adjacent edges.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.RectangleProjectedShape

**Inheritance:** Shape

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Gets the object's bounds. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the shape's center. |
| has_segments | bool | r | Gets a value indicating whether shape has segments. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the left bottom rectangle point. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the left top rectangle point. |
| rectangle_height | float | r | Gets the rectangle height. |
| rectangle_width | float | r | Gets the rectangle width. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the right bottom rectangle point. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the right top rectangle point. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Gets the shape segments. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Gets the object's bounds. |
| [transform(transform)](#transform_transform_3) | Applies the specified transformation to the shape. |


### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The transformation to apply. |

