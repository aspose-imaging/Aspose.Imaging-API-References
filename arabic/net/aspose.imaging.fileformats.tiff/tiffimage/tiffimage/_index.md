---
title: TiffImage
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفTiffImageaspose.imaging.fileformats.tiff/tiffimage فئة .
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/tiffimage/
---
## TiffImage(TiffFrame) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`TiffImage`](../../tiffimage) فئة .

```csharp
public TiffImage(TiffFrame frame)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| frame | TiffFrame | إطار tiff لتهيئة الصورة به. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | لا يمكن أن يكون إطار Tiff فارغًا. ؛ إطار |

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

### أنظر أيضا

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* المجسم [Aspose.Imaging](../../../)

---

## TiffImage(TiffFrame[]) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`TiffImage`](../../tiffimage) فئة .

```csharp
public TiffImage(TiffFrame[] frames)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| frames | TiffFrame[] | الإطارات. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | الإطارات |

### أمثلة

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

* class [TiffFrame](../../tiffframe)
* class [TiffImage](../../tiffimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
