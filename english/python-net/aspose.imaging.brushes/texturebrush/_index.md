---
title: TextureBrush Class
type: docs
weight: 90
url: /python-net/api-reference/aspose.imaging.brushes/texturebrush/
---

Each property of the [TextureBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/texturebrush/) class is a [Brush](/imaging/python-net/api-reference/aspose.imaging/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Namespace:** [aspose.imaging.brushes](/imaging/python-net/api-reference/aspose.imaging.brushes/)

**Full Class Name:** aspose.imaging.brushes.TextureBrush

**Assembly:**  Aspose.Imaging Version: 23.3.0

The TextureBrush type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|TextureBrush(image)|Initializes a new instance of the TextureBrush class|
|TextureBrush(image, wrap_mode)|Initializes a new instance of the TextureBrush class|
|TextureBrush(image, wrap_mode, destination_rectangle)|Initializes a new instance of the TextureBrush class|
|TextureBrush(image, wrap_mode, destination_rectangle)|Initializes a new instance of the TextureBrush class|
|TextureBrush(image, destination_rectangle)|Initializes a new instance of the TextureBrush class|
|TextureBrush(image, destination_rectangle, image_attributes)|Initializes a new instance of the TextureBrush class|
|TextureBrush(image, destination_rectangle)|Initializes a new instance of the TextureBrush class|
|TextureBrush(image, destination_rectangle, image_attributes)|Initializes a new instance of the TextureBrush class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|opacity|  |
|wrap_mode|Gets or sets a [WrapMode](/imaging/python-net/api-reference/aspose.imaging/wrapmode/) enumeration that indicates the wrap mode for this [TransformBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/transformbrush/).|
|transform|Gets or sets a copy [Matrix](/imaging/python-net/api-reference/aspose.imaging/matrix/) that defines a local geometric transform for this [TransformBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/transformbrush/).|
|is_transform_changed|Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or<br/>            calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+.|
|image|Gets the [Image](/imaging/python-net/api-reference/aspose.imaging/image/) object associated with this [TextureBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/texturebrush/) object.|
|image_attributes|Gets the [image_attributes](/imaging/python-net/api-reference/aspose.imaging.brushes/texturebrush/) associated with this [TextureBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/texturebrush/).|
|image_rectangle|Gets the [Rectangle](/imaging/python-net/api-reference/aspose.imaging/rectangle/) associated with this [TextureBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/texturebrush/).|
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
|deep_clone()|  |
|reset_transform()|Resets the [transform](/imaging/python-net/api-reference/aspose.imaging.brushes/transformbrush/) property to identity.|
|create_with_image_wrap_mode(image, wrap_mode)|Initializes a new instance of the [TextureBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/texturebrush/) class that uses the specified image and wrap mode.|
|create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)|Initializes a new instance of the [TextureBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle.|
|create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)|Initializes a new instance of the [TextureBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle.|
|create_with_image_rect_f(image, destination_rectangle)|Initializes a new instance of the [TextureBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/texturebrush/) class that uses the specified image and bounding rectangle.|
|create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)|Initializes a new instance of the [TextureBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes.|
|create_with_image_rect(image, destination_rectangle)|Initializes a new instance of the [TextureBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/texturebrush/) class that uses the specified image and bounding rectangle.|
|create_with_image_rect_attribs(image, destination_rectangle, image_attributes)|Initializes a new instance of the [TextureBrush](/imaging/python-net/api-reference/aspose.imaging.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes.|
