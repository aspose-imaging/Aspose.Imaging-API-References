---
title: "الفئة CdrImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Cdr.CdrImage. واجهة برمجة التطبيقات (API) لدعم تنسيق الصورة المتجهة CorelDRAW CDR هي مجموعة أدوات أساسية للمطورين الذين يعملون مع الرسومات المتجهة. تتيح هذه الواجهة معالجة ملفات CDR بسلاسة، مما يسمح بتخزين وتعديل عناصر متنوعة مثل سطور النص، الأشكال، الصور، الألوان والتأثيرات. بفضل قدراتها الشاملة، يمكن للمطورين العمل بفعالية مع تمثيلات متجهة لمحتوى الصور، مما يضمن الدقة والمرونة في إنشاء وتحرير رسومات CorelDRAW المتجهة برمجياً."
type: docs
weight: 1470
url: /ar/net/aspose.imaging.fileformats.cdr/cdrimage/
---
## CdrImage class

واجهة برمجة التطبيقات لدعم تنسيق صورة CorelDRAW CDR المتجهة هي مجموعة أدوات أساسية للمطورين الذين يعملون مع الرسومات المتجهة. تمكّن هذه API من معالجة ملفات CDR بسلاسة، مما يسمح بتخزين وتعديل عناصر متنوعة مثل النصوص، الخطوط، الأشكال، الصور، الألوان، والتأثيرات. بفضل قدراتها الشاملة، يمكن للمطورين العمل بفعالية مع تمثيلات متجهة لمحتوى الصور، مما يضمن الدقة والمرونة في إنشاء وتحرير رسومات CorelDRAW المتجهة برمجيًا.

