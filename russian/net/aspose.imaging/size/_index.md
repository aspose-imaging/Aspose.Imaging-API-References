---
title: Size
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет размер.
type: docs
weight: 11050
url: /ru/net/aspose.imaging/size/
---
## Size structure

Представляет размер.

```csharp
public struct Size
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Size](size#constructor)(Point) | Инициализирует новый экземпляр структуры[`Size`](../size)из указаннойТочка. |
| [Size](size#constructor_1)(int, int) | Инициализирует новый экземпляр структуры[`Size`](../size)из указанных измерений. |

## Характеристики

| Имя | Описание |
| --- | --- |
| static [Empty](../../aspose.imaging/size/empty) { get; } | Получает новый экземпляр структуры[`Size`](../size)сWidthи[`Height`](./height)равны нулю. |
| [Height](../../aspose.imaging/size/height) { get; set; } | Получает или задает вертикальный компонент этого[`Size`](../size). |
| [IsEmpty](../../aspose.imaging/size/isempty) { get; } | Получает значение, указывающее, имеет ли этот[`Size`](../size)ширину и высоту 0. |
| [Width](../../aspose.imaging/size/width) { get; set; } | Получает или задает горизонтальный компонент этого[`Size`](../size). |

## Методы

| Имя | Описание |
| --- | --- |
| static [Add](../../aspose.imaging/size/add)(Size, Size) | Добавляет ширину и высоту одной[`Size`](../size)структуры к ширине и высоте другой[`Size`](../size)структура. |
| static [Ceiling](../../aspose.imaging/size/ceiling)(SizeF) | Преобразует указанную структуру[`SizeF`](../sizef)в структуру[`Size`](../size)структура путем округления значений структуры[`Size`](../size)до следующего большего целочисленного значения. |
| static [Round](../../aspose.imaging/size/round)(SizeF) | Преобразует указанную структуру[`SizeF`](../sizef)в структуру[`Size`](../size)путем округления значений структуры[`SizeF`](../sizef)до ближайших целых значений. |
| static [Subtract](../../aspose.imaging/size/subtract)(Size, Size) | Вычитает ширину и высоту одной[`Size`](../size)структуры из ширины и высоты другой[`Size`](../size)структура. |
| static [Truncate](../../aspose.imaging/size/truncate)(SizeF) | Преобразует указанную структуру[`SizeF`](../sizef)в структуру[`Size`](../size)усекая значения структуры[`SizeF`](../sizef)до следующих меньших целых значений. |
| override [Equals](../../aspose.imaging/size/equals)(object) | Проверяет, является ли указанный объект объектом[`Size`](../size)с такими же размерами, как этот[`Size`](../size). |
| override [GetHashCode](../../aspose.imaging/size/gethashcode)() | Возвращает хэш-код для этой[`Size`](../size)структуры. |
| override [ToString](../../aspose.imaging/size/tostring)() | Создает удобочитаемую строку, которая представляет этот[`Size`](../size). |
| [operator +](../../aspose.imaging/size/op_addition) | Добавляет ширину и высоту одной[`Size`](../size)структуры к ширине и высоте другой[`Size`](../size)структура. |
| [operator ==](../../aspose.imaging/size/op_equality) | Проверяет, равны ли две структуры[`Size`](../size). |
| [explicit operator](../../aspose.imaging/size/op_explicit) | Преобразует указанный[`Size`](../size)в[`Point`](../point). |
| [implicit operator](../../aspose.imaging/size/op_implicit) | Преобразует указанный[`Size`](../size)в[`SizeF`](../sizef). |
| [operator !=](../../aspose.imaging/size/op_inequality) | Проверяет, различаются ли две структуры[`Size`](../size). |
| [operator -](../../aspose.imaging/size/op_subtraction) | Вычитает ширину и высоту одной[`Size`](../size)структуры из ширины и высоты другой[`Size`](../size)структура. |

### Смотрите также

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
