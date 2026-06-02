---
title: "JpegOptions.ColorType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية JpegOptions. يحصل أو يضبط نوع اللون لصورة jpeg"
type: docs
weight: 40
url: /ar/net/aspose.imaging.imageoptions/jpegoptions/colortype/
---
## JpegOptions.ColorType property

يحصل أو يضبط نوع اللون لصورة JPEG.

```csharp
public JpegCompressionColorMode ColorType { get; set; }
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

المثال التالي يقوم بتحميل PNG ويحفظه كـ CMYK JPEG باستخدام ملف ICC مخصص. ثم يقوم بتحميل CMYK JPEG ويحفظه مرة أخرى كـ PNG. يتم إجراء تحويل اللون من RGB إلى CMYK ومن CMYK إلى RGB باستخدام ملفات ICC مخصصة.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل PNG واحفظه كـ CMYK JPEG
using (Aspose.Imaging.FileFormats.Png.PngImage image = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Load(dir + "sample.png"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();
        saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Cmyk;

        // استخدم ملفات ICC مخصصة
        saveOptions.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        saveOptions.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        image.Save(dir + "output.cmyk.jpg", saveOptions);
    }
}

// حمّل CMYK JPEG واحفظه كـ PNG
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "output.cmyk.jpg"))
{
    using (System.IO.Stream rgbProfileStream = System.IO.File.OpenRead(dir + "eciRGB_v2.icc"))
    using (System.IO.Stream cmykProfileStream = System.IO.File.OpenRead(dir + "ISOcoated_v2_FullGamut4.icc"))
    {
        // استخدم ملفات ICC مخصصة
        image.RgbColorProfile = new Aspose.Imaging.Sources.StreamSource(rgbProfileStream);
        image.CmykColorProfile = new Aspose.Imaging.Sources.StreamSource(cmykProfileStream);

        Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        image.Save(dir + "output.rgb.png", saveOptions);
    }
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

* enum [JpegCompressionColorMode](../../../aspose.imaging.fileformats.jpeg/jpegcompressioncolormode/)
* class [JpegOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../jpegoptions/)
* assembly [Aspose.Imaging](../../../)


