---
title: "Класс ColorPalette"
type: docs
weight: 1190
url: /ru/python-net/aspose.imaging/colorpalette/
---

**Summary:** Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ColorPalette

**Inheritance:** IColorPalette

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorPalette(argb_32_entries)](#ColorPalette_argb_32_entries_1) | Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) и устанавливает IsCompactPalette в false. |
| [ColorPalette(argb_32_entries, is_compact_palette)](#ColorPalette_argb_32_entries_is_compact_palette_2) | Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [ColorPalette(entries)](#ColorPalette_entries_3) | Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) и устанавливает IsCompactPalette в false. |
| [ColorPalette(entries, is_compact_palette)](#ColorPalette_entries_is_compact_palette_4) | Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Возвращает массив 32-битных структур ARGB. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Возвращает массив структур [Color](/imaging/python-net/aspose.imaging/color/). |
| entries_count | int | r | Возвращает количество элементов. |
| is_compact_palette | bool | r | Возвращает или задает значение, указывающее, используется ли компактная палитра. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_palette(color_palette)](#copy_palette_color_palette_1) | Копирует палитру. |
| [copy_palette(color_palette, use_compact_palette)](#copy_palette_color_palette_use_compact_palette_2) | Копирует палитру. |
| [create_with_argb(argb_32_entries)](#create_with_argb_argb_32_entries_3) | Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) и устанавливает IsCompactPalette в false. |
| [create_with_argb_compact(argb_32_entries, is_compact_palette)](#create_with_argb_compact_argb_32_entries_is_compact_palette_4) | Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [create_with_colors(entries)](#create_with_colors_entries_5) | Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) и устанавливает IsCompactPalette в false. |
| [create_with_colors_compact(entries, is_compact_palette)](#create_with_colors_compact_entries_is_compact_palette_6) | Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/). |
| [get_argb_32_color(index)](#get_argb_32_color_index_7) | Возвращает 32-битный цвет палитры ARGB по индексу. |
| [get_color(index)](#get_color_index_8) | Возвращает цвет палитры по индексу. |
| [get_nearest_argb_index(argb_32_color)](#get_nearest_argb_index_argb_32_color_9) | Возвращает индекс ближайшего цвета. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_10) | Возвращает индекс ближайшего цвета. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_11) | Возвращает индекс ближайшего цвета. |


### Constructor: ColorPalette(argb_32_entries) {#ColorPalette_argb_32_entries_1}


```
 ColorPalette(argb_32_entries) 
```

Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) и устанавливает IsCompactPalette в false.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_32_entries | int[] | Записи 32-битовой цветовой палитры ARGB. |

### Constructor: ColorPalette(argb_32_entries, is_compact_palette) {#ColorPalette_argb_32_entries_is_compact_palette_2}


```
 ColorPalette(argb_32_entries, is_compact_palette) 
```

Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_32_entries | int[] | Записи 32-битовой цветовой палитры ARGB. |
| is_compact_palette | bool | Указывает, является ли палитра компактной. |

### Constructor: ColorPalette(entries) {#ColorPalette_entries_3}


```
 ColorPalette(entries) 
```

Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) и устанавливает IsCompactPalette в false.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |

### Constructor: ColorPalette(entries, is_compact_palette) {#ColorPalette_entries_is_compact_palette_4}


```
 ColorPalette(entries, is_compact_palette) 
```

Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) |  |
| is_compact_palette | bool | Указывает, является ли палитра компактной. |

### Method: copy_palette(color_palette)  [static] {#copy_palette_color_palette_1}


```
 copy_palette(color_palette) 
```

Копирует палитру.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Цветовая палитра. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Новосозданная и скопированная палитра или null, если передана null палитра. |


### Method: copy_palette(color_palette, use_compact_palette)  [static] {#copy_palette_color_palette_use_compact_palette_2}


```
 copy_palette(color_palette, use_compact_palette) 
```

Копирует палитру.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Цветовая палитра. |
| use_compact_palette | bool | Указывает, является ли палитра компактной. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Новосозданная и скопированная палитра или null, если передана null палитра. |


### Method: create_with_argb(argb_32_entries)  [static] {#create_with_argb_argb_32_entries_3}


```
 create_with_argb(argb_32_entries) 
```

Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) и устанавливает IsCompactPalette в false.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_32_entries | int[] | Записи 32-битовой цветовой палитры ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_argb_compact(argb_32_entries, is_compact_palette)  [static] {#create_with_argb_compact_argb_32_entries_is_compact_palette_4}


```
 create_with_argb_compact(argb_32_entries, is_compact_palette) 
```

Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_32_entries | int[] | Записи 32-битовой цветовой палитры ARGB. |
| is_compact_palette | bool | Указывает, является ли палитра компактной. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors(entries)  [static] {#create_with_colors_entries_5}


```
 create_with_colors(entries) 
```

Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) и устанавливает IsCompactPalette в false.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Записи цветовой палитры. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: create_with_colors_compact(entries, is_compact_palette)  [static] {#create_with_colors_compact_entries_is_compact_palette_6}


```
 create_with_colors_compact(entries, is_compact_palette) 
```

Инициализирует новый экземпляр класса [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | Записи цветовой палитры. |
| is_compact_palette | bool | Указывает, является ли палитра компактной. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) |  |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_7}


```
 get_argb_32_color(index) 
```

Возвращает 32-битный цвет палитры ARGB по индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | Индекс цвета палитры 32-битового ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Запись цветовой палитры, указанная по _index_. |


### Method: get_color(index) {#get_color_index_8}


```
 get_color(index) 
```

Возвращает цвет палитры по индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | Индекс цвета палитры. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Запись цветовой палитры, указанная по _index_. |


### Method: get_nearest_argb_index(argb_32_color) {#get_nearest_argb_index_argb_32_color_9}


```
 get_nearest_argb_index(argb_32_color) 
```

Возвращает индекс ближайшего цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_32_color | int | 32-битовый цвет ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Индекс ближайшего цвета. |


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_10}


```
 get_nearest_color_index(argb_32_color) 
```

Возвращает индекс ближайшего цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_32_color | int | 32-битовый цвет ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Индекс ближайшего цвета. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_11}


```
 get_nearest_color_index(color) 
```

Возвращает индекс ближайшего цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Индекс ближайшего цвета. |


