---
title: "الفئة GifImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Gif.GifImage. توفر واجهة برمجة التطبيقات لملف صورة GIF (تنسيق التبادل الرسومي) للمطورين أدوات متعددة لمعالجة الصور النقطية المضغوطة وملفات GIF المتحركة. تشمل الميزات معالجة بيانات XMP الوصفية، إعدادات لوحة الألوان، التحكم في الخلفية واللون الشفاف، إعدادات الشفافية، تعديل الحجم، القص، تطبيق الفلاتر، تصحيح غاما، تعديل التباين، التحويل إلى تدرج الرمادي والتحويل إلى صيغ أخرى. تمكّن هذه الواجهة المطورين من التلاعب السلس وتحسين صور GIF لمجموعة واسعة من التطبيقات."
type: docs
weight: 6800
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/
---
## GifImage class

توفر API لتنسيق تبادل الرسومات (GIF) أدوات متعددة للمطورين لمعالجة الصور النقطية المضغوطة وملفات GIF المتحركة. تشمل الميزات معالجة بيانات التعريف XMP، إعدادات لوحة الألوان، التحكم في لون الخلفية والشفافية، إعدادات الشفافية، تغيير الحجم، القص، تطبيق الفلاتر، تصحيح غاما، تعديل التباين، تحويل إلى تدرج الرمادي، والتحويل إلى صيغ أخرى. تمكّن هذه API المطورين من التلاعب السلس وتحسين صور GIF لمجموعة واسعة من التطبيقات.

