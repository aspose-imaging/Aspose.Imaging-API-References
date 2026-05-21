---
title: "Graphics.FillPie"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Graphics. تملأ داخل قطاع الفطيرة المحدد بقطعة ناقصة محددة بواسطة بنية RectangleF وخطين شعاعيين."
type: docs
weight: 380
url: /ar/net/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

تملأ داخل قطاع الفطيرة المحدد بقطعة ناقصة محددة بواسطة بنية [`RectangleF`](../../rectanglef/) وخطين شعاعيين.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد خصائص التعبئة. |
| rect | Rectangle | بنية [`Rectangle`](../../rectangle/) التي تمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| startAngle | فردي | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweepAngle | فردي | الزاوية بالدرجات تُقاس باتجاه عقارب الساعة من المعامل *startAngle* إلى الجانب الثاني من قطاع الفطيرة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* هو null. |

## أمثلة

المثال التالي يوضح كيفية تجميع صورة GIF متحركة من كتل GIF فردية.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة GIF بحجم 100 × 100 بكسل.
// الكتلة الأولى تكون سوداء بالكامل بشكل افتراضي.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // الدائرة الأولى حمراء
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // الدائرة الثانية سوداء
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // زد تدريجياً زاوية الشكل القوسي الأحمر.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // زد تدريجياً زاوية القوس الأسود وأزل القوس الأحمر.
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

### انظر أيضًا

* class [Brush](../../brush/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

تملأ داخل قطاع الفطيرة المحدد بقطعة ناقصة محددة بواسطة بنية [`RectangleF`](../../rectanglef/) وخطين شعاعيين.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد خصائص التعبئة. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) بنية التي تمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| startAngle | فردي | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweepAngle | فردي | الزاوية بالدرجات تُقاس باتجاه عقارب الساعة من المعامل *startAngle* إلى الجانب الثاني من قطاع الفطيرة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* هو null. |

### انظر أيضًا

* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

يملأ داخل قطاع فطيرة معرف بإهليلج محدد بزوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد خصائص التعبئة. |
| x | فردي | الإحداثي x للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| y | فردي | الإحداثي y للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| العرض | فردي | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| الارتفاع | فردي | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| startAngle | فردي | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweepAngle | فردي | الزاوية بالدرجات تُقاس باتجاه عقارب الساعة من المعامل *startAngle* إلى الجانب الثاني من قطاع الفطيرة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* هو null. |

### انظر أيضًا

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

يملأ داخل قطاع فطيرة معرف بإهليلج محدد بزوج من الإحداثيات، عرض، ارتفاع، وخطين شعاعيين.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد خصائص التعبئة. |
| x | Int32 | الإحداثي x للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| y | Int32 | الإحداثي y للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| العرض | Int32 | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| الارتفاع | Int32 | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه قطاع الفطيرة. |
| startAngle | Int32 | الزاوية بالدرجات المقاسة باتجاه عقارب الساعة من محور x إلى الجانب الأول لقطاع الفطيرة. |
| sweepAngle | Int32 | الزاوية بالدرجات تُقاس باتجاه عقارب الساعة من المعامل *startAngle* إلى الجانب الثاني من قطاع الفطيرة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* هو null. |

### انظر أيضًا

* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


