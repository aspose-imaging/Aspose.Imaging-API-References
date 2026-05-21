---
title: "Graphics.DrawCurve"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Graphics. ترسم منحنى كاردينال عبر مصفوفة محددة من هياكل PointF. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5"
type: docs
weight: 210
url: /ar/net/aspose.imaging/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

ترسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../../pointf/). تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تحدد المنحنى. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

ترسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../../pointf/) باستخدام توتر محدد.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تمثل النقاط التي تحدد المنحنى. |
| توتر | فردي | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

ترسم منحنى كاردينال عبر مصفوفة محددة من هياكل [`PointF`](../../pointf/). يبدأ الرسم متأخرًا عن بداية المصفوفة. تستخدم هذه الطريقة توترًا افتراضيًا قدره 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تحدد المنحنى. |
| الإزاحة | Int32 | الإزاحة من العنصر الأول في مصفوفة المعامل *points* إلى نقطة البدء في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع بعد نقطة البدء لتضمينها في المنحنى. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

يرسم منحنى كاردينال سبلين عبر مصفوفة محددة من هياكل [`PointF`](../../pointf/) باستخدام توتر محدد. يبدأ الرسم بإزاحة من بداية المصفوفة.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تحدد المنحنى. |
| الإزاحة | Int32 | الإزاحة من العنصر الأول في مصفوفة المعامل *points* إلى نقطة البدء في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع بعد نقطة البدء لتضمينها في المنحنى. |
| توتر | فردي | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

يرسم منحنى كاردينال سبلين عبر مصفوفة محددة من هياكل [`Point`](../../point/).

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | Point[] | مصفوفة من هياكل [`Point`](../../point/) التي تحدد المنحنى. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

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
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

يرسم منحنى كاردينال سبلين عبر مصفوفة محددة من هياكل [`Point`](../../point/) باستخدام توتر محدد.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | Point[] | مصفوفة من هياكل [`Point`](../../point/) التي تحدد المنحنى. |
| توتر | فردي | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

يرسم منحنى كاردينال سبلين عبر مصفوفة محددة من هياكل [`Point`](../../point/) باستخدام توتر محدد.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) التي تحدد اللون والعرض والارتفاع للمنحنى. |
| points | Point[] | مصفوفة من هياكل [`Point`](../../point/) التي تحدد المنحنى. |
| الإزاحة | Int32 | الإزاحة من العنصر الأول في مصفوفة المعامل *points* إلى نقطة البدء في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع بعد نقطة البدء لتضمينها في المنحنى. |
| توتر | فردي | قيمة أكبر من أو تساوي 0.0F تحدد توتر المنحنى. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* هو null. -or- *points* هو null. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


