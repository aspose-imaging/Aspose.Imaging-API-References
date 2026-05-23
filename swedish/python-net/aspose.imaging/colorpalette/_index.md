---
title: "ColorPalette-klass"
type: docs
weight: 1190
url: /sv/python-net/aspose.imaging/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPalette

**Inheritance:** IColorPalette

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen och IsCompactPalette är falskt. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen. |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen och IsCompactPalette är falskt. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Hämtar en array av 32-bitars ARGB-strukturer. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Hämtar en array av [Color](/imaging/python-net/aspose.imaging/color/) strukturer. |
| entries_count | int | r | Hämtar antalet poster. |
| is_compact_palette | bool | r | Hämtar eller anger ett värde som indikerar om kompakt palett används. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Kopierar paletten. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Kopierar paletten. |
| [create_with_argb(argb_32_entries)](#create_with_argb_argb_32_entries_3) | Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen och IsCompactPalette är falskt. |
| [create_with_argb_compact(argb_32_entries, is_compact_palette)](#create_with_argb_compact_argb_32_entries_is_compact_palette_4) | Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen. |
| [create_with_colors(entries)](#create_with_colors_entries_5) | Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen och IsCompactPalette är falskt. |
| [create_with_colors_compact(entries, is_compact_palette)](#create_with_colors_compact_entries_is_compact_palette_6) | Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen. |
| [get_argb_32_color(index)](#get_argb_32_color_index_7) | Hämtar 32-bitars ARGB-palettfärgen efter index. |
| [get_color(index)](#get_color_index_8) | Hämtar palettfärgen efter index. |
| [get_nearest_argb_index(argb_32_color)](#get_nearest_argb_index_argb_32_color_9) | Hämtar index för den närmaste färgen. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_10) | Hämtar index för den närmaste färgen. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_11) | Hämtar index för den närmaste färgen. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen och IsCompactPalette är falskt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_32_entries | int[] | De 32-bitars ARGB-färgpalettposterna. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_32_entries | int[] | De 32-bitars ARGB-färgpalettposterna. |
| is_compact_palette | bool | Anger om paletten är kompakt. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen och IsCompactPalette är falskt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |
| is_compact_palette | bool | Anger om paletten är kompakt. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Kopierar paletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Den nyss skapade och kopierade paletten eller null om en null-palett skickas. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Kopierar paletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten. |
| use_compact_palette | bool | Anger om paletten är kompakt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Den nyss skapade och kopierade paletten eller null om en null-palett skickas. |


### Method: create_with_argb(argb_32_entries)  [static] {#create_with_argb_argb_32_entries_3}


```
 create_with_argb(argb_32_entries) 
```

Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen och IsCompactPalette är falskt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_32_entries | int[] | De 32-bitars ARGB-färgpalettposterna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_argb_compact(argb_32_entries, is_compact_palette)  [static] {#create_with_argb_compact_argb_32_entries_is_compact_palette_4}


```
 create_with_argb_compact(argb_32_entries, is_compact_palette) 
```

Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_32_entries | int[] | De 32-bitars ARGB-färgpalettposterna. |
| is_compact_palette | bool | Anger om paletten är kompakt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors(entries)  [static] {#create_with_colors_entries_5}


```
 create_with_colors(entries) 
```

Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen och IsCompactPalette är falskt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Färgpalettposterna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors_compact(entries, is_compact_palette)  [static] {#create_with_colors_compact_entries_is_compact_palette_6}


```
 create_with_colors_compact(entries, is_compact_palette) 
```

Initierar en ny instans av [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Färgpalettposterna. |
| is_compact_palette | bool | Anger om paletten är kompakt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_7}


```
 get_argb_32_color(index) 
```

Hämtar 32-bitars ARGB-palettfärgen efter index.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Det 32-bitars ARGB-palettfärgindexet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Färgpalettposten som anges av _index_. |


### Method: get_color(index) {#get_color_index_8}


```
 get_color(index) 
```

Hämtar palettfärgen efter index.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Palettfärgindexet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Färgpalettposten som anges av _index_. |


### Method: get_nearest_argb_index(argb_32_color) {#get_nearest_argb_index_argb_32_color_9}


```
 get_nearest_argb_index(argb_32_color) 
```

Hämtar index för den närmaste färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_32_color | int | Den 32-bitars ARGB-färgen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Indexet för den närmaste färgen. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_10}


```
 get_nearest_color_index(argb_32_color) 
```

Hämtar index för den närmaste färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_32_color | int | Den 32-bitars ARGB-färgen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Indexet för den närmaste färgen. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_11}


```
 get_nearest_color_index(color) 
```

Hämtar index för den närmaste färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Indexet för den närmaste färgen. |


