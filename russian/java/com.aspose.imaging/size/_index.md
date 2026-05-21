---
title: "Size"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет размер."
type: docs
weight: 104
url: /ru/java/com.aspose.imaging/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Представляет размер.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.imaging.Point-) | Инициализирует новый экземпляр структуры `Aspose.Imaging.Size` из указанного `Aspose.Imaging.Point`. |
| [Size(int width, int height)](#Size-int-int-) | Инициализирует новый экземпляр структуры `Aspose.Imaging.Size` из указанных размеров. |
## Методы

| Метод | Описание |
| --- | --- |
| [getEmpty()](#getEmpty--) | Возвращает новый экземпляр структуры `Aspose.Imaging.Size`, у которого значения `Aspose.Imaging.Size.Width` и `Aspose.Imaging.Size.Height` установлены в ноль. |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.imaging.Size-) | Преобразует указанный `Aspose.Imaging.Size` в `Aspose.Imaging.SizeF`. |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Добавляет ширину и высоту одной структуры `Aspose.Imaging.Size` к ширине и высоте другой структуры `Aspose.Imaging.Size`. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Вычитает ширину и высоту одной структуры `Aspose.Imaging.Size` из ширины и высоты другой структуры `Aspose.Imaging.Size`. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Проверяет, равны ли две структуры `Aspose.Imaging.Size`. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Проверяет, различаются ли две структуры `Aspose.Imaging.Size`. |
| [to_Point(Size size)](#to-Point-com.aspose.imaging.Size-) | Преобразует указанный `Aspose.Imaging.Size` в `Aspose.Imaging.Point`. |
| [add(Size size1, Size size2)](#add-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Добавляет ширину и высоту одной структуры `Aspose.Imaging.Size` к ширине и высоте другой структуры `Aspose.Imaging.Size`. |
| [ceiling(SizeF size)](#ceiling-com.aspose.imaging.SizeF-) | Преобразует указанную структуру `Aspose.Imaging.SizeF` в структуру `Aspose.Imaging.Size`, округляя значения до следующего большего целого. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Вычитает ширину и высоту одной структуры `Aspose.Imaging.Size` из ширины и высоты другой структуры `Aspose.Imaging.Size`. |
| [truncate(SizeF size)](#truncate-com.aspose.imaging.SizeF-) | Преобразует указанную структуру `Aspose.Imaging.SizeF` в структуру `Aspose.Imaging.Size`, отбрасывая дробную часть и приводя значения к следующему меньшему целому. |
| [round(SizeF size)](#round-com.aspose.imaging.SizeF-) | Преобразует указанную структуру `Aspose.Imaging.SizeF` в структуру `Aspose.Imaging.Size`, округляя значения до ближайшего целого числа. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-) |  |
| [isEmpty()](#isEmpty--) | Возвращает значение, указывающее, имеет ли данный `Aspose.Imaging.Size` нулевую ширину и высоту. |
| [getWidth()](#getWidth--) | Получает или задает горизонтальную компоненту данного `Aspose.Imaging.Size`. |
| [setWidth(int value)](#setWidth-int-) | Получает или задает горизонтальную компоненту данного `Aspose.Imaging.Size`. |
| [getHeight()](#getHeight--) | Получает или задает вертикальную компоненту этого `Aspose.Imaging.Size`. |
| [setHeight(int value)](#setHeight-int-) | Получает или задает вертикальную компоненту этого `Aspose.Imaging.Size`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, является ли указанный объект `Aspose.Imaging.Size` с теми же размерами, что и этот `Aspose.Imaging.Size`. |
| [hashCode()](#hashCode--) | Возвращает хеш‑код для этой структуры `Aspose.Imaging.Size`. |
| [toString()](#toString--) | Создаёт человекочитаемую строку, представляющую этот `Aspose.Imaging.Size`. |
| [CloneTo(Size that)](#CloneTo-com.aspose.imaging.Size-) |  |
| [Clone()](#Clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.imaging.Point-}
```
public Size(Point point)
```


Инициализирует новый экземпляр структуры `Aspose.Imaging.Size` из указанного `Aspose.Imaging.Point`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Объект `Aspose.Imaging.Point`, из которого инициализируется этот `Aspose.Imaging.Size`. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Инициализирует новый экземпляр структуры `Aspose.Imaging.Size` из указанных размеров.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Компонент ширины нового `Aspose.Imaging.Size`. |
| height | int | Компонент высоты нового `Aspose.Imaging.Size`. |

### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Возвращает новый экземпляр структуры `Aspose.Imaging.Size`, у которого значения `Aspose.Imaging.Size.Width` и `Aspose.Imaging.Size.Height` установлены в ноль.

**Returns:**
[Size](../../com.aspose.imaging/size)
### to_SizeF(Size size) {#to-SizeF-com.aspose.imaging.Size-}
```
public static SizeF to_SizeF(Size size)
```


Преобразует указанный `Aspose.Imaging.Size` в `Aspose.Imaging.SizeF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` для преобразования. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` structure to which this operator converts.
### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Добавляет ширину и высоту одной структуры `Aspose.Imaging.Size` к ширине и высоте другой структуры `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Первый `Aspose.Imaging.Size` для добавления. |
| size2 | [Size](../../com.aspose.imaging/size) | Второй `Aspose.Imaging.Size` для добавления. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Вычитает ширину и высоту одной структуры `Aspose.Imaging.Size` из ширины и высоты другой структуры `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Структура `Aspose.Imaging.Size` слева от оператора вычитания. |
| size2 | [Size](../../com.aspose.imaging/size) | Структура `Aspose.Imaging.Size` справа от оператора вычитания. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the subtraction operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


Проверяет, равны ли две структуры `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Структура `Aspose.Imaging.Size` слева от оператора равенства. |
| size2 | [Size](../../com.aspose.imaging/size) | Структура `Aspose.Imaging.Size` справа от оператора равенства. |

**Returns:**
boolean — True, если `size1` и `size2` имеют одинаковую ширину и высоту; иначе false.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


Проверяет, различаются ли две структуры `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Структура `Aspose.Imaging.Size` слева от оператора неравенства. |
| size2 | [Size](../../com.aspose.imaging/size) | Структура `Aspose.Imaging.Size` справа от оператора неравенства. |

**Returns:**
boolean — True, если `size1` и `size2` различаются по ширине или высоте; false, если `size1` и `size2` равны.
### to_Point(Size size) {#to-Point-com.aspose.imaging.Size-}
```
public static Point to_Point(Size size)
```


Преобразует указанный `Aspose.Imaging.Size` в `Aspose.Imaging.Point`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` для преобразования. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` structure to which this operator converts.
### add(Size size1, Size size2) {#add-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size add(Size size1, Size size2)
```


Добавляет ширину и высоту одной структуры `Aspose.Imaging.Size` к ширине и высоте другой структуры `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Первый `Aspose.Imaging.Size` для добавления. |
| size2 | [Size](../../com.aspose.imaging/size) | Второй `Aspose.Imaging.Size` для добавления. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.imaging.SizeF-}
```
public static Size ceiling(SizeF size)
```


Преобразует указанную структуру `Aspose.Imaging.SizeF` в структуру `Aspose.Imaging.Size`, округляя значения до следующего большего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Структура `Aspose.Imaging.SizeF` для преобразования. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### subtract(Size size1, Size size2) {#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Вычитает ширину и высоту одной структуры `Aspose.Imaging.Size` из ширины и высоты другой структуры `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Структура `Aspose.Imaging.Size` слева от оператора вычитания. |
| size2 | [Size](../../com.aspose.imaging/size) | Структура `Aspose.Imaging.Size` справа от оператора вычитания. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that is a result of the subtraction operation.
### truncate(SizeF size) {#truncate-com.aspose.imaging.SizeF-}
```
public static Size truncate(SizeF size)
```


Преобразует указанную структуру `Aspose.Imaging.SizeF` в структуру `Aspose.Imaging.Size`, отбрасывая дробную часть и приводя значения к следующему меньшему целому.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Структура `Aspose.Imaging.SizeF` для преобразования. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### round(SizeF size) {#round-com.aspose.imaging.SizeF-}
```
public static Size round(SizeF size)
```


Преобразует указанную структуру `Aspose.Imaging.SizeF` в структуру `Aspose.Imaging.Size`, округляя значения до ближайшего целого числа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Структура `Aspose.Imaging.SizeF` для преобразования. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.imaging/size) |  |
| obj2 | [Size](../../com.aspose.imaging/size) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Возвращает значение, указывающее, имеет ли данный `Aspose.Imaging.Size` нулевую ширину и высоту.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает или задает горизонтальную компоненту данного `Aspose.Imaging.Size`.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Получает или задает горизонтальную компоненту данного `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает или задает вертикальную компоненту этого `Aspose.Imaging.Size`.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Получает или задает вертикальную компоненту этого `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, является ли указанный объект `Aspose.Imaging.Size` с теми же размерами, что и этот `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект `System.Object` для тестирования. |

**Returns:**
boolean — True, если `obj` является `Aspose.Imaging.Size` и имеет ту же ширину и высоту, что и этот `Aspose.Imaging.Size`; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш‑код для этой структуры `Aspose.Imaging.Size`.

**Returns:**
int — целочисленное значение, задающее хеш‑значение для этой структуры `Aspose.Imaging.Size`.
### toString() {#toString--}
```
public String toString()
```


Создаёт человекочитаемую строку, представляющую этот `Aspose.Imaging.Size`.

**Returns:**
java.lang.String — строка, представляющая этот `Aspose.Imaging.Size`.
### CloneTo(Size that) {#CloneTo-com.aspose.imaging.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [Size](../../com.aspose.imaging/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.imaging/size)
