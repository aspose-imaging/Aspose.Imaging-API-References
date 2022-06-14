---
title: RectangleF
second_title: Справочник по Aspose.Imaging for .NET API
description: Хранит набор из четырех чисел с плавающей запятой которые представляют положение и размер прямоугольника.
type: docs
weight: 10850
url: /ru/net/aspose.imaging/rectanglef/
---
## RectangleF structure

Хранит набор из четырех чисел с плавающей запятой, которые представляют положение и размер прямоугольника.

```csharp
public struct RectangleF
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RectangleF](rectanglef#constructor)(PointF, SizeF) | Инициализирует новый экземпляр структуры[`RectangleF`](../rectanglef)с указанным расположением и размером. |
| [RectangleF](rectanglef#constructor_1)(float, float, float, float) | Инициализирует новый экземпляр структуры[`RectangleF`](../rectanglef)с указанным расположением и размером. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.imaging/rectanglef/empty) { get; } | Получает новый экземпляр структуры[`RectangleF`](../rectanglef)с[`X`](./x),[`Y`](./y),[`Width`](./width)иHeightравны нулю. |
| [Bottom](../../aspose.imaging/rectanglef/bottom) { get; set; } | Получает или задает координату y, которая является суммой[`Y`](./y)и[`Height`](./height)этой[`RectangleF`](../rectanglef)структуры. |
| [Height](../../aspose.imaging/rectanglef/height) { get; set; } | Получает или задает высоту этой[`RectangleF`](../rectanglef)структуры. |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty) { get; } | Получает значение, указывающее, является ли[`Width`](./width)или[`Height`](./height)свойство этого[`RectangleF`](../rectanglef)имеет нулевое значение. |
| [Left](../../aspose.imaging/rectanglef/left) { get; set; } | Получает или задает координату x левого края этой[`RectangleF`](../rectanglef)структуры. |
| [Location](../../aspose.imaging/rectanglef/location) { get; set; } | Получает или задает координаты верхнего левого угла этой[`RectangleF`](../rectanglef)структуры. |
| [Right](../../aspose.imaging/rectanglef/right) { get; set; } | Получает или задает координату x, которая является суммой[`X`](./x)и[`Width`](./width)этой[`RectangleF`](../rectanglef)структуры. |
| [Size](../../aspose.imaging/rectanglef/size) { get; set; } | Получает или задает размер этого[`RectangleF`](../rectanglef). |
| [Top](../../aspose.imaging/rectanglef/top) { get; set; } | Получает или задает координату y верхнего края этой[`RectangleF`](../rectanglef)структуры. |
| [Width](../../aspose.imaging/rectanglef/width) { get; set; } | Получает или задает ширину этой[`RectangleF`](../rectanglef)структуры. |
| [X](../../aspose.imaging/rectanglef/x) { get; set; } | Получает или задает координату x левого верхнего угла этой[`RectangleF`](../rectanglef)структуры. |
| [Y](../../aspose.imaging/rectanglef/y) { get; set; } | Получает или задает координату y верхнего левого угла этой[`RectangleF`](../rectanglef)структуры. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom)(float, float, float, float) | Создает структуру[`RectangleF`](../rectanglef)с левым верхним и правым нижним углами в указанных местах. |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints)(PointF, PointF) | Создает новый[`Rectangle`](../rectangle)из двух указанных точек. Две вершины созданного[`Rectangle`](../rectangle)будут равны переданным*point1*и*point2*. Обычно это противоположные вершины. |
| static [Inflate](../../aspose.imaging/rectanglef/inflate)(RectangleF, float, float) | Создает и возвращает увеличенную копию указанной[`RectangleF`](../rectanglef)структуры. Копия завышена на указанную сумму. Исходный прямоугольник остается неизменным. |
| static [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF, RectangleF) | Возвращает структуру[`RectangleF`](../rectanglef), представляющую пересечение двух прямоугольников. Если пересечения нет и возвращается пустой[`RectangleF`](../rectanglef). |
| static [Union](../../aspose.imaging/rectanglef/union)(RectangleF, RectangleF) | Создает наименьший возможный третий прямоугольник, который может содержать два прямоугольника, образующих объединение. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains)(PointF) | Определяет, содержится ли указанная точка в этой[`RectangleF`](../rectanglef)структуре. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_1)(RectangleF) | Определяет, содержится ли прямоугольная область, представленная*rect*полностью внутри этого[`RectangleF`](../rectanglef)структура. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_2)(float, float) | Определяет, содержится ли указанная точка в этой[`RectangleF`](../rectanglef)структуре. |
| override [Equals](../../aspose.imaging/rectanglef/equals)(object) | Проверяет, является ли*obj*объектом[`RectangleF`](../rectanglef)с тем же расположением и размером это[`RectangleF`](../rectanglef). |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode)() | Получает хеш-код для этой[`RectangleF`](../rectanglef)структуры. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate)(SizeF) | Увеличивает это[`RectangleF`](../rectanglef)на указанную величину. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate_1)(float, float) | Раздувает эту структуру[`RectangleF`](../rectanglef)на указанную величину. |
| [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF) | Заменяет эту структуру[`RectangleF`](../rectanglef)пересечением самой себя и указанной[`RectangleF`](../rectanglef)структура. |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith)(RectangleF) | Определяет, пересекается ли этот прямоугольник с*rect*. |
| [Normalize](../../aspose.imaging/rectanglef/normalize)() | Нормализует прямоугольник, делая его ширину и высоту положительными, слева меньше, чем справа, а верх меньше, чем низ. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset)(PointF) | Изменяет положение этого прямоугольника на указанную величину. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset_1)(float, float) | Изменяет положение этого прямоугольника на указанную величину. |
| override [ToString](../../aspose.imaging/rectanglef/tostring)() | Преобразует атрибуты этого[`RectangleF`](../rectanglef)в удобочитаемую строку. |
| [operator /](../../aspose.imaging/rectanglef/op_division) | Реализует оператор /. |
| [operator ==](../../aspose.imaging/rectanglef/op_equality) | Проверяет, имеют ли две структуры[`RectangleF`](../rectanglef)одинаковое расположение и размер. |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit) | Преобразует указанную структуру[`Rectangle`](../rectangle)в[`RectangleF`](../rectanglef)структура. |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality) | Проверяет, различаются ли две структуры[`RectangleF`](../rectanglef)расположением или размером. |
| [operator *](../../aspose.imaging/rectanglef/op_multiply) | Реализует оператор *. |

### Смотрите также

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
