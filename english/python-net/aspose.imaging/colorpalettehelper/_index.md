---
title: ColorPaletteHelper Class
type: docs
weight: 1200
url: /python-net/aspose.imaging/colorpalettehelper/
---

**Summary:** Helper class for color palettes manipulation.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPaletteHelper

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_4_bit()](#create_4_bit__1) | Creates the 4 bit color palette. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_2) | Creates the 4 bit grayscale palette. |
| [create_8_bit()](#create_8_bit__3) | Creates the 8 bit color palette. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_4) | Creates the 8 bit grayscale palette. |
| [create_grayscale(bits)](#create_grayscale_bits_5) | Gets the grayscale palette of specified bit count. Allowed bit values are 1, 2, 4, 8. |
| [create_monochrome()](#create_monochrome__6) | Creates a monochrome color palette containing 2 colors only. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_7) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_11) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_image_palette(image, entries_count, palette_mining_method)](#get_close_image_palette_image_entries_count_palette_mining_method_12) | Gets color palette from raster image (palletizes image) in case the image does not have one. Palette is about to be optimized for better indexed image quality or taken "AS IS" when PaletteMiningMethod.UseCurrentPalette is used. |
| [get_close_image_palette_by_method(image, entries_count, palette_mining_method)](#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13) | Gets color palette from raster image (palletizes image) in case the image does not have one. Palette is about to be optimized for better indexed image quality or taken "AS IS" when PaletteMiningMethod.UseCurrentPalette is used. |
| [get_close_image_palette_by_rect(image, dest_bounds, entries_count)](#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_transparent_image_palette(image, entries_count)](#get_close_transparent_image_palette_image_entries_count_15) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_downscale_palette(image)](#get_downscale_palette_image_16) | Get 256 color palette, composed from upper bits of initial image color values. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_17) | Get uniform 256 color palette. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_18) | Determines whether the specified palette has transparent colors. |


### Method: create_4_bit()  [static] {#create_4_bit__1}


```
 create_4_bit() 
```

Creates the 4 bit color palette.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The 4 bit color palette. |


### Method: create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_2}


```
 create_4_bit_grayscale(min_is_white) 
```

Creates the 4 bit grayscale palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| min_is_white | bool | if set to <c>true</c> the palette starts with white color, otherwise it starts with black color. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The 4 bit grayscale palette. |


### Method: create_8_bit()  [static] {#create_8_bit__3}


```
 create_8_bit() 
```

Creates the 8 bit color palette.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The 8 bit color palette. |


### Method: create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_4}


```
 create_8_bit_grayscale(min_is_white) 
```

Creates the 8 bit grayscale palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| min_is_white | bool | if set to <c>true</c> the palette starts with white color, otherwise it starts with black color. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The 8 bit grayscale palette. |


### Method: create_grayscale(bits)  [static] {#create_grayscale_bits_5}


```
 create_grayscale(bits) 
```

Gets the grayscale palette of specified bit count. Allowed bit values are 1, 2, 4, 8.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bits | int | The bit count. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Grayscale palette. |


### Method: create_monochrome()  [static] {#create_monochrome__6}


```
 create_monochrome() 
```

Creates a monochrome color palette containing 2 colors only.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Color palette for monochrome images. |


### Method: get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_7}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The raster image. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds. |
| entries_count | int | The desired entries count. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The color palette which starts with the most frequent colors from the _image_ and contains _entriesCount_ entries. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_8}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The raster image. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds. |
| entries_count | int | The desired entries count. |
| use_image_palette | bool | If set, it will use its own image palette if available |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The color palette which starts with the most frequent colors from the _image_ and contains _entriesCount_ entries. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_9}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The raster image. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds. |
| entries_count | int | The desired entries count. |
| use_image_palette | bool | If set, it will use its own image palette if available |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | The color that should be used as a background color for semi-transparent alpha replacement. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The color palette which starts with the most frequent colors from the _image_ and contains _entriesCount_ entries. |


### Method: get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_10}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The raster image. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds. |
| entries_count | int | The desired entries count. |
| use_image_palette | bool | If set, it will use its own image palette if available |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color/) | The color that should be used as a background color for semi-transparent alpha replacement. |
| keep_transparency | bool | If set, it will consider alpha channel bits of the image colors. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The color palette which starts with the most frequent colors from the _image_ and contains _entriesCount_ entries. |


### Method: get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_11}


```
 get_close_image_palette(image, entries_count) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The raster image. |
| entries_count | int | The desired entries count. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The color palette which starts with the most frequent colors from the _image_ and contains _entriesCount_ entries. |



**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Method: get_close_image_palette(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_image_entries_count_palette_mining_method_12}


```
 get_close_image_palette(image, entries_count, palette_mining_method) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. Palette is about to be optimized for better indexed image quality or taken "AS IS" when PaletteMiningMethod.UseCurrentPalette is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The raster image. |
| entries_count | int | The desired entries count. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | The palette mining method. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The color palette which starts with the most frequent colors from the _image_ and contains _entriesCount_ entries. |



**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Method: get_close_image_palette_by_method(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_by_method_image_entries_count_palette_mining_method_13}


```
 get_close_image_palette_by_method(image, entries_count, palette_mining_method) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. Palette is about to be optimized for better indexed image quality or taken "AS IS" when PaletteMiningMethod.UseCurrentPalette is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The raster image. |
| entries_count | int | The desired entries count. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | The palette mining method. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The color palette which starts with the most frequent colors from the _image_ and contains _entriesCount_ entries. |


### Method: get_close_image_palette_by_rect(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_by_rect_image_dest_bounds_entries_count_14}


```
 get_close_image_palette_by_rect(image, dest_bounds, entries_count) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The raster image. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds. |
| entries_count | int | The desired entries count. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The color palette which starts with the most frequent colors from the _image_ and contains _entriesCount_ entries. |


### Method: get_close_transparent_image_palette(image, entries_count)  [static] {#get_close_transparent_image_palette_image_entries_count_15}


```
 get_close_transparent_image_palette(image, entries_count) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The raster image. |
| entries_count | int | The desired entries count. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The color palette which starts with the most frequent colors from the _image_ and contains _entriesCount_ entries. |


### Method: get_downscale_palette(image)  [static] {#get_downscale_palette_image_16}


```
 get_downscale_palette(image) 
```

Get 256 color palette, composed from upper bits of initial image color values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The image. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | The [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_17}


```
 get_uniform_color_palette(image) 
```

Get uniform 256 color palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The image. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | The [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### Method: has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_18}


```
 has_transparent_colors(palette) 
```

Determines whether the specified palette has transparent colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The palette. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if the specified palette has transparent colors; otherwise, <c>false</c>. |


## **Examples**
### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Create a BMP image 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# The linear gradient from the left-top to the right-bottom corner of the image.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Fill the entire image with the linear gradient brush.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Get the closest 8-bit color palette which covers as many pixels as possible, so that a palettized image
	# is almost visually indistinguishable from a bmp without palette
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# 8-bit palette contains at most 256 colors.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# The output looks like this:
# The size of image with palette is 11078 bytes.
# The size of image without palette is 40054 bytes.

```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# Loads png image        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# Use indexed color type
	png_options.color_type = PngColorType.INDEXED_COLOR
	# Use maximal compression
	png_options.compression_level = 9
	# Get the closest 8-bit color palette, covering as many pixels as possible, so that an image
	# with palette is almost visually indistinguishable from an image without a palette.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# The output file size should be significantly reduced

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

	# Create BmpOptions
	saveOptions = BmpOptions()

	# Use 8 bits per pixel to reduce the size of the output image.
	saveOptions.bits_per_pixel = 8

	# Set the closest 8-bit color palette which covers the maximal number of image pixels, so that a palettized image
	# is almost visually indistinguishable from a non-palletized one.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# Save without compression.
	# You can also use RLE-8 compression to reduce the size of the output image.
	saveOptions.compression = BitmapCompression.RGB

	# Set the horizontal and vertical resolution to 96 dpi.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

