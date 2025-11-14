---
title: RectangleMask Class
type: docs
weight: 80
url: /python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/
---

**Summary:** Describes a rectangle mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.RectangleMask

**Inheritance:** IImageMask, ImageMask

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RectangleMask(selected_area)](#RectangleMask_selected_area_1) | Initializes a new instance of the [RectangleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/) class with the specified rectangle. |
| [RectangleMask(x, y, width, height)](#RectangleMask_x_y_width_height_2) | Initializes a new instance of the [RectangleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/) class with the specified left-top point, width and height. |
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
| [exclusive_disjunction(image, settings)](#exclusive_disjunction_image_settings_6) | Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the provided image. |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_7) | Gets the exclusive disjunction of current mask with provided. |
| [exclusive_disjunction(settings)](#exclusive_disjunction_settings_8) | Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the source of the mask. |
| [get(x, y)](#get_x_y_9) | Gets the opacity of the specified pixel. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_10) | Gets the opacity of the specified pixel with byte precision. |
| [get_feathered(settings)](#get_feathered_settings_11) | Gets grayscale mask with the border feathered with the specified settings. |
| [inflate(size)](#inflate_size_12) | Inflates this mask by the specified amount. |
| [intersect(image, settings)](#intersect_image_settings_13) | Gets the intersection of the current mask with the result of magic wand selection applied to the provided image. |
| [intersect(mask)](#intersect_mask_14) | Gets the intersection of current mask with provided. |
| [intersect(settings)](#intersect_settings_15) | Gets the intersection of the current mask with the result of magic wand selection applied to the source of the mask. |
| [invert()](#invert__16) | Gets the inversion of the current mask. |
| [is_opaque(x, y)](#is_opaque_x_y_17) | Checks if the specified pixel is opaque. |
| [is_transparent(x, y)](#is_transparent_x_y_18) | Checks if the specified pixel is transparent. |
| [subtract(image, settings)](#subtract_image_settings_19) | Gets the result of magic wand selection applied to the provided image subtracted from the current mask. |
| [subtract(mask)](#subtract_mask_20) | Gets the subtraction of the provided mask from current. |
| [subtract(settings)](#subtract_settings_21) | Gets the result of magic wand selection applied to the source of the current mask subtracted from the mask. |
| [union(image, settings)](#union_image_settings_22) | Gets the union of the current mask with the result of magic wand selection applied to the provided image. |
| [union(mask)](#union_mask_23) | Gets the union of the current mask with provided. |
| [union(settings)](#union_settings_24) | Gets the union of the current mask with the result of magic wand selection applied to the source of the mask. |


### Constructor: RectangleMask(selected_area) {#RectangleMask_selected_area_1}


```
 RectangleMask(selected_area) 
```

Initializes a new instance of the [RectangleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/) class with the specified rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| selected_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Selected area specified as a rectangle. |

### Constructor: RectangleMask(x, y, width, height) {#RectangleMask_x_y_width_height_2}


```
 RectangleMask(x, y, width, height) 
```

Initializes a new instance of the [RectangleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/) class with the specified left-top point, width and height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the left-top point of the selected area. |
| y | int | The y-coordinate of the left-top point of the selected area. |
| width | int | Width of the selected area. |
| height | int | Height of the selected area. |

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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | A cropped RectangleMask as ImageMask. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | An ImageMask. |


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
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | An ImageMask. |


### Method: exclusive_disjunction(image, settings) {#exclusive_disjunction_image_settings_6}


```
 exclusive_disjunction(image, settings) 
```

Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the provided image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image for magic wand. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Magic wand settings. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_7}


```
 exclusive_disjunction(mask) 
```

Gets the exclusive disjunction of current mask with provided.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Provided mask |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: exclusive_disjunction(settings) {#exclusive_disjunction_settings_8}


```
 exclusive_disjunction(settings) 
```

Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the source of the mask.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Magic wand settings. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: get(x, y) {#get_x_y_9}


```
 get(x, y) 
```

Gets the opacity of the specified pixel.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if the specified pixel is opaque; otherwise, false. |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_10}


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


### Method: get_feathered(settings) {#get_feathered_settings_11}


```
 get_feathered(settings) 
```

Gets grayscale mask with the border feathered with the specified settings.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| settings | [FeatheringSettings](/imaging/python-net/aspose.imaging.magicwand.imagemasks/featheringsettings/) | Feathering settings. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) with feathered border. |


### Method: inflate(size) {#inflate_size_12}


```
 inflate(size) 
```

Inflates this mask by the specified amount.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| size | int | The amount to inflate this mask. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | An inflated RectangleMask as ImageMask. |


### Method: intersect(image, settings) {#intersect_image_settings_13}


```
 intersect(image, settings) 
```

Gets the intersection of the current mask with the result of magic wand selection applied to the provided image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image for magic wand. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Magic wand settings. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(mask) {#intersect_mask_14}


```
 intersect(mask) 
```

Gets the intersection of current mask with provided.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Provided mask |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: intersect(settings) {#intersect_settings_15}


```
 intersect(settings) 
```

Gets the intersection of the current mask with the result of magic wand selection applied to the source of the mask.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Magic wand settings. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: invert() {#invert__16}


```
 invert() 
```

Gets the inversion of the current mask.

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: is_opaque(x, y) {#is_opaque_x_y_17}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_18}


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


### Method: subtract(image, settings) {#subtract_image_settings_19}


```
 subtract(image, settings) 
```

Gets the result of magic wand selection applied to the provided image subtracted from the current mask.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image for magic wand. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Magic wand settings. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(mask) {#subtract_mask_20}


```
 subtract(mask) 
```

Gets the subtraction of the provided mask from current.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Provided mask |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: subtract(settings) {#subtract_settings_21}


```
 subtract(settings) 
```

Gets the result of magic wand selection applied to the source of the current mask subtracted from the mask.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Magic wand settings. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(image, settings) {#union_image_settings_22}


```
 union(image, settings) 
```

Gets the union of the current mask with the result of magic wand selection applied to the provided image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image for magic wand. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Magic wand settings. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(mask) {#union_mask_23}


```
 union(mask) 
```

Gets the union of the current mask with provided.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | Provided mask |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


### Method: union(settings) {#union_settings_24}


```
 union(settings) 
```

Gets the union of the current mask with the result of magic wand selection applied to the source of the mask.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Magic wand settings. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


