---
title: IColorPalette Class
type: docs
weight: 5170
url: /python-net/aspose.imaging/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorPalette

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Gets an array of 32-bit ARGB structures. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Gets an array of [Color](/imaging/python-net/aspose.imaging/color/) structures. |
| entries_count | int | r | Gets the entries count. |
| is_compact_palette | bool | r | Gets a value indicating whether compact palette is used. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Gets the 32-bit ARGB palette color by index. |
| [get_color(index)](#get_color_index_2) | Gets the palette color by index. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Gets the index of the nearest 32-bit ARGB color. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Gets the index of the nearest 32-bit ARGB color. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


```
 get_argb_32_color(index) 
```

Gets the 32-bit ARGB palette color by index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The 32-bit ARGB palette color index. |

**Returns**

| Type | Description |
| :- | :- |
| int | The color palette entry specified by the _index_. |


### Method: get_color(index) {#get_color_index_2}


```
 get_color(index) 
```

Gets the palette color by index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The palette color index. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | The color palette entry specified by the _index_. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Gets the index of the nearest 32-bit ARGB color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_32_color | int | The 32-bit ARGB color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The index of the nearest color. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Gets the index of the nearest 32-bit ARGB color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | The index of the nearest color. |


