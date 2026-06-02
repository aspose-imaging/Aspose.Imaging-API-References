---
title: "JpegImage.JpegImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ JpegImage. يبدأ فئة JpegImage بسهولة عن طريق استدعاء منشئها مع معامل المسار المحدد. يتيح هذا المنشئ إنشاء صور JPEG بسلاسة، مما يضمن دمجًا سريعًا في مشاريعك بسهولة."
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegimage/
---
## JpegImage(string) {#constructor_4}

الفئة [`JpegImage`](../) تبدأ بسهولة عن طريق استدعاء منشئها مع معامل المسار المحدد. يتيح هذا المنشئ إنشاء صور JPEG بسلاسة، مما يضمن دمجًا سريعًا في مشاريعك بسهولة.

```csharp
public JpegImage(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

## أمثلة

يوضح المثال كيفية تحميل كائن JpegImage من ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة JPEG من ملف.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // قم ببعض معالجة الصورة.
    // احفظ إلى ملف JPEG آخر.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### انظر أيضًا

* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)

---

## JpegImage(Stream) {#constructor_3}

قم بتهيئة كائن صورة JPEG باستخدام الفئة [`JpegImage`](../) مع معامل تدفق. يبسط هذا المنشئ عملية العمل مع صور JPEG، مقدماً نهجًا مباشرًا لدمجها في مشاريعك بسهولة.

```csharp
public JpegImage(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

## أمثلة

المثال يوضح كيفية تحميل JpegImage من تدفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة JPEG من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jpg"))
{
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(stream))
    {
        // قم ببعض معالجة الصورة.
        // احفظ إلى ملف JPEG آخر.
        jpegImage.Save(dir + "sample.output.jpg");
    }
}
```

### انظر أيضًا

* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)

---

## JpegImage(RasterImage) {#constructor_1}

قم بتهيئة نسخة جديدة من الفئة [`JpegImage`](../) باستخدام معامل صورة نقطية. يوفر هذا المنشئ طريقة مريحة لإنشاء صور JPEG مباشرةً من الصور النقطية، مما يبسط سير العمل عند التعامل مع صور JPEG في تطبيقاتك.

```csharp
public JpegImage(RasterImage rasterImage)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة لتهيئة بيانات البكسل ولوحة الألوان بها. |

## أمثلة

يوضح المثال كيفية تحميل JpegImage من RasterImage أخرى.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة JPEG من صورة نقطية أخرى.
// أولاً، أنشئ صورة PNG مؤقتة ستكون أساسًا لإنشاء صورة JPEG.
// يمكنك أيضًا تحميل صورة PNG من ملف أو استخدام صورة بأي تنسيق نقطي آخر.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), false);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // املأ صورة PNG بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, rasterImage.Bounds);

    // أنشئ صورة JPEG بناءً على صورة PNG.
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(rasterImage))
    {
        // احفظ إلى ملف JPEG
        jpegImage.Save(dir + "output.jpg");
    }
}
```

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)

---

## JpegImage(int, int) {#constructor_2}

أنشئ نسخة جديدة من الفئة [`JpegImage`](../) بالعرض والارتفاع المحددين. يتيح لك هذا المُنشئ إنشاء صور JPEG بأبعاد مخصصة، مما يمنحك مرونة في إدارة أحجام الصور في تطبيقك.

```csharp
public JpegImage(int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |

## أمثلة

يوضح المثال التالي كيفية إنشاء صورة JPEG بالحجم المحدد.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة JPEG بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(100, 100))
{
    // قم ببعض معالجة الصورة.
    // احفظ إلى ملف.
    jpegImage.Save(dir + "output.jpg");
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

### انظر أيضًا

* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)

---

## JpegImage(JpegOptions, int, int) {#constructor}

ابدأ كائنًا جديدًا من [`JpegImage`](../) باستخدام خيارات JPEG المقدمة. يتيح لك هذا المُنشئ تخصيص إعدادات مختلفة لصورة JPEG، مثل مستوى الضغط والجودة والمعلمات الإضافية، مما يمنحك تحكمًا دقيقًا في تنسيق الصورة الناتج.

```csharp
public JpegImage(JpegOptions jpegOptions, int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| jpegOptions | JpegOptions | خيارات JPEG. |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |

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

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions/)
* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


