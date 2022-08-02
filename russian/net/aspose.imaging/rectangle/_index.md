---
title: Rectangle
second_title: Справочник по Aspose.Imaging for .NET API
description: Хранит набор из четырех целых чисел представляющих расположение и размер прямоугольника.
type: docs
weight: 10830
url: /ru/net/aspose.imaging/rectangle/
---
## Rectangle structure

Хранит набор из четырех целых чисел, представляющих расположение и размер прямоугольника.

```csharp
public struct Rectangle
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | Инициализирует новый экземпляр[`Rectangle`](../rectangle) структура с указанным расположением и размером. |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | Инициализирует новый экземпляр[`Rectangle`](../rectangle) структура с указанным расположением и размером. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.imaging/rectangle/empty) { get; } | Получает новый экземпляр[`Rectangle`](../rectangle) структура, которая имеет[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) а также[`Height`](./height) значения равны нулю. |
| [Bottom](../../aspose.imaging/rectangle/bottom) { get; set; } | Получает или задает координату y, которая является суммой[`Y`](./y) а также[`Height`](./height) значения свойств этого[`Rectangle`](../rectangle) структура. |
| [Height](../../aspose.imaging/rectangle/height) { get; set; } | Получает или задает высоту этого[`Rectangle`](../rectangle) структура. |
| [IsEmpty](../../aspose.imaging/rectangle/isempty) { get; } | Получает значение, указывающее, все ли числовые свойства этого[`Rectangle`](../rectangle) имеют нулевые значения. |
| [Left](../../aspose.imaging/rectangle/left) { get; set; } | Получает или задает x-координату левого края этого[`Rectangle`](../rectangle) структура. |
| [Location](../../aspose.imaging/rectangle/location) { get; set; } | Получает или задает координаты левого верхнего угла этого[`Rectangle`](../rectangle) структура. |
| [Right](../../aspose.imaging/rectangle/right) { get; set; } | Получает или задает координату x, которая является суммой[`X`](./x) а также[`Width`](./width) значения свойств этого[`Rectangle`](../rectangle) структура. |
| [Size](../../aspose.imaging/rectangle/size) { get; set; } | Получает или задает размер этого[`Rectangle`](../rectangle) . |
| [Top](../../aspose.imaging/rectangle/top) { get; set; } | Получает или задает координату y верхнего края этого[`Rectangle`](../rectangle) структура. |
| [Width](../../aspose.imaging/rectangle/width) { get; set; } | Получает или задает ширину этого[`Rectangle`](../rectangle) структура. |
| [X](../../aspose.imaging/rectangle/x) { get; set; } | Получает или задает x-координату левого верхнего угла этого[`Rectangle`](../rectangle) структура. |
| [Y](../../aspose.imaging/rectangle/y) { get; set; } | Получает или задает координату Y верхнего левого угла этого[`Rectangle`](../rectangle) структура. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Ceiling](../../aspose.imaging/rectangle/ceiling)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef) структура к[`Rectangle`](../rectangle) структура путем округления[`RectangleF`](../rectanglef) значения до следующего более высокого целочисленного значения. |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectangle/fromlefttoprightbottom)(int, int, int, int) | Создает[`Rectangle`](../rectangle) структура с указанными местоположениями ребер. |
| static [FromPoints](../../aspose.imaging/rectangle/frompoints)(Point, Point) | Создает новый[`Rectangle`](../rectangle) из двух указанных точек. Две вертикали созданного[`Rectangle`](../rectangle) будет равно переданному*point1* а также*point2* . Обычно это противоположные вершины. |
| static [Inflate](../../aspose.imaging/rectangle/inflate)(Rectangle, int, int) | Создает и возвращает увеличенную копию указанного[`Rectangle`](../rectangle) структура. Копия завышена на указанную сумму. Оригинал[`Rectangle`](../rectangle) структура остается неизменной. |
| static [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle, Rectangle) | Возвращает третий[`Rectangle`](../rectangle) структура, которая представляет собой пересечение двух других[`Rectangle`](../rectangle) структуры. Если пересечения нет, то пустой[`Rectangle`](../rectangle) возвращается. |
| static [Round](../../aspose.imaging/rectangle/round)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef) к[`Rectangle`](../rectangle) путем округления[`RectangleF`](../rectanglef)значения до ближайших целочисленных значений. |
| static [Truncate](../../aspose.imaging/rectangle/truncate)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef) к[`Rectangle`](../rectangle) путем усечения[`RectangleF`](../rectanglef) значения. |
| static [Union](../../aspose.imaging/rectangle/union)(Rectangle, Rectangle) | Получает[`Rectangle`](../rectangle) структура, содержащая объединение двух[`Rectangle`](../rectangle) структуры. |
| [Contains](../../aspose.imaging/rectangle/contains#contains)(Point) | Определяет, содержится ли указанная точка в этом[`Rectangle`](../rectangle) структура. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_1)(Rectangle) | Определяет, является ли прямоугольная область, представленная*rect* полностью содержится в этом[`Rectangle`](../rectangle) структура. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_2)(int, int) | Определяет, содержится ли указанная точка в этом[`Rectangle`](../rectangle) структура. |
| override [Equals](../../aspose.imaging/rectangle/equals)(object) | Проверяет,*obj* это[`Rectangle`](../rectangle)структура с тем же расположением и размером этого[`Rectangle`](../rectangle) структура. |
| override [GetHashCode](../../aspose.imaging/rectangle/gethashcode)() | Возвращает хеш-код для этого[`Rectangle`](../rectangle) структура. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate)(Size) | раздувает это[`Rectangle`](../rectangle) на указанную сумму. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate_1)(int, int) | раздувает это[`Rectangle`](../rectangle) на указанную сумму. |
| [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle) | Заменяет это[`Rectangle`](../rectangle) с пересечением себя и указанного[`Rectangle`](../rectangle) . |
| [IntersectsWith](../../aspose.imaging/rectangle/intersectswith)(Rectangle) | Определяет, пересекается ли этот прямоугольник с*rect* . |
| [Normalize](../../aspose.imaging/rectangle/normalize)() | Нормализует прямоугольник, делая его ширину и высоту положительными, слева меньше, чем справа, а верх меньше, чем низ. |
| [Offset](../../aspose.imaging/rectangle/offset#offset)(Point) | Изменяет положение этого прямоугольника на указанную величину. |
| [Offset](../../aspose.imaging/rectangle/offset#offset_1)(int, int) | Изменяет положение этого прямоугольника на указанную величину. |
| override [ToString](../../aspose.imaging/rectangle/tostring)() | Преобразует атрибуты этого[`Rectangle`](../rectangle) в удобочитаемую строку. |
| [operator ==](../../aspose.imaging/rectangle/op_equality) | Проверяет, являются ли два[`Rectangle`](../rectangle)структуры имеют одинаковое расположение и размер. |
| [operator !=](../../aspose.imaging/rectangle/op_inequality) | Проверяет, являются ли два[`Rectangle`](../rectangle) структуры отличаются расположением или размером. |

### Смотрите также

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
