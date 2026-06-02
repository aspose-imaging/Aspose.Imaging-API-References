---
title: "Класс ColorPaletteHelper"
type: docs
weight: 1200
url: /ru/python-net/aspose.imaging/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPaletteHelper

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Создает 4-битовую цветовую палитру. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Создает 4-битовую палитру градаций серого. |
| [create_8_bit()](#create_8_bit__3) | Создает 8-битовую цветовую палитру. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Создает 8-битовую палитру градаций серого. |
| [create_grayscale(bits)](#create_grayscale_bits_5) | Получает градационную палитру указанного количества бит. Допустимые значения бит: 1, 2, 4, 8. |
| [create_monochrome()](#create_monochrome__6) | Создаёт монохромную цветовую палитру, содержащую только 2 цвета. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_7) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_11) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений. |
| [get_close_image_palette(image, entries_count, palette_mining_method)](#get_close_image_palette_image_entries_count_palette_mining_method_12) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Палитра будет оптимизирована для лучшего качества индексированного изображения или оставлена "AS IS", когда используется PaletteMiningMethod.UseCurrentPalette. |
| [get_close_image_palette_by_method(image, entries_count, palette_mining_method)](#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Палитра будет оптимизирована для лучшего качества индексированного изображения или оставлена "AS IS", когда используется PaletteMiningMethod.UseCurrentPalette. |
| [get_close_image_palette_by_rect(image, dest_bounds, entries_count)](#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений. |
| [get_close_transparent_image_palette(image, entries_count)](#get_close_transparent_image_palette_image_entries_count_15) | Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений. |
| [get_downscale_palette(image)](#get_downscale_palette_image_16) | Получить 256‑цветную палитру, составленную из старших битов начальных цветовых значений изображения. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_17) | Получить однородную 256‑цветную палитру. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_18) | Определяет, содержит ли указанная палитра прозрачные цвета. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Создает 4-битовую цветовую палитру.

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 4‑битная цветовая палитра. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Создает 4-битовую палитру градаций серого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| min_is_white | bool | если установлено в <c>true</c>, палитра начинается с белого цвета, иначе начинается с чёрного цвета. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 4‑битная градационная палитра. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Создает 8-битовую цветовую палитру.

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 8‑битная цветовая палитра. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Создает 8-битовую палитру градаций серого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| min_is_white | bool | если установлено в <c>true</c>, палитра начинается с белого цвета, иначе начинается с чёрного цвета. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 8‑битная градационная палитра. |


### Method: create_grayscale(bits)  [static] {#create_grayscale_bits_5}


```
 create_grayscale(bits) 
```

Получает градационную палитру указанного количества бит. Допустимые значения бит: 1, 2, 4, 8.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| биты | int | Количество бит. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Градационная палитра. |


### Method: create_monochrome()  [static] {#create_monochrome__6}


```
 create_monochrome() 
```

Создаёт монохромную цветовую палитру, содержащую только 2 цвета.

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Цветовая палитра для монохромных изображений. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_7}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Растровое изображение. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы целевого изображения. |
| entries_count | int | Желаемое количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Цветовая палитра, которая начинается с самых часто встречающихся цветов из _image_ и содержит _entriesCount_ элементов. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Растровое изображение. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы целевого изображения. |
| entries_count | int | Желаемое количество элементов. |
| use_image_palette | bool | Если установлено, будет использована собственная палитра изображения, если она доступна |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Цветовая палитра, которая начинается с самых часто встречающихся цветов из _image_ и содержит _entriesCount_ элементов. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color) 
```

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Растровое изображение. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы целевого изображения. |
| entries_count | int | Желаемое количество элементов. |
| use_image_palette | bool | Если установлено, будет использована собственная палитра изображения, если она доступна |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет, который следует использовать в качестве фонового при полупрозрачной замене альфа‑канала. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Цветовая палитра, которая начинается с самых часто встречающихся цветов из _image_ и содержит _entriesCount_ элементов. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency) 
```

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Растровое изображение. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы целевого изображения. |
| entries_count | int | Желаемое количество элементов. |
| use_image_palette | bool | Если установлено, будет использована собственная палитра изображения, если она доступна |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | Цвет, который следует использовать в качестве фонового при полупрозрачной замене альфа‑канала. |
| keep_transparency | bool | Если установлено, будут учитываться биты альфа‑канала цветов изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Цветовая палитра, которая начинается с самых часто встречающихся цветов из _image_ и содержит _entriesCount_ элементов. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_11}


```
 get_close_image_palette(image, entries_count) 
```

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Растровое изображение. |
| entries_count | int | Желаемое количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Цветовая палитра, которая начинается с самых часто встречающихся цветов из _image_ и содержит _entriesCount_ элементов. |



**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Method: get_close_image_palette(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_image_entries_count_palette_mining_method_12}


```
 get_close_image_palette(image, entries_count, palette_mining_method) 
```

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Палитра будет оптимизирована для лучшего качества индексированного изображения или оставлена "AS IS", когда используется PaletteMiningMethod.UseCurrentPalette.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Растровое изображение. |
| entries_count | int | Желаемое количество элементов. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Метод извлечения палитры. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Цветовая палитра, которая начинается с самых часто встречающихся цветов из _image_ и содержит _entriesCount_ элементов. |



**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Method: get_close_image_palette_by_method(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13}


```
 get_close_image_palette_by_method(image, entries_count, palette_mining_method) 
```

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Палитра будет оптимизирована для лучшего качества индексированного изображения или оставлена "AS IS", когда используется PaletteMiningMethod.UseCurrentPalette.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Растровое изображение. |
| entries_count | int | Желаемое количество элементов. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Метод извлечения палитры. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Цветовая палитра, которая начинается с самых часто встречающихся цветов из _image_ и содержит _entriesCount_ элементов. |


### Method: get_close_image_palette_by_rect(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14}


```
 get_close_image_palette_by_rect(image, dest_bounds, entries_count) 
```

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Растровое изображение. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Границы целевого изображения. |
| entries_count | int | Желаемое количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Цветовая палитра, которая начинается с самых часто встречающихся цветов из _image_ и содержит _entriesCount_ элементов. |


### Method: get_close_transparent_image_palette(image, entries_count)  [static] {#get_close_transparent_image_palette_image_entries_count_15}


```
 get_close_transparent_image_palette(image, entries_count) 
```

Получает цветовую палитру из растрового изображения (палетизирует изображение), если у изображения её нет. Если палитра существует, она будет использована вместо выполнения вычислений.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Растровое изображение. |
| entries_count | int | Желаемое количество элементов. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Цветовая палитра, которая начинается с самых часто встречающихся цветов из _image_ и содержит _entriesCount_ элементов. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_16}


```
 get_downscale_palette(image) 
```

Получить 256‑цветную палитру, составленную из старших битов начальных цветовых значений изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Класс [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_17}


```
 get_uniform_color_palette(image) 
```

Получить однородную 256‑цветную палитру.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Изображение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Класс [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_18}


```
 has_transparent_colors(palette) 
```

Определяет, содержит ли указанная палитра прозрачные цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Палитра. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если указанная палитра содержит прозрачные цвета; в противном случае <c>false</c>. |


## **Examples**
### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Создайте BMP‑изображение размером 100 × 100 px.
with BmpImage(100, 100) as bmpImage:
	# Линейный градиент от левого верхнего до правого нижнего угла изображения.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Заполните всё изображение кистью линейного градиента.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Получите ближайшую 8‑битную цветовую палитру, покрывающую как можно больше пикселей, так чтобы палитризированное изображение
	# было почти визуально неотличимо от BMP без палитры
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# 8‑битная палитра содержит не более 256 цветов.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# Вывод выглядит так:
# Размер изображения с палитрой составляет 11078 байт.
# Размер изображения без палитры составляет 40054 байт.

```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Загружает PNG‑изображение
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Использовать индексный тип цвета
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Использовать максимальное сжатие
	png_options.compression_level = 9
	# Получите ближайшую 8‑битную цветовую палитру, покрывающую как можно больше пикселей, так чтобы изображение
	# с палитрой было почти визуально неотличимо от изображения без палитры.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# Размер выходного файла должен значительно уменьшиться

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

	# Создайте BmpOptions
	saveOptions = BmpOptions()

	# Используйте 8 бит на пиксель, чтобы уменьшить размер выходного изображения.
	saveOptions.bits_per_pixel = 8

	# Установите ближайшую 8‑битную цветовую палитру, покрывающую максимальное количество пикселей изображения, так чтобы палитризированное изображение
	# почти визуально не отличим от непалетизированного.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Сохранить без сжатия.
	# Вы также можете использовать сжатие RLE-8, чтобы уменьшить размер выходного изображения.
	saveOptions.compression = BitmapCompression.RGB

	# Установите горизонтальное и вертикальное разрешение в 96 dpi.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

