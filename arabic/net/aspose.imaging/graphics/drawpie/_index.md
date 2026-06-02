---
title: "Graphics.DrawPie"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Graphics. ترسم شكل فطيرة معرف بواسطة إهليلج محدد بواسطة بنية RectangleF وخطين شعاعيين"
type: docs
weight: 290
url: /ar/net/aspose.imaging/graphics/drawpie/
---
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

ترسم شكل فطيرة معرف بواسطة إهليلج محدد بواسطة بنية [`RectangleF`](../../rectanglef/) وخطين شعاعيين.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) التي تمثل المستطيل المحيط الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| startAngle | فردي | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من محور x إلى الجانب الأول لشكل الفطيرة. |
| sweepAngle | فردي | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المتغير *startAngle* إلى الجانب الثاني لشكل الفطيرة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

يرسم شكل فطيرة معرفًا بقطع ناقص محدد بأزواج الإحداثيات، العرض، الارتفاع، وخطين شعاعيين.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| x | فردي | الإحداثي x للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| y | فردي | الإحداثي y للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| العرض | فردي | عرض المستطيل المحيط الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| الارتفاع | فردي | ارتفاع المستطيل المحيط الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| startAngle | فردي | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من محور x إلى الجانب الأول لشكل الفطيرة. |
| sweepAngle | فردي | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المتغير *startAngle* إلى الجانب الثاني لشكل الفطيرة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

ترسم شكل فطيرة معرف بواسطة إهليلج محدد بواسطة بنية [`Rectangle`](../../rectangle/) وخطين شعاعيين.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) التي تمثل المستطيل المحيط الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| startAngle | فردي | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من محور x إلى الجانب الأول لشكل الفطيرة. |
| sweepAngle | فردي | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المتغير *startAngle* إلى الجانب الثاني لشكل الفطيرة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. |

## أمثلة

يستخدم هذا المثال فئة Graphics لإنشاء أشكال أولية على سطح Image. لتوضيح العملية، ينشئ المثال صورة جديدة بصيغة PNG ويرسم أشكالًا أولية على سطح Image باستخدام طرق Draw التي توفرها فئة Graphics.

```csharp
[C#]

//ينشئ مثيلًا من FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //إنشاء مثيل من PngOptions وتعيين خصائصه المتنوعة
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //تعيين المصدر لـ PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //إنشاء مثيل من Image
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //إنشاء وتهيئة مثيل من فئة Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //مسح سطح Graphics
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //رسم قوس بتحديد كائن Pen الذي له اللون الأسود،
        //مستطيل يحيط بالقوس، زاوية البداية وزاوية المسح
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //رسم منحنى بيزيير بتحديد كائن Pen الذي له اللون الأزرق ونقاط الإحداثيات.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //رسم منحنى بتحديد كائن Pen الذي له اللون الأخضر ومصفوفة من النقاط
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //رسم إهليلج باستخدام كائن Pen ومستطيل محيط
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //رسم خط
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //رسم قطعة فطيرة
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //رسم مضلع بتحديد كائن Pen الذي له اللون الأحمر ومصفوفة من النقاط
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //رسم مستطيل
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //إنشاء كائن SolidBrush وتعيين خصائصه المتنوعة
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //رسم نص باستخدام كائن SolidBrush والخط، عند نقطة محددة
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // احفظ جميع التغييرات.
        image.Save();
    }
}
```

### انظر أيضًا

* class [Pen](../../pen/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

يرسم شكل فطيرة معرفًا بقطع ناقص محدد بأزواج الإحداثيات، العرض، الارتفاع، وخطين شعاعيين.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط لشكل الفطيرة. |
| x | Int32 | الإحداثي x للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| y | Int32 | الإحداثي y للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| العرض | Int32 | عرض المستطيل المحيط الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| الارتفاع | Int32 | ارتفاع المستطيل المحيط الذي يحدد الإهليلج الذي يأتي منه شكل الفطيرة. |
| startAngle | Int32 | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من محور x إلى الجانب الأول لشكل الفطيرة. |
| sweepAngle | Int32 | الزاوية مقاسة بالدرجات في اتجاه عقارب الساعة من المتغير *startAngle* إلى الجانب الثاني لشكل الفطيرة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


