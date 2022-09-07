---
title: MetaImage
second_title: Aspose.Imaging لمرجع NET API
description: الفئة الأساسية لفئات كائن التعريف
type: docs
weight: 6510
url: /ar/net/aspose.imaging.fileformats.emf/metaimage/
---
## MetaImage class

الفئة الأساسية لفئات كائن التعريف

```csharp
public abstract class MetaImage : VectorImage
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت لوحة الضبط التلقائي. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية . |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel) { get; } | الحصول على عدد بتات الصورة لكل بكسل . |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | يحصل على حدود الصورة . |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [Container](../../aspose.imaging/image/container) { get; } | يحصل على ملف[`Image`](../../aspose.imaging/image) حاوية . |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | يحصل على دفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | يحصل على قيمة تنسيق الملف |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [Height](../../aspose.imaging/vectorimage/height) { get; } | الحصول على ارتفاع الصورة . |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | الحصول على ارتفاع الكائن بالبوصة . |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | الحصول على أو تعيين شاشة المقاطعة. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها. لا يتم استخدام لوحة الألوان عندما يتم تمثيل وحدات البكسل مباشرةً. |
| virtual [Records](../../aspose.imaging.fileformats.emf/metaimage/records) { get; set; } | الحصول على السجلات أو تعيينها. |
| [Size](../../aspose.imaging/image/size) { get; } | يحصل على حجم الصورة . |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | الحصول على حجم الكائن بالبوصة . |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة الصور مستخدمة. |
| override [Width](../../aspose.imaging/vectorimage/width) { get; } | الحصول على عرض الصورة . |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | الحصول على عرض الكائن بالبوصة . |

## طُرق

| اسم | وصف |
| --- | --- |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | يخزن البيانات ويضمن عدم إجراء أي تحميل إضافي للبيانات من الأساس[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بتنسيق الملف المحدد الذي تم تمثيله بواسطة خيارات الحفظ التي تم تمريرها. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop#crop)(Rectangle) | يقطع المستطيل المحدد . |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop#crop_1)(int, int, int, int) | اقتصاص الصورة مع التحولات . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | يحصل على الخيارات الافتراضية . |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | الحصول على الصور المضمنة . |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts)() | إرجاع قائمة الخطوط المستخدمة داخل ملف التعريف ولكن لم يتم العثور عليها. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | الحصول على الخيارات بناءً على إعدادات الملف الأصلية. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت والمعلمات الأخرى للصورة الأصلية دون تغيير . على سبيل المثال ، إذا قمنا بتحميل صورة PNG أبيض وأسود مع 1 بت لكل بكسل ثم احفظه باستخدام the [`Save`](../../aspose.imaging/datastreamsupporter/save) الطريقة ، سيتم إنتاج صورة PNG الناتجة بمعدل 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بمعدل 1 بت لكل بكسل ، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى[`Save`](../../aspose.imaging/image/save) الطريقة كمعامل ثاني. |
| abstract [GetUsedFonts](../../aspose.imaging.fileformats.emf/metaimage/getusedfonts)() | إرجاع قائمة الخطوط المستخدمة داخل ملف التعريف. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | يغير حجم الصورة. الافتراضيNearestNeighbourResample يستخدم . |
| abstract [Resize](../../aspose.imaging/image/resize)(int, int, ImageResizeSettings) | يغير حجم الصورة. |
| abstract [Resize](../../aspose.imaging/image/resize)(int, int, ResizeType) | يغير حجم الصورة. |
| abstract [ResizeCanvas](../../aspose.imaging.fileformats.emf/metaimage/resizecanvas)(Rectangle) | يغير حجم اللوحة . |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | يغير حجم الارتفاع بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | يغير حجم الارتفاع بشكل متناسب . |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | يغير حجم الارتفاع بشكل متناسب . |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | يغير حجم العرض بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | يغير حجم العرض بشكل متناسب . |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | يقوم بتدوير الصورة أو قلبها أو تدويرها وقلبها. |
| [Save](../../aspose.imaging/image/save)() | يحفظ بيانات الصورة في التدفق الأساسي. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | يحفظ بيانات الكائن في الدفق المحدد. |
| override [Save](../../aspose.imaging/image/save)(string) | يحفظ الصورة في موقع الملف المحدد. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | يحفظ بيانات الكائن في موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| abstract [SetPalette](../../aspose.imaging/image/setpalette)(IColorPalette, bool) | يضبط لوحة الصور . |

### أنظر أيضا

* class [VectorImage](../../aspose.imaging/vectorimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Emf](../../aspose.imaging.fileformats.emf)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
