---
title: LinearGradientBrush
second_title: Справочник по Aspose.Imaging for .NET API
description: ИнкапсулируетBrush../aspose.imaging/brush с линейным градиентом. Этот класс не может быть унаследован.
type: docs
weight: 150
url: /ru/aspose.imaging.brushes/lineargradientbrush/
---
## LinearGradientBrush class

Инкапсулирует[`Brush`](../../aspose.imaging/brush) с линейным градиентом. Этот класс не может быть унаследован.

```csharp
public sealed class LinearGradientBrush : LinearGradientBrushBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LinearGradientBrush](lineargradientbrush#constructor)() | Инициализирует новый экземпляр[`LinearGradientBrush`](../lineargradientbrush) класс с параметрами по умолчанию. Начальный цвет черный, конечный цвет белый, угол 45 градусов и прямоугольник расположен в (0,0) с размером (1,1). |
| [LinearGradientBrush](lineargradientbrush#constructor_1)(Point, Point, Color, Color) | Инициализирует новый экземпляр[`LinearGradientBrush`](../lineargradientbrush) класс с указанными точками и цветами. |
| [LinearGradientBrush](lineargradientbrush#constructor_2)(PointF, PointF, Color, Color) | Инициализирует новый экземпляр[`LinearGradientBrush`](../lineargradientbrush) класс с указанными точками и цветами. |
| [LinearGradientBrush](lineargradientbrush#constructor_3)(Rectangle, Color, Color, float) | Инициализирует новый экземпляр[`LinearGradientBrush`](../lineargradientbrush) класс на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [LinearGradientBrush](lineargradientbrush#constructor_5)(RectangleF, Color, Color, float) | Инициализирует новый экземпляр[`LinearGradientBrush`](../lineargradientbrush) класс на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [LinearGradientBrush](lineargradientbrush#constructor_4)(Rectangle, Color, Color, float, bool) | Инициализирует новый экземпляр[`LinearGradientBrush`](../lineargradientbrush) класс на основе прямоугольника, начального и конечного цветов и угла ориентации. |
| [LinearGradientBrush](lineargradientbrush#constructor_6)(RectangleF, Color, Color, float, bool) | Инициализирует новый экземпляр[`LinearGradientBrush`](../lineargradientbrush) класс на основе прямоугольника, начального и конечного цветов и угла ориентации. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Angle](../../aspose.imaging.brushes/lineargradientbrushbase/angle) { get; set; } | Получает или задает угол градиента. |
| [Blend](../../aspose.imaging.brushes/lineargradientbrush/blend) { get; set; } | Получает или задает[`Blend`](../../aspose.imaging/blend) который указывает позиции и факторы, которые определяют пользовательский спад для градиента. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [EndColor](../../aspose.imaging.brushes/lineargradientbrush/endcolor) { get; set; } | Получает или задает конечный цвет градиента. |
| [GammaCorrection](../../aspose.imaging.brushes/lineargradientbrushbase/gammacorrection) { get; set; } | Получает или задает значение, указывающее, включена ли гамма-коррекция для этого[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsAngleScalable](../../aspose.imaging.brushes/lineargradientbrushbase/isanglescalable) { get; set; } | Получает или задает значение, указывающее,[`Angle`](../lineargradientbrushbase/angle) изменяется во время трансформаций с этим[`LinearGradientBrushBase`](../lineargradientbrushbase) . |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видна, значение 1 означает, что кисть полностью непрозрачна. |
| [Rectangle](../../aspose.imaging.brushes/lineargradientbrushbase/rectangle) { get; set; } | Получает или задает прямоугольную область, определяющую начальную и конечную точки градиента. |
| [StartColor](../../aspose.imaging.brushes/lineargradientbrush/startcolor) { get; set; } | Получает или задает начальный цвет градиента. |
| [Transform](../../aspose.imaging.brushes/transformbrush/transform) { get; set; } | Получает или устанавливает копию[`Matrix`](../../aspose.imaging/matrix) который определяет локальное геометрическое преобразование для этого[`TransformBrush`](../transformbrush) . |
| [WrapMode](../../aspose.imaging.brushes/transformbrush/wrapmode) { get; set; } | Получает или задает[`WrapMode`](../../aspose.imaging/wrapmode) перечисление, указывающее режим переноса для этого[`TransformBrush`](../transformbrush) . |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [DeepClone](../../aspose.imaging/brush/deepclone)() | Создает новый глубокий клон текущего[`Brush`](../../aspose.imaging/brush) . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix) | Умножает[`Matrix`](../../aspose.imaging/matrix) который представляет собой локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush) указанным[`Matrix`](../../aspose.imaging/matrix) путем добавления указанного[`Matrix`](../../aspose.imaging/matrix) . |
| [MultiplyTransform](../../aspose.imaging.brushes/transformbrush/multiplytransform)(Matrix, MatrixOrder) | Умножает[`Matrix`](../../aspose.imaging/matrix) который представляет собой локальное геометрическое преобразование этого[`LinearGradientBrush`](../lineargradientbrush) указанным[`Matrix`](../../aspose.imaging/matrix) в указанном порядке. |
| [ResetTransform](../../aspose.imaging.brushes/transformbrush/resettransform)() | Сбрасывает[`Transform`](../transformbrush/transform) свойство к личности. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет поворот к преобразованию. |
| [RotateTransform](../../aspose.imaging.brushes/transformbrush/rotatetransform)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования перед преобразованием. |
| [ScaleTransform](../../aspose.imaging.brushes/transformbrush/scaletransform)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | Создает линейный градиент с центральным цветом и линейным спадом к одному цвету на обоих концах. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/lineargradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | Создает линейный градиент с центральным цветом и линейным спадом к одному цвету на обоих концах. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape)(float) | Создает спад градиента на основе колоколообразной кривой. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/lineargradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | Создает спад градиента на основе колоколообразной кривой. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Преобразует локальное геометрическое преобразование по указанным размерам. Этот метод добавляет перевод к transform. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Смотрите также

* class [LinearGradientBrushBase](../lineargradientbrushbase)
* пространство имен [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
