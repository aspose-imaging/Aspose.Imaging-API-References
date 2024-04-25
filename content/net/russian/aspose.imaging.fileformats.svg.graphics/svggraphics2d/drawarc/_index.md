---
title: DrawArc
second_title: Справочник по Aspose.Imaging for .NET API
description: Рисует дугу представляющую часть эллипса заданного структурой Rectangle.
type: docs
weight: 20
url: /ru/aspose.imaging.fileformats.svg.graphics/svggraphics2d/drawarc/
---
## SvgGraphics2D.DrawArc method

Рисует дугу, представляющую часть эллипса, заданного структурой Rectangle.

```csharp
public void DrawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | Перо, чтобы нарисовать контур фигуры. |
| rect | Rectangle | Границы эллипса. |
| startAngle | Single | Угол в градусах, измеренный по часовой стрелке от оси x до начальной точки дуги. |
| arcAngle | Single | Угол в градусах, измеренный по часовой стрелке от параметра startAngle до конечной точки дуги. |

### Примеры

В этом примере показано, как создать изображение SVG указанного размера и нарисовать на нем различные фигуры с помощью SvgGraphics2D.

```csharp
[C#]

string dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D graphics = new Aspose.Imaging.FileFormats.Svg.Graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Нарисуйте черный прямоугольник вдоль границ изображения, используя черную ручку шириной 1 пиксель.
graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 1), 0, 0, imageWidth, imageHeight);

// Заливаем прямоугольник цветом белого дыма.
graphics.FillRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.WhiteSmoke, 1), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.WhiteSmoke), 10, 10, 580, 380);

// Нарисуйте две диагональные линии темно-зеленым пером шириной 1 пиксель.
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, 0, imageWidth, imageHeight);
graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.DarkGreen, 1), 0, imageHeight, imageWidth, 0);

// Нарисуйте дугу внутри прямоугольника {0, 0, 200, 200}, используя синее перо шириной 2 пикселя.
graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Заполнить дугу
graphics.FillArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.LightCoral, 10), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.LightSkyBlue), new Aspose.Imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Нарисуйте куб Безье с помощью красного пера шириной 2 пикселя.
graphics.DrawCubicBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2),
    new Aspose.Imaging.PointF(0, 0),
    new Aspose.Imaging.PointF(200, 133),
    new Aspose.Imaging.PointF(400, 166),
    new Aspose.Imaging.PointF(600, 400));

// Рисуем растровое изображение указанного размера в указанном месте.
// Изображение масштабируется, чтобы соответствовать нужному прямоугольнику.
using (Aspose.Imaging.RasterImage imageToDraw = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    graphics.DrawImage(imageToDraw, new Aspose.Imaging.Point(400, 200), new Aspose.Imaging.Size(100, 50));
}

// Рисуем текстовую строку
graphics.DrawString(new Aspose.Imaging.Font("Arial", 48, Aspose.Imaging.FontStyle.Regular), "Hello World!", new Aspose.Imaging.Point(200, 300), Aspose.Imaging.Color.DarkRed);

// Создаем путь для заполнения
Aspose.Imaging.Figure figureToFill = new Aspose.Imaging.Figure();
figureToFill.IsClosed = true;

Aspose.Imaging.GraphicsPath pathToFill = new Aspose.Imaging.GraphicsPath();
pathToFill.AddFigure(figureToFill);

figureToFill.AddShapes(new Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.Rectangle(400, 0, 200, 100), 45, 300),
        new Aspose.Imaging.Shapes.BezierShape(
            new Aspose.Imaging.PointF[]
            {
                new Aspose.Imaging.PointF(300, 200),
                new Aspose.Imaging.PointF(400, 200),
                new Aspose.Imaging.PointF(500, 100),
                new Aspose.Imaging.PointF(600, 200),
            }),
        new Aspose.Imaging.Shapes.PolygonShape(
            new Aspose.Imaging.PointF[]
            {
                new Aspose.Imaging.PointF(300, 100),
            }),
        new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(0, 100, 200, 200)),
    });

// Закрасьте путь, используя желтую кисть и зеленое перо, чтобы нарисовать контур
graphics.FillPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Yellow), pathToFill);

// Создаем путь для рисования
Aspose.Imaging.GraphicsPath pathToDraw = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figureToDraw = new Aspose.Imaging.Figure();
pathToDraw.AddFigure(figureToDraw);

figureToDraw.AddShapes(new Aspose.Imaging.Shape[]
    {
        new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(200, 200, 200, 200), 0, 360),
    });

// Нарисуйте путь оранжевым пером шириной 5 пикселей.
graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 5), pathToDraw);

// Получить окончательное изображение SVG, которое включает все команды рисования
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = graphics.EndRecording())
{
    svgImage.Save(dir + "test.output.svg");
}
```

### Смотрите также

* class [Pen](../../../aspose.imaging/pen)
* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [SvgGraphics2D](../../svggraphics2d)
* пространство имен [Aspose.Imaging.FileFormats.Svg.Graphics](../../svggraphics2d)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
