---
title: "فئة EpsImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Eps.EpsImage class. توفر واجهة برمجة التطبيقات لدعم تنسيق ملف صورة Encapsulated PostScript EPS قدرات قوية لمعالجة التركيبات التي تتضمن نصًا ورسومات وصورًا. مع ميزات مثل معالجة صورة المعاينة bitmap، وتدوير الاتجاه، وقلب الصورة، واسترجاع صندوق الحدود للرسوم التوضيحية، وتغيير حجم الصور، وتدويرها، وإضافة صور معاينة، تضمن هذه الواجهة معالجة سلسة وتكامل ملفات EPS في تطبيقات مختلفة بدقة وتنوع."
type: docs
weight: 6670
url: /ar/net/aspose.imaging.fileformats.eps/epsimage/
---
## EpsImage class

توفر واجهة برمجة التطبيقات (API) لدعم تنسيق ملف صورة Encapsulated PostScript (EPS) قدرات قوية لمعالجة التركيبات التي تتضمن نصًا ورسومات وصورًا. مع ميزات مثل معالجة صورة المعاينة النقطية، وتدوير الاتجاه، واسترجاع صندوق الحدود لتحديد حدود الرسوم التوضيحية، وتغيير الحجم، وتدوير الصور، وإضافة صور معاينة، تضمن هذه الواجهة معالجة سلسة وتكامل ملفات EPS في تطبيقات مختلفة بدقة وتنوع.

