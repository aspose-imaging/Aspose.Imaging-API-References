---
title: MetafileRecorderGraphics2D
second_title: Справочник по Aspose.Imaging for .NET API
description: Графика записи метафайлов
type: docs
weight: 6500
url: /ru/net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
## MetafileRecorderGraphics2D class

Графика записи метафайлов

```csharp
public abstract class MetafileRecorderGraphics2D
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/backgroundcolor) { get; set; } | Получает или задает цвет фона. |
| [Clip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clip) { get; set; } | Получает или задает регион, который ограничивает область рисования этой графики |
| [ClipBounds](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clipbounds) { get; } | Получает границы клипа. |

## Методы

| Имя | Описание |
| --- | --- |
| [Clear](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/clear)() | Очищает состояние графического объекта |
| [DrawArc](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawarc)(Pen, Rectangle, float, float) | Рисует дугу, представляющую часть эллипса, заданного структурой Rectangle. |
| [DrawCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawcubicbezier)(Pen, Point, Point, Point, Point) | Рисует куб Безье. |
| [DrawEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawellipse)(Pen, Rectangle) | Рисует эллипс. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage)(RasterImage, Point) | Рисует указанное изображение, используя его исходный физический размер, в указанном месте. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage_2)(byte[], Rectangle, GraphicsUnit) | Рисует изображение. |
| [DrawImage](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawimage#drawimage_1)(RasterImage, Rectangle, Rectangle, GraphicsUnit) | Рисует указанную часть указанного изображения в указанном месте и с указанным размером. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline#drawline)(Pen, Point, Point) | Рисует линию. |
| [DrawLine](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawline#drawline_1)(Pen, int, int, int, int) | Рисует линию. |
| [DrawPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpath)(Pen, GraphicsPath) | Рисует путь. |
| [DrawPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpie)(Pen, Rectangle, float, float) | Рисует круг. |
| [DrawPolyCubicBezier](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolycubicbezier)(Pen, Point[]) | Рисует многогранник Безье. |
| [DrawPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolygon)(Pen, Point[]) | Рисует многоугольник. |
| [DrawPolyline](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawpolyline)(Pen, Point[]) | Рисует полилинию. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle#drawrectangle)(Pen, Rectangle) | Рисует прямоугольник. |
| [DrawRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawrectangle#drawrectangle_1)(Pen, int, int, int, int) | Рисует прямоугольник. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring#drawstring)(string, Font, Color, int, int) | Рисует строку. |
| [DrawString](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/drawstring#drawstring_1)(string, Font, Color, int, int, float) | Рисует строку. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip#excludeclip)(Rectangle) | Обновляет область отсечения этой графики, чтобы исключить область, указанную структурой Rectangle. |
| [ExcludeClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/excludeclip#excludeclip_1)(Region) | Обновляет область отсечения этой графики, чтобы исключить область, указанную в области. |
| [FillEllipse](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillellipse)(Brush, Rectangle) | Заполняет эллипс. |
| [FillPath](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpath)(Pen, Brush, GraphicsPath) | Заполняет путь. |
| [FillPie](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpie)(Brush, Rectangle, float, float) | Заполняет круг. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon#fillpolygon)(Brush, Point[]) | Заполняет полигон. |
| [FillPolygon](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillpolygon#fillpolygon_1)(Brush, Point[], FillMode) | Заполняет полигон. |
| [FillRectangle](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/fillrectangle)(Brush, Rectangle) | Заполняет прямоугольник. |
| [GetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/gettransform)() | Получает преобразование мира. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip#intersectclip)(RectangleF) | Обновляет область отсечения этого объекта Graphics до пересечения текущей области отсечения и указанной структуры Rectangle. |
| [IntersectClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/intersectclip#intersectclip_1)(Region) | Обновляет область отсечения этой графики до пересечения текущей области отсечения и указанной области. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform#multiplytransform)(Matrix) | Умножает мировое преобразование этой Графики и указанной Матрицы. |
| [MultiplyTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Умножает мировое преобразование этой Графики и указанной Матрицы в указанном порядке. |
| [ResetClip](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/resetclip)() | Сбрасывает клип. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform#rotatetransform)(float) | Применяет указанное вращение к матрице преобразования этой графики. |
| [RotateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/rotatetransform#rotatetransform_1)(float, PointF, MatrixOrder) | Применяет указанное вращение к матрице преобразования этой графики в указанном порядке. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform#scaletransform)(float, float) | Применяет указанную операцию масштабирования к матрице преобразования этого объекта Graphics, добавляя ее перед матрицей преобразования объекта. |
| [ScaleTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Применяет указанную операцию масштабирования к матрице преобразования этой графики в указанном порядке. |
| [SetTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform)(Matrix) | Устанавливает преобразование. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform#translatetransform)(float, float) | Изменяет начало системы координат, добавляя указанный перевод к матрице преобразования этой графики. |
| [TranslateTransform](../../aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Изменяет начало системы координат, применяя указанный перевод к матрице преобразования этого Графика в указанном порядке. |

### Смотрите также

* пространство имен [Aspose.Imaging.FileFormats.Emf.Graphics](../../aspose.imaging.fileformats.emf.graphics)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
