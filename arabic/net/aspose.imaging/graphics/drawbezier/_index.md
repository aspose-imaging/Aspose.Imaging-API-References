---
title: DrawBezier
second_title: Aspose.Imaging لمرجع NET API
description: يرسم شريحة بيزير محددة بأربعة أزواج مرتبة من الإحداثيات التي تمثل النقاط.
type: docs
weight: 170
url: /ar/net/aspose.imaging/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

يرسم شريحة بيزير محددة بأربعة أزواج مرتبة من الإحداثيات التي تمثل النقاط.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون وعرض وأسلوب المنحنى. |
| x1 | Single | إحداثي x لنقطة بداية المنحنى. |
| y1 | Single | إحداثي y لنقطة بداية المنحنى. |
| x2 | Single | إحداثي x لنقطة التحكم الأولى في المنحنى. |
| y2 | Single | إحداثي y لنقطة التحكم الأولى في المنحنى. |
| x3 | Single | الإحداثي x لنقطة التحكم الثانية للمنحنى. |
| y3 | Single | الإحداثي y لنقطة التحكم الثانية للمنحنى. |
| x4 | Single | إحداثي x لنقطة نهاية المنحنى. |
| y4 | Single | إحداثي y لنقطة نهاية المنحنى. |

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

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

يرسم شريحة بيزير محددة بأربعة[`PointF`](../../pointf) الهياكل .

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) التي تحدد لون وعرض وأسلوب المنحنى. |
| pt1 | PointF | [`PointF`](../../pointf) الهيكل الذي يمثل نقطة البداية للمنحنى. |
| pt2 | PointF | [`PointF`](../../pointf) الهيكل الذي يمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | PointF | [`PointF`](../../pointf) الهيكل الذي يمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | PointF | [`PointF`](../../pointf) الهيكل الذي يمثل نقطة نهاية المنحنى. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *pen* باطل. |

### أنظر أيضا

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

يرسم شريحة بيزير محددة بأربعة[`Point`](../../point) الهياكل .

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) الهيكل الذي يحدد لون وعرض وأسلوب المنحنى. |
| pt1 | Point | [`Point`](../../point) الهيكل الذي يمثل نقطة البداية للمنحنى. |
| pt2 | Point | [`Point`](../../point) الهيكل الذي يمثل نقطة التحكم الأولى للمنحنى. |
| pt3 | Point | [`Point`](../../point) الهيكل الذي يمثل نقطة التحكم الثانية للمنحنى. |
| pt4 | Point | [`Point`](../../point) الهيكل الذي يمثل نقطة نهاية المنحنى. |

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
* struct [Point](../../point)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
