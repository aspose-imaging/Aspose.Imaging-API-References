---
title: "PointF"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет упорядоченную пару координат x и y с плавающей точкой, определяющих точку в двумерной плоскости."
type: docs
weight: 87
url: /ru/java/com.aspose.imaging/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

Представляет упорядоченную пару координат x и y с плавающей точкой, определяющих точку в двумерной плоскости.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Инициализирует новый экземпляр структуры `com.aspose.imaging.PointF` с указанными координатами. |
## Методы

| Метод | Описание |
| --- | --- |
| [getEmpty()](#getEmpty--) | Получает новый экземпляр структуры `com.aspose.imaging.PointF`, у которой значения `com.aspose.imaging.PointF.X` и `com.aspose.imaging.PointF.Y` установлены в ноль. |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Перемещает `com.aspose.imaging.PointF` на заданный `com.aspose.imaging.Size`. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Перемещает `com.aspose.imaging.PointF` на отрицательное значение заданного `com.aspose.imaging.Size`. |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Перемещает `com.aspose.imaging.PointF` на указанный `com.aspose.imaging.SizeF`. |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Перемещает `com.aspose.imaging.PointF` на отрицательное значение указанного `com.aspose.imaging.SizeF`. |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Сравнивает две структуры `com.aspose.imaging.PointF`. |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Определяет, не равны ли координаты указанных точек. |
| [add(PointF point, Size size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Перемещает заданный `com.aspose.imaging.PointF` на указанный `com.aspose.imaging.Size`. |
| [subtract(PointF point, Size size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Перемещает `com.aspose.imaging.PointF` на отрицательное значение указанного размера. |
| [add(PointF point, SizeF size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Перемещает заданный `com.aspose.imaging.PointF` на указанный `com.aspose.imaging.SizeF`. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Перемещает `com.aspose.imaging.PointF` на отрицательное значение указанного размера. |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) |  |
| [isEmpty()](#isEmpty--) | Получает значение, указывающее, пустой ли этот `com.aspose.imaging.PointF`. |
| [getX()](#getX--) | Получает или задает координату X этого `com.aspose.imaging.PointF`. |
| [setX(float value)](#setX-float-) | Получает или задает координату X этого `com.aspose.imaging.PointF`. |
| [getY()](#getY--) | Получает или задает координату Y этого `com.aspose.imaging.PointF`. |
| [setY(float value)](#setY-float-) | Получает или задает координату Y этого `com.aspose.imaging.PointF`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Указывает, содержит ли этот `com.aspose.imaging.PointF` те же координаты, что и указанный `System.Object`. |
| [hashCode()](#hashCode--) | Возвращает хеш-код этой структуры `com.aspose.imaging.PointF`. |
| [toString()](#toString--) | Преобразует этот `com.aspose.imaging.PointF` в читаемую человеком строку. |
| [CloneTo(PointF that)](#CloneTo-com.aspose.imaging.PointF-) |  |
| [Clone()](#Clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Инициализирует новый экземпляр структуры `com.aspose.imaging.PointF` с указанными координатами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Горизонтальное положение точки. |
| y | float | Вертикальное положение точки. |

### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


Получает новый экземпляр структуры `com.aspose.imaging.PointF`, у которой значения `com.aspose.imaging.PointF.X` и `com.aspose.imaging.PointF.Y` установлены в ноль.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Перемещает `com.aspose.imaging.PointF` на заданный `com.aspose.imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF` для преобразования. |
| size | [Size](../../com.aspose.imaging/size) | Объект `com.aspose.imaging.Size`, определяющий пару чисел для добавления к координатам `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns the translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Перемещает `com.aspose.imaging.PointF` на отрицательное значение заданного `com.aspose.imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF` для преобразования. |
| size | [Size](../../com.aspose.imaging/size) | Объект `com.aspose.imaging.Size`, определяющий числа для вычитания из x- и y-координат `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


Перемещает `com.aspose.imaging.PointF` на указанный `com.aspose.imaging.SizeF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF` для преобразования. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Объект `com.aspose.imaging.SizeF`, определяющий числа для добавления к x- и y-координатам `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Перемещает `com.aspose.imaging.PointF` на отрицательное значение указанного `com.aspose.imaging.SizeF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF` для преобразования. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Объект `com.aspose.imaging.SizeF`, определяющий числа для вычитания из координат `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


Сравнивает две структуры `com.aspose.imaging.PointF`. Результат указывает, равны ли значения свойств `com.aspose.imaging.PointF.X` и `com.aspose.imaging.PointF.Y` у обеих структур `com.aspose.imaging.PointF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Первый `com.aspose.imaging.PointF` для сравнения. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Второй `com.aspose.imaging.PointF` для сравнения. |

**Returns:**
boolean — true, если значения `com.aspose.imaging.PointF.X` и `com.aspose.imaging.PointF.Y` первой и второй структур `com.aspose.imaging.PointF` равны; иначе false.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Определяет, не равны ли координаты указанных точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Первый `com.aspose.imaging.PointF` для сравнения. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Второй `com.aspose.imaging.PointF` для сравнения. |

**Returns:**
boolean — true, указывая, что значения `com.aspose.imaging.PointF.X` и `com.aspose.imaging.PointF.Y` `point1` и `point2` не равны; иначе false.
### add(PointF point, Size size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF add(PointF point, Size size)
```


Перемещает заданный `com.aspose.imaging.PointF` на указанный `com.aspose.imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF` для преобразования. |
| size | [Size](../../com.aspose.imaging/size) | Объект `com.aspose.imaging.Size`, определяющий числа для добавления к координатам `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, Size size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Перемещает `com.aspose.imaging.PointF` на отрицательное значение указанного размера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF` для преобразования. |
| size | [Size](../../com.aspose.imaging/size) | Объект `com.aspose.imaging.Size`, определяющий числа для вычитания из координат `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### add(PointF point, SizeF size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Перемещает заданный `com.aspose.imaging.PointF` на указанный `com.aspose.imaging.SizeF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF` для преобразования. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Объект `com.aspose.imaging.SizeF`, определяющий числа для добавления к координатам `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, SizeF size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Перемещает `com.aspose.imaging.PointF` на отрицательное значение указанного размера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF` для преобразования. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Объект `com.aspose.imaging.SizeF`, определяющий числа для вычитания из координат `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.imaging/pointf) |  |
| obj2 | [PointF](../../com.aspose.imaging/pointf) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Получает значение, указывающее, пустой ли этот `com.aspose.imaging.PointF`.

**Returns:**
boolean — true, если оба `com.aspose.imaging.PointF.X` и `com.aspose.imaging.PointF.Y` равны 0; иначе false.
### getX() {#getX--}
```
public float getX()
```


Получает или задает координату X этого `com.aspose.imaging.PointF`.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Получает или задает координату X этого `com.aspose.imaging.PointF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public float getY()
```


Получает или задает координату Y этого `com.aspose.imaging.PointF`.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Получает или задает координату Y этого `com.aspose.imaging.PointF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Указывает, содержит ли этот `com.aspose.imaging.PointF` те же координаты, что и указанный `System.Object`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект `System.Object` для тестирования. |

**Returns:**
boolean — метод возвращает true, если `obj` является `com.aspose.imaging.PointF` и имеет те же координаты, что и данный `com.aspose.imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код этой структуры `com.aspose.imaging.PointF`.

**Returns:**
int — целочисленное значение, определяющее хеш для этой структуры `com.aspose.imaging.PointF`.
### toString() {#toString--}
```
public String toString()
```


Преобразует этот `com.aspose.imaging.PointF` в читаемую человеком строку.

**Returns:**
java.lang.String — строка, представляющая этот `com.aspose.imaging.PointF`.
### CloneTo(PointF that) {#CloneTo-com.aspose.imaging.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [PointF](../../com.aspose.imaging/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.imaging/pointf)
