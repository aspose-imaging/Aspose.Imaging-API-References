---
title: "Graphics.DrawEllipse"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Graphics. ترسم إهليلجًا يُعرّف بواسطة RectangleF محيط."
type: docs
weight: 220
url: /ar/net/aspose.imaging/graphics/drawellipse/
---
## DrawEllipse(Pen, RectangleF) {#drawellipse_1}

ترسم إهليلجًا يُعرّف بواسطة محيط [`RectangleF`](../../rectanglef/).

```csharp
public void DrawEllipse(Pen pen, RectangleF rect)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط للإهليلج. |
| rect | RectangleF | بنية [`RectangleF`](../../rectanglef/) التي تحدد حدود الإهليلج. |

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

## DrawEllipse(Pen, float, float, float, float) {#drawellipse_3}

يرسم إهليلجًا معرفًا بواسطة مستطيل محيط محدد بواسطة زوج من الإحداثيات، ارتفاع، وعرض.

```csharp
public void DrawEllipse(Pen pen, float x, float y, float width, float height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط للإهليلج. |
| x | فردي | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد الإهليلج. |
| y | فردي | الإحداثي ص للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| العرض | فردي | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| الارتفاع | فردي | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

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

## DrawEllipse(Pen, Rectangle) {#drawellipse}

يرسم قطعًا ناقصًا محددًا بواسطة بنية [`Rectangle`](../../rectangle/) محيطة.

```csharp
public void DrawEllipse(Pen pen, Rectangle rect)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط للإهليلج. |
| rect | Rectangle | بنية [`Rectangle`](../../rectangle/) التي تحدد حدود القطع الناقص. |

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

## DrawEllipse(Pen, int, int, int, int) {#drawellipse_2}

يرسم إهليلجًا معرفًا بواسطة مستطيل محيط محدد بواسطة زوج من الإحداثيات، ارتفاع، وعرض.

```csharp
public void DrawEllipse(Pen pen, int x, int y, int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط للإهليلج. |
| x | Int32 | الإحداثي السيني للزاوية العليا اليسرى للمستطيل المحيط الذي يحدد الإهليلج. |
| y | Int32 | الإحداثي ص للزاوية العلوية اليسرى للمستطيل المحيط الذي يحدد القطع الناقص. |
| العرض | Int32 | عرض المستطيل المحيط الذي يحدد القطع الناقص. |
| الارتفاع | Int32 | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


