---
title: PieShape
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземплярPieShapeaspose.imaging.shapes/pieshape класс.
type: docs
weight: 10
url: /ru/net/aspose.imaging.shapes/pieshape/pieshape/
---
## PieShape() {#constructor}

Инициализирует новый экземпляр[`PieShape`](../../pieshape) класс.

```csharp
public PieShape()
```

### Смотрите также

* class [PieShape](../../pieshape)
* пространство имен [Aspose.Imaging.Shapes](../../pieshape)
* сборка [Aspose.Imaging](../../../)

---

## PieShape(RectangleF, float, float) {#constructor_1}

Инициализирует новый экземпляр[`PieShape`](../../pieshape) класс.

```csharp
public PieShape(RectangleF rectangle, float startAngle, float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | RectangleF | Прямоугольник. |
| startAngle | Single | Начальный угол. |
| sweepAngle | Single | Угол развертки. |

### Примеры

В этих примерах используются GraphicsPath и класс Graphics для создания и управления рисунками на поверхности изображения. Пример создает новое изображение (типа Tiff), очищает поверхность и рисует пути с помощью класса GraphicsPath. В конце вызывается метод DrawPath, предоставляемый классом Graphics, для отображения путей на поверхности.

```csharp
[C#]

//Создаем экземпляр FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Создаем экземпляр TiffOptions и устанавливаем его различные свойства
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Устанавливаем источник для экземпляра ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Создаем экземпляр изображения 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Создаем и инициализируем экземпляр класса Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Очистить графическую поверхность
        graphics.Clear(Color.Wheat);

        //Создаем экземпляр класса GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Создаем экземпляр класса Figure
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        // Добавляем фигуры к объекту Figure
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Добавить объект Figure в GraphicsPath
        graphicspath.AddFigure(figure);

        // Нарисовать путь с помощью объекта Pen черного цвета
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // сохранить все изменения.
        image.Save();
    }
}
```

### Смотрите также

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* class [PieShape](../../pieshape)
* пространство имен [Aspose.Imaging.Shapes](../../pieshape)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
