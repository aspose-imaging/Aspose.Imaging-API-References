---
title: Pen Class
type: docs
weight: 6890
url: /python-net/aspose.imaging/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Pen

**Inheritance:** TransparencySupporter

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [Pen.brush](/imaging/python-net/aspose.imaging/pen/). |
| [Pen(brush, width)](#Pen_brush_width_2) | Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [Pen.brush](/imaging/python-net/aspose.imaging/pen/) and [Pen.width](/imaging/python-net/aspose.imaging/pen/). |
| [Pen(color)](#Pen_color_3) | Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified color. |
| [Pen(color, width)](#Pen_color_width_4) | Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [Pen.color](/imaging/python-net/aspose.imaging/pen/) and [Pen.width](/imaging/python-net/aspose.imaging/pen/) properties. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | r/w | Gets or sets the alignment for this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | r/w | Gets or sets the [Pen.brush](/imaging/python-net/aspose.imaging/pen/) that determines attributes of this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets or sets the color of this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| compound_array | float[] | r/w | Gets or sets an array of values that specifies a compound pen. A compound pen draws a compound line made up of parallel lines and spaces. |
| custom_end_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Gets or sets a custom cap to use at the end of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| custom_start_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Gets or sets a custom cap to use at the beginning of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | r/w | Gets or sets the cap style used at the end of the dashes that make up dashed lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_offset | float | r/w | Gets or sets the distance from the start of a line to the beginning of a dash pattern. |
| dash_pattern | float[] | r/w | Gets or sets an array of custom dashes and spaces. |
| dash_style | [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | r/w | Gets or sets the style used for dashed lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Gets or sets the cap style used at the end of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| line_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Gets or sets the join style for the ends of two consecutive lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| miter_limit | float | r/w | Gets or sets the limit of the thickness of the join on a mitered corner. |
| opacity | float | r/w | Gets or sets the object's opacity. The value should be between 0 and 1. Value of 0 means that object is fully visible, value of 1 means the object is fully opaque. |
| pen_type | [PenType](/imaging/python-net/aspose.imaging/pentype/) | r | Gets the style of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Gets or sets the cap style used at the beginning of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Gets or sets a copy of the geometric transformation for this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | r/w | Gets or sets the width of this [Pen](/imaging/python-net/aspose.imaging/pen/), in units of the Graphics object used for drawing. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_brush(brush)](#create_with_brush_brush_1) | Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [Pen.brush](/imaging/python-net/aspose.imaging/pen/). |
| [create_with_brush_width(brush, width)](#create_with_brush_width_brush_width_2) | Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [Pen.brush](/imaging/python-net/aspose.imaging/pen/) and [Pen.width](/imaging/python-net/aspose.imaging/pen/). |
| [create_with_color(color)](#create_with_color_color_3) | Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified color. |
| [create_with_color_width(color, width)](#create_with_color_width_color_width_4) | Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [Pen.color](/imaging/python-net/aspose.imaging/pen/) and [Pen.width](/imaging/python-net/aspose.imaging/pen/) properties. |
| [multiply_transform(matrix)](#multiply_transform_matrix_5) | Multiplies the transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_6) | Multiplies the transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order. |
| reset_transform() | Resets the geometric transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) to identity. |
| [rotate_transform(angle)](#rotate_transform_angle_7) | Rotates the local geometric transformation by the specified angle. This method prepends the rotation to the transformation. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_8) | Rotates the local geometric transformation by the specified angle in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_9) | Scales the local geometric transformation by the specified factors. This method prepends the scaling matrix to the transformation. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_10) | Scales the local geometric transformation by the specified factors in the specified order. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_11) | Sets the values that determine the style of cap used to end lines drawn by this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Translates the local geometric transformation by the specified dimensions. This method prepends the translation to the transformation. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Translates the local geometric transformation by the specified dimensions in the specified order. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [Pen.brush](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | A [Pen.brush](/imaging/python-net/aspose.imaging/pen/) that determines the fill properties of this [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [Pen.brush](/imaging/python-net/aspose.imaging/pen/) and [Pen.width](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | A [Pen.brush](/imaging/python-net/aspose.imaging/pen/) that determines the characteristics of this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | The width of the new [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | A [Pen.color](/imaging/python-net/aspose.imaging/pen/) structure that indicates the color of this [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [Pen.color](/imaging/python-net/aspose.imaging/pen/) and [Pen.width](/imaging/python-net/aspose.imaging/pen/) properties.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | A [Pen.color](/imaging/python-net/aspose.imaging/pen/) structure that indicates the color of this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | A value indicating the width of this [Pen](/imaging/python-net/aspose.imaging/pen/). |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: create_with_brush(brush)  [static] {#create_with_brush_brush_1}


```
 create_with_brush(brush) 
```

Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [Pen.brush](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | A [Pen.brush](/imaging/python-net/aspose.imaging/pen/) that determines the fill properties of this [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_brush_width(brush, width)  [static] {#create_with_brush_width_brush_width_2}


```
 create_with_brush_width(brush, width) 
```

Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [Pen.brush](/imaging/python-net/aspose.imaging/pen/) and [Pen.width](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | A [Pen.brush](/imaging/python-net/aspose.imaging/pen/) that determines the characteristics of this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | The width of the new [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color(color)  [static] {#create_with_color_color_3}


```
 create_with_color(color) 
```

Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | A [Pen.color](/imaging/python-net/aspose.imaging/pen/) structure that indicates the color of this [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color_width(color, width)  [static] {#create_with_color_width_color_width_4}


```
 create_with_color_width(color, width) 
```

Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [Pen.color](/imaging/python-net/aspose.imaging/pen/) and [Pen.width](/imaging/python-net/aspose.imaging/pen/) properties.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | A [Pen.color](/imaging/python-net/aspose.imaging/pen/) structure that indicates the color of this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | A value indicating the width of this [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Type | Description |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_5}


```
 multiply_transform(matrix) 
```

Multiplies the transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) object by which to multiply the transformation matrix. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_6}


```
 multiply_transform(matrix, order) 
```

Multiplies the transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to multiply the transformation matrix. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | The order in which to perform the multiplication operation. |

### Method: rotate_transform(angle) {#rotate_transform_angle_7}


```
 rotate_transform(angle) 
```

Rotates the local geometric transformation by the specified angle. This method prepends the rotation to the transformation.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_8}


```
 rotate_transform(angle, order) 
```

Rotates the local geometric transformation by the specified angle in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the rotation matrix. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_9}


```
 scale_transform(sx, sy) 
```

Scales the local geometric transformation by the specified factors. This method prepends the scaling matrix to the transformation.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The factor by which to scale the transformation in the x-axis direction. |
| sy | float | The factor by which to scale the transformation in the y-axis direction. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_10}


```
 scale_transform(sx, sy, order) 
```

Scales the local geometric transformation by the specified factors in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The factor by which to scale the transformation in the x-axis direction. |
| sy | float | The factor by which to scale the transformation in the y-axis direction. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the scaling matrix. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_11}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Sets the values that determine the style of cap used to end lines drawn by this [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | A [LineCap](/imaging/python-net/aspose.imaging/linecap/) that represents the cap style to use at the beginning of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | A [LineCap](/imaging/python-net/aspose.imaging/linecap/) that represents the cap style to use at the end of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | A [LineCap](/imaging/python-net/aspose.imaging/linecap/) that represents the cap style to use at the beginning or end of dashed lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Translates the local geometric transformation by the specified dimensions. This method prepends the translation to the transformation.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Translates the local geometric transformation by the specified dimensions in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | The order (prepend or append) in which to apply the translation. |

## **Examples**
### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Create an instance of BmpOptions and set its various properties
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
# Second Boolean parameter determines if the file to be created IsTemporal or not
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Create an instance of Image at specified Path
with Image.create(bmpOptions, 500, 500) as image:
	# Create an instance of Graphics and initialize it with Image object
	graphics = Graphics(image)
	# Clear the Graphics surface with White Color
	graphics.clear(Color.white)
	#Create an instance of Pen with color Red and width 5
	pen = Pen(Color.red, 5.0);
	# Create an instance of HatchBrush and set its properties
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Create an instance of Pen
	# initialize it with HatchBrush object and width
	brusedpen = Pen(brush, 5.0)
	# Draw Rectangles by specifying Pen object
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Draw Rectangles by specifying Pen object
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# save all changes.
	image.save()


```

