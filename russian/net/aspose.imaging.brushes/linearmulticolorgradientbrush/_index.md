---
title: LinearMulticolorGradientBrush
second_title: Справочник по Aspose.Imaging for .NET API
description: ПредставляетBrush../aspose.imaging/brushс линейным градиентом определяемым несколькими цветами и соответствующими позициями. Этот класс не может быть унаследован.
type: docs
weight: 170
url: /ru/net/aspose.imaging.brushes/linearmulticolorgradientbrush/
---
## LinearMulticolorGradientBrush class

Представляет[`Brush`](../../aspose.imaging/brush)с линейным градиентом, определяемым несколькими цветами и соответствующими позициями. Этот класс не может быть унаследован.

```csharp
public sealed class LinearMulticolorGradientBrush : LinearGradientBrushBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor)() | Инициализирует новый экземпляр класса[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)с параметрами по умолчанию. Начальный цвет черный, конечный цвет белый, угол 45 градусов и прямоугольник расположен в (0,0) с размером (1,1). |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_1)(Point, Point) | Инициализирует новый экземпляр класса[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)с указанными точками. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_2)(PointF, PointF) | Инициализирует новый экземпляр класса[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)с указанными точками. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_3)(Rectangle, float) | Инициализирует новый экземпляр класса[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)на основе прямоугольника и угла ориентации. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_5)(RectangleF, float) | Инициализирует новый экземпляр класса[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)на основе прямоугольника и угла ориентации. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_4)(Rectangle, float, bool) | Инициализирует новый экземпляр класса[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)на основе прямоугольника и угла ориентации. |
| [LinearMulticolorGradientBrush](linearmulticolorgradientbrush#constructor_6)(RectangleF, float, bool) | Инициализирует новый экземпляр класса[`LinearMulticolorGradientBrush`](../linearmulticolorgradientbrush)на основе прямоугольника и угла ориентации. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | Получает или задает угол градиента. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | Получает или задает значение, указывающее, включена ли гамма-коррекция для этого[`LinearGradientBrushBase`](../lineargradientbrushbase). |
| [InterpolationColors](../../aspose.imaging.brushes/linearmulticolorgradientbrush/interpolationcolors) { get; set; } | Получает или задает[`ColorBlend`](../../aspose.imaging/colorblend), определяющий многоцветный линейный градиент. |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | Получает или задает значение, указывающее, изменяется ли[`Angle`](../lineargradientbrushbase/angle)во время преобразований с этим[`LinearGradientBrushBase`](../lineargradientbrushbase). |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например, установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видна, значение 1 означает, что кисть полностью непрозрачна. |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | Получает или задает прямоугольную область, определяющую начальную и конечную точки градиента. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | Получает или задает копию[`Matrix`](../../aspose.imaging/matrix), которая определяет локальное геометрическое преобразование для этого[`TransformBrush`](../transformbrush). |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | Получает или задает перечисление[`WrapMode`](../../aspose.imaging/wrapmode), указывающее режим переноса для этого[`TransformBrush`](../transformbrush). |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | Создает новый глубокий клон текущего[`Brush`](../../aspose.imaging/brush). |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | Умножает[`Matrix`](../../aspose.imaging/matrix), которая представляет локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush)указанным[`Matrix`](../../aspose.imaging/matrix)путем добавления указанного[`Matrix`](../../aspose.imaging/matrix). |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Умножает[`Matrix`](../../aspose.imaging/matrix), которая представляет локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush)указанным[`Matrix`](../../aspose.imaging/matrix)в указанном порядке. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | Сбрасывает свойство[`Transform`](../transformbrush/transform)в идентичность. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет поворот к преобразованию. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования к преобразованию. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Переносит локальное геометрическое преобразование на заданные размеры. Этот метод добавляет перевод к преобразованию. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Смотрите также

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* пространство имен [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
