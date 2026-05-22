---
title: "ColorPaletteHelper 类"
type: docs
weight: 1200
url: /zh/python-net/aspose.imaging/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPaletteHelper

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | 创建 4 位颜色调色板。 |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | 创建 4 位灰度调色板。 |
| [create_8_bit()](#create_8_bit__3) | 创建 8 位颜色调色板。 |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | 创建 8 位灰度调色板。 |
| [create_grayscale(bits)](#create_grayscale_bits_5) | 获取指定位数的灰度调色板。允许的位值为 1、2、4、8。 |
| [create_monochrome()](#create_monochrome__6) | 创建仅包含 2 种颜色的单色调色板。 |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_7) | 在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。 |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8) | 在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。 |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9) | 在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。 |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10) | 在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。 |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_11) | 在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。 |
| [get_close_image_palette(image, entries_count, palette_mining_method)](#get_close_image_palette_image_entries_count_palette_mining_method_12) | 在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。调色板将被优化以获得更好的索引图像质量，或者在使用 PaletteMiningMethod.UseCurrentPalette 时保持 "AS IS"。 |
| [get_close_image_palette_by_method(image, entries_count, palette_mining_method)](#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13) | 在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。调色板将被优化以获得更好的索引图像质量，或者在使用 PaletteMiningMethod.UseCurrentPalette 时保持 "AS IS"。 |
| [get_close_image_palette_by_rect(image, dest_bounds, entries_count)](#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14) | 在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。 |
| [get_close_transparent_image_palette(image, entries_count)](#get_close_transparent_image_palette_image_entries_count_15) | 在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。 |
| [get_downscale_palette(image)](#get_downscale_palette_image_16) | 获取 256 色调色板，由初始图像颜色值的高位组成。 |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_17) | 获取统一的 256 色调色板。 |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_18) | 确定指定的调色板是否具有透明颜色。 |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

创建 4 位颜色调色板。

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 4 位颜色调色板。 |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

创建 4 位灰度调色板。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| min_is_white | bool | 如果设置为 <c>true</c>，调色板将以白色开始，否则以黑色开始。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 4 位灰度调色板。 |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

创建 8 位颜色调色板。

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 8 位颜色调色板。 |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

创建 8 位灰度调色板。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| min_is_white | bool | 如果设置为 <c>true</c>，调色板将以白色开始，否则以黑色开始。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 8 位灰度调色板。 |


### Method: create_grayscale(bits)  [static] {#create_grayscale_bits_5}


```
 create_grayscale(bits) 
```

获取指定位数的灰度调色板。允许的位值为 1、2、4、8。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 位 | int | 位计数。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 灰度调色板。 |


### Method: create_monochrome()  [static] {#create_monochrome__6}


```
 create_monochrome() 
```

创建仅包含 2 种颜色的单色调色板。

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 单色图像的颜色调色板。 |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_7}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标图像边界。 |
| entries_count | int | 所需条目数。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 该颜色调色板以 _image_ 中出现频率最高的颜色开始，并包含 _entriesCount_ 个条目。 |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标图像边界。 |
| entries_count | int | 所需条目数。 |
| use_image_palette | bool | 如果设置，则在可用时使用其自身的图像调色板。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 该颜色调色板以 _image_ 中出现频率最高的颜色开始，并包含 _entriesCount_ 个条目。 |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color) 
```

在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标图像边界。 |
| entries_count | int | 所需条目数。 |
| use_image_palette | bool | 如果设置，则在可用时使用其自身的图像调色板。 |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | 应作为半透明 alpha 替换的背景颜色的颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 该颜色调色板以 _image_ 中出现频率最高的颜色开始，并包含 _entriesCount_ 个条目。 |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency) 
```

在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标图像边界。 |
| entries_count | int | 所需条目数。 |
| use_image_palette | bool | 如果设置，则在可用时使用其自身的图像调色板。 |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | 应作为半透明 alpha 替换的背景颜色的颜色。 |
| keep_transparency | bool | 如果设置，它将考虑图像颜色的 alpha 通道位。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 该颜色调色板以 _image_ 中出现频率最高的颜色开始，并包含 _entriesCount_ 个条目。 |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_11}


```
 get_close_image_palette(image, entries_count) 
```

在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |
| entries_count | int | 所需条目数。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 该颜色调色板以 _image_ 中出现频率最高的颜色开始，并包含 _entriesCount_ 个条目。 |



**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Method: get_close_image_palette(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_image_entries_count_palette_mining_method_12}


```
 get_close_image_palette(image, entries_count, palette_mining_method) 
```

在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。调色板将被优化以获得更好的索引图像质量，或者在使用 PaletteMiningMethod.UseCurrentPalette 时保持 "AS IS"。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |
| entries_count | int | 所需条目数。 |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | 调色板挖掘方法。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 该颜色调色板以 _image_ 中出现频率最高的颜色开始，并包含 _entriesCount_ 个条目。 |



**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Method: get_close_image_palette_by_method(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13}


```
 get_close_image_palette_by_method(image, entries_count, palette_mining_method) 
```

在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。调色板将被优化以获得更好的索引图像质量，或者在使用 PaletteMiningMethod.UseCurrentPalette 时保持 "AS IS"。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |
| entries_count | int | 所需条目数。 |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | 调色板挖掘方法。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 该颜色调色板以 _image_ 中出现频率最高的颜色开始，并包含 _entriesCount_ 个条目。 |


### Method: get_close_image_palette_by_rect(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14}


```
 get_close_image_palette_by_rect(image, dest_bounds, entries_count) 
```

在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标图像边界。 |
| entries_count | int | 所需条目数。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 该颜色调色板以 _image_ 中出现频率最高的颜色开始，并包含 _entriesCount_ 个条目。 |


### Method: get_close_transparent_image_palette(image, entries_count)  [static] {#get_close_transparent_image_palette_image_entries_count_15}


```
 get_close_transparent_image_palette(image, entries_count) 
```

在图像没有调色板的情况下，从光栅图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则会使用它，而不是执行计算。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |
| entries_count | int | 所需条目数。 |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 该颜色调色板以 _image_ 中出现频率最高的颜色开始，并包含 _entriesCount_ 个条目。 |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_16}


```
 get_downscale_palette(image) 
```

获取 256 色调色板，由初始图像颜色值的高位组成。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 图像。 |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | 此 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/)。 |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_17}


```
 get_uniform_color_palette(image) 
```

获取统一的 256 色调色板。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 图像。 |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | 此 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/)。 |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_18}


