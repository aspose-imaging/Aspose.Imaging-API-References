---
title: TiffOptions
second_title: Aspose.Imaging لمرجع NET API
description: خيارات تنسيق ملف tiff . لاحظ أنه سيتم الكتابة فوق علامات العرض والارتفاع عند إنشاء الصورة بواسطة معلمات العرض والارتفاع  لذلك ليست هناك حاجة لتحديدها مباشرة. لاحظ أن العديد من الخيارات ترجع قيمة افتراضية ولكن هذا لا يعني ذلك يتم تعيين هذا الخيار بشكل صريح كقيمة علامة. للتحقق من وجود العلامة  استخدم خاصية العلامات أو طريقة IsTagPresent المقابلة.
type: docs
weight: 10220
url: /ar/net/aspose.imaging.imageoptions/tiffoptions/
---
## TiffOptions class

خيارات تنسيق ملف tiff . لاحظ أنه سيتم الكتابة فوق علامات العرض والارتفاع عند إنشاء الصورة بواسطة معلمات العرض والارتفاع ، لذلك ليست هناك حاجة لتحديدها مباشرة. لاحظ أن العديد من الخيارات ترجع قيمة افتراضية ولكن هذا لا يعني ذلك يتم تعيين هذا الخيار بشكل صريح كقيمة علامة. للتحقق من وجود العلامة ، استخدم خاصية العلامات أو طريقة IsTagPresent المقابلة.

