---
title: Rectangle
second_title: Справочник по Aspose.Imaging for .NET API
description: Сохраняет набор из четырех целых чисел представляющих расположение и размер прямоугольника.
type: docs
weight: 10840
url: /ru/net/aspose.imaging/rectangle/
---
## Rectangle structure

Сохраняет набор из четырех целых чисел, представляющих расположение и размер прямоугольника.

```csharp
public struct Rectangle
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | Инициализирует новый экземпляр структуры[`Rectangle`](../rectangle)с указанным расположением и размером. |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | Инициализирует новый экземпляр структуры[`Rectangle`](../rectangle)с указанным расположением и размером. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.imaging/rectangle/empty) { get; } | Получает новый экземпляр структуры[`Rectangle`](../rectangle)с[`X`](./x),[`Y`](./y),[`Width`](./width)иHeightравны нулю. |
| [Bottom](../../aspose.imaging/rectangle/bottom) { get; set; } | Получает или задает координату y, которая является суммой[`Y`](./y)и[`Height`](./height)значения свойств этой[`Rectangle`](../rectangle)структуры. |
| [Height](../../aspose.imaging/rectangle/height) { get; set; } | Получает или задает высоту этой[`Rectangle`](../rectangle)структуры. |
| [IsEmpty](../../aspose.imaging/rectangle/isempty) { get; } | Получает значение, указывающее, имеют ли все числовые свойства этого[`Rectangle`](../rectangle)нулевые значения. |
| [Left](../../aspose.imaging/rectangle/left) { get; set; } | Получает или задает x-координату левого края этой[`Rectangle`](../rectangle)структуры. |
| [Location](../../aspose.imaging/rectangle/location) { get; set; } | Получает или задает координаты верхнего левого угла этой[`Rectangle`](../rectangle)структуры. |
| [Right](../../aspose.imaging/rectangle/right) { get; set; } | Получает или задает координату x, которая является суммой[`X`](./x)и[`Width`](./width)значения свойств этой[`Rectangle`](../rectangle)структуры. |
| [Size](../../aspose.imaging/rectangle/size) { get; set; } | Получает или задает размер этого[`Rectangle`](../rectangle). |
| [Top](../../aspose.imaging/rectangle/top) { get; set; } | Получает или задает координату y верхнего края этой[`Rectangle`](../rectangle)структуры. |
| [Width](../../aspose.imaging/rectangle/width) { get; set; } | Получает или задает ширину этой[`Rectangle`](../rectangle)структуры. |
| [X](../../aspose.imaging/rectangle/x) { get; set; } | Получает или задает координату x левого верхнего угла этой[`Rectangle`](../rectangle)структуры. |
| [Y](../../aspose.imaging/rectangle/y) { get; set; } | Получает или задает координату y верхнего левого угла этой[`Rectangle`](../rectangle)структуры. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Ceiling](../../aspose.imaging/rectangle/ceiling)(RectangleF) | Преобразует указанную структуру[`RectangleF`](../rectanglef)в[`Rectangle`](../rectangle)структура путем округления значений[`RectangleF`](../rectanglef)до следующего большего целочисленного значения. |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectangle/fromlefttoprightbottom)(int, int, int, int) | Создает структуру[`Rectangle`](../rectangle)с указанными местоположениями ребер. |
| static [FromPoints](../../aspose.imaging/rectangle/frompoints)(Point, Point) | Создает новый[`Rectangle`](../rectangle)из двух указанных точек. Две вертикали созданного[`Rectangle`](../rectangle)будут равны переданным*point1*и*point2*. Обычно это противоположные вершины. |
| static [Inflate](../../aspose.imaging/rectangle/inflate)(Rectangle, int, int) | Создает и возвращает увеличенную копию указанной[`Rectangle`](../rectangle)структуры. Копия завышена на указанную сумму. Исходная структура[`Rectangle`](../rectangle)остается неизменной. |
| static [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle, Rectangle) | Возвращает третью структуру[`Rectangle`](../rectangle), представляющую пересечение двух других[`Rectangle`](../rectangle)структуры. Если пересечения нет, возвращается пустой[`Rectangle`](../rectangle). |
| static [Round](../../aspose.imaging/rectangle/round)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef)в[`Rectangle`](../rectangle)путем округления значений[`RectangleF`](../rectanglef)до ближайших целых значений. |
| static [Truncate](../../aspose.imaging/rectangle/truncate)(RectangleF) | Преобразует указанный[`RectangleF`](../rectanglef)в[`Rectangle`](../rectangle)путем усечения значений[`RectangleF`](../rectanglef). |
| static [Union](../../aspose.imaging/rectangle/union)(Rectangle, Rectangle) | Получает структуру[`Rectangle`](../rectangle), содержащую объединение двухПрямоугольникструктуры. |
| [Contains](../../aspose.imaging/rectangle/contains#contains)(Point) | Определяет, содержится ли указанная точка в этой[`Rectangle`](../rectangle)структуре. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_1)(Rectangle) | Определяет, содержится ли прямоугольная область, представленная*rect*полностью внутри этого[`Rectangle`](../rectangle)структура. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_2)(int, int) | Определяет, содержится ли указанная точка в этой[`Rectangle`](../rectangle)структуре. |
| override [Equals](../../aspose.imaging/rectangle/equals)(object) | Проверяет, является ли*obj*структурой[`Rectangle`](../rectangle)с тем же расположением и размером этой[`Rectangle`](../rectangle)структуры. |
| override [GetHashCode](../../aspose.imaging/rectangle/gethashcode)() | Возвращает хеш-код для этой[`Rectangle`](../rectangle)структуры. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate)(Size) | Увеличивает этот[`Rectangle`](../rectangle)на указанную величину. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate_1)(int, int) | Увеличивает этот[`Rectangle`](../rectangle)на указанную величину. |
| [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle) | Заменяет это[`Rectangle`](../rectangle)пересечением самого себя и указанногоПрямоугольник. |
| [IntersectsWith](../../aspose.imaging/rectangle/intersectswith)(Rectangle) | Определяет, пересекается ли этот прямоугольник с*rect*. |
| [Normalize](../../aspose.imaging/rectangle/normalize)() | Нормализует прямоугольник, делая его ширину и высоту положительными, слева меньше, чем справа, а верх меньше, чем низ. |
| [Offset](../../aspose.imaging/rectangle/offset#offset)(Point) | Изменяет положение этого прямоугольника на указанную величину. |
| [Offset](../../aspose.imaging/rectangle/offset#offset_1)(int, int) | Изменяет положение этого прямоугольника на указанную величину. |
| override [ToString](../../aspose.imaging/rectangle/tostring)() | Преобразует атрибуты этого[`Rectangle`](../rectangle)в удобочитаемую строку. |
| [operator ==](../../aspose.imaging/rectangle/op_equality) | Проверяет, имеют ли две структуры[`Rectangle`](../rectangle)одинаковое расположение и размер. |
| [operator !=](../../aspose.imaging/rectangle/op_inequality) | Проверяет, различаются ли две структуры[`Rectangle`](../rectangle)расположением или размером. |

### Смотрите также

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