```
 has_transparent_colors(palette) 
```

确定指定的调色板是否具有透明颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 调色板。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> 如果指定的调色板具有透明颜色；否则，<c>false</c>。 |


## **Examples**
### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# 创建一个 100 x 100 像素的 BMP 图像。
with BmpImage(100, 100) as bmpImage:
	# 图像左上角到右下角的线性渐变。
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# 使用线性渐变画刷填充整个图像。
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# 获取最接近的 8 位颜色调色板，覆盖尽可能多的像素，以便调色板图像
	# 在视觉上几乎与没有调色板的 bmp 无法区分
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# 8 位调色板最多包含 256 种颜色。
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# 输出如下：
# 带调色板的图像大小为 11078 字节。
# 不带调色板的图像大小为 40054 字节。

```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# 加载 png 图像
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# 使用索引颜色类型
	png_options.color_type = PngColorType.INDEXED_COLOR
	# 使用最大压缩
	png_options.compression_level = 9
	# 获取最接近的 8 位颜色调色板，覆盖尽可能多的像素，以便图像
	# 带调色板的图像在视觉上几乎与没有调色板的图像无法区分。
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# 输出文件大小应显著减小

```

### The following example loads a BMP image and saves it back to BMP using various save options. {#example_91}
``` python
from aspose.imaging import Image, RasterImage, ColorPaletteHelper, ResolutionSetting
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
import os
import aspose.pycore as aspycore

directory = "c:\\temp\\"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	
	rasterImage = aspycore.as_of(image, RasterImage)

	# 创建 BmpOptions
	saveOptions = BmpOptions()

	# 使用每像素 8 位来减小输出图像的大小。
	saveOptions.bits_per_pixel = 8

	# 设置最接近的 8 位颜色调色板，覆盖最多的图像像素，以便调色板图像
	# 几乎在视觉上与非调色板图像无异。
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# 保存时不使用压缩。
	# 您也可以使用 RLE-8 压缩来减小输出图像的大小。
	saveOptions.compression = BitmapCompression.RGB

	# 将水平和垂直分辨率设置为 96 dpi。
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

