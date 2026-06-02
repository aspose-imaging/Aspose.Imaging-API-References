---
title: "الفئة TiffOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageOptions.TiffOptions. خيارات تنسيق ملف TIFF. لاحظ أن وسمي العرض والارتفاع سيتم استبدالهما عند إنشاء الصورة بواسطة معلمات العرض والارتفاع، لذا لا حاجة لتحديدهما مباشرة. لاحظ أن العديد من الخيارات تُعيد قيمة افتراضية لكن هذا لا يعني أن هذا الخيار تم تعيينه صراحةً كقيمة للوسم. للتحقق من وجود الوسم، استخدم خاصية Tags أو الطريقة المقابلة IsTagPresent."
type: docs
weight: 10610
url: /ar/net/aspose.imaging.imageoptions/tiffoptions/
---
## TiffOptions class

خيارات تنسيق ملف tiff. لاحظ أن وسمي العرض والارتفاع سيتم استبدالهما عند إنشاء الصورة بواسطة معلمات العرض والارتفاع، لذا لا حاجة لتحديدهما مباشرة. لاحظ أن العديد من الخيارات تُعيد قيمة افتراضية ولكن هذا لا يعني أن هذا الخيار تم تعيينه صراحةً كقيمة للوسم. للتحقق من وجود الوسم استخدم خاصية Tags أو الطريقة المقابلة IsTagPresent.

