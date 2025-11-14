---
title: ImageGrayscaleMask Class
type: docs
weight: 60
url: /python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---

**Summary:** Describes a grayscale image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask

**Inheritance:** IImageMask

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageGrayscaleMask(image)](#ImageGrayscaleMask_image_1) | Initializes a new instance of the [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) class with the size of the specified existing [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).<br/>            Specified [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) will be stored as source image. |
| [ImageGrayscaleMask(width, height)](#ImageGrayscaleMask_width_height_2) | Initializes a new instance of the [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) class with the specified width and height. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Gets the bounds, in pixels, of this mask. |
| height | int | r | Gets the height, in pixels, of this mask. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Gets the bounds of the selected part of the mask, in pixels. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | Gets the source image used to create this mask, if exists. |
| width | int | r | Gets the width, in pixels, of this mask. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| apply() | Applies current mask to the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) source, if exists. |
| [apply_to(image)](#apply_to_image_1) | Applies current mask to the specified [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [clone()](#clone__2) | Creates a new object that is a copy of the current instance. |
| [crop(rectangle)](#crop_rectangle_3) | Crops mask with the specified rectangle. |
| [crop(size)](#crop_size_4) | Crops mask with the specified size. |
| [crop(width, height)](#crop_width_height_5) | Crops mask with the specified width and height. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_6) | Gets the exclusive disjunction of current mask with provided. |
| [get(x, y)](#get_x_y_7) | Gets or sets the opacity of the specified pixel. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_8) | Gets the opacity of the specified pixel with byte precision. |
| [intersect(mask)](#intersect_mask_9) | Gets the intersection of current mask with provided. |
| [invert()](#invert__10) | Gets the inversion of the current mask. |
| [is_opaque(x, y)](#is_opaque_x_y_11) | Checks if the specified pixel is opaque. |
| [is_transparent(x, y)](#is_transparent_x_y_12) | Checks if the specified pixel is transparent. |
| [set(x, y, value)](#set_x_y_value_13) | Sets the opacity of the specified pixel. |
| [subtract(mask)](#subtract_mask_14) | Gets the subtraction of the provided mask from current. |
| [union(mask)](#union_mask_15) | Union of two masks. |


### Constructor: ImageGrayscaleMask(image) {#ImageGrayscaleMask_image_1}


```
 ImageGrayscaleMask(image) 
```

Initializes a new instance of the [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) class with the size of the specified existing [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).<br/>            Specified [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) will be stored as source image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Source image. |

### Constructor: ImageGrayscaleMask(width, height) {#ImageGrayscaleMask_width_height_2}


```
 ImageGrayscaleMask(width, height) 
```

Initializes a new instance of the [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) class with the specified width and height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | Width of the mask. |
| height | int | Height of the mask. |

### Method: apply_to(image) {#apply_to_image_1}


```
 apply_to(image) 
```

Applies current mask to the specified [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image to apply mask to. |

### Method: clone() {#clone__2}


```
 clone() 
```

Creates a new object that is a copy of the current instance.

**Returns**

| Type | Description |
| :- | :- |
| System.Object | A new object that is a copy of this instance. |


### Method: crop(rectangle) {#crop_rectangle_3}


```
 crop(rectangle) 
```

Crops mask with the specified rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The specified rectangle. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | A cropped [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: crop(size) {#crop_size_4}


```
 crop(size) 
```

Crops mask with the specified size.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | The specified size. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | An cropped [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: crop(width, height) {#crop_width_height_5}


```
 crop(width, height) 
```

Crops mask with the specified width and height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The specified width. |
| height | int | The specified height. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | An cropped [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_6}


```
 exclusive_disjunction(mask) 
```

Gets the exclusive disjunction of current mask with provided.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Provided mask |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | New [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: get(x, y) {#get_x_y_7}


```
 get(x, y) 
```

Gets or sets the opacity of the specified pixel.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Byte value; 0 if transparent; 255 if opaque. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_8}


```
 get_byte_opacity(x, y) 
```

Gets the opacity of the specified pixel with byte precision.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Byte value, representing the opacity of the specified pixel. |


### Method: intersect(mask) {#intersect_mask_9}


```
 intersect(mask) 
```

Gets the intersection of current mask with provided.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Provided mask |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | New [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: invert() {#invert__10}


```
 invert() 
```

Gets the inversion of the current mask.

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | New [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_11}


```
 is_opaque(x, y) 
```

Checks if the specified pixel is opaque.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if the specified pixel is opaque; otherwise, false. |


### Method: is_transparent(x, y) {#is_transparent_x_y_12}


```
 is_transparent(x, y) 
```

Checks if the specified pixel is transparent.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if the specified pixel is transparent; otherwise, false. |


### Method: set(x, y, value) {#set_x_y_value_13}


```
 set(x, y, value) 
```

Sets the opacity of the specified pixel.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |
| value | System.Byte | Byte value; 0 if transparent; 255 if opaque. |

### Method: subtract(mask) {#subtract_mask_14}


```
 subtract(mask) 
```

Gets the subtraction of the provided mask from current.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Provided mask |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | New [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


### Method: union(mask) {#union_mask_15}


```
 union(mask) 
```

Union of two masks.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | Provided mask |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | New [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/). |


