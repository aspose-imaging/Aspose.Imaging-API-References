---
title: Pen Class
type: docs
weight: 660
url: /python-net/aspose.imaging/pen/
---

Defines an object used to draw lines, curves and figures.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.Pen

**Assembly:**  Aspose.Imaging Version: 23.6.0

The Pen type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|Pen(color)|Initializes a new instance of the Pen class|
|Pen(color, width)|Initializes a new instance of the Pen class|
|Pen(brush)|Initializes a new instance of the Pen class|
|Pen(brush, width)|Initializes a new instance of the Pen class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|opacity|Gets or sets the object's opacity. The value should be between 0 and 1. Value of 0 means that object is fully visible, value of 1 means the object is fully opaque.|
|width|Gets or sets the width of this [Pen](/imaging/python-net/aspose.imaging/pen/), in units of the Graphics object used for drawing.|
|start_cap|Gets or sets the cap style used at the beginning of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|end_cap|Gets or sets the cap style used at the end of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|dash_cap|Gets or sets the cap style used at the end of the dashes that make up dashed lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|line_join|Gets or sets the join style for the ends of two consecutive lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|custom_start_cap|Gets or sets a custom cap to use at the beginning of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|custom_end_cap|Gets or sets a custom cap to use at the end of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|miter_limit|Gets or sets the limit of the thickness of the join on a mitered corner.|
|alignment|Gets or sets the alignment for this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|transform|Gets or sets a copy of the geometric transformation for this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|pen_type|Gets the style of lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|color|Gets or sets the color of this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|brush|Gets or sets the [brush](/imaging/python-net/aspose.imaging/pen/) that determines attributes of this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|dash_style|Gets or sets the style used for dashed lines drawn with this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|dash_offset|Gets or sets the distance from the start of a line to the beginning of a dash pattern.|
|dash_pattern|Gets or sets an array of custom dashes and spaces.|
|compound_array|Gets or sets an array of values that specifies a compound pen. A compound pen draws a compound line made up of parallel lines and spaces.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|multiply_transform(matrix)|Multiplies the transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/).|
|multiply_transform(matrix, order)|Multiplies the transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order.|
|translate_transform(dx, dy)|Translates the local geometric transformation by the specified dimensions. This method prepends the translation to the transformation.|
|translate_transform(dx, dy, order)|Translates the local geometric transformation by the specified dimensions in the specified order.|
|scale_transform(sx, sy)|Scales the local geometric transformation by the specified factors. This method prepends the scaling matrix to the transformation.|
|scale_transform(sx, sy, order)|Scales the local geometric transformation by the specified factors in the specified order.|
|rotate_transform(angle)|Rotates the local geometric transformation by the specified angle. This method prepends the rotation to the transformation.|
|rotate_transform(angle, order)|Rotates the local geometric transformation by the specified angle in the specified order.|
|create_with_color(color)|Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified color.|
|create_with_color_width(color, width)|Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [color](/imaging/python-net/aspose.imaging/pen/) and [width](/imaging/python-net/aspose.imaging/pen/) properties.|
|create_with_brush(brush)|Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [brush](/imaging/python-net/aspose.imaging/pen/).|
|create_with_brush_width(brush, width)|Initializes a new instance of the [Pen](/imaging/python-net/aspose.imaging/pen/) class with the specified [brush](/imaging/python-net/aspose.imaging/pen/) and [width](/imaging/python-net/aspose.imaging/pen/).|
|set_line_cap(start_cap, end_cap, dash_cap)|Sets the values that determine the style of cap used to end lines drawn by this [Pen](/imaging/python-net/aspose.imaging/pen/).|
|reset_transform()|Resets the geometric transformation matrix for this [Pen](/imaging/python-net/aspose.imaging/pen/) to identity.|
