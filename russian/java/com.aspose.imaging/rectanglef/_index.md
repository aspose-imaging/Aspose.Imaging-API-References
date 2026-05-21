---
title: "RectangleF"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Сохраняет набор из четырёх чисел с плавающей точкой, представляющих положение и размер прямоугольника."
type: docs
weight: 94
url: /ru/java/com.aspose.imaging/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Сохраняет набор из четырёх чисел с плавающей точкой, представляющих положение и размер прямоугольника.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Инициализирует новый экземпляр структуры `com.aspose.imaging.RectangleF` с указанным расположением и размером. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Инициализирует новый экземпляр структуры `com.aspose.imaging.RectangleF` с указанным расположением и размером. |
## Методы

| Метод | Описание |
| --- | --- |
| [getEmpty()](#getEmpty--) | Возвращает новый экземпляр структуры `com.aspose.imaging.RectangleF`, у которой значения `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` и `com.aspose.imaging.RectangleF.Height` установлены в ноль. |
| [getLocation()](#getLocation--) | Получает или задает координаты верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`. |
| [setLocation(PointF value)](#setLocation-com.aspose.imaging.PointF-) | Получает или задает координаты верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`. |
| [getSize()](#getSize--) | Получает или задает размер этой `com.aspose.imaging.RectangleF`. |
| [setSize(SizeF value)](#setSize-com.aspose.imaging.SizeF-) | Получает или задает размер этой `com.aspose.imaging.RectangleF`. |
| [getX()](#getX--) | Получает или задает координату x верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`. |
| [setX(float value)](#setX-float-) | Получает или задает координату x верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`. |
| [getY()](#getY--) | Получает или задает координату y верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`. |
| [setY(float value)](#setY-float-) | Получает или задает координату y верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`. |
| [getWidth()](#getWidth--) | Получает или задает ширину этой структуры `com.aspose.imaging.RectangleF`. |
| [setWidth(float value)](#setWidth-float-) | Получает или задает ширину этой структуры `com.aspose.imaging.RectangleF`. |
| [getHeight()](#getHeight--) | Получает или задает высоту этой структуры `com.aspose.imaging.RectangleF`. |
| [setHeight(float value)](#setHeight-float-) | Получает или задает высоту этой структуры `com.aspose.imaging.RectangleF`. |
| [getLeft()](#getLeft--) | Получает или задает координату x левой грани этой структуры `com.aspose.imaging.RectangleF`. |
| [setLeft(float value)](#setLeft-float-) | Получает или задает координату x левой грани этой структуры `com.aspose.imaging.RectangleF`. |
| [getTop()](#getTop--) | Получает или задает координату y верхней грани этой структуры `com.aspose.imaging.RectangleF`. |
| [setTop(float value)](#setTop-float-) | Получает или задает координату y верхней грани этой структуры `com.aspose.imaging.RectangleF`. |
| [getRight()](#getRight--) | Получает или задает координату x, которая является суммой `com.aspose.imaging.RectangleF.X` и `com.aspose.imaging.RectangleF.Width` этой структуры `com.aspose.imaging.RectangleF`. |
| [setRight(float value)](#setRight-float-) | Получает или задает координату x, которая является суммой `com.aspose.imaging.RectangleF.X` и `com.aspose.imaging.RectangleF.Width` этой структуры `com.aspose.imaging.RectangleF`. |
| [getBottom()](#getBottom--) | Получает или задает координату y, которая является суммой `com.aspose.imaging.RectangleF.Y` и `com.aspose.imaging.RectangleF.Height` этой структуры `com.aspose.imaging.RectangleF`. |
| [setBottom(float value)](#setBottom-float-) | Получает или задает координату y, которая является суммой `com.aspose.imaging.RectangleF.Y` и `com.aspose.imaging.RectangleF.Height` этой структуры `com.aspose.imaging.RectangleF`. |
| [isEmpty()](#isEmpty--) | Возвращает значение, указывающее, имеет ли свойство `com.aspose.imaging.RectangleF.Width` или `com.aspose.imaging.RectangleF.Height` этой `com.aspose.imaging.RectangleF` значение ноль. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Создает новый `Rectangle` из двух указанных точек. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.imaging.RectangleF-float-float-) | Создает и возвращает расширенную копию указанной структуры `com.aspose.imaging.RectangleF`. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Возвращает структуру `com.aspose.imaging.RectangleF`, представляющую пересечение двух прямоугольников. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Создает наименьший возможный третий прямоугольник, который может содержать оба прямоугольника, образующих объединение. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Проверяет, имеют ли две структуры `com.aspose.imaging.RectangleF` одинаковое расположение и размер. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Проверяет, различаются ли две структуры `com.aspose.imaging.RectangleF` по расположению или размеру. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.imaging.RectangleF-float-) | Реализует оператор \*. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.imaging.RectangleF-float-) | Реализует оператор /. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.imaging.Rectangle-) | Преобразует указанную структуру `com.aspose.imaging.Rectangle` в структуру `com.aspose.imaging.RectangleF`. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Создает структуру `com.aspose.imaging.RectangleF` с верхним левым и нижним правым углом в указанных позициях. |
| [normalize()](#normalize--) | Нормализует прямоугольник, делая его ширину и высоту положительными, левую сторону меньше правой и верхнюю сторону меньше нижней. |
| [contains(float x, float y)](#contains-float-float-) | Определяет, находится ли указанная точка внутри этой структуры `com.aspose.imaging.RectangleF`. |
| [contains(PointF point)](#contains-com.aspose.imaging.PointF-) | Определяет, находится ли указанная точка внутри этой структуры `com.aspose.imaging.RectangleF`. |
| [contains(RectangleF rect)](#contains-com.aspose.imaging.RectangleF-) | Определяет, полностью ли прямоугольный регион, представленный `rect`, содержится в этой структуре `com.aspose.imaging.RectangleF`. |
| [inflate(float x, float y)](#inflate-float-float-) | Увеличивает эту структуру `com.aspose.imaging.RectangleF` на указанную величину. |
| [inflate(SizeF size)](#inflate-com.aspose.imaging.SizeF-) | Увеличивает этот `com.aspose.imaging.RectangleF` на указанную величину. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Заменяет эту структуру `com.aspose.imaging.RectangleF` пересечением её с указанной структурой `com.aspose.imaging.RectangleF`. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.imaging.RectangleF-) | Определяет, пересекается ли этот прямоугольник с `rect`. |
| [offset(PointF pos)](#offset-com.aspose.imaging.PointF-) | Корректирует положение этого прямоугольника на указанную величину. |
| [offset(float x, float y)](#offset-float-float-) | Корректирует положение этого прямоугольника на указанную величину. |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, является ли `obj` объектом `com.aspose.imaging.RectangleF` с тем же расположением и размером, что и этот `com.aspose.imaging.RectangleF`. |
| [hashCode()](#hashCode--) | Получает хеш‑код этой структуры `com.aspose.imaging.RectangleF`. |
| [toString()](#toString--) | Преобразует атрибуты этого `com.aspose.imaging.RectangleF` в читаемую строку. |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.imaging.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Инициализирует новый экземпляр структуры `com.aspose.imaging.RectangleF` с указанным расположением и размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x верхнего левого угла прямоугольника. |
| y | float | Координата y верхнего левого угла прямоугольника. |
| width | float | Ширина прямоугольника. |
| height | float | Высота прямоугольника. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Инициализирует новый экземпляр структуры `com.aspose.imaging.RectangleF` с указанным расположением и размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| location | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF`, представляющий верхний левый угол прямоугольного региона. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Объект `com.aspose.imaging.SizeF`, представляющий ширину и высоту прямоугольного региона. |

### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Возвращает новый экземпляр структуры `com.aspose.imaging.RectangleF`, у которой значения `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` и `com.aspose.imaging.RectangleF.Height` установлены в ноль.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Получает или задает координаты верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `com.aspose.imaging.PointF` that represents the upper-left corner of this `com.aspose.imaging.RectangleF` structure.
### setLocation(PointF value) {#setLocation-com.aspose.imaging.PointF-}
```
public void setLocation(PointF value)
```


Получает или задает координаты верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSize() {#getSize--}
```
public SizeF getSize()
```


Получает или задает размер этой `com.aspose.imaging.RectangleF`.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `com.aspose.imaging.SizeF` that represents the width and height of this `com.aspose.imaging.RectangleF` structure.
### setSize(SizeF value) {#setSize-com.aspose.imaging.SizeF-}
```
public void setSize(SizeF value)
```


Получает или задает размер этой `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) |  |

### getX() {#getX--}
```
public float getX()
```


Получает или задает координату x верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`.

**Returns:**
float — координата x верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`.
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Получает или задает координату x верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public float getY()
```


Получает или задает координату y верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`.

**Returns:**
float — координата y верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`.
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Получает или задает координату y верхнего левого угла этой структуры `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Получает или задает ширину этой структуры `com.aspose.imaging.RectangleF`.

**Returns:**
float — ширина этой структуры `com.aspose.imaging.RectangleF`.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Получает или задает ширину этой структуры `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Получает или задает высоту этой структуры `com.aspose.imaging.RectangleF`.

**Returns:**
float — высота этой структуры `com.aspose.imaging.RectangleF`.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Получает или задает высоту этой структуры `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getLeft() {#getLeft--}
```
public float getLeft()
```


Получает или задает координату x левой грани этой структуры `com.aspose.imaging.RectangleF`.

**Returns:**
float — координата x левого края этой структуры `com.aspose.imaging.RectangleF`.
### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Получает или задает координату x левой грани этой структуры `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getTop() {#getTop--}
```
public float getTop()
```


Получает или задает координату y верхней грани этой структуры `com.aspose.imaging.RectangleF`.

**Returns:**
float — координата y верхнего края этой структуры `com.aspose.imaging.RectangleF`.
### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Получает или задает координату y верхней грани этой структуры `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public float getRight()
```


Получает или задает координату x, которая является суммой `com.aspose.imaging.RectangleF.X` и `com.aspose.imaging.RectangleF.Width` этой структуры `com.aspose.imaging.RectangleF`.

**Returns:**
float - X‑координата, которая является суммой `com.aspose.imaging.RectangleF.X` и `com.aspose.imaging.RectangleF.Width` этой структуры `com.aspose.imaging.RectangleF`.
### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Получает или задает координату x, которая является суммой `com.aspose.imaging.RectangleF.X` и `com.aspose.imaging.RectangleF.Width` этой структуры `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getBottom() {#getBottom--}
```
public float getBottom()
```


Получает или задает координату y, которая является суммой `com.aspose.imaging.RectangleF.Y` и `com.aspose.imaging.RectangleF.Height` этой структуры `com.aspose.imaging.RectangleF`.

**Returns:**
float - Y‑координата, которая является суммой `com.aspose.imaging.RectangleF.Y` и `com.aspose.imaging.RectangleF.Height` этой структуры `com.aspose.imaging.RectangleF`.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Получает или задает координату y, которая является суммой `com.aspose.imaging.RectangleF.Y` и `com.aspose.imaging.RectangleF.Height` этой структуры `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Возвращает значение, указывающее, имеет ли свойство `com.aspose.imaging.RectangleF.Width` или `com.aspose.imaging.RectangleF.Height` этой `com.aspose.imaging.RectangleF` значение ноль.

**Returns:**
boolean - Это свойство возвращает true, если свойство `com.aspose.imaging.RectangleF.Width` или `com.aspose.imaging.RectangleF.Height` этой `com.aspose.imaging.RectangleF` имеет значение ноль; в противном случае — false.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Создаёт новый `Rectangle` из двух указанных точек. Две вершины создаваемого `Rectangle` будут равны переданным `point1` и `point2`. Обычно это противоположные вершины.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Первая `Point` для нового прямоугольника. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Вторая `Point` для нового прямоугольника. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A newly created `Rectangle`.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.imaging.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Создаёт и возвращает увеличенную копию указанной структуры `com.aspose.imaging.RectangleF`. Копия увеличивается на заданную величину. Исходный прямоугольник остаётся неизменным.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` для копирования. Этот прямоугольник не изменяется. |
| x | float | Величина, на которую нужно увеличить копию прямоугольника по горизонтали. |
| y | float | Величина, на которую нужно увеличить копию прямоугольника по вертикали. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The inflated `com.aspose.imaging.RectangleF`.
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Возвращает структуру `com.aspose.imaging.RectangleF`, представляющую пересечение двух прямоугольников. Если пересечения нет, возвращается пустой `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Первый прямоугольник для пересечения. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Второй прямоугольник для пересечения. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Создает наименьший возможный третий прямоугольник, который может содержать оба прямоугольника, образующих объединение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Первый прямоугольник для объединения. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Второй прямоугольник для объединения. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure that contains both of the two rectangles that form the union.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Проверяет, имеют ли две структуры `com.aspose.imaging.RectangleF` одинаковое расположение и размер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF`, находящаяся слева от оператора равенства. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF`, находящаяся справа от оператора равенства. |

**Returns:**
boolean - Этот оператор возвращает true, если две указанные структуры `com.aspose.imaging.RectangleF` имеют одинаковые свойства `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` и `com.aspose.imaging.RectangleF.Height`.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Проверяет, различаются ли две структуры `com.aspose.imaging.RectangleF` по расположению или размеру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF`, находящаяся слева от оператора неравенства. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF`, находящаяся справа от оператора неравенства. |

**Returns:**
boolean - Этот оператор возвращает true, если любое из свойств `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` или `com.aspose.imaging.RectangleF.Height` двух структур `com.aspose.imaging.RectangleF` не равно; в противном случае — false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Реализует оператор \*.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Прямоугольник. |
| множитель | float | Множитель. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Реализует оператор /.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Прямоугольник. |
| делитель | float | Делитель. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.imaging.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Преобразует указанную структуру `com.aspose.imaging.Rectangle` в структуру `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `com.aspose.imaging.Rectangle` для преобразования. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The `com.aspose.imaging.RectangleF` structure that is converted from the specified `com.aspose.imaging.Rectangle` structure.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Создает структуру `com.aspose.imaging.RectangleF` с верхним левым и нижним правым углом в указанных позициях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| слева | float | Координата x верхнего левого угла прямоугольной области. |
| сверху | float | Координата y верхнего левого угла прямоугольной области. |
| справа | float | Координата x нижнего правого угла прямоугольной области. |
| снизу | float | Координата y нижнего правого угла прямоугольной области. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The new `com.aspose.imaging.RectangleF` that this method creates.
### normalize() {#normalize--}
```
public void normalize()
```


Нормализует прямоугольник, делая его ширину и высоту положительными, левую сторону меньше правой и верхнюю сторону меньше нижней.

### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Определяет, находится ли указанная точка внутри этой структуры `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |

**Returns:**
boolean — Этот метод возвращает true, если точка, определённая `x` и `y`, содержится в этой структуре `com.aspose.imaging.RectangleF`; в противном случае — false.
### contains(PointF point) {#contains-com.aspose.imaging.PointF-}
```
public boolean contains(PointF point)
```


Определяет, находится ли указанная точка внутри этой структуры `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF` для проверки. |

**Returns:**
boolean — Этот метод возвращает true, если точка, представленная параметром `point`, содержится в этой структуре `com.aspose.imaging.RectangleF`; в противном случае — false.
### contains(RectangleF rect) {#contains-com.aspose.imaging.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Определяет, полностью ли прямоугольный регион, представленный `rect`, содержится в этой структуре `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Объект `com.aspose.imaging.RectangleF` для проверки. |

**Returns:**
boolean — Этот метод возвращает true, если прямоугольная область, представленная `rect`, полностью содержится в прямоугольной области, представленной этой `com.aspose.imaging.RectangleF`; в противном случае — false.
### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Увеличивает эту структуру `com.aspose.imaging.RectangleF` на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Величина расширения этой структуры `com.aspose.imaging.RectangleF` по горизонтали. |
| y | float | Величина расширения этой структуры `com.aspose.imaging.RectangleF` по вертикали. |

### inflate(SizeF size) {#inflate-com.aspose.imaging.SizeF-}
```
public void inflate(SizeF size)
```


Увеличивает этот `com.aspose.imaging.RectangleF` на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Величина расширения этого прямоугольника. |

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Заменяет эту структуру `com.aspose.imaging.RectangleF` пересечением её с указанной структурой `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Прямоугольник для пересечения. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.imaging.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Определяет, пересекается ли этот прямоугольник с `rect`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Прямоугольник для проверки. |

**Returns:**
boolean — Этот метод возвращает true, если существует любое пересечение.
### offset(PointF pos) {#offset-com.aspose.imaging.PointF-}
```
public void offset(PointF pos)
```


Корректирует положение этого прямоугольника на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.imaging/pointf) | Величина смещения положения. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Корректирует положение этого прямоугольника на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Величина смещения положения по горизонтали. |
| y | float | Величина смещения положения по вертикали. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, является ли `obj` объектом `com.aspose.imaging.RectangleF` с тем же расположением и размером, что и этот `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект `System.Object` для тестирования. |

**Returns:**
boolean - Этот метод возвращает true, если `obj` является `com.aspose.imaging.RectangleF` и его свойства X, Y, Width и Height равны соответствующим свойствам этого `com.aspose.imaging.RectangleF`; в противном случае — false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш‑код этой структуры `com.aspose.imaging.RectangleF`.

**Returns:**
int - Хеш‑код для этого `com.aspose.imaging.RectangleF`.
### toString() {#toString--}
```
public String toString()
```


Преобразует атрибуты этого `com.aspose.imaging.RectangleF` в читаемую строку.

**Returns:**
java.lang.String - Строка, содержащая позицию, ширину и высоту этой структуры `com.aspose.imaging.RectangleF`.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.imaging.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

**Returns:**
boolean
