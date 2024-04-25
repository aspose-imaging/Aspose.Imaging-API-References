---
title: DrawBezier
second_title: Справочник по Aspose.Imaging for .NET API
description: Рисует сплайн Безье определяемый четырьмя упорядоченными парами координат представляющими точки.
type: docs
weight: 170
url: /ru/aspose.imaging/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Рисует сплайн Безье, определяемый четырьмя упорядоченными парами координат, представляющими точки.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и стиль кривой. |
| x1 | Single | Координата x начальной точки кривой. |
| y1 | Single | Y-координата начальной точки кривой. |
| x2 | Single | Координата x первой контрольной точки кривой. |
| y2 | Single | Y-координата первой контрольной точки кривой. |
| x3 | Single | Координата x второй контрольной точки кривой. |
| y3 | Single | Y-координата второй контрольной точки кривой. |
| x4 | Single | Координата x конечной точки кривой. |
| y4 | Single | Y-координата конечной точки кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* нулевой. |

### Смотрите также

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Рисует сплайн Безье, определяемый четырьмя[`PointF`](../../pointf) структуры.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и стиль кривой. |
| pt1 | PointF | [`PointF`](../../pointf) структура, представляющая начальную точку кривой. |
| pt2 | PointF | [`PointF`](../../pointf) структура, представляющая первую контрольную точку кривой. |
| pt3 | PointF | [`PointF`](../../pointf) структура, представляющая вторую контрольную точку кривой. |
| pt4 | PointF | [`PointF`](../../pointf) структура, представляющая конечную точку кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* нулевой. |

### Смотрите также

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Рисует сплайн Безье, определяемый четырьмя[`Point`](../../point) структуры.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) структура, определяющая цвет, ширину и стиль кривой. |
| pt1 | Point | [`Point`](../../point) структура, представляющая начальную точку кривой. |
| pt2 | Point | [`Point`](../../point) структура, представляющая первую контрольную точку кривой. |
| pt3 | Point | [`Point`](../../point) структура, представляющая вторую контрольную точку кривой. |
| pt4 | Point | [`Point`](../../point) структура, представляющая конечную точку кривой. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* нулевой. |

### Примеры

В этом примере класс Graphics используется для создания примитивных фигур на поверхности изображения. Чтобы продемонстрировать операцию, в примере создается новое изображение в формате PNG и рисуются примитивные фигуры на поверхности изображения с использованием методов Draw, предоставляемых классом Graphics.

```csharp
[C#]

// Создает экземпляр FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Создаем экземпляр PngOptions и устанавливаем его различные свойства
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Установить источник для PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Создаем экземпляр изображения 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Создаем и инициализируем экземпляр класса Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Очистить графическую поверхность
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        // Нарисуйте дугу, указав объект Pen, имеющий черный цвет, 
        //прямоугольник, окружающий дугу, начальный угол и угол развертки
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        // Нарисуйте кривую Безье, задав объект Pen синего цвета и координаты Points.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Нарисуйте кривую, указав объект Pen зеленого цвета и массив точек
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        // Нарисуйте эллипс, используя объект Pen и окружающий прямоугольник
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        // Нарисовать линию 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        // Нарисовать сегмент пирога
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        // Нарисуйте многоугольник, указав объект Pen красного цвета и массив точек
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        // Рисуем прямоугольник
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Создаем объект SolidBrush и устанавливаем его различные свойства
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        // Нарисуйте строку, используя объект SolidBrush и шрифт, в определенной точке
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
