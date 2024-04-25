---
title: GraphicsPath
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет набор соединенных линий и кривых. Этот класс не может быть унаследован.
type: docs
weight: 9370
url: /ru/aspose.imaging/graphicspath/
---
## GraphicsPath class

Представляет набор соединенных линий и кривых. Этот класс не может быть унаследован.

```csharp
public sealed class GraphicsPath : ObjectWithBounds
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GraphicsPath](graphicspath#constructor)() | Инициализирует новый экземпляр[`GraphicsPath`](../graphicspath) класс. |
| [GraphicsPath](graphicspath#constructor_1)(Figure[]) | Инициализирует новый экземпляр[`GraphicsPath`](../graphicspath) класс. |
| [GraphicsPath](graphicspath#constructor_3)(FillMode) | Инициализирует новый экземпляр[`GraphicsPath`](../graphicspath) класс. |
| [GraphicsPath](graphicspath#constructor_2)(Figure[], FillMode) | Инициализирует новый экземпляр[`GraphicsPath`](../graphicspath) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [Bounds](../../aspose.imaging/graphicspath/bounds) { get; } | Получает или устанавливает границы объекта. |
| [Figures](../../aspose.imaging/graphicspath/figures) { get; } | Получает цифры пути. |
| [FillMode](../../aspose.imaging/graphicspath/fillmode) { get; set; } | Получает или задает[`FillMode`](../fillmode) перечисление, которое определяет, как внутренности фигур в этом[`GraphicsPath`](../graphicspath) заполнены. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddFigure](../../aspose.imaging/graphicspath/addfigure)(Figure) | Добавляет новую фигуру. |
| [AddFigures](../../aspose.imaging/graphicspath/addfigures)(Figure[]) | Добавляет новые фигуры. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath)(GraphicsPath) | Добавляет указанный[`GraphicsPath`](../graphicspath) на этот путь. |
| [AddPath](../../aspose.imaging/graphicspath/addpath#addpath_1)(GraphicsPath, bool) | Добавляет указанный[`GraphicsPath`](../graphicspath) на этот путь. |
| [DeepClone](../../aspose.imaging/graphicspath/deepclone)() | Выполняет глубокое клонирование этого графического пути. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten)() | Преобразует каждую кривую на этом пути в последовательность соединенных сегментов линии. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_1)(Matrix) | Применяет указанное преобразование, а затем преобразует каждую кривую в этот[`GraphicsPath`](../graphicspath) в последовательность соединенных отрезков линии. |
| [Flatten](../../aspose.imaging/graphicspath/flatten#flatten_2)(Matrix, float) | Преобразует каждую кривую в этот[`GraphicsPath`](../graphicspath) в последовательность соединенных отрезков линии. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds)(Matrix) | Получает границы объекта. |
| override [GetBounds](../../aspose.imaging/graphicspath/getbounds#getbounds_1)(Matrix, Pen) | Получает границы объекта. |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible)(Point, Pen) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_2)(PointF, Pen) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_6)(float, float, Pen) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_4)(int, int, Pen) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_1)(Point, Pen, Graphics) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) и с помощью указанного[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_3)(PointF, Pen, Graphics) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) и с помощью указанного[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_7)(float, float, Pen, Graphics) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) и с помощью указанного[`Graphics`](../graphics) . |
| [IsOutlineVisible](../../aspose.imaging/graphicspath/isoutlinevisible#isoutlinevisible_5)(int, int, Pen, Graphics) | Указывает, содержится ли указанная точка внутри (под) контура этого[`GraphicsPath`](../graphicspath) при рисовании с указанным[`Pen`](../pen) и с помощью указанного[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible)(Point) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_2)(PointF) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_6)(float, float) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_4)(int, int) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_1)(Point, Graphics) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_3)(PointF, Graphics) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_7)(float, float, Graphics) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) в видимой области клипа указанного[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/graphicspath/isvisible#isvisible_5)(int, int, Graphics) | Указывает, содержится ли указанная точка в этом[`GraphicsPath`](../graphicspath) , используя указанный[`Graphics`](../graphics) . |
| [RemoveFigure](../../aspose.imaging/graphicspath/removefigure)(Figure) | Удаляет фигурку. |
| [RemoveFigures](../../aspose.imaging/graphicspath/removefigures)(Figure[]) | Удаляет фигуры. |
| [Reset](../../aspose.imaging/graphicspath/reset)() | Очищает путь к графике и устанавливает[`FillMode`](../fillmode) кAlternate . |
| [Reverse](../../aspose.imaging/graphicspath/reverse)() | Меняет порядок фигур, фигур и точек в каждой фигуре этого изображения на противоположный.[`GraphicsPath`](../graphicspath) . |
| override [Transform](../../aspose.imaging/graphicspath/transform)(Matrix) | Применяет указанное преобразование к фигуре. |
| [Warp](../../aspose.imaging/graphicspath/warp#warp)(PointF[], RectangleF) | Применяет преобразование деформации, заданное прямоугольником и параллелограммом, к этому[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_1)(PointF[], RectangleF, Matrix) | Применяет преобразование деформации, заданное прямоугольником и параллелограммом, к этому[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_2)(PointF[], RectangleF, Matrix, WarpMode) | Применяет преобразование деформации, заданное прямоугольником и параллелограммом, к этому[`GraphicsPath`](../graphicspath) . |
| [Warp](../../aspose.imaging/graphicspath/warp#warp_3)(PointF[], RectangleF, Matrix, WarpMode, float) | Применяет преобразование деформации, заданное прямоугольником и параллелограммом, к этому[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen)(Pen) | Добавляет дополнительный контур пути. |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_1)(Pen, Matrix) | Добавляет дополнительный контур к[`GraphicsPath`](../graphicspath) . |
| [Widen](../../aspose.imaging/graphicspath/widen#widen_2)(Pen, Matrix, float) | Заменяет это[`GraphicsPath`](../graphicspath)с кривыми, которые охватывают область, которая заполняется, когда этот путь рисуется указанным пером. |

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

* class [ObjectWithBounds](../objectwithbounds)
* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
