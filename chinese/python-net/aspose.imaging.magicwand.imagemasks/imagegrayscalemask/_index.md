---
title: "ImageGrayscaleMask 类"
type: docs
weight: 60
url: /zh/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---

**Summary:** Describes a grayscale image mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask

**Inheritance:** IImageMask

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ImageGrayscaleMask(image)](#ImageGrayscaleMask_image_1) | 使用指定的现有 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的尺寸，初始化 [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) 类的新实例。<br/>            指定的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 将被存储为源图像。 |
| [ImageGrayscaleMask(width, height)](#ImageGrayscaleMask_width_height_2) | 使用指定的宽度和高度，初始化 [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) 类的新实例。 |
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
| [exclusive_disjunction(mask)](#exclusive_disjunction_mask_6) | 获取当前掩码与提供的内容的异或。 |
| [get(x, y)](#get_x_y_7) | 获取或设置指定像素的不透明度。 |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_8) | 获取指定像素的透明度（以字节精度）。 |
| [intersect(mask)](#intersect_mask_9) | 获取当前遮罩与提供的遮罩的交集。 |
| [invert()](#invert__10) | 获取当前遮罩的反转。 |
| [is_opaque(x, y)](#is_opaque_x_y_11) | 检查指定像素是否不透明。 |
| [is_transparent(x, y)](#is_transparent_x_y_12) | 检查指定像素是否透明。 |
| [set(x, y, value)](#set_x_y_value_13) | 设置指定像素的不透明度。 |
| [subtract(mask)](#subtract_mask_14) | 获取当前遮罩减去提供的遮罩的结果。 |
| [union(mask)](#union_mask_15) | 两个掩码的并集。 |


### Constructor: ImageGrayscaleMask(image) {#ImageGrayscaleMask_image_1}


```
 ImageGrayscaleMask(image) 
```

使用指定的现有 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的尺寸，初始化 [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) 类的新实例。<br/>            指定的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 将被存储为源图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 源图像。 |

### Constructor: ImageGrayscaleMask(width, height) {#ImageGrayscaleMask_width_height_2}


```
 ImageGrayscaleMask(width, height) 
```

使用指定的宽度和高度，初始化 [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 掩码的宽度。 |
| height | int | 掩码的高度。 |

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
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | 裁剪后的 [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/)。 |


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
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | 裁剪后的 [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/)。 |


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
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | 裁剪后的 [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/)。 |


### Method: exclusive_disjunction(mask) {#exclusive_disjunction_mask_6}


```
 exclusive_disjunction(mask) 
```

获取当前掩码与提供的内容的异或。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | 提供的掩码 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | 新的 [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/)。 |


### Method: get(x, y) {#get_x_y_7}


```
 get(x, y) 
```

获取或设置指定像素的不透明度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | 字节值；透明为 0；不透明为 255。 |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_8}


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


### Method: intersect(mask) {#intersect_mask_9}


```
 intersect(mask) 
```

获取当前遮罩与提供的遮罩的交集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | 提供的掩码 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | 新的 [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/)。 |


### Method: invert() {#invert__10}


```
 invert() 
```

获取当前遮罩的反转。

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | 新的 [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/)。 |


### Method: is_opaque(x, y) {#is_opaque_x_y_11}


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


### Method: is_transparent(x, y) {#is_transparent_x_y_12}


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


### Method: set(x, y, value) {#set_x_y_value_13}


```
 set(x, y, value) 
```

设置指定像素的不透明度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |
| value | System.Byte | 字节值；透明为 0；不透明为 255。 |

### Method: subtract(mask) {#subtract_mask_14}


```
 subtract(mask) 
```

获取当前遮罩减去提供的遮罩的结果。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | 提供的掩码 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | 新的 [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/)。 |


### Method: union(mask) {#union_mask_15}


```
 union(mask) 
```

两个掩码的并集。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| mask | [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | 提供的掩码 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/) | 新的 [ImageGrayscaleMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/)。 |


