---
title: "RectangleMask 类"
type: docs
weight: 80
url: /zh/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/
---

**Summary:** Describes a rectangle mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.RectangleMask

**Inheritance:** IImageMask, ImageMask

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [RectangleMask(selected_area)](#RectangleMask_selected_area_1) | 使用指定的矩形初始化 [RectangleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/) 类的新实例。 |
| [RectangleMask(x, y, width, height)](#RectangleMask_x_y_width_height_2) | 使用指定的左上点、宽度和高度初始化 [RectangleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | 获取此掩码的边界（以像素为单位）。 |
| height | int | r | 获取此掩码的高度（以像素为单位）。 |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | 获取掩码选定部分的边界（以像素为单位）。 |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | 获取用于创建此掩码的源图像（如果存在）。 |
| width | int | r | 获取此掩码的宽度（以像素为单位）。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| apply() | 如果存在，将当前掩码应用于 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 源。 |
| [apply_to(image)](#apply_to_image_1) | 将当前掩码应用于指定的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)。 |
| [clone()](#clone__2) | 创建一个新对象，该对象是当前实例的副本。 |
| [crop(rectangle)](#crop_rectangle_3) | 使用指定的矩形裁剪掩码。 |
| [crop(size)](#crop_size_4) | 使用指定的尺寸裁剪掩码。 |
| [crop(width, height)](#crop_width_height_5) | 使用指定的宽度和高度裁剪掩码。 |
| [exclusive_disjunction(image, settings)](#exclusive_disjunction_image_settings_6) | 获取当前掩码与对提供的图像应用魔棒选择结果的异或。 |
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_7) | 获取当前掩码与提供的内容的异或。 |
| [exclusive_disjunction(settings)](#exclusive_disjunction_settings_8) | 获取当前掩码与对掩码源应用魔棒选择结果的异或。 |
| [get(x, y)](#get_x_y_9) | 获取指定像素的透明度。 |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_10) | 获取指定像素的透明度（以字节精度）。 |
| [get_feathered(settings)](#get_feathered_settings_11) | 获取使用指定设置羽化边框的灰度遮罩。 |
| [inflate(size)](#inflate_size_12) | 按指定量膨胀此遮罩。 |
| [intersect(image, settings)](#intersect_image_settings_13) | 获取当前遮罩与对提供的图像应用魔棒选择的结果的交集。 |
| [intersect(mask)](#intersect_mask_14) | 获取当前遮罩与提供的遮罩的交集。 |
| [intersect(settings)](#intersect_settings_15) | 获取当前遮罩与对遮罩源应用魔棒选择的结果的交集。 |
| [invert()](#invert__16) | 获取当前遮罩的反转。 |
| [is_opaque(x, y)](#is_opaque_x_y_17) | 检查指定像素是否不透明。 |
| [is_transparent(x, y)](#is_transparent_x_y_18) | 检查指定像素是否透明。 |
| [subtract(image, settings)](#subtract_image_settings_19) | 获取将对提供的图像应用魔棒选择的结果从当前遮罩中减去后的结果。 |
| [subtract(mask)](#subtract_mask_20) | 获取当前遮罩减去提供的遮罩的结果。 |
| [subtract(settings)](#subtract_settings_21) | 获取将对当前遮罩源应用魔棒选择的结果从遮罩中减去后的结果。 |
| [union(image, settings)](#union_image_settings_22) | 获取当前遮罩与对提供的图像应用魔棒选择的结果的并集。 |
| [union(mask)](#union_mask_23) | 获取当前遮罩与提供的遮罩的并集。 |
| [union(settings)](#union_settings_24) | 获取当前遮罩与对遮罩源应用魔棒选择的结果的并集。 |


### Constructor: RectangleMask(selected_area) {#RectangleMask_selected_area_1}


```
 RectangleMask(selected_area) 
```

使用指定的矩形初始化 [RectangleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| selected_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 选定区域以矩形形式指定。 |

### Constructor: RectangleMask(x, y, width, height) {#RectangleMask_x_y_width_height_2}


```
 RectangleMask(x, y, width, height) 
```

使用指定的左上点、宽度和高度初始化 [RectangleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/rectanglemask/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 选定区域左上点的 x 坐标。 |
| y | int | 选定区域左上点的 y 坐标。 |
| width | int | 选定区域的宽度。 |
| height | int | 选定区域的高度。 |

### Method: apply_to(image) {#apply_to_image_1}


```
 apply_to(image) 
```

将当前掩码应用于指定的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 用于应用遮罩的图像。 |

### Method: clone() {#clone__2}


```
 clone() 
```

创建一个新对象，该对象是当前实例的副本。

**Returns**

| Type | Description |
| :- | :- |
| System.Object | 此实例的副本的新对象。 |


### Method: crop(rectangle) {#crop_rectangle_3}


```
 crop(rectangle) 
```

使用指定的矩形裁剪掩码。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 指定的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | 裁剪的 RectangleMask 作为 ImageMask。 |


### Method: crop(size) {#crop_size_4}


```
 crop(size) 
```

使用指定的尺寸裁剪掩码。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | 指定的大小。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | 一个 ImageMask。 |


### Method: crop(width, height) {#crop_width_height_5}


```
 crop(width, height) 
```

使用指定的宽度和高度裁剪掩码。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 指定的宽度。 |
| height | int | 指定的高度。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | 一个 ImageMask。 |


### Method: exclusive_disjunction(image, settings) {#exclusive_disjunction_image_settings_6}


```
 exclusive_disjunction(image, settings) 
```

获取当前掩码与对提供的图像应用魔棒选择结果的异或。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 魔棒使用的图像。 |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | 魔棒设置。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_7}


```
 exclusive_disjunction(mask) 
```

获取当前掩码与提供的内容的异或。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | 提供的掩码 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: exclusive_disjunction(settings) {#exclusive_disjunction_settings_8}


```
 exclusive_disjunction(settings) 
```

获取当前掩码与对掩码源应用魔棒选择结果的异或。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | 魔棒设置。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: get(x, y) {#get_x_y_9}


```
 get(x, y) 
```

获取指定像素的透明度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定像素不透明则为 true；否则为 false。 |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_10}


```
 get_byte_opacity(x, y) 
```

获取指定像素的透明度（以字节精度）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | 字节值，表示指定像素的透明度。 |


### Method: get_feathered(settings) {#get_feathered_settings_11}


```
 get_feathered(settings) 
```

获取使用指定设置羽化边框的灰度遮罩。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| settings | [FeatheringSettings](/imaging/python-net/aspose.imaging.magicwand.imagemasks/featheringsettings/) | 羽化设置。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) 带羽化边框。 |


### Method: inflate(size) {#inflate_size_12}


```
 inflate(size) 
```

按指定量膨胀此遮罩。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| size | int | 要膨胀此掩码的量。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | 膨胀的 RectangleMask 作为 ImageMask。 |


### Method: intersect(image, settings) {#intersect_image_settings_13}


```
 intersect(image, settings) 
```

获取当前遮罩与对提供的图像应用魔棒选择的结果的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 魔棒使用的图像。 |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | 魔棒设置。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: intersect(mask) {#intersect_mask_14}


```
 intersect(mask) 
```

获取当前遮罩与提供的遮罩的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | 提供的掩码 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: intersect(settings) {#intersect_settings_15}


```
 intersect(settings) 
```

获取当前遮罩与对遮罩源应用魔棒选择的结果的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | 魔棒设置。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: invert() {#invert__16}


```
 invert() 
```

获取当前遮罩的反转。

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: is_opaque(x, y) {#is_opaque_x_y_17}


```
 is_opaque(x, y) 
```

检查指定像素是否不透明。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定像素不透明则为 true；否则为 false。 |


### Method: is_transparent(x, y) {#is_transparent_x_y_18}


```
 is_transparent(x, y) 
```

检查指定像素是否透明。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果指定像素透明则为 true；否则为 false。 |


### Method: subtract(image, settings) {#subtract_image_settings_19}


```
 subtract(image, settings) 
```

获取将对提供的图像应用魔棒选择的结果从当前遮罩中减去后的结果。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 魔棒使用的图像。 |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | 魔棒设置。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: subtract(mask) {#subtract_mask_20}


```
 subtract(mask) 
```

获取当前遮罩减去提供的遮罩的结果。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | 提供的掩码 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: subtract(settings) {#subtract_settings_21}


```
 subtract(settings) 
```

获取将对当前遮罩源应用魔棒选择的结果从遮罩中减去后的结果。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | 魔棒设置。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: union(image, settings) {#union_image_settings_22}


```
 union(image, settings) 
```

获取当前遮罩与对提供的图像应用魔棒选择的结果的并集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 魔棒使用的图像。 |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | 魔棒设置。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: union(mask) {#union_mask_23}


```
 union(mask) 
```

获取当前遮罩与提供的遮罩的并集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mask | [ImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagemask/) | 提供的掩码 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


### Method: union(settings) {#union_settings_24}


```
 union(settings) 
```

获取当前遮罩与对遮罩源应用魔棒选择的结果的并集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | 魔棒设置。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | 新建 [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |


