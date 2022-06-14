---
title: RectangleShape
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземпляр классаRectangleShapeaspose.imaging.shapes/rectangleshape.
type: docs
weight: 10
url: /ru/net/aspose.imaging.shapes/rectangleshape/rectangleshape/
---
## RectangleShape() {#constructor}

Инициализирует новый экземпляр класса[`RectangleShape`](../../rectangleshape).

```csharp
public RectangleShape()
```

### Смотрите также

* class [RectangleShape](../../rectangleshape)
* пространство имен [Aspose.Imaging.Shapes](../../rectangleshape)
* сборка [Aspose.Imaging](../../../)

---

## RectangleShape(RectangleF) {#constructor_1}

Инициализирует новый экземпляр класса[`RectangleShape`](../../rectangleshape).

```csharp
public RectangleShape(RectangleF rectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | RectangleF | Прямоугольник. |

### Примеры

В этих примерах классы GraphicsPath и Graphics используются для создания фигур на поверхности изображения и управления ими. Пример создает новое изображение (типа Tiff), очищает поверхность и рисует пути с помощью класса GraphicsPath. В конце вызывается метод DrawPath, предоставляемый классом Graphics, для отображения путей на поверхности.

```csharp
[C#]

 // Создает экземпляр BmpOptions и устанавливает его различные свойства 
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

 //Создаем экземпляр FileCreateSource и назначаем его в качестве источника для экземпляра BmpOptions
 //Второй логический параметр определяет, является ли создаваемый файл временным или нет
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

 //Создаем экземпляр изображения 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
     //Создаем и инициализируем экземпляр Graphics class
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

     //Очистить графику surface
    graphics.Clear(Color.Wheat);

     //Создаем экземпляр GraphicsPath class
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //Создаем экземпляр рисунка class
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

     //Добавить фигуру к рисунку object
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Создаем экземпляр рисунка class
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

     //Добавить фигуру к рисунку object
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

     //Добавить объект Figure в GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

     //Нарисовать путь с помощью объекта Pen цвета Black
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

     // сохранить все изменения.
    image.Save();
}
```

В этом примере создается новое изображение и рисуются различные фигуры с использованием Figures и GraphicsPath на поверхности изображения

```csharp
[C#]

 // Создает экземпляр BmpOptions и устанавливает его различные свойства 
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

 //Создаем экземпляр FileCreateSource и назначаем его в качестве источника для экземпляра BmpOptions
 //Второй логический параметр определяет, является ли создаваемый файл временным или нет
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"c:\temp\output.bmp", false);

 //Создаем экземпляр изображения 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
     //Создаем и инициализируем экземпляр Graphics class
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

     //Очистить графику surface
    graphics.Clear(Color.Wheat);

     //Создаем экземпляр GraphicsPath class
    Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

    //Создаем экземпляр рисунка class
    Aspose.Imaging.Figure figure1 = new Aspose.Imaging.Figure();

     //Добавить фигуру к рисунку object
    figure1.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure1.AddShape(new Aspose.Imaging.Shapes.PieShape(new Rectangle(new Point(110, 110), new Size(200, 200)), 0, 90));

    //Создаем экземпляр рисунка class
    Aspose.Imaging.Figure figure2 = new Aspose.Imaging.Figure();

     //Добавить фигуру к рисунку object
    figure2.AddShape(new Aspose.Imaging.Shapes.ArcShape(new Aspose.Imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.AddShape(new Aspose.Imaging.Shapes.PolygonShape(new[] { new Aspose.Imaging.PointF(150, 10), new Aspose.Imaging.PointF(150, 200), new Aspose.Imaging.PointF(250, 300), new Aspose.Imaging.PointF(350, 400) }, true));
    figure2.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(200, 200))));

     //Добавить объект Figure в GraphicsPath
    graphicspath.AddFigures(new[] { figure1, figure2 });

     //Нарисовать путь с помощью объекта Pen цвета Black
    graphics.DrawPath(new Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

     // сохранить все изменения.
    image.Save();
}
```

### Смотрите также

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* class [RectangleShape](../../rectangleshape)
* пространство имен [Aspose.Imaging.Shapes](../../rectangleshape)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
