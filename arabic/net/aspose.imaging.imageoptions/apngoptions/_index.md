---
title: ApngOptions
second_title: Aspose.Imaging لمرجع NET API
description: خيارات تنسيق ملف PNG المتحركة
type: docs
weight: 9900
url: /ar/net/aspose.imaging.imageoptions/apngoptions/
---
## ApngOptions class

خيارات تنسيق ملف PNG المتحركة

```csharp
public class ApngOptions : PngOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ApngOptions](apngoptions)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth) { get; set; } | عمق البت . |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype) { get; set; } | الحصول على أو تحديد نوع اللون. |
| [CompressionLevel](../../aspose.imaging.imageoptions/pngoptions/compressionlevel) { get; set; } | مستوى ضغط الصورة png في النطاق من 0 إلى 9 ، حيث يمثل 9 أقصى ضغط ويكون 0 هو وضع التخزين. |
| [DefaultFrameTime](../../aspose.imaging.imageoptions/apngoptions/defaultframetime) { get; set; } | الحصول على أو تحديد مدة الإطار الافتراضية. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype) { get; set; } | الحصول على أو تحديد نوع المرشح المستخدم أثناء عملية حفظ ملف png. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان [إطار كامل] . |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | خيارات متعدد الصفحات |
| [NumPlays](../../aspose.imaging.imageoptions/apngoptions/numplays) { get; set; } | الحصول على أو تعيين عدد مرات تكرار الرسوم المتحركة. 0 يشير إلى التكرار اللانهائي. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها . |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | الحصول على معالج حدث التقدم أو تعيينه. |
| [Progressive](../../aspose.imaging.imageoptions/pngoptions/progressive) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا[`PngOptions`](../pngoptions) تقدمية. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | الحصول على إعدادات الدقة أو تعيينها . |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | الحصول على أو تعيين المصدر لإنشاء الصورة فيه. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | الحصول على أو تعيين خيارات التحويل النقطي للمتجه. |
| override [XmpData](../../aspose.imaging.imageoptions/pngoptions/xmpdata) { get; set; } | الحصول على أو تعيين حاوية بيانات تعريف XMP. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | استنساخ هذا المثال . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |

### أمثلة

يوضح المثال التالي كيفية تصدير تنسيق ملف APNG من تنسيق آخر متعدد الصفحات غير متحرك.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // إعداد مدة الإطار الافتراضية
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 مللي ثانية
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 مللي ثانية
}
```

يوضح المثال التالي كيفية التصدير إلى تنسيق ملف APNG.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // تصدير إلى رسوم متحركة APNG مع دورات رسوم متحركة غير محدودة كإعداد افتراضي
    image.Save("Animation1.webp.png", new ApngOptions());
    // إعداد دورات الرسوم المتحركة
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 دورات
}
```

يوضح المثال التالي كيفية إنشاء صورة APNG من صورة نقطية أخرى أحادية الصفحة.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 ثانية
const int FrameDuration = 70; // 70 مللي ثانية
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // من الممكن ضبط وقت الإطار الافتراضي للصورة هناك: apngImage.DefaultFrameTime = (uint) FrameDuration ;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // التنظيف لأن الصورة تحتوي على إطار واحد افتراضيًا
        apngImage.RemoveAllFrames();

        // إضافة الإطار الأول
        apngImage.AddFrame(sourceImage);

        // إضافة إطارات وسيطة
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // إضافة الإطار الأخير
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### أنظر أيضا

* class [PngOptions](../pngoptions)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
