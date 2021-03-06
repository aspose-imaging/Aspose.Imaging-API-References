---
title: Point
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет упорядоченную пару целых чисел x- и y-координат определяющую точку на двумерной плоскости.
type: docs
weight: 10750
url: /ru/net/aspose.imaging/point/
---
## Point structure

Представляет упорядоченную пару целых чисел x- и y-координат, определяющую точку на двумерной плоскости.

```csharp
public struct Point
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Point](point#constructor_1)(int) | Инициализирует новый экземпляр структуры[`Point`](../point), используя координаты, заданные целочисленным значением. |
| [Point](point#constructor)(Size) | Инициализирует новый экземпляр структуры[`Point`](../point)изРазмерструктура. |
| [Point](point#constructor_2)(int, int) | Инициализирует новый экземпляр структуры[`Point`](../point)с указанными координатами. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.imaging/point/empty) { get; } | Получает новый экземпляр структуры[`Point`](../point)сXи[`Y`](./y)равны нулю. |
| [IsEmpty](../../aspose.imaging/point/isempty) { get; } | Получает значение, указывающее, является ли этот[`Point`](../point)пустым. |
| [X](../../aspose.imaging/point/x) { get; set; } | Получает или задает координату x этого[`Point`](../point). |
| [Y](../../aspose.imaging/point/y) { get; set; } | Получает или задает координату y этого[`Point`](../point). |

## Методы

| Имя | Описание |
| --- | --- |
| static [Add](../../aspose.imaging/point/add)(Point, Size) | Добавляет указанный[`Size`](../size)к указанному[`Point`](../point). |
| static [Ceiling](../../aspose.imaging/point/ceiling)(PointF) | Преобразует указанный[`PointF`](../pointf)в[`Point`](../point)путем округления значений[`PointF`](../pointf)до следующего большего целочисленного значения. |
| static [Round](../../aspose.imaging/point/round)(PointF) | Преобразует указанный[`PointF`](../pointf)в[`Point`](../point)объекта путем округления значений[`Point`](../point)до ближайшего целого числа. |
| static [Subtract](../../aspose.imaging/point/subtract)(Point, Size) | Возвращает результат вычитания указанного[`Size`](../size)из указанногоТочка. |
| static [Truncate](../../aspose.imaging/point/truncate)(PointF) | Преобразует указанный[`PointF`](../pointf)в[`Point`](../point)путем усечения значений[`Point`](../point). |
| override [Equals](../../aspose.imaging/point/equals)(object) | Указывает, содержит ли этот[`Point`](../point)те же координаты, что и указанныйObject. |
| override [GetHashCode](../../aspose.imaging/point/gethashcode)() | Возвращает хэш-код для этого[`Point`](../point). |
| [Offset](../../aspose.imaging/point/offset#offset)(Point) | Переводит это[`Point`](../point)по указанному[`Point`](../point). |
| [Offset](../../aspose.imaging/point/offset#offset_1)(int, int) | Переводит это[`Point`](../point)на указанную сумму. |
| override [ToString](../../aspose.imaging/point/tostring)() | Преобразует это[`Point`](../point)в удобочитаемую строку. |
| [operator +](../../aspose.imaging/point/op_addition) | Переводит[`Point`](../point)на указанный[`Size`](../size). |
| [operator ==](../../aspose.imaging/point/op_equality) | Сравнивает два объекта[`Point`](../point). Результат указывает, соответствуют ли значения свойств[`X`](./x)и[`Y`](./y)двух[`Point`](../point)объекты равны. |
| [explicit operator](../../aspose.imaging/point/op_explicit) | Преобразует указанную структуру[`Point`](../point)в структуру[`Size`](../size)структура. |
| [implicit operator](../../aspose.imaging/point/op_implicit) | Преобразует указанную структуру[`Point`](../point)в структуру[`PointF`](../pointf)структура. |
| [operator !=](../../aspose.imaging/point/op_inequality) | Сравнивает два объекта[`Point`](../point). Результат указывает, будут ли значения свойств[`X`](./x)или[`Y`](./y)двух[`Point`](../point)объекты не равны. |
| [operator -](../../aspose.imaging/point/op_subtraction) | Переводит[`Point`](../point)на отрицательную величину заданного[`Size`](../size). |

### Смотрите также

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
