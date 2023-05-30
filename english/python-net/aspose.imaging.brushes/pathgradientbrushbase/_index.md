---
title: PathGradientBrushBase Class
type: docs
weight: 60
url: /python-net/aspose.imaging.brushes/pathgradientbrushbase/
---

Represents a [Brush](/imaging/python-net/aspose.imaging/brush/) with base path gradient functionality.

**Namespace:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Class Name:** aspose.imaging.brushes.PathGradientBrushBase

**Assembly:**  Aspose.Imaging Version: 23.5.6

The PathGradientBrushBase type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|opacity|  |
|wrap_mode|Gets or sets a [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration that indicates the wrap mode for this [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/).|
|transform|Gets or sets a copy [Matrix](/imaging/python-net/aspose.imaging/matrix/) that defines a local geometric transform for this [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/).|
|is_transform_changed|Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or<br/>            calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+.|
|path_points|Gets the path points this brush was build upon.|
|graphics_path|Gets the graphics path this brush was build upon.|
|center_point|Gets or sets the center point of the path gradient.|
|focus_scales|Gets or sets the focus point for the gradient falloff.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|multiply_transform(matrix)|Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/).|
|multiply_transform(matrix, order)|Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order.|
|translate_transform(dx, dy)|Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.|
|translate_transform(dx, dy, order)|Translates the local geometric transform by the specified dimensions in the specified order.|
|scale_transform(sx, sy)|Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.|
|scale_transform(sx, sy, order)|Scales the local geometric transform by the specified amounts in the specified order.|
|rotate_transform(angle)|Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.|
|rotate_transform(angle, order)|Rotates the local geometric transform by the specified amount in the specified order.|
|deep_clone()|  |
|reset_transform()|Resets the [transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) property to identity.|
