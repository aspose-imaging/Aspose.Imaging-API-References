---
title: JpegImage
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفJpegImageaspose.imaging.fileformats.jpeg/jpegimage فئة .
type: docs
weight: 10
url: /ar/aspose.imaging.fileformats.jpeg/jpegimage/jpegimage/
---
## JpegImage(string) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`JpegImage`](../../jpegimage) فئة .

```csharp
public JpegImage(string path)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | مسار تحميل الصورة منه وتهيئة بيانات البكسل واللوحة باستخدام . |

### أمثلة

يوضح المثال كيفية تحميل JpegImage من ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بتحميل صورة JPEG من ملف.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // قم ببعض معالجة الصور.
    // حفظ في ملف JPEG آخر.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### أنظر أيضا

* class [JpegImage](../../jpegimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* المجسم [Aspose.Imaging](../../../)

---

## JpegImage(Stream) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`JpegImage`](../../jpegimage) فئة .

```csharp
public JpegImage(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة باستخدام . |

### أمثلة

يوضح المثال كيفية تحميل JpegImage من تدفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة JPEG من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jpg"))
{
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(stream))
    {
        // قم ببعض معالجة الصور.
        // حفظ في ملف JPEG آخر.
        jpegImage.Save(dir + "sample.output.jpg");
    }
}
```

### أنظر أيضا

* class [JpegImage](../../jpegimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* المجسم [Aspose.Imaging](../../../)

---

## JpegImage(RasterImage) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`JpegImage`](../../jpegimage) فئة .

```csharp
public JpegImage(RasterImage rasterImage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة المطلوب تهيئة بيانات البكسل واللوحة باستخدام . |

### أمثلة

يوضح المثال كيفية تحميل JpegImage من RasterImage آخر.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بتحميل صورة JPEG من صورة نقطية أخرى.
// أولاً ، قم بإنشاء صورة PNG مؤقتة والتي ستكون أساسًا لبناء صورة JPEG.
// يمكنك أيضًا تحميل صورة PNG من ملف أو استخدام صورة بأي تنسيق نقطي آخر.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), false);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // املأ صورة PNG بأكملها باللون الأحمر.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, rasterImage.Bounds);

    // قم بإنشاء صورة JPEG بناءً على صورة PNG.
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(rasterImage))
    {
        // حفظ في ملف JPEG
        jpegImage.Save(dir + "output.jpg");
    }
}
```

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [JpegImage](../../jpegimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* المجسم [Aspose.Imaging](../../../)

---

## JpegImage(int, int) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`JpegImage`](../../jpegimage) فئة .

```csharp
public JpegImage(int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | عرض الصورة . |
| height | Int32 | ارتفاع الصورة . |

### أمثلة

يوضح المثال التالي كيفية إنشاء صورة JPEG بالحجم المحدد.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بإنشاء صورة JPEG بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(100, 100))
{
    // قم ببعض معالجة الصور.
    // حفظ في ملف.
    jpegImage.Save(dir + "output.jpg");
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

### أنظر أيضا

* class [JpegImage](../../jpegimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* المجسم [Aspose.Imaging](../../../)

---

## JpegImage(JpegOptions, int, int) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`JpegImage`](../../jpegimage) فئة .

```csharp
public JpegImage(JpegOptions jpegOptions, int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| jpegOptions | JpegOptions | خيارات jpeg . |
| width | Int32 | عرض الصورة . |
| height | Int32 | ارتفاع الصورة . |

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

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
