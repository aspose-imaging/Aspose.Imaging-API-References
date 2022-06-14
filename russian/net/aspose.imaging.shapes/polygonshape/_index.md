---
title: PolygonShape
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет форму многоугольника.
type: docs
weight: 11010
url: /ru/net/aspose.imaging.shapes/polygonshape/
---
## PolygonShape class

Представляет форму многоугольника.

```csharp
public class PolygonShape : Shape, IOrderedShape
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PolygonShape](polygonshape#constructor)() | Инициализирует новый экземпляр класса[`PolygonShape`](../polygonshape). |
| [PolygonShape](polygonshape#constructor_1)(PointF[]) | Инициализирует новый экземпляр класса[`PolygonShape`](../polygonshape). |
| [PolygonShape](polygonshape#constructor_2)(PointF[], bool) | Инициализирует новый экземпляр класса[`PolygonShape`](../polygonshape). |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/polygonshape/bounds) { get; } | Получает границы объекта. |
| override [Center](../../aspose.imaging.shapes/polygonshape/center) { get; } | Получает центр фигуры. |
| virtual [EndPoint](../../aspose.imaging.shapes/polygonshape/endpoint) { get; } | Получает конечную точку формы. |
| override [HasSegments](../../aspose.imaging.shapes/polygonshape/hassegments) { get; } | Получает значение, указывающее, есть ли у фигуры сегменты. |
| [IsClosed](../../aspose.imaging.shapes/polygonshape/isclosed) { get; set; } | Получает или задает значение, указывающее, закрыта ли фигура. |
| [Points](../../aspose.imaging.shapes/polygonshape/points) { get; set; } | Получает или задает точки кривой. |
| override [Segments](../../aspose.imaging.shapes/polygonshape/segments) { get; } | Получает сегменты формы. |
| virtual [StartPoint](../../aspose.imaging.shapes/polygonshape/startpoint) { get; } | Получает начальную точку формы. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/polygonshape/getbounds#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.imaging.shapes/polygonshape/getbounds#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [Reverse](../../aspose.imaging.shapes/polygonshape/reverse)() | Меняет порядок точек этой фигуры на обратный. |
| override [Transform](../../aspose.imaging.shapes/polygonshape/transform)(Matrix) | Применяет указанное преобразование к фигуре. |

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

* class [Shape](../../aspose.imaging/shape)
* interface [IOrderedShape](../../aspose.imaging/iorderedshape)
* пространство имен [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