```csharp
public class TiffOptions : ImageOptionsBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | يقوم بتهيئة مثيل جديد لملف[`TiffOptions`](../tiffoptions) فئة . |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | يقوم بتهيئة مثيل جديد لملف[`TiffOptions`](../tiffoptions)صف دراسي. بشكل افتراضي ، يتم استخدام اصطلاح Endian الصغير. |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | يقوم بتهيئة مثيل جديد لملف[`TiffOptions`](../tiffoptions) فئة . |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | يقوم بتهيئة مثيل جديد لملف[`TiffOptions`](../tiffoptions) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage) { get; set; } | الحصول على أو تحديد خيار تخزين ألفا. خيارات أخرى غيرUnspecified يتم استخدام عندما يكون هناك أكثر من 3[`SamplesPerPixel`](./samplesperpixel) محددة . |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist) { get; set; } | الحصول على الفنان أو تعيينه . |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel) { get; } | يحصل على وحدات البت لكل بكسل . |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample) { get; set; } | الحصول على أو تعيين وحدات البت لكل عينة. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ترتيب tiff بايت. |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap) { get; set; } | الحصول على خريطة الألوان أو تعيينها . |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality) { get; set; } | الحصول على جودة الصورة المضغوطة أو تعيينها. يستخدم مع ضغط Jpeg . |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression) { get; set; } | الحصول على الضغط أو تعيينه . |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright) { get; set; } | الحصول على حقوق النشر أو تعيينها. |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime) { get; set; } | الحصول على أو تحديد التاريخ والوقت. |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport) { get; set; } | الحصول على أو تحديد قيمة تشير إلى ما إذا كان تصدير ملف تعريف ICC معطلاً (يتم تطبيق ملف تعريف ICC على وحدات البكسل المصدر مسبقًا) . |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname) { get; set; } | الحصول على أو تحديد اسم المستند. |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd) { get; } | الحصول على المؤشر أو تعيينه إلى EXIF IFD . |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples) { get; } | يحصل على قيم العينات الإضافية . |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options) { get; set; } | الحصول على أو تعيين خيارات الفاكس t4 . |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard) { get; set; } | الحصول على أو تحديد معيار ملف TIFF. |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder) { get; set; } | الحصول على أو تعيين ترتيب ملء بتات البايت. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [إطار كامل] . |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints) { get; set; } | الحصول على تلميحات الألوان النصفية أو تعيينها. |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile) { get; set; } | الحصول على دفق ملف تعريف Icc أو تعيينه. |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription) { get; set; } | الحصول على أو تحديد وصف الصورة. |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength) { get; set; } | الحصول على أو تحديد طول الصورة . |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth) { get; set; } | الحصول على عرض الصورة أو تحديده . |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames) { get; set; } | الحصول على أسماء الحبر أو تعيينها. |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent) { get; } | الحصول على قيمة تشير إلى وجود العينات الإضافية . |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الصورة مقسمة. |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid) { get; } | يحصل على قيمة تشير إلى ما إذا كان ملف[`TiffOptions`](../tiffoptions) تم تكوينه بشكل صحيح. استخدم طريقة التحقق من الصحة للعثور على سبب الفشل. |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | الحصول على الحد الأقصى لقيمة العينة أو تعيينها. |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue) { get; set; } | الحصول على الحد الأدنى لقيمة العينة أو تعيينها. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | خيارات متعدد الصفحات |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation) { get; set; } | الحصول على الاتجاه أو تحديده. |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename) { get; set; } | الحصول على اسم الصفحة أو تعيينه . |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber) { get; set; } | الحصول على علامة رقم الصفحة أو تعيينها. |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها . |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric) { get; set; } | الحصول على القياس الضوئي أو تعيينه. |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration) { get; set; } | الحصول على التكوين المستوي أو تعيينه. |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor) { get; set; } | الحصول على أو تعيين المتنبئ لضغط LZW . |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب مضاعفة المكونات مسبقًا. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | الحصول على معالج حدث التقدم أو تعيينه. |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings) { get; set; } | الحصول على إعدادات الدقة أو تعيينها . |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit) { get; set; } | الحصول على أو تعيين وحدة الدقة . |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip) { get; set; } | الحصول على أو تعيين الصفوف لكل شريط . |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat) { get; set; } | الحصول على تنسيق العينة أو تعيينه. |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel) { get; } | يحصل على عينات لكل بكسل. لتغيير قيمة هذه الخاصية ، استخدم ملحق[`BitsPerSample`](./bitspersample) واضع الممتلكات . |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | الحصول على أو تعيين الشركة المصنعة للماسح الضوئي. |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel) { get; set; } | الحصول على أو تحديد طراز الماسح . |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | الحصول على الحد الأقصى لقيمة العينة أو تعيينها. تحتوي القيمة على نوع حقل يتطابق بشكل أفضل مع بيانات العينة (نوع بايت أو قصير أو طويل). |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | الحصول على القيمة الدنيا للعينة أو تعيينها. تحتوي القيمة على نوع حقل يتطابق بشكل أفضل مع بيانات العينة (نوع بايت أو قصير أو طويل). |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype) { get; set; } | يحصل أو يحدد نوع البرنامج. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | الحصول على أو تعيين المصدر لإنشاء الصورة فيه. |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts) { get; set; } | الحصول على عدد بايتات الشريط أو تعيينه. |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets) { get; set; } | الحصول على أو تعيين إزاحة الشريط . |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype) { get; set; } | الحصول على أو تعيين إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي. |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags) { get; set; } | الحصول على العلامات أو تعيينها. |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter) { get; set; } | الحصول على الطابعة المستهدفة أو تعيينها . |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding) { get; set; } | الحصول على العتبة أو تعيينها. |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts) { get; set; } | الحصول على عدد بايتات التجانب أو تعيينه. |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength) { get; set; } | يحصل على تعيين طول البلاط. |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets) { get; set; } | الحصول على تعويضات التجانب أو تعيينها. |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth) { get; set; } | يحصل على تعيينات عرض البلاط . |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages) { get; } | الحصول على إجمالي الصفحات . |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount) { get; } | يحصل على عدد العلامات الصالح. هذا ليس إجمالي عدد العلامات ولكن عدد العلامات التي يمكن الاحتفاظ بها. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | الحصول على أو تعيين خيارات التحويل النقطي للمتجه. |
| override [XmpData](../../aspose.imaging.imageoptions/tiffoptions/xmpdata) { get; set; } | الحصول على أو تعيين حاوية بيانات تعريف XMP. |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor) { get; set; } | الحصول على مؤلف الصورة أو تعيينه ، والذي يستخدمه مستكشف Windows. |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment) { get; set; } | الحصول على تعليق على الصورة أو تعيينه ، والذي يستخدمه مستكشف Windows. |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords) { get; set; } | الحصول على أو تعيين صورة الموضوع ، والتي يستخدمها مستكشف Windows . |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition) { get; set; } | الحصول على موضع x أو تحديده . |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject) { get; set; } | الحصول على معلومات حول الصورة أو تعيينها ، والتي يستخدمها مستكشف Windows. |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle) { get; set; } | الحصول على معلومات حول الصورة أو تعيينها ، والتي يستخدمها مستكشف Windows. |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution) { get; set; } | الحصول على دقة x أو تعيينها . |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | الحصول على أو تعيين YCbCrCoefficients . |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | الحصول على أو تعيين عوامل أخذ العينات الفرعية لمقاييس الضوء YCbCr . |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition) { get; set; } | الحصول على أو تحديد الموضع y . |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution) { get; set; } | الحصول على دقة y أو تعيينها . |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag)(TiffDataType) | يضيف علامة جديدة . |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags)(TiffDataType[]) | يضيف العلامات . |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | استنساخ هذا المثال . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype)(TiffTags) | الحصول على مثيل العلامة حسب النوع. |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent)(TiffTags) | لتحديد ما إذا كانت العلامة موجودة في الخيارات أم لا. |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag)(TiffTags) | يزيل العلامة . |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate)() | يتحقق مما إذا كانت الخيارات تحتوي على مجموعة صالحة من العلامات |
| static [GetValidTagsCount](../../aspose.imaging.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | الحصول على عدد العلامات الصالحة . |

### أمثلة

يوضح هذا المثال استخدام فئات مختلفة من SaveOptions Namespace لأغراض التصدير. يتم تحميل صورة من نوع Gif في مثيل Image ثم تصديرها إلى عدة تنسيقات.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة موجودة (من النوع Gif) في مثيل لفئة Image
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تصدير إلى تنسيق ملف BMP باستخدام الخيارات الافتراضية
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    // تصدير إلى تنسيق ملف JPEG باستخدام الخيارات الافتراضية
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    // تصدير إلى تنسيق ملف PNG باستخدام الخيارات الافتراضية
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    // تصدير إلى تنسيق ملف TIFF باستخدام الخيارات الافتراضية
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

يوضح المثال التالي كيفية تحويل صورة متجهية متعددة الصفحات إلى تنسيق TIFF بشكل عام دون الرجوع إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.tiff");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // تصدير أول صفحتين فقط. سيتم تقديم هذه الصفحات كإطارات في إخراج TIFF.
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

تستخدم هذه الأمثلة فئة GraphicsPath و Graphics لإنشاء الأشكال ومعالجتها على سطح الصورة. ينشئ المثال صورة جديدة (من النوع Tiff) ، ويمسح السطح ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية ، يتم استدعاء طريقة DrawPath المعروضة بواسطة فئة الرسومات لعرض المسارات على السطح.

```csharp
[C#]

// إنشاء مثيل لـ FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    // قم بإنشاء مثيل لـ TiffOptions وعيّن خصائصه المتنوعة
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // تعيين المصدر لمثيل ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    // إنشاء مثيل للصورة 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        // إنشاء وتهيئة مثيل لفئة الرسومات
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        // مسح سطح الرسومات
        graphics.Clear(Color.Wheat);

        // إنشاء مثيل لفئة GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        // إنشاء مثيل لفئة الشكل
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        // إضافة أشكال إلى كائن الشكل
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        // إضافة كائن الشكل إلى GraphicsPath
        graphicspath.AddFigure(figure);

        // رسم المسار باستخدام كائن القلم ذي اللون الأسود
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // احفظ جميع التغييرات.
        image.Save();
    }
}
```

### أنظر أيضا

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
