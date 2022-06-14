---
title: DrawCurve
second_title: Справочник по Aspose.Imaging for .NET API
description: Рисует кардинальный сплайн через указанный массив структурPointFaspose.imaging/pointf. Этот метод использует натяжение по умолчанию 05.
type: docs
weight: 200
url: /ru/net/aspose.imaging/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Рисует кардинальный сплайн через указанный массив структур[`PointF`](../../pointf). Этот метод использует натяжение по умолчанию 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)который определяет цвет, ширину и высоту Кривая. |
| points | PointF[] | Массив структур[`PointF`](../../pointf), определяющих сплайн. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen*равно нулю. -или- *points*равно null. |

### Смотрите также

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Рисует кардинальный сплайн через указанный массив структур[`PointF`](../../pointf)с заданным натяжением.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)который определяет цвет, ширину и высоту Кривая. |
| points | PointF[] | Массив структур[`PointF`](../../pointf), представляющих точки, определяющие кривую. |
| tension | Single | Значение больше или равное 0,0F, определяющее натяжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen*равно нулю. -или- *points*равно null. |

### Смотрите также

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Рисует кардинальный сплайн через указанный массив структур[`PointF`](../../pointf). Рисунок начинается со смещения от начала массива. Этот метод использует натяжение по умолчанию 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)который определяет цвет, ширину и высоту Кривая. |
| points | PointF[] | Массив структур[`PointF`](../../pointf), определяющих сплайн. |
| offset | Int32 | Смещение от первого элемента в массиве параметра*points*до начальной точки кривой. |
| numberOfSegments | Int32 | Количество сегментов после начальной точки для включения в кривую. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen*равно нулю. -или- *points*равно null. |

### Смотрите также

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Рисует кардинальный сплайн через указанный массив структур[`PointF`](../../pointf)с заданным натяжением. Рисунок начинается со смещения от начала массива.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)который определяет цвет, ширину и высоту Кривая. |
| points | PointF[] | Массив структур[`PointF`](../../pointf), определяющих сплайн. |
| offset | Int32 | Смещение от первого элемента в массиве параметра*points*до начальной точки кривой. |
| numberOfSegments | Int32 | Количество сегментов после начальной точки для включения в кривую. |
| tension | Single | Значение больше или равное 0,0F, определяющее натяжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen*равно нулю. -или- *points*равно null. |

### Смотрите также

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Рисует кардинальный сплайн через указанный массив структур[`Point`](../../point).

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)который определяет цвет, ширину и высоту Кривая. |
| points | Point[] | Массив структур[`Point`](../../point), определяющих сплайн. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen*равно нулю. -или- *points*равно null. |

### Примеры

В этом примере класс Graphics используется для создания примитивных форм на поверхности изображения. Чтобы продемонстрировать операцию, в примере создается новое изображение в формате PNG и рисуются примитивные фигуры на поверхности изображения с использованием методов Draw, предоставляемых классом Graphics

```csharp
[C#]

//Создает экземпляр FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
     //Создаем экземпляр PngOptions и устанавливаем его различные свойства
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

     //Установите источник для PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

     //Создаем экземпляр изображения 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
         //Создаем и инициализируем экземпляр Graphics class
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

         //Очистить графику surface
        graphics.Clear(Aspose.Imaging.Color.Wheat);

         // Нарисуйте дугу, указав объект Pen черного цвета, 
         //прямоугольник, окружающий дугу, начальный угол и угол развертки
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

         // Нарисуйте кривую Безье, задав объект Pen синего цвета и координаты Points.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

         // Нарисуйте кривую, указав объект Pen зеленого цвета и массив Points
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

         // Нарисуйте эллипс, используя объект Pen и окружающий прямоугольник Rectangle
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

         // Нарисовать линию 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

         // Нарисовать круговую диаграмму segment
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

         // Нарисуйте многоугольник, указав объект Pen красного цвета и массив Points
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

         // Рисуем прямоугольник
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

         //Создаем объект SolidBrush и устанавливаем его различные свойства
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        // Нарисуйте строку, используя объект SolidBrush и шрифт, в определенной точке Point
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

         // сохранить все изменения.
        image.Save();
    }
}
```

### Смотрите также

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Рисует кардинальный сплайн через указанный массив структур[`Point`](../../point)с заданным натяжением.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)который определяет цвет, ширину и высоту Кривая. |
| points | Point[] | Массив структур[`Point`](../../point), определяющих сплайн. |
| tension | Single | Значение больше или равное 0,0F, определяющее натяжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen*равно нулю. -или- *points*равно null. |

### Смотрите также

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Рисует кардинальный сплайн через указанный массив структур[`Point`](../../point)с заданным натяжением.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen)который определяет цвет, ширину и высоту Кривая. |
| points | Point[] | Массив структур[`Point`](../../point), определяющих сплайн. |
| offset | Int32 | Смещение от первого элемента в массиве параметра*points*до начальной точки кривой. |
| numberOfSegments | Int32 | Количество сегментов после начальной точки для включения в кривую. |
| tension | Single | Значение больше или равное 0,0F, определяющее натяжение кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen*равно нулю. -или- *points*равно null. |

### Смотрите также

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
