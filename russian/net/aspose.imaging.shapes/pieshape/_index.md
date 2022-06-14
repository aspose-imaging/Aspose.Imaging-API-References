---
title: PieShape
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет форму круга.
type: docs
weight: 11000
url: /ru/net/aspose.imaging.shapes/pieshape/
---
## PieShape class

Представляет форму круга.

```csharp
public class PieShape : EllipseShape
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PieShape](pieshape#constructor)() | Инициализирует новый экземпляр класса[`PieShape`](../pieshape). |
| [PieShape](pieshape#constructor_1)(RectangleF, float, float) | Инициализирует новый экземпляр класса[`PieShape`](../pieshape). |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.imaging.shapes/rectangleprojectedshape/bounds) { get; } | Получает границы объекта. |
| override [Center](../../aspose.imaging.shapes/rectangleprojectedshape/center) { get; } | Получает центр фигуры. |
| override [HasSegments](../../aspose.imaging.shapes/rectangleprojectedshape/hassegments) { get; } | Получает значение, указывающее, есть ли у фигуры сегменты. |
| [LeftBottom](../../aspose.imaging.shapes/rectangleprojectedshape/leftbottom) { get; } | Получает точку левого нижнего прямоугольника. |
| [LeftTop](../../aspose.imaging.shapes/rectangleprojectedshape/lefttop) { get; } | Получает левую верхнюю точку прямоугольника. |
| [RectangleHeight](../../aspose.imaging.shapes/rectangleprojectedshape/rectangleheight) { get; } | Получает высоту прямоугольника. |
| [RectangleWidth](../../aspose.imaging.shapes/rectangleprojectedshape/rectanglewidth) { get; } | Получает ширину прямоугольника. |
| [RightBottom](../../aspose.imaging.shapes/rectangleprojectedshape/rightbottom) { get; } | Получает правую нижнюю точку прямоугольника. |
| [RightTop](../../aspose.imaging.shapes/rectangleprojectedshape/righttop) { get; } | Получает правую верхнюю точку прямоугольника. |
| override [Segments](../../aspose.imaging.shapes/pieshape/segments) { get; } | Получает сегменты формы. |
| [StartAngle](../../aspose.imaging.shapes/pieshape/startangle) { get; set; } | Получает или задает начальный угол. |
| [SweepAngle](../../aspose.imaging.shapes/pieshape/sweepangle) { get; set; } | Получает или задает угол развертки. |

## Методы

| Имя | Описание |
| --- | --- |
| override [GetBounds](../../aspose.imaging.shapes/rectangleprojectedshape/getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.imaging.shapes/rectangleprojectedshape/getbounds)(Matrix, Pen) | Получает границы объекта. |
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

* class [EllipseShape](../ellipseshape)
* пространство имен [Aspose.Imaging.Shapes](../../aspose.imaging.shapes)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
