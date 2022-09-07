---
title: DrawCurve
second_title: Aspose.Imaging لمرجع NET API
description: يرسم العمود الفقري الأساسي من خلال مصفوفة محددة منPointFaspose.imaging/pointf الهياكل. تستخدم هذه الطريقة معدل توتر افتراضي 0.5 .
type: docs
weight: 200
url: /ar/net/aspose.imaging/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../../pointf) الهياكل. تستخدم هذه الطريقة معدل توتر افتراضي 0.5 .

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | PointF[] | مصفوفة من[`PointF`](../../pointf) الهياكل التي تحدد الشريحة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../../pointf) الهياكل باستخدام التوتر المحدد.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | PointF[] | مصفوفة من[`PointF`](../../pointf) الهياكل التي تمثل النقاط التي تحدد المنحنى. |
| tension | Single | القيمة أكبر من أو تساوي 0.0F التي تحدد شد المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../../pointf) الهياكل. يبدأ الرسم في الإزاحة من بداية المصفوفة . تستخدم هذه الطريقة شد افتراضي 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | PointF[] | مصفوفة من[`PointF`](../../pointf) الهياكل التي تحدد الشريحة. |
| offset | Int32 | الإزاحة من العنصر الأول في مصفوفة*points* المعلمة إلى نقطة البداية في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع بعد نقطة البداية لتضمينها في المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`PointF`](../../pointf)الهياكل التي تستخدم توترًا محددًا. يبدأ الرسم في الإزاحة من بداية المصفوفة.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | PointF[] | مصفوفة من[`PointF`](../../pointf) الهياكل التي تحدد الشريحة. |
| offset | Int32 | الإزاحة من العنصر الأول في مصفوفة*points* المعلمة إلى نقطة البداية في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع بعد نقطة البداية لتضمينها في المنحنى. |
| tension | Single | القيمة أكبر من أو تساوي 0.0F التي تحدد شد المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`Point`](../../point) الهياكل .

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | Point[] | مصفوفة من[`Point`](../../point) الهياكل التي تحدد الشريحة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

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
* struct [Point](../../point)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`Point`](../../point) الهياكل باستخدام التوتر المحدد.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | Point[] | مصفوفة من[`Point`](../../point) الهياكل التي تحدد الشريحة. |
| tension | Single | القيمة أكبر من أو تساوي 0.0F التي تحدد شد المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

يرسم العمود الفقري الأساسي من خلال مصفوفة محددة من[`Point`](../../point) الهياكل باستخدام التوتر المحدد.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون وعرض وارتفاع المنحنى. |
| points | Point[] | مصفوفة من[`Point`](../../point) الهياكل التي تحدد الشريحة. |
| offset | Int32 | الإزاحة من العنصر الأول في مصفوفة*points* المعلمة إلى نقطة البداية في المنحنى. |
| numberOfSegments | Int32 | عدد المقاطع بعد نقطة البداية لتضمينها في المنحنى. |
| tension | Single | القيمة أكبر من أو تساوي 0.0F التي تحدد شد المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* فارغ. -أو *points* باطل. |

### أنظر أيضا

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
