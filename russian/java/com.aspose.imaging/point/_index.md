---
title: "Point"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет упорядоченную пару целочисленных координат x и y, определяющих точку в двумерной плоскости."
type: docs
weight: 86
url: /ru/java/com.aspose.imaging/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Представляет упорядоченную пару целочисленных координат x и y, определяющих точку в двумерной плоскости.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Инициализирует новый экземпляр структуры `Aspose.Imaging.Point` с указанными координатами. |
| [Point(Size size)](#Point-com.aspose.imaging.Size-) | Инициализирует новый экземпляр структуры `Aspose.Imaging.Point` из структуры `Aspose.Imaging.Size`. |
| [Point(int dw)](#Point-int-) | Инициализирует новый экземпляр структуры `Aspose.Imaging.Point`, используя координаты, указанные целочисленным значением. |
## Методы

| Метод | Описание |
| --- | --- |
| [getEmpty()](#getEmpty--) | Получает новый экземпляр структуры `Aspose.Imaging.Point`, у которого значения `Aspose.Imaging.Point.X` и `Aspose.Imaging.Point.Y` установлены в ноль. |
| [add(Point point, Size size)](#add-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Добавляет указанный `Aspose.Imaging.Size` к указанному `Aspose.Imaging.Point`. |
| [subtract(Point point, Size size)](#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Возвращает результат вычитания указанного `Aspose.Imaging.Size` из указанного `Aspose.Imaging.Point`. |
| [ceiling(PointF point)](#ceiling-com.aspose.imaging.PointF-) | Преобразует указанный `Aspose.Imaging.PointF` в `Aspose.Imaging.Point`, округляя значения `Aspose.Imaging.PointF` до следующего большего целого. |
| [round(PointF point)](#round-com.aspose.imaging.PointF-) | Преобразует указанный `Aspose.Imaging.PointF` в объект `Aspose.Imaging.Point`, округляя значения `Aspose.Imaging.Point` до ближайшего целого. |
| [truncate(PointF point)](#truncate-com.aspose.imaging.PointF-) | Преобразует указанный `Aspose.Imaging.PointF` в `Aspose.Imaging.Point`, отбрасывая дробную часть значений `Aspose.Imaging.Point`. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Смещает `Aspose.Imaging.Point` на заданный `Aspose.Imaging.Size`. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Смещает `Aspose.Imaging.Point` на отрицательное значение заданного `Aspose.Imaging.Size`. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Сравнивает два объекта `Aspose.Imaging.Point`. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Сравнивает два объекта `Aspose.Imaging.Point`. |
| [to_Size(Point point)](#to-Size-com.aspose.imaging.Point-) | Преобразует указанную структуру `Aspose.Imaging.Point` в структуру `Aspose.Imaging.Size`. |
| [to_PointF(Point point)](#to-PointF-com.aspose.imaging.Point-) | Преобразует указанную структуру `Point` в структуру `PointF`. |
| [fromLong(long packedPoint, int[] x, int[] y)](#fromLong-long-int---int---) | Разбирает объект Point, упакованный в long, на отдельные целочисленные значения X и Y. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-) |  |
| [isEmpty()](#isEmpty--) | Возвращает значение, указывающее, пустой ли этот `Aspose.Imaging.Point`. |
| [getX()](#getX--) | Получает или задает координату x этого `Aspose.Imaging.Point`. |
| [setX(int value)](#setX-int-) | Получает или задает координату x этого `Aspose.Imaging.Point`. |
| [getY()](#getY--) | Получает или задает координату y этого `Aspose.Imaging.Point`. |
| [setY(int value)](#setY-int-) | Получает или задает координату y этого `Aspose.Imaging.Point`. |
| [offset(Point point)](#offset-com.aspose.imaging.Point-) | Смещает этот `Aspose.Imaging.Point` на указанный `Aspose.Imaging.Point`. |
| [offset(int dx, int dy)](#offset-int-int-) | Смещает этот `Aspose.Imaging.Point` на указанную величину. |
| [equals(Object obj)](#equals-java.lang.Object-) | Указывает, содержит ли этот `Aspose.Imaging.Point` те же координаты, что и указанный `System.Object`. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого `Aspose.Imaging.Point`. |
| [toLong()](#toLong--) | Преобразует этот Point в одно значение типа long, содержащее координаты X и Y в старших и младших битах. |
| [toString()](#toString--) | Преобразует этот `Aspose.Imaging.Point` в человекочитаемую строку. |
| [CloneTo(Point that)](#CloneTo-com.aspose.imaging.Point-) |  |
| [Clone()](#Clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Инициализирует новый экземпляр структуры `Aspose.Imaging.Point` с указанными координатами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Горизонтальное положение точки. |
| y | int | Вертикальное положение точки. |

### Point(Size size) {#Point-com.aspose.imaging.Size-}
```
public Point(Size size)
```


Инициализирует новый экземпляр структуры `Aspose.Imaging.Point` из структуры `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Содержит новые координаты точки. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Инициализирует новый экземпляр структуры `Aspose.Imaging.Point`, используя координаты, указанные целочисленным значением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dw | int | 32-битное целое число, указывающее координаты новой точки. |

### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Получает новый экземпляр структуры `Aspose.Imaging.Point`, у которого значения `Aspose.Imaging.Point.X` и `Aspose.Imaging.Point.Y` установлены в ноль.

**Returns:**
[Point](../../com.aspose.imaging/point)
### add(Point point, Size size) {#add-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point add(Point point, Size size)
```


Добавляет указанный `Aspose.Imaging.Size` к указанному `Aspose.Imaging.Point`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | `Aspose.Imaging.Point`, к которому нужно добавить. |
| size | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size`, который нужно добавить к `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the addition operation.
### subtract(Point point, Size size) {#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point subtract(Point point, Size size)
```


Возвращает результат вычитания указанного `Aspose.Imaging.Size` из указанного `Aspose.Imaging.Point`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Точка `Aspose.Imaging.Point`, из которой будет вычитаться. |
| size | [Size](../../com.aspose.imaging/size) | Размер `Aspose.Imaging.Size`, из которого будет вычитаться `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the subtraction operation.
### ceiling(PointF point) {#ceiling-com.aspose.imaging.PointF-}
```
public static Point ceiling(PointF point)
```


Преобразует указанный `Aspose.Imaging.PointF` в `Aspose.Imaging.Point`, округляя значения `Aspose.Imaging.PointF` до следующего большего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Точка `Aspose.Imaging.PointF` для преобразования. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### round(PointF point) {#round-com.aspose.imaging.PointF-}
```
public static Point round(PointF point)
```


Преобразует указанный `Aspose.Imaging.PointF` в объект `Aspose.Imaging.Point`, округляя значения `Aspose.Imaging.Point` до ближайшего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Точка `Aspose.Imaging.PointF` для преобразования. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### truncate(PointF point) {#truncate-com.aspose.imaging.PointF-}
```
public static Point truncate(PointF point)
```


Преобразует указанный `Aspose.Imaging.PointF` в `Aspose.Imaging.Point`, отбрасывая дробную часть значений `Aspose.Imaging.Point`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Точка `Aspose.Imaging.PointF` для преобразования. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### op_Addition(Point point, Size size) {#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Смещает `Aspose.Imaging.Point` на заданный `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Точка `Aspose.Imaging.Point` для перемещения. |
| size | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size`, определяющий пару чисел для добавления к координатам `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The translated `Aspose.Imaging.Point`.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Смещает `Aspose.Imaging.Point` на отрицательное значение заданного `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Точка `Aspose.Imaging.Point` для перемещения. |
| size | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size`, определяющий пару чисел для вычитания из координат `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - A `Aspose.Imaging.Point` structure that is translated by the negative of a given `Aspose.Imaging.Size` structure.
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Сравнивает два объекта `Aspose.Imaging.Point`. Результат указывает, равны ли значения свойств `Aspose.Imaging.Point.X` и `Aspose.Imaging.Point.Y` у обоих объектов `Aspose.Imaging.Point`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Первый `Aspose.Imaging.Point` для сравнения. |
| point2 | [Point](../../com.aspose.imaging/point) | Второй `Aspose.Imaging.Point` для сравнения. |

**Returns:**
boolean — true, если значения `Aspose.Imaging.Point.X` и `Aspose.Imaging.Point.Y` у `point1` и `point2` равны; иначе false.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Сравнивает два объекта `Aspose.Imaging.Point`. Результат указывает, не равны ли значения свойств `Aspose.Imaging.Point.X` или `Aspose.Imaging.Point.Y` у обоих объектов `Aspose.Imaging.Point`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Первый `Aspose.Imaging.Point` для сравнения. |
| point2 | [Point](../../com.aspose.imaging/point) | Второй `Aspose.Imaging.Point` для сравнения. |

**Returns:**
boolean — true, если значения свойства `Aspose.Imaging.Point.X` или свойства `Aspose.Imaging.Point.Y` у `point1` и `point2` различаются; иначе false.
### to_Size(Point point) {#to-Size-com.aspose.imaging.Point-}
```
public static Size to_Size(Point point)
```


Преобразует указанную структуру `Aspose.Imaging.Point` в структуру `Aspose.Imaging.Size`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | `Aspose.Imaging.Point` для преобразования. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that results from the conversion.
### to_PointF(Point point) {#to-PointF-com.aspose.imaging.Point-}
```
public static PointF to_PointF(Point point)
```


Преобразует указанную структуру `Point` в структуру `PointF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | `Point` для преобразования. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `PointF` that results from the conversion.
### fromLong(long packedPoint, int[] x, int[] y) {#fromLong-long-int---int---}
```
public static void fromLong(long packedPoint, int[] x, int[] y)
```


Разбирает объект Point, упакованный в long, на отдельные целочисленные значения X и Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| packedPoint | long | Объект Point, упакованный в одно значение типа long. |
| x | int[] | Извлечённое из упакованного Point значение X. |
| y | int[] | Извлечённое из упакованного Point значение Y. |

### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.imaging/point) |  |
| obj2 | [Point](../../com.aspose.imaging/point) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Возвращает значение, указывающее, пустой ли этот `Aspose.Imaging.Point`.

**Returns:**
boolean — true, если оба `Aspose.Imaging.Point.X` и `Aspose.Imaging.Point.Y` равны 0; иначе false.
### getX() {#getX--}
```
public int getX()
```


Получает или задает координату x этого `Aspose.Imaging.Point`.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Получает или задает координату x этого `Aspose.Imaging.Point`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public int getY()
```


Получает или задает координату y этого `Aspose.Imaging.Point`.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Получает или задает координату y этого `Aspose.Imaging.Point`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### offset(Point point) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point point)
```


Смещает этот `Aspose.Imaging.Point` на указанный `Aspose.Imaging.Point`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | `Aspose.Imaging.Point`, используемый для смещения данного `Aspose.Imaging.Point`. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Смещает этот `Aspose.Imaging.Point` на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | int | Величина смещения координаты x. |
| dy | int | Величина смещения координаты y. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Указывает, содержит ли этот `Aspose.Imaging.Point` те же координаты, что и указанный `System.Object`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект `System.Object` для тестирования. |

**Returns:**
boolean — true, если `obj` является `Aspose.Imaging.Point` и имеет те же координаты, что и данный `Aspose.Imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого `Aspose.Imaging.Point`.

**Returns:**
int — хеш-код для этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
### toLong() {#toLong--}
```
public final long toLong()
```


Преобразует этот Point в одно значение типа long, содержащее координаты X и Y в старших и младших битах.

**Returns:**
long — объект Point, упакованный в одно значение типа long.
### toString() {#toString--}
```
public String toString()
```


Преобразует этот `Aspose.Imaging.Point` в человекочитаемую строку.

**Returns:**
java.lang.String - `System.String`, представляющая этот экземпляр.
### CloneTo(Point that) {#CloneTo-com.aspose.imaging.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [Point](../../com.aspose.imaging/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.imaging/point)
