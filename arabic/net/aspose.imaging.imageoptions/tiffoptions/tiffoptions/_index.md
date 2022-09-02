---
title: TiffOptions
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفTiffOptionsaspose.imaging.imageoptions/tiffoptions فئة .
type: docs
weight: 10
url: /ar/net/aspose.imaging.imageoptions/tiffoptions/tiffoptions/
---
## TiffOptions(TiffExpectedFormat, TiffByteOrder) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`TiffOptions`](../../tiffoptions) فئة .

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat, TiffByteOrder byteOrder)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | تنسيق ملف tiff المتوقع. |
| byteOrder | TiffByteOrder | ترتيب بايت تنسيق ملف tiff للاستخدام. |

### أنظر أيضا

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder)
* class [TiffOptions](../../tiffoptions)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../tiffoptions)
* المجسم [Aspose.Imaging](../../../)

---

## TiffOptions(TiffExpectedFormat) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`TiffOptions`](../../tiffoptions)صف دراسي. بشكل افتراضي ، يتم استخدام اصطلاح Endian الصغير.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | تنسيق ملف tiff المتوقع. |

### أمثلة

يوضح المثال التالي كيفية إنشاء نسخة بتدرج الرمادي لإطار موجود وإضافته إلى صورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// إنشاء مصدر ملف دائم وليس مؤقتًا.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // التدرج الخطي من الزاوية اليسرى العلوية إلى الزاوية اليمنى السفلية للصورة.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // املأ الإطار النشط بفرشاة متدرجة خطية.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // خيارات تدرج الرمادي
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // إنشاء نسخة بتدرج الرمادي من الإطار النشط.
    // يتم الاحتفاظ ببيانات البكسل ولكن يتم تحويلها إلى التنسيق المطلوب.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // أضف الإطار الذي تم إنشاؤه حديثًا إلى صورة TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

يوضح هذا المثال كيفية حفظ صورة نقطية بتنسيق TIFF باستخدام خيارات متنوعة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// اضبط 8 بت لكل مكون من مكونات اللون.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// تعيين ترتيب بايت Endian الكبير (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// اضبط ضغط LZW.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// السماح بتقليل حجم الصور ذات الدرجة اللونية المستمرة.
// حاليًا يُستخدم هذا الحقل فقط مع ترميز LZW لأن LZW ربما يكون مخطط ترميز TIFF الوحيد
// التي تستفيد بشكل كبير من خطوة التنبؤ.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// اضبط نموذج ألوان RGB.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// بالنسبة إلى YCbCr ، يمكنك استخدام أحد الخيارات التالية:
// YCbCrSubSubSampling Field عوامل أخذ عينات JPEG
// ----------------------------------------------
// 1،1 1x1، 1x1، 1x1
// 2،1 2x1، 1x1، 1x1
// 2،2 (القيمة الافتراضية) 2x2، 1x1، 1x1
// saveOptions.YCbCrSubsampling = new ushort [] {2، 2};

// سيتم تخزين جميع مكونات اللون داخل مستوى واحد.
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// قم بإنشاء إطار TIFF بحجم 100 × 100 بكسل.
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // املأ الصورة بأكملها بالتدرج اللوني الأزرق والأصفر.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(image.Width, image.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save(dir + "output.tif", saveOptions);
}
```

### أنظر أيضا

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat)
* class [TiffOptions](../../tiffoptions)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../tiffoptions)
* المجسم [Aspose.Imaging](../../../)

---

## TiffOptions(TiffOptions) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`TiffOptions`](../../tiffoptions) فئة .

```csharp
public TiffOptions(TiffOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| options | TiffOptions | خيارات النسخ من. |

### أنظر أيضا

* class [TiffOptions](../../tiffoptions)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../tiffoptions)
* المجسم [Aspose.Imaging](../../../)

---

## TiffOptions(TiffDataType[]) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`TiffOptions`](../../tiffoptions) فئة .

```csharp
public TiffOptions(TiffDataType[] tags)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| tags | TiffDataType[] | العلامات المراد تهيئة الخيارات بها. |

### أنظر أيضا

* class [TiffDataType](../../../aspose.imaging.fileformats.tiff/tiffdatatype)
* class [TiffOptions](../../tiffoptions)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../tiffoptions)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
