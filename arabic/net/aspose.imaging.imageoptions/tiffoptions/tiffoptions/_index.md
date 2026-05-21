---
title: "TiffOptions.TiffOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ TiffOptions. يهيئ نسخة جديدة من فئة TiffOptions"
type: docs
weight: 10
url: /ar/net/aspose.imaging.imageoptions/tiffoptions/tiffoptions/
---
## TiffOptions(TiffExpectedFormat, TiffByteOrder) {#constructor_1}

يهيئ نسخة جديدة من الفئة [`TiffOptions`](../).

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat, TiffByteOrder byteOrder)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | تنسيق ملف TIFF المتوقع. |
| byteOrder | TiffByteOrder | ترتيب البايت لتنسيق ملف TIFF الذي سيتم استخدامه. |

### انظر أيضًا

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/)
* enum [TiffByteOrder](../../../aspose.imaging.fileformats.tiff.enums/tiffbyteorder/)
* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)

---

## TiffOptions(TiffExpectedFormat) {#constructor}

يقوم بتهيئة نسخة جديدة من الفئة [`TiffOptions`](../). بشكل افتراضي يتم استخدام نظام little endian.

```csharp
public TiffOptions(TiffExpectedFormat expectedFormat)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| expectedFormat | TiffExpectedFormat | تنسيق ملف TIFF المتوقع. |

## أمثلة

المثال التالي يوضح كيفية إنشاء نسخة بالأبيض والأسود من إطار موجود وإضافتها إلى صورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// إنشاء مصدر ملف دائم، وليس مؤقت.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // التدرج الخطي من الزاوية اليسرى العليا إلى الزاوية اليمنى السفلى للصورة.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // ملء الإطار النشط بفرشاة تدرج خطي.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // خيارات التدرج الرمادي
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // إنشاء نسخة تدرج رمادي من الإطار النشط.
    // يتم الحفاظ على بيانات البكسل ولكن يتم تحويلها إلى الصيغة المطلوبة.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // إضافة الإطار الذي تم إنشاؤه حديثًا إلى صورة TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

يوضح هذا المثال كيفية حفظ صورة نقطية إلى تنسيق TIFF باستخدام خيارات مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// حدد 8 بتات لكل مكوّن لوني.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// حدد ترتيب البايت Big Endian (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// حدد ضغط LZW.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// يسمح بتقليل حجم الصور ذات النغمات المستمرة.
// حاليًا يتم استخدام هذا الحقل فقط مع ترميز LZW لأن LZW ربما يكون نظام الترميز الوحيد لتنسيق TIFF
// الذي يستفيد بشكل كبير من خطوة التنبؤ.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// حدد نموذج اللون RGB.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// بالنسبة إلى YCbCr، يمكنك استخدام أحد الخيارات التالية:
// حقل YCbCrSubSampling   عوامل أخذ عينات JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// سيتم تخزين جميع مكونات اللون داخل مستوى واحد.
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// إنشاء إطار TIFF بحجم 100x100 بكسل.
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // املأ الصورة بالكامل بالتدرج الأزرق-الأصفر.
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

### انظر أيضًا

* enum [TiffExpectedFormat](../../../aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/)
* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)

---

## TiffOptions(TiffOptions) {#constructor_3}

يهيئ نسخة جديدة من الفئة [`TiffOptions`](../).

```csharp
public TiffOptions(TiffOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الخيارات | TiffOptions | الخيارات للنسخ منها. |

### انظر أيضًا

* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)

---

## TiffOptions(TiffDataType[]) {#constructor_2}

يهيئ نسخة جديدة من الفئة [`TiffOptions`](../).

```csharp
public TiffOptions(TiffDataType[] tags)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| tags | TiffDataType[] | العلامات لتهيئة الخيارات بها. |

### انظر أيضًا

* class [TiffDataType](../../../aspose.imaging.fileformats.tiff/tiffdatatype/)
* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)


