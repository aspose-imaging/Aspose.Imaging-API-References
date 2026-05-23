---
title: "ColorPalette Sınıfı"
type: docs
weight: 1190
url: /tr/python-net/aspose.imaging/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPalette

**Inheritance:** IColorPalette

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır ve IsCompactPalette false'tur. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır. |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır ve IsCompactPalette false'tur. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | 32-bit ARGB yapılarının bir dizisini alır. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | [Color](/imaging/python-net/aspose.imaging/color/) yapılarının bir dizisini alır. |
| entries_count | int | r | Giriş sayısını alır. |
| is_compact_palette | bool | r | Kompakt paletin kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Paleti kopyalar. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Paleti kopyalar. |
| [create_with_argb(argb_32_entries)](#create_with_argb_argb_32_entries_3) | Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır ve IsCompactPalette false'tur. |
| [create_with_argb_compact(argb_32_entries, is_compact_palette)](#create_with_argb_compact_argb_32_entries_is_compact_palette_4) | Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır. |
| [create_with_colors(entries)](#create_with_colors_entries_5) | Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır ve IsCompactPalette false'tur. |
| [create_with_colors_compact(entries, is_compact_palette)](#create_with_colors_compact_entries_is_compact_palette_6) | Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır. |
| [get_argb_32_color(index)](#get_argb_32_color_index_7) | İndeksle 32-bit ARGB palet rengini alır. |
| [get_color(index)](#get_color_index_8) | İndeksle palet rengini alır. |
| [get_nearest_argb_index(argb_32_color)](#get_nearest_argb_index_argb_32_color_9) | En yakın rengin indeksini alır. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_10) | En yakın rengin indeksini alır. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_11) | En yakın rengin indeksini alır. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır ve IsCompactPalette false'tur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_32_entries | int[] | 32 bit ARGB renk paleti girişleri. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_32_entries | int[] | 32 bit ARGB renk paleti girişleri. |
| is_compact_palette | bool | Paletin sıkıştırılmış olup olmadığını gösterir. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır ve IsCompactPalette false'tur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |
| is_compact_palette | bool | Paletin sıkıştırılmış olup olmadığını gösterir. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Paleti kopyalar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Renk paleti. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Yeni oluşturulan ve kopyalanan palet veya null, eğer null palet geçilmişse. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Paleti kopyalar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Renk paleti. |
| use_compact_palette | bool | Sıkıştırılmış palet olup olmadığını gösterir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Yeni oluşturulan ve kopyalanan palet veya null, eğer null palet geçilmişse. |


### Method: create_with_argb(argb_32_entries)  [static] {#create_with_argb_argb_32_entries_3}


```
 create_with_argb(argb_32_entries) 
```

Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır ve IsCompactPalette false'tur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_32_entries | int[] | 32 bit ARGB renk paleti girişleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_argb_compact(argb_32_entries, is_compact_palette)  [static] {#create_with_argb_compact_argb_32_entries_is_compact_palette_4}


```
 create_with_argb_compact(argb_32_entries, is_compact_palette) 
```

Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_32_entries | int[] | 32 bit ARGB renk paleti girişleri. |
| is_compact_palette | bool | Paletin sıkıştırılmış olup olmadığını gösterir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors(entries)  [static] {#create_with_colors_entries_5}


```
 create_with_colors(entries) 
```

Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır ve IsCompactPalette false'tur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Renk paleti girişleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors_compact(entries, is_compact_palette)  [static] {#create_with_colors_compact_entries_is_compact_palette_6}


```
 create_with_colors_compact(entries, is_compact_palette) 
```

Yeni bir [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) sınıfı örneği başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Renk paleti girişleri. |
| is_compact_palette | bool | Paletin sıkıştırılmış olup olmadığını gösterir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_7}


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


### Method: get_color(index) {#get_color_index_8}


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


### Method: get_nearest_argb_index(argb_32_color) {#get_nearest_argb_index_argb_32_color_9}


```
 get_nearest_argb_index(argb_32_color) 
```

En yakın rengin indeksini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_32_color | int | 32 bit ARGB renk. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | En yakın rengin indeksi. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_10}


```
 get_nearest_color_index(argb_32_color) 
```

En yakın rengin indeksini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| argb_32_color | int | 32 bit ARGB renk. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | En yakın rengin indeksi. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_11}


```
 get_nearest_color_index(color) 
```

En yakın rengin indeksini alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | En yakın rengin indeksi. |


