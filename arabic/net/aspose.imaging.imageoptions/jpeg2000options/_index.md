---
title: "الفئة Jpeg2000Options"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.ImageOptions.Jpeg2000Options. إنشاء ملفات صور JPEG2000 JP2 باستخدام واجهة برمجة التطبيقات الخاصة بنا باستخدام تقنية الموجة المتقدمة لتشفير المحتوى غير الفاقد. الاستفادة من الدعم لمختلف الترميزات بما في ذلك الضغط غير العكسي والضغط غير الفاقد بالإضافة إلى حاويات بيانات التعريف XMP لضمان التنوع وإنشاء صور عالية الجودة مخصصة لاحتياجاتك"
type: docs
weight: 10380
url: /ar/net/aspose.imaging.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

أنشئ ملفات صورة JPEG2000 (JP2) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مستفيدًا من تقنية الموجة المتقدمة لتشفير المحتوى بدون فقدان. استفد من الدعم لمختلف الترميزات، بما في ذلك الضغط غير القابل للعكس والضغط بدون فقدان، بالإضافة إلى حاويات بيانات التعريف XMP، مما يضمن تنوعًا وإنشاء صور عالية الجودة مخصصًا لاحتياجاتك.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | يُنشئ مثيلاً جديدًا للفئة `Jpeg2000Options`. |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | يُنشئ مثيلاً جديدًا للفئة `Jpeg2000Options`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Codec](../../aspose.imaging.imageoptions/jpeg2000options/codec/) { get; set; } | يحصل أو يعيّن برنامج الترميز JPEG2000 |
| [Comments](../../aspose.imaging.imageoptions/jpeg2000options/comments/) { get; set; } | يحصل أو يعيّن علامات تعليقات Jpeg. |
| [CompressionRatios](../../aspose.imaging.imageoptions/jpeg2000options/compressionratios/) { get; set; } | يحصل أو يعيّن مصفوفة نسب الضغط. نسب ضغط مختلفة للطبقات المتتالية. المعدل المحدد لكل مستوى جودة هو عامل الضغط المطلوب. النسب المتناقصة مطلوبة. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [Irreversible](../../aspose.imaging.imageoptions/jpeg2000options/irreversible/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان سيتم استخدام DWT غير العكسي 9-7 (true) أو استخدام ضغط DWT غير الفاقد 5-3 (الافتراضي). |
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

يوضح المثال التالي كيفية تحويل صورة متجهية متعددة الصفحات إلى تنسيق JPEG 2000 بطريقة عامة دون الإشارة إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.j2k");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // تصدير الصفحتين الأوليين فقط. في الواقع، سيتم تحويل صفحة واحدة فقط إلى نقطية لأن JPEG 2000 ليس تنسيقًا متعدد الصفحات.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


