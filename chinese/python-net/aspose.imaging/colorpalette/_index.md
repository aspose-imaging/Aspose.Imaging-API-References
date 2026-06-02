---
title: "ColorPalette 类"
type: docs
weight: 1190
url: /zh/python-net/aspose.imaging/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPalette

**Inheritance:** IColorPalette

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | 初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例，并且 IsCompactPalette 为 false。 |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | 初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例。 |
| [ColorPalette(entries)](#ColorPalette_entries_3) | 初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例，并且 IsCompactPalette 为 false。 |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | 初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | 获取 32 位 ARGB 结构的数组。 |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | 获取 [Color](/imaging/python-net/aspose.imaging/color/) 结构的数组。 |
| entries_count | int | r | 获取条目计数。 |
| is_compact_palette | bool | r | 获取或设置一个值，指示是否使用紧凑调色板。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | 复制调色板。 |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | 复制调色板。 |
| [create_with_argb(argb_32_entries)](#create_with_argb_argb_32_entries_3) | 初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例，并且 IsCompactPalette 为 false。 |
| [create_with_argb_compact(argb_32_entries, is_compact_palette)](#create_with_argb_compact_argb_32_entries_is_compact_palette_4) | 初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例。 |
| [create_with_colors(entries)](#create_with_colors_entries_5) | 初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例，并且 IsCompactPalette 为 false。 |
| [create_with_colors_compact(entries, is_compact_palette)](#create_with_colors_compact_entries_is_compact_palette_6) | 初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例。 |
| [get_argb_32_color(index)](#get_argb_32_color_index_7) | 按索引获取 32 位 ARGB 调色板颜色。 |
| [get_color(index)](#get_color_index_8) | 按索引获取调色板颜色。 |
| [get_nearest_argb_index(argb_32_color)](#get_nearest_argb_index_argb_32_color_9) | 获取最近颜色的索引。 |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_10) | 获取最近颜色的索引。 |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_11) | 获取最近颜色的索引。 |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例，并且 IsCompactPalette 为 false。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_32_entries | int[] | 32 位 ARGB 颜色调色板条目。 |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_32_entries | int[] | 32 位 ARGB 颜色调色板条目。 |
| is_compact_palette | bool | 指示调色板是否紧凑。 |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例，并且 IsCompactPalette 为 false。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |
| is_compact_palette | bool | 指示调色板是否紧凑。 |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

复制调色板。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 颜色调色板。 |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | 如果传入空调色板，则返回新创建和复制的调色板，否则为 null。 |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

复制调色板。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 颜色调色板。 |
| use_compact_palette | bool | 指示调色板是否紧凑。 |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | 如果传入空调色板，则返回新创建和复制的调色板，否则为 null。 |


### Method: create_with_argb(argb_32_entries)  [static] {#create_with_argb_argb_32_entries_3}


```
 create_with_argb(argb_32_entries) 
```

初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例，并且 IsCompactPalette 为 false。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_32_entries | int[] | 32 位 ARGB 颜色调色板条目。 |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_argb_compact(argb_32_entries, is_compact_palette)  [static] {#create_with_argb_compact_argb_32_entries_is_compact_palette_4}


```
 create_with_argb_compact(argb_32_entries, is_compact_palette) 
```

初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_32_entries | int[] | 32 位 ARGB 颜色调色板条目。 |
| is_compact_palette | bool | 指示调色板是否紧凑。 |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors(entries)  [static] {#create_with_colors_entries_5}


```
 create_with_colors(entries) 
```

初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例，并且 IsCompactPalette 为 false。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | 颜色调色板条目。 |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors_compact(entries, is_compact_palette)  [static] {#create_with_colors_compact_entries_is_compact_palette_6}


```
 create_with_colors_compact(entries, is_compact_palette) 
```

初始化 [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | 颜色调色板条目。 |
| is_compact_palette | bool | 指示调色板是否紧凑。 |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_7}


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


### Method: get_color(index) {#get_color_index_8}


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


### Method: get_nearest_argb_index(argb_32_color) {#get_nearest_argb_index_argb_32_color_9}


```
 get_nearest_argb_index(argb_32_color) 
```

获取最近颜色的索引。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_32_color | int | 32 位 ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 最近颜色的索引。 |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_10}


```
 get_nearest_color_index(argb_32_color) 
```

获取最近颜色的索引。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| argb_32_color | int | 32 位 ARGB 颜色。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 最近颜色的索引。 |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_11}


```
 get_nearest_color_index(color) 
```

获取最近颜色的索引。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | 最近颜色的索引。 |


