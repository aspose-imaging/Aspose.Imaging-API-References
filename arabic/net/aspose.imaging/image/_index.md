---
title: "الفئة Image"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Image. الصورة هي الفئة الأساسية لجميع أنواع الصور"
type: docs
weight: 9860
url: /ar/net/aspose.imaging/image/
---
## Image class

الصورة هي الفئة الأساسية لجميع أنواع الصور.

```csharp
public abstract class Image : DataStreamSupporter, IMetadataContainer, IObjectWithBounds
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel/) { get; } | الحصول على عدد البتات لكل بكسل في الصورة. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | يحصل على حاوية `Image`. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat/) { get; } | يحصل على قيمة تنسيق الملف |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| abstract [Height](../../aspose.imaging/image/height/) { get; } | الحصول على ارتفاع الصورة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | يحصل على بيانات تعريف الصورة. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| abstract [Width](../../aspose.imaging/image/width/) { get; } | يحصل على عرض الصورة. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.imaging/image/create/#create_3)(Image[]) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| static [Create](../../aspose.imaging/image/create/#create)(MultipageCreateOptions) | ينشئ خيارات الإنشاء المتعددة الصفحات المحددة. |
| static [Create](../../aspose.imaging/image/create/#create_5)(string[]) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة. |
| static [Create](../../aspose.imaging/image/create/#create_4)(Image[], bool) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| static [Create](../../aspose.imaging/image/create/#create_6)(string[], bool) | ينشئ الصورة المتعددة الصفحات التي تحتوي على الملفات المحددة. |
| static [Create](../../aspose.imaging/image/create/#create_1)(ImageOptionsBase, int, int) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| static [Create](../../aspose.imaging/image/create/#create_2)(ImageOptionsBase, int, int, int[]) | ينشئ كائنًا من نوع [`RasterImage`](../rasterimage/) من مصفوفة البكسلات المقدمة. يتحقق من أن العرض والارتفاع المحددين يتطابقان مع أبعاد بيانات البكسل. لا يمكن استخدام هذه الطريقة إلا عندما تكون المكتبة في وضع الترخيص. |
| static [Load](../../aspose.imaging/image/load/#load)(Stream) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| static [Load](../../aspose.imaging/image/load/#load_2)(string) | يقوم بتحميل صورة جديدة من مسار الملف أو عنوان URL المحدد. إذا كان *filePath* مسار ملف، فإن الطريقة تفتح الملف فقط. إذا كان *filePath* عنوان URL، فإن الطريقة تقوم بتنزيل الملف، وتخزينه مؤقتًا، ثم فتحه. |
| static [Load](../../aspose.imaging/image/load/#load_1)(Stream, LoadOptions) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| static [Load](../../aspose.imaging/image/load/#load_3)(string, LoadOptions) | يقوم بتحميل صورة جديدة من مسار الملف أو عنوان URL المحدد. إذا كان *filePath* مسار ملف، فإن الطريقة تفتح الملف فقط. إذا كان *filePath* عنوان URL، فإن الطريقة تقوم بتنزيل الملف، وتخزينه مؤقتًا، ثم فتحه. |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) الأساسي. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| virtual [Crop](../../aspose.imaging/image/crop/#crop)(Rectangle) | يقص المستطيل المحدد. |
| virtual [Crop](../../aspose.imaging/image/crop/#crop_1)(int, int, int, int) | قص الصورة مع إزاحات. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون ذلك مفيدًا للحفاظ على عمق اللون وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [`Save`](./save/) كمعامل ثانٍ. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | يزيل البيانات الوصفية. |
| [Resize](../../aspose.imaging/image/resize/#resize)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| abstract [Resize](../../aspose.imaging/image/resize/#resize_1)(int, int, ImageResizeSettings) | تغيير حجم الصورة. |
| virtual [Resize](../../aspose.imaging/image/resize/#resize_2)(int, int, ResizeType) | تغيير حجم الصورة. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/#resizeheightproportionally)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | يُعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/#resizewidthproportionally)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| virtual [Rotate](../../aspose.imaging/image/rotate/)(float) | دوّر الصورة حول المركز. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip/)(RotateFlipType) | يدور أو يقلب أو يدور ويقلب الصورة. |
| [Save](../../aspose.imaging/image/save/#save)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| override [Save](../../aspose.imaging/image/save/#save_4)(string) | يحفظ الصورة إلى موقع الملف المحدد. |
| [Save](../../aspose.imaging/image/save/#save_2)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/image/save/#save_5)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save/#save_6)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| abstract [SetPalette](../../aspose.imaging/image/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان كائن `Image` هذا يدعم وينفذ النوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |
| static [CanLoad](../../aspose.imaging/image/canload/#canload)(Stream) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| static [CanLoad](../../aspose.imaging/image/canload/#canload_2)(string) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| static [CanLoad](../../aspose.imaging/image/canload/#canload_1)(Stream, LoadOptions) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واختيارياً باستخدام *loadOptions* المحددة. |
| static [CanLoad](../../aspose.imaging/image/canload/#canload_3)(string, LoadOptions) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واختيارياً باستخدام خيارات الفتح المحددة. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat/#getfileformat)(Stream) | يحصل على تنسيق الملف. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat/#getfileformat_1)(string) | يحصل على تنسيق الملف. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle/#getfittingrectangle)(Rectangle, int, int) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle/#getfittingrectangle_1)(Rectangle, int[], int, int) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| static [GetProportionalHeight](../../aspose.imaging/image/getproportionalheight/)(int, int, int) | يحصل على ارتفاع نسبي. |
| static [GetProportionalWidth](../../aspose.imaging/image/getproportionalwidth/)(int, int, int) | يحصل على عرض نسبي. |

## أمثلة

تحديد ما إذا كانت اللوحة مستخدمة من قبل الصورة.

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

تغيير حجم الصورة باستخدام نوع التحجيم المحدد.

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

هذا المثال ينشئ ملف صورة جديد في موقع على القرص كما هو محدد بواسطة خاصية Source لكائن BmpOptions. يتم تعيين عدة خصائص لكائن BmpOptions قبل إنشاء الصورة الفعلية. خاصةً خاصية Source التي تشير إلى موقع القرص الفعلي في هذه الحالة.

```csharp
[C#]

//أنشئ مثيلاً من BmpOptions وعيّن خصائصه المتنوعة
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//أنشئ مثيلاً من FileCreateSource وعيّنها كمصدر للمثيل من BmpOptions
//المعامل المنطقي الثاني يحدد ما إذا كان الملف الذي سيُنشأ مؤقتًا أم لا
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//إنشاء كائن من نوع Image وتهيئته بكائن BmpOptions عن طريق استدعاء طريقة Create.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //قم ببعض معالجة الصورة.

    // احفظ جميع التغييرات.
    image.Save();
}
```

### انظر أيضًا

* class [DataStreamSupporter](../datastreamsupporter/)
* interface [IObjectWithBounds](../iobjectwithbounds/)
* interface [IMetadataContainer](../imetadatacontainer/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


