---
title: Pen Class
type: docs
weight: 6670
url: /python-net/aspose.imaging/pen/
---

Defines an object used to draw lines, curves and figures.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Pen

**Inheritance:** TransparencySupporter

**Aspose.Imaging Version:** 23.6

The Pen type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [Pen(color)](#Pen_color_0) | Initializes a new instance of the Pen class |
| [Pen(color, width)](#Pen_color_width_1) | Initializes a new instance of the Pen class |
| [Pen(brush)](#Pen_brush_2) | Initializes a new instance of the Pen class |
| [Pen(brush, width)](#Pen_brush_width_3) | Initializes a new instance of the Pen class |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| opacity | float | r/w | Gets or sets the object's opacity. The value should be between 0 and 1. Value of 0 means that object is fully visible, value of 1 means the object is fully opaque. |
| width | float | r/w | Gets or sets the width of this [Pen](/imaging/python-net/aspose.imaging/pen/), in units of the Graphics object used for drawing. |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap) | r/w | Gets or sets the cap style used at the beginning of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap) | r/w | Gets or sets the cap style used at the end of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap) | r/w | Gets or sets the cap style used at the end of the dashes that make up dashed lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| line_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin) | r/w | Gets or sets the join style for the ends of two consecutive lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| custom_start_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap) | r/w | Gets or sets a custom cap to use at the beginning of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| custom_end_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap) | r/w | Gets or sets a custom cap to use at the end of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| miter_limit | float | r/w | Gets or sets the limit of the thickness of the join on a mitered corner. |
| alignment | [PenAlignment](/imaging/python-net/aspose.imaging/penalignment) | r/w | Gets or sets the alignment for this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix) | r/w | Gets or sets a copy of the geometric transformation for this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| pen_type | [PenType](/imaging/python-net/aspose.imaging/pentype) | r | Gets the style of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets the color of this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) | r/w | Gets or sets the [brush](/imaging/python-net/aspose.imaging/pen/) that determines attributes of this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_style | [DashStyle](/imaging/python-net/aspose.imaging/dashstyle) | r/w | Gets or sets the style used for dashed lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_offset | float | r/w | Gets or sets the distance from the start of a line to the beginning of a dash pattern. |
| dash_pattern | float | r/w | Gets or sets an array of custom dashes and spaces. |
| compound_array | float | r/w | Gets or sets an array of values that specifies a compound pen. A compound pen draws a compound line made up of parallel lines and spaces. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [multiply_transform(matrix)](#multiply_transform_matrix_4) | Multiplies the transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_5) | Multiplies the transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_6) | Translates the local geometric transformation by the specified dimensions. This method prepends the translation to the transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_7) | Translates the local geometric transformation by the specified dimensions in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_8) | Scales the local geometric transformation by the specified factors. This method prepends the scaling matrix to the transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_9) | Scales the local geometric transformation by the specified factors in the specified order. |
| [rotate_transform(angle)](#rotate_transform_angle_10) | Rotates the local geometric transformation by the specified angle. This method prepends the rotation to the transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_11) | Rotates the local geometric transformation by the specified angle in the specified order. |
| [create_with_color(color)](#create_with_color_color_12) | Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified color. |
| [create_with_color_width(color, width)](#create_with_color_width_color_width_13) | Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [color](/imaging/python-net/aspose.imaging/pen/) and [width](/imaging/python-net/aspose.imaging/pen/) properties. |
| [create_with_brush(brush)](#create_with_brush_brush_14) | Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [brush](/imaging/python-net/aspose.imaging/pen/). |
| [create_with_brush_width(brush, width)](#create_with_brush_width_brush_width_15) | Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [brush](/imaging/python-net/aspose.imaging/pen/) and [width](/imaging/python-net/aspose.imaging/pen/). |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_16) | Sets the values that determine the style of cap used to end lines drawn by this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| reset_transform() | Resets the geometric transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) to identity. |

### Pen(color) {#Pen_color_0}


```
 Pen(color) 
```

Initializes a new instance of the Pen class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color) |  |

### Pen(color, width) {#Pen_color_width_1}


```
 Pen(color, width) 
```

Initializes a new instance of the Pen class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color) |  |
| width | float |  |

### Pen(brush) {#Pen_brush_2}


```
 Pen(brush) 
```

Initializes a new instance of the Pen class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) |  |

### Pen(brush, width) {#Pen_brush_width_3}


```
 Pen(brush, width) 
```

Initializes a new instance of the Pen class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) |  |
| width | float |  |

### multiply_transform(matrix) {#multiply_transform_matrix_4}


```
 multiply_transform(matrix) 
```

Multiplies the transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) object by which to multiply the transformation matrix. |

### multiply_transform(matrix, order) {#multiply_transform_matrix_order_5}


```
 multiply_transform(matrix, order) 
```

Multiplies the transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to multiply the transformation matrix. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | The order in which to perform the multiplication operation. |

### translate_transform(dx, dy) {#translate_transform_dx_dy_6}


```
 translate_transform(dx, dy) 
```

Translates the local geometric transformation by the specified dimensions. This method prepends the translation to the transformation.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_7}


