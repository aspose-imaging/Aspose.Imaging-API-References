---
title: "ImageOptionsBase.ResolutionSettings"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية ImageOptionsBase. تحصل أو تعين إعدادات الدقة."
type: docs
weight: 80
url: /ar/net/aspose.imaging/imageoptionsbase/resolutionsettings/
---
## ImageOptionsBase.ResolutionSettings property

يحصل أو يضبط إعدادات الدقة.

```csharp
public virtual ResolutionSetting ResolutionSettings { get; set; }
```

## أمثلة

المثال التالي يحمل صورة BMP ويحفظها مرة أخرى كـ BMP باستخدام خيارات حفظ مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // إنشاء BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // استخدم 8 بتات لكل بكسل لتقليل حجم صورة الإخراج.
    saveOptions.BitsPerPixel = 8;

    // حدد أقرب لوحة ألوان 8‑bit التي تغطي الحد الأقصى من بكسلات الصورة، بحيث تكون الصورة مُلوَّنة بلوحة ألوان
    // تقريبًا لا يمكن تمييزها بصريًا عن صورة غير ملوّنة بلوحة ألوان.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // احفظ دون ضغط.
    // يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // حدد الدقة الأفقية والعمودية إلى 96 نقطة في البوصة.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

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

المثال التالي ينشئ صورة BMP بتدرج رمادي مُلوَّنة بلوحة ألوان ثم يحفظها إلى ملف

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// احفظ إلى ملف
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// استخدم 8 بتات لكل بكسل لتقليل حجم صورة الإخراج.
createOptions.BitsPerPixel = 8;

// حدد لوحة ألوان تدرج رمادي قياسية 8‑bit التي تغطي جميع ألوان التدرج الرمادي.
// إذا كانت الصورة المعالجة تحتوي فقط على ألوان تدرج رمادي، فإن نسختها المُلوَّنة بلوحة ألوان
// تكون غير قابلة للتمييز بصريًا عن نسخة غير مُلوَّنة بلوحة ألوان.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// احفظ دون ضغط.
// يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// حدد الدقة الأفقية والعمودية إلى 96 نقطة في البوصة.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// أنشئ صورة BMP بحجم 100 × 100 بكسل واحفظها إلى ملف
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // املأ الصورة بتدرج رمادي
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
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

* class [ResolutionSetting](../../resolutionsetting/)
* class [ImageOptionsBase](../)
* namespace [Aspose.Imaging](../../imageoptionsbase/)
* assembly [Aspose.Imaging](../../../)


