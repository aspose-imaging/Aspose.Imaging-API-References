---
title: "فئة DicomOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.ImageOptions.DicomOptions. واجهة برمجة التطبيقات لإنشاء تنسيق صورة نقطية DICOM (التصوير الرقمي والاتصالات في الطب) هي أداة متخصصة موجهة لتطبيقات الأجهزة الطبية. تتيح توليد صور DICOM بسلاسة، وهو أمر حيوي لتخزين البيانات الطبية واحتواء معلومات التعريف الحيوية. مع ميزات لتعيين الضغط، تعريف أنواع الألوان وتضمين بيانات تعريف XMP، يمكن للمطورين ضمان الامتثال والمرونة في إدارة صور DICOM لأغراض التصوير الطبي."
type: docs
weight: 10290
url: /ar/net/aspose.imaging.imageoptions/dicomoptions/
---
## DicomOptions class

واجهة برمجة التطبيقات لإنشاء صيغة صورة DICOM (Digital Imaging and Communications in Medicine) النقطية هي أداة متخصصة مخصصة لتطبيقات الأجهزة الطبية. تتيح إنشاء صور DICOM بسلاسة، وهو أمر حيوي لتخزين البيانات الطبية واحتواء معلومات التعريف الضرورية. مع ميزات لضبط الضغط، تعريف أنواع الألوان، وتضمين بيانات التعريف XMP، يمكن للمطورين ضمان الامتثال والمرونة في إدارة صور DICOM لأغراض التصوير الطبي.

```csharp
public class DicomOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DicomOptions](dicomoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [ColorType](../../aspose.imaging.imageoptions/dicomoptions/colortype/) { get; set; } | يحصل أو يضبط نوع اللون. |
| [Compression](../../aspose.imaging.imageoptions/dicomoptions/compression/) { get; set; } | الحصول أو تعيين الضغط. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يضبط معالج حدث التقدم. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | يحصل أو يضبط إعدادات الدقة. |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | يحصل أو يضبط حاوية بيانات تعريف XMP. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | ينشئ نسخة عضوية من هذه الحالة. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين مثيل *metadata*، إذا كان مثيل [`Image`](../../aspose.imaging/image/) يدعم ويطبق مثيل [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |

## أمثلة

تغيير نوع اللون في ضغط DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

استخدام ضغط RLE في صورة DICOM.

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

استخدام ضغط JPEG 2000 في صورة DICOM.

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

استخدام ضغط JPEG في صورة DICOM.

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

المثال التالي يوضح تصدير إلى تنسيق ملف DICOM (صفحة واحدة ومتعددة الصفحات).

```csharp
[C#]

string fileName = "sample.jpg";
string inputFileNameSingle = fileName;
string inputFileNameMultipage = "multipage.tif";
string outputFileNameSingleDcm = "output.dcm";
string outputFileNameMultipageDcm = "outputMultipage.dcm";

// عينة الشيفرة التالية تحول صورة JPEG إلى تنسيق ملف DICOM
using (var image = Aspose.Imaging.Image.Load(inputFileNameSingle))
{
    image.Save(outputFileNameSingleDcm, new Aspose.Imaging.ImageOptions.DicomOptions());
}

// يدعم تنسيق DICOM الصور متعددة الصفحات. يمكنك تحويل صور GIF أو TIFF إلى DICOM بنفس طريقة تحويل صور JPEG.
using (var imageMultiple = Aspose.Imaging.Image.Load(inputFileNameMultipage))
{
    imageMultiple.Save(outputFileNameMultipageDcm, new Aspose.Imaging.ImageOptions.DicomOptions());
}
```

إنشاء صورة DICOM متعددة الصفحات.

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

    // احفظ بكسلات الصورة المرسومة. الآن هي على الصفحة الأولى من صورة DICOM.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // أضف بعض الصفحات بعد ذلك، لتجعلها أغمق
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // أضف بعض الصفحات أمام الصفحة الرئيسية، لتجعلها أكثر سطوعًا
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // احفظ الصورة المتعددة الصفحات التي تم إنشاؤها إلى ملف الإخراج
    image.Save("MultiPage.dcm");
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


