---
title: "الفئة WmfImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Wmf.WmfImage. قم بالتعامل مع صور Microsoft Windows Metafile WMF باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع معالجة سلسة لكل من البيانات المتجهية والبتية المخزنة داخل سجلات ذات طول متغير. قم بتغيير الحجم وتدوير وقلب الصور بسهولة مع ضبط لوحات ألوان مخصصة. حوّل ملفات WMF إلى صيغ WMZ مضغوطة أو احفظها بصيغ صور نقطية للاستخدام المتعدد عبر المنصات والتطبيقات."
type: docs
weight: 9460
url: /ar/net/aspose.imaging.fileformats.wmf/wmfimage/
---
## WmfImage class

تفاعل مع صور Microsoft Windows Metafile (WMF) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع معالجة سلسة لكل من البيانات المتجهية والبتية المخزنة في سجلات ذات طول متغير. قم بتغيير حجم الصور، تدويرها، وعكسها بسهولة مع ضبط لوحات ألوان مخصصة. حوّل ملفات WMF إلى تنسيقات WMZ مضغوطة أو احفظها بتنسيقات صور نقطية للاستخدام المتعدد عبر المنصات والتطبيقات.

```csharp
public class WmfImage : MetaImage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WmfImage](wmfimage/#constructor)() | أنشئ نسخة جديدة من الفئة `WmfImage`، مهيئًا إياها لمزيد من التلاعب ومعالجة بيانات صورة Windows Metafile (WMF). يوفر هذا المُنشئ كائنًا أساسيًا للعمل مع صور WMF، مما يتيح دمجًا سلسًا لقدرات معالجة صور WMF في وظائف تطبيقك. |
| [WmfImage](wmfimage/#constructor_1)(int, int) | أنشئ نسخة جديدة من الفئة `WmfImage` مع معلمات عرض وارتفاع قابلة للتخصيص، لتسهيل إنشاء صور WMF فارغة مُصممة بأبعاد محددة. استخدم هذا المُنشئ لتوليد صور WMF ديناميكيًا بأبعاد دقيقة، مما يتيح إنشاء وتعديل صور مرن داخل تطبيقك. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.wmf/wmfimage/bitsperpixel/) { get; } | استرجع عدد البتات لكل بكسل في الصورة، مما يدل على مستوى عمق اللون أو الدقة. استخدم هذه الخاصية لتحديد تمثيل اللون في الصورة ودقتها، مما يسهل فحوص التوافق ومعالجة اللون داخل تطبيقك. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.wmf/wmfimage/fileformat/) { get; } | الوصول إلى قيمة تنسيق الملف المرتبط بالصورة، لتوفير معلومات حول الصيغة التي تُخزن بها الصورة. استخدم هذه الخاصية لتحديد تنسيق ملف الصورة، مما يسهل فحوصات التوافق والمعالجة الخاصة بالتنسيق داخل تطبيقك. |
| [FrameBounds](../../aspose.imaging.fileformats.wmf/wmfimage/framebounds/) { get; } | الوصول إلى حدود الإطار، موضحًا موقعه وأبعاده داخل الصورة. استخدم هذه الخاصية لاسترجاع معلومات مفصلة عن الموقع المكاني للإطار، مما يتيح تعديلًا دقيقًا وعرضًا داخل تطبيقك. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [Height](../../aspose.imaging/vectorimage/height/) { get; } | الحصول على ارتفاع الصورة. |
| override [HeightF](../../aspose.imaging.fileformats.wmf/wmfimage/heightf/) { get; } | الوصول إلى ارتفاع الصورة، الذي يمثل عدد البكسلات على المحور العمودي. استخدم هذه الخاصية لتحديد أبعاد الصورة المكانية ونسبة العرض إلى الارتفاع، مما يتيح ضبطًا دقيقًا للتخطيط والعرض داخل تطبيقك. |
| [Inch](../../aspose.imaging.fileformats.wmf/wmfimage/inch/) { get; set; } | الوصول إلى خاصية البوصة أو تعديلها، التي تمثل وحدة قياس تُستخدم عادة لتحديد الأبعاد الفيزيائية في الطباعة أو العرض. استخدم هذه الخاصية لتعيين أو استرجاع قيم البوصة المرتبطة بالصورة، مما يسهل تمثيلًا دقيقًا للأبعاد الفيزيائية داخل تطبيقك. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging.fileformats.wmf/wmfimage/iscached/) { get; } | استرجع قيمة منطقية تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى عمليات قراءة بيانات إضافية. استخدم هذه الخاصية لتحسين الأداء من خلال تحديد ما إذا كانت بيانات الكائن متاحة فورًا دون الحاجة إلى عمليات استرجاع بيانات مكلفة داخل تطبيقك. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | يحصل على بيانات تعريف الصورة. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| virtual [Records](../../aspose.imaging.fileformats.emf/metaimage/records/) { get; set; } | يحصل أو يعيّن السجلات. |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | يحصل على حجم الكائن، بالبوصة. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| override [Width](../../aspose.imaging/vectorimage/width/) { get; } | يحصل على عرض الصورة. |
| override [WidthF](../../aspose.imaging.fileformats.wmf/wmfimage/widthf/) { get; } | الوصول إلى عرض الصورة، الذي يدل على عدد البكسلات على المحور الأفقي. استخدم هذه الخاصية لتحديد أبعاد الصورة المكانية ونسبة العرض إلى الارتفاع، مما يتيح ضبطًا دقيقًا للتخطيط والعرض داخل تطبيقك. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddRecord](../../aspose.imaging.fileformats.wmf/wmfimage/addrecord/)(WmfObject) | دمج كائن السجل المحدد في الصورة، مما يثري محتواها ببيانات إضافية أو بيانات وصفية. استخدم هذه الطريقة لدمج كائنات السجل بسلاسة في الصورة، مما يسهل تخزين البيانات بشكل شامل وتنظيمها داخل تطبيقك. |
| override [CacheData](../../aspose.imaging.fileformats.wmf/wmfimage/cachedata/)() | قم بتخزين البيانات مؤقتًا بفعالية، مما يلغي الحاجة إلى تحميل إضافي من الـ[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/). استخدم هذه الطريقة لتحسين الأداء وتقليل استهلاك الموارد داخل تطبيقك عن طريق حفظ البيانات محليًا والوصول إلى الذاكرة المؤقتة. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| override [Crop](../../aspose.imaging/vectorimage/crop/)(Rectangle) | يقص المستطيل المحدد. |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | قص الصورة مع إزاحات. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | يحصل على خيارات الصورة الافتراضية. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages/)() | يحصل على الصور المضمنة. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts/)() | يعيد قائمة الخطوط المستخدمة داخل ملف الميتا ولكن لم يتم العثور عليها. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.wmf/wmfimage/getoriginaloptions/)() | يحصل على خيارات الصورة الأصلية. |
| [GetPostScript](../../aspose.imaging.fileformats.wmf/wmfimage/getpostscript/)() | الوصول إلى بيانات PostScript المرتبطة بالصورة، موفرًا معلومات مفصلة عن هيكلها أو محتواها. استخدم هذه الطريقة لاسترجاع بيانات PostScript لمزيد من التحليل أو المعالجة داخل تطبيقك، مما يتيح وظائف متقدمة متعلقة بعرض أو تعديل PostScript. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| override [GetUsedFonts](../../aspose.imaging.fileformats.wmf/wmfimage/getusedfonts/)() | استرجع قائمة الخطوط المستخدمة داخل ملف الميتا، موفرًا نظرة على موارد الخطوط المستخدمة في الصورة. استخدم هذه الطريقة لتحليل استخدام الخطوط وضمان توفر الخطوط للعرض أو المعالجة الإضافية داخل تطبيقك. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)() | يزيل الخلفية. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)(RemoveBackgroundSettings) | يزيل الخلفية. |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | يزيل البيانات الوصفية. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ImageResizeSettings) | يعيد تحجيم الصورة باستخدام خيارات موسعة. |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ResizeType) | يعيد تحجيم العرض الجديد المحدد. |
| override [ResizeCanvas](../../aspose.imaging.fileformats.wmf/wmfimage/resizecanvas/)(Rectangle) | غيّر حجم لوحة الرسم للصورة، معدلاً أبعادها مع الحفاظ على محتوى الصورة. استخدم هذه الطريقة لتعديل حجم اللوحة دون تغيير المحتوى، مما يسهل تعديل التخطيط وتغييرات التكوين داخل تطبيقك. |
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
| override [SetPalette](../../aspose.imaging.fileformats.wmf/wmfimage/setpalette/)(IColorPalette, bool) | طبق لوحة ألوان محددة على الصورة، مما يتيح تخصيص تمثيل اللون. استخدم هذه الطريقة لتحسين العرض البصري وتحقيق تأثيرات لونية محددة داخل تطبيقك. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |

## أمثلة

يوضح المثال التالي كيفية تحويل صور wmz إلى تنسيق wmf.

```csharp
[C#]

string file = "example.wmz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

يوضح المثال التالي كيفية تحويل صور wmf إلى تنسيق wmz.

```csharp
[C#]

string file = "castle.wmf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
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

يوضح هذا المثال كيفية تحميل صورة WMF من ملف وتحويلها إلى SVG باستخدام WmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // سيتم تحويل النص إلى أشكال.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // لون خلفية سطح الرسم.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // حجم الصفحة.
    rasterizationOptions.PageSize = wmfImage.Size;

    // إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### انظر أيضًا

* class [MetaImage](../../aspose.imaging.fileformats.emf/metaimage/)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../aspose.imaging.fileformats.wmf/)
* assembly [Aspose.Imaging](../../)


