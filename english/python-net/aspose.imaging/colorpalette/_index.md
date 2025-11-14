---
title: ColorPalette Class
type: docs
weight: 1190
url: /python-net/aspose.imaging/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPalette

**Inheritance:** IColorPalette

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class and IsCompactPalette is false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class. |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class and IsCompactPalette is false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Gets an array of 32-bit ARGB structures. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Gets an array of [Color](/imaging/python-net/aspose.imaging/color/) structures. |
| entries_count | int | r | Gets the entries count. |
| is_compact_palette | bool | r | Gets or sets a value indicating whether compact palette is used. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Copies the palette. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Copies the palette. |
| [create_with_argb(argb_32_entries)](#create_with_argb_argb_32_entries_3) | Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class and IsCompactPalette is false. |
| [create_with_argb_compact(argb_32_entries, is_compact_palette)](#create_with_argb_compact_argb_32_entries_is_compact_palette_4) | Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class. |
| [create_with_colors(entries)](#create_with_colors_entries_5) | Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class and IsCompactPalette is false. |
| [create_with_colors_compact(entries, is_compact_palette)](#create_with_colors_compact_entries_is_compact_palette_6) | Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class. |
| [get_argb_32_color(index)](#get_argb_32_color_index_7) | Gets the 32-bit ARGB palette color by index. |
| [get_color(index)](#get_color_index_8) | Gets the palette color by index. |
| [get_nearest_argb_index(argb_32_color)](#get_nearest_argb_index_argb_32_color_9) | Gets the index of the nearest color. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_10) | Gets the index of the nearest color. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_11) | Gets the index of the nearest color. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class and IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_32_entries | int[] | The 32-bit ARGB color palette entries. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_32_entries | int[] | The 32-bit ARGB color palette entries. |
| is_compact_palette | bool | Indicating whether compact it palette. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class and IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |
| is_compact_palette | bool | Indicating whether compact it palette. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Copies the palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The color palette. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | The newly created and copied palette or null if null palette passed. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Copies the palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The color palette. |
| use_compact_palette | bool | Indicating whether compact palette. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | The newly created and copied palette or null if null palette passed. |


### Method: create_with_argb(argb_32_entries)  [static] {#create_with_argb_argb_32_entries_3}


```
 create_with_argb(argb_32_entries) 
```

Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class and IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_32_entries | int[] | The 32-bit ARGB color palette entries. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_argb_compact(argb_32_entries, is_compact_palette)  [static] {#create_with_argb_compact_argb_32_entries_is_compact_palette_4}


```
 create_with_argb_compact(argb_32_entries, is_compact_palette) 
```

Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_32_entries | int[] | The 32-bit ARGB color palette entries. |
| is_compact_palette | bool | Indicating whether compact it palette. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors(entries)  [static] {#create_with_colors_entries_5}


```
 create_with_colors(entries) 
```

Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class and IsCompactPalette is false.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | The color palette entries. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors_compact(entries, is_compact_palette)  [static] {#create_with_colors_compact_entries_is_compact_palette_6}


```
 create_with_colors_compact(entries, is_compact_palette) 
```

Initializes a new instance of the [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | The color palette entries. |
| is_compact_palette | bool | Indicating whether compact it palette. |

**Returns**

| Type | Description |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_7}


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


### Method: get_color(index) {#get_color_index_8}


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


### Method: get_nearest_argb_index(argb_32_color) {#get_nearest_argb_index_argb_32_color_9}


```
 get_nearest_argb_index(argb_32_color) 
```

Gets the index of the nearest color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_32_color | int | The 32-bit ARGB color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The index of the nearest color. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_10}


```
 get_nearest_color_index(argb_32_color) 
```

Gets the index of the nearest color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| argb_32_color | int | The 32-bit ARGB color. |

**Returns**

| Type | Description |
| :- | :- |
| int | The index of the nearest color. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_11}


```
 get_nearest_color_index(color) 
```

Gets the index of the nearest color.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Type | Description |
| :- | :- |
| int | The index of the nearest color. |


