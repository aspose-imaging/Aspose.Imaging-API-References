---
title: "TiffFrame.TiffFrame"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ TiffFrame. يهيئ نسخة جديدة من فئة TiffFrame"
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.tiff/tiffframe/tiffframe/
---
## TiffFrame(Stream) {#constructor_3}

يهيئ نسخة جديدة من الفئة [`TiffFrame`](../).

```csharp
public TiffFrame(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل الصورة منه وتهيئة بكسلات الإطار وبيانات اللوحة. |

### انظر أيضًا

* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(Stream, TiffOptions) {#constructor_4}

يهيئ نسخة جديدة من الفئة [`TiffFrame`](../).

```csharp
public TiffFrame(Stream stream, TiffOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل الصورة منه وتهيئة بكسلات الإطار وبيانات اللوحة. |
| الخيارات | TiffOptions | الخيارات لاستخدامها مع الإطار الذي تم إنشاؤه حديثًا. |

### انظر أيضًا

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(string) {#constructor_5}

يهيئ نسخة جديدة من الفئة [`TiffFrame`](../).

```csharp
public TiffFrame(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل الصورة منه وتهيئة بكسلات الإطار وبيانات اللوحة. |

### انظر أيضًا

* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(string, TiffOptions) {#constructor_6}

يهيئ نسخة جديدة من الفئة [`TiffFrame`](../).

```csharp
public TiffFrame(string path, TiffOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل الصورة منه وتهيئة بكسلات الإطار وبيانات اللوحة. |
| الخيارات | TiffOptions | الخيارات لاستخدامها مع الإطار الذي تم إنشاؤه حديثًا. |

### انظر أيضًا

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage) {#constructor_1}

يهيئ نسخة جديدة من الفئة [`TiffFrame`](../).

```csharp
public TiffFrame(RasterImage image)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة المستخدمة لتهيئة بكسلات الإطار وبيانات اللوحة. |

## أمثلة

المثال التالي يوضح كيفية تجميع ملف TIFF متعدد الصفحات من صور نقطية فردية.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // هذا هو Font و Brush لرسم النص على الإطارات الفردية.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // إنشاء 5 إطارات
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // إنشاء صورة PNG ورسم رقم الصفحة عليها.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // إنشاء إطار بناءً على صورة PNG.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // إضافة الإطار إلى صورة TIFF.
        tiffImage.AddFrame(frame);
    }

    // تم إنشاء الصورة بإطار افتراضي واحد. لنقم بإزالته.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // لا تنسَ تحرير الإطار إذا لم تقم بإضافته إلى TiffImage آخر
    activeFrame.Dispose();

    tiffImage.Save();
}
```

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage, TiffOptions) {#constructor_2}

يهيئ نسخة جديدة من الفئة [`TiffFrame`](../).

```csharp
public TiffFrame(RasterImage image, TiffOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة المستخدمة لتهيئة بكسلات الإطار وبيانات اللوحة. |
| الخيارات | TiffOptions | الخيارات لاستخدامها مع الإطار الذي تم إنشاؤه حديثًا. |

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(TiffOptions, int, int) {#constructor}

يهيئ نسخة جديدة من الفئة [`TiffFrame`](../).

```csharp
public TiffFrame(TiffOptions options, int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الخيارات | TiffOptions | خيارات الإطار. |
| العرض | Int32 | العرض. |
| الارتفاع | Int32 | الارتفاع. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | معامل الخيارات هو null. |

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة TIFF من الصفر وحفظها إلى ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// حدد 8 بتات لكل مكوّن لوني.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// حدد ترتيب البايت Big Endian (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// حدد ضغط LZW.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// حدد نموذج اللون RGB.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// سيتم تخزين جميع مكونات اللون داخل مستوى واحد.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// إنشاء إطار TIFF بحجم 100x100 بكسل.
// لاحظ أنك لست مضطرًا لتفريغ الإطار صراحةً إذا تم تضمينه في TiffImage.
// عند تفريغ الحاوية سيتم تفريغ جميع الإطارات تلقائيًا.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// املأ الإطار بالكامل بالتدرج الأزرق-الأصفر.
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

يوضح هذا المثال كيفية إنشاء صورة TIFF باثنين من الإطارات وحفظها إلى ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// خيارات الإطار الأول
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// حدد 8 بتات لكل مكوّن لوني.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// حدد ترتيب البايت Big Endian (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// حدد ضغط LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// حدد نموذج اللون RGB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// سيتم تخزين جميع مكونات اللون داخل مستوى واحد.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// إنشاء الإطار الأول من TIFF بحجم 100×100 بكسل.
// لاحظ أنه لا يلزمك التخلص من الإطارات صراحةً إذا تم تضمينها في TiffImage.
// عند تفريغ الحاوية سيتم تفريغ جميع الإطارات تلقائيًا.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// ملء الإطار الأول بتدرج اللون الأزرق-الأصفر.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// خيارات الإطار الأول
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// تعيين 1 بت لكل بكسل لصورة بالأبيض والأسود.
createOptions2.BitsPerSample = new ushort[] { 1 };

// تعيين ترتيب البايت Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// تعيين ضغط الفاكس CCITT Group 3.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// تعيين نموذج ألوان الأبيض والأسود حيث 0 هو الأسود، 1 هو الأبيض.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// إنشاء الإطار الثاني من TIFF بحجم 200×200 بكسل.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// ملء الإطار الثاني بتدرج اللون الأزرق-الأصفر.
// سيتم تحويله تلقائيًا إلى تنسيق الأبيض والأسود بسبب الإعدادات المقابلة للإطار.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// إنشاء صورة TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### انظر أيضًا

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


