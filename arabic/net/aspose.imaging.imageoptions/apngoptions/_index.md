---
title: "الفئة ApngOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.ImageOptions.ApngOptions الفئة. واجهة برمجة التطبيقات (API) لإنشاء تنسيق ملف صورة متحركة Animated PNG (Animated Portable Network Graphics) هي أداة ديناميكية للمطورين الذين يسعون لإنشاء صور متحركة جذابة. مع خيارات قابلة للتخصيص مثل مدة الإطار وعدد مرات تكرار الحلقة، تتيح هذه الواجهة ضبط المحتوى المتحرك وفقًا للاحتياجات المحددة. سواءً كنت تنشئ رسومات ويب جذابة أو مرئيات تفاعلية، يمكنك الاستفادة من هذه الواجهة لدمج صور APNG بسلاسة مع تحكم دقيق في معلمات الرسوم المتحركة"
type: docs
weight: 10230
url: /ar/net/aspose.imaging.imageoptions/apngoptions/
---
## ApngOptions class

واجهة برمجة التطبيقات لإنشاء صيغة ملف صورة Animated PNG (Animated Portable Network Graphics) هي أداة ديناميكية للمطورين الذين يسعون لتوليد صور متحركة جذابة. مع خيارات قابلة للتخصيص مثل مدة الإطار وعدد مرات التكرار، تتيح هذه الواجهة ضبط المحتوى المتحرك وفقًا للاحتياجات المحددة. سواءً كنت تنشئ رسومات ويب جذابة أو مرئيات تفاعلية، يمكنك الاستفادة من هذه الواجهة لدمج صور APNG بسلاسة مع تحكم دقيق في معلمات الرسوم المتحركة.

```csharp
public class ApngOptions : PngOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ApngOptions](apngoptions/)() | يُنشئ مثلاً جديدًا من الفئة `ApngOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth/) { get; set; } | يحصل أو يعيّن قيم عمق البت في النطاق 1، 2، 4، 8، 16. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype/) { get; set; } | يحصل أو يضبط نوع اللون. |
| [DefaultFrameTime](../../aspose.imaging.imageoptions/apngoptions/defaultframetime/) { get; set; } | يحصل أو يعيّن مدة الإطار الافتراضية. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype/) { get; set; } | يحصل أو يعيّن نوع الفلتر المستخدم أثناء عملية حفظ ملف png. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| [NumPlays](../../aspose.imaging.imageoptions/apngoptions/numplays/) { get; set; } | يحصل أو يعيّن عدد مرات تكرار الرسوم المتحركة. 0 تشير إلى تكرار لا نهائي. |
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

## أمثلة

المثال التالي يوضح كيفية تصدير تنسيق ملف apng APNG من تنسيق متعدد الصفحات غير متحرك آخر.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // إعداد مدة الإطار الافتراضية
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

المثال التالي يوضح كيفية التصدير إلى تنسيق ملف APNG.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // تصدير إلى رسوم متحركة بصيغة APNG مع دورات رسوم متحركة غير محدودة كإعداد افتراضي
    image.Save("Animation1.webp.png", new ApngOptions());
    // إعداد دورات الرسوم المتحركة
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 cycles
}
```

يوضح المثال التالي كيفية إنشاء صورة APNG من صورة نقطية صفحة واحدة أخرى.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 s
const int FrameDuration = 70; // 70 ms
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
        // يمكن تعيين الوقت الافتراضي لإطار الصورة هناك: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // جارٍ التنظيف لأن الصورة تحتوي على إطار واحد افتراضيًا
        apngImage.RemoveAllFrames();

        // إضافة الإطار الأول
        apngImage.AddFrame(sourceImage);

        // إضافة إطارات وسطية
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

### انظر أيضًا

* class [PngOptions](../pngoptions/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


