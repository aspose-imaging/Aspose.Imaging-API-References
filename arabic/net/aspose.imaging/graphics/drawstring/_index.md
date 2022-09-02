---
title: DrawString
second_title: Aspose.Imaging لمرجع NET API
description: رسم السلسلة النصية المحددة بالموقع المحددBrushaspose.imaging/brush وFontaspose.imaging/font الكائنات .
type: docs
weight: 320
url: /ar/net/aspose.imaging/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../../brush) و[`Font`](../../font) الكائنات .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| s | String | سلسلة للرسم. |
| font | Font | [`Font`](../../font) التي تحدد تنسيق النص للسلسلة. |
| brush | Brush | [`Brush`](../../brush) التي تحدد لون وملمس النص المرسوم. |
| x | Single | إحداثي x للركن الأيسر العلوي للنص المرسوم. |
| y | Single | إحداثي ص للركن الأيسر العلوي للنص المرسوم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو *s* باطل. |

### أنظر أيضا

* class [Font](../../font)
* class [Brush](../../brush)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../../brush) و[`Font`](../../font) الكائنات .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| s | String | سلسلة للرسم. |
| font | Font | [`Font`](../../font) التي تحدد تنسيق النص للسلسلة. |
| brush | Brush | [`Brush`](../../brush) التي تحدد لون وملمس النص المرسوم. |
| point | PointF | [`PointF`](../../pointf) هيكل يحدد الزاوية العلوية اليسرى للنص المرسوم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو *s* باطل. |

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

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../../brush) و[`Font`](../../font) كائنات باستخدام سمات التنسيق المحددة[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| s | String | سلسلة للرسم. |
| font | Font | [`Font`](../../font) التي تحدد تنسيق النص للسلسلة. |
| brush | Brush | [`Brush`](../../brush) التي تحدد لون وملمس النص المرسوم. |
| x | Single | إحداثي x للركن الأيسر العلوي للنص المرسوم. |
| y | Single | إحداثي ص للركن الأيسر العلوي للنص المرسوم. |
| format | StringFormat | [`StringFormat`](../../stringformat) يحدد سمات التنسيق ، مثل تباعد الأسطر والمحاذاة ، التي يتم تطبيقها على النص المرسوم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو *s* باطل. |

### أنظر أيضا

* class [Font](../../font)
* class [Brush](../../brush)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

رسم السلسلة النصية المحددة بالموقع المحدد[`Brush`](../../brush) و[`Font`](../../font) كائنات باستخدام سمات التنسيق المحددة[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| s | String | سلسلة للرسم. |
| font | Font | [`Font`](../../font) التي تحدد تنسيق النص للسلسلة. |
| brush | Brush | [`Brush`](../../brush) التي تحدد لون وملمس النص المرسوم. |
| point | PointF | [`PointF`](../../pointf) هيكل يحدد الزاوية العلوية اليسرى للنص المرسوم. |
| format | StringFormat | [`StringFormat`](../../stringformat) يحدد سمات التنسيق ، مثل تباعد الأسطر والمحاذاة ، التي يتم تطبيقها على النص المرسوم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو *s* باطل. |

### أنظر أيضا

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

رسم السلسلة النصية المحددة في المستطيل المحدد بالقيمة المحددة[`Brush`](../../brush) و[`Font`](../../font) الكائنات .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| s | String | سلسلة للرسم. |
| font | Font | [`Font`](../../font) التي تحدد تنسيق النص للسلسلة. |
| brush | Brush | [`Brush`](../../brush) التي تحدد لون وملمس النص المرسوم. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) الهيكل الذي يحدد موقع النص المرسوم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو *s* باطل. |

### أنظر أيضا

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

رسم السلسلة النصية المحددة في المستطيل المحدد بالقيمة المحددة[`Brush`](../../brush) و[`Font`](../../font) كائنات باستخدام سمات التنسيق المحددة[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| s | String | سلسلة للرسم. |
| font | Font | [`Font`](../../font) التي تحدد تنسيق النص للسلسلة. |
| brush | Brush | [`Brush`](../../brush) التي تحدد لون وملمس النص المرسوم. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) الهيكل الذي يحدد موقع النص المرسوم. |
| format | StringFormat | [`StringFormat`](../../stringformat) يحدد سمات التنسيق ، مثل تباعد الأسطر والمحاذاة ، التي يتم تطبيقها على النص المرسوم. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | *brush* فارغ. -أو *s* فارغ. -أو *brush* باطل. |

### أنظر أيضا

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
