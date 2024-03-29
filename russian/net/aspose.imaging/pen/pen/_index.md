---
title: Pen
second_title: Справочник по Aspose.Imaging for .NET API
description: Инициализирует новый экземплярPenaspose.imaging/pen класс с указанным цветом.
type: docs
weight: 10
url: /ru/net/aspose.imaging/pen/pen/
---
## Pen(Color) {#constructor_2}

Инициализирует новый экземпляр[`Pen`](../../pen) класс с указанным цветом.

```csharp
public Pen(Color color)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| color | Color | А[`Color`](../color) структура, указывающая на цвет этого[`Pen`](../../pen). |

### Смотрите также

* struct [Color](../../color)
* class [Pen](../../pen)
* пространство имен [Aspose.Imaging](../../pen)
* сборка [Aspose.Imaging](../../../)

---

## Pen(Color, float) {#constructor_3}

Инициализирует новый экземпляр[`Pen`](../../pen) класс с указанным[`Color`](../color) а также[`Width`](../width) свойства.

```csharp
public Pen(Color color, float width)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| color | Color | А[`Color`](../color) структура, указывающая на цвет этого[`Pen`](../../pen). |
| width | Single | Значение, указывающее ширину этого[`Pen`](../../pen). |

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

* struct [Color](../../color)
* class [Pen](../../pen)
* пространство имен [Aspose.Imaging](../../pen)
* сборка [Aspose.Imaging](../../../)

---

## Pen(Brush) {#constructor}

Инициализирует новый экземпляр[`Pen`](../../pen) класс с указанным[`Brush`](../brush) .

```csharp
public Pen(Brush brush)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | А[`Brush`](../brush) который определяет свойства заполнения этого[`Pen`](../../pen). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* нулевой. |

### Смотрите также

* class [Brush](../../brush)
* class [Pen](../../pen)
* пространство имен [Aspose.Imaging](../../pen)
* сборка [Aspose.Imaging](../../../)

---

## Pen(Brush, float) {#constructor_1}

Инициализирует новый экземпляр[`Pen`](../../pen) класс с указанным[`Brush`](../brush) а также[`Width`](../width) .

```csharp
public Pen(Brush brush, float width)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | А[`Brush`](../brush) что определяет характеристики этого[`Pen`](../../pen). |
| width | Single | Ширина нового[`Pen`](../../pen). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush* нулевой. |

### Смотрите также

* class [Brush](../../brush)
* class [Pen](../../pen)
* пространство имен [Aspose.Imaging](../../pen)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
