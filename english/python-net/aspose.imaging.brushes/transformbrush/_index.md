---
title: TransformBrush Class
type: docs
weight: 100
url: /python-net/api-reference/aspose.imaging.brushes/transformbrush/
---

A [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) with transform capabilities.

**Namespace:** [aspose.imaging.brushes](/imaging/python-net/api-reference/aspose.imaging.brushes/)

**Full Class Name:** aspose.imaging.brushes.TransformBrush

**Assembly:**  Aspose.Imaging Version: 23.3.0

The TransformBrush type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|opacity|Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque.|
|wrap_mode|Gets or sets a [WrapMode](/imaging/python-net/api-reference/aspose.imaging/wrapmode/) enumeration that indicates the wrap mode for this [TransformBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/transformbrush/).|
|transform|Gets or sets a copy [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) that defines a local geometric transform for this [TransformBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/transformbrush/).|
|is_transform_changed|Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or<br/>            calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|multiply_transform(matrix)|Multiplies the [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/).|
|multiply_transform(matrix, order)|Multiplies the [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) in the specified order.|
|translate_transform(dx, dy)|Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.|
|translate_transform(dx, dy, order)|Translates the local geometric transform by the specified dimensions in the specified order.|
|scale_transform(sx, sy)|Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.|
|scale_transform(sx, sy, order)|Scales the local geometric transform by the specified amounts in the specified order.|
|rotate_transform(angle)|Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.|
|rotate_transform(angle, order)|Rotates the local geometric transform by the specified amount in the specified order.|
|deep_clone()|Creates a new deep clone of the current [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/).|
|reset_transform()|Resets the [transform](/imaging/python-net/api-reference/aspose.imaging.brushes/transformbrush/) property to identity.|
