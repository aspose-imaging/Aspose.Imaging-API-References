---
title: "الفئة OdgImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.OpenDocument.OdgImage. قم بمعالجة صورة ODG الرسومية من نوع OpenDocument بصيغة ملف متجه باستخدام واجهة برمجة التطبيقات الخاصة بنا، والتي تُستخدم على نطاق واسع من قبل تطبيقات OpenOffice وLibreOffice Draw لتخزين عناصر الرسم بصيغة متجهة. قم بتحليل المستندات بسلاسة، والوصول إلى الصفحات، وتغيير حجم الصور وتدويرها، مما يضمن معالجة فعّالة وتخصيص ملفات ODG لتلبية متطلباتك المحددة."
type: docs
weight: 7500
url: /ar/net/aspose.imaging.fileformats.opendocument/odgimage/
---
## OdgImage class

التعامل مع تنسيق ملف الصورة المتجهة OpenDocument Graphic (ODG) باستخدام واجهة برمجة التطبيقات الخاصة بنا، وهو مستخدم على نطاق واسع من قبل تطبيقات OpenOffice وLibreOffice Draw لتخزين عناصر الرسم بصيغة متجهة. قم بتحليل المستندات بسلاسة، والوصول إلى الصفحات، وتغيير حجم الصور وتدويرها، مما يضمن معالجة فعّالة وتخصيص ملفات ODG لتلبية متطلباتك الخاصة.

```csharp
public class OdgImage : OdImage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [OdgImage](odgimage/#constructor)(StreamContainer) | تم تصميمه للتكامل السلس في حلول البرمجيات، يقوم المُنشئ `OdgImage` بتهيئة نسخة جديدة باستخدام حاوية تدفق. تضمن هذه الطريقة معالجة فعّالة لبيانات صورة ODG داخل بيئات البرمجيات، مع تحسين استهلاك الموارد وتسهيل سير عمل معالجة الصور بشكل مبسط. |
| [OdgImage](odgimage/#constructor_1)(StreamContainer, LoadOptions) | ابدأ بإنشاء جديد لكائن الفئة `OdgImage` مع تهيئة نسخة جديدة. استغل إمكانات حاوية التدفق المقترنة بمعلمات خيارات التحميل، حافظ على مُنشئ متعدد الاستخدامات لتحميل الصور بسلاسة. يمنح هذا المُنشئ قدرة معالجة صور فعّالة، مع توفير تكوينات تحميل قابلة للتخصيص لتعزيز التكيف والأداء عبر سيناريوهات متعددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.opendocument/odimage/bitsperpixel/) { get; } | يسترجع عدد البتات لكل بكسل في الصورة. توفر هذه الخاصية نظرة على مستوى التفاصيل وعمق اللون الممثل في الصورة، مما يساعد في مهام معالجة الصور المختلفة والتحسينات. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.opendocument/odgimage/fileformat/) { get; } | يحصل على قيمة تنسيق الملف |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [Height](../../aspose.imaging/vectormultipageimage/height/) { get; } | الحصول على ارتفاع الصورة. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf/) { get; } | يحصل على ارتفاع الكائن، بالبوصة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging.fileformats.opendocument/odimage/iscached/) { get; } | يحصل على قيمة منطقية تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة البيانات. تُعد هذه الخاصية مؤشرًا على التحسين، حيث تعزز الأداء من خلال تقليل عمليات الوصول المتكررة للبيانات. |
| [Metadata](../../aspose.imaging.fileformats.opendocument/odimage/metadata/) { get; } | يسترجع البيانات الوصفية الخاصة بملفات OpenDocument. تتيح هذه الخاصية الوصول إلى المعلومات الأساسية المضمنة داخل ملفات OD، مما يسهل عمليات مختلفة مثل الاستخراج أو التعديل أو تحليل البيانات الوصفية. |
| override [Metadata](../../aspose.imaging/vectormultipageimage/metadata/) { get; } | يحصل على بيانات تعريف الصورة. |
| override [PageCount](../../aspose.imaging.fileformats.opendocument/odimage/pagecount/) { get; } | يسترجع العدد الإجمالي للصفحات داخل الصورة. هذه الخاصية أساسية للتطبيقات التي تدير صورًا متعددة الصفحات، مما يتيح لها تحديد عدد الصفحات المتاحة للمعالجة أو العرض بدقة. |
| virtual [PageExportingAction](../../aspose.imaging/vectormultipageimage/pageexportingaction/) { get; set; } | يحصل أو يعيّن إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرةً قبل حفظ كل صفحة. |
| override [Pages](../../aspose.imaging.fileformats.opendocument/odgimage/pages/) { get; } | من خلال استرجاع مجموعة الصفحات، تمكّن هذه الخاصية من الوصول إلى جميع الصفحات المرتبطة بصورة. عبر الوصول إلى هذه الخاصية، يمكن للمطورين التكرار عبر الصفحات الفردية، استرجاع صفحات محددة بناءً على فهرسها، أو تنفيذ عمليات جماعية على المجموعة بأكملها. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| [Records](../../aspose.imaging.fileformats.opendocument/odimage/records/) { get; } | يسترجع سجلات OpenDocument المخزنة داخل الصورة. تمنح هذه الخاصية الوصول إلى عناصر بيانات هيكلية محددة مدمجة داخل ملفات OpenDocument، مما يسهل استرجاع أو معالجة المعلومات ذات الصلة لمزيد من المعالجة أو التحليل. |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | يحصل على حجم الكائن، بالبوصة. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| override [Width](../../aspose.imaging/vectormultipageimage/width/) { get; } | يحصل على عرض الصورة. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf/) { get; } | يحصل على عرض الكائن، بالبوصة. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [CacheData](../../aspose.imaging/vectormultipageimage/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) الأساسي. |
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
| override [SetPalette](../../aspose.imaging/vectormultipageimage/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |

## أمثلة

هذا المثال يحمل صورة ODG متعددة الصفحات.

```csharp
[C#]

string dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل الصورة.
using (Aspose.Imaging.FileFormats.OpenDocument.OdImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // تحويل إلى OdgImage
    Aspose.Imaging.FileFormats.OpenDocument.OdgImage odgImage = (Aspose.Imaging.FileFormats.OpenDocument.OdgImage)image;

    // احصل على جميع الصفحات
    Aspose.Imaging.Image[] pages = odgImage.Pages;

    // قم ببعض معالجة الصورة
}
```

المثال التالي يوضح كيفية تصدير صورة FODG (قالب ODF XML مسطح) إلى صيغة PDF.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3635";

string inputFileName = System.IO.Path.Combine(dir, "VariousObjectsMultiPage.fodg");
string outputFileName = inputFileName + ".pdf";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFileName))
{
    Aspose.Imaging.ImageOptions.OdgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.OdgRasterizationOptions();
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.White;
    rasterizationOptions.PageSize = image.Size;

    Aspose.Imaging.ImageOptions.PdfOptions saveOptions = new Aspose.Imaging.ImageOptions.PdfOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    image.Save(outputFileName, saveOptions);
}
```

### انظر أيضًا

* class [OdImage](../odimage/)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../aspose.imaging.fileformats.opendocument/)
* assembly [Aspose.Imaging](../../)


