---
title: "Graphics.DrawBezier"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Graphics. ترسم منحنى Bézier محدد بأربع أزواج مرتبة من الإحداثيات تمثل نقاطًا"
type: docs
weight: 180
url: /ar/net/aspose.imaging/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

يرسم منحنى بيزيير معرف بأربع أزواج مرتبة من الإحداثيات تمثل نقاطًا.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| x1 | فردي | الإحداثي x لنقطة بدء المنحنى. |
| y1 | فردي | الإحداثي y لنقطة بدء المنحنى. |
| x2 | فردي | الإحداثي x للنقطة التحكمية الأولى للمنحنى. |
| y2 | فردي | الإحداثي ص للنقطة التحكمية الأولى للمنحنى. |
| x3 | فردي | الإحداثي س للنقطة التحكمية الثانية للمنحنى. |
| y3 | فردي | الإحداثي ص للنقطة التحكمية الثانية للمنحنى. |
| x4 | فردي | الإحداثي س للنقطة النهائية للمنحنى. |
| y4 | فردي | الإحداثي ص للنقطة النهائية للمنحنى. |

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

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

يرسم منحنى بيزيير محدد بأربع هياكل [`PointF`](../../pointf/).

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| pt1 | PointF | هيكل [`PointF`](../../pointf/) الذي يمثل نقطة البداية للمنحنى. |
| pt2 | PointF | هيكل [`PointF`](../../pointf/) الذي يمثل النقطة التحكمية الأولى للمنحنى. |
| pt3 | PointF | هيكل [`PointF`](../../pointf/) الذي يمثل النقطة التحكمية الثانية للمنحنى. |
| pt4 | PointF | هيكل [`PointF`](../../pointf/) الذي يمثل نقطة النهاية للمنحنى. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *pen* فارغ. |

### انظر أيضًا

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

يرسم منحنى بيزيير محدد بأربع هياكل [`Point`](../../point/).

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | Pen | هيكل [`Pen`](../../pen/) الذي يحدد اللون والعرض والنمط للمنحنى. |
| pt1 | Point | هيكل [`Point`](../../point/) الذي يمثل نقطة البداية للمنحنى. |
| pt2 | Point | هيكل [`Point`](../../point/) الذي يمثل النقطة التحكمية الأولى للمنحنى. |
| pt3 | Point | هيكل [`Point`](../../point/) الذي يمثل النقطة التحكمية الثانية للمنحنى. |
| pt4 | Point | هيكل [`Point`](../../point/) الذي يمثل نقطة النهاية للمنحنى. |

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
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


