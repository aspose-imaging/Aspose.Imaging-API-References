---
title: TextureBrush
second_title: Справочник по Aspose.Imaging for .NET API
description: Каждое свойство классаTextureBrush./texturebrushявляетсяBrush../aspose.imaging/brushобъект использующий изображение для заполнения внутренней части фигуры. Этот класс не может быть унаследован.
type: docs
weight: 220
url: /ru/net/aspose.imaging.brushes/texturebrush/
---
## TextureBrush class

Каждое свойство класса[`TextureBrush`](../texturebrush)является[`Brush`](../../aspose.imaging/brush)объект, использующий изображение для заполнения внутренней части фигуры. Этот класс не может быть унаследован.

```csharp
public sealed class TextureBrush : TransformBrush
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextureBrush](texturebrush#constructor)(Image) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение. |
| [TextureBrush](texturebrush#constructor_1)(Image, Rectangle) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush](texturebrush#constructor_3)(Image, RectangleF) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение и ограничивающий прямоугольник. |
| [TextureBrush](texturebrush#constructor_5)(Image, WrapMode) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение и режим переноса. |
| [TextureBrush](texturebrush#constructor_2)(Image, Rectangle, ImageAttributes) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение, ограничивающий прямоугольник и изображение атрибуты. |
| [TextureBrush](texturebrush#constructor_4)(Image, RectangleF, ImageAttributes) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение, ограничивающий прямоугольник и изображение атрибуты. |
| [TextureBrush](texturebrush#constructor_6)(Image, WrapMode, Rectangle) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение, режим переноса и границы прямоугольник. |
| [TextureBrush](texturebrush#constructor_7)(Image, WrapMode, RectangleF) | Инициализирует новый экземпляр класса[`TextureBrush`](../texturebrush), который использует указанное изображение, режим переноса и границы прямоугольник. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [Image](../../aspose.imaging.brushes/texturebrush/image) { get; } | Получает объект[`Image`](../../aspose.imaging/image), связанный с этим[`TextureBrush`](../texturebrush)объект. |
| [ImageAttributes](../../aspose.imaging.brushes/texturebrush/imageattributes) { get; } | Получает атрибут[`ImageAttributes`](./imageattributes), связанный с этимТекстурнаякисть. |
| [ImageRectangle](../../aspose.imaging.brushes/texturebrush/imagerectangle) { get; } | Получает[`Rectangle`](../../aspose.imaging/rectangle)связанный с этим[`TextureBrush`](../texturebrush). |
| [IsTransformChanged](../../aspose.imaging.brushes/transformbrush/istransformchanged) { get; } | Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например, установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+. |
| [Opacity](../../aspose.imaging/brush/opacity) { get; set; } | Получает или задает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видна, значение 1 означает, что кисть полностью непрозрачна. |
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

* class [TransformBrush](../transformbrush)
* пространство имен [Aspose.Imaging.Brushes](../../aspose.imaging.brushes)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
