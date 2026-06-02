---
title: "TiffOptions.PlanarConfiguration"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TiffOptions. تحصل أو تعين تكوين المستوى"
type: docs
weight: 360
url: /ar/net/aspose.imaging.imageoptions/tiffoptions/planarconfiguration/
---
## TiffOptions.PlanarConfiguration property

الحصول أو تعيين تكوين المستوى.

```csharp
public TiffPlanarConfigs PlanarConfiguration { get; set; }
```

### Property Value

التكوين المستوي.

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

* enum [TiffPlanarConfigs](../../../aspose.imaging.fileformats.tiff.enums/tiffplanarconfigs/)
* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)


