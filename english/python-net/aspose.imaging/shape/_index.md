---
title: Shape Class
type: docs
weight: 7040
url: /python-net/aspose.imaging/shape/
---

The shape. A continuous set of points connected using a specific rule.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Shape

**Inheritance:** ObjectWithBounds

**Aspose.Imaging Version:** 23.6

The Shape type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | r | Gets the object's bounds. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf) | r | Gets the shape's center. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment) | r | Gets the shape segments. |
| has_segments | bool | r | Gets a value indicating whether shape has segments. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_0) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_1) | Gets the object's bounds. |
| [transform(transform)](#transform_transform_2) | Applies the specified transformation to the shape. |

### get_bounds(matrix) {#get_bounds_matrix_0}


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


### get_bounds(matrix, pen) {#get_bounds_matrix_pen_1}


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


### transform(transform) {#transform_transform_2}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The transformation to apply. |

