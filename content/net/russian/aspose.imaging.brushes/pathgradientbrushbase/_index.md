---
title: PathGradientBrushBase
second_title: Справочник по Aspose.Imaging for .NET API
description: ПредставляетBrush../aspose.imaging/brush с функцией градиента базового пути.
type: docs
weight: 190
url: /ru/aspose.imaging.brushes/pathgradientbrushbase/
---
## PathGradientBrushBase class

Представляет[`Brush`](../../aspose.imaging/brush) с функцией градиента базового пути.

```csharp
public abstract class PathGradientBrushBase : TransformBrush
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Получает или задает центральную точку градиента пути. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Получает или задает точку фокусировки для спада градиента. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Получает графический путь, на котором построена эта кисть. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видна, значение 1 означает, что кисть полностью непрозрачна. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Получает точки пути, на которых построена эта кисть. |
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
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Преобразует локальное геометрическое преобразование по указанным размерам. Этот метод добавляет перевод к transform. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Примечания

Обратите внимание, что при создании[`PathGradientBrushBase`](../pathgradientbrushbase) class он должен быть инициализирован как минимум двумя точками. Внутренний путь created всегда будет замкнутой фигурой, последняя точка соединяет первую точку. Эта форма заполнена этим[`PathGradientBrushBase`](../pathgradientbrushbase) . Реализация GDI+ вызываетOutOfMemoryException при передаче пустых массивов или наборов точек с одинаковыми координатами. [`PathGradientBrushBase`](../pathgradientbrushbase) выдает исключение, когда массив точек содержит менее 2 точек,ArgumentException is брошен, а неOutOfMemoryExceptionкогда массив точек недопустим. Центральная точка рассчитывается как центр масс для переданных точек по умолчанию. Пользователь может изменить эту точку позже. По умолчанию шкала фокуса представляет собой пустую точку (0,0, 0,0).

### Смотрите также

* class [TransformBrush](../transformbrush)
* пространство имен [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
