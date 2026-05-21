---
title: "فئة PngOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.ImageOptions.PngOptions. أنشئ صور PNG نقطية عالية الجودة بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا التي توفر خيارات قابلة للتخصيص لمستويات الضغط، عدد البتات لكل بكسل، عمق اللون وبتات ألفا. عالج حاويات بيانات تعريف XMP بسلاسة لضمان إدارة شاملة لبيانات تعريف الصور، وتمكينك من تخصيص صور PNG وفقًا لمواصفاتك الدقيقة بسهولة."
type: docs
weight: 10510
url: /ar/net/aspose.imaging.imageoptions/pngoptions/
---
## PngOptions class

أنشئ صورًا نقطية عالية الجودة بصيغة Portable Network Graphics (PNG) بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع توفير خيارات قابلة للتخصيص لمستويات الضغط، وعدد البتات لكل بكسل، وبتات ألفا. عالج حاويات بيانات التعريف XMP بسلاسة، مما يضمن إدارة شاملة لبيانات تعريف الصورة، ويمكنك من تخصيص صور PNG وفقًا لمواصفاتك الدقيقة بسهولة.

```csharp
public class PngOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PngOptions](pngoptions/#constructor)() | يُنشئ مثيلًا جديدًا من فئة `PngOptions`. |
| [PngOptions](pngoptions/#constructor_1)(PngOptions) | يُنشئ مثيلًا جديدًا من فئة `PngOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth/) { get; set; } | يحصل أو يعيّن قيم عمق البت في النطاق 1، 2، 4، 8، 16. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype/) { get; set; } | يحصل أو يضبط نوع اللون. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype/) { get; set; } | يحصل أو يعيّن نوع الفلتر المستخدم أثناء عملية حفظ ملف png. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. |
| [PngCompressionLevel](../../aspose.imaging.imageoptions/pngoptions/pngcompressionlevel/) { get; set; } | يحصل أو يعيّن مستوى ضغط [`PngImage`](../../aspose.imaging.fileformats.png/pngimage/). |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يضبط معالج حدث التقدم. |
| [Progressive](../../aspose.imaging.imageoptions/pngoptions/progressive/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [`PngImage`](../../aspose.imaging.fileformats.png/pngimage/) تقدميًا. |
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

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.imaging.imageoptions/pngoptions/defaultcompressionlevel/) | مستوى الضغط الافتراضي. |

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

المثال التالي يوضح كيفية تحويل صورة متجهة متعددة الصفحات إلى تنسيق PNG بطريقة عامة دون الإشارة إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.png");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // تصدير الصفحتين الأوليين فقط. في الواقع، سيتم تحويل صفحة واحدة فقط إلى نقطية لأن تنسيق PNG ليس تنسيقًا متعدد الصفحات.
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

يستخدم هذا المثال فئة Graphics لإنشاء أشكال أولية على سطح Image. لتوضيح العملية، ينشئ المثال صورة جديدة بصيغة PNG ويرسم أشكالًا أولية على سطح Image باستخدام طرق Draw التي توفرها فئة Graphics.

```csharp
[C#]

//ينشئ مثيلًا من FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //إنشاء مثيل من PngOptions وتعيين خصائصه المتنوعة
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //تعيين المصدر لـ PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //إنشاء مثيل من Image
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //إنشاء وتهيئة مثيل من فئة Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //مسح سطح Graphics
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //رسم قوس بتحديد كائن Pen الذي له اللون الأسود،
        //مستطيل يحيط بالقوس، زاوية البداية وزاوية المسح
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //رسم منحنى بيزيير بتحديد كائن Pen الذي له اللون الأزرق ونقاط الإحداثيات.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //رسم منحنى بتحديد كائن Pen الذي له اللون الأخضر ومصفوفة من النقاط
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //رسم إهليلج باستخدام كائن Pen ومستطيل محيط
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //رسم خط
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //رسم قطعة فطيرة
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //رسم مضلع بتحديد كائن Pen الذي له اللون الأحمر ومصفوفة من النقاط
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //رسم مستطيل
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //إنشاء كائن SolidBrush وتعيين خصائصه المتنوعة
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //رسم نص باستخدام كائن SolidBrush والخط، عند نقطة محددة
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // احفظ جميع التغييرات.
        image.Save();
    }
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


