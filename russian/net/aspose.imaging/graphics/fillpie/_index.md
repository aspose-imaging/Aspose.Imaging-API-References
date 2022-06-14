---
title: FillPie
second_title: Справочник по Aspose.Imaging for .NET API
description: Заполняет внутреннюю часть сектора круговой диаграммы определяемого эллипсом заданным структуройRectangleFaspose.imaging/rectanglefи двумя радиальными линиями.
type: docs
weight: 370
url: /ru/net/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, заданным структурой[`RectangleF`](../../rectanglef)и двумя радиальными линиями.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)который определяет характеристики заливки. |
| rect | Rectangle | [`Rectangle`](../../rectangle)структура, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого исходит сектор круговой диаграммы. |
| startAngle | Single | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора круговой диаграммы. |
| sweepAngle | Single | Угол в градусах, измеренный по часовой стрелке от параметра*startAngle*до второй стороны сектора круговой диаграммы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. |

### Примеры

В следующем примере показано, как составить анимированное изображение GIF из отдельных блоков GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

 // Создаем GIF-изображение 100 x 100 px.
 // Первый блок по умолчанию полностью черный.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
     // Первый круг — red
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

     // Второй круг — black
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

     // Постепенно увеличиваем угол красной дуги shape.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

     // Постепенно увеличиваем угол черной дуги и стираем красную дугу.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### Смотрите также

* class [Brush](../../brush)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, заданным структурой[`RectangleF`](../../rectanglef)и двумя радиальными линиями.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)который определяет характеристики заливки. |
| rect | RectangleF | [`RectangleF`](../../rectanglef)структура, представляющая ограничивающий прямоугольник, определяющий эллипс, из которого исходит сектор круговой диаграммы. |
| startAngle | Single | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора круговой диаграммы. |
| sweepAngle | Single | Угол в градусах, измеренный по часовой стрелке от параметра*startAngle*до второй стороны сектора круговой диаграммы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. |

### Смотрите также

* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)который определяет характеристики заливки. |
| x | Single | Координата x левого верхнего угла ограничивающего прямоугольника, определяющего эллипс, из которого исходит сектор круговой диаграммы. |
| y | Single | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого исходит сектор круговой диаграммы. |
| width | Single | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого исходит сектор круговой диаграммы. |
| height | Single | Высота ограничивающего прямоугольника, определяющего эллипс, из которого исходит сектор круговой диаграммы. |
| startAngle | Single | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора круговой диаграммы. |
| sweepAngle | Single | Угол в градусах, измеренный по часовой стрелке от параметра*startAngle*до второй стороны сектора круговой диаграммы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. |

### Смотрите также

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush)который определяет характеристики заливки. |
| x | Int32 | Координата x левого верхнего угла ограничивающего прямоугольника, определяющего эллипс, из которого исходит сектор круговой диаграммы. |
| y | Int32 | Координата y верхнего левого угла ограничивающего прямоугольника, определяющего эллипс, из которого исходит сектор круговой диаграммы. |
| width | Int32 | Ширина ограничивающего прямоугольника, определяющего эллипс, из которого исходит сектор круговой диаграммы. |
| height | Int32 | Высота ограничивающего прямоугольника, определяющего эллипс, из которого исходит сектор круговой диаграммы. |
| startAngle | Int32 | Угол в градусах, измеренный по часовой стрелке от оси x до первой стороны сектора круговой диаграммы. |
| sweepAngle | Int32 | Угол в градусах, измеренный по часовой стрелке от параметра*startAngle*до второй стороны сектора круговой диаграммы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *brush*равно null. |

### Смотрите также

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* пространство имен [Aspose.Imaging](../../graphics)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
