---
title: WebPOptions
second_title: Aspose.Imaging لمرجع NET API
description: خيارات صورة Webp
type: docs
weight: 10280
url: /ar/net/aspose.imaging.imageoptions/webpoptions/
---
## WebPOptions class

خيارات صورة Webp

```csharp
public class WebPOptions : ImageOptionsBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [WebPOptions](webpoptions)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AnimBackgroundColor](../../aspose.imaging.imageoptions/webpoptions/animbackgroundcolor) { get; set; } | الحصول على أو تعيين لون خلفية الرسوم المتحركة . |
| [AnimLoopCount](../../aspose.imaging.imageoptions/webpoptions/animloopcount) { get; set; } | الحصول على أو تعيين عدد حلقات الرسوم المتحركة . |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [إطار كامل] . |
| [Lossless](../../aspose.imaging.imageoptions/webpoptions/lossless) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا[`WebPOptions`](../webpoptions) ضياع. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | خيارات متعدد الصفحات |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها . |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | الحصول على معالج حدث التقدم أو تعيينه. |
| [Quality](../../aspose.imaging.imageoptions/webpoptions/quality) { get; set; } | الحصول على الجودة أو تعيينها . |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | الحصول على إعدادات الدقة أو تعيينها . |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | الحصول على أو تعيين المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | الحصول على أو تعيين خيارات التحويل النقطي للمتجه. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | الحصول على أو تعيين حاوية بيانات تعريف XMP. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | استنساخ هذا المثال . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة WebP من صورة نقطية أخرى بجودة ضغط مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة GIF متحركة
using (Aspose.Imaging.Image image = new Aspose.Imaging.Image.Load(dir + "test.gif"))
{
    // للضغط بدون فقد ، تؤدي زيادة إعداد الجودة إلى زيادة جودة الضغط وتقليل حجم الملف
    image.Save(
        dir + "output_lossless_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 20 }); // حجم الملف: 42 كيلو بايت

    image.Save(
        dir + "output_lossless_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 50 }); // حجم الملف: 41 كيلوبايت

    image.Save(
        dir + "output_lossless_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = true, Quality = 80 }); // حجم الملف: 40 كيلو بايت


    // للضغط مع فقدان البيانات ، تؤدي زيادة قيمة الجودة إلى زيادة جودة الصورة وزيادة حجم الملف
    image.Save(
        dir + "output_lossy_20.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 20 }); // حجم الملف: 24 كيلو بايت

    image.Save(
        dir + "output_lossy_50.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 50 }); // حجم الملف: 36 كيلوبايت

    image.Save(
        dir + "output_lossy_80.webp",
        new  Aspose.Imaging.ImageOptions.WebPOptions() { Lossless = false, Quality = 80 }); // حجم الملف: 51 كيلو بايت
}
```

يوضح المثال التالي كيفية تحويل صورة متجهية متعددة الصفحات إلى تنسيق WEBP بشكل عام دون الرجوع إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.webp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.WebPOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // تصدير أول صفحتين فقط. سيتم تقديم هذه الصفحات كإطارات متحركة في إخراج WEBP.
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

### أنظر أيضا

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
