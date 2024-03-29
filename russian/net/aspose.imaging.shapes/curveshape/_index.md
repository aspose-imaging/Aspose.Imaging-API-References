---
title: CurveShape
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет форму изогнутого сплайна.
type: docs
weight: 10970
url: /ru/net/aspose.imaging.shapes/curveshape/
---
## CurveShape class

Представляет форму изогнутого сплайна.

```csharp
public sealed class CurveShape : PolygonShape
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [CurveShape](curveshape#constructor)() | Инициализирует новый экземпляр[`CurveShape`](../curveshape) класс. |
| [CurveShape](curveshape#constructor_1)(PointF[]) | Инициализирует новый экземпляр[`CurveShape`](../curveshape) учебный класс. Используется натяжение по умолчанию 0,5. |
| [CurveShape](curveshape#constructor_2)(PointF[], bool) | Инициализирует новый экземпляр[`CurveShape`](../curveshape) учебный класс. Используется натяжение по умолчанию 0,5. |
| [CurveShape](curveshape#constructor_3)(PointF[], float) | Инициализирует новый экземпляр[`CurveShape`](../curveshape) класс. |
| [CurveShape](curveshape#constructor_4)(PointF[], float, bool) | Инициализирует новый экземпляр[`CurveShape`](../curveshape) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/curveshape/bounds) { get; } | Получает границы объекта. |
| override [Center](../../aspose.imaging.shapes/curveshape/center) { get; } | Получает центр фигуры. |
| virtual [EndPoint](../../aspose.imaging.shapes/polygonshape/endpoint) { get; } | Получает конечную точку формы. |
| override [HasSegments](../../aspose.imaging.shapes/polygonshape/hassegments) { get; } | Получает значение, указывающее, есть ли у фигуры сегменты. |
| [IsClosed](../../aspose.imaging.shapes/polygonshape/isclosed) { get; set; } | Получает или задает значение, указывающее, закрыта ли фигура. |
| [Points](../../aspose.imaging.shapes/polygonshape/points) { get; set; } | Получает или задает точки кривой. |
| override [Segments](../../aspose.imaging.shapes/curveshape/segments) { get; } | Получает сегменты формы. |
| virtual [StartPoint](../../aspose.imaging.shapes/polygonshape/startpoint) { get; } | Получает начальную точку формы. |
| [Tension](../../aspose.imaging.shapes/curveshape/tension) { get; set; } | Получает или задает натяжение кривой. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/curveshape/getbounds#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.imaging.shapes/curveshape/getbounds#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [Reverse](../../aspose.imaging.shapes/polygonshape/reverse)() | Меняет порядок точек этой фигуры на обратный. |
| override [Transform](../../aspose.imaging.shapes/polygonshape/transform)(Matrix) | Применяет указанное преобразование к фигуре. |

### Смотрите также

* class [PolygonShape](../polygonshape)
* пространство имен [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
