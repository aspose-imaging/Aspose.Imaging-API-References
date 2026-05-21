---
title: "TiffImage.TiffImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ TiffImage. إنشاء كائن جديد من فئة TiffImage مع تحديد معامل الإطار. يسهل هذا المنشئ إنشاء نسخة من TiffImage مما يسمح للمطورين بتحديد الإطار الذي سيتم تحميله أو معالجته، مما يبسط مهام التعامل مع صور Tiff داخل تطبيقاتهم."
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/tiffimage/
---
## TiffImage(TiffFrame) {#constructor}

إنشاء كائن جديد من الفئة [`TiffImage`](../)، مع تحديد معامل الإطار. يسهل هذا المنشئ إنشاء نسخة من TiffImage، مما يسمح للمطورين بتحديد الإطار الذي سيتم تحميله أو معالجته، مما يبسط مهام التعامل مع صور Tiff داخل تطبيقاتهم.

```csharp
public TiffImage(TiffFrame frame)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| إطار | TiffFrame | إطار TIFF لتهيئة الصورة به. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | إطار *frame* في Tiff لا يمكن أن يكون فارغًا. |

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

### انظر أيضًا

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)

---

## TiffImage(TiffFrame[]) {#constructor_1}

إنشاء نسخة جديدة من الفئة [`TiffImage`](../)، مع توفير قائمة بالإطارات كمعامل. يتيح هذا المنشئ تهيئة كائن TiffImage بعدة إطارات، مما يسهل التعامل الفعال ومعالجة تسلسلات صور TIFF داخل تطبيقات البرمجيات.

```csharp
public TiffImage(TiffFrame[] frames)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| إطارات | TiffFrame[] | الإطارات. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | إطارات |

## أمثلة

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

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


