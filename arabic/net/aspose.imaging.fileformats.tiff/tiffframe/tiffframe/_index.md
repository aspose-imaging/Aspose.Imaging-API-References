---
title: TiffFrame
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفTiffFrameaspose.imaging.fileformats.tiff/tiffframe فئة .
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.tiff/tiffframe/tiffframe/
---
## TiffFrame(Stream) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`TiffFrame`](../../tiffframe) فئة .

```csharp
public TiffFrame(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل صورة من وتهيئة بكسل الإطار وبيانات اللوحة باستخدام. |

### أنظر أيضا

* class [TiffFrame](../../tiffframe)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* المجسم [Aspose.Imaging](../../../)

---

## TiffFrame(Stream, TiffOptions) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`TiffFrame`](../../tiffframe) فئة .

```csharp
public TiffFrame(Stream stream, TiffOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل صورة من وتهيئة بكسل الإطار وبيانات اللوحة باستخدام. |
| options | TiffOptions | الخيارات المراد استخدامها للإطار الذي تم إنشاؤه حديثًا. |

### أنظر أيضا

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* المجسم [Aspose.Imaging](../../../)

---

## TiffFrame(string) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`TiffFrame`](../../tiffframe) فئة .

```csharp
public TiffFrame(string path)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | المسار المطلوب تحميل صورة منه وتهيئة بكسل الإطار وبيانات اللوحة به. |

### أنظر أيضا

* class [TiffFrame](../../tiffframe)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* المجسم [Aspose.Imaging](../../../)

---

## TiffFrame(string, TiffOptions) {#constructor_6}

يقوم بتهيئة مثيل جديد لملف[`TiffFrame`](../../tiffframe) فئة .

```csharp
public TiffFrame(string path, TiffOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | المسار المطلوب تحميل صورة منه وتهيئة بكسل الإطار وبيانات اللوحة به. |
| options | TiffOptions | الخيارات المراد استخدامها للإطار الذي تم إنشاؤه حديثًا. |

### أنظر أيضا

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* المجسم [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`TiffFrame`](../../tiffframe) فئة .

```csharp
public TiffFrame(RasterImage image)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة المراد تهيئة بكسل الإطار وبيانات اللوحة بها. |

### أمثلة

يوضح المثال التالي كيفية تكوين TIFF متعدد الأشكال من الصور النقطية الفردية.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // هذا هو الخط والفرشاة لرسم النص على إطارات فردية.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // إنشاء 5 إطارات
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // قم بإنشاء صورة PNG وارسم رقم الصفحة عليها.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // إنشاء إطار بناءً على صورة PNG.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // أضف الإطار إلى صورة TIFF.
        tiffImage.AddFrame(frame);
    }

    // تم إنشاء الصورة بإطار افتراضي واحد. دعونا نزيله.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // لا تنس التخلص من الإطار إذا لم تقم بإضافته إلى بعض صور TiffImage الأخرى
    activeFrame.Dispose();

    tiffImage.Save();
}
```

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffFrame](../../tiffframe)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* المجسم [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage, TiffOptions) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`TiffFrame`](../../tiffframe) فئة .

```csharp
public TiffFrame(RasterImage image, TiffOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة المراد تهيئة بكسل الإطار وبيانات اللوحة بها. |
| options | TiffOptions | الخيارات المراد استخدامها للإطار الذي تم إنشاؤه حديثًا. |

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* المجسم [Aspose.Imaging](../../../)

---

## TiffFrame(TiffOptions, int, int) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`TiffFrame`](../../tiffframe) فئة .

```csharp
public TiffFrame(TiffOptions options, int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| options | TiffOptions | خيارات الإطار. |
| width | Int32 | العرض. |
| height | Int32 | الإرتفاع. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | معلمة الخيارات خالية. |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة TIFF من البداية وحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// اضبط 8 بت لكل مكون من مكونات اللون.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// تعيين ترتيب بايت Endian الكبير (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// اضبط ضغط LZW.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// اضبط نموذج ألوان RGB.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// سيتم تخزين جميع مكونات اللون في مستوى واحد.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// قم بإنشاء إطار TIFF بحجم 100 × 100 بكسل.
// لاحظ أنه لا يتعين عليك التخلص من إطار بشكل صريح إذا تم تضمينه في TiffImage.
// عندما يتم التخلص من الحاوية ، سيتم التخلص من جميع الإطارات تلقائيًا.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// املأ الإطار بالكامل بالتدرج اللوني الأزرق والأصفر.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// إنشاء صورة TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

يوضح هذا المثال كيفية إنشاء صورة TIFF بإطارين وحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// خيارات الإطار الأول
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// اضبط 8 بت لكل مكون من مكونات اللون.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// تعيين ترتيب بايت Endian الكبير (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// اضبط ضغط LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// اضبط نموذج ألوان RGB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// سيتم تخزين جميع مكونات اللون في مستوى واحد.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// أنشئ أول إطار TIFF بحجم 100x100 بكسل.
// لاحظ أنه لا يتعين عليك التخلص من الإطارات بشكل صريح إذا تم تضمينها في TiffImage.
// عندما يتم التخلص من الحاوية ، سيتم التخلص من جميع الإطارات تلقائيًا.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// املأ الإطار الأول بالتدرج اللوني الأزرق والأصفر.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// خيارات الإطار الأول
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// ضبط 1 بت لكل بكسل لصورة B / W.
createOptions2.BitsPerSample = new ushort[] { 1 };

// تعيين ترتيب بايت Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// تعيين ضغط الفاكس CCITT Group 3.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// اضبط نموذج اللون B / W حيث يكون 0 أسود و 1 أبيض.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// أنشئ إطار TIFF الثاني بحجم 200 × 200 بكسل.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// املأ الإطار الثاني بالتدرج اللوني الأزرق والأصفر.
// سيتم تحويله تلقائيًا إلى تنسيق B / W بسبب الإعدادات المقابلة للإطار.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// إنشاء صورة TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### أنظر أيضا

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions)
* class [TiffFrame](../../tiffframe)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
