---
title: DrawPie
second_title: Справочник по Aspose.Imaging for .NET API
description: Рисует круговую форму определяемую эллипсом указаннымRectangleFaspose.imaging/rectanglef структура и две радиальные линии.
type: docs
weight: 280
url: /ru/net/aspose.imaging/graphics/drawpie/
---
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

Рисует круговую форму, определяемую эллипсом, указанным[`RectangleF`](../../rectanglef) структура и две радиальные линии.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и стиль формы круга. |
| rect | RectangleF | [`RectangleF`](../../rectanglef) структура, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого получается круговая фигура. |
| startAngle | Single | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны круговой диаграммы. |
| sweepAngle | Single | Угол, измеряемый в градусах по часовой стрелке от*startAngle* параметра ко второй стороне круговой формы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* нулевой. |

### Смотрите также

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

Рисует круговую форму, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и стиль формы круга. |
| x | Single | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого получается круговая фигура. |
| y | Single | Координата Y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого получается круговая фигура. |
| width | Single | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого получается круговая фигура. |
| height | Single | Высота ограничивающего прямоугольника, определяющего эллипс, из которого получается круговая фигура. |
| startAngle | Single | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны круговой диаграммы. |
| sweepAngle | Single | Угол, измеряемый в градусах по часовой стрелке от*startAngle* параметра ко второй стороне круговой формы. |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

Рисует круговую форму, определяемую эллипсом, указанным[`Rectangle`](../../rectangle) структура и две радиальные линии.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и стиль формы круга. |
| rect | Rectangle | [`Rectangle`](../../rectangle) структура, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого получается круговая фигура. |
| startAngle | Single | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны круговой диаграммы. |
| sweepAngle | Single | Угол, измеряемый в градусах по часовой стрелке от*startAngle* параметра ко второй стороне круговой формы. |

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
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

Рисует круговую форму, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) который определяет цвет, ширину и стиль формы круга. |
| x | Int32 | Координата x верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого получается круговая фигура. |
| y | Int32 | Координата Y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого получается круговая фигура. |
| width | Int32 | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого получается круговая фигура. |
| height | Int32 | Высота ограничивающего прямоугольника, определяющего эллипс, из которого получается круговая фигура. |
| startAngle | Int32 | Угол, измеряемый в градусах по часовой стрелке от оси x до первой стороны круговой диаграммы. |
| sweepAngle | Int32 | Угол, измеряемый в градусах по часовой стрелке от*startAngle* параметра ко второй стороне круговой формы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *pen* нулевой. |

### Смотрите также

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
