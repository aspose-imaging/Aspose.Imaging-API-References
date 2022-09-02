---
title: Pen
second_title: Справочник по Aspose.Imaging for .NET API
description: Определяет объект используемый для рисования линий кривых и фигур.
type: docs
weight: 10690
url: /ru/net/aspose.imaging/pen/
---
## Pen class

Определяет объект, используемый для рисования линий, кривых и фигур.

```csharp
public class Pen : TransparencySupporter
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Pen](pen#constructor)(Brush) | Инициализирует новый экземпляр[`Pen`](../pen) класс с указанным[`Brush`](./brush) . |
| [Pen](pen#constructor_2)(Color) | Инициализирует новый экземпляр[`Pen`](../pen) класс с указанным цветом. |
| [Pen](pen#constructor_1)(Brush, float) | Инициализирует новый экземпляр[`Pen`](../pen) класс с указанным[`Brush`](./brush) а также[`Width`](./width) . |
| [Pen](pen#constructor_3)(Color, float) | Инициализирует новый экземпляр[`Pen`](../pen) класс с указанным[`Color`](./color) а также[`Width`](./width) свойства. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Alignment](../../aspose.imaging/pen/alignment) { get; set; } | Получает или задает выравнивание для этого[`Pen`](../pen) . |
| [Brush](../../aspose.imaging/pen/brush) { get; set; } | Получает или задает[`Brush`](./brush) что определяет атрибуты этого[`Pen`](../pen) . |
| [Color](../../aspose.imaging/pen/color) { get; set; } | Получает или устанавливает цвет этого[`Pen`](../pen) . |
| [CompoundArray](../../aspose.imaging/pen/compoundarray) { get; set; } | Получает или задает массив значений, указывающий составное перо. Составное перо рисует составную линию, состоящую из параллельных линий и пробелов. |
| [CustomEndCap](../../aspose.imaging/pen/customendcap) { get; set; } | Получает или задает пользовательскую заглушку для использования в конце строк, нарисованных с помощью этого[`Pen`](../pen) . |
| [CustomStartCap](../../aspose.imaging/pen/customstartcap) { get; set; } | Получает или задает пользовательскую заглушку для использования в начале строк, нарисованных с помощью этого[`Pen`](../pen) . |
| [DashCap](../../aspose.imaging/pen/dashcap) { get; set; } | Получает или задает стиль заглавных букв, используемый в конце штрихов, составляющих пунктирные линии, нарисованные с помощью этого[`Pen`](../pen) . |
| [DashOffset](../../aspose.imaging/pen/dashoffset) { get; set; } | Получает или задает расстояние от начала линии до начала штрихового узора. |
| [DashPattern](../../aspose.imaging/pen/dashpattern) { get; set; } | Получает или задает массив пользовательских дефисов и пробелов. |
| [DashStyle](../../aspose.imaging/pen/dashstyle) { get; set; } | Получает или задает стиль, используемый для пунктирных линий, нарисованных с помощью этого[`Pen`](../pen) . |
| [EndCap](../../aspose.imaging/pen/endcap) { get; set; } | Получает или задает стиль заглавных букв, используемый в конце строк, нарисованных с помощью этого[`Pen`](../pen) . |
| [LineJoin](../../aspose.imaging/pen/linejoin) { get; set; } | Получает или задает стиль соединения концов двух последовательных линий, нарисованных с помощью этого[`Pen`](../pen) . |
| [MiterLimit](../../aspose.imaging/pen/miterlimit) { get; set; } | Получает или задает предел толщины соединения на скошенном углу. |
| [Opacity](../../aspose.imaging/transparencysupporter/opacity) { get; set; } | Получает или задает прозрачность объекта. Значение должно быть от 0 до 1. Значение 0 означает, что объект полностью виден, значение 1 означает, что объект полностью непрозрачен. |
| [PenType](../../aspose.imaging/pen/pentype) { get; } | Получает стиль линий, нарисованных с помощью этого[`Pen`](../pen) . |
| [StartCap](../../aspose.imaging/pen/startcap) { get; set; } | Получает или задает стиль заглавных букв, используемый в начале строк, нарисованных с помощью этого[`Pen`](../pen) . |
| [Transform](../../aspose.imaging/pen/transform) { get; set; } | Получает или задает копию геометрического преобразования для этого[`Pen`](../pen) . |
| [Width](../../aspose.imaging/pen/width) { get; set; } | Получает или задает ширину этого[`Pen`](../pen) , в единицах объекта Graphics, используемого для рисования. |

## Методы

| Имя | Описание |
| --- | --- |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform)(Matrix) | Умножает матрицу преобразования для этого[`Pen`](../pen) указанным[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Умножает матрицу преобразования для этого[`Pen`](../pen) указанным[`Matrix`](../matrix) в указанном порядке. |
| [ResetTransform](../../aspose.imaging/pen/resettransform)() | Сбрасывает матрицу геометрического преобразования для этого[`Pen`](../pen) к личности. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанный угол. Этот метод добавляет поворот к преобразованию. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанный угол в указанном порядке. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование по указанным коэффициентам. Этот метод добавляет матрицу масштабирования к преобразованию. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование по указанным коэффициентам в указанном порядке. |
| [SetLineCap](../../aspose.imaging/pen/setlinecap)(LineCap, LineCap, DashCap) | Устанавливает значения, определяющие стиль заглавных букв, используемых для окончания линий, нарисованных этим[`Pen`](../pen) . |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform)(float, float) | Преобразует локальное геометрическое преобразование по указанным размерам. Этот метод добавляет перевод к преобразованию. |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

### Примеры

В этом примере показано создание и использование объектов Pen. В примере создается новое изображение и рисуются прямоугольники на поверхности изображения.

```csharp
[C#]

//Создаем экземпляр BmpOptions и устанавливаем его различные свойства
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Создаем экземпляр FileCreateSource и назначаем его в качестве источника для экземпляра BmpOptions
//Второй логический параметр определяет, является ли создаваемый файл временным или нет
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//Создаем экземпляр изображения по указанному пути
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Создаем экземпляр Graphics и инициализируем его объектом Image
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    // Очистить графическую поверхность белым цветом
    graphics.Clear(Aspose.Imaging.Color.White);

    //Создаем экземпляр Pen красного цвета и ширины 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //Создаем экземпляр HatchBrush и устанавливаем его свойства
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //Создаем экземпляр пера
    // инициализируем его объектом HatchBrush и шириной
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    // Рисуем прямоугольники, указав объект Pen
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    // Рисуем прямоугольники, указав объект Pen
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // сохранить все изменения.
    image.Save();
}
```

### Смотрите также

* class [TransparencySupporter](../transparencysupporter)
* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
