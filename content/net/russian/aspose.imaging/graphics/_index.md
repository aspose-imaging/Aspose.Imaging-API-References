---
title: Graphics
second_title: Справочник по Aspose.Imaging for .NET API
description: Представляет графику в соответствии с графическим движком используемым в текущей сборке.
type: docs
weight: 9360
url: /ru/aspose.imaging/graphics/
---
## Graphics class

Представляет графику в соответствии с графическим движком, используемым в текущей сборке.

```csharp
public sealed class Graphics
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Graphics](graphics)(Image) | Инициализирует новый экземпляр[`Graphics`](../graphics) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Clip](../../aspose.imaging/graphics/clip) { get; set; } | Получает или задает область клипа. |
| [CompositingQuality](../../aspose.imaging/graphics/compositingquality) { get; set; } | Получает или задает качество композитинга. |
| [DpiX](../../aspose.imaging/graphics/dpix) { get; } | Получает горизонтальное разрешение этого Aspose.Imaging.Graphics. |
| [DpiY](../../aspose.imaging/graphics/dpiy) { get; } | Получает вертикальное разрешение Aspose.Imaging.Graphics. |
| [Image](../../aspose.imaging/graphics/image) { get; } | Получает изображение. |
| [InterpolationMode](../../aspose.imaging/graphics/interpolationmode) { get; set; } | Получает или задает режим интерполяции. |
| [IsInBeginUpdateCall](../../aspose.imaging/graphics/isinbeginupdatecall) { get; } | Получает значение, указывающее, находится ли графика в состоянии вызова BeginUpdate. |
| [PageScale](../../aspose.imaging/graphics/pagescale) { get; set; } | Получает или задает масштаб между мировыми единицами и единицами страницы для этого Aspose.Imaging.Graphics. |
| [PageUnit](../../aspose.imaging/graphics/pageunit) { get; set; } | Получает или задает единицу измерения, используемую для координат страницы в этом Aspose.Imaging.Graphics. |
| [SmoothingMode](../../aspose.imaging/graphics/smoothingmode) { get; set; } | Получает или задает режим сглаживания. |
| [TextRenderingHint](../../aspose.imaging/graphics/textrenderinghint) { get; set; } | Получает или задает подсказку рендеринга текста. |
| [Transform](../../aspose.imaging/graphics/transform) { get; set; } | Получает или задает копию геометрического преобразования мира для этого[`Graphics`](../graphics) . |

## Методы

| Имя | Описание |
| --- | --- |
| [BeginUpdate](../../aspose.imaging/graphics/beginupdate)() | Запускает кэширование следующих графических операций. Графические эффекты, примененные впоследствии, не будут применены немедленно, вместо этого EndUpdate вызовет одновременное применение всех эффектов. |
| [Clear](../../aspose.imaging/graphics/clear)(Color) | Очищает графическую поверхность, используя указанный цвет. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc)(Pen, Rectangle, float, float) | Рисует дугу, представляющую часть эллипса, заданного[`Rectangle`](../rectangle) структура. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_1)(Pen, RectangleF, float, float) | Рисует дугу, представляющую часть эллипса, заданного[`RectangleF`](../rectanglef) структура. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_3)(Pen, float, float, float, float, float, float) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [DrawArc](../../aspose.imaging/graphics/drawarc#drawarc_2)(Pen, int, int, int, int, int, int) | Рисует дугу, представляющую часть эллипса, заданную парой координат, шириной и высотой. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier)(Pen, Point, Point, Point, Point) | Рисует сплайн Безье, определяемый четырьмя[`Point`](../point) структуры. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_1)(Pen, PointF, PointF, PointF, PointF) | Рисует сплайн Безье, определяемый четырьмя[`PointF`](../pointf) структуры. |
| [DrawBezier](../../aspose.imaging/graphics/drawbezier#drawbezier_2)(Pen, float, float, float, float, float, float, float, float) | Рисует сплайн Безье, определяемый четырьмя упорядоченными парами координат, представляющими точки. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers)(Pen, PointF[]) | Рисует серию сплайнов Безье из массива[`PointF`](../pointf) структуры. |
| [DrawBeziers](../../aspose.imaging/graphics/drawbeziers#drawbeziers_1)(Pen, Point[]) | Рисует серию сплайнов Безье из массива[`Point`](../point) структуры. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve)(Pen, PointF[]) | Рисует замкнутый кардинальный сплайн, определяемый массивом[`PointF`](../pointf) структуры. Этот метод использует натяжение по умолчанию 0,5 иAlternate режим заполнения. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_2)(Pen, Point[]) | Рисует замкнутый кардинальный сплайн, определяемый массивом[`Point`](../point) структуры. Этот метод использует натяжение по умолчанию 0,5 иAlternate режим заполнения. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_1)(Pen, PointF[], float) | Рисует замкнутый кардинальный сплайн, определяемый массивом[`PointF`](../pointf) конструкции с заданным натяжением. Этот метод использует значение по умолчаниюAlternate режим заполнения. |
| [DrawClosedCurve](../../aspose.imaging/graphics/drawclosedcurve#drawclosedcurve_3)(Pen, Point[], float) | Рисует замкнутый кардинальный сплайн, определяемый массивом[`Point`](../point) конструкции с заданным натяжением. Этот метод использует значение по умолчаниюAlternate режим заполнения. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve)(Pen, PointF[]) | Рисует кардинальный сплайн через заданный массив[`PointF`](../pointf) структуры. Этот метод использует натяжение по умолчанию 0,5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_4)(Pen, Point[]) | Рисует кардинальный сплайн через заданный массив[`Point`](../point) структуры. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_3)(Pen, PointF[], float) | Рисует кардинальный сплайн через заданный массив[`PointF`](../pointf) конструкции с заданным натяжением. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_6)(Pen, Point[], float) | Рисует кардинальный сплайн через заданный массив[`Point`](../point) конструкции с заданным натяжением. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_1)(Pen, PointF[], int, int) | Рисует кардинальный сплайн через заданный массив[`PointF`](../pointf) структуры. Рисунок начинается со смещения от начала массива. Этот метод использует натяжение по умолчанию 0,5. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_2)(Pen, PointF[], int, int, float) | Рисует кардинальный сплайн через заданный массив[`PointF`](../pointf)конструкции с заданным натяжением. Рисунок начинается со смещения от начала массива. |
| [DrawCurve](../../aspose.imaging/graphics/drawcurve#drawcurve_5)(Pen, Point[], int, int, float) | Рисует кардинальный сплайн через заданный массив[`Point`](../point) конструкции с заданным натяжением. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse)(Pen, Rectangle) | Рисует эллипс, заданный ограничивающей[`Rectangle`](../rectangle) структура. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_1)(Pen, RectangleF) | Рисует эллипс, определяемый ограничивающей[`RectangleF`](../rectanglef) . |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_3)(Pen, float, float, float, float) | Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [DrawEllipse](../../aspose.imaging/graphics/drawellipse#drawellipse_2)(Pen, int, int, int, int) | Рисует эллипс, определяемый ограничивающим прямоугольником, заданным парой координат, высотой и шириной. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage)(Image, Point) | Рисует указанный[`Image`](./image) , используя исходный физический размер, в указанном месте. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_1)(Image, PointF) | Рисует указанный[`Image`](./image) , используя исходный физический размер, в указанном месте. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_2)(Image, PointF[]) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_6)(Image, Point[]) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_10)(Image, Rectangle) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_15)(Image, RectangleF) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_22)(Image, float, float) | Рисует указанный[`Image`](./image) , используя исходный физический размер, в указанном месте. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_20)(Image, int, int) | Рисует указанное изображение, используя исходный физический размер, в месте, указанном парой координат. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_3)(Image, PointF[], RectangleF) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_7)(Image, Point[], Rectangle) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_11)(Image, Rectangle, GraphicsUnit) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_16)(Image, RectangleF, GraphicsUnit) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_4)(Image, PointF[], RectangleF, GraphicsUnit) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_8)(Image, Point[], Rectangle, GraphicsUnit) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_12)(Image, Rectangle, GraphicsUnit, ImageAttributes) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_13)(Image, Rectangle, Rectangle, GraphicsUnit) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_17)(Image, RectangleF, GraphicsUnit, ImageAttributes) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_18)(Image, RectangleF, RectangleF, GraphicsUnit) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_23)(Image, float, float, float, float) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_21)(Image, int, int, int, int) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_5)(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_9)(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) | Рисует указанную часть указанного*image* в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_14)(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImage](../../aspose.imaging/graphics/drawimage#drawimage_19)(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) | Рисует указанный[`Image`](./image) в указанном месте и с указанным размером. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled)(Image, Point) | Рисует указанное изображение, используя исходный физический размер в указанном месте. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_1)(Image, Rectangle) | Рисует указанное изображение, используя исходный физический размер в указанном месте. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_2)(Image, int, int) | Рисует указанное изображение, используя его исходный физический размер в месте, указанном парой координат. |
| [DrawImageUnscaled](../../aspose.imaging/graphics/drawimageunscaled#drawimageunscaled_3)(Image, int, int, int, int) | Рисует указанное изображение, используя исходный физический размер в указанном месте. |
| [DrawImageUnscaledAndClipped](../../aspose.imaging/graphics/drawimageunscaledandclipped)(Image, Rectangle) | Рисует заданное изображение без масштабирования и при необходимости обрезает его, чтобы оно поместилось в указанный прямоугольник. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline)(Pen, Point, Point) | Рисует линию, соединяющую два[`Point`](../point) структуры. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_1)(Pen, PointF, PointF) | Рисует линию, соединяющую два[`PointF`](../pointf) структуры. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_3)(Pen, float, float, float, float) | Рисует линию, соединяющую две точки, заданные парами координат. |
| [DrawLine](../../aspose.imaging/graphics/drawline#drawline_2)(Pen, int, int, int, int) | Рисует линию, соединяющую две точки, заданные парами координат. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines)(Pen, PointF[]) | Рисует серию отрезков, соединяющих массив[`PointF`](../pointf) структуры. |
| [DrawLines](../../aspose.imaging/graphics/drawlines#drawlines_1)(Pen, Point[]) | Рисует серию отрезков, соединяющих массив[`Point`](../point) структуры. |
| [DrawPath](../../aspose.imaging/graphics/drawpath)(Pen, GraphicsPath) | Рисует[`GraphicsPath`](../graphicspath) . |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie)(Pen, Rectangle, float, float) | Рисует круговую форму, определяемую эллипсом, указанным[`Rectangle`](../rectangle) структура и две радиальные линии. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_1)(Pen, RectangleF, float, float) | Рисует круговую форму, определяемую эллипсом, указанным[`RectangleF`](../rectanglef) структура и две радиальные линии. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_3)(Pen, float, float, float, float, float, float) | Рисует круговую форму, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [DrawPie](../../aspose.imaging/graphics/drawpie#drawpie_2)(Pen, int, int, int, int, int, int) | Рисует круговую форму, определяемую эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon)(Pen, PointF[]) | Рисует многоугольник, определяемый массивом[`PointF`](../pointf) структуры. |
| [DrawPolygon](../../aspose.imaging/graphics/drawpolygon#drawpolygon_1)(Pen, Point[]) | Рисует многоугольник, определяемый массивом[`Point`](../point) структуры. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle)(Pen, Rectangle) | Рисует прямоугольник, заданный[`Rectangle`](../rectangle) структура. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_1)(Pen, RectangleF) | Рисует прямоугольник, заданный[`RectangleF`](../rectanglef) структура. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_3)(Pen, float, float, float, float) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [DrawRectangle](../../aspose.imaging/graphics/drawrectangle#drawrectangle_2)(Pen, int, int, int, int) | Рисует прямоугольник, заданный парой координат, шириной и высотой. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles)(Pen, RectangleF[]) | Рисует серию прямоугольников, указанных[`RectangleF`](../rectanglef) структуры. |
| [DrawRectangles](../../aspose.imaging/graphics/drawrectangles#drawrectangles_1)(Pen, Rectangle[]) | Рисует серию прямоугольников, указанных[`Rectangle`](../rectangle) структуры. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring)(string, Font, Brush, PointF) | Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../brush) а также[`Font`](../font) объекты. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_2)(string, Font, Brush, RectangleF) | Рисует указанную текстовую строку в указанном прямоугольнике с указанным[`Brush`](../brush) а также[`Font`](../font) объекты. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_4)(string, Font, Brush, float, float) | Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../brush) а также[`Font`](../font) объекты. |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_1)(string, Font, Brush, PointF, StringFormat) | Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../brush) а также[`Font`](../font) объекты, использующие атрибуты форматирования указанного[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_3)(string, Font, Brush, RectangleF, StringFormat) | Рисует указанную текстовую строку в указанном прямоугольнике с указанным[`Brush`](../brush) а также[`Font`](../font) объекты, использующие атрибуты форматирования указанного[`StringFormat`](../stringformat) . |
| [DrawString](../../aspose.imaging/graphics/drawstring#drawstring_5)(string, Font, Brush, float, float, StringFormat) | Рисует указанную текстовую строку в указанном месте с указанным[`Brush`](../brush) а также[`Font`](../font) объекты, использующие атрибуты форматирования указанного[`StringFormat`](../stringformat) . |
| [EndUpdate](../../aspose.imaging/graphics/endupdate)() | Завершает кэширование графических операций, запущенных после вызова BeginUpdate. Предыдущие графические операции будут применены сразу при вызове этого метода. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve)(Brush, PointF[]) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом[`PointF`](../pointf) структуры. Этот метод использует натяжение по умолчанию 0,5 иAlternate режим заполнения. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_3)(Brush, Point[]) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом[`Point`](../point) структуры. Этот метод использует натяжение по умолчанию 0,5 иAlternate режим заполнения. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_1)(Brush, PointF[], FillMode) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом[`PointF`](../pointf) структуры, использующие указанный режим заполнения. Этот метод использует натяжение по умолчанию 0,5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_4)(Brush, Point[], FillMode) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом[`Point`](../point) структуры, использующие указанный режим заполнения. Этот метод использует натяжение по умолчанию 0,5. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_2)(Brush, PointF[], FillMode, float) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом[`PointF`](../pointf) структуры с использованием указанного режима заполнения и напряжения. |
| [FillClosedCurve](../../aspose.imaging/graphics/fillclosedcurve#fillclosedcurve_5)(Brush, Point[], FillMode, float) | Заполняет внутреннюю часть замкнутой кардинальной сплайновой кривой, определяемой массивом[`Point`](../point) структуры с использованием указанного режима заполнения и напряжения. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse)(Brush, Rectangle) | Заполняет внутреннюю часть эллипса, определяемого ограничивающим прямоугольником, указанным[`Rectangle`](../rectangle) структура. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_1)(Brush, RectangleF) | Заполняет внутреннюю часть эллипса, определяемого ограничивающим прямоугольником, указанным[`RectangleF`](../rectanglef) структура. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_3)(Brush, float, float, float, float) | Заполняет внутреннюю часть эллипса, определяемого ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [FillEllipse](../../aspose.imaging/graphics/fillellipse#fillellipse_2)(Brush, int, int, int, int) | Заполняет внутреннюю часть эллипса, определяемого ограничивающим прямоугольником, заданным парой координат, шириной и высотой. |
| [FillPath](../../aspose.imaging/graphics/fillpath)(Brush, GraphicsPath) | Заполняет внутреннюю часть[`GraphicsPath`](../graphicspath) . |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie)(Brush, Rectangle, float, float) | Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, указанным[`RectangleF`](../rectanglef) структура и две радиальные линии. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_1)(Brush, RectangleF, float, float) | Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, указанным[`RectangleF`](../rectanglef) структура и две радиальные линии. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_3)(Brush, float, float, float, float, float, float) | Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [FillPie](../../aspose.imaging/graphics/fillpie#fillpie_2)(Brush, int, int, int, int, int, int) | Заполняет внутреннюю часть сектора круговой диаграммы, определяемого эллипсом, заданным парой координат, шириной, высотой и двумя радиальными линиями. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon)(Brush, PointF[]) | Заполняет внутреннюю часть многоугольника, определяемого массивом точек, заданным параметром[`PointF`](../pointf) структуры иAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_2)(Brush, Point[]) | Заполняет внутреннюю часть многоугольника, определяемого массивом точек, заданным параметром[`Point`](../point) структуры иAlternate . |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_1)(Brush, PointF[], FillMode) | Заполняет внутреннюю часть многоугольника, определяемого массивом точек, заданным параметром[`PointF`](../pointf) структуры, использующие указанный режим заливки. |
| [FillPolygon](../../aspose.imaging/graphics/fillpolygon#fillpolygon_3)(Brush, Point[], FillMode) | Заполняет внутреннюю часть многоугольника, определяемого массивом точек, заданным параметром[`Point`](../point) структуры, использующие указанный режим заливки. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle)(Brush, Rectangle) | Заполняет внутреннюю часть прямоугольника, указанного[`Rectangle`](../rectangle) структура. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_1)(Brush, RectangleF) | Заполняет внутреннюю часть прямоугольника, указанного[`RectangleF`](../rectanglef) структура. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_3)(Brush, float, float, float, float) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [FillRectangle](../../aspose.imaging/graphics/fillrectangle#fillrectangle_2)(Brush, int, int, int, int) | Заполняет внутреннюю часть прямоугольника, заданного парой координат, шириной и высотой. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles)(Brush, RectangleF[]) | Заполняет внутреннюю часть ряда прямоугольников, заданных параметром[`RectangleF`](../rectanglef) структуры. |
| [FillRectangles](../../aspose.imaging/graphics/fillrectangles#fillrectangles_1)(Brush, Rectangle[]) | Заполняет внутреннюю часть ряда прямоугольников, заданных параметром[`Rectangle`](../rectangle) структуры. |
| [FillRegion](../../aspose.imaging/graphics/fillregion)(Brush, Region) | Заполняет внутреннюю часть[`Region`](../region) . |
| [MeasureString](../../aspose.imaging/graphics/measurestring)(string, Font, SizeF, StringFormat) | Измеряет указанную текстовую строку с указанными параметрами |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform)(Matrix) | Умножает[`Matrix`](../matrix) который представляет собой локальное геометрическое преобразование этого[`Graphics`](../graphics) указанным[`Matrix`](../matrix) путем добавления указанного[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/graphics/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Умножает[`Matrix`](../matrix) который представляет собой локальное геометрическое преобразование этого[`Graphics`](../graphics) указанным[`Matrix`](../matrix) в указанном порядке. |
| [ResetTransform](../../aspose.imaging/graphics/resettransform)() | Сбрасывает[`Transform`](./transform) свойство к личности. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform)(float) | Поворачивает локальное геометрическое преобразование на указанную величину. Этот метод добавляет поворот к преобразованию. |
| [RotateTransform](../../aspose.imaging/graphics/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform)(float, float) | Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования перед преобразованием. |
| [ScaleTransform](../../aspose.imaging/graphics/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Масштабирует локальное геометрическое преобразование на указанные величины в указанном порядке. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform)(float, float) | Преобразует локальное геометрическое преобразование по указанным размерам. Этот метод добавляет перевод к transform. |
| [TranslateTransform](../../aspose.imaging/graphics/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Преобразует локальное геометрическое преобразование по указанным размерам в указанном порядке. |

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

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
