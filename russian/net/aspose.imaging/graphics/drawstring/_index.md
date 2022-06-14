---
title: DrawString
second_title: Справочник по Aspose.Imaging for .NET API
description: Рисует указанную текстовую строку в указанном месте с указаннымBrushaspose.imaging/brushиFontaspose.imaging/fontобъекты.
type: docs
weight: 320
url: /ru/net/aspose.imaging/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../../brush)и[`Font`](../../font)объекты.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Строка для рисования. |
| font | Font | [`Font`](../../font), который определяет текстовый формат строки. |
| brush | Brush | [`Brush`](../../brush)определяющий цвет и текстуру рисуемого текста. |
| x | Single | Координата x левого верхнего угла нарисованного текста. |
| y | Single | Y-координата левого верхнего угла нарисованного текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. -или- *s*равно нулю. |

### Смотрите также

* class [Font](../../font)
* class [Brush](../../brush)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../../brush)и[`Font`](../../font)объекты.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Строка для рисования. |
| font | Font | [`Font`](../../font), который определяет текстовый формат строки. |
| brush | Brush | [`Brush`](../../brush)определяющий цвет и текстуру рисуемого текста. |
| point | PointF | [`PointF`](../../pointf)структура, указывающая верхний левый угол нарисованного текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. -или- *s*равно нулю. |

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

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../../brush)и[`Font`](../../font)объекты, использующие атрибуты форматирования указанного[`StringFormat`](../../stringformat).

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Строка для рисования. |
| font | Font | [`Font`](../../font), который определяет текстовый формат строки. |
| brush | Brush | [`Brush`](../../brush)определяющий цвет и текстуру рисуемого текста. |
| x | Single | Координата x левого верхнего угла нарисованного текста. |
| y | Single | Y-координата левого верхнего угла нарисованного текста. |
| format | StringFormat | [`StringFormat`](../../stringformat)который определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, которые применяются к нарисованный текст. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. -или- *s*равно нулю. |

### Смотрите также

* class [Font](../../font)
* class [Brush](../../brush)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../../brush)и[`Font`](../../font)объекты, использующие атрибуты форматирования указанного[`StringFormat`](../../stringformat).

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Строка для рисования. |
| font | Font | [`Font`](../../font), который определяет текстовый формат строки. |
| brush | Brush | [`Brush`](../../brush)определяющий цвет и текстуру рисуемого текста. |
| point | PointF | [`PointF`](../../pointf)структура, указывающая верхний левый угол нарисованного текста. |
| format | StringFormat | [`StringFormat`](../../stringformat)который определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, которые применяются к нарисованный текст. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. -или- *s*равно нулю. |

### Смотрите также

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Рисует указанную текстовую строку в указанном прямоугольнике с указанным[`Brush`](../../brush)и[`Font`](../../font)объекты.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Строка для рисования. |
| font | Font | [`Font`](../../font), который определяет текстовый формат строки. |
| brush | Brush | [`Brush`](../../brush)определяющий цвет и текстуру рисуемого текста. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef)структура, указывающая расположение нарисованного текста. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. -или- *s*равно нулю. |

### Смотрите также

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Рисует указанную текстовую строку в указанном прямоугольнике с указанным[`Brush`](../../brush)и[`Font`](../../font)объекты, использующие атрибуты форматирования указанного[`StringFormat`](../../stringformat).

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | String | Строка для рисования. |
| font | Font | [`Font`](../../font), который определяет текстовый формат строки. |
| brush | Brush | [`Brush`](../../brush)определяющий цвет и текстуру рисуемого текста. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef)структура, указывающая расположение нарисованного текста. |
| format | StringFormat | [`StringFormat`](../../stringformat)который определяет атрибуты форматирования, такие как межстрочный интервал и выравнивание, которые применяются к нарисованный текст. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. -или- *s*равно нулю. -или- *brush*равно null. |

### Смотрите также

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
