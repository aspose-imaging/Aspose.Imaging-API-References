---
title: PathGradientBrush Class
type: docs
weight: 50
url: /python-net/aspose.imaging.brushes/pathgradientbrush/
---

Encapsulates a [Brush](/imaging/python-net/aspose.imaging/brush/) object with a gradient. This class cannot be inherited.

**Namespace:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Class Name:** aspose.imaging.brushes.PathGradientBrush

**Assembly:**  Aspose.Imaging Version: 23.5.6

The PathGradientBrush type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|PathGradientBrush(path_points)|Initializes a new instance of the PathGradientBrush class|
|PathGradientBrush(path_points, wrap_mode)|Initializes a new instance of the PathGradientBrush class|
|PathGradientBrush(path_points)|Initializes a new instance of the PathGradientBrush class|
|PathGradientBrush(path_points, wrap_mode)|Initializes a new instance of the PathGradientBrush class|
|PathGradientBrush(path)|Initializes a new instance of the PathGradientBrush class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|opacity|  |
|wrap_mode|  |
|transform|  |
|is_transform_changed|  |
|path_points|Gets the path points this brush was build upon.|
|graphics_path|Gets the graphics path this brush was build upon.|
|center_point|Gets or sets the center point of the path gradient.|
|focus_scales|Gets or sets the focus point for the gradient falloff.|
|interpolation_colors|Gets or sets a [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) that defines a multicolor linear gradient.|
|center_color|Gets or sets the color at the center of the path gradient.|
|surround_colors|Gets or sets an array of colors that correspond to the points in the path this [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) fills.|
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
|set_sigma_bell_shape(focus)|Creates a gradient brush that changes color starting from the center of the path outward to the path's boundary. The transition from one color to another is based on a bell-shaped curve.|
|set_sigma_bell_shape(focus, scale)|Creates a gradient brush that changes color starting from the center of the path outward to the path's boundary. The transition from one color to another is based on a bell-shaped curve.|
|set_blend_triangular_shape(focus)|Creates a gradient with a center color and a linear falloff to one surrounding color.|
|set_blend_triangular_shape(focus, scale)|Creates a gradient with a center color and a linear falloff to one surrounding color.|
|deep_clone()|  |
|reset_transform()|  |
|create_with_points_f(path_points)|Initializes a new instance of the [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) class with the specified points.|
|create_with_points_f_wrap_mode(path_points, wrap_mode)|Initializes a new instance of the [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) class with the specified points and wrap mode.|
|create_with_points(path_points)|Initializes a new instance of the [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) class with the specified points.|
|create_with_points_wrap_mode(path_points, wrap_mode)|Initializes a new instance of the [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) class with the specified points and wrap mode.|
|create_with_path(path)|Initializes a new instance of the [PathGradientBrush](/imaging/python-net/aspose.imaging.brushes/pathgradientbrush/) class with the specified path.|
