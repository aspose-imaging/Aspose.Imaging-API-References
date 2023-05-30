---
title: LinearGradientBrush Class
type: docs
weight: 20
url: /python-net/aspose.imaging.brushes/lineargradientbrush/
---

Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) with a linear gradient. This class cannot be inherited.

**Namespace:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Class Name:** aspose.imaging.brushes.LinearGradientBrush

**Assembly:**  Aspose.Imaging Version: 23.5.6

The LinearGradientBrush type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|LinearGradientBrush()|Initializes a new instance of the [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) class with default parameters.<br/>            The starting color is black, the ending color is white, the angle is 45 degrees and the rectangle is located in (0,0) with size (1,1).|
|LinearGradientBrush(point1, point2, color1, color2)|Initializes a new instance of the LinearGradientBrush class|
|LinearGradientBrush(point1, point2, color1, color2)|Initializes a new instance of the LinearGradientBrush class|
|LinearGradientBrush(rect, color1, color2, angle)|Initializes a new instance of the LinearGradientBrush class|
|LinearGradientBrush(rect, color1, color2, angle)|Initializes a new instance of the LinearGradientBrush class|
|LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)|Initializes a new instance of the LinearGradientBrush class|
|LinearGradientBrush(rect, color1, color2, angle, is_angle_scalable)|Initializes a new instance of the LinearGradientBrush class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|opacity|  |
|wrap_mode|  |
|transform|  |
|is_transform_changed|  |
|rectangle|Gets or sets a rectangular region that defines the starting and ending points of the gradient.|
|angle|Gets or sets the gradient angle.|
|is_angle_scalable|Gets or sets a value indicating whether [angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) is changed during trasnformations with this [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/).|
|gamma_correction|Gets or sets a value indicating whether gamma correction is enabled for this [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/).|
|interpolation_colors|Gets or sets a [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) that defines a multicolor linear gradient.|
|linear_colors|Gets or sets the starting and ending colors of the gradient.|
|start_color|Gets or sets the starting gradient color.|
|end_color|Gets or sets the ending gradient color.|
|blend|Gets or sets a [Blend](/imaging/python-net/aspose.imaging/blend/) that specifies positions and factors that define a custom falloff for the gradient.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|multiply_transform(matrix)|  |
|multiply_transform(matrix, order)|  |
|translate_transform(dx, dy)|  |
|translate_transform(dx, dy, order)|  |
|scale_transform(sx, sy)|  |
|scale_transform(sx, sy, order)|  |
|rotate_transform(angle)|  |
|rotate_transform(angle, order)|  |
|set_sigma_bell_shape(focus)|Creates a gradient falloff based on a bell-shaped curve.|
|set_sigma_bell_shape(focus, scale)|Creates a gradient falloff based on a bell-shaped curve.|
|set_blend_triangular_shape(focus)|Creates a linear gradient with a center color and a linear falloff to a single color on both ends.|
|set_blend_triangular_shape(focus, scale)|Creates a linear gradient with a center color and a linear falloff to a single color on both ends.|
|deep_clone()|  |
|reset_transform()|  |
|create_with_points(point1, point2, color1, color2)|Initializes a new instance of the [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) class with the specified points and colors.|
|create_with_points_f(point1, point2, color1, color2)|Initializes a new instance of the [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) class with the specified points and colors.|
|create_with_rect_colors_angle(rect, color1, color2, angle)|Initializes a new instance of the [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) class based on a rectangle, starting and ending colors, and an orientation angle.|
|create_with_rect_f_colors_angle(rect, color1, color2, angle)|Initializes a new instance of the [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) class based on a rectangle, starting and ending colors, and an orientation angle.|
|create_with_rect_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)|Initializes a new instance of the [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) class based on a rectangle, starting and ending colors, and an orientation angle.|
|create_with_rect_f_colors_angle_scalable(rect, color1, color2, angle, is_angle_scalable)|Initializes a new instance of the [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) class based on a rectangle, starting and ending colors, and an orientation angle.|