```
 translate_transform(dx, dy, order) 
```

Translates the local geometric transformation by the specified dimensions in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | The order (prepend or append) in which to apply the translation. |

### scale_transform(sx, sy) {#scale_transform_sx_sy_8}


```
 scale_transform(sx, sy) 
```

Scales the local geometric transformation by the specified factors. This method prepends the scaling matrix to the transformation.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The factor by which to scale the transformation in the x-axis direction. |
| sy | float | The factor by which to scale the transformation in the y-axis direction. |

### scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_9}


```
 scale_transform(sx, sy, order) 
```

Scales the local geometric transformation by the specified factors in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The factor by which to scale the transformation in the x-axis direction. |
| sy | float | The factor by which to scale the transformation in the y-axis direction. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the scaling matrix. |

### rotate_transform(angle) {#rotate_transform_angle_10}


```
 rotate_transform(angle) 
```

Rotates the local geometric transformation by the specified angle. This method prepends the rotation to the transformation.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |

### rotate_transform(angle, order) {#rotate_transform_angle_order_11}


```
 rotate_transform(angle, order) 
```

Rotates the local geometric transformation by the specified angle in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the rotation matrix. |

### create_with_color(color)  [static] {#create_with_color_color_12}


```
 create_with_color(color) 
```

Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color) | A [color](/imaging/python-net/aspose.imaging/pen/) structure that indicates the color of this [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen) |  |


### create_with_color_width(color, width)  [static] {#create_with_color_width_color_width_13}


```
 create_with_color_width(color, width) 
```

Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [color](/imaging/python-net/aspose.imaging/pen/) and [width](/imaging/python-net/aspose.imaging/pen/) properties.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color) | A [color](/imaging/python-net/aspose.imaging/pen/) structure that indicates the color of this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | A value indicating the width of this [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen) |  |


### create_with_brush(brush)  [static] {#create_with_brush_brush_14}


```
 create_with_brush(brush) 
```

Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [brush](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) | A [brush](/imaging/python-net/aspose.imaging/pen/) that determines the fill properties of this [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen) |  |


### create_with_brush_width(brush, width)  [static] {#create_with_brush_width_brush_width_15}


```
 create_with_brush_width(brush, width) 
```

Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [brush](/imaging/python-net/aspose.imaging/pen/) and [width](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush) | A [brush](/imaging/python-net/aspose.imaging/pen/) that determines the characteristics of this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | The width of the new [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen) |  |


### set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_16}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Sets the values that determine the style of cap used to end lines drawn by this [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap) | A [LineCap](/imaging/python-net/aspose.imaging/linecap/) that represents the cap style to use at the beginning of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap) | A [LineCap](/imaging/python-net/aspose.imaging/linecap/) that represents the cap style to use at the end of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap) | A [LineCap](/imaging/python-net/aspose.imaging/linecap/) that represents the cap style to use at the beginning or end of dashed lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |

