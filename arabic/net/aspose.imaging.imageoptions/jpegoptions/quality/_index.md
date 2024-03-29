---
title: Quality
second_title: Aspose.Imaging لمرجع NET API
description: الحصول على جودة الصورة أو تعيينها .
type: docs
weight: 140
url: /ar/net/aspose.imaging.imageoptions/jpegoptions/quality/
---
## JpegOptions.Quality property

الحصول على جودة الصورة أو تعيينها .

```csharp
public int Quality { get; set; }
```

### أمثلة

يقوم المثال التالي بتحميل صورة BMP وحفظها في JPEG باستخدام خيارات حفظ متنوعة.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة BMP من ملف.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // قم ببعض معالجة الصور.

    // استخدم خيارات إضافية لتحديد معلمات الصورة المطلوبة.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // عدد البتات لكل قناة هو 8.
    // عند استخدام لوحة ، يتم تخزين فهرس اللون في بيانات الصورة بدلاً من اللون نفسه.
    saveOptions.BitsPerChannel = 8;

    // ضبط النوع التدريجي للضغط.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // ضبط جودة الصورة. إنها قيمة بين 1 و 100.
    saveOptions.Quality = 100;

    // اضبط الدقة الأفقية / الرأسية على 96 نقطة في البوصة.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // إذا كانت الصورة المصدر ملونة ، فسيتم تحويلها إلى تدرج الرمادي.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // استخدم لوحة لتقليل حجم الإخراج.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

يوضح المثال التالي كيفية إنشاء صورة JPEG بالحجم المحدد باستخدام المعلمات المحددة.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بإنشاء صورة JPEG بحجم 100 × 100 بكسل.
// استخدم خيارات إضافية لتحديد معلمات الصورة المطلوبة.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// عدد البتات لكل قناة هو 8 ، 8 ، 8 لمكونات Y و Cr و Cb وفقًا لذلك.
createOptions.BitsPerChannel = 8;

// ضبط النوع التدريجي للضغط.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// ضبط جودة الصورة. إنها قيمة بين 1 و 100.
createOptions.Quality = 100;

// اضبط الدقة الأفقية / الرأسية على 96 نقطة في البوصة.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// هذا خيار قياسي لصور JPEG.
// يمكن اختزال مكونين من مكونات الصفاء (Cb و Cr) من عرض النطاق الترددي ، وتقسيم عيناتهما ، وضغطهما.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // املأ الصورة بتدرج الرمادي
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // حفظ في ملف.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### أنظر أيضا

* class [JpegOptions](../../jpegoptions)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../jpegoptions)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
