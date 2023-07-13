---
title: TextShape Class
type: docs
weight: 90
url: /python-net/aspose.imaging.shapes/textshape/
---

Represents a text shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.Imaging Version:** 23.6

The TextShape type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [TextShape()](#TextShape__0) | Initializes a new instance of the [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/) class. |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_1) | Initializes a new instance of the [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/) class. |
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
| text | string | r/w | Gets or sets the drawn text. |
| font | [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font) | r/w | Gets or sets the font used to draw the text. |
| text_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat) | r/w | Gets or sets the text format. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_2) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_3) | Gets the object's bounds. |
| [transform(transform)](#transform_transform_4) | Applies the specified transformation to the shape. |

### TextShape() {#TextShape__0}


```
 TextShape() 
```

Initializes a new instance of the [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/) class.

### TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_1}


```
 TextShape(text, rectangle, font, string_format) 
```

Initializes a new instance of the [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| text | string | The text to draw. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef) | The text rectangle. |
| font | [Font](/imaging/python-net/aspose.imaging.xmp.types.complex.font/font) | The font to use. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat) | The string format. |

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

