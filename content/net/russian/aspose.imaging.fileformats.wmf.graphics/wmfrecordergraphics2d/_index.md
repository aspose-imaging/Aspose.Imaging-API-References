---
title: WmfRecorderGraphics2D
second_title: Справочник по Aspose.Imaging for .NET API
description: Рекордер Wmf.
type: docs
weight: 8370
url: /ru/aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/
---
## WmfRecorderGraphics2D class

Рекордер Wmf.

```csharp
public sealed class WmfRecorderGraphics2D : MetafileRecorderGraphics2D
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WmfRecorderGraphics2D](wmfrecordergraphics2d)(Rectangle, int) | Инициализирует новый экземпляр[`WmfRecorderGraphics2D`](../wmfrecordergraphics2d) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/backgroundcolor) { get; set; } | Получает или задает цвет фона. |
| [BackgroundMode](../../aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/backgroundmode) { get; set; } | Получает или устанавливает фоновый режим. |
| [Clip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clip) { get; set; } | Получает или задает регион, который ограничивает область рисования этого объекта Graphics |
| [ClipBounds](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clipbounds) { get; } | Получает границы клипа. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromWmfImage](../../aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/fromwmfimage)(WmfImage) | Получает экземпляр средства записи Wmf для существующего образа Wmf. |
| [Clear](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clear)() | Очищает состояние графического объекта |
| [DrawArc](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawarc)(Pen, Rectangle, float, float) | Рисует дугу, представляющую часть эллипса, заданного структурой Rectangle. |
| [DrawCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawcubicbezier)(Pen, Point, Point, Point, Point) | Рисует куб Безье. |
| [DrawEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawellipse)(Pen, Rectangle) | Рисует эллипс. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(RasterImage, Point) | Рисует указанное изображение, используя исходный физический размер, в указанном месте. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(byte[], Rectangle, GraphicsUnit) | Рисует изображение. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(Stream, Rectangle, GraphicsUnit) | Рисует изображение. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | Рисует указанную часть указанного изображения в указанном месте и с указанным размером. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline)(Pen, Point, Point) | Рисует линию. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline)(Pen, int, int, int, int) | Рисует линию. |
| [DrawPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpath)(Pen, GraphicsPath) | Рисует путь. |
| [DrawPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpie)(Pen, Rectangle, float, float) | Рисует круг. |
| [DrawPolyCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolycubicbezier)(Pen, Point[]) | Рисует многогранник Безье. |
| [DrawPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolygon)(Pen, Point[]) | Рисует многоугольник. |
| [DrawPolyline](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolyline)(Pen, Point[]) | Рисует полилинию. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle)(Pen, Rectangle) | Рисует прямоугольник. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle)(Pen, int, int, int, int) | Рисует прямоугольник. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring)(string, Font, Color, int, int) | Рисует строку. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring)(string, Font, Color, int, int, float) | Рисует строку. |
| [EndRecording](../../aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/endrecording)() | Завершает запись. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip)(Rectangle) | Обновляет область отсечения этой графики, чтобы исключить область, указанную структурой Rectangle. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip)(Region) | Обновляет область отсечения этой графики, чтобы исключить область, указанную в Region. |
| [FillEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillellipse)(Brush, Rectangle) | Заполняет эллипс. |
| [FillPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpath)(Pen, Brush, GraphicsPath) | Заполняет путь. |
| [FillPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpie)(Brush, Rectangle, float, float) | Заполняет круг. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon)(Brush, Point[]) | Заполняет полигон. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon)(Brush, Point[], FillMode) | Заполняет полигон. |
| [FillRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillrectangle)(Brush, Rectangle) | Заполняет прямоугольник. |
| [GetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/gettransform)() | Получает преобразование мира. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip)(RectangleF) | Обновляет область отсечения этой графики до пересечения текущей области отсечения и указанной структуры Rectangle. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip)(Region) | Обновляет область отсечения этой графики до пересечения текущей области отсечения и указанной области. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform)(Matrix) | Умножает мировое преобразование этого Графика и указанную Матрицу. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform)(Matrix, MatrixOrder) | Умножает мировое преобразование этой Графики и указанной Матрицы в указанном порядке. |
| [ResetClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/resetclip)() | Сбрасывает клип. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform)(float) | Применяет указанное вращение к матрице преобразования этой графики. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform)(float, PointF, MatrixOrder) | Применяет указанное вращение к матрице преобразования этой графики в указанном порядке. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform)(float, float) | Применяет указанную операцию масштабирования к матрице преобразования этой графики, добавляя ее перед матрицей преобразования объекта. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform)(float, float, MatrixOrder) | Применяет указанную операцию масштабирования к матрице преобразования этой графики в указанном порядке. |
| [SetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform)(Matrix) | Устанавливает преобразование. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform)(float, float) | Изменяет начало системы координат, добавляя указанный перевод к матрице преобразования этой графики. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform)(float, float, MatrixOrder) | Изменяет начало системы координат, применяя указанный перевод к матрице преобразования этой графики в указанном порядке. |

### Смотрите также

* class [MetafileRecorderGraphics2D](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d)
* пространство имен [Aspose.Imaging.FileFormats.Wmf.Graphics](../../aspose.imaging.fileformats.wmf.graphics)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
