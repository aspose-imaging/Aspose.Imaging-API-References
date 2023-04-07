---
title: LinearMulticolorGradientBrush Class
type: docs
weight: 40
url: /python-net/api-reference/aspose.imaging.brushes/linearmulticolorgradientbrush/
---

Represents a [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) with linear gradient defined by multiple colors and appropriate positions. This class cannot be inherited.

**Namespace:** [aspose.imaging.brushes](/imaging/python-net/api-reference/aspose.imaging.brushes/)

**Full Class Name:** aspose.imaging.brushes.LinearMulticolorGradientBrush

**Assembly:**  Aspose.Imaging Version: 23.3.0

The LinearMulticolorGradientBrush type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|LinearMulticolorGradientBrush()|Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/linearmulticolorgradientbrush/) class with default parameters.<br/>            The starting color is black, the ending color is white, the angle is 45 degrees and the rectangle is located in (0,0) with size (1,1).|
|LinearMulticolorGradientBrush(point1, point2)|Initializes a new instance of the LinearMulticolorGradientBrush class|
|LinearMulticolorGradientBrush(point1, point2)|Initializes a new instance of the LinearMulticolorGradientBrush class|
|LinearMulticolorGradientBrush(rect, angle)|Initializes a new instance of the LinearMulticolorGradientBrush class|
|LinearMulticolorGradientBrush(rect, angle)|Initializes a new instance of the LinearMulticolorGradientBrush class|
|LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)|Initializes a new instance of the LinearMulticolorGradientBrush class|
|LinearMulticolorGradientBrush(rect, angle, is_angle_scalable)|Initializes a new instance of the LinearMulticolorGradientBrush class|
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
|is_angle_scalable|Gets or sets a value indicating whether [angle](/imaging/python-net/api-reference/aspose.imaging.brushes/lineargradientbrushbase/) is changed during trasnformations with this [LinearGradientBrushBase](/imaging/python-net/api-reference/aspose.imaging.brushes/lineargradientbrushbase/).|
|gamma_correction|Gets or sets a value indicating whether gamma correction is enabled for this [LinearGradientBrushBase](/imaging/python-net/api-reference/aspose.imaging.brushes/lineargradientbrushbase/).|
|interpolation_colors|Gets or sets a [ColorBlend](/imaging/python-net/api-reference/aspose.imaging/colorblend/) that defines a multicolor linear gradient.|
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
|deep_clone()|  |
|reset_transform()|  |
|create_with_points(point1, point2)|Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/linearmulticolorgradientbrush/) class with the specified points.|
|create_with_points_f(point1, point2)|Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/linearmulticolorgradientbrush/) class with the specified points.|
|create_with_rect(rect, angle)|Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle.|
|create_with_rect_f(rect, angle)|Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle.|
|create_with_rect_angle_scalable(rect, angle, is_angle_scalable)|Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle.|
|create_with_rect_f_angle_scalable(rect, angle, is_angle_scalable)|Initializes a new instance of the [LinearMulticolorGradientBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/linearmulticolorgradientbrush/) class based on a rectangle and an orientation angle.|