```csharp
public sealed class GifImage : RasterCachedMultipageImage, IMultipageImageExt
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GifImage](gifimage/#constructor)(GifFrameBlock) | إنشاء صور GIF يصبح سهلًا مع منشئ `GifImage`. باستخدام معلمة firstFrame فقط، يدخل في عالم التواصل البصري الديناميكي. |
| [GifImage](gifimage/#constructor_1)(GifFrameBlock, IColorPalette) | ابدأ كائنًا جديدًا من نوع `GifImage` مع المعلمات المحددة للإطار الأول ولوحة الألوان العامة. ابدأ بإدارة صور GIF بسرعة، مع ضمان تمثيل دقيق باستخدام إعدادات قابلة للتخصيص للحصول على أفضل النتائج. |
| [GifImage](gifimage/#constructor_2)(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) | ابدأ بسهولة مع منشئ `GifImage`. باستخدام هذه الطريقة البسيطة، يمكنك الغوص في إنشاء ملفات GIF المتحركة بسهولة. ما عليك سوى توفير firstFrame و globalPalette و paletteColorResolution و aspectRatio وغيرها من المعلمات، وستكون جاهزًا لإحياء تصاميمك. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.gif/gifimage/activeframe/) { get; set; } | قم بإدارة وتعديل الإطارات باستخدام هذه الخاصية، مما يتيح تنقلًا سلسًا وتعديلًا للإطار النشط داخل صورة GIF. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| override [BackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolor/) { get; set; } | تحكم في لون خلفية صورة GIF باستخدام هذه الخاصية. يمكنك تعيين أو استرجاع لون الخلفية لضمان التناسق وتعزيز الجاذبية البصرية. |
| [BackgroundColorIndex](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolorindex/) { get; set; } | تحكم في فهرس لون الخلفية لصورة GIF باستخدام هذه الخاصية. عيّن أو استرجع الفهرس للحفاظ على التناسق أو لتحقيق التأثيرات البصرية المطلوبة. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | الحصول على عدد البتات لكل بكسل في الصورة. |
| [Blocks](../../aspose.imaging.fileformats.gif/gifimage/blocks/) { get; } | احصل على وصول سلس إلى كتل GIF باستخدام هذه الخاصية، مما يسهل استرجاع وتعديل هياكل البيانات الأساسية للصورة. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.gif/gifimage/fileformat/) { get; } | استرجع تنسيق الملف بسهولة باستخدام هذه الخاصية. إنها المصدر الأساسي لتحديد تنسيق ملفاتك. مدمجة بسلاسة في سير عملك، توفر معلومات حيوية دون أي عناء. |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/hasbackgroundcolor/) { get; } | تحدد هذه الخاصية ما إذا كانت صورة GIF تحتوي على لون خلفية. إذا كانت true، فهذا يعني أن الصورة تشمل لون خلفية. |
| [HasTrailer](../../aspose.imaging.fileformats.gif/gifimage/hastrailer/) { get; set; } | تحكم في وجود مقطع نهائي (trailer) في ملفات GIF الخاصة بك باستخدام هذه الخاصية. سواء كنت بحاجة للتحقق مما إذا كان هناك مقطع نهائي أو تعيين وجوده، فإن هذه الخاصية تبسط العملية. حافظ على هيكلة ملفات GIF الخاصة بك والامتثال باستخدام هذه الميزة البديهية. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.gif/gifimage/hastransparentcolor/) { get; set; } | حدد ما إذا كان الإطار النشط لصورة GIF يتضمن لونًا شفافًا. توفر هذه الخاصية طريقة مريحة للتحقق من الشفافية داخل الصورة. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | الحصول على ارتفاع الصورة. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | الحصول على أو تعيين الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذه [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [ImageOpacity](../../aspose.imaging.fileformats.gif/gifimage/imageopacity/) { get; } | استرجع شفافية الإطار النشط داخل الصورة، مما يوفر نظرة على مستوى شفافيته. هذه الخاصية مفيدة بشكل خاص لفهم درجة الشفافية أو العتمة للإطار النشط في الصورة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsInterlaced](../../aspose.imaging.fileformats.gif/gifimage/isinterlaced/) { get; } | تحدد ما إذا كانت الصورة متشابكة (interlaced)، مما يؤثر على عرضها أثناء التحميل. توفر هذه الخاصية نظرة على سلوك عرض الصورة، وهو أمر أساسي لتحسين استراتيجيات التحميل وتعزيز تجربة المشاهدة العامة. |
| [IsPaletteSorted](../../aspose.imaging.fileformats.gif/gifimage/ispalettesorted/) { get; set; } | تحكم في ترتيب لوحة الألوان في صور GIF الخاصة بك باستخدام هذه الخاصية. سواء كنت بحاجة للتحقق مما إذا كانت لوحة الألوان مرتبة أو تعيين سلوك الترتيب، فإن هذه الخاصية توفر طريقة بسيطة لإدارة تنظيم لوحة الألوان في ملفات GIF. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| [LoopsCount](../../aspose.imaging.fileformats.gif/gifimage/loopscount/) { get; set; } | استرجع عدد التكرارات بسهولة باستخدام هذه الخاصية. إذا كانت صورة GIF الخاصة بك تتضمن معلومات التكرار، فإن هذه الخاصية تمنحك وصولًا سريعًا إلى عدد التكرارات، مما يتيح لك إدارة سلوك التكرار بسلاسة في ملفات GIF. |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | الحصول على أو تعيين بيانات XMP من الإطار. |
| override [PageCount](../../aspose.imaging.fileformats.gif/gifimage/pagecount/) { get; } | استرجع العدد الإجمالي للصفحات الموجودة داخل الصورة باستخدام هذه الخاصية البسيطة. مثالية لتقييم مدى محتوى الصورة بسرعة. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | يحصل أو يعيّن إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرةً قبل حفظ كل صفحة. |
| override [Pages](../../aspose.imaging.fileformats.gif/gifimage/pages/) { get; } | احصل على الوصول إلى الصفحات داخل الصورة عبر هذه الخاصية المريحة، مما يسمح بالتنقل السلس ومعالجة الصفحات الفردية حسب الحاجة. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| [PaletteColorResolutionBits](../../aspose.imaging.fileformats.gif/gifimage/palettecolorresolutionbits/) { get; set; } | تحكم في دقة ألوان لوحة الألوان لصور GIF الخاصة بك باستخدام هذه الخاصية. اضبط عدد البتات المستخدمة لتمثيل الألوان في اللوحة، مما يوفر تحكمًا دقيقًا في عمق اللون وجودة الصورة. |
| [PixelAspectRatio](../../aspose.imaging.fileformats.gif/gifimage/pixelaspectratio/) { get; set; } | تحكم في نسبة أبعاد البكسل لصورة GIF باستخدام هذه الخاصية. اضبط أو استرجع نسبة الأبعاد لضمان عرض دقيق والحفاظ على جودة الصورة البصرية. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | يحصل أو يعيّن محول الألوان المخصص |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat/) { get; } | يحصل على تنسيق البيانات الخام. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات بدون تحويل. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | يحصل أو يعيّن فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق. |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | يحصل أو يعيّن محول الألوان المفهرسة |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | يحصل على حجم السطر الخام بالبايت. |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| override [TransparentColor](../../aspose.imaging.fileformats.gif/gifimage/transparentcolor/) { get; } | استرجع اللون الشفاف للإطار النشط في صورة GIF. تتيح لك هذه الخاصية الوصول إلى اللون المحدد كشفاف داخل الإطار النشط حاليًا. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات التعريف XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution/) { get; set; } | يحصل أو يعيّن الدقة العمودية، بوحدة البكسل لكل بوصة، لهذا [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width/) { get; } | يحصل على عرض الصورة. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.gif/gifimage/addblock/)(IGifBlock) | إضافة كتلة GIF جديدة تتيح لك تضمين بيانات إضافية داخل الصورة. تمكّن هذه الطريقة من إلحاق كتل مخصصة إلى صورة GIF، والتي يمكن أن تحتوي على أنواع مختلفة من المعلومات. |
| [AddPage](../../aspose.imaging.fileformats.gif/gifimage/addpage/)(RasterImage) | أدمج صفحة جديدة بسلاسة في الصورة الحالية، معزّزًا محتواها وموسعًا نطاقها. تُضيف هذه الطريقة مجموعات الصور بمحتوى إضافي، مما يعزز الإبداع والمرونة في إدارة وتكوين الصور. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.gif/gifimage/adjustbrightness/)(int) | يضبط سطوع الصورة وفقًا للمعامل *brightness* المحدد. تقوم هذه الطريقة بتعديل سطوع الصورة بالكامل بشكل موحد، معززةً أو مخفضةً الإضاءة العامة لتحقيق التأثير المطلوب. |
| override [AdjustContrast](../../aspose.imaging.fileformats.gif/gifimage/adjustcontrast/)(float) | يضبط تباين الصورة، معززًا أو مخفضًا الفرق في السطوع بين البكسلات. تقوم هذه الطريقة بتعديل النطاق اللوني العام للصورة، مما يجعل المناطق الداكنة أظلم والأجزاء الفاتحة أفتح لتحسين الوضوح البصري والتفاصيل. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma/#adjustgamma)(float) | حسّن جودة الصورة بتطبيق تصحيح جاما. تقوم هذه الطريقة بضبط جاما اللون للصورة لتحقيق وضوح بصري أمثل. إنها تعدل قيمة الجاما لكل بكسل، مما ينتج عنه تحسين في تجسيد الألوان ومظهر الصورة العام. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma/#adjustgamma_1)(float, float, float) | تطبيق تصحيح جاما على الصورة يضيف تعديلًا غير خطي لقيم البكسل، معززًا أو مخفضًا السطوع بناءً على المعاملات المحددة للقنوات الحمراء والخضراء والزرقاء. تساعد هذه الطريقة على ضبط توازن اللون وإضاءة الصورة بدقة، مما يحسن مظهرها العام وجودتها البصرية. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | ينفّذ تعديلًا تلقائيًا متكيفًا للسطوع والتباين عبر الصورة بأكملها. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | يقوم بتدوير الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من بيانات Exif. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح، مما يعزز تجربة المستخدم ويقضي على الحاجة إلى التعديلات اليدوية. من خلال تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، مما يوفر تجربة مشاهدة سلسة عبر مختلف المنصات والأجهزة. تبسط عملية التدوير الآلية معالجة الصور وتحسن قابلية الاستخدام العامة، خاصةً عند التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المتنوعة. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.gif/gifimage/binarizebradley/#binarizebradley)(double) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي مع عتبة الصورة المتكاملة هو طريقة لتحويل صورة رمادية إلى صورة ثنائية. تحسب هذه الخوارزمية عتبة محلية لكل بكسل بناءً على متوسط شدة البكسلات المحيطة داخل نافذة محددة. من خلال تعديل العتبة محليًا بناءً على شدة البكسلات، تكون طريقة برايدلي فعّالة في التعامل مع تباينات الإضاءة والظلال عبر الصورة. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double, int) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| override [BinarizeFixed](../../aspose.imaging.fileformats.gif/gifimage/binarizefixed/)(byte) | تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا يحول صورة رمادية أو ملونة إلى صورة ثنائية، حيث يُصنّف كل بكسل إما أسود أو أبيض بناءً على ما إذا كانت قيمته الشدة تتجاوز العتبة المحددة. |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.gif/gifimage/binarizeotsu/)() | تحويل الصورة إلى ثنائية باستخدام عتبة أوتو هو طريقة تُستخدم لتحديد قيمة العتبة المثلى تلقائيًا لتحويل صورة رمادية إلى صورة ثنائية. تحسب خوارزمية عتبة أوتو العتبة التي تقلل من التباين داخل الفئات لبكسلات الصورة في الفئتين الناتجتين (المقدمة والخلفية). تكون هذه التقنية مفيدة بشكل خاص عندما تكون قيمة العتبة المثلى غير معروفة وتحتاج إلى تحديدها بشكل تكيفي بناءً على مخطط ترددات الصورة. |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata/)() | يخزن البيانات بشكل خاص. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| [ClearBlocks](../../aspose.imaging.fileformats.gif/gifimage/clearblocks/)() | مسح جميع كتل GIF يزيل أي بيانات موجودة مخزنة داخل الصورة. تقوم هذه العملية بإعادة تعيين الصورة إلى حالة فارغة، وإزالة أي كتل مضافة مسبقًا. استخدم هذه الطريقة عندما تحتاج إلى بدء جديد بصفحة نظيفة لإنشاء أو تعديل صورة GIF. |
| override [Crop](../../aspose.imaging.fileformats.gif/gifimage/crop/#crop)(Rectangle) | قم بقص الصورة باستخدام منطقة مستطيلة محددة. تزيل هذه العملية الجزء الخارجي من الصورة، تاركةً فقط المنطقة المختارة المحددة بالمستطيل. |
| override [Crop](../../aspose.imaging/rastercachedmultipageimage/crop/)(int, int, int, int) | قص الصورة مع إزاحات. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | يقوم بأداء التمويه على الصورة الحالية. |
| override [Dither](../../aspose.imaging.fileformats.gif/gifimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | طبق التمويه على الصورة الحالية. تعزز هذه العملية جودة الصورة عن طريق تقليل تدرجات اللون وتحسين الانتقالات اللونية، مما ينتج مظهرًا أكثر سلاسة. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | أدمج توقيعًا رقميًا بناءً على كلمة المرور المقدمة في كل صفحة من الصورة. |
| override [Filter](../../aspose.imaging.fileformats.gif/gifimage/filter/)(Rectangle, FilterOptionsBase) | طبق مرشحًا محددًا على المنطقة المخصصة من الصورة، معززًا جودتها البصرية أو معدلاً مظهرها حسب الرغبة. تقوم هذه الطريقة بمعالجة البكسلات داخل المستطيل المحدد بشكل انتقائي، مما يسمح بإجراء تعديلات مستهدفة مع الحفاظ على سلامة بيانات الصورة المحيطة. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | يحصل على بكسل صورة 32-بت ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | يحصل على مصفوفة بكسلات 32-بت ARGB الافتراضية. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.gif/gifimage/getoriginaloptions/)() | استرجع الخيارات المستندة إلى إعدادات الملف الأصلي، وهي ضرورية للحفاظ على الدقة والاتساق في معالجة وتعديل الصور. تتيح هذه الطريقة دمج معلمات الملف المحددة بسلاسة في العمليات اللاحقة، مما يضمن تجسيدًا دقيقًا والالتزام بخصائص الصورة الأصلية. يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت ومعلمات أخرى للصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.imaging/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [`Save`](../../aspose.imaging/image/save/) كمعامل ثاني. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | يحصل على بكسل صورة. |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | يحصل على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف عند المسح. |
| override [Grayscale](../../aspose.imaging.fileformats.gif/gifimage/grayscale/)() | تحويل الصورة إلى تمثيلها الرمادي يحول الصورة الملونة إلى نسخة رمادية عن طريق إزالة معلومات اللون مع الحفاظ على الإضاءة. تبسط هذه العملية الصورة إلى درجات من الرمادي، مما يجعلها مناسبة لتطبيقات مختلفة مثل الطباعة ومعالجة المستندات والتحليل الرمادي. |
| [InsertBlock](../../aspose.imaging.fileformats.gif/gifimage/insertblock/)(int, IGifBlock) | إدراج كتلة GIF جديدة يتيح لك إضافة بيانات مخصصة في موضع محدد داخل الصورة. تمكّن هذه الطريقة من وضع كتل مخصصة في الموقع المطلوب داخل صورة GIF، مما يوفر مرونة في تنظيم وهيكلة بيانات الصورة. |
| override [IsDigitalSigned](../../aspose.imaging/rastercachedmultipageimage/isdigitalsigned/)(string, int) | يُجري فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والحدّ المحدد. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels/)(Rectangle) | يحمّل بكسلات ARGB 32‑بت. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels/)(Rectangle) | يحمّل بكسلات ARGB 64‑بت. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels/)(Rectangle) | يحمّل بكسلات بتنسيق CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | يحمّل بكسلات ARGB 32‑بت جزئيًا عن طريق الحزم. |
| [LoadPartialArgb64Pixels](../../aspose.imaging/rasterimage/loadpartialargb64pixels/)(Rectangle, IPartialArgb64PixelLoader) | يحمّل بكسلات ARGB 64‑بت جزئيًا عن طريق الحزم. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | يحمّل البكسلات جزئيًا عن طريق الحزم. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels/)(Rectangle) | يحمّل البكسلات. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | يحمّل البيانات الخام. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | يحمّل البيانات الخام. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle/)() | يضبط الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف. تستخدم هذه الطريقة [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) و[`Rotate`](../../aspose.imaging/rasterimage/rotate/) الطرق. |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle/)(bool, Color) | يضبط الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف. تستخدم هذه الطريقة [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) و[`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate/) الطرق. |
| override [NormalizeHistogram](../../aspose.imaging/rastercachedmultipageimage/normalizehistogram/)() | يضبط هيستوجرام الصورة — يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [OrderBlocks](../../aspose.imaging.fileformats.gif/gifimage/orderblocks/)() | ترتيب كتل GIF وفقًا لمواصفات GIF يضمن تخطيط GIF صحيح والامتثال للمعيار. تتضمن هذه العملية ترتيب الكتل بالتسلسل الصحيح كما هو معرف في المواصفات. بالإضافة إلى ذلك، قد تشمل إزالة بعض كائنات [`GifGraphicsControlBlock`](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) غير الضرورية للتخطيط النهائي. بالالتزام بمواصفات GIF، ستكون الصورة الناتجة مُهيكلة بشكل صحيح ومتوافقة مع تطبيقات عرض GIF. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [RemoveBlock](../../aspose.imaging.fileformats.gif/gifimage/removeblock/)(IGifBlock) | إزالة كتلة GIF تزيل بيانات محددة من الصورة، مما يتيح القدرة على تنظيف أو تعديل بنية الصورة. تمكّن هذه الطريقة من إزالة الكتل غير المرغوب فيها أو غير الضرورية، مما يُحسّن من كفاءة تخزين صورة GIF. استخدم هذه الوظيفة لإزالة المعلومات القديمة من الصورة مع الحفاظ على سلامتها وجودتها. |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | يزيل بيانات التعريف الخاصة بهذه الصورة عن طريق تعيين قيمة [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) إلى `null`. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize/#resize_1)(int, int, ImageResizeSettings) | يقوم بتغيير حجم هذه [`Image`](../../aspose.imaging/image/) المثيل. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize/#resize_2)(int, int, ResizeType) | يقوم بتغيير حجم هذه [`Image`](../../aspose.imaging/image/) المثيل. |
| [ResizeFullFrame](../../aspose.imaging.fileformats.gif/gifimage/resizefullframe/)(int, int, ResizeType) | تغيير حجم الصورة مع مراعاة الإطارات الكاملة لكل صفحة في GIF، مما يمنع ظهور العيوب المحتملة. هذه الطريقة أساسية للحفاظ على سلامة وجودة الصورة، خاصةً عند التعامل مع GIF متحركة أو تسلسلات إطارات. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| override [ResizeHeightProportionally](../../aspose.imaging/rastercachedmultipageimage/resizeheightproportionally/)(int, ResizeType) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| [ResizeProportional](../../aspose.imaging.fileformats.gif/gifimage/resizeproportional/)(int, int, ResizeType) | يحافظ التحجيم النسبي على نسبة أبعاد الصورة أثناء تعديل حجمها، مما يضمن عدم ظهور الصورة مشوهة أو ممدودة. تقوم هذه الطريقة بتحجيم الصورة بشكل نسبي، حيث يتم تكبير كل من العرض والارتفاع بنفس العامل. سيقوم التحجيم النسبي بتغيير حجم كل إطار وفقًا لنسبة *newWidth*/العرض و*newHeight*/الارتفاع. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [ResizeWidthProportionally](../../aspose.imaging/rastercachedmultipageimage/resizewidthproportionally/)(int, ResizeType) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | دوّر الصورة حول المركز. |
| override [Rotate](../../aspose.imaging.fileformats.gif/gifimage/rotate/#rotate_1)(float, bool, Color) | تقوم هذه الطريقة بتدوير الصورة حول نقطة مركزها. من خلال تحديد زاوية الدوران، يمكنك تدوير الصورة باتجاه عقارب الساعة أو عكسها لتحقيق الاتجاه المطلوب. يساعد هذا الدوران على تعديل عرض الصورة أو محاذاتها دون تشويه محتواها. |
| override [RotateFlip](../../aspose.imaging.fileformats.gif/gifimage/rotateflip/)(RotateFlipType) | قم بأداء الدوران أو القلب أو كليهما على الإطار النشط فقط. يطبق هذا الإجراء التحويلات حصريًا على الإطار النشط حاليًا في الصورة، مع الحفاظ على سلامة الإطارات الأخرى في التسلسل. |
| [Save](../../aspose.imaging/image/save/)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| override [Save](../../aspose.imaging/image/save/)(string) | يحفظ الصورة إلى موقع الملف المحدد. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.imaging/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels/)(Rectangle, int[]) | يحفظ بكسلات ARGB 32 بت. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | يحفظ البكسلات. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels/)(Rectangle, Color[]) | يحفظ البكسلات. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | يحفظ البيانات الخام. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel/)(int, int, int) | يضبط بكسل صورة ARGB 32 بت للموقع المحدد. |
| [SetFrameTime](../../aspose.imaging.fileformats.gif/gifimage/setframetime/)(ushort) | يضبط مدة كل إطار بالمللي ثانية، مما يضمن توقيتًا متسقًا عبر تسلسل الصورة. تقوم هذه الطريقة بتعيين وقت العرض لكل إطار بشكل موحد، مما يسمح بالتحكم الدقيق في سرعة الرسوم المتحركة. تغيير هذه القيمة سيعيد ضبط التأخير لجميع الإطارات. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | يضبط بكسل الصورة للموقع المحدد. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | يعيّن الدقة لهذا [`RasterImage`](../../aspose.imaging/rasterimage/). |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | يحوّل الصورة النقطية إلى bitmap. هذه الطريقة غير مدعومة في الإصدارات بدءًا من .Net7.0 وما فوق. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |

## أمثلة

تصدير جزء من الرسوم المتحركة من صورة GIF بناءً على الفاصل الزمني.

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

يوضح هذا المثال كيفية إنشاء صورة GIF وحفظها إلى ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء كتلة إطار GIF بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // ملء الكتلة بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

إنشاء صورة GIF متعددة الصفحات باستخدام صور نقطية ذات صفحة واحدة.

```csharp
[C#]

static void Main(string[] args)
{
    // تحميل الإطارات
    var frames = LoadFrames("Animation frames").ToArray();

    // إنشاء صورة GIF باستخدام الإطار الأول
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // إضافة إطارات إلى صورة GIF باستخدام طريقة AddPage
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // حفظ صورة GIF
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### انظر أيضًا

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif/)
* assembly [Aspose.Imaging](../../)


