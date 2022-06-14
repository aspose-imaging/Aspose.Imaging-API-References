---
title: ArcShape
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет форму дуги.
type: docs
weight: 10960
url: /ru/net/aspose.imaging.shapes/arcshape/
---
## ArcShape class

Представляет форму дуги.

```csharp
public sealed class ArcShape : PieShape, IOrderedShape
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ArcShape](arcshape#constructor)() | Инициализирует новый экземпляр класса[`ArcShape`](../arcshape). |
| [ArcShape](arcshape#constructor_1)(RectangleF, float, float) | Инициализирует новый экземпляр класса[`ArcShape`](../arcshape). |
| [ArcShape](arcshape#constructor_2)(RectangleF, float, float, bool) | Инициализирует новый экземпляр класса[`ArcShape`](../arcshape). |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/rectangleprojectedshape/bounds) { get; } | Получает границы объекта. |
| override [Center](../../aspose.imaging.shapes/rectangleprojectedshape/center) { get; } | Получает центр фигуры. |
| [EndPoint](../../aspose.imaging.shapes/arcshape/endpoint) { get; } | Получает конечную точку формы. |
| override [HasSegments](../../aspose.imaging.shapes/rectangleprojectedshape/hassegments) { get; } | Получает значение, указывающее, есть ли у фигуры сегменты. |
| [IsClosed](../../aspose.imaging.shapes/arcshape/isclosed) { get; set; } | Получает или задает значение, указывающее, закрыта ли упорядоченная фигура. При обработке замкнутой упорядоченной формы начальная и конечная точки не имеют значения. |
| [LeftBottom](../../aspose.imaging.shapes/rectangleprojectedshape/leftbottom) { get; } | Получает точку левого нижнего прямоугольника. |
| [LeftTop](../../aspose.imaging.shapes/rectangleprojectedshape/lefttop) { get; } | Получает левую верхнюю точку прямоугольника. |
| [RectangleHeight](../../aspose.imaging.shapes/rectangleprojectedshape/rectangleheight) { get; } | Получает высоту прямоугольника. |
| [RectangleWidth](../../aspose.imaging.shapes/rectangleprojectedshape/rectanglewidth) { get; } | Получает ширину прямоугольника. |
| [RightBottom](../../aspose.imaging.shapes/rectangleprojectedshape/rightbottom) { get; } | Получает правую нижнюю точку прямоугольника. |
| [RightTop](../../aspose.imaging.shapes/rectangleprojectedshape/righttop) { get; } | Получает правую верхнюю точку прямоугольника. |
| override [Segments](../../aspose.imaging.shapes/arcshape/segments) { get; } | Получает сегменты формы. |
| [StartAngle](../../aspose.imaging.shapes/pieshape/startangle) { get; set; } | Получает или задает начальный угол. |
| [StartPoint](../../aspose.imaging.shapes/arcshape/startpoint) { get; } | Получает начальную точку формы. |
| [SweepAngle](../../aspose.imaging.shapes/pieshape/sweepangle) { get; set; } | Получает или задает угол развертки. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/arcshape/getbounds#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.imaging.shapes/arcshape/getbounds#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [Reverse](../../aspose.imaging.shapes/arcshape/reverse)() | Меняет порядок точек этой фигуры на обратный. |
| override [Transform](../../aspose.imaging.shapes/rectangleprojectedshape/transform)(Matrix) | Применяет указанное преобразование к фигуре. |

### Примеры

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

* class [PieShape](../pieshape)
* interface [IOrderedShape](../../aspose.imaging/iorderedshape)
* пространство имен [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
