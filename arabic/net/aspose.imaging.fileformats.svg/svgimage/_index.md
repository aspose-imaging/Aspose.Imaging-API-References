---
title: "فئة SvgImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.FileFormats.Svg.SvgImage. تعامل مع ملفات صور SVG (Scalar Vector Graphics) باستخدام API الخاص بنا مستفيدًا من قوة تنسيق النص القائم على XML لتخصيص سلس وقابلية التوسع. حمّل صور SVG بسهولة، حول العناصر المتجهة إلى نقطية، وحوّلها إلى صيغ أخرى مع التحكم في مستويات الضغط لتحسين حجم الملف والجودة لمشاريعك"
type: docs
weight: 7660
url: /ar/net/aspose.imaging.fileformats.svg/svgimage/
---
## SvgImage class

تفاعل مع ملفات رسومات المتجهات القابلة للقياس (SVG) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مستفيدًا من قوة تنسيق النص القائم على XML للتخصيص السلس والقابلية للتوسع. قم بتحميل صور SVG بسهولة، وتحويل العناصر المتجهية إلى نقطية، وتحويلها إلى تنسيقات أخرى، مع التحكم في مستويات الضغط لتحسين حجم الملف وجودته لمشاريعك.

```csharp
public sealed class SvgImage : VectorImage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SvgImage](svgimage/#constructor_2)(Stream) | ينشئ مثيلًا جديدًا من فئة `SvgImage`، محملاً الصورة من الدفق المقدم. يتيح هذا المُنشئ تحميل صور SVG مباشرةً من الدفقات، مما يعزز المرونة والكفاءة في معالجة موارد الصور داخل تطبيقات البرمجيات. |
| [SvgImage](svgimage/#constructor_3)(string) | ينشئ كائنًا جديدًا من فئة `SvgImage`، باستخدام المسار المحدد لتحديد موقع الصورة وتحميلها. يسهل هذا المُنشئ إنشاء مثيلات صور SVG من ملفات خارجية، مما يتيح دمجًا سلسًا في أنظمة البرمجيات وتدفقات العمل. |
| [SvgImage](svgimage/#constructor_1)(int, int) | ينشئ كائن `SvgImage` جديد بالأبعاد المحددة للعرض والارتفاع. يتيح هذا المُنشئ للمطورين إنشاء صور SVG بأبعاد مسبقة التعريف، مما يسهل التحكم الدقيق في حجم الصورة أثناء التهيئة. |
| [SvgImage](svgimage/#constructor)(SvgOptions, int, int) | ينشئ مثيلًا جديدًا من فئة `SvgImage` مع خيارات SVG المحددة، وعرض الصورة، ومعلمات الارتفاع. يتيح هذا المُنشئ للمطورين تهيئة صور SVG بخيارات وأبعاد مخصصة، مما يوفر مرونة في إدارة محتوى SVG وتخطيطه. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.svg/svgimage/bitsperpixel/) { get; } | يسترجع عدد البتات لكل بكسل في الصورة. من المهم ملاحظة أن هذا المعامل غير قابل للتطبيق على الصور المتجهية، لأنها لا تُقاس بالبكسل. توفر هذه الخاصية معلومات حيوية حول عمق ألوان الصورة، مما يساعد في مهام المعالجة والتلاعب. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.svg/svgimage/fileformat/) { get; } | يسترجع تنسيق ملف الصورة، موفرًا بيانات تعريفية أساسية للمعالجة وفحوصات التوافق. تُعد هذه الخاصية أساسية في تحديد استراتيجيات الترميز وفك الترميز المناسبة للتعامل مع بيانات الصورة بفعالية عبر الأنظمة والتطبيقات المختلفة. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [Height](../../aspose.imaging/vectorimage/height/) { get; } | الحصول على ارتفاع الصورة. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf/) { get; } | يحصل على ارتفاع الكائن، بالبوصة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging.fileformats.svg/svgimage/iscached/) { get; } | يسترجع قيمة منطقية تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى عمليات قراءة إضافية للبيانات. توفر هذه الخاصية نظرة على حالة التخزين المؤقت الحالية، مما يُحسّن عمليات استرجاع البيانات وسير عمل المعالجة لأداء وكفاءة أعلى. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | يحصل على بيانات تعريف الصورة. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | يحصل على حجم الكائن، بالبوصة. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| override [Width](../../aspose.imaging/vectorimage/width/) { get; } | يحصل على عرض الصورة. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf/) { get; } | يحصل على عرض الكائن، بالبوصة. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.svg/svgimage/cachedata/)() | قم بتخزين البيانات مؤقتًا وتأكد من عدم تحميل أي بيانات إضافية من الكائن الأساسي [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/). تعزز هذه التحسينات الأداء عن طريق القضاء على عمليات استرجاع البيانات المتكررة، وهو أمر مفيد بشكل خاص في السيناريوهات التي تتطلب وصولًا متكررًا إلى بيانات الصورة. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| override [Crop](../../aspose.imaging.fileformats.svg/svgimage/crop/#crop)(Rectangle) | يقص المستطيل المحدد. |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | قص الصورة مع إزاحات. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | يحصل على خيارات الصورة الافتراضية. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages/)() | يحصل على الصور المضمنة. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.imaging/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [`Save`](../../aspose.imaging/image/save/) كمعامل ثاني. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)() | يزيل الخلفية. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)(RemoveBackgroundSettings) | يزيل الخلفية. |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | يزيل البيانات الوصفية. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ImageResizeSettings) | يعيد تحجيم الصورة باستخدام خيارات موسعة. |
| override [Resize](../../aspose.imaging.fileformats.svg/svgimage/resize/#resize_2)(int, int, ResizeType) | قم بتغيير حجم الصورة لتتناسب مع الأبعاد المحددة مع الحفاظ على نسبة العرض إلى الارتفاع. توفر هذه الطريقة وسيلة مريحة لضبط حجم الصورة دون تشويه نسبها، مما يضمن عرضًا أو تخزينًا مثاليًا وفقًا للأبعاد المطلوبة. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | يُعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [Rotate](../../aspose.imaging.fileformats.svg/svgimage/rotate/)(float) | دوّر الصورة حول المركز. |
| override [RotateFlip](../../aspose.imaging/vectorimage/rotateflip/)(RotateFlipType) | يدور أو يقلب أو يدور ويقلب الصورة. |
| [Save](../../aspose.imaging/image/save/)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| override [Save](../../aspose.imaging/image/save/)(string) | يحفظ الصورة إلى موقع الملف المحدد. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [SetPalette](../../aspose.imaging.fileformats.svg/svgimage/setpalette/)(IColorPalette, bool) | يطبق لوحة ألوان محددة على الصورة، مما يتيح تخصيص مخططات الألوان لأغراض جمالية أو وظيفية. توفر هذه الطريقة مرونة في إدارة لوحات الألوان لتلبية متطلبات التصميم أو التطبيق المختلفة. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |

## أمثلة

المثال التالي يوضح كيفية تحويل صور svgz إلى صيغة svg.

```csharp
[C#]

string file = "example.svgz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svg";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

المثال التالي يوضح كيفية تحويل صور svg إلى صيغة svgz.

```csharp
[C#]

string file = "juanmontoya_lingerie.svg";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svgz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

يوضح هذا المثال كيفية تحميل صورة SVG من تدفق ملف وتحويلها إلى PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة SVG من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.svg"))
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = new Aspose.Imaging.FileFormats.Svg.SvgImage(stream))
{
    // من أجل تحويل SVG إلى نقطية نحتاج إلى تحديد خيارات التحويل النقطي.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

المثال التالي يوضح كيفية تحويل الصور المضغوطة (*.emz,*.wmz, *.svgz) إلى صيغة نقطية.

```csharp
[C#]

string[] files = new[] {"example.emz", "example.wmz", "example.svgz"};
string baseFolder = System.IO.Path.Combine("D:","Compressed");
foreach (var file in files)
{
    string inputFile = System.IO.Path.Combine(baseFolder, file);
    string outFile = inputFile + ".png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
    {
        Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Color.White, image.Width, image.Height });
        image.Save(outFile, new Aspose.Imaging.ImageOptions.PngOptions(){VectorRasterizationOptions = vectorRasterizationOptions});
    }
}
```

### انظر أيضًا

* class [VectorImage](../../aspose.imaging/vectorimage/)
* namespace [Aspose.Imaging.FileFormats.Svg](../../aspose.imaging.fileformats.svg/)
* assembly [Aspose.Imaging](../../)