```csharp
public class TiffOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | يُنشئ كائنًا جديدًا من الفئة `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | يُنشئ كائنًا جديدًا من الفئة `TiffOptions`. بشكل افتراضي يتم استخدام نظام little endian. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | يُنشئ كائنًا جديدًا من الفئة `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | يُنشئ كائنًا جديدًا من الفئة `TiffOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage/) { get; set; } | يحصل أو يعيّن خيار تخزين ألفا. تُستخدم الخيارات غير Unspecified عندما يكون هناك أكثر من 3 [`SamplesPerPixel`](./samplesperpixel/) معرفة. |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist/) { get; set; } | الحصول أو تعيين الفنان. |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel/) { get; } | يحصل على عدد البتات لكل بكسل. |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample/) { get; set; } | الحصول أو تعيين عدد البتات لكل عينة. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ترتيب بايتات TIFF. |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap/) { get; set; } | يحصل أو يعيّن خريطة الألوان. |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality/) { get; set; } | يحصل أو يعيّن جودة الصورة المضغوطة. يُستخدم مع ضغط JPEG. |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression/) { get; set; } | الحصول أو تعيين الضغط. |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright/) { get; set; } | الحصول أو تعيين حقوق النشر. |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime/) { get; set; } | يحصل أو يعيّن التاريخ والوقت. |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصدير ملف تعريف ICC معطلاً (يُطبق ملف تعريف ICC على بكسلات المصدر مسبقًا). |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname/) { get; set; } | يحصل أو يعيّن اسم المستند. |
| override [ExifData](../../aspose.imaging.imageoptions/tiffoptions/exifdata/) { get; set; } | تحصل أو تعين بيانات Exif. |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd/) { get; } | الحصول أو تعيين المؤشر إلى EXIF IFD. |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples/) { get; } | يحصل على قيم العينات الإضافية. |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options/) { get; set; } | يحصل أو يعيّن خيارات الفاكس T4. |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard/) { get; set; } | يحصل أو يعيّن معيار ملف TIFF. |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder/) { get; set; } | يحصل أو يعيّن ترتيب تعبئة بتات البايت. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints/) { get; set; } | يحصل أو يعيّن تلميحات نصف النغمة. |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile/) { get; set; } | يحصل أو يعيّن تدفق ملف تعريف ICC. |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription/) { get; set; } | الحصول أو تعيين وصف الصورة. |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength/) { get; set; } | الحصول أو تعيين طول الصورة. |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth/) { get; set; } | الحصول أو تعيين عرض الصورة. |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames/) { get; set; } | يحصل أو يعيّن أسماء الأحبار. |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت العينات الإضافية موجودة. |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الصورة مقسمة إلى بلاطات. |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid/) { get; } | يحصل على قيمة تُشير إلى ما إذا كانت `TiffOptions` مُكوّنة بشكل صحيح. استخدم طريقة Validate للعثور على سبب الفشل. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير. |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | يحصل أو يعيّن قيمة العينة القصوى. |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | يحصل أو يعيّن قيمة العينة الدنيا. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation/) { get; set; } | يحصل أو يضبط الاتجاه. |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename/) { get; set; } | يحصل أو يعيّن اسم الصفحة. |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber/) { get; set; } | يحصل أو يعيّن وسم رقم الصفحة. |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric/) { get; set; } | يحصل أو يعيّن الفوتومتري. |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | الحصول أو تعيين تكوين المستوى. |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor/) { get; set; } | يحصل أو يعيّن المتنبئ لضغط LZW. |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب المكونات مسبقًا. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يضبط معالج حدث التقدم. |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | يحصل أو يضبط إعدادات الدقة. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit/) { get; set; } | الحصول أو تعيين وحدة الدقة. |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | يحصل أو يعيّن عدد الصفوف لكل شريط. |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat/) { get; set; } | يحصل أو يعيّن تنسيق العينة. |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel/) { get; } | يحصل على عدد العينات لكل بكسل. لتغيير قيمة هذه الخاصية استخدم مُعيّن الخاصية [`BitsPerSample`](./bitspersample/). |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | يحصل أو يعيّن شركة صانع الماسح. |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel/) { get; set; } | يحصل أو يعيّن طراز الماسح. |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | يحصل أو يعيّن قيمة العينة القصوى. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (نوع Byte أو Short أو Long). |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | يحصل أو يعيّن قيمة العينة الدنيا. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (نوع Byte أو Short أو Long). |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype/) { get; set; } | يحصل أو يعيّن نوع البرنامج. |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | يحصل أو يعيّن عدد بايتات الشريط. |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets/) { get; set; } | يحصل أو يعيّن إزاحات الشريط. |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype/) { get; set; } | يحصل أو يعيّن إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي. |
| [TagCount](../../aspose.imaging.imageoptions/tiffoptions/tagcount/) { get; } | يحصل على عدد الوسوم. |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags/) { get; set; } | يحصل أو يعيّن الوسوم. |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter/) { get; set; } | يحصل أو يعيّن الطابعة المستهدفة. |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding/) { get; set; } | يحصل أو يعيّن تحديد العتبة. |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | يحصل أو يعيّن عدد بايتات البلاط. |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength/) { get; set; } | يحصل أو يضبط طول البلاطة. |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets/) { get; set; } | يحصل أو يضبط إزاحات البلاطة. |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth/) { get; set; } | يحصل أو يضبط عرض البلاطة. |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages/) { get; } | يحصل على إجمالي الصفحات. |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount/) { get; } | يحصل على عدد العلامات الصالحة. هذا ليس إجمالي عدد العلامات بل عدد العلامات التي يمكن حفظها. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | يحصل أو يضبط حاوية بيانات تعريف XMP. |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor/) { get; set; } | يحصل أو يضبط مؤلف الصورة، الذي يستخدمه مستكشف Windows. |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment/) { get; set; } | يحصل أو يضبط التعليق على الصورة، الذي يستخدمه مستكشف Windows. |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords/) { get; set; } | يحصل أو يضبط موضوع الصورة، الذي يستخدمه مستكشف Windows. |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition/) { get; set; } | يحصل أو يضبط موضع x. |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject/) { get; set; } | يحصل أو يضبط معلومات حول الصورة، التي يستخدمها مستكشف Windows. |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle/) { get; set; } | يحصل أو يضبط معلومات حول الصورة، التي يستخدمها مستكشف Windows. |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution/) { get; set; } | يحصل أو يضبط دقة x. |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | يحصل أو يضبط معاملات YCbCr. |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | يحصل أو يضبط عوامل أخذ العينات الفرعية للقياس الضوئي YCbCr. |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition/) { get; set; } | يحصل أو يضبط موضع y. |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution/) { get; set; } | الحصول أو تعيين دقة y. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag/)(TiffDataType) | يضيف علامة جديدة. |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | يضيف العلامات. |
| override [Clone](../../aspose.imaging.imageoptions/tiffoptions/clone/)() | ينسخ هذه المثيلة. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | يحصل على نسخة العلامة حسب النوع. |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent/)(TiffTags) | يحدد ما إذا كانت العلامة موجودة في الخيارات أم لا. |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag/)(TiffTags) | يزيل العلامة. |
| [RemoveTags](../../aspose.imaging.imageoptions/tiffoptions/removetags/)(params TiffTags[]) | يزيل العلامات. |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين مثيل *metadata*، إذا كان مثيل [`Image`](../../aspose.imaging/image/) يدعم ويطبق مثيل [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate/)() | يتحقق من صحة ما إذا كانت الخيارات تحتوي على تركيبة صالحة من العلامات. |
| static [GetValidTagsCount](../../aspose.imaging.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | يحصل على عدد العلامات الصالحة. |

## أمثلة

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

يوضح المثال التالي كيفية تحويل صورة متجهية متعددة الصفحات إلى تنسيق TIFF بطريقة عامة دون الإشارة إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.tiff");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // تصدير الصفحتين الأوليين فقط. سيتم عرض هاتين الصفحتين كإطارات في ملف TIFF الناتج.
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

تستخدم هذه الأمثلة فئة GraphicsPath وفئة Graphics لإنشاء وتعديل الأشكال على سطح صورة. ينشئ المثال صورة جديدة (من نوع Tiff)، يمسح السطح ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية يتم استدعاء طريقة DrawPath التي توفرها فئة Graphics لعرض المسارات على السطح.

```csharp
[C#]

//إنشاء مثيل من FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //إنشاء مثيل من TiffOptions وتعيين خصائصه المتنوعة
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //تعيين المصدر لمثيل ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //إنشاء مثيل من Image
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //إنشاء وتهيئة مثيل من فئة Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //مسح سطح Graphics
        graphics.Clear(Color.Wheat);

        //إنشاء مثيل من فئة GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //إنشاء كائن من الفئة Figure
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //إضافة أشكال إلى كائن Figure
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //إضافة كائن Figure إلى GraphicsPath
        graphicspath.AddFigure(figure);

        //رسم المسار باستخدام كائن Pen باللون الأسود
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // احفظ جميع التغييرات.
        image.Save();
    }
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


