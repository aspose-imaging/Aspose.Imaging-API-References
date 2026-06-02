---
title: "IColorPalette 类"
type: docs
weight: 5210
url: /zh/python-net/aspose.imaging/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorPalette

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | 获取 32 位 ARGB 结构的数组。 |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | 获取 [Color](/imaging/python-net/aspose.imaging/color/) 结构的数组。 |
| entries_count | int | r | 获取条目计数。 |
| is_compact_palette | bool | r | 获取一个值，指示是否使用紧凑调色板。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | 按索引获取 32 位 ARGB 调色板颜色。 |
| [get_color(index)](#get_color_index_2) | 按索引获取调色板颜色。 |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | 获取最近的 32 位 ARGB 颜色的索引。 |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | 获取最近的 32 位 ARGB 颜色的索引。 |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


```
 get_argb_32_color(index) 
```

按索引获取 32 位 ARGB 调色板颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| index | int | 32 位 ARGB 调色板颜色索引。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 由 _index_ 指定的颜色调色板条目。 |


### Method: get_color(index) {#get_color_index_2}


```
 get_color(index) 
```

按索引获取调色板颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| index | int | 调色板颜色索引。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | 由 _index_ 指定的颜色调色板条目。 |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

获取最近的 32 位 ARGB 颜色的索引。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_32_color | int | 32 位 ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 最近颜色的索引。 |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

获取最近的 32 位 ARGB 颜色的索引。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | 最近颜色的索引。 |


