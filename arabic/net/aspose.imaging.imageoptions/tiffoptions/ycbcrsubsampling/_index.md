---
title: "TiffOptions.YCbCrSubsampling"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TiffOptions. تحصل أو تعين عوامل التقسيم الفرعي للقياس الضوئي YCbCr"
type: docs
weight: 700
url: /ar/net/aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling/
---
## TiffOptions.YCbCrSubsampling property

يحصل أو يضبط عوامل أخذ العينات الفرعية للقياس الضوئي YCbCr.

```csharp
public ushort[] YCbCrSubsampling { get; set; }
```

### Property Value

عوامل التقسيم الفرعي للقياس الضوئي YCbCr.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [TiffImageException](../../../aspose.imaging.coreexceptions.imageformats/tiffimageexception/) | طول الحقل غير صالح. يجب أن يحتوي حقل YCbCrSubsampling على قيمتين. |
| ArgumentNullException | قيمة |

## أمثلة

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

* class [TiffOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../tiffoptions/)
* assembly [Aspose.Imaging](../../../)


