---
title: "الفئة DxfOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageOptions.DxfOptions. واجهة برمجة التطبيقات لإنشاء صور متجهة بصيغة Drawing Interchange Format DXF تقدم حلولاً مخصصة لتوليد ملفات رسومات AutoCAD بدقة ومرونة. صُممت خصيصًا للعمل مع خطوط النص ومنحنيات بيزيه حيث يمكن للمطورين معالجة هذه العناصر بكفاءة، حساب نقاط بيزيه وتحويل المنحنيات إلى خطوط متعددة النقاط لتصدير سلس يضمن التوافق والوفاء في صور DXF المتجهة"
type: docs
weight: 10310
url: /ar/net/aspose.imaging.imageoptions/dxfoptions/
---
## DxfOptions class

واجهة برمجة التطبيقات لإنشاء صور متجهية بصيغة Drawing Interchange Format (DXF) تقدم حلولًا مخصصة لتوليد ملفات رسومات AutoCAD بدقة ومرونة. صُممت خصيصًا للعمل مع خطوط النص ومنحنيات بيزيه، يمكن للمطورين معالجة هذه العناصر بفعالية، عد نقاط بيزيه، وتحويل المنحنيات إلى خطوط متعددة النقاط لتصدير سلس، مما يضمن التوافق والدقة في صور DXF المتجهية.

```csharp
public class DxfOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DxfOptions](dxfoptions/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BezierPointCount](../../aspose.imaging.imageoptions/dxfoptions/bezierpointcount/) { get; set; } | عدد النقاط التي يجب توليدها عند تحويل منحنيات بيزيه إلى خطوط متعددة النقاط، الحد الأدنى 4. يُستخدم عندما  و  كلاهما /// مضبوط إلى `true` |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [ConvertTextBeziers](../../aspose.imaging.imageoptions/dxfoptions/converttextbeziers/) { get; set; } | يعمل عندما يتم ضبط  إلى `true`. ما إذا كان سيتم تحويل منحنيات بيزيه في حدود النص إلى خطوط متعددة النقاط. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | خيارات الصفحات المتعددة |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | يحصل أو يضبط لوحة الألوان. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | يحصل أو يضبط معالج حدث التقدم. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | يحصل أو يضبط إعدادات الدقة. |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [TextAsLines](../../aspose.imaging.imageoptions/dxfoptions/textaslines/) { get; set; } | ما إذا كان يجب تصدير النص كحدود تتكون من خطوط متعددة النقاط (افتراضي) أو ككيانات TEXT قابلة للتحرير في AutoCAD. إذا تم ضبط هذا الخيار |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | يحصل أو يضبط حاوية بيانات تعريف XMP. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | ينشئ نسخة عضوية من هذه الحالة. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين مثيل *metadata*، إذا كان مثيل [`Image`](../../aspose.imaging/image/) يدعم ويطبق مثيل [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |

## أمثلة

يوضح هذا المثال تصديرًا إلى تنسيق Dxf

```csharp
[C#]

//إنشاء كائن Image وتهيئته بملف صورة موجود من موقع القرص
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"input.svg"))
{
    Aspose.Imaging.ImageOptions.DxfOptions options = new Aspose.Imaging.ImageOptions.DxfOptions();
    options.TextAsLines = true;
    options.ConvertTextBeziers = true;
    options.BezierPointCount = 20;
    image.Save("output.dxf", options);
}
```

### انظر أيضًا

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


