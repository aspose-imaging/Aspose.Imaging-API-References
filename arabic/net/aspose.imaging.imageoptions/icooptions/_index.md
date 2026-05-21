---
title: "الفئة IcoOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageOptions.IcoOptions. أنشئ ملفات ICO مخصصة لأيقونات التطبيقات بسهولة باستخدام واجهتنا البرمجية التي تمكّنك من تمثيل برنامجك بسلاسة. تدعم واجهتنا إطارات صور PNG و BMP مع قيم مختلفة للبتات لكل بكسل، مما يضمن تنوعًا وتوافقًا لاحتياجات إنشاء الأيقونات الخاصة بك."
type: docs
weight: 10370
url: /ar/net/aspose.imaging.imageoptions/icooptions/
---
## IcoOptions class

أنشئ ملفات صورة ICO مخصصة لأيقونات التطبيقات بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا، مما يمكّنك من تمثيل برنامجك بسلاسة. تدعم واجهتنا إطارات صور PNG و BMP مع قيم مختلفة لعدد البتات لكل بكسل، مما يضمن تنوعًا وتوافقًا لاحتياجات إنشاء الأيقونات الخاصة بك.

```csharp
public class IcoOptions : ImageOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [IcoOptions](icooptions/#constructor)() | يُنشئ كائنًا جديدًا من الفئة `IcoOptions` مع تنسيق إطار ICO يساوي Png وbitsPerPixel يساوي 32. |
| [IcoOptions](icooptions/#constructor_1)(FileFormat, int) | يُنشئ كائنًا جديدًا من الفئة `IcoOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BitsPerPixel](../../aspose.imaging.imageoptions/icooptions/bitsperpixel/) { get; set; } | يحصل أو يعيّن قيمة البتات لكل بكسل. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| [Format](../../aspose.imaging.imageoptions/icooptions/format/) { get; set; } | يحصل أو يعيّن تنسيق إطار ICO. |
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
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين مثيل *metadata*، إذا كان مثيل [`Image`](../../aspose.imaging/image/) يدعم ويطبق مثيل [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |

### انظر أيضًا

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


