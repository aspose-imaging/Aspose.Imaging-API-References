---
title: RectangleF
second_title: Справочник по Aspose.Imaging for .NET API
description: Хранит набор из четырех чисел с плавающей запятой которые представляют положение и размер прямоугольника.
type: docs
weight: 10840
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
| [RectangleF](rectanglef#constructor)(PointF, SizeF) | Инициализирует новый экземпляр[`RectangleF`](../rectanglef) структура с указанным расположением и размером. |
| [RectangleF](rectanglef#constructor_1)(float, float, float, float) | Инициализирует новый экземпляр[`RectangleF`](../rectanglef) структура с указанным расположением и размером. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.imaging/rectanglef/empty) { get; } | Получает новый экземпляр[`RectangleF`](../rectanglef) структура, которая имеет[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) а также[`Height`](./height) значения равны нулю. |
| [Bottom](../../aspose.imaging/rectanglef/bottom) { get; set; } | Получает или задает координату y, которая является суммой[`Y`](./y) а также[`Height`](./height) этого[`RectangleF`](../rectanglef) структура. |
| [Height](../../aspose.imaging/rectanglef/height) { get; set; } | Получает или задает высоту этого[`RectangleF`](../rectanglef) структура. |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty) { get; } | Получает значение, указывающее,[`Width`](./width) или же[`Height`](./height) свойство этого[`RectangleF`](../rectanglef) имеет нулевое значение. |
| [Left](../../aspose.imaging/rectanglef/left) { get; set; } | Получает или задает x-координату левого края этого[`RectangleF`](../rectanglef) структура. |
| [Location](../../aspose.imaging/rectanglef/location) { get; set; } | Получает или задает координаты левого верхнего угла этого[`RectangleF`](../rectanglef) структура. |
| [Right](../../aspose.imaging/rectanglef/right) { get; set; } | Получает или задает координату x, которая является суммой[`X`](./x) а также[`Width`](./width) этого[`RectangleF`](../rectanglef) структура. |
| [Size](../../aspose.imaging/rectanglef/size) { get; set; } | Получает или задает размер этого[`RectangleF`](../rectanglef) . |
| [Top](../../aspose.imaging/rectanglef/top) { get; set; } | Получает или задает координату y верхнего края этого[`RectangleF`](../rectanglef) структура. |
| [Width](../../aspose.imaging/rectanglef/width) { get; set; } | Получает или задает ширину этого[`RectangleF`](../rectanglef) структура. |
| [X](../../aspose.imaging/rectanglef/x) { get; set; } | Получает или задает x-координату левого верхнего угла этого[`RectangleF`](../rectanglef) структура. |
| [Y](../../aspose.imaging/rectanglef/y) { get; set; } | Получает или задает координату Y верхнего левого угла этого[`RectangleF`](../rectanglef) структура. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom)(float, float, float, float) | Создает[`RectangleF`](../rectanglef) структура с левым верхним и правым нижним углами в указанных местах. |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints)(PointF, PointF) | Создает новый[`Rectangle`](../rectangle) из двух указанных точек. Две вершины созданного[`Rectangle`](../rectangle) будет равно переданному*point1* а также*point2* . Обычно это противоположные вершины. |
| static [Inflate](../../aspose.imaging/rectanglef/inflate)(RectangleF, float, float) | Создает и возвращает увеличенную копию указанного[`RectangleF`](../rectanglef)структура. Копия завышена на указанную сумму. Исходный прямоугольник остается без изменений. |
| static [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF, RectangleF) | Возвращает[`RectangleF`](../rectanglef) структура, представляющая собой пересечение двух прямоугольников. Если пересечения нет и пусто[`RectangleF`](../rectanglef) возвращается. |
| static [Union](../../aspose.imaging/rectanglef/union)(RectangleF, RectangleF) | Создает наименьший возможный третий прямоугольник, который может содержать оба прямоугольника, образующие объединение. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains)(PointF) | Определяет, содержится ли указанная точка в этом[`RectangleF`](../rectanglef) структура. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_1)(RectangleF) | Определяет, является ли прямоугольная область, представленная*rect* полностью содержится в этом[`RectangleF`](../rectanglef) структура. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_2)(float, float) | Определяет, содержится ли указанная точка в этом[`RectangleF`](../rectanglef) структура. |
| override [Equals](../../aspose.imaging/rectanglef/equals)(object) | Проверяет,*obj* это[`RectangleF`](../rectanglef) с таким же расположением и размером этого[`RectangleF`](../rectanglef) . |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode)() | Получает хэш-код для этого[`RectangleF`](../rectanglef) структура. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate)(SizeF) | раздувает это[`RectangleF`](../rectanglef) на указанную сумму. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate_1)(float, float) | раздувает это[`RectangleF`](../rectanglef) структуру на указанную сумму. |
| [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF) | Заменяет это[`RectangleF`](../rectanglef)структура с пересечением себя и заданного[`RectangleF`](../rectanglef) структура. |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith)(RectangleF) | Определяет, пересекается ли этот прямоугольник с*rect* . |
| [Normalize](../../aspose.imaging/rectanglef/normalize)() | Нормализует прямоугольник, делая его ширину и высоту положительными, слева меньше, чем справа, а верх меньше, чем низ. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset)(PointF) | Изменяет положение этого прямоугольника на указанную величину. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset_1)(float, float) | Изменяет положение этого прямоугольника на указанную величину. |
| override [ToString](../../aspose.imaging/rectanglef/tostring)() | Преобразует атрибуты этого[`RectangleF`](../rectanglef) в удобочитаемую строку. |
| [operator /](../../aspose.imaging/rectanglef/op_division) | Реализует оператор /. |
| [operator ==](../../aspose.imaging/rectanglef/op_equality) | Проверяет, являются ли два[`RectangleF`](../rectanglef)структуры имеют одинаковое расположение и размер. |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit) | Преобразует указанный[`Rectangle`](../rectangle) структура к[`RectangleF`](../rectanglef) структура. |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality) | Проверяет, являются ли два[`RectangleF`](../rectanglef) структуры отличаются расположением или размером. |
| [operator *](../../aspose.imaging/rectanglef/op_multiply) | Реализует оператор *. |

### Смотрите также

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
