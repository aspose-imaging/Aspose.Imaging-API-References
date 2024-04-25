---
title: DrawPie
second_title: Aspose.Imaging لمرجع NET API
description: يرسم شكل دائري معرف بقطع ناقص محدد بواسطةRectangleFaspose.imaging/rectanglef هيكل وخطين شعاعي.
type: docs
weight: 280
url: /ar/aspose.imaging/graphics/drawpie/
---
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

يرسم شكل دائري معرف بقطع ناقص محدد بواسطة[`RectangleF`](../../rectanglef) هيكل وخطين شعاعي.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون الشكل الدائري وعرضه ونمطه. |
| rect | RectangleF | [`RectangleF`](../../rectanglef) الهيكل الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه الشكل الدائري. |
| startAngle | Single | تقاس الزاوية بالدرجات في اتجاه عقارب الساعة من المحور x إلى الجانب الأول من الشكل الدائري. |
| sweepAngle | Single | تقاس الزاوية بالدرجات في اتجاه عقارب الساعة من*startAngle* معلمة إلى الجانب الثاني من شكل دائري. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* باطل. |

### أنظر أيضا

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

يرسم شكل دائري محدد بواسطة شكل بيضاوي محدد بواسطة زوج إحداثيات ، وعرض ، وارتفاع ، وخطين نصف قطريين.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون الشكل الدائري وعرضه ونمطه. |
| x | Single | إحداثي x للركن الأيسر العلوي للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه الشكل الدائري. |
| y | Single | إحداثي y للركن الأيسر العلوي للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه الشكل الدائري. |
| width | Single | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه الشكل الدائري. |
| height | Single | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه الشكل الدائري. |
| startAngle | Single | تقاس الزاوية بالدرجات في اتجاه عقارب الساعة من المحور x إلى الجانب الأول من الشكل الدائري. |
| sweepAngle | Single | تقاس الزاوية بالدرجات في اتجاه عقارب الساعة من*startAngle* معلمة إلى الجانب الثاني من شكل دائري. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* باطل. |

### أنظر أيضا

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

يرسم شكل دائري معرف بقطع ناقص محدد بواسطة[`Rectangle`](../../rectangle) هيكل وخطين شعاعي.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون الشكل الدائري وعرضه ونمطه. |
| rect | Rectangle | [`Rectangle`](../../rectangle) الهيكل الذي يمثل المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه الشكل الدائري. |
| startAngle | Single | تقاس الزاوية بالدرجات في اتجاه عقارب الساعة من المحور x إلى الجانب الأول من الشكل الدائري. |
| sweepAngle | Single | تقاس الزاوية بالدرجات في اتجاه عقارب الساعة من*startAngle* معلمة إلى الجانب الثاني من شكل دائري. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* باطل. |

### أمثلة

يستخدم هذا المثال فئة الرسومات لإنشاء أشكال بدائية على سطح الصورة. لتوضيح العملية ، يقوم المثال بإنشاء صورة جديدة بتنسيق PNG ورسم أشكال بدائية على سطح الصورة باستخدام طرق الرسم المكشوفة بواسطة فئة الرسومات

```csharp
[C#]

// ينشئ مثيلاً من FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    // قم بإنشاء مثيل لـ PngOptions وقم بتعيين خصائصه المختلفة
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // تعيين المصدر لخيارات PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    // إنشاء مثيل للصورة 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        // إنشاء وتهيئة مثيل لفئة الرسومات
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        // مسح سطح الرسومات
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        // ارسم قوسًا بتحديد كائن القلم ذي اللون الأسود ، 
        // أ مستطيل يحيط بالقوس وزاوية البدء وزاوية المسح
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        // ارسم بيزير عن طريق تحديد كائن القلم ذي اللون الأزرق ونقاط التنسيق.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        // ارسم منحنى عن طريق تحديد كائن القلم ذي اللون الأخضر ومجموعة من النقاط
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        // ارسم شكل بيضاوي باستخدام كائن القلم والمستطيل المحيط
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //ارسم خطا 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        // ارسم مقطع دائري
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        // ارسم مضلعًا بتحديد كائن القلم ذي اللون الأحمر ومجموعة من النقاط
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        // ارسم مستطيلاً
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        // إنشاء كائن SolidBrush وضبط خصائصه المختلفة
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        // ارسم سلسلة باستخدام كائن SolidBrush والخط ، عند نقطة معينة
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // احفظ جميع التغييرات.
        image.Save();
    }
}
```

### أنظر أيضا

* class [Pen](../../pen)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

يرسم شكل دائري محدد بواسطة شكل بيضاوي محدد بواسطة زوج إحداثيات ، وعرض ، وارتفاع ، وخطين نصف قطريين.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون الشكل الدائري وعرضه ونمطه. |
| x | Int32 | إحداثي x للركن الأيسر العلوي للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه الشكل الدائري. |
| y | Int32 | إحداثي y للركن الأيسر العلوي للمستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه الشكل الدائري. |
| width | Int32 | عرض المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه الشكل الدائري. |
| height | Int32 | ارتفاع المستطيل المحيط الذي يحدد القطع الناقص الذي يأتي منه الشكل الدائري. |
| startAngle | Int32 | تقاس الزاوية بالدرجات في اتجاه عقارب الساعة من المحور x إلى الجانب الأول من الشكل الدائري. |
| sweepAngle | Int32 | تقاس الزاوية بالدرجات في اتجاه عقارب الساعة من*startAngle* معلمة إلى الجانب الثاني من شكل دائري. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* باطل. |

### أنظر أيضا

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
