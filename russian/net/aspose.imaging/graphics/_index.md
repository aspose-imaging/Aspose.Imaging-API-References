---
title: Graphics
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет графику в соответствии с графическим движком используемым в текущей сборке.
type: docs
weight: 9360
url: /ru/net/aspose.imaging/graphics/
---
## Graphics class

Представляет графику в соответствии с графическим движком, используемым в текущей сборке.

```csharp
public sealed class Graphics
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Graphics](graphics)(Image) | Инициализирует новый экземпляр класса[`Graphics`](../graphics). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip) { get; set; } | Получает или задает область отсечения. |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality) { get; set; } | Получает или задает качество композиции. |
| [DpiX](../../aspose.imaging/graphics/dpix) { get; } | Получает горизонтальное разрешение этого Aspose.Imaging.Graphics. |
| [DpiY](../../aspose.imaging/graphics/dpiy) { get; } | Получает вертикальное разрешение этого Aspose.Imaging.Graphics. |
| [Image](../../aspose.imaging/graphics/image) { get; } | Получает изображение. |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode) { get; set; } | Получает или задает режим интерполяции. |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall) { get; } | Получает значение, указывающее, находится ли графика в состоянии вызова BeginUpdate. |
| [PageScale](../../aspose.imaging/graphics/pagescale) { get; set; } | Получает или задает масштабирование между мировыми единицами и единицами страницы для этого Aspose.Imaging.Graphics. |
| [PageUnit](../../aspose.imaging/graphics/pageunit) { get; set; } | Получает или задает единицу измерения, используемую для координат страницы в этом Aspose.Imaging.Graphics. |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode) { get; set; } | Получает или задает режим сглаживания. |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint) { get; set; } | Получает или задает подсказку рендеринга текста. |
| [Transform](../../aspose.imaging/graphics/transform) { get; set; } | Получает или задает копию геометрического преобразования мира для этого[`Graphics`](../graphics). |

## Методы

| Имя | Описание |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate)() | Запускает кэширование следующих графических операций. Графические эффекты, примененные впоследствии, не будут применены немедленно, вместо этого EndUpdate вызовет одновременное применение всех эффектов. |
| [Clear](../../aspose.imaging/graphics/clear)(Color) | Очищает графическую поверхность, используя указанный цвет. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc)(Pen, Rectangle, float, float) | Рисует дугу, представляющую часть эллипса, заданного структурой[`Rectangle`](../rectangle). |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_1)(Pen, RectangleF, float, float) | Рисует дугу, представляющую часть эллипса, заданного структурой[`RectangleF`](../rectanglef). |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_3)(Pen, float, float, float, float, float, float) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_2)(Pen, int, int, int, int, int, int) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier)(Pen, Point, Point, Point, Point) | Рисует сплайн Безье, определяемый четырьмя структурами[`Point`](../point). |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Рисует сплайн Безье, определяемый четырьмя[`PointF`](../pointf)структурами. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Рисует сплайн Безье, определяемый четырьмя упорядоченными парами координат, представляющими точки. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers)(Pen, PointF[]) | Рисует серию сплайнов Безье из массива структур[`PointF`](../pointf). |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers_1)(Pen, Point[]) | Рисует ряд сплайнов Безье из массива структур[`Point`](../point). |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve)(Pen, PointF[]) | Рисует замкнутый кардинальный сплайн, определяемый массивом структур[`PointF`](../pointf). Этот метод использует натяжение по умолчанию 0,5 иAlternateрежим заполнения. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_2)(Pen, Point[]) | Рисует замкнутый кардинальный сплайн, определяемый массивом структур[`Point`](../point). Этот метод использует натяжение по умолчанию 0,5 иAlternateрежим заполнения. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_1)(Pen, PointF[], float) | Рисует замкнутый кардинальный сплайн, определяемый массивом структур[`PointF`](../pointf), используя заданное натяжение. Этот метод использует режим заливки по умолчаниюAlternate. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_3)(Pen, Point[], float) | Рисует замкнутый кардинальный сплайн, определяемый массивом структур[`Point`](../point)с заданным натяжением. Этот метод использует режим заливки по умолчаниюAlternate. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve)(Pen, PointF[]) | Рисует кардинальный сплайн через указанный массив структур[`PointF`](../pointf). Этот метод использует натяжение по умолчанию 0,5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_4)(Pen, Point[]) | Рисует кардинальный сплайн через указанный массив структур[`Point`](../point). |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_3)(Pen, PointF[], float) | Рисует кардинальный сплайн через указанный массив структур[`PointF`](../pointf)с заданным натяжением. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_6)(Pen, Point[], float) | Рисует кардинальный сплайн через указанный массив структур[`Point`](../point)с заданным натяжением. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_1)(Pen, PointF[], int, int) | Рисует кардинальный сплайн через указанный массив структур[`PointF`](../pointf). Рисунок начинается со смещения от начала массива. Этот метод использует натяжение по умолчанию 0,5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_2)(Pen, PointF[], int, int, float) | Рисует кардинальный сплайн через указанный массив структур[`PointF`](../pointf)с заданным натяжением. Рисунок начинается со смещения от начала массива. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_5)(Pen, Point[], int, int, float) | Рисует кардинальный сплайн через указанный массив структур[`Point`](../point)с заданным натяжением. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse)(Pen, Rectangle) | Рисует эллипс, заданный ограничивающей[`Rectangle`](../rectangle)структурой. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_1)(Pen, RectangleF) | Рисует эллипс, определенный границей[`RectangleF`](../rectanglef). |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_3)(Pen, float, float, float, float) | Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_2)(Pen, int, int, int, int) | Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage)(Image, Point) | Рисует указанный[`Image`](./image), используя исходный физический размер, в указанном месте. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_1)(Image, PointF) | Рисует указанный[`Image`](./image), используя исходный физический размер, в указанном месте. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_2)(Image, PointF[]) | Рисует указанную часть указанного*image*в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_6)(Image, Point[]) | Рисует указанную часть указанного*image*в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_10)(Image, Rectangle) | Рисует указанный[`Image`](./image)в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_15)(Image, RectangleF) | Рисует указанный[`Image`](./image)в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_22)(Image, float, float) | Рисует указанный[`Image`](./image), используя исходный физический размер, в указанном месте. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_20)(Image, int, int) | Рисует указанное изображение, используя его исходный физический размер, в месте, указанном парой координат. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_3)(Image, PointF[], RectangleF) | Рисует указанную часть указанного*image*в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_7)(Image, Point[], Rectangle) | Рисует указанную часть указанного*image*в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_11)(Image, Rectangle, GraphicsUnit) | Рисует указанный[`Image`](./image)в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_16)(Image, RectangleF, GraphicsUnit) | Рисует указанный[`Image`](./image)в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Рисует указанную часть указанного*image*в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Рисует указанную часть указанного*image*в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Рисует указанный[`Image`](./image)в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Рисует указанный[`Image`](./image)в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Рисует указанный[`Image`](./image)в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Рисует указанный[`Image`](./image)в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_23)(Image, float, float, float, float) | Рисует указанный[`Image`](./image)в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_21)(Image, int, int, int, int) | Рисует указанный[`Image`](./image)в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Рисует указанную часть указанного*image*в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Рисует указанную часть указанного*image*в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Рисует указанный[`Image`](./image)в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Рисует указанный[`Image`](./image)в указанном месте и с указанным размером. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled)(Image, Point) | Рисует указанное изображение, используя его исходный физический размер в указанном месте. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_1)(Image, Rectangle) | Рисует указанное изображение, используя его исходный физический размер в указанном месте. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_2)(Image, int, int) | Рисует указанное изображение, используя его исходный физический размер, в месте, указанном парой координат. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_3)(Image, int, int, int, int) | Рисует указанное изображение, используя его исходный физический размер в указанном месте. |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped)(Image, Rectangle) | Рисует указанное изображение без масштабирования и при необходимости обрезает его, чтобы оно поместилось в указанный прямоугольник. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline)(Pen, Point, Point) | Рисует линию, соединяющую две структуры[`Point`](../point). |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_1)(Pen, PointF, PointF) | Рисует линию, соединяющую две структуры[`PointF`](../pointf). |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_3)(Pen, float, float, float, float) | Рисует линию, соединяющую две точки, заданные парами координат. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_2)(Pen, int, int, int, int) | Рисует линию, соединяющую две точки, заданные парами координат. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines)(Pen, PointF[]) | Рисует ряд отрезков, соединяющих массив структур[`PointF`](../pointf). |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines_1)(Pen, Point[]) | Рисует ряд отрезков, соединяющих массив структур[`Point`](../point). |
| [DrawPath](../../aspose.imaging/graphics/drawpath)(Pen, GraphicsPath) | Рисует[`GraphicsPath`](../graphicspath). |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie)(Pen, Rectangle, float, float) | Рисует круговую форму, определяемую эллипсом, заданным структурой[`Rectangle`](../rectangle)и двумя радиальными линиями. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_1)(Pen, RectangleF, float, float) | Рисует круговую форму, определяемую эллипсом, заданным структурой[`RectangleF`](../rectanglef)и двумя радиальными линиями. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_3)(Pen, float, float, float, float, float, float) | Рисует круговую фигуру, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_2)(Pen, int, int, int, int, int, int) | Рисует круговую фигуру, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon)(Pen, PointF[]) | Рисует многоугольник, определяемый массивом структур[`PointF`](../pointf). |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon_1)(Pen, Point[]) | Рисует многоугольник, определяемый массивом структур[`Point`](../point). |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle)(Pen, Rectangle) | Рисует прямоугольник, заданный структурой[`Rectangle`](../rectangle). |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_1)(Pen, RectangleF) | Рисует прямоугольник, заданный структурой[`RectangleF`](../rectanglef). |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_3)(Pen, float, float, float, float) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_2)(Pen, int, int, int, int) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles)(Pen, RectangleF[]) | Рисует ряд прямоугольников, заданных структурами[`RectangleF`](../rectanglef). |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles_1)(Pen, Rectangle[]) | Рисует ряд прямоугольников, заданных структурами[`Rectangle`](../rectangle). |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring)(string, Font, Brush, PointF) | Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../brush)и[`Font`](../font)объекты. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_2)(string, Font, Brush, RectangleF) | Рисует указанную текстовую строку в указанном прямоугольнике с указанным[`Brush`](../brush)и[`Font`](../font)объекты. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_4)(string, Font, Brush, float, float) | Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../brush)и[`Font`](../font)объекты. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../brush)и[`Font`](../font)объекты, использующие атрибуты форматирования указанного[`StringFormat`](../stringformat). |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Рисует указанную текстовую строку в указанном прямоугольнике с указанным[`Brush`](../brush)и[`Font`](../font)объекты, использующие атрибуты форматирования указанного[`StringFormat`](../stringformat). |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../brush)и[`Font`](../font)объекты, использующие атрибуты форматирования указанного[`StringFormat`](../stringformat). |
| [EndUpdate](../../aspose.imaging/graphics/endupdate)() | Завершает кэширование графических операций, запущенных после вызова BeginUpdate. Предыдущие графические операции будут применены сразу при вызове этого метода. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve)(Brush, PointF[]) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом структур[`PointF`](../pointf). Этот метод использует натяжение по умолчанию 0,5 иAlternateрежим заполнения. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_3)(Brush, Point[]) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом структур[`Point`](../point). Этот метод использует натяжение по умолчанию 0,5 иAlternateрежим заполнения. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_1)(Brush, PointF[], FillMode) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, заданной массивом структур[`PointF`](../pointf)с использованием указанного режима заполнения . Этот метод использует натяжение по умолчанию 0,5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_4)(Brush, Point[], FillMode) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, заданной массивом структур[`Point`](../point)с использованием указанного режима заполнения . Этот метод использует натяжение по умолчанию 0,5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, заданной массивом структур[`PointF`](../pointf)с использованием указанного режима заполнения и напряжение. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, заданной массивом структур[`Point`](../point)с использованием указанного режима заполнения и напряжение. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse)(Brush, Rectangle) | Заполняет внутреннюю часть эллипса, определяемого ограничивающим прямоугольником, заданным структурой[`Rectangle`](../rectangle). |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_1)(Brush, RectangleF) | Заполняет внутреннюю часть эллипса, определяемого ограничивающим прямоугольником, заданным структурой[`RectangleF`](../rectanglef). |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_3)(Brush, float, float, float, float) | Заполняет внутреннюю часть эллипса, определяемого ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_2)(Brush, int, int, int, int) | Заполняет внутреннюю часть эллипса, определяемого ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [FillPath](../../aspose.imaging/graphics/fillpath)(Brush, GraphicsPath) | Заполняет внутреннюю часть[`GraphicsPath`](../graphicspath). |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie)(Brush, Rectangle, float, float) | Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, заданным структурой[`RectangleF`](../rectanglef)и двумя радиальными линиями. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_1)(Brush, RectangleF, float, float) | Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, заданным структурой[`RectangleF`](../rectanglef)и двумя радиальными линиями. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_3)(Brush, float, float, float, float, float, float) | Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_2)(Brush, int, int, int, int, int, int) | Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon)(Brush, PointF[]) | Заполняет внутреннюю часть многоугольника, определяемого массивом точек, заданным[`PointF`](../pointf)структурами иAlternate. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_2)(Brush, Point[]) | Заполняет внутреннюю часть многоугольника, определяемого массивом точек, заданным[`Point`](../point)структурами иAlternate. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_1)(Brush, PointF[], FillMode) | Заполняет внутреннюю часть полигона, определяемого массивом точек, заданных структурами[`PointF`](../pointf)с использованием указанного режима заполнения . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_3)(Brush, Point[], FillMode) | Заполняет внутреннюю часть полигона, определяемого массивом точек, заданных структурами[`Point`](../point)с использованием указанного режима заполнения . |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle)(Brush, Rectangle) | Заполняет внутреннюю часть прямоугольника, заданного структурой[`Rectangle`](../rectangle). |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_1)(Brush, RectangleF) | Заполняет внутреннюю часть прямоугольника, заданного структурой[`RectangleF`](../rectanglef). |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_3)(Brush, float, float, float, float) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_2)(Brush, int, int, int, int) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles)(Brush, RectangleF[]) | Заполняет внутреннюю часть ряда прямоугольников, заданных структурами[`RectangleF`](../rectanglef). |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles_1)(Brush, Rectangle[]) | Заполняет внутреннюю часть серии прямоугольников, заданных структурами[`Rectangle`](../rectangle). |
| [FillRegion](../../aspose.imaging/graphics/fillregion)(Brush, Region) | Заполняет внутреннюю часть[`Region`](../region). |
| [MeasureString](../../aspose.imaging/graphics/measurestring)(string, Font, SizeF, StringFormat) | Измеряет указанную текстовую строку с заданными параметрами |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform)(Matrix) | Умножает[`Matrix`](../matrix), которая представляет локальное геометрическое преобразование этого[`Graphics`](../graphics)указанным[`Matrix`](../matrix)путем добавления указанного[`Matrix`](../matrix). |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Умножает[`Matrix`](../matrix), которая представляет локальное геометрическое преобразование этого[`Graphics`](../graphics)указанным[`Matrix`](../matrix)в указанном порядке. |
| [ResetTransform](../../aspose.imaging/graphics/resettransform)() | Сбрасывает свойство[`Transform`](./transform)в идентичность. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет поворот к преобразованию. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования к преобразованию. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform)(float, float) | Переносит локальное геометрическое преобразование на заданные размеры. Этот метод добавляет перевод к преобразованию. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

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

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
