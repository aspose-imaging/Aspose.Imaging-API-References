---
title: ColorPaletteHelper Class
type: docs
weight: 1190
url: /python-net/aspose.imaging/colorpalettehelper/
---

Helper class for color palettes manipulation.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPaletteHelper

**Aspose.Imaging Version:** 23.6

The ColorPaletteHelper type exposes the following members:
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_close_image_palette(image, entries_count)](#get_close_image_palette_image_entries_count_0) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_image_palette(image, entries_count, palette_mining_method)](#get_close_image_palette_image_entries_count_palette_mining_method_1) | Gets color palette from raster image (palletizes image) in case the image does not have one. Palette is about to be optimized for better indexed image quality or taken "AS IS" when PaletteMiningMethod.UseCurrentPalette is used. |
| [get_close_image_palette(image, dest_bounds, entries_count)](#get_close_image_palette_image_dest_bounds_entries_count_2) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_3) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_4) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)](#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_5) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [create_monochrome()](#create_monochrome__6) | Creates a monochrome color palette containing 2 colors only. |
| [create_4_bit()](#create_4_bit__7) | Creates the 4 bit color palette. |
| [create_4_bit_grayscale(min_is_white)](#create_4_bit_grayscale_min_is_white_8) | Creates the 4 bit grayscale palette. |
| [create_8_bit()](#create_8_bit__9) | Creates the 8 bit color palette. |
| [create_8_bit_grayscale(min_is_white)](#create_8_bit_grayscale_min_is_white_10) | Creates the 8 bit grayscale palette. |
| [get_close_transparent_image_palette(image, entries_count)](#get_close_transparent_image_palette_image_entries_count_11) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_close_image_palette_by_method(image, entries_count, palette_mining_method)](#get_close_image_palette_by_method_image_entries_count_palette_mining_method_12) | Gets color palette from raster image (palletizes image) in case the image does not have one. Palette is about to be optimized for better indexed image quality or taken "AS IS" when PaletteMiningMethod.UseCurrentPalette is used. |
| [get_close_image_palette_by_rect(image, dest_bounds, entries_count)](#get_close_image_palette_by_rect_image_dest_bounds_entries_count_13) | Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations. |
| [get_uniform_color_palette(image)](#get_uniform_color_palette_image_14) | Get uniform 256 color palette. |
| [get_downscale_palette(image)](#get_downscale_palette_image_15) | Get 256 color palette, composed from upper bits of initial image color values. |
| [has_transparent_colors(palette)](#has_transparent_colors_palette_16) | Determines whether the specified palette has transparent colors. |

### get_close_image_palette(image, entries_count)  [static] {#get_close_image_palette_image_entries_count_0}


```
 get_close_image_palette(image, entries_count) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |
| entries_count | int | The desired entries count. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The color palette which starts with the most frequent colors from the <paramref name="image" /> and contains <paramref name="entriesCount" /> entries. |


### get_close_image_palette(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_image_entries_count_palette_mining_method_1}


```
 get_close_image_palette(image, entries_count, palette_mining_method) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. Palette is about to be optimized for better indexed image quality or taken "AS IS" when PaletteMiningMethod.UseCurrentPalette is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |
| entries_count | int | The desired entries count. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod) | The palette mining method. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The color palette which starts with the most frequent colors from the <paramref name="image" /> and contains <paramref name="entriesCount" /> entries. |


### get_close_image_palette(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_2}


```
 get_close_image_palette(image, dest_bounds, entries_count) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds. |
| entries_count | int | The desired entries count. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The color palette which starts with the most frequent colors from the <paramref name="image" /> and contains <paramref name="entriesCount" /> entries. |


### get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_3}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds. |
| entries_count | int | The desired entries count. |
| use_image_palette | bool | If set, it will use its own image palette if available |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The color palette which starts with the most frequent colors from the <paramref name="image" /> and contains <paramref name="entriesCount" /> entries. |


### get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_4}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds. |
| entries_count | int | The desired entries count. |
| use_image_palette | bool | If set, it will use its own image palette if available |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color) | The color that should be used as a background color for semi-transparent alpha replacement. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The color palette which starts with the most frequent colors from the <paramref name="image" /> and contains <paramref name="entriesCount" /> entries. |


### get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)  [static] {#get_close_image_palette_image_dest_bounds_entries_count_use_image_palette_alpha_blend_in_color_keep_transparency_5}


```
 get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds. |
| entries_count | int | The desired entries count. |
| use_image_palette | bool | If set, it will use its own image palette if available |
| alpha_blend_in_color | [Color](/imaging/python-net/aspose.imaging/color) | The color that should be used as a background color for semi-transparent alpha replacement. |
| keep_transparency | bool | If set, it will consider alpha channel bits of the image colors. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The color palette which starts with the most frequent colors from the <paramref name="image" /> and contains <paramref name="entriesCount" /> entries. |


### create_monochrome()  [static] {#create_monochrome__6}


```
 create_monochrome() 
```

Creates a monochrome color palette containing 2 colors only.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | Color palette for monochrome images. |


### create_4_bit()  [static] {#create_4_bit__7}


```
 create_4_bit() 
```

Creates the 4 bit color palette.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The 4 bit color palette. |


### create_4_bit_grayscale(min_is_white)  [static] {#create_4_bit_grayscale_min_is_white_8}


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
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The 4 bit grayscale palette. |


### create_8_bit()  [static] {#create_8_bit__9}


```
 create_8_bit() 
```

Creates the 8 bit color palette.

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The 8 bit color palette. |


### create_8_bit_grayscale(min_is_white)  [static] {#create_8_bit_grayscale_min_is_white_10}


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
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The 8 bit grayscale palette. |


### get_close_transparent_image_palette(image, entries_count)  [static] {#get_close_transparent_image_palette_image_entries_count_11}


```
 get_close_transparent_image_palette(image, entries_count) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |
| entries_count | int | The desired entries count. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The color palette which starts with the most frequent colors from the <paramref name="image" /> and contains <paramref name="entriesCount" /> entries. |


### get_close_image_palette_by_method(image, entries_count, palette_mining_method)  [static] {#get_close_image_palette_by_method_image_entries_count_palette_mining_method_12}


```
 get_close_image_palette_by_method(image, entries_count, palette_mining_method) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. Palette is about to be optimized for better indexed image quality or taken "AS IS" when PaletteMiningMethod.UseCurrentPalette is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |
| entries_count | int | The desired entries count. |
| palette_mining_method | [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod) | The palette mining method. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The color palette which starts with the most frequent colors from the <paramref name="image" /> and contains <paramref name="entriesCount" /> entries. |


### get_close_image_palette_by_rect(image, dest_bounds, entries_count)  [static] {#get_close_image_palette_by_rect_image_dest_bounds_entries_count_13}


```
 get_close_image_palette_by_rect(image, dest_bounds, entries_count) 
```

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |
| dest_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds. |
| entries_count | int | The desired entries count. |

**Returns**

| Type | Description |
| :- | :- |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The color palette which starts with the most frequent colors from the <paramref name="image" /> and contains <paramref name="entriesCount" /> entries. |


### get_uniform_color_palette(image)  [static] {#get_uniform_color_palette_image_14}


```
 get_uniform_color_palette(image) 
```

Get uniform 256 color palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The image. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette) | The [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### get_downscale_palette(image)  [static] {#get_downscale_palette_image_15}


```
 get_downscale_palette(image) 
```

Get 256 color palette, composed from upper bits of initial image color values.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The image. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette) | The [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |


### has_transparent_colors(palette)  [static] {#has_transparent_colors_palette_16}


```
 has_transparent_colors(palette) 
```

Determines whether the specified palette has transparent colors.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The palette. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if the specified palette has transparent colors; otherwise, <c>false</c>. |


