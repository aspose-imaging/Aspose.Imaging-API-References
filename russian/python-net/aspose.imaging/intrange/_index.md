---
title: "Класс IntRange"
type: docs
weight: 5810
url: /ru/python-net/aspose.imaging/intrange/
---

**Summary:** Class for representing sequence of elements

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.IntRange

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [IntRange(range)](#IntRange_range_1) | Инициализирует новый экземпляр класса [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| [IntRange(start, count)](#IntRange_start_count_2) | Инициализирует новый экземпляр класса [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
| [IntRange(start, count, delta)](#IntRange_start_count_delta_3) | Инициализирует новый экземпляр класса [IntRange](/imaging/python-net/aspose.imaging/intrange/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| диапазон | int[] | r/w | Получает или задает диапазон. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_array_one_item_from_index(index)](#get_array_one_item_from_index_index_1) | Возвращает массив из одного элемента по указанному индексу. |
| [get_range(start, count, delta)](#get_range_start_count_delta_2) | Получает диапазон количества целочисленных элементов, начиная с start. |


### Constructor: IntRange(range) {#IntRange_range_1}


```
 IntRange(range) 
```

Инициализирует новый экземпляр класса [IntRange](/imaging/python-net/aspose.imaging/intrange/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| диапазон | int[] | Диапазон. |

### Constructor: IntRange(start, count) {#IntRange_start_count_2}


```
 IntRange(start, count) 
```

Инициализирует новый экземпляр класса [IntRange](/imaging/python-net/aspose.imaging/intrange/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| начало | int | Начало. |
| count | int | Количество. |

### Constructor: IntRange(start, count, delta) {#IntRange_start_count_delta_3}


```
 IntRange(start, count, delta) 
```

Инициализирует новый экземпляр класса [IntRange](/imaging/python-net/aspose.imaging/intrange/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| начало | int | Начало. |
| count | int | Количество. |
| дельта | int | Дельта. |

### Method: get_array_one_item_from_index(index) {#get_array_one_item_from_index_index_1}


```
 get_array_one_item_from_index(index) 
```

Возвращает массив из одного элемента по указанному индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | int | Индекс диапазона. |

**Returns**

| Тип | Описание |
| :- | :- |
| int[] | Массив строк |


### Method: get_range(start, count, delta)  [static] {#get_range_start_count_delta_2}


```
 get_range(start, count, delta) 
```

Получает диапазон количества целочисленных элементов, начиная с start.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| начало | int | Начало. |
| count | int | Количество. |
| дельта | int | Дельта. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.IEnumerable`1[[System.Int32]] | Массив элементов |


