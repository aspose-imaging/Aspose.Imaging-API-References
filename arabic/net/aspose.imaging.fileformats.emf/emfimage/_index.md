---
title: "الفئة EmfImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.EmfImage. واجهة برمجة التطبيقات لتنسيق Enhanced Metafile Format (EMF) لدعم صور المتجه هي أداة شاملة لمعالجة الصور الرسومية بطريقة غير معتمدة على الجهاز مع الحفاظ على خصائصها الأصلية. تم تطويرها للحفاظ على النسب والأبعاد والألوان وغيرها من سمات الرسوم، وتضم دعم تنسيق EMF Plus وميزات لقص المناطق، وتحجيم اللوحة والصور، وتدويرها، وعكسها، وتعيين لوحات ألوان الصور، وتصدير واستيراد إلى سياق جهاز APS، وضغط وتحويل EMF إلى صيغ أخرى، مما يضمن معالجة متعددة الاستخدامات وتكاملًا سلسًا لصور EMF عبر التطبيقات"
type: docs
weight: 4790
url: /ar/net/aspose.imaging.fileformats.emf/emfimage/
---
## EmfImage class

واجهة برمجة التطبيقات لدعم تنسيق الصورة المتجهية Enhanced Metafile Format (EMF) هي أداة شاملة لمعالجة الصور الرسومية بطريقة غير معتمدة على الجهاز مع الحفاظ على خصائصها الأصلية. تم تطويرها للحفاظ على النسب والأبعاد والألوان وغيرها من سمات الرسوم، وتضم دعم تنسيق EMF Plus وميزات لقص المناطق، تغيير حجم اللوحة والصور، التدوير، العكس، ضبط لوحات ألوان الصور، التصدير والاستيراد إلى سياق جهاز APS، الضغط وتحويل EMF إلى تنسيقات أخرى، مما يضمن معالجة متعددة الاستخدامات وتكامل سلس لصور EMF عبر التطبيقات.