```csharp
public sealed class EpsImage : VectorImage
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.eps/epsimage/bitsperpixel/) { get; } | الوصول إلى عمق البت الدقيق للصورة بسهولة باستخدام هذه الخاصية. استرجاع عدد البتات لكل بكسل، مما يوفر رؤى حاسمة حول عمق ألوان الصورة ويساعد في تحسين مهام المعالجة. مثالي للتطبيقات التي تتطلب تحكمًا دقيقًا في معالجة وتحليل الصور. |
| [BoundingBox](../../aspose.imaging.fileformats.eps/epsimage/boundingbox/) { get; } | من خلال الوصول إلى صندوق الحدود الأصلي بنقاط مستقلة عن الجهاز، توفر هذه الخاصية معلومات هندسية حاسمة حول أبعاد `EpsImage`. من خلال استرجاع هذه البيانات، يمكن للمستخدمين تقييم حجم الصورة ونسبة أبعادها بدقة، مما يسهل التخطيط والتموضع الدقيق في تطبيقات مختلفة. |
| [BoundingBoxPx](../../aspose.imaging.fileformats.eps/epsimage/boundingboxpx/) { get; } | تُعيد هذه الخاصية صندوق الحدود الأصلي لنسخة `EpsImage` بوحدات البكسل، موفرةً بيانات هندسية أساسية للتصوير والتلاعب الدقيق. باستخدام هذه المعلومات، يمكن للمستخدمين ضمان وضع وحجم دقيق /// لصور EPS في مشاريعهم، مما يعزز العرض البصري العام والجودة. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [CreationDate](../../aspose.imaging.fileformats.eps/epsimage/creationdate/) { get; } | من خلال استرجاع تاريخ الإنشاء من تعليقات EPS Document Structuring Conventions (DSC)، توفر هذه الخاصية بيانات وصفية أساسية تشير إلى بداية ملف EPS. من خلال الوصول إلى هذه المعلومات، يحصل المستخدمون على رؤى حول أصل الملف وتاريخه، مما يعزز إدارة الملفات وتنظيمها. |
| [Creator](../../aspose.imaging.fileformats.eps/epsimage/creator/) { get; } | توفر هذه الخاصية إمكانية الوصول إلى معلومات المنشئ المستخرجة من تعليقات EPS Document Structuring Conventions (DSC) الموجودة داخل ملف EPS. فهم تفاصيل المنشئ يمنح رؤى حول البرنامج أو الأداة المستخدمة لإنشاء ملف EPS، مما يسهل تقييم التوافق عبر منصات وتطبيقات مختلفة. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [EpsType](../../aspose.imaging.fileformats.eps/epsimage/epstype/) { get; } | الوصول إلى قيمة النوع الفرعي لصورة EPS الخاصة بك وتفسيرها، مما يبسط سير العمل ويعزز التوافق عبر المنصات. مثالي لتحسين استرجاع النوع الفرعي لـ EPS في مشاريعك بدقة وكفاءة. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.eps/epsimage/fileformat/) { get; } | الوصول إلى تنسيق ملف الصورة الخاص بك باستخدام هذه الخاصية. استرجاع المعلومات الأساسية حول تنسيق ملف الصورة الخاص بك، مما يسهل التوافق والمعالجة الفعّالة. مثالي لتحديد تنسيق ملفات الصور الخاصة بك للتكامل السلس في مشاريعك. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| [HasRasterPreview](../../aspose.imaging.fileformats.eps/epsimage/hasrasterpreview/) { get; } | اكتشف وجود معاينة نقطية بسهولة باستخدام هذه الخاصية. احصل على القيمة المنطقية التي تشير إلى ما إذا كانت نسخة `EpsImage` تتضمن معاينة نقطية، مما يعزز مهام معالجة الصور لديك بالوضوح والكفاءة. مثالي لتبسيط قرارات سير العمل بناءً على وجود أو عدم وجود معاينات نقطية في صور EPS. |
| override [Height](../../aspose.imaging/vectorimage/height/) { get; } | الحصول على ارتفاع الصورة. |
| override [HeightF](../../aspose.imaging.fileformats.eps/epsimage/heightf/) { get; } | الوصول إلى ارتفاع الصورة باستخدام هذه الخاصية. احصل على ارتفاع الصورة بسهولة، مما يتيح تعديل التخطيط بسلاسة، وحساب نسب الأبعاد، وعرض دقيق عبر مختلف دقات الشاشات وبيئات العرض. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging.fileformats.eps/epsimage/iscached/) { get; } | توفر هذه الخاصية طريقة مريحة للتحقق مما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة بيانات إضافية. إنها تقدم طريقة سريعة وفعّالة لتحديد ما إذا كانت المعلومات المطلوبة متاحة فورًا، مما يحسن الأداء ويقلل من استهلاك الموارد في العمليات المكثفة للبيانات. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | يحصل على بيانات تعريف الصورة. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| [PostScriptVersion](../../aspose.imaging.fileformats.eps/epsimage/postscriptversion/) { get; } | تسترجع هذه الخاصية نسخة PostScript المرتبطة بنسخة `EpsImage`. إنها توفر نظرة على نسخة لغة PostScript المحددة المستخدمة داخل ملف EPS، مما يساعد في تقييم التوافق وتسهيل التكامل السلس مع البيئات المتوافقة مع PostScript. |
| [PreviewImageCount](../../aspose.imaging.fileformats.eps/epsimage/previewimagecount/) { get; } | الوصول إلى عدد صور المعاينة المتاحة بسهولة. تتيح لك هذه الخاصية استرجاع عدد صور المعاينة المرتبطة بملفك بسهولة، مما يتيح إدارة فعّالة وتصفحًا لصور المعاينة. مثالي لتحسين سير العمل وتنظيم أصول الصور الخاصة بك بفعالية. |
| [PreviewImages](../../aspose.imaging.fileformats.eps/epsimage/previewimages/) { get; } | استرجاع صور المعاينة المرتبطة بملفك. توفر هذه الخاصية وصولًا سلسًا إلى مجموعة صور المعاينة، مما يتيح لك تصفحها وإدارتها بكفاءة حسب الحاجة. مثالي لمعاينة سريعة واختيار الصورة المناسبة لمشروعك. |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | يحصل على حجم الكائن، بالبوصة. |
| [Title](../../aspose.imaging.fileformats.eps/epsimage/title/) { get; } | تسترجع هذه الخاصية العنوان المستخرج من تعليقات توثيق بنية مستندات EPS (DSC) المضمنة داخل ملف EPS. إنها توفر بيانات وصفية قيمة حول محتوى ملف EPS، مما يساعد في تنظيم المستندات وتحديدها داخل التطبيقات المتوافقة. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| override [Width](../../aspose.imaging/vectorimage/width/) { get; } | يحصل على عرض الصورة. |
| override [WidthF](../../aspose.imaging.fileformats.eps/epsimage/widthf/) { get; } | استرجاع عرض الصورة باستخدام هذه الخاصية المريحة. احصل على عرض الصورة بسهولة، مما يسهل حسابات التخطيط الدقيقة، وعمليات التحجيم، والمهام المتعلقة بالأبعاد داخل تطبيقك. مثالي لضمان عرض دقيق للصور عبر مختلف المنصات والأجهزة. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.eps/epsimage/cachedata/)() | هذه الطريقة لا تقوم بأي شيء لأن تنفيذ الفئة `EpsImage` الحالي لا يتضمن تخزين البيانات مؤقتًا. رغم أنها قد لا تنفذ أي إجراء، فإن فهم هذا السلوك أمر حاسم للمطورين الذين يعملون مع صور EPS، لضمان إدارة موارد فعّالة وأداء أمثل داخل تطبيقاتهم. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| override [Crop](../../aspose.imaging/vectorimage/crop/)(Rectangle) | يقص المستطيل المحدد. |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | قص الصورة مع إزاحات. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | يحصل على خيارات الصورة الافتراضية. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages/)() | يحصل على الصور المضمنة. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.imaging/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [`Save`](../../aspose.imaging/image/save/) كمعامل ثاني. |
| [GetPreviewImage](../../aspose.imaging.fileformats.eps/epsimage/getpreviewimage/)(EpsPreviewFormat) | يسترجع الصورة المعاينة الموجودة بالتنسيق المحدد *format* أو يعيد `null` إذا لم يتم العثور على أي منها. توفر هذه الطريقة مرونة في الوصول إلى صور المعاينة المخصصة لتنسيقات معينة، مما يحسن التوافق وإدارة الموارد داخل التطبيقات. |
| [GetPreviewImages](../../aspose.imaging.fileformats.eps/epsimage/getpreviewimages/)() | يصل إلى صور المعاينة المرتبطة بنسخة `EpsImage`، مما يسمح باسترجاع سلس للتفتيش أو الاستخدام في التطبيقات. توفر هذه الطريقة وصولًا مريحًا إلى صور المعاينة، مما يعزز تفاعل المستخدم مع بيانات الصورة. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)() | يزيل الخلفية. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)(RemoveBackgroundSettings) | يزيل الخلفية. |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | يزيل البيانات الوصفية. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ImageResizeSettings) | يعيد تحجيم الصورة باستخدام خيارات موسعة. |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ResizeType) | يعيد تحجيم العرض الجديد المحدد. |
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
| override [SetPalette](../../aspose.imaging.fileformats.eps/epsimage/setpalette/)(IColorPalette, bool) | خصص لوحات ألوان الصورة لتحقيق مخططات ألوان فريدة وتعزيز الجاذبية البصرية. صمم الألوان لتأثيرات محددة وحسّن جودة الصورة عبر مختلف المنصات والأجهزة بسهولة. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |

## أمثلة

إعادة تحجيم صورة EPS وتصديرها إلى صيغة PNG.

```csharp
[C#]

// تحميل صورة EPS
using (var image = Image.Load("AstrixObelix.eps"))
{
    // إعادة تحجيم الصورة باستخدام طريقة Mitchell cubic interpolation.
    image.Resize(400, 400, ResizeType.Mitchell);

    // تصدير الصورة إلى صيغة PNG
    image.Save("ExportResult.png", new PngOptions());
}
```

تحويل صورة EPS إلى PDF باستخدام عرض PostScript.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PdfOptions
    {
        PdfCoreOptions = new PdfCoreOptions
        {
            PdfCompliance = PdfComplianceVersion.PdfA1b // Set required PDF compliance
        }
    };
  
    image.Save("Sample.pdf", options);
}
```

تحويل صورة EPS إلى PNG باستخدام تصيير PostScript.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PngOptions
    {
        VectorRasterizationOptions = new EpsRasterizationOptions
        {
            PageWidth = 500, // Image width
            PageHeight = 500 // Image height
            PreviewToExport = EpsPreviewFormat.PostScriptRendering; // Render raster image using the PostScript
        }
    };

    image.Save("Sample.png", options);
}
```

إعادة تحجيم صورة EPS باستخدام إعدادات متقدمة.

```csharp
[C#]

// تحميل صورة EPS
using (var image = Image.Load("AstrixObelix.eps"))
{
    // إعادة تحجيم الصورة باستخدام إعدادات تحجيم متقدمة
    image.Resize(400, 400, new ImageResizeSettings
    {
        // تعيين وضع الاستيفاء
        Mode = ResizeType.LanczosResample,

        // تعيين نوع الفلتر
        FilterType = ImageFilterType.SmallRectangular,

        // يضبط طريقة مقارنة اللون
        ColorCompareMethod = ColorCompareMethod.Euclidian,

        // حدد طريقة تكميم اللون
        ColorQuantizationMethod = ColorQuantizationMethod.Popularity
    });

    // تصدير الصورة إلى صيغة PNG
    image.Save("ExportResult.png", new PngOptions());
}
```

### انظر أيضًا

* class [VectorImage](../../aspose.imaging/vectorimage/)
* namespace [Aspose.Imaging.FileFormats.Eps](../../aspose.imaging.fileformats.eps/)
* assembly [Aspose.Imaging](../../)


