---
title: DrawRectangles
second_title: Справочник по Aspose.Imaging for .NET API
description: Рисует ряд прямоугольников заданных структурамиRectangleFaspose.imaging/rectanglef.
type: docs
weight: 310
url: /ru/net/aspose.imaging/graphics/drawrectangles/
---
## DrawRectangles(Pen, RectangleF[]) {#drawrectangles}

Рисует ряд прямоугольников, заданных структурами[`RectangleF`](../../rectanglef).

```csharp
public void DrawRectangles(Pen pen, RectangleF[] rects)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)который определяет цвет, ширину и стиль очертания прямоугольников. |
| rects | RectangleF[] | Массив структур[`RectangleF`](../../rectanglef), которые представляют прямоугольники для рисования. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen*равно нулю. -или- *rects*равно null. |

### Смотрите также

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawRectangles(Pen, Rectangle[]) {#drawrectangles_1}

Рисует ряд прямоугольников, заданных структурами[`Rectangle`](../../rectangle).

```csharp
public void DrawRectangles(Pen pen, Rectangle[] rects)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)который определяет цвет, ширину и стиль очертания прямоугольников. |
| rects | Rectangle[] | Массив структур[`Rectangle`](../../rectangle), которые представляют прямоугольники для рисования. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen*равно нулю. -или- *rects*равно null. |

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

 //Создать экземпляр изображения по указанному пути
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
     //Создаем экземпляр Graphics и инициализируем его изображением object
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

     // Очистить графическую поверхность с помощью белого цвета
    graphics.Clear(Aspose.Imaging.Color.White);

     //Создаем экземпляр Pen красного цвета и ширины 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

     //Создаем экземпляр HatchBrush и устанавливаем его свойства
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

     //Создаем экземпляр Pen
     //инициализируем его с помощью объекта HatchBrush и width
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

     // Рисуем прямоугольники, указав Pen object
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

     // Рисуем прямоугольники, указав Pen object
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

* class [Pen](../../pen)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->