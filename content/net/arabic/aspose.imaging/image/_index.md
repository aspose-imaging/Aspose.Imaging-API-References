---
title: Image
second_title: Aspose.Imaging لمرجع NET API
description: الصورة هي الفئة الأساسية لجميع أنواع الصور.
type: docs
weight: 9660
url: /ar/aspose.imaging/image/
---
## Image class

الصورة هي الفئة الأساسية لجميع أنواع الصور.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت لوحة الضبط التلقائي. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية . |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel) { get; } | الحصول على عدد بتات الصورة لكل بكسل . |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | يحصل على حدود الصورة . |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [Container](../../aspose.imaging/image/container) { get; } | يحصل على ملف[`Image`](../image) حاوية . |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | يحصل على دفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | يحصل على قيمة تنسيق الملف |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| abstract [Height](../../aspose.imaging/image/height) { get; } | الحصول على ارتفاع الصورة . |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | الحصول على أو تعيين شاشة المقاطعة. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها. لا يتم استخدام لوحة الألوان عندما يتم تمثيل وحدات البكسل مباشرةً. |
| [Size](../../aspose.imaging/image/size) { get; } | يحصل على حجم الصورة . |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة الصور مستخدمة. |
| abstract [Width](../../aspose.imaging/image/width) { get; } | الحصول على عرض الصورة . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Create](../../aspose.imaging/image/create#create_1)(Image[]) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| static [Create](../../aspose.imaging/image/create#create_2)(Image[], bool) | ينشئ صورة جديدة الصور المحددة كصفحات . |
| static [Create](../../aspose.imaging/image/create#create)(ImageOptionsBase, int, int) | لإنشاء صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| static [Load](../../aspose.imaging/image/load#load)(Stream) | يتم تحميل صورة جديدة من التدفق المحدد. |
| static [Load](../../aspose.imaging/image/load#load_2)(string) | يقوم بتحميل صورة جديدة من الملف المحدد. |
| static [Load](../../aspose.imaging/image/load#load_1)(Stream, LoadOptions) | يتم تحميل صورة جديدة من التدفق المحدد. |
| static [Load](../../aspose.imaging/image/load#load_3)(string, LoadOptions) | يقوم بتحميل صورة جديدة من الملف المحدد. |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | يخزن البيانات ويضمن عدم إجراء أي تحميل إضافي للبيانات من الأساس[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بتنسيق الملف المحدد الذي تم تمثيله بواسطة خيارات الحفظ التي تم تمريرها. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | يحصل على الخيارات الافتراضية . |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | الحصول على الخيارات بناءً على إعدادات الملف الأصلية. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت والمعلمات الأخرى للصورة الأصلية دون تغيير . على سبيل المثال ، إذا قمنا بتحميل صورة PNG أبيض وأسود مع 1 بت لكل بكسل ثم احفظه باستخدام the [`Save`](../datastreamsupporter/save) الطريقة ، سيتم إنتاج صورة PNG الناتجة بمعدل 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بمعدل 1 بت لكل بكسل ، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى[`Save`](./save) الطريقة كمعامل ثاني. |
| [Resize](../../aspose.imaging/image/resize#resize)(int, int) | يغير حجم الصورة. الافتراضيNearestNeighbourResample يستخدم . |
| abstract [Resize](../../aspose.imaging/image/resize#resize_1)(int, int, ImageResizeSettings) | يغير حجم الصورة. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_2)(int, int, ResizeType) | يغير حجم الصورة. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally)(int) | يغير حجم الارتفاع بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | يغير حجم الارتفاع بشكل متناسب . |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | يغير حجم الارتفاع بشكل متناسب . |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally)(int) | يغير حجم العرض بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | يغير حجم العرض بشكل متناسب . |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | يقوم بتدوير الصورة أو قلبها أو تدويرها وقلبها. |
| [Save](../../aspose.imaging/image/save#save)() | يحفظ بيانات الصورة في التدفق الأساسي. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | يحفظ بيانات الكائن في الدفق المحدد. |
| override [Save](../../aspose.imaging/image/save#save_4)(string) | يحفظ الصورة في موقع الملف المحدد. |
| [Save](../../aspose.imaging/image/save#save_2)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | يحفظ بيانات الكائن في موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/image/save#save_5)(string, ImageOptionsBase) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save#save_3)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save#save_6)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| abstract [SetPalette](../../aspose.imaging/image/setpalette)(IColorPalette, bool) | يضبط لوحة الصور . |
| static [CanLoad](../../aspose.imaging/image/canload#canload)(Stream) | يحدد ما إذا كان يمكن تحميل الصورة من التدفق المحدد. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_2)(string) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_1)(Stream, LoadOptions) | لتحديد ما إذا كان يمكن تحميل الصورة من التدفق المحدد واختيارياً باستخدام المحدد*loadOptions* . |
| static [CanLoad](../../aspose.imaging/image/canload#canload_3)(string, LoadOptions) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واختيارياً باستخدام خيارات الفتح المحددة. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat)(Stream) | يحصل على تنسيق الملف. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat_1)(string) | يحصل على تنسيق الملف. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle)(Rectangle, int, int) | يحصل على مستطيل يناسب الصورة الحالية. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle_1)(Rectangle, int[], int, int) | يحصل على مستطيل يناسب الصورة الحالية. |
| static [GetProportionalHeight](../../aspose.imaging/image/getproportionalheight)(int, int, int) | الحصول على ارتفاع نسبي . |
| static [GetProportionalWidth](../../aspose.imaging/image/getproportionalwidth)(int, int, int) | الحصول على عرض نسبي . |

### أمثلة

حدد ما إذا كانت الصورة تستخدم اللوحة.

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.UsePalette)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

تغيير حجم الصورة باستخدام نوع معين من تغيير الحجم.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

يقوم هذا المثال بإنشاء ملف صورة جديد في موقع ما على القرص كما هو محدد بواسطة خاصية المصدر لمثيل BmpOptions. يتم تعيين العديد من الخصائص لمثيل BmpOptions قبل إنشاء الصورة الفعلية. خاصة خاصية المصدر ، التي تشير إلى موقع القرص الفعلي في هذه الحالة.

```csharp
[C#]

// قم بإنشاء مثيل لـ BmpOptions وقم بتعيين خصائصه المختلفة
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

// قم بإنشاء مثيل لـ FileCreateSource وقم بتعيينه كمصدر لمثيل BmpOptions
// تحدد المعلمة المنطقية الثانية ما إذا كان الملف المراد إنشاؤه ثابتًا أم لا
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

// قم بإنشاء مثيل للصورة وقم بتهيئته باستخدام مثيل BmpOptions عن طريق استدعاء طريقة الإنشاء
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // القيام ببعض معالجة الصور

    // احفظ جميع التغييرات
    image.Save();
}
```

### أنظر أيضا

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* مساحة الاسم [Aspose.Imaging](../../aspose.imaging)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
