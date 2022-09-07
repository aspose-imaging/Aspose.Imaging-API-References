---
title: Clear
second_title: Aspose.Imaging لمرجع NET API
description: مسح سطح الرسومات باستخدام اللون المحدد.
type: docs
weight: 150
url: /ar/net/aspose.imaging/graphics/clear/
---
## Graphics.Clear method

مسح سطح الرسومات باستخدام اللون المحدد.

```csharp
public void Clear(Color color)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| color | Color | اللون المراد مسح سطح الرسومات به. |

### أمثلة

تستخدم هذه الأمثلة فئة GraphicsPath و Graphics لإنشاء الأشكال ومعالجتها على سطح الصورة. ينشئ المثال صورة جديدة (من النوع Tiff) ، ويمسح السطح ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية ، يتم استدعاء طريقة DrawPath المعروضة بواسطة فئة الرسومات لعرض المسارات على السطح.

```csharp
[C#]

// إنشاء مثيل لـ FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    // قم بإنشاء مثيل لـ TiffOptions وعيّن خصائصه المتنوعة
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // تعيين المصدر لمثيل ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    // إنشاء مثيل للصورة 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        // إنشاء وتهيئة مثيل لفئة الرسومات
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        // مسح سطح الرسومات
        graphics.Clear(Color.Wheat);

        // إنشاء مثيل لفئة GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        // إنشاء مثيل لفئة الشكل
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        // إضافة أشكال إلى كائن الشكل
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        // إضافة كائن الشكل إلى GraphicsPath
        graphicspath.AddFigure(figure);

        // رسم المسار باستخدام كائن القلم ذي اللون الأسود
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // احفظ جميع التغييرات.
        image.Save();
    }
}
```

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

* struct [Color](../../color)
* class [Graphics](../../graphics)
* مساحة الاسم [Aspose.Imaging](../../graphics)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