```csharp
public class CdrImage : VectorMultipageImage, ICdrImage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CdrImage](cdrimage/)(Stream, LoadOptions) | ابدأ العمل مع الفئة `CdrImage` بسهولة عن طريق تهيئة مثيل جديد باستخدام معلمات التدفق وloadOptions. مثالي للمطورين الذين يبحثون عن طريقة مريحة لتحميل صور CDR من مصادر بيانات مختلفة مع تخصيص عملية التحميل حسب الحاجة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.cdr/cdrimage/bitsperpixel/) { get; } | استرجع عمق البت للصورة بسهولة باستخدام هذه الخاصية السهلة الاستخدام. مثالي للمطورين الذين يرغبون في تحديد مستوى التفاصيل أو عمق اللون في صورهم، مما يضمن معالجة وتعديل دقيقة. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [CdrDocument](../../aspose.imaging.fileformats.cdr/cdrimage/cdrdocument/) { get; } | استرجع أو حدّث مستند CDR بسهولة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يرغبون في الوصول إلى مستند CDR أو تعديله، مما يضمن المرونة والكفاءة في تطبيقاتهم. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.cdr/cdrimage/fileformat/) { get; } | استرجع تنسيق ملف الصورة بسهولة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يرغبون في تحديد تنسيق صورهم بشكل ديناميكي، مما يضمن التوافق والمعالجة الدقيقة في تطبيقاتهم. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [Height](../../aspose.imaging.fileformats.cdr/cdrimage/height/) { get; } | الحصول على ارتفاع الصورة. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf/) { get; } | يحصل على ارتفاع الكائن، بالبوصة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging.fileformats.cdr/cdrimage/iscached/) { get; } | حدد بسهولة ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً، مما يلغي الحاجة لقراءة البيانات. مثالي للمطورين الذين يسعون لتحسين الأداء باستخدام البيانات المخزنة مؤقتاً بفعالية، مما يضمن وصولاً أسرع إلى معلومات الكائن. |
| override [Metadata](../../aspose.imaging/vectormultipageimage/metadata/) { get; } | يحصل على بيانات تعريف الصورة. |
| override [PageCount](../../aspose.imaging.fileformats.cdr/cdrimage/pagecount/) { get; } | استرجع أو حدّث عدد الصفحات الإجمالي للصورة بسهولة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يرغبون في إدارة الصور متعددة الصفحات بشكل ديناميكي، مما يضمن تنقلاً فعالاً وتعديل محتوى الصورة. |
| virtual [PageExportingAction](../../aspose.imaging/vectormultipageimage/pageexportingaction/) { get; set; } | يحصل أو يعيّن إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرةً قبل حفظ كل صفحة. |
| override [Pages](../../aspose.imaging.fileformats.cdr/cdrimage/pages/) { get; } | استرجع صفحات الصورة بسلاسة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يسعون للوصول إلى صفحات فردية داخل الصور متعددة الصفحات ومعالجتها، مما يضمن تنقلًا فعالًا ومعالجةً كفء. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | يحصل على حجم الكائن، بالبوصة. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| override [Width](../../aspose.imaging.fileformats.cdr/cdrimage/width/) { get; } | يحصل على عرض الصورة. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf/) { get; } | يحصل على عرض الكائن، بالبوصة. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.cdr/cdrimage/cachedata/)() | قم بتخزين البيانات مؤقتًا بسهولة لمنع التحميل الإضافي من المصدر الأساسي باستخدام هذه الطريقة سهلة الاستخدام. مثالي للمطورين الذين يرغبون في تحسين الأداء من خلال التحميل المسبق للبيانات، مما يضمن وصولًا أسرع وتشغيلًا أكثر سلاسة في تطبيقاتهم. [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| override [Crop](../../aspose.imaging/vectormultipageimage/crop/)(Rectangle) | يقص المستطيل المحدد. |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | قص الصورة مع إزاحات. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | يحصل على خيارات الصورة الافتراضية. |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages/)() | يحصل على الصور المضمنة. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.imaging/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [`Save`](../../aspose.imaging/image/save/) كمعامل ثاني. |
| override [GetSerializedStream](../../aspose.imaging/vectormultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| override [RemoveBackground](../../aspose.imaging/vectormultipageimage/removebackground/)() | يزيل الخلفية. |
| override [RemoveBackground](../../aspose.imaging/vectormultipageimage/removebackground/)(RemoveBackgroundSettings) | يزيل الخلفية. |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | يزيل البيانات الوصفية. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging/vectormultipageimage/resize/)(int, int, ImageResizeSettings) | تغيير حجم الصورة. |
| override [Resize](../../aspose.imaging/vectormultipageimage/resize/)(int, int, ResizeType) | تغيير حجم الصورة. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | يُعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [Rotate](../../aspose.imaging/vectormultipageimage/rotate/)(float) | دوّر الصورة حول المركز. |
| override [RotateFlip](../../aspose.imaging/vectormultipageimage/rotateflip/)(RotateFlipType) | يدور أو يقلب أو يدور ويقلب الصورة. |
| [Save](../../aspose.imaging/image/save/)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| override [Save](../../aspose.imaging/image/save/)(string) | يحفظ الصورة إلى موقع الملف المحدد. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [SetPalette](../../aspose.imaging.fileformats.cdr/cdrimage/setpalette/)(IColorPalette, bool) | خصص لوحة ألوان الصورة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تطبيق أنظمة ألوان محددة أو تعديلات بشكل ديناميكي، مما يضمن تحكمًا دقيقًا في المظهر البصري لصورهم. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |

## أمثلة

يوضح المثال التالي كيفية تخزين جميع صفحات صورة CDR مؤقتًا.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة من ملف CDR.
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // هذه العملية تخزن الصفحة الافتراضية فقط مؤقتًا.
    image.CacheData();

    // قم بتخزين جميع الصفحات مؤقتًا بحيث لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي.
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### انظر أيضًا

* class [Image](../../aspose.imaging/image/)
* interface [ICdrImage](../icdrimage/)
* class [VectorMultipageImage](../../aspose.imaging/vectormultipageimage/)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../aspose.imaging.fileformats.cdr/)
* assembly [Aspose.Imaging](../../)


