---
title: ColorPalette Class
type: docs
weight: 110
url: /python-net/api-reference/aspose.imaging/colorpalette/
---

Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Namespace:** [aspose.imaging](/imaging/python-net/api-reference/aspose.imaging/)

**Full Class Name:** aspose.imaging.ColorPalette

**Assembly:**  Aspose.Imaging Version: 23.3.0

The ColorPalette type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|ColorPalette(argb_32_entries, is_compact_palette)|Initializes a new instance of the ColorPalette class|
|ColorPalette(argb_32_entries)|Initializes a new instance of the ColorPalette class|
|ColorPalette(entries, is_compact_palette)|Initializes a new instance of the ColorPalette class|
|ColorPalette(entries)|Initializes a new instance of the ColorPalette class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|entries_count|Gets the entries count.|
|argb_32_entries|Gets an array of 32-bit ARGB structures.|
|entries|Gets an array of [Color](/imaging/python-net/api-reference/aspose.imaging/color/) structures.|
|is_compact_palette|Gets or sets a value indicating whether compact palette is used.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|copy_palette(color_palette, use_compact_palette)|Copies the palette.|
|copy_palette(color_palette)|Copies the palette.|
|get_nearest_color_index(argb_32_color)|Gets the index of the nearest color.|
|get_nearest_color_index(color)|Gets the index of the nearest color.|
|create_with_argb_compact(argb_32_entries, is_compact_palette)|Initializes a new instance of the [ColorPalette](/imaging/python-net/api-reference/aspose.imaging/colorpalette/) class.|
|create_with_argb(argb_32_entries)|Initializes a new instance of the [ColorPalette](/imaging/python-net/api-reference/aspose.imaging/colorpalette/) class.|
|create_with_colors_compact(entries, is_compact_palette)|Initializes a new instance of the [ColorPalette](/imaging/python-net/api-reference/aspose.imaging/colorpalette/) class.|
|create_with_colors(entries)|Initializes a new instance of the [ColorPalette](/imaging/python-net/api-reference/aspose.imaging/colorpalette/) class.|
|get_nearest_argb_index(argb_32_color)|Gets the index of the nearest color.|
|get_argb_32_color(index)|Gets the 32-bit ARGB palette color by index.|
|get_color(index)|Gets the palette color by index.|
