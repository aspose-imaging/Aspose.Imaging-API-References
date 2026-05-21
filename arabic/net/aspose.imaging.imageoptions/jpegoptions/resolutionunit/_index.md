---
title: "JpegOptions.ResolutionUnit"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية JpegOptions. يحصل أو يعيّن وحدة الدقة"
type: docs
weight: 160
url: /ar/net/aspose.imaging.imageoptions/jpegoptions/resolutionunit/
---
## JpegOptions.ResolutionUnit property

الحصول أو تعيين وحدة الدقة.

```csharp
public ResolutionUnit ResolutionUnit { get; set; }
```

## أمثلة

المثال التالي يحمل صورة BMP ويحفظها كـ JPEG باستخدام خيارات حفظ مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة BMP من ملف.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // قم ببعض معالجة الصورة.

    // استخدم خيارات إضافية لتحديد معلمات الصورة المطلوبة.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // عدد البتات لكل قناة هو 8.
    // عند استخدام لوحة ألوان، يتم تخزين فهرس اللون في بيانات الصورة بدلاً من اللون نفسه.
    saveOptions.BitsPerChannel = 8;

    // حدد نوع الضغط المتدرج.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // حدد جودة الصورة. إنها قيمة بين 1 و 100.
    saveOptions.Quality = 100;

    // حدد الدقة الأفقية/العمودية إلى 96 نقطة في البوصة.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // إذا كانت الصورة الأصلية ملونة، فسيتم تحويلها إلى تدرج رمادي.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // استخدم لوحة ألوان لتقليل حجم الناتج.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

المثال التالي يوضح كيفية إنشاء صورة JPEG بالحجم المحدد باستخدام المعلمات المحددة.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة JPEG بحجم 100×100 بكسل.
// استخدم خيارات إضافية لتحديد معلمات الصورة المطلوبة.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// عدد البتات لكل قناة هو 8، 8، 8 للمكونات Y و Cr و Cb على التوالي.
createOptions.BitsPerChannel = 8;

// حدد نوع الضغط المتدرج.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// حدد جودة الصورة. إنها قيمة بين 1 و 100.
createOptions.Quality = 100;

// حدد الدقة الأفقية/العمودية إلى 96 نقطة في البوصة.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// هذا خيار قياسي لصور JPEG.
// يمكن تقليل عرض النطاق، أخذ عينات فرعية، وضغط مكوّنَي اللون (Cb و Cr).
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // املأ الصورة بتدرج رمادي
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // احفظ إلى ملف.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### انظر أيضًا

* enum [ResolutionUnit](../../../aspose.imaging/resolutionunit/)
* class [JpegOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../jpegoptions/)
* assembly [Aspose.Imaging](../../../)


