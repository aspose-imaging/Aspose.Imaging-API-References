---
title: "Graphics.DrawString"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Graphics. ترسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات Brush و Font المحددة."
type: docs
weight: 330
url: /ar/net/aspose.imaging/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

ترسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../../brush/) و [`Font`](../../font/) المحددة.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | String | السلسلة المراد رسمها. |
| font | Font | [`Font`](../../font/) الذي يحدد تنسيق النص للسلسلة. |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| x | فردي | الإحداثي السيني للزاوية العلوية اليسرى للنص المرسوم. |
| y | فردي | الإحداثي الصادي للزاوية العلوية اليسرى للنص المرسوم. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو- *s* فارغ. |

### انظر أيضًا

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

ترسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../../brush/) و [`Font`](../../font/) المحددة.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | String | السلسلة المراد رسمها. |
| font | Font | [`Font`](../../font/) الذي يحدد تنسيق النص للسلسلة. |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| point | PointF | هيكل [`PointF`](../../pointf/) الذي يحدد الزاوية العلوية اليسرى للنص المرسوم. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو- *s* فارغ. |

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

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

ترسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../../brush/) و [`Font`](../../font/) المحددة مع خصائص التنسيق من [`StringFormat`](../../stringformat/) المحدد.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | String | السلسلة المراد رسمها. |
| font | Font | [`Font`](../../font/) الذي يحدد تنسيق النص للسلسلة. |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| x | فردي | الإحداثي السيني للزاوية العلوية اليسرى للنص المرسوم. |
| y | فردي | الإحداثي الصادي للزاوية العلوية اليسرى للنص المرسوم. |
| format | StringFormat | [`StringFormat`](../../stringformat/) الذي يحدد خصائص التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو- *s* فارغ. |

### انظر أيضًا

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

ترسم سلسلة النص المحددة في الموقع المحدد باستخدام كائنات [`Brush`](../../brush/) و [`Font`](../../font/) المحددة مع خصائص التنسيق من [`StringFormat`](../../stringformat/) المحدد.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | String | السلسلة المراد رسمها. |
| font | Font | [`Font`](../../font/) الذي يحدد تنسيق النص للسلسلة. |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| point | PointF | هيكل [`PointF`](../../pointf/) الذي يحدد الزاوية العلوية اليسرى للنص المرسوم. |
| format | StringFormat | [`StringFormat`](../../stringformat/) الذي يحدد خصائص التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو- *s* فارغ. |

### انظر أيضًا

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

ترسم سلسلة النص المحددة داخل المستطيل المحدد باستخدام كائنات [`Brush`](../../brush/) و [`Font`](../../font/) المحددة.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | String | السلسلة المراد رسمها. |
| font | Font | [`Font`](../../font/) الذي يحدد تنسيق النص للسلسلة. |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| layoutRectangle | RectangleF | بنية [`RectangleF`](../../rectanglef/) التي تحدد موقع النص المرسوم. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو- *s* فارغ. |

### انظر أيضًا

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

يرسم سلسلة النص المحددة في المستطيل المحدد باستخدام كائنات [`Brush`](../../brush/) و[`Font`](../../font/) المحددة، باستخدام سمات التنسيق لكائن [`StringFormat`](../../stringformat/) المحدد.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| s | String | السلسلة المراد رسمها. |
| font | Font | [`Font`](../../font/) الذي يحدد تنسيق النص للسلسلة. |
| brush | Brush | [`Brush`](../../brush/) الذي يحدد اللون والملمس للنص المرسوم. |
| layoutRectangle | RectangleF | بنية [`RectangleF`](../../rectanglef/) التي تحدد موقع النص المرسوم. |
| format | StringFormat | [`StringFormat`](../../stringformat/) الذي يحدد خصائص التنسيق، مثل تباعد الأسطر والمحاذاة، التي تُطبق على النص المرسوم. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *brush* هو null. -or- *s* هو null. -or- *brush* هو null. |

### انظر أيضًا

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.Imaging](../../graphics/)
* assembly [Aspose.Imaging](../../../)


