---
title: "IntRange"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс для представления последовательности элементов"
type: docs
weight: 64
url: /ru/java/com.aspose.imaging/intrange/
---
**Inheritance:**
java.lang.Object
```
public class IntRange
```

Класс для представления последовательности элементов
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [IntRange(int start, int count)](#IntRange-int-int-) | Инициализирует новый экземпляр класса `IntRange`. |
| [IntRange(int start, int count, int delta)](#IntRange-int-int-int-) | Инициализирует новый экземпляр класса `IntRange`. |
| [IntRange(int[] range)](#IntRange-int---) | Инициализирует новый экземпляр класса `IntRange`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRange()](#getRange--) | Получает диапазон. |
| [setRange(int[] value)](#setRange-int---) | Устанавливает диапазон. |
| [getArrayOneItemFromIndex(int index)](#getArrayOneItemFromIndex-int-) | Возвращает массив из одного элемента по указанному индексу |
| [getRange(int start, int count, int delta)](#getRange-int-int-int-) | Получает диапазон количества элементов типа int, начиная с start |
### IntRange(int start, int count) {#IntRange-int-int-}
```
public IntRange(int start, int count)
```


Инициализирует новый экземпляр класса `IntRange`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| start | int | Начало. |
| count | int | Количество. |

### IntRange(int start, int count, int delta) {#IntRange-int-int-int-}
```
public IntRange(int start, int count, int delta)
```


Инициализирует новый экземпляр класса `IntRange`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| start | int | Начало. |
| count | int | Количество. |
| delta | int | Дельта. |

### IntRange(int[] range) {#IntRange-int---}
```
public IntRange(int[] range)
```


Инициализирует новый экземпляр класса `IntRange`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| range | int[] | Диапазон. |

### getRange() {#getRange--}
```
public int[] getRange()
```


Получает диапазон.

**Returns:**
int[] - Диапазон.
### setRange(int[] value) {#setRange-int---}
```
public void setRange(int[] value)
```


Устанавливает диапазон.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] | Диапазон. |

### getArrayOneItemFromIndex(int index) {#getArrayOneItemFromIndex-int-}
```
public int[] getArrayOneItemFromIndex(int index)
```


Возвращает массив из одного элемента по указанному индексу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс диапазона. |

**Returns:**
int[] - Массив `System.Int32`
### getRange(int start, int count, int delta) {#getRange-int-int-int-}
```
public static int[] getRange(int start, int count, int delta)
```


Получает диапазон количества элементов типа int, начиная с start

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| start | int | Начало. |
| count | int | Количество. |
| delta | int | Дельта. |

**Returns:**
int[] - Массив элементов
