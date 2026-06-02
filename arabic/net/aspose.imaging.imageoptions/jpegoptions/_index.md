---
title: "الفئة JpegOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageOptions.JpegOptions. أنشئ صور JPEG عالية الجودة بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا التي تقدم مستويات ضغط قابلة للتعديل لتحسين حجم التخزين دون التضحية بجودة الصورة. استفد من الدعم لأنواع مختلفة من الضغط، الترميز القريب من فقدان البيانات، ملفات تعريف ألوان RGB وCMYK بالإضافة إلى بيانات صورة EXIF وJFIF وحاويات XMP، مما يضمن خيارات مرنة وقابلة للتخصيص لاحتياجات إنشاء الصور الخاصة بك."
type: docs
weight: 10390
url: /ar/net/aspose.imaging.imageoptions/jpegoptions/
---
## JpegOptions class

أنشئ صور JPEG عالية الجودة بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا، حيث توفر مستويات ضغط قابلة للتعديل لتحسين حجم التخزين دون المساس بجودة الصورة. استفد من الدعم لأنواع مختلفة من الضغط، الترميز شبه غير الفاقد، ملفات تعريف الألوان RGB و CMYK، بالإضافة إلى بيانات EXIF و JFIF، وحاويات XMP، مما يضمن خيارات متعددة وقابلة للتخصيص لإنشاء الصور وفقًا لاحتياجاتك.

```csharp
public class JpegOptions : ImageOptionsBase, IHasJpegExifData
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | يُهيئ مثيلاً جديدًا من الفئة `JpegOptions`. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | يُهيئ مثيلاً جديدًا من الفئة `JpegOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitsPerChannel](../../aspose.imaging.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | يحصل أو يضبط عدد البتات لكل قناة في صورة JPEG غير مضغوطة. الآن ندعم من 2 إلى 8 بتات لكل قناة. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [CmykColorProfile](../../aspose.imaging.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | ملف تعريف اللون CMYK الوجهة لصور JPEG بنظام CMYK. يُستخدم لحفظ الصور. يجب أن يكون مقترنًا بملف تعريف اللون RGBColorProfile للتحويل اللوني الصحيح. |
| [ColorType](../../aspose.imaging.imageoptions/jpegoptions/colortype/) { get; set; } | يحصل أو يضبط نوع اللون لصورة JPEG. |
| [Comment](../../aspose.imaging.imageoptions/jpegoptions/comment/) { get; set; } | يحصل أو يضبط تعليق ملف JPEG. |
| [CompressionType](../../aspose.imaging.imageoptions/jpegoptions/compressiontype/) { get; set; } | يحصل أو يضبط نوع الضغط. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging.imageoptions/jpegoptions/exifdata/) { get; set; } | احصل أو اضبط حاوية بيانات Exif. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [HorizontalSampling](../../aspose.imaging.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | يحصل أو يضبط العينات الفرعية الأفقية لكل مكوّن. |
| [Jfif](../../aspose.imaging.imageoptions/jpegoptions/jfif/) { get; set; } | يحصل أو يضبط الـ jfif. |
| [JpegLsAllowedLossyError](../../aspose.imaging.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | يحصل أو يضبط حد الفرق في JPEG-LS للترميز القريب من فقدان البيانات (معامل NEAR من مواصفة JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.imaging.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | يحصل أو يضبط وضع التداخل في JPEG-LS. |
| [JpegLsPreset](../../aspose.imaging.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | يحصل أو يضبط معلمات الإعداد المسبق لـ JPEG-LS. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. |
| [PreblendAlphaIfPresent](../../aspose.imaging.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب خلط مكونات الأحمر والأخضر والأزرق مع لون الخلفية، إذا كان هناك قناة ألفا. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يضبط معالج حدث التقدم. |
| [Quality](../../aspose.imaging.imageoptions/jpegoptions/quality/) { get; set; } | يحصل أو يضبط جودة الصورة. |
| [RdOptSettings](../../aspose.imaging.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | يحصل أو يضبط إعدادات مُحسّن RD. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | يحصل أو يضبط إعدادات الدقة. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/jpegoptions/resolutionunit/) { get; set; } | الحصول أو تعيين وحدة الدقة. |
| [RgbColorProfile](../../aspose.imaging.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | ملف تعريف اللون RGB الوجهة لصور JPEG بنظام CMYK. يُستخدم لحفظ الصور. يجب أن يكون مقترنًا بـ CMYKColorProfile للتحويل اللوني الصحيح. |
| [SampleRoundingMode](../../aspose.imaging.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | يحصل أو يعيّن وضع تقريب العينة لتلائم قيمة 8-بت إلى قيمة n-بت. BitsPerChannel |
| [ScaledQuality](../../aspose.imaging.imageoptions/jpegoptions/scaledquality/) { get; } | الجودة المُقاسة. |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| [VerticalSampling](../../aspose.imaging.imageoptions/jpegoptions/verticalsampling/) { get; set; } | يحصل أو يعيّن عمليات التقليل العمودي لكل مكوّن. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | يحصل أو يضبط حاوية بيانات تعريف XMP. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | ينشئ نسخة عضوية من هذه الحالة. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين مثيل *metadata*، إذا كان مثيل [`Image`](../../aspose.imaging/image/) يدعم ويطبق مثيل [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |

## أمثلة

يوضح هذا المثال استخدام System.IO.Stream لإنشاء ملف صورة جديد (نوع JPEG).

```csharp
[C#]

//ينشئ مثيلًا من JpegOptions ويضبط خصائصه المتنوعة.
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//إنشاء مثيل من System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//حدد خاصية المصدر للمثيل من JpegOptions.
//المعامل المنطقي الثاني يحدد ما إذا كان سيتم التخلص من الـ Stream بمجرد الخروج من النطاق.
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//ينشئ مثيلًا من Image ويستدعي طريقة Create مع JpegOptions كمعامل لتهيئة كائن Image.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    //قم ببعض معالجة الصورة.
}
```

يوضح هذا المثال استخدام فئات مختلفة من مساحة الأسماء SaveOptions لأغراض التصدير. يتم تحميل صورة من نوع Gif في مثيل من الفئة Image ثم يتم تصديرها إلى عدة تنسيقات.

```csharp
[C#]

string dir = "c:\\temp\\";

//حمّل صورة موجودة (من نوع Gif) في مثيل من الفئة Image
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //تصدير إلى تنسيق ملف BMP باستخدام الخيارات الافتراضية
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //تصدير إلى تنسيق ملف JPEG باستخدام الخيارات الافتراضية
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //تصدير إلى تنسيق ملف PNG باستخدام الخيارات الافتراضية
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //تصدير إلى تنسيق ملف TIFF باستخدام الخيارات الافتراضية
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

يوضح المثال التالي كيفية تحويل صورة متجه متعددة الصفحات إلى تنسيق JPEG بطريقة عامة دون الإشارة إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.jpeg");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // تصدير الصفحتين الأوليين فقط. في الواقع، سيتم تحويل صفحة واحدة فقط إلى نقطية لأن JPEG ليس تنسيقًا متعدد الصفحات.
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
* interface [IHasJpegExifData](../../aspose.imaging.exif/ihasjpegexifdata/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


