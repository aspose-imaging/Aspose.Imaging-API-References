---
title: "الفئة Html5CanvasOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageOptions.Html5CanvasOptions. أنشئ ملفات HTML5 Canvas بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا التي تتيح لك دمج العناصر مثل النماذج والنصوص والصور والرسوم المتحركة والروابط بسلاسة. استفد من ميزات قوية تشمل معرف العلامة وإعدادات الترميز لضمان الأداء الأمثل وتخصيص مشاريع الويب الخاصة بك"
type: docs
weight: 10360
url: /ar/net/aspose.imaging.imageoptions/html5canvasoptions/
---
## Html5CanvasOptions class

أنشئ ملفات HTML5 Canvas بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا، مما يتيح لك دمج العناصر مثل النماذج والنصوص والصور والرسوم المتحركة والروابط بسلاسة. استفد من ميزات قوية تشمل دعم معرف العلامة وإعدادات الترميز، لضمان أداء مثالي وتخصيص لمشاريع الويب الخاصة بك.

```csharp
public class Html5CanvasOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Html5CanvasOptions](html5canvasoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [CanvasTagId](../../aspose.imaging.imageoptions/html5canvasoptions/canvastagid/) { get; set; } | يحصل أو يعيّن معرف وسم الـ canvas. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [Encoding](../../aspose.imaging.imageoptions/html5canvasoptions/encoding/) { get; set; } | يسترجع أو يعيّن الترميز. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [FullHtmlPage](../../aspose.imaging.imageoptions/html5canvasoptions/fullhtmlpage/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب إنشاء صفحة HTML كاملة. |
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

يمكن استخدام أي صورة متجهة (SVG، WMF، CMX، إلخ) كمصدر لصور الـ Canvas الخاصة بك. الشيفرة التالية تنشئ صورة Canvas بسيطة.

```csharp
[C#]

using (var image = Image.Load(@"Sample.svg"))
{
    image.Save(@"Canvas.html", new Html5CanvasOptions
    {
        VectorRasterizationOptions = new SvgRasterizationOptions()
    });
}
```

يمكنك تضمين أكثر من صورة Canvas داخل صفحة HTML أو تحديث صفحة موجودة بالفعل. للقيام بذلك تحتاج إلى تصدير وسم الـ Canvas فقط.

```csharp
[C#]

using (var image = Image.Load(@"Sample.svg"))
{
    image.Save(@"Canvas.html", new Html5CanvasOptions
    {
        VectorRasterizationOptions = new SvgRasterizationOptions(),
        FullHtmlPage = false
    });
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


