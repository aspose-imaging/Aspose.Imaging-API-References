---
title: PsdOptions
second_title: Aspose.Imaging لمرجع NET API
description: خيارات إنشاء تنسيق ملف psd .
type: docs
weight: 10140
url: /ar/net/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

خيارات إنشاء تنسيق ملف psd .

```csharp
public class PsdOptions : ImageOptionsBase
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PsdOptions](psdoptions#constructor)() | يقوم بتهيئة مثيل جديد لملف[`PsdOptions`](../psdoptions) فئة . |
| [PsdOptions](psdoptions#constructor_1)(PsdOptions) | يقوم بتهيئة مثيل جديد لملف[`PsdOptions`](../psdoptions) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [ChannelBitsCount](../../aspose.imaging.imageoptions/psdoptions/channelbitscount) { get; set; } | الحصول على أو تعيين عدد البتات لكل قناة لون. |
| [ChannelsCount](../../aspose.imaging.imageoptions/psdoptions/channelscount) { get; set; } | الحصول على أو تعيين عدد قنوات اللون . |
| [ColorMode](../../aspose.imaging.imageoptions/psdoptions/colormode) { get; set; } | الحصول على أو تعيين وضع لون psd . |
| [CompressionMethod](../../aspose.imaging.imageoptions/psdoptions/compressionmethod) { get; set; } | الحصول على أو تعيين طريقة ضغط psd. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [إطار كامل] . |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | خيارات متعدد الصفحات |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها . |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | الحصول على معالج حدث التقدم أو تعيينه. |
| [PsdVersion](../../aspose.imaging.imageoptions/psdoptions/psdversion) { get; set; } | الحصول على أو تحديد إصدار تنسيق الملف. يمكن أن يكون PSD أو PSB. |
| [RefreshImagePreviewData](../../aspose.imaging.imageoptions/psdoptions/refreshimagepreviewdata) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [تحديث بيانات معاينة الصورة] - الخيار المستخدم لزيادة التوافق مع برامج عرض صور PSD الأخرى. |
| [RemoveGlobalTextEngineResource](../../aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العام - يستخدم لبعض ملفات psd ذات طبقات النص ، في الحالة فقط ، عندما لا يمكن فتحها في Adobe Photoshop بعد المعالجة (غالبًا بالنسبة لطبقات النص الخاصة بالخطوط الغائبة). بعد استخدام هذا الخيار ، يحتاج المستخدم إلى جعل التالي مفتوحًا في ملف Photoshop: قائمة "نص" -&gt; "معالجة الخطوط الغائبة". بعد هذه العملية سيظهر النص بالكامل مرة أخرى. يرجى ملاحظة أن هذه العملية قد تسبب بعض التغييرات النهائية في التخطيط. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | الحصول على إعدادات الدقة أو تعيينها . |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | الحصول على أو تعيين المصدر لإنشاء الصورة فيه. |
| [VectorizationOptions](../../aspose.imaging.imageoptions/psdoptions/vectorizationoptions) { get; set; } | الحصول على أو تعيين خيارات توجيه PSD. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | الحصول على أو تعيين خيارات التحويل النقطي للمتجه. |
| [Version](../../aspose.imaging.imageoptions/psdoptions/version) { get; set; } | الحصول على أو تعيين إصدار ملف psd. |
| override [XmpData](../../aspose.imaging.imageoptions/psdoptions/xmpdata) { get; set; } | الحصول على أو تعيين حاوية بيانات XMP |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | استنساخ هذا المثال . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |

### أمثلة

يوضح هذا المثال استخدام Aspsoe.Imaging لـ NET API لتحويل الصور إلى تنسيق PSD. لتحقيق هذا الهدف ، يقوم هذا المثال بتحميل صورة موجودة ثم يحفظها مرة أخرى بتنسيق PSD.

```csharp
[C#]

string dir = "c:\\temp\\";

// ينشئ مثيلاً لفئة الصورة وتهيئته بملف موجود من خلال مسار الملف
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // إنشاء مثيل لفئة PsdOptions
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    // قم بتعيين CompressionMethod كـ RLE
    // ملاحظة: طريقة الضغط المدعومة الأخرى هي CompressionMethod.RAW [بدون ضغط]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    // اضبط ColorMode على GrayScale
    // ملاحظة: رموز ColorModes الأخرى المدعومة هي ColorModes.Bitmap و ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    // احفظ الصورة في موقع القرص باستخدام إعدادات PsdOptions المتوفرة
    image.Save(dir + "output.psd", psdOptions);
}
```

يوضح المثال التالي كيفية تحويل صورة متجه متعددة الصفحات إلى تنسيق PSD بشكل عام دون الرجوع إلى نوع صورة معين.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.psd");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // تصدير أول صفحتين فقط. سيتم تقديم هذه الصفحات كطبقات في PSD الناتج.
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
