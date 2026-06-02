---
title: "الفئة GifOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageOptions.GifOptions. توفر واجهة برمجة التطبيقات لإنشاء ملفات صور نقطية بصيغة GIF (Graphics Interchange Format) للمطورين خيارات شاملة لتوليد صور GIF مع تحكم دقيق. مع ميزات لتعيين لون الخلفية، لوحة ألوان، الدقة، النوع المتشابك، اللون الشفاف، حاوية بيانات XMP الوصفية، وضغط الصورة، تضمن هذه الواجهة مرونة وكفاءة في إنشاء ملفات GIF مُحسّنة وجذابة بصريًا مُصممة لتلبية متطلبات التطبيقات المحددة."
type: docs
weight: 10350
url: /ar/net/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

واجهة برمجة التطبيقات لإنشاء ملفات صورة GIF (Graphical Interchange Format) النقطية توفر للمطورين خيارات شاملة لتوليد صور GIF مع تحكم دقيق. مع ميزات لتعيين لون الخلفية، لوحة الألوان، الدقة، نوع التداخل، اللون الشفاف، حاوية بيانات التعريف XMP، وضغط الصورة، تضمن هذه الواجهة المرونة والكفاءة في إنشاء GIFs محسّنة وجذابة بصريًا مخصصة وفقًا لمتطلبات التطبيق المحددة.

```csharp
public class GifOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | يُهيئ مثيلًا جديدًا من الفئة `GifOptions`. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | يُهيئ مثيلًا جديدًا من الفئة `GifOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor/) { get; set; } | يحصل أو يضبط لون الخلفية. |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | يحصل أو يضبط فهرس لون خلفية GIF. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution/) { get; set; } | يحصل أو يضبط دقة ألوان GIF. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا تم تطبيق تصحيح لوحة الألوان. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع تمهيدي. |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كانت صورة GIF لها لون شفاف. إذا كانت القيمة المرجعة هي `null`، يتم تجاوز هذه الخاصية بواسطة سياق الصورة المصدر. |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced/) { get; set; } | صحيح إذا كان يجب أن تكون الصورة متشابكة. |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كانت مدخلات اللوحة مرتبة. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير. |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount/) { get; set; } | يحصل أو يضبط عدد الحلقات (الافتراضي حلقة واحدة). |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff/) { get; set; } | يحصل أو يضبط الحد الأقصى المسموح به لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان البيانات. القيمة الموصى بها لضغط فقدان البيانات الأمثل هي 80. 30 يعني ضغط خفيف جدًا، 200 يعني ضغط ثقيل. يعمل بشكل أفضل عندما يتم إدخال فقدان قليل فقط، وبسبب قيود خوارزمية الضغط فإن مستويات الفقدان العالية جدًا لن تعطي الكثير من الفائدة. النطاق المسموح به للقيم هو [0, 1000]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | يحصل أو يضبط نسبة أبعاد بكسل GIF. |
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

المثال التالي يوضح كيفية تحويل صورة متجه متعددة الصفحات إلى تنسيق GIF بطريقة عامة دون الإشارة إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.gif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.GifOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // تصدير الصفحتين الأوليين فقط. ستُعرض هذه الصفحات كإطارات متحركة في GIF الناتج.
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

يوضح هذا المثال كيفية تحميل معلومات البكسل في مصفوفة من النوع Color، تعديل المصفوفة وإعادتها إلى الصورة. لتنفيذ هذه العمليات، ينشئ هذا المثال ملف صورة جديد (بتنسيق GIF) باستخدام كائن MemoryStream.

```csharp
[C#]

//إنشاء مثيل من MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //إنشاء مثيل من GifOptions وتعيين خصائصه المتنوعة بما في ذلك خاصية Source
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //إنشاء مثيل من Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //احصل على بكسلات الصورة عن طريق تحديد المنطقة كحدود الصورة
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //التكرار عبر المصفوفة وتعيين لون البكسل المفهرس البديل
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //تعيين لون البكسل المفهرس إلى الأصفر
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //تعيين لون البكسل المفهرس إلى الأزرق
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //تطبيق تغييرات البكسل على الصورة
        image.SavePixels(image.Bounds, pixels);

        // احفظ جميع التغييرات.
        image.Save();
    }

    // كتابة MemoryStream إلى ملف
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


