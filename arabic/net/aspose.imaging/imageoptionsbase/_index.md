---
title: "الفئة ImageOptionsBase"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageOptionsBase. خيارات الصورة الأساسية"
type: docs
weight: 10690
url: /ar/net/aspose.imaging/imageoptionsbase/
---
## ImageOptionsBase class

خيارات قاعدة الصورة.

```csharp
public abstract class ImageOptionsBase : DisposableObject, ICloneable, IMetadataContainer
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان [full frame]. |
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
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين نسخة *metadata*، إذا كان هذا المثال [`Image`](../image/) يدعم ويطبق نسخة [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |

### انظر أيضًا

* class [DisposableObject](../disposableobject/)
* interface [IMetadataContainer](../imetadatacontainer/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


