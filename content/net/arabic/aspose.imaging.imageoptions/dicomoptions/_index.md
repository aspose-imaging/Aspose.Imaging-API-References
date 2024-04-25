---
title: DicomOptions
second_title: Aspose.Imaging لمرجع NET API
description: خيارات إنشاء تنسيق ملف DICOM .
type: docs
weight: 9940
url: /ar/aspose.imaging.imageoptions/dicomoptions/
---
## DicomOptions class

خيارات إنشاء تنسيق ملف DICOM .

```csharp
public class DicomOptions : ImageOptionsBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [DicomOptions](dicomoptions)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [ColorType](../../aspose.imaging.imageoptions/dicomoptions/colortype) { get; set; } | الحصول على أو تحديد نوع اللون. |
| [Compression](../../aspose.imaging.imageoptions/dicomoptions/compression) { get; set; } | الحصول على الضغط أو تعيينه . |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [إطار كامل] . |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | خيارات متعدد الصفحات |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها . |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | الحصول على معالج حدث التقدم أو تعيينه. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | الحصول على إعدادات الدقة أو تعيينها . |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | الحصول على أو تعيين المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | الحصول على أو تعيين خيارات التحويل النقطي للمتجه. |
| override [XmpData](../../aspose.imaging.imageoptions/dicomoptions/xmpdata) { get; set; } | الحصول على أو تعيين بيانات Xmp . |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | استنساخ هذا المثال . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |

### أمثلة

تغيير نوع اللون في ضغط DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

استخدم ضغط RLE في صورة DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression { Type = CompressionType.Rle }
    };

    inputImage.Save("original_RLE.dcm", options);
}
```

استخدم ضغط JPEG 2000 في صورة DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg2000,
            Jpeg2000 = new Jpeg2000Options
            {
                Codec = Jpeg2000Codec.Jp2,
                Irreversible = false
            }
        }
    };

    inputImage.Save("original_JPEG2000.dcm", options);
}
```

استخدم ضغط JPEG في صورة DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg,
            Jpeg = new JpegOptions
            {
                CompressionType = JpegCompressionMode.Baseline,
                SampleRoundingMode = SampleRoundingMode.Truncate,
                Quality = 50
            }
        }
    };

    inputImage.Save("original_JPEG.dcm", options);
}
```

يوضح المثال التالي التصدير إلى تنسيق ملف DICOM (فردي ومتعدد الصفحات).

```csharp
[C#]

string fileName = "sample.jpg";
string inputFileNameSingle = fileName;
string inputFileNameMultipage = "multipage.tif";
string outputFileNameSingleDcm = "output.dcm";
string outputFileNameMultipageDcm = "outputMultipage.dcm";

// يحول نموذج الكود التالي صورة JPEG إلى تنسيق ملف DICOM
using (var image = Aspose.Imaging.Image.Load(inputFileNameSingle))
{
    image.Save(outputFileNameSingleDcm, new Aspose.Imaging.ImageOptions.DicomOptions());
}

// يدعم تنسيق DICOM الصور متعددة الصفحات. يمكنك تحويل صور GIF أو TIFF إلى DICOM بنفس طريقة صور JPEG
using (var imageMultiple = Aspose.Imaging.Image.Load(inputFileNameMultipage))
{
    imageMultiple.Save(outputFileNameMultipageDcm, new Aspose.Imaging.ImageOptions.DicomOptions());
}
```

قم بإنشاء صورة Dicom متعددة الصفحات.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // ارسم شيئًا باستخدام الرسومات المتجهة
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // احفظ وحدات البكسل للصورة المرسومة. هم الآن على الصفحة الأولى من صورة Dicom.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // أضف بضع صفحات بعد ذلك ، مما يجعلها أكثر قتامة
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // أضف بضع صفحات أمام الصفحة الرئيسية ، مما يجعلها أكثر إشراقًا
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // احفظ الصورة متعددة الصفحات التي تم إنشاؤها في ملف الإخراج
    image.Save("MultiPage.dcm");
}
```

### أنظر أيضا

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
