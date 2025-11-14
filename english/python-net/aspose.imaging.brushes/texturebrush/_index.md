---
title: TextureBrush Class
type: docs
weight: 90
url: /python-net/aspose.imaging.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class is a [Brush](/imaging/python-net/aspose.imaging/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.TextureBrush

**Inheritance:** TransformBrush

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image and bounding rectangle. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image and bounding rectangle. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image and wrap mode. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | r | Gets the [Image](/imaging/python-net/aspose.imaging/image/) object associated with this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | r | Gets the [TextureBrush.image_attributes](/imaging/python-net/aspose.imaging.brushes/texturebrush/) associated with this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| image_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Gets the [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) associated with this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/). |
| is_transform_changed | bool | r | Gets a value indicating whether transformations were changed in some way. For example setting the transformation matrix or<br/>            calling any of the methods altering the transformation matrix. The property is introduced for backward compatibility with GDI+. |
| opacity | float | r/w | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Gets or sets a copy [Matrix](/imaging/python-net/aspose.imaging/matrix/) that defines a local geometric transform for this [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | r/w | Gets or sets a [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration that indicates the wrap mode for this [TransformBrush](/imaging/python-net/aspose.imaging.brushes/transformbrush/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_image_rect(image, destination_rectangle)](#create_with_image_rect_image_destination_rectangle_1) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image and bounding rectangle. |
| [create_with_image_rect_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes. |
| [create_with_image_rect_f(image, destination_rectangle)](#create_with_image_rect_f_image_destination_rectangle_3) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image and bounding rectangle. |
| [create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)](#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes. |
| [create_with_image_wrap_mode(image, wrap_mode)](#create_with_image_wrap_mode_image_wrap_mode_5) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image and wrap mode. |
| [create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle. |
| [create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)](#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7) | Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle. |
| [deep_clone()](#deep_clone__8) | Creates a new deep clone of the current [Brush](/imaging/python-net/aspose.imaging/brush/). |
| [multiply_transform(matrix)](#multiply_transform_matrix_9) | Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/). |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_10) | Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order. |
| reset_transform() | Resets the [TransformBrush.transform](/imaging/python-net/aspose.imaging.brushes/transformbrush/) property to identity. |
| [rotate_transform(angle)](#rotate_transform_angle_11) | Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_12) | Rotates the local geometric transform by the specified amount in the specified order. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_13) | Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_14) | Scales the local geometric transform by the specified amounts in the specified order. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_15) | Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_16) | Translates the local geometric transform by the specified dimensions in the specified order. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image and bounding rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the bounding rectangle for this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image and bounding rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the bounding rectangle for this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the bounding rectangle for this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object that contains additional information about the image used by this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the bounding rectangle for this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object that contains additional information about the image used by this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image and wrap mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | A [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration that specifies how this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object is tiled. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | A [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration that specifies how this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object is tiled. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the bounding rectangle for this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | A [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration that specifies how this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object is tiled. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the bounding rectangle for this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |

### Method: create_with_image_rect(image, destination_rectangle)  [static] {#create_with_image_rect_image_destination_rectangle_1}


```
 create_with_image_rect(image, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image and bounding rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_attribs_image_destination_rectangle_image_attributes_2}


```
 create_with_image_rect_attribs(image, destination_rectangle, image_attributes) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) structure that represents the bounding rectangle for this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object that contains additional information about the image used by this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f(image, destination_rectangle)  [static] {#create_with_image_rect_f_image_destination_rectangle_3}


```
 create_with_image_rect_f(image, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image and bounding rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes)  [static] {#create_with_image_rect_f_attribs_image_destination_rectangle_image_attributes_4}


```
 create_with_image_rect_f_attribs(image, destination_rectangle, image_attributes) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, bounding rectangle, and image attributes.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |
| image_attributes | [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object that contains additional information about the image used by this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode(image, wrap_mode)  [static] {#create_with_image_wrap_mode_image_wrap_mode_5}


```
 create_with_image_wrap_mode(image, wrap_mode) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image and wrap mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | A [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration that specifies how this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object is tiled. |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_image_wrap_mode_destination_rectangle_6}


```
 create_with_image_wrap_mode_rect(image, wrap_mode, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | A [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration that specifies how this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object is tiled. |
| destination_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle)  [static] {#create_with_image_wrap_mode_rect_f_image_wrap_mode_destination_rectangle_7}


```
 create_with_image_wrap_mode_rect_f(image, wrap_mode, destination_rectangle) 
```

Initializes a new instance of the [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) class that uses the specified image, wrap mode, and bounding rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [Image](/imaging/python-net/aspose.imaging/image/) | The [Image](/imaging/python-net/aspose.imaging/image/) object with which this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object fills interiors. |
| wrap_mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | A [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) enumeration that specifies how this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object is tiled. |
| destination_rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | A [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) structure that represents the bounding rectangle for this [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) object. |

**Returns**

| Type | Description |
| :- | :- |
| [TextureBrush](/imaging/python-net/aspose.imaging.brushes/texturebrush/) |  |


### Method: deep_clone() {#deep_clone__8}


```
 deep_clone() 
```

Creates a new deep clone of the current [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | A new [Brush](/imaging/python-net/aspose.imaging/brush/) which is the deep clone of this [Brush](/imaging/python-net/aspose.imaging/brush/) instance. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_9}


```
 multiply_transform(matrix) 
```

Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) by prepending the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to multiply the geometric transform. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_10}


```
 multiply_transform(matrix, order) 
```

Multiplies the [Matrix](/imaging/python-net/aspose.imaging/matrix/) that represents the local geometric transform of this [LinearGradientBrush](/imaging/python-net/aspose.imaging.brushes/lineargradientbrush/) by the specified [Matrix](/imaging/python-net/aspose.imaging/matrix/) in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The [Matrix](/imaging/python-net/aspose.imaging/matrix/) by which to multiply the geometric transform. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies in which order to multiply the two matrices. |

### Method: rotate_transform(angle) {#rotate_transform_angle_11}


```
 rotate_transform(angle) 
```

Rotates the local geometric transform by the specified amount. This method prepends the rotation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_12}


```
 rotate_transform(angle, order) 
```

Rotates the local geometric transform by the specified amount in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The angle of rotation. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the rotation matrix. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_13}


```
 scale_transform(sx, sy) 
```

Scales the local geometric transform by the specified amounts. This method prepends the scaling matrix to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_14}


```
 scale_transform(sx, sy, order) 
```

Scales the local geometric transform by the specified amounts in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The amount by which to scale the transform in the x-axis direction. |
| sy | float | The amount by which to scale the transform in the y-axis direction. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | A [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) that specifies whether to append or prepend the scaling matrix. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_15}


```
 translate_transform(dx, dy) 
```

Translates the local geometric transform by the specified dimensions. This method prepends the translation to the transform.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_16}


```
 translate_transform(dx, dy, order) 
```

Translates the local geometric transform by the specified dimensions in the specified order.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dx | float | The value of the translation in x. |
| dy | float | The value of the translation in y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | The order (prepend or append) in which to apply the translation. |

