---
title: "الفئة BmpOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageOptions.BmpOptions. توفر واجهة برمجة التطبيقات (API) لخيارات إنشاء تنسيق الصورة النقطية BMP و DIB مجموعة أدوات متعددة الاستخدامات للمطورين لإنشاء صور Bitmap BMP و Device Independent Bitmap DIB مخصصة. باستخدام هذه الواجهة يمكنك تحديد خصائص الصورة بدقة مثل عدد البتات لكل بكسل ومستوى الضغط ونوع الضغط، مما يتيح تخصيص الناتج لتلبية المتطلبات المحددة. هذه الواجهة الغنية بالميزات تمكّن المطورين من إنشاء صور نقطية مخصصة عالية الجودة بسهولة ومرونة لتطبيقات متنوعة."
type: docs
weight: 10260
url: /ar/net/aspose.imaging.imageoptions/bmpoptions/
---
## BmpOptions class

واجهة برمجة التطبيقات لإنشاء خيارات صيغة صورة BMP و DIB النقطية توفر للمطورين مجموعة أدوات متعددة الاستخدامات لتوليد صور Bitmap (BMP) و Device Independent Bitmap (DIB) مخصصة. باستخدام هذه الواجهة، يمكنك تحديد خصائص الصورة بدقة مثل عدد البتات لكل بكسل، مستوى الضغط ونوع الضغط، لتكييف النتيجة وفقًا للمتطلبات المحددة. تُمكّن هذه الواجهة الغنية بالميزات المطورين من إنشاء صور نقطية عالية الجودة ومخصصة بسهولة ومرونة لتطبيقات متنوعة.

```csharp
public class BmpOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [BmpOptions](bmpoptions/#constructor)() | ينشئ مثيلًا جديدًا للفئة `BmpOptions`. |
| [BmpOptions](bmpoptions/#constructor_1)(BmpOptions) | ينشئ مثيلًا جديدًا للفئة `BmpOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitsPerPixel](../../aspose.imaging.imageoptions/bmpoptions/bitsperpixel/) { get; set; } | يحصل أو يضبط عدد البتات لكل بكسل في الصورة. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Compression](../../aspose.imaging.imageoptions/bmpoptions/compression/) { get; set; } | يحصل أو يضبط نوع الضغط. النوع الافتراضي للضغط هو Bitfields، الذي يسمح بحفظ [`BmpImage`](../../aspose.imaging.fileformats.bmp/bmpimage/) مع الشفافية. |
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

هذا المثال ينشئ ملف صورة جديد في موقع على القرص كما هو محدد بواسطة خاصية Source لكائن BmpOptions. يتم تعيين عدة خصائص لكائن BmpOptions قبل إنشاء الصورة الفعلية. خاصةً خاصية Source التي تشير إلى موقع القرص الفعلي في هذه الحالة.

```csharp
[C#]

//أنشئ مثيلاً من BmpOptions وعيّن خصائصه المتنوعة
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//أنشئ مثيلاً من FileCreateSource وعيّنها كمصدر للمثيل من BmpOptions
//المعامل المنطقي الثاني يحدد ما إذا كان الملف الذي سيُنشأ مؤقتًا أم لا
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//إنشاء كائن من نوع Image وتهيئته بكائن BmpOptions عن طريق استدعاء طريقة Create.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //قم ببعض معالجة الصورة.

    // احفظ جميع التغييرات.
    image.Save();
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

المثال التالي يوضح كيفية تحويل صورة متجهة متعددة الصفحات إلى تنسيق BMP بطريقة عامة دون الإشارة إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.bmp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // قم بتصدير الصفحتين الأوليتين فقط. في الواقع، سيتم تحويل صفحة واحدة فقط إلى نقطية لأن BMP ليس تنسيقًا متعدد الصفحات.
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


