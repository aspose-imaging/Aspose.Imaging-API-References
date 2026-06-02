---
title: "Rectangle"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Сохраняет набор из четырёх целых чисел, представляющих положение и размер прямоугольника."
type: docs
weight: 93
url: /ru/java/com.aspose.imaging/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Сохраняет набор из четырёх целых чисел, представляющих положение и размер прямоугольника.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Инициализирует новый экземпляр структуры `com.aspose.imaging.Rectangle` с указанным расположением и размером. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Инициализирует новый экземпляр структуры `com.aspose.imaging.Rectangle` с указанным расположением и размером. |
## Методы

| Метод | Описание |
| --- | --- |
| [getEmpty()](#getEmpty--) | Получает новый экземпляр структуры `com.aspose.imaging.Rectangle`, у которого значения `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` и `com.aspose.imaging.Rectangle.Height` установлены в ноль. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Создает новый `Rectangle` из двух указанных точек. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.imaging.RectangleF-) | Преобразует указанную структуру `com.aspose.imaging.RectangleF` в структуру `com.aspose.imaging.Rectangle`, округляя значения `com.aspose.imaging.RectangleF` до следующего большего целого. |
| [truncate(RectangleF value)](#truncate-com.aspose.imaging.RectangleF-) | Преобразует указанный `com.aspose.imaging.RectangleF` в `com.aspose.imaging.Rectangle`, усекнув значения `com.aspose.imaging.RectangleF`. |
| [round(RectangleF value)](#round-com.aspose.imaging.RectangleF-) | Преобразует указанный `com.aspose.imaging.RectangleF` в `com.aspose.imaging.Rectangle`, округляя значения `com.aspose.imaging.RectangleF` до ближайших целых чисел. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.imaging.Rectangle-int-int-) | Создаёт и возвращает расширенную копию указанной структуры `com.aspose.imaging.Rectangle`. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Возвращает третью структуру `com.aspose.imaging.Rectangle`, представляющую пересечение двух других структур `com.aspose.imaging.Rectangle`. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Получает структуру `com.aspose.imaging.Rectangle`, содержащую объединение двух структур `com.aspose.imaging.Rectangle`. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Проверяет, имеют ли две структуры `com.aspose.imaging.Rectangle` одинаковое положение и размер. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Проверяет, отличаются ли две структуры `com.aspose.imaging.Rectangle` по положению или размеру. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Создаёт структуру `com.aspose.imaging.Rectangle` с указанными координатами краёв. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) |  |
| [getLocation()](#getLocation--) | Получает или задаёт координаты верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`. |
| [setLocation(Point value)](#setLocation-com.aspose.imaging.Point-) | Получает или задаёт координаты верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`. |
| [getSize()](#getSize--) | Получает или задаёт размер этой `com.aspose.imaging.Rectangle`. |
| [setSize(Size value)](#setSize-com.aspose.imaging.Size-) | Получает или задаёт размер этой `com.aspose.imaging.Rectangle`. |
| [getX()](#getX--) | Получает или задаёт координату x верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`. |
| [setX(int value)](#setX-int-) | Получает или задаёт координату x верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`. |
| [getY()](#getY--) | Получает или задаёт координату y верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`. |
| [setY(int value)](#setY-int-) | Получает или задаёт координату y верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`. |
| [getWidth()](#getWidth--) | Получает ширину этой структуры `com.aspose.imaging.Rectangle`. |
| [setWidth(int value)](#setWidth-int-) | Задаёт ширину этой структуры `com.aspose.imaging.Rectangle`. |
| [getHeight()](#getHeight--) | Получает или задаёт высоту этой структуры `com.aspose.imaging.Rectangle`. |
| [setHeight(int value)](#setHeight-int-) | Получает или задаёт высоту этой структуры `com.aspose.imaging.Rectangle`. |
| [getLeft()](#getLeft--) | Получает или задаёт координату x левой границы этой структуры `com.aspose.imaging.Rectangle`. |
| [setLeft(int value)](#setLeft-int-) | Получает или задаёт координату x левой границы этой структуры `com.aspose.imaging.Rectangle`. |
| [getTop()](#getTop--) | Получает или задаёт координату y верхней границы этой структуры `com.aspose.imaging.Rectangle`. |
| [setTop(int value)](#setTop-int-) | Получает или задаёт координату y верхней границы этой структуры `com.aspose.imaging.Rectangle`. |
| [getRight()](#getRight--) | Получает или задаёт координату x, которая является суммой значений свойств `com.aspose.imaging.Rectangle.X` и `com.aspose.imaging.Rectangle.Width` этой структуры `com.aspose.imaging.Rectangle`. |
| [setRight(int value)](#setRight-int-) | Получает или задаёт координату x, которая является суммой значений свойств `com.aspose.imaging.Rectangle.X` и `com.aspose.imaging.Rectangle.Width` этой структуры `com.aspose.imaging.Rectangle`. |
| [getBottom()](#getBottom--) | Получает или задаёт координату y, которая является суммой значений свойств `com.aspose.imaging.Rectangle.Y` и `com.aspose.imaging.Rectangle.Height` этой структуры `com.aspose.imaging.Rectangle`. |
| [setBottom(int value)](#setBottom-int-) | Получает или задаёт координату y, которая является суммой значений свойств `com.aspose.imaging.Rectangle.Y` и `com.aspose.imaging.Rectangle.Height` этой структуры `com.aspose.imaging.Rectangle`. |
| [isEmpty()](#isEmpty--) | Получает значение, указывающее, имеют ли все числовые свойства этой `com.aspose.imaging.Rectangle` нулевые значения. |
| [contains(int x, int y)](#contains-int-int-) | Определяет, содержится ли указанная точка внутри этой структуры `com.aspose.imaging.Rectangle`. |
| [contains(Point point)](#contains-com.aspose.imaging.Point-) | Определяет, содержится ли указанная точка внутри этой структуры `com.aspose.imaging.Rectangle`. |
| [contains(Rectangle rect)](#contains-com.aspose.imaging.Rectangle-) | Определяет, полностью ли прямоугольный регион, представленный `rect`, содержится внутри этой структуры `com.aspose.imaging.Rectangle`. |
| [inflate(int width, int height)](#inflate-int-int-) | Увеличивает эту `com.aspose.imaging.Rectangle` на указанную величину. |
| [inflate(Size size)](#inflate-com.aspose.imaging.Size-) | Увеличивает эту `com.aspose.imaging.Rectangle` на указанную величину. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Заменяет эту `com.aspose.imaging.Rectangle` пересечением её с указанной `com.aspose.imaging.Rectangle`. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.imaging.Rectangle-) | Определяет, пересекается ли этот прямоугольник с `rect`. |
| [offset(Point pos)](#offset-com.aspose.imaging.Point-) | Корректирует положение этого прямоугольника на указанную величину. |
| [offset(int x, int y)](#offset-int-int-) | Корректирует положение этого прямоугольника на указанную величину. |
| [normalize()](#normalize--) | Нормализует прямоугольник, делая его ширину и высоту положительными, левый край меньше правого и верхний меньше нижнего. |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, является ли `obj` структурой `com.aspose.imaging.Rectangle` с тем же положением и размером, что и эта структура `com.aspose.imaging.Rectangle`. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этой структуры `com.aspose.imaging.Rectangle`. |
| [toString()](#toString--) | Преобразует атрибуты этой `com.aspose.imaging.Rectangle` в читаемую строку. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.imaging.Rectangle-) |  |
| [Clone()](#Clone--) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Инициализирует новый экземпляр структуры `com.aspose.imaging.Rectangle` с указанным расположением и размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x верхнего левого угла прямоугольника. |
| y | int | Координата y верхнего левого угла прямоугольника. |
| width | int | Ширина прямоугольника. |
| height | int | Высота прямоугольника. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public Rectangle(Point location, Size size)
```


Инициализирует новый экземпляр структуры `com.aspose.imaging.Rectangle` с указанным расположением и размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| location | [Point](../../com.aspose.imaging/point) | Объект `com.aspose.imaging.Point`, представляющий верхний левый угол прямоугольной области. |
| size | [Size](../../com.aspose.imaging/size) | Объект `com.aspose.imaging.Size`, представляющий ширину и высоту прямоугольной области. |

### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Получает новый экземпляр структуры `com.aspose.imaging.Rectangle`, у которого значения `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` и `com.aspose.imaging.Rectangle.Height` установлены в ноль.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Создаёт новый `Rectangle` из двух указанных точек. Две вертикали создаваемого `Rectangle` будут равны переданным `point1` и `point2`. Обычно это противоположные вершины.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Первая `Point` для нового прямоугольника. |
| point2 | [Point](../../com.aspose.imaging/point) | Вторая `Point` для нового прямоугольника. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A newly created `Rectangle`.
### ceiling(RectangleF value) {#ceiling-com.aspose.imaging.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Преобразует указанную структуру `com.aspose.imaging.RectangleF` в структуру `com.aspose.imaging.Rectangle`, округляя значения `com.aspose.imaging.RectangleF` до следующего большего целого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура `com.aspose.imaging.RectangleF`, подлежащая конвертации. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - Returns a `com.aspose.imaging.Rectangle`.
### truncate(RectangleF value) {#truncate-com.aspose.imaging.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Преобразует указанный `com.aspose.imaging.RectangleF` в `com.aspose.imaging.Rectangle`, усекнув значения `com.aspose.imaging.RectangleF`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`, подлежащий конвертации. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### round(RectangleF value) {#round-com.aspose.imaging.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Преобразует указанный `com.aspose.imaging.RectangleF` в `com.aspose.imaging.Rectangle`, округляя значения `com.aspose.imaging.RectangleF` до ближайших целых чисел.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`, подлежащий конвертации. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Создаёт и возвращает расширенную копию указанной структуры `com.aspose.imaging.Rectangle`. Копия расширяется на указанную величину. Исходная структура `com.aspose.imaging.Rectangle` остаётся неизменной.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle`, с которым начинается. Этот прямоугольник не изменяется. |
| x | int | Величина горизонтального расширения этого `com.aspose.imaging.Rectangle`. |
| y | int | Величина вертикального расширения этого `com.aspose.imaging.Rectangle`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The inflated `com.aspose.imaging.Rectangle`.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Возвращает третью структуру `com.aspose.imaging.Rectangle`, представляющую пересечение двух других структур `com.aspose.imaging.Rectangle`. Если пересечения нет, возвращается пустой `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Первый прямоугольник для пересечения. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Второй прямоугольник для пересечения. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` that represents the intersection of `a` and `b`.
### union(Rectangle a, Rectangle b) {#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Получает структуру `com.aspose.imaging.Rectangle`, содержащую объединение двух структур `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Первый прямоугольник для объединения. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Второй прямоугольник для объединения. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` structure that bounds the union of the two `com.aspose.imaging.Rectangle` structures.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Проверяет, имеют ли две структуры `com.aspose.imaging.Rectangle` одинаковое положение и размер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `com.aspose.imaging.Rectangle`, находящаяся слева от оператора равенства. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `com.aspose.imaging.Rectangle`, находящаяся справа от оператора равенства. |

**Returns:**
boolean — Этот оператор возвращает true, если две структуры `com.aspose.imaging.Rectangle` имеют одинаковые свойства `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` и `com.aspose.imaging.Rectangle.Height`.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Проверяет, отличаются ли две структуры `com.aspose.imaging.Rectangle` по положению или размеру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `com.aspose.imaging.Rectangle`, находящаяся слева от оператора неравенства. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | Структура `com.aspose.imaging.Rectangle`, находящаяся справа от оператора неравенства. |

**Returns:**
boolean — Этот оператор возвращает true, если любые из свойств `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` или `com.aspose.imaging.Rectangle.Height` двух структур `com.aspose.imaging.Rectangle` не равны; в противном случае — false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Создаёт структуру `com.aspose.imaging.Rectangle` с указанными координатами краёв.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| слева | int | Координата x верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`. |
| сверху | int | Координата y верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`. |
| справа | int | Координата x нижнего правого угла этой структуры `com.aspose.imaging.Rectangle`. |
| снизу | int | Координата y нижнего правого угла этой структуры `com.aspose.imaging.Rectangle`. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The new `com.aspose.imaging.Rectangle` that this method creates.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.imaging/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.imaging/rectangle) |  |

**Returns:**
boolean
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Получает или задаёт координаты верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`.

**Returns:**
[Point](../../com.aspose.imaging/point) - A `com.aspose.imaging.Point` that represents the upper-left corner of this `com.aspose.imaging.Rectangle` structure.
### setLocation(Point value) {#setLocation-com.aspose.imaging.Point-}
```
public void setLocation(Point value)
```


Получает или задаёт координаты верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) | `Point`, представляющий верхний левый угол этой структуры `com.aspose.imaging.Rectangle`. |

### getSize() {#getSize--}
```
public Size getSize()
```


Получает или задаёт размер этой `com.aspose.imaging.Rectangle`.

**Returns:**
[Size](../../com.aspose.imaging/size) - A `com.aspose.imaging.Size` that represents the width and height of this `com.aspose.imaging.Rectangle` structure.
### setSize(Size value) {#setSize-com.aspose.imaging.Size-}
```
public void setSize(Size value)
```


Получает или задаёт размер этой `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) | `com.aspose.imaging.Size`, представляющий ширину и высоту этой структуры `com.aspose.imaging.Rectangle`. |

### getX() {#getX--}
```
public int getX()
```


Получает или задаёт координату x верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`.

**Returns:**
int — Координата x верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Получает или задаёт координату x верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Координата x верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`. |

### getY() {#getY--}
```
public int getY()
```


Получает или задаёт координату y верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`.

**Returns:**
int - Y‑координата верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`.
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Получает или задаёт координату y верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Координата y верхнего левого угла этой структуры `com.aspose.imaging.Rectangle`. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину этой структуры `com.aspose.imaging.Rectangle`.

**Returns:**
int - Ширина этой структуры `com.aspose.imaging.Rectangle`.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Задаёт ширину этой структуры `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Ширина этой структуры `com.aspose.imaging.Rectangle`. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает или задаёт высоту этой структуры `com.aspose.imaging.Rectangle`.

**Returns:**
int - Высота этой структуры `com.aspose.imaging.Rectangle`.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Получает или задаёт высоту этой структуры `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Высота этой структуры `com.aspose.imaging.Rectangle`. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Получает или задаёт координату x левой границы этой структуры `com.aspose.imaging.Rectangle`.

**Returns:**
int - X‑координата левого края этой структуры `com.aspose.imaging.Rectangle`.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Получает или задаёт координату x левой границы этой структуры `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | X‑координата левого края этой структуры `com.aspose.imaging.Rectangle`. |

### getTop() {#getTop--}
```
public int getTop()
```


Получает или задаёт координату y верхней границы этой структуры `com.aspose.imaging.Rectangle`.

**Returns:**
int - Y‑координата верхнего края этой структуры `com.aspose.imaging.Rectangle`.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Получает или задаёт координату y верхней границы этой структуры `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Y‑координата верхнего края этой структуры `com.aspose.imaging.Rectangle`. |

### getRight() {#getRight--}
```
public int getRight()
```


Получает или задаёт координату x, которая является суммой значений свойств `com.aspose.imaging.Rectangle.X` и `com.aspose.imaging.Rectangle.Width` этой структуры `com.aspose.imaging.Rectangle`.

**Returns:**
int - X‑координата, являющаяся суммой `com.aspose.imaging.Rectangle.X` и `com.aspose.imaging.Rectangle.Width` этого `com.aspose.imaging.Rectangle`.
### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Получает или задаёт координату x, которая является суммой значений свойств `com.aspose.imaging.Rectangle.X` и `com.aspose.imaging.Rectangle.Width` этой структуры `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | X‑координата, являющаяся суммой `com.aspose.imaging.Rectangle.X` и `com.aspose.imaging.Rectangle.Width` этого `com.aspose.imaging.Rectangle`. |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Получает или задаёт координату y, которая является суммой значений свойств `com.aspose.imaging.Rectangle.Y` и `com.aspose.imaging.Rectangle.Height` этой структуры `com.aspose.imaging.Rectangle`.

**Returns:**
int - Y‑координата, являющаяся суммой `com.aspose.imaging.Rectangle.Y` и `com.aspose.imaging.Rectangle.Height` этого `com.aspose.imaging.Rectangle`.
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Получает или задаёт координату y, которая является суммой значений свойств `com.aspose.imaging.Rectangle.Y` и `com.aspose.imaging.Rectangle.Height` этой структуры `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Y‑координата, являющаяся суммой `com.aspose.imaging.Rectangle.Y` и `com.aspose.imaging.Rectangle.Height` этого `com.aspose.imaging.Rectangle`. |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Получает значение, указывающее, имеют ли все числовые свойства этой `com.aspose.imaging.Rectangle` нулевые значения.

**Returns:**
boolean - Это свойство возвращает true, если свойства `com.aspose.imaging.Rectangle.Width`, `com.aspose.imaging.Rectangle.Height`, `com.aspose.imaging.Rectangle.X` и `com.aspose.imaging.Rectangle.Y` этого `com.aspose.imaging.Rectangle` имеют значение ноль; в противном случае — false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Определяет, содержится ли указанная точка внутри этой структуры `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |

**Returns:**
boolean - Этот метод возвращает true, если точка, определённая `x` и `y`, находится внутри этой структуры `com.aspose.imaging.Rectangle`; в противном случае — false.
### contains(Point point) {#contains-com.aspose.imaging.Point-}
```
public boolean contains(Point point)
```


Определяет, содержится ли указанная точка внутри этой структуры `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Тестируемый `com.aspose.imaging.Point`. |

**Returns:**
boolean - Этот метод возвращает true, если точка, представленная `point`, находится внутри этой структуры `com.aspose.imaging.Rectangle`; в противном случае — false.
### contains(Rectangle rect) {#contains-com.aspose.imaging.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Определяет, полностью ли прямоугольный регион, представленный `rect`, содержится внутри этой структуры `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Тестируемый `com.aspose.imaging.Rectangle`. |

**Returns:**
boolean - Этот метод возвращает true, если прямоугольный регион, представленный `rect`, полностью находится внутри этой структуры `com.aspose.imaging.Rectangle`; в противном случае — false.
### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Увеличивает эту `com.aspose.imaging.Rectangle` на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Величина горизонтального расширения этого `com.aspose.imaging.Rectangle`. |
| height | int | Величина вертикального расширения этого `com.aspose.imaging.Rectangle`. |

### inflate(Size size) {#inflate-com.aspose.imaging.Size-}
```
public void inflate(Size size)
```


Увеличивает эту `com.aspose.imaging.Rectangle` на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Величина расширения этого прямоугольника. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Заменяет эту `com.aspose.imaging.Rectangle` пересечением её с указанной `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle` для пересечения. |

### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.imaging.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Определяет, пересекается ли этот прямоугольник с `rect`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник для проверки. |

**Returns:**
boolean - Этот метод возвращает true, если существует какое‑либо пересечение, в противном случае — false.
### offset(Point pos) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point pos)
```


Корректирует положение этого прямоугольника на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pos | [Point](../../com.aspose.imaging/point) | Величина смещения положения. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Корректирует положение этого прямоугольника на указанную величину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Горизонтальное смещение. |
| y | int | Вертикальное смещение. |

### normalize() {#normalize--}
```
public void normalize()
```


Нормализует прямоугольник, делая его ширину и высоту положительными, левый край меньше правого и верхний меньше нижнего.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, является ли `obj` структурой `com.aspose.imaging.Rectangle` с тем же положением и размером, что и эта структура `com.aspose.imaging.Rectangle`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект `System.Object` для тестирования. |

**Returns:**
boolean - Этот метод возвращает true, если `obj` является структурой `com.aspose.imaging.Rectangle` и её свойства `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` и `com.aspose.imaging.Rectangle.Height` равны соответствующим свойствам этой структуры `com.aspose.imaging.Rectangle`; в противном случае — false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этой структуры `com.aspose.imaging.Rectangle`.

**Returns:**
int - Целое число, представляющее хеш‑код этого прямоугольника.
### toString() {#toString--}
```
public String toString()
```


Преобразует атрибуты этой `com.aspose.imaging.Rectangle` в читаемую строку.

**Returns:**
java.lang.String - Строка, содержащая позицию, ширину и высоту этой структуры `com.aspose.imaging.Rectangle`.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.imaging.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
