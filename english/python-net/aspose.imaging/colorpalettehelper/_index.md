---
title: ColorPaletteHelper Class
type: docs
weight: 120
url: /python-net/aspose.imaging/colorpalettehelper/
---

Helper class for color palettes manipulation.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.ColorPaletteHelper

**Assembly:**  Aspose.Imaging Version: 23.5.6

The ColorPaletteHelper type exposes the following members:
## **Methods**
|**Name**|**Description**|
| :- | :- |
|get_close_image_palette(image, entries_count)|Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.|
|get_close_image_palette(image, entries_count, palette_mining_method)|Gets color palette from raster image (palletizes image) in case the image does not have one. Palette is about to be optimized for better indexed image quality or taken "AS IS" when PaletteMiningMethod.UseCurrentPalette is used.|
|get_close_image_palette(image, dest_bounds, entries_count)|Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.|
|get_close_image_palette(image, dest_bounds, entries_count, use_image_palette)|Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.|
|get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color)|Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.|
|get_close_image_palette(image, dest_bounds, entries_count, use_image_palette, alpha_blend_in_color, keep_transparency)|Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.|
|create_monochrome()|Creates a monochrome color palette containing 2 colors only.|
|create_4_bit()|Creates the 4 bit color palette.|
|create_4_bit_grayscale(min_is_white)|Creates the 4 bit grayscale palette.|
|create_8_bit()|Creates the 8 bit color palette.|
|create_8_bit_grayscale(min_is_white)|Creates the 8 bit grayscale palette.|
|get_close_transparent_image_palette(image, entries_count)|Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.|
|get_close_image_palette_by_method(image, entries_count, palette_mining_method)|Gets color palette from raster image (palletizes image) in case the image does not have one. Palette is about to be optimized for better indexed image quality or taken "AS IS" when PaletteMiningMethod.UseCurrentPalette is used.|
|get_close_image_palette_by_rect(image, dest_bounds, entries_count)|Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.|
|get_uniform_color_palette(image)|Get uniform 256 color palette.|
|get_downscale_palette(image)|Get 256 color palette, composed from upper bits of initial image color values.|
|has_transparent_colors(palette)|Determines whether the specified palette has transparent colors.|