```csharp
public sealed class EmfImage : MetaImage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfImage](emfimage/#constructor)() | ابدأ العمل مع صور EMF بإنشاء مثيل جديد من الفئة `EmfImage`. مثالي لإدراج صور EMF بسرعة في مشاريعك بسهولة وكفاءة. |
| [EmfImage](emfimage/#constructor_1)(int, int) | أنشئ مثيلًا جديدًا من الفئة `EmfImage` عن طريق تحديد معلمات العرض والارتفاع. يبسط هذا المُنشئ عملية إنشاء صور EMF بأبعاد محددة، مما يعزز كفاءة سير عمل التطوير الخاص بك. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.emf/emfimage/bitsperpixel/) { get; } | استرجع عدد البتات لكل بكسل الخاص بالصور النقطية، حيث لا ينطبق هذا المعامل على الصور المتجهية. حدد بسرعة عمق البكسل للصور النقطية لتحليل ومعالجة دقيقة، مما يضمن التعامل الصحيح مع بيانات الصورة. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.emf/emfimage/fileformat/) { get; } | الوصول إلى قيمة تنسيق الملف المرتبط بالكائن. حدد بسهولة تنسيق الملف المرتبط بالكائن لتسهيل المعالجة وفحوصات التوافق. بسط سير عملك باسترجاع معلومات تنسيق الملف بسهولة. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| [Header](../../aspose.imaging.fileformats.emf/emfimage/header/) { get; set; } | استرجع أو عدل سجل رأس ملف الميتا EMF باستخدام هذه الخاصية. مثالي لإدارة بيانات ملف الميتا بكفاءة داخل تطبيقك. حسّن سير عملك من خلال وصول مبسط إلى معلومات رأس ملف الميتا. |
| override [Height](../../aspose.imaging/vectorimage/height/) { get; } | الحصول على ارتفاع الصورة. |
| override [HeightF](../../aspose.imaging.fileformats.emf/emfimage/heightf/) { get; } | استرجع ارتفاع الصورة، مما يسهل العرض الدقيق وتعديل التخطيط. يضمن الوصول إلى خاصية الارتفاع التوافق والتكامل السلس عبر مختلف المنصات والتطبيقات. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging.fileformats.emf/emfimage/iscached/) { get; } | الوصول إلى قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة بيانات إضافية. عزّز الكفاءة من خلال تحديد سريع ما إذا كانت البيانات المخزنة متاحة للوصول الفوري. حسّن سير عملك بعمليات استرجاع بيانات مبسطة. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | يحصل على بيانات تعريف الصورة. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| override [Records](../../aspose.imaging.fileformats.emf/emfimage/records/) { get; set; } | استرجع أو عدل السجلات المرتبطة بالكائن. وصول وإدارة فعّالة لمجموعة السجلات لتحسين معالجة البيانات وتعديلها. حسّن سير عملك من خلال التفاعل السلس مع سجلات الكائن. |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | يحصل على حجم الكائن، بالبوصة. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| override [Width](../../aspose.imaging/vectorimage/width/) { get; } | يحصل على عرض الصورة. |
| override [WidthF](../../aspose.imaging.fileformats.emf/emfimage/widthf/) { get; } | الوصول إلى عرض الصورة، مما يوفر معلومات أساسية للتصيير الدقيق والمعالجة. استرجع عرض الصورة بسرعة لضمان التوافق والتخطيط السليم داخل التطبيقات والمنصات المختلفة. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.emf/emfimage/cachedata/)() | قم بتخزين البيانات مؤقتًا بكفاءة ومنع التحميل المتكرر من الـ[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) الأساسي باستخدام هذه الطريقة. حسّن الأداء وسهّل الوصول إلى البيانات في تطبيقك، مع تحسين استغلال الموارد للحصول على استجابة محسّنة. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| override [Crop](../../aspose.imaging/vectorimage/crop/)(Rectangle) | يقص المستطيل المحدد. |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | قص الصورة مع إزاحات. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | يحصل على خيارات الصورة الافتراضية. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages/)() | يحصل على الصور المضمنة. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts/)() | يعيد قائمة الخطوط المستخدمة داخل ملف الميتا ولكن لم يتم العثور عليها. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.emf/emfimage/getoriginaloptions/)() | يحصل على خيارات الصورة الأصلية. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| override [GetUsedFonts](../../aspose.imaging.fileformats.emf/emfimage/getusedfonts/)() | استرجع قائمة الخطوط المستخدمة داخل ملف الميتا باستخدام هذه الطريقة. احصل على رؤى حول استخدام الخطوط، مما يسهل الإدارة الفعّالة وتحسين موارد الخطوط للحصول على تصيير وعرض أكثر دقة. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)() | يزيل الخلفية. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)(RemoveBackgroundSettings) | يزيل الخلفية. |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | يزيل البيانات الوصفية. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ImageResizeSettings) | يعيد تحجيم الصورة باستخدام خيارات موسعة. |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ResizeType) | يعيد تحجيم العرض الجديد المحدد. |
| override [ResizeCanvas](../../aspose.imaging.fileformats.emf/emfimage/resizecanvas/)(Rectangle) | غيّر حجم اللوحة بسهولة باستخدام هذه الدالة. مثالية لضبط الأبعاد الكلية للصورة دون تعديل محتواها. حسّن العرض واستعد الصور لأحجام عرض مختلفة بسهولة. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | يُعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [Rotate](../../aspose.imaging/vectorimage/rotate/)(float) | دوّر الصورة حول المركز. |
| override [RotateFlip](../../aspose.imaging/vectorimage/rotateflip/)(RotateFlipType) | يدور أو يقلب أو يدور ويقلب الصورة. |
| [Save](../../aspose.imaging/image/save/)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| override [Save](../../aspose.imaging/image/save/)(string) | يحفظ الصورة إلى موقع الملف المحدد. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [SetPalette](../../aspose.imaging.fileformats.emf/emfimage/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |

## أمثلة

المثال التالي يوضح كيفية تحويل صور emz إلى تنسيق emf

```csharp
[C#]

string file = "example.emz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions {PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

المثال التالي يوضح كيفية تحويل صور emf إلى تنسيق emz

```csharp
[C#]

string file = "input.emf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
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

يوضح هذا المثال كيفية تحميل صورة EMF من ملف وتحويلها إلى SVG باستخدام EmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // سيتم تحويل النص إلى أشكال.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // لون خلفية سطح الرسم.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // حجم الصفحة.
    rasterizationOptions.PageSize = emfImage.Size;

    // إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // عيّن الهامش الأفقي
    rasterizationOptions.BorderX = 50;

    // تعيين الهامش العمودي
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### انظر أيضًا

* class [MetaImage](../metaimage/)
* namespace [Aspose.Imaging.FileFormats.Emf](../../aspose.imaging.fileformats.emf/)
* assembly [Aspose.Imaging](../../)


