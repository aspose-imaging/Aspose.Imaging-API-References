---
title: "IColorPalette klass"
type: docs
weight: 5210
url: /sv/python-net/aspose.imaging/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorPalette

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Hämtar en array av 32-bitars ARGB-strukturer. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Hämtar en array av [Color](/imaging/python-net/aspose.imaging/color/) strukturer. |
| entries_count | int | r | Hämtar antalet poster. |
| is_compact_palette | bool | r | Hämtar ett värde som indikerar om kompakt palett används. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Hämtar 32-bitars ARGB-palettfärgen efter index. |
| [get_color(index)](#get_color_index_2) | Hämtar palettfärgen efter index. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Hämtar indexet för den närmaste 32-bitars ARGB-färgen. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Hämtar indexet för den närmaste 32-bitars ARGB-färgen. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


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


### Method: get_color(index) {#get_color_index_2}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Hämtar indexet för den närmaste 32-bitars ARGB-färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| argb_32_color | int | Den 32-bitars ARGB-färgen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Indexet för den närmaste färgen. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Hämtar indexet för den närmaste 32-bitars ARGB-färgen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Indexet för den närmaste färgen. |


