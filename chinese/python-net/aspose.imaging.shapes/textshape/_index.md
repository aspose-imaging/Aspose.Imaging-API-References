---
title: "TextShape 类"
type: docs
weight: 90
url: /zh/python-net/aspose.imaging.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.TextShape

**Inheritance:** RectangleProjectedShape

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [TextShape()](#TextShape__1) | 初始化一个新的 [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/) 类实例。 |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | 初始化一个新的 [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | 获取对象的边界。 |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取形状的中心。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | r/w | 获取或设置用于绘制文本的字体。 |
| has_segments | bool | r | 获取一个值，指示形状是否具有段。 |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取左下矩形点。 |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取左上矩形点。 |
| rectangle_height | float | r | 获取矩形高度。 |
| rectangle_width | float | r | 获取矩形宽度。 |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取右下矩形点。 |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | 获取右上矩形点。 |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | 获取形状的段。 |
| text | string | r/w | 获取或设置已绘制的文本。 |
| text_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r/w | 获取或设置文本格式。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | 获取对象的边界。 |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | 获取对象的边界。 |
| [transform(transform)](#transform_transform_3) | 对形状应用指定的变换。 |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

初始化一个新的 [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/) 类实例。

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

初始化一个新的 [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| text | string | 要绘制的文本。 |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 文本矩形。 |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | 要使用的字体。 |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | 字符串格式。 |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

获取对象的边界。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 在计算边界之前要应用的矩阵。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 估计的对象边界。 |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

获取对象的边界。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 在计算边界之前要应用的矩阵。 |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | 用于对象的笔。这可能会影响对象边界的大小。 |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | 估计的对象边界。 |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

对形状应用指定的变换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | 要应用的变换。 |

