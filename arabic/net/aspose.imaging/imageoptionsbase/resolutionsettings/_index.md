---
title: ResolutionSettings
second_title: Aspose.Imaging لمرجع NET API
description: الحصول على إعدادات الدقة أو تعيينها .
type: docs
weight: 60
url: /ar/net/aspose.imaging/imageoptionsbase/resolutionsettings/
---
## ImageOptionsBase.ResolutionSettings property

الحصول على إعدادات الدقة أو تعيينها .

```csharp
public virtual ResolutionSetting ResolutionSettings { get; set; }
```

### أمثلة

يقوم المثال التالي بتحميل صورة BMP وحفظها مرة أخرى في BMP باستخدام خيارات حفظ متنوعة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // إنشاء BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // استخدم 8 بت لكل بكسل لتقليل حجم الصورة الناتجة.
    saveOptions.BitsPerPixel = 8;

    // قم بتعيين أقرب لوحة ألوان 8 بت تغطي العدد الأقصى لوحدات البكسل للصورة ، بحيث تكون الصورة ذات لوحة الألوان
    // يكاد لا يمكن تمييزه بصريًا عن غير المنقول.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // حفظ بدون ضغط.
    // يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // اضبط الدقة الأفقية والعمودية على 96 نقطة في البوصة.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

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

يُنشئ المثال التالي صورة BMP ذات تدرج رمادي متدرج ثم يحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// حفظ في ملف
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// استخدم 8 بت لكل بكسل لتقليل حجم الصورة الناتجة.
createOptions.BitsPerPixel = 8;

// قم بتعيين لوحة الألوان القياسية ذات التدرج الرمادي 8 بت والتي تغطي جميع ألوان التدرج الرمادي.
// إذا كانت الصورة المعالجة تحتوي على ألوان ذات تدرج رمادي فقط ، فإن نسختها الملونة
// لا يمكن تمييزه بصريًا عن غير المنقول.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// حفظ بدون ضغط.
// يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// اضبط الدقة الأفقية والعمودية على 96 نقطة في البوصة.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// قم بإنشاء صورة BMP بحجم 100 × 100 بكسل واحفظها في ملف.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // املأ الصورة بتدرج الرمادي
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
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

* class [ResolutionSetting](../../resolutionsetting)
* class [ImageOptionsBase](../../imageoptionsbase)
* مساحة الاسم [Aspose.Imaging](../../imageoptionsbase)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
