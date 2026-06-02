---
title: "الفئة WebPOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageOptions.WebPOptions. أنشئ صور ويب raster بصيغة WebP الحديثة باستخدام واجهة برمجة التطبيقات الخاصة بنا التي توفر دعمًا قويًا للضغط غير الفاقد والفقدان بالإضافة إلى قنوات ألفا وحلقات الرسوم المتحركة. حسّن محتوى الويب الخاص بك بصور ديناميكية مع تحسين أحجام الملفات لسرعات تحميل محسّنة وتجربة مستخدم أفضل."
type: docs
weight: 10660
url: /ar/net/aspose.imaging.imageoptions/webpoptions/
---
## WebPOptions class

أنشئ صور ويب نقطية حديثة بصيغة WebP باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع دعم قوي للضغط غير الفاقد والفقدان، بالإضافة إلى قنوات ألفا وحلقات الرسوم المتحركة. حسّن محتوى الويب الخاص بك بصور ديناميكية مع تحسين أحجام الملفات لزيادة سرعات التحميل وتحسين تجربة المستخدم.

```csharp
public class WebPOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WebPOptions](webpoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AnimBackgroundColor](../../aspose.imaging.imageoptions/webpoptions/animbackgroundcolor/) { get; set; } | يحصل أو يعيّن لون خلفية الرسوم المتحركة. |
| [AnimLoopCount](../../aspose.imaging.imageoptions/webpoptions/animloopcount/) { get; set; } | يحصل أو يعيّن عدد دورات الرسوم المتحركة. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير. |
| [Lossless](../../aspose.imaging.imageoptions/webpoptions/lossless/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `WebPOptions` بدون فقدان. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يضبط معالج حدث التقدم. |
| [Quality](../../aspose.imaging.imageoptions/webpoptions/quality/) { get; set; } | يحصل أو يعيّن الجودة. |
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

يوضح هذا المثال كيفية إنشاء صورة WebP من صورة نقطية أخرى مع جودة ضغط مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل رسوم متحركة GIF
using (Aspose.Imaging.Image image = new Aspose.Imaging.Image.Load(dir + "test.gif"))
{
    // لضغط بدون فقدان، زيادة إعداد الجودة يزيد من جودة الضغط ويقلل من حجم الملف
    image.Save(
        dir + "output_lossless_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 20 }); // file size: 42 KB

    image.Save(
        dir + "output_lossless_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 50 }); // file size: 41 KB

    image.Save(
        dir + "output_lossless_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 80 }); // file size: 40 KB


    // لضغط بفقدان، زيادة قيمة الجودة يزيد من جودة الصورة ويزيد من حجم الملف
    image.Save(
        dir + "output_lossy_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 20 }); // file size: 24 KB

    image.Save(
        dir + "output_lossy_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 50 }); // file size: 36 KB

    image.Save(
        dir + "output_lossy_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 80 }); // file size: 51 KB
}
```

يوضح المثال التالي كيفية تحويل صورة متجه متعددة الصفحات إلى تنسيق WEBP بطريقة عامة دون الإشارة إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.webp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.WebPOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // تصدير الصفحتين الأوليين فقط. سيتم تقديم هاتين الصفحتين كإطارات متحركة في WEBP الناتج.
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


