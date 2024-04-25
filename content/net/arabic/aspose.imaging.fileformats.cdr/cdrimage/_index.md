---
title: CdrImage
second_title: Aspose.Imaging لمرجع NET API
description: صورة مجلس الإنماء والإعمار .
type: docs
weight: 1420
url: /ar/aspose.imaging.fileformats.cdr/cdrimage/
---
## CdrImage class

صورة مجلس الإنماء والإعمار .

```csharp
public class CdrImage : VectorMultipageImage, ICdrImage
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [CdrImage](cdrimage)(Stream, LoadOptions) | يقوم بتهيئة مثيل جديد لملف[`CdrImage`](../cdrimage) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت لوحة الضبط التلقائي. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية . |
| override [BitsPerPixel](../../aspose.imaging.fileformats.cdr/cdrimage/bitsperpixel) { get; } | الحصول على عدد بتات الصورة لكل بكسل . |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | يحصل على حدود الصورة . |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [CdrDocument](../../aspose.imaging.fileformats.cdr/cdrimage/cdrdocument) { get; } | الحصول على مستند CDR أو تعيينه. |
| [Container](../../aspose.imaging/image/container) { get; } | يحصل على ملف[`Image`](../../aspose.imaging/image) حاوية . |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | يحصل على دفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| override [FileFormat](../../aspose.imaging.fileformats.cdr/cdrimage/fileformat) { get; } | يحصل على قيمة تنسيق الملف |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [Height](../../aspose.imaging.fileformats.cdr/cdrimage/height) { get; } | الحصول على ارتفاع الصورة . |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | الحصول على ارتفاع الكائن بالبوصة . |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | الحصول على أو تعيين شاشة المقاطعة. |
| override [IsCached](../../aspose.imaging.fileformats.cdr/cdrimage/iscached) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة بيانات. |
| override [PageCount](../../aspose.imaging.fileformats.cdr/cdrimage/pagecount) { get; } | الحصول على أو تعيين عدد الصفحات . |
| override [PageExportingAction](../../aspose.imaging.fileformats.cdr/cdrimage/pageexportingaction) { get; set; } | الحصول على إجراء تصدير الصفحة أو تعيينه . يرجى ملاحظة أن تعيين هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها قبل حفظ كل صفحة مباشرةً. |
| override [Pages](../../aspose.imaging.fileformats.cdr/cdrimage/pages) { get; } | الحصول على الصفحات . |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها. لا يتم استخدام لوحة الألوان عندما يتم تمثيل وحدات البكسل مباشرةً. |
| [Size](../../aspose.imaging/image/size) { get; } | يحصل على حجم الصورة . |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | الحصول على حجم الكائن بالبوصة . |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة الصور مستخدمة. |
| override [Width](../../aspose.imaging.fileformats.cdr/cdrimage/width) { get; } | الحصول على عرض الصورة . |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | الحصول على عرض الكائن بالبوصة . |

## طُرق

| اسم | وصف |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.cdr/cdrimage/cachedata)() | يخزن البيانات مؤقتًا ويضمن عدم إجراء تحميل بيانات إضافي من الملف الأساسي [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بتنسيق الملف المحدد الذي تم تمثيله بواسطة خيارات الحفظ التي تم تمريرها. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.cdr/cdrimage/getdefaultoptions)(object[]) | يحصل على الخيارات الافتراضية . |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages)() | الحصول على الصور المضمنة . |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | الحصول على الخيارات بناءً على إعدادات الملف الأصلية. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت والمعلمات الأخرى للصورة الأصلية دون تغيير . على سبيل المثال ، إذا قمنا بتحميل صورة PNG أبيض وأسود مع 1 بت لكل بكسل ثم احفظه باستخدام the [`Save`](../../aspose.imaging/datastreamsupporter/save) الطريقة ، سيتم إنتاج صورة PNG الناتجة بمعدل 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بمعدل 1 بت لكل بكسل ، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى[`Save`](../../aspose.imaging/image/save) الطريقة كمعامل ثاني. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | يغير حجم الصورة. الافتراضيNearestNeighbourResample يستخدم . |
| override [Resize](../../aspose.imaging.fileformats.cdr/cdrimage/resize#resize_1)(int, int, ImageResizeSettings) | يغير حجم الصورة. |
| override [Resize](../../aspose.imaging.fileformats.cdr/cdrimage/resize#resize_2)(int, int, ResizeType) | يغير حجم الصورة. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | يغير حجم الارتفاع بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | يغير حجم الارتفاع بشكل متناسب . |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | يغير حجم الارتفاع بشكل متناسب . |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | يغير حجم العرض بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | يغير حجم العرض بشكل متناسب . |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| override [RotateFlip](../../aspose.imaging.fileformats.cdr/cdrimage/rotateflip)(RotateFlipType) | يقوم بتدوير الصورة أو قلبها أو تدويرها وقلبها. |
| [Save](../../aspose.imaging/image/save)() | يحفظ بيانات الصورة في التدفق الأساسي. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | يحفظ بيانات الكائن في الدفق المحدد. |
| override [Save](../../aspose.imaging/image/save)(string) | يحفظ الصورة في موقع الملف المحدد. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | يحفظ بيانات الكائن في موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [SetPalette](../../aspose.imaging.fileformats.cdr/cdrimage/setpalette)(IColorPalette, bool) | يضبط لوحة الصور . |

### أمثلة

يوضح المثال التالي كيفية تخزين جميع صفحات صورة CDR مؤقتًا.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة من ملف CDR.
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // يخزن هذا الاستدعاء مؤقتًا الصفحة الافتراضية فقط.
    image.CacheData();

    // تخزين جميع الصفحات مؤقتًا بحيث لا يتم إجراء أي تحميل بيانات إضافية من دفق البيانات الأساسي.
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### أنظر أيضا

* class [Image](../../aspose.imaging/image)
* interface [ICdrImage](../icdrimage)
* class [VectorMultipageImage](../../aspose.imaging/vectormultipageimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Cdr](../../aspose.imaging.fileformats.cdr)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
