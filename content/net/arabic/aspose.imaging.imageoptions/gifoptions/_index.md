---
title: GifOptions
second_title: Aspose.Imaging لمرجع NET API
description: خيارات إنشاء تنسيق ملف gif .
type: docs
weight: 10000
url: /ar/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

خيارات إنشاء تنسيق ملف gif .

```csharp
public class GifOptions : ImageOptionsBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | يقوم بتهيئة مثيل جديد لملف[`GifOptions`](../gifoptions) فئة . |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | يقوم بتهيئة مثيل جديد لملف[`GifOptions`](../gifoptions) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor) { get; set; } | الحصول على لون الخلفية أو تعيينه. |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | الحصول على فهرس لون خلفية GIF أو تعيينه. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution) { get; set; } | الحصول على دقة ألوان GIF أو تعيينها. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان قد تم تطبيق تصحيح لوح الألوان . |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [إطار كامل] . |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع دعائي . |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت صورة GIF لها لون شفاف. |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced) { get; set; } | صحيح إذا كان يجب تشابك الصورة . |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت مدخلات اللوحة مرتبة أم لا. |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount) { get; set; } | الحصول على عدد الحلقات أو تعيينه (حلقة واحدة افتراضية) |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff) { get; set; } | الحصول على أو تحديد أقصى فرق بكسل مسموح به. إذا كانت القيمة أكبر من الصفر ، فسيتم استخدام ضغط الفقد . القيمة الموصى بها للضغط الأمثل مع فقدان البيانات هي 80. 30 ضغط خفيف جدًا ، و 200 ثقيل . يعمل بشكل أفضل عند تقديم خسارة قليلة فقط ، وبسبب قيود خوارزمية الضغط مستويات الخسارة العالية جدًا لن تعطي قدرًا كبيرًا من المكاسب . نطاق القيم المسموح بها هو [0 ، 1000] . |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | خيارات متعدد الصفحات |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها . |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio) { get; set; } | الحصول على أو تعيين نسبة العرض إلى الارتفاع بتنسيق GIF بكسل. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | الحصول على معالج حدث التقدم أو تعيينه. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | الحصول على إعدادات الدقة أو تعيينها . |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | الحصول على أو تعيين المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | الحصول على أو تعيين خيارات التحويل النقطي للمتجه. |
| override [XmpData](../../aspose.imaging.imageoptions/gifoptions/xmpdata) { get; set; } | الحصول على أو تعيين حاوية بيانات تعريف XMP. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | استنساخ هذا المثال . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |

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

يوضح المثال التالي كيفية تحويل صورة متجهة متعددة الصفحات إلى تنسيق GIF بشكل عام دون الرجوع إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.gif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.GifOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // تصدير أول صفحتين فقط. سيتم تقديم هذه الصفحات كإطارات متحركة في ملف GIF الناتج.
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

يوضح هذا المثال كيفية تحميل معلومات البكسل في مصفوفة من نوع اللون ، ومعالجة المصفوفة وإعادة تعيينها إلى الصورة. لإجراء هذه العمليات ، يقوم هذا المثال بإنشاء ملف صورة جديد (بتنسيق GIF) كائن MemoryStream.

```csharp
[C#]

// إنشاء مثيل MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    // إنشاء مثيل لـ GifOptions وتعيين خصائصه المختلفة بما في ذلك خاصية المصدر
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    // إنشاء مثيل للصورة
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        // احصل على وحدات البكسل في الصورة عن طريق تحديد المنطقة كحدود للصورة
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        // حلقة فوق المصفوفة وتعيين لون البكسل المفهرس
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                // اضبط لون البكسل المفهرس على اللون الأصفر
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                // اضبط لون البكسل المفهرس على اللون الأزرق
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        // قم بتطبيق تغييرات البكسل على الصورة
        image.SavePixels(image.Bounds, pixels);

        // احفظ جميع التغييرات.
        image.Save();
    }

    // اكتب MemoryStream إلى ملف
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### أنظر أيضا

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
