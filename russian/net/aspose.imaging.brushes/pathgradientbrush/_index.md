---
title: PathGradientBrush
second_title: Справочник по Aspose.Imaging for .NET API
description: Инкапсулирует объектBrush../aspose.imaging/brushс градиентом. Этот класс не может быть унаследован.
type: docs
weight: 180
url: /ru/net/aspose.imaging.brushes/pathgradientbrush/
---
## PathGradientBrush class

Инкапсулирует объект[`Brush`](../../aspose.imaging/brush)с градиентом. Этот класс не может быть унаследован.

```csharp
public sealed class PathGradientBrush : PathGradientBrushBase
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PathGradientBrush](pathgradientbrush#constructor)(GraphicsPath) | Инициализирует новый экземпляр класса[`PathGradientBrush`](../pathgradientbrush)с указанным путем. |
| [PathGradientBrush](pathgradientbrush#constructor_1)(PointF[]) | Инициализирует новый экземпляр класса[`PathGradientBrush`](../pathgradientbrush)с указанными точками. |
| [PathGradientBrush](pathgradientbrush#constructor_3)(Point[]) | Инициализирует новый экземпляр класса[`PathGradientBrush`](../pathgradientbrush)с указанными точками. |
| [PathGradientBrush](pathgradientbrush#constructor_2)(PointF[], WrapMode) | Инициализирует новый экземпляр класса[`PathGradientBrush`](../pathgradientbrush)с указанными точками и режимом переноса. |
| [PathGradientBrush](pathgradientbrush#constructor_4)(Point[], WrapMode) | Инициализирует новый экземпляр класса[`PathGradientBrush`](../pathgradientbrush)с указанными точками и режимом переноса. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Blend](../../aspose.imaging.brushes/pathgradientbrush/blend) { get; set; } | Получает или задает[`Blend`](../../aspose.imaging/blend), который указывает позиции и факторы, определяющие пользовательский спад для градиента. |
| [CenterColor](../../aspose.imaging.brushes/pathgradientbrush/centercolor) { get; set; } | Получает или задает цвет в центре градиента контура. |
| [CenterPoint](../../aspose.imaging.brushes/pathgradientbrushbase/centerpoint) { get; set; } | Получает или задает центральную точку градиента пути. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FocusScales](../../aspose.imaging.brushes/pathgradientbrushbase/focusscales) { get; set; } | Получает или задает точку фокусировки для спада градиента. |
| [GraphicsPath](../../aspose.imaging.brushes/pathgradientbrushbase/graphicspath) { get; } | Получает графический путь, на котором построена эта кисть. |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например, установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видна, значение 1 означает, что кисть полностью непрозрачна. |
| [PathPoints](../../aspose.imaging.brushes/pathgradientbrushbase/pathpoints) { get; } | Получает точки пути, на которых построена эта кисть. |
| [SurroundColors](../../aspose.imaging.brushes/pathgradientbrush/surroundcolors) { get; set; } | Получает или задает массив цветов, соответствующих точкам на пути, который заполняет этот[`PathGradientBrush`](../pathgradientbrush). |
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
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape)(float) | Создает градиент с центральным цветом и линейным спадом к одному окружающему цвету. |
| [SetBlendTriangularShape](../../aspose.imaging.brushes/pathgradientbrush/setblendtriangularshape#setblendtriangularshape_1)(float, float) | Создает градиент с центральным цветом и линейным спадом для каждого окружающего цвета. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape)(float) | Создает градиентную кисть, которая меняет цвет, начиная с центра пути наружу и заканчивая его границей. Переход от одного цвета к другому основан на колоколообразной кривой. |
| [SetSigmaBellShape](../../aspose.imaging.brushes/pathgradientbrush/setsigmabellshape#setsigmabellshape_1)(float, float) | Создает градиентную кисть, которая меняет цвет, начиная с центра пути наружу и заканчивая его границей. Переход от одного цвета к другому основан на колоколообразной кривой. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float) | Переносит локальное геометрическое преобразование на заданные размеры. Этот метод добавляет перевод к преобразованию. |
| [TranslateTransform](../../aspose.imaging.brushes/transformbrush/translatetransform)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Примечания

Цвет центра по умолчанию белый. Пользователь может изменить это значение в любое время позже.

Массив объемных цветов по умолчанию инициализируется одним элементом, содержащим белый цвет. Цвета объемного звучания можно изменить позже, однако при настройке цветов объемного звучания требуется хотя бы один элемент.

См.[`Blend`](./blend)для более подробной информации о его инициализации.

### Смотрите также

* class [PathGradientBrushBase](../pathgradientbrushbase)
* пространство имен [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
