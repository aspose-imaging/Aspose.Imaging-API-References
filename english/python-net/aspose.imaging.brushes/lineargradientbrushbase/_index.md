---
title: LinearGradientBrushBase Class
type: docs
weight: 30
url: /python-net/aspose.imaging.brushes/lineargradientbrushbase/
---

Represents a [Brush](/imaging/python-net/aspose.imaging/brush/) with gradient capabilities and appropriate properties.

**Namespace:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Class Name:** aspose.imaging.brushes.LinearGradientBrushBase

**Assembly:**  Aspose.Imaging Version: 23.5.6

The LinearGradientBrushBase type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|opacity|  |
|wrap_mode|Gets or sets a [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration that indicates the wrap mode for this [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/).|
|transform|Gets or sets a copy [Matrix](/imaging/python-net/aspose.imaging/matrix/) that defines a local geometric transform for this [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/).|
|is_transform_changed|Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or<br/>            calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+.|
|rectangle|Gets or sets a rectangular region that defines the starting and ending points of the gradient.|
|angle|Gets or sets the gradient angle.|
|is_angle_scalable|Gets or sets a value indicating whether [angle](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/) is changed during trasnformations with this [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/).|
|gamma_correction|Gets or sets a value indicating whether gamma correction is enabled for this [LinearGradientBrushBase](/imaging/python-net/aspose.imaging.brushes/lineargradientbrushbase/).|
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
