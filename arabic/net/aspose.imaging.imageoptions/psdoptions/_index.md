---
title: "الفئة PsdOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageOptions.PsdOptions. إنشاء صور مستندات Photoshop بصيغة PSD باستخدام واجهة برمجة التطبيقات الخاصة بنا التي توفر خيارات متعددة مع إصدارات تنسيق مختلفة، وأساليب ضغط، وأنماط ألوان، وعدد البتات لكل قناة لون. التعامل بسلاسة مع حاويات بيانات XMP لضمان معالجة شاملة للصور مع قوة ميزات تنسيق PSD مثل طبقات الصورة، أقنعة الطبقة، ومعلومات الملف للتخصيص والإبداع في تصاميمك."
type: docs
weight: 10530
url: /ar/net/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

أنشئ صور مستندات فوتوشوب (PSD) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع توفير خيارات متعددة لإصدارات الصيغة المختلفة، وطرق الضغط، وأنماط الألوان، وعدد البتات لكل قناة لون. عالج حاويات بيانات التعريف XMP بسلاسة، مما يضمن معالجة شاملة للصور باستخدام ميزات صيغة PSD مثل طبقات الصورة، وأقنعة الطبقات، ومعلومات الملف لتخصيص وإبداع تصاميمك.

```csharp
public class PsdOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | يُهيئ مثيلًا جديدًا من الفئة `PsdOptions`. |
| [PsdOptions](psdoptions/#constructor_1)(PsdOptions) | يُهيئ مثيلًا جديدًا من الفئة `PsdOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [ChannelBitsCount](../../aspose.imaging.imageoptions/psdoptions/channelbitscount/) { get; set; } | يحصل أو يعيّن عدد البتات لكل قناة لون. |
| [ChannelsCount](../../aspose.imaging.imageoptions/psdoptions/channelscount/) { get; set; } | يحصل أو يعيّن عدد قنوات اللون. |
| [ColorMode](../../aspose.imaging.imageoptions/psdoptions/colormode/) { get; set; } | يحصل أو يعيّن وضع لون PSD. |
| [CompressionMethod](../../aspose.imaging.imageoptions/psdoptions/compressionmethod/) { get; set; } | يحصل أو يعيّن طريقة ضغط PSD. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يضبط معالج حدث التقدم. |
| [PsdVersion](../../aspose.imaging.imageoptions/psdoptions/psdversion/) { get; set; } | يحصل أو يضبط نسخة تنسيق الملف. يمكن أن تكون PSD أو PSB. |
| [RefreshImagePreviewData](../../aspose.imaging.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [refresh image preview data] - خيار يُستخدم لتعزيز التوافق مع عارضات صور PSD أخرى. يرجى ملاحظة أن رسم طبقات النص إلى التخطيط النهائي غير مدعوم لمنصة Compact Framework. |
| [RemoveGlobalTextEngineResource](../../aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العالمي - يُستخدم لبعض ملفات PSD ذات الطبقات النصية، في الحالة الوحيدة التي لا يمكن فتحها في Adobe Photoshop بعد المعالجة (غالبًا ما يتعلق بطبقات النص التي تفتقد الخطوط). بعد استخدام هذا الخيار، يحتاج المستخدم إلى تنفيذ التالي في الملف المفتوح في Photoshop: القائمة "Text" -&gt; "Process absent fonts". بعد تلك العملية سيظهر كل النص مرة أخرى. يرجى ملاحظة أن هذه العملية قد تسبب بعض تغييرات التخطيط النهائي. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | يحصل أو يضبط إعدادات الدقة. |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [VectorizationOptions](../../aspose.imaging.imageoptions/psdoptions/vectorizationoptions/) { get; set; } | يحصل أو يضبط خيارات تحويل PSD إلى متجهات. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| [Version](../../aspose.imaging.imageoptions/psdoptions/version/) { get; set; } | يحصل أو يضبط نسخة ملف PSD. |
| override [XmpData](../../aspose.imaging.imageoptions/psdoptions/xmpdata/) { get; set; } | احصل أو اضبط حاوية بيانات XMP |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | ينشئ نسخة عضوية من هذه الحالة. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين مثيل *metadata*، إذا كان مثيل [`Image`](../../aspose.imaging/image/) يدعم ويطبق مثيل [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |

## أمثلة

يوضح هذا المثال استخدام Aspsoe.Imaging لواجهة برمجة التطبيقات .Net لتحويل الصور إلى تنسيق PSD. لتحقيق هذا الهدف، يقوم المثال بتحميل صورة موجودة ثم حفظها مرة أخرى بتنسيق PSD.

```csharp
[C#]

string dir = "c:\\temp\\";

//ينشئ مثيلاً من فئة الصورة ويُهيئه بملف موجود عبر مسار الملف
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //إنشاء مثيل من فئة PsdOptions
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    //ضبط CompressionMethod كـ RLE
    //ملاحظة: CompressionMethod المدعومة الأخرى هي CompressionMethod.RAW [بدون ضغط]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    //ضبط ColorMode إلى GrayScale
    //ملاحظة: ColorModes المدعومة الأخرى هي ColorModes.Bitmap و ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    //احفظ الصورة إلى موقع القرص باستخدام إعدادات PsdOptions المقدمة
    image.Save(dir + "output.psd", psdOptions);
}
```

يوضح المثال التالي كيفية تحويل صورة متجهية متعددة الصفحات إلى تنسيق PSD بطريقة عامة دون الإشارة إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.psd");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // تصدير الصفحتين الأوليين فقط. ستُعرض هاتان الصفحتان كطبقات في ملف PSD الناتج.
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


