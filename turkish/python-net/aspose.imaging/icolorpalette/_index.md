---
title: "IColorPalette Sınıfı"
type: docs
weight: 5210
url: /tr/python-net/aspose.imaging/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorPalette

## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | 32-bit ARGB yapılarının bir dizisini alır. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | [Color](/imaging/python-net/aspose.imaging/color/) yapılarının bir dizisini alır. |
| entries_count | int | r | Giriş sayısını alır. |
| is_compact_palette | bool | r | Kompakt paletin kullanılıp kullanılmadığını gösteren bir değer alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | İndeksle 32-bit ARGB palet rengini alır. |
| [get_color(index)](#get_color_index_2) | İndeksle palet rengini alır. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | En yakın 32-bit ARGB renginin indeksini alır. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | En yakın 32-bit ARGB renginin indeksini alır. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


```
 get_argb_32_color(index) 
```

İndeksle 32-bit ARGB palet rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| index | int | 32 bit ARGB palet renk indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | _index_ tarafından belirtilen renk paleti girişi. |


### Method: get_color(index) {#get_color_index_2}


```
 get_color(index) 
```

İndeksle palet rengini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| index | int | Palet renk indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | _index_ tarafından belirtilen renk paleti girişi. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

En yakın 32-bit ARGB renginin indeksini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_32_color | int | 32 bit ARGB renk. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | En yakın rengin indeksi. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

En yakın 32-bit ARGB renginin indeksini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | En yakın rengin indeksi. |


