---
title: "Класс IColorPalette"
type: docs
weight: 5210
url: /ru/python-net/aspose.imaging/icolorpalette/
---

**Summary:** The color palette interface.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IColorPalette

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_entries | int[] | r | Возвращает массив 32-битных структур ARGB. |
| entries | [Color[]](/imaging/python-net/aspose.imaging/color/) | r | Возвращает массив структур [Color](/imaging/python-net/aspose.imaging/color/). |
| entries_count | int | r | Возвращает количество элементов. |
| is_compact_palette | bool | r | Возвращает значение, указывающее, используется ли компактная палитра. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_argb_32_color(index)](#get_argb_32_color_index_1) | Возвращает 32-битный цвет палитры ARGB по индексу. |
| [get_color(index)](#get_color_index_2) | Возвращает цвет палитры по индексу. |
| [get_nearest_color_index(argb_32_color)](#get_nearest_color_index_argb_32_color_3) | Возвращает индекс ближайшего 32-битного цвета ARGB. |
| [get_nearest_color_index(color)](#get_nearest_color_index_color_4) | Возвращает индекс ближайшего 32-битного цвета ARGB. |


### Method: get_argb_32_color(index) {#get_argb_32_color_index_1}


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


### Method: get_color(index) {#get_color_index_2}


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


### Method: get_nearest_color_index(argb_32_color) {#get_nearest_color_index_argb_32_color_3}


```
 get_nearest_color_index(argb_32_color) 
```

Возвращает индекс ближайшего 32-битного цвета ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| argb_32_color | int | 32-битовый цвет ARGB. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Индекс ближайшего цвета. |


### Method: get_nearest_color_index(color) {#get_nearest_color_index_color_4}


```
 get_nearest_color_index(color) 
```

Возвращает индекс ближайшего 32-битного цвета ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Индекс ближайшего цвета. |


