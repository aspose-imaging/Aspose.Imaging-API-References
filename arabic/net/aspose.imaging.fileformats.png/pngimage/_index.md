---
title: "الفئة PngImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Png.PngImage. قم بمعالجة صور PNG النقطية (Portable Network Graphics) باستخدام واجهة برمجة التطبيقات المتعددة الاستخدامات التي تدعم مستويات الضغط ومختلف أعماق الألوان بما في ذلك الرمادي، اللون المفهرس، TrueColor والقنوات ألفا. عالج بيانات XMP الوصفية بسلاسة مما يتيح إدارة شاملة للبيانات الوصفية للصور، مع تحميل صور PNG بسهولة، وإجراء تعديلات متنوعة، وتطبيق الفلاتر، وتحويل الصور إلى صيغ ملفات أخرى لتحقيق أقصى قدر من المرونة والتخصيص."
type: docs
weight: 7560
url: /ar/net/aspose.imaging.fileformats.png/pngimage/
---
## PngImage class

قم بمعالجة صور الرسوميات النقطية (PNG) باستخدام واجهة برمجة التطبيقات المتعددة الاستخدامات لدينا، التي تدعم مستويات الضغط وعمق الألوان المتنوعة بما في ذلك الرمادي، اللون المفهرس، TrueColor، وقنوات ألفا. عالج بيانات XMP الوصفية بسلاسة، مما يتيح إدارة شاملة لبيانات وصف الصورة، بينما يمكنك بسهولة تحميل صور PNG، وإجراء تعديلات متنوعة، وتطبيق الفلاتر، وتحويل الصور إلى صيغ ملفات أخرى لتحقيق أقصى قدر من التنوع والتخصيص.

```csharp
public class PngImage : RasterCachedImage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PngImage](pngimage/#constructor_1)(RasterImage) | ينشئ مثيلًا جديدًا للفئة `PngImage` عن طريق توفير صورة نقطية كمعامل. يتيح هذا المُنشئ للمطورين تهيئة كائن صورة PNG مباشرةً باستخدام صورة نقطية موجودة، مما يبسط عملية العمل مع صور PNG في تطبيقاتهم. |
| [PngImage](pngimage/#constructor_5)(Stream) | ينشئ مثيلًا جديدًا للفئة `PngImage` عن طريق تهيئتها باستخدام تدفق. يتيح هذا المُنشئ للمطورين تحميل صور PNG مباشرةً من تدفق، مما يوفر مرونة في استرجاع الصور من مصادر مختلفة. |
| [PngImage](pngimage/#constructor_6)(string) | يبني مثيلًا جديدًا للفئة `PngImage` باستخدام معامل المسار لتحديد موقع ملف الصورة المراد تحميله. يتيح هذا المُنشئ للمطورين إنشاء صور PNG بسهولة عن طريق تحميلها من ملف، مما يبسط عملية العمل مع صور PNG في تطبيقاتهم. |
| [PngImage](pngimage/#constructor_3)(int, int) | قم بتهيئة كائن جديد من الفئة `PngImage` عن طريق توفير معلمات العرض والارتفاع. يبسط هذا المُنشئ إنشاء صور PNG من خلال السماح للمطورين بتحديد الأبعاد مباشرةً، مما يسهل إدارة فعّالة لبيانات صورة PNG داخل تطبيقاتهم. |
| [PngImage](pngimage/#constructor_2)(RasterImage, PngColorType) | ينشئ مثيلًا جديدًا للفئة `PngImage` عن طريق تحديد صورة نقطية ونوع اللون. يتيح هذا المُنشئ للمطورين تحويل الصور النقطية مباشرةً إلى صيغة PNG مع تحديد نوع اللون المطلوب، مما يوفر مرونة في تمثيل الألوان. |
| [PngImage](pngimage/#constructor_7)(string, PngColorType) | يُهيئ مثيلًا جديدًا للفئة `PngImage` عن طريق تحديد مسار ملف الصورة ونوع اللون. يتيح هذا المُنشئ إنشاء صور PNG بسهولة من ملفات بأنواع ألوان مختلفة، مما يوفر مرونة في التعامل مع صيغ الصور المتنوعة. |
| [PngImage](pngimage/#constructor_4)(int, int, PngColorType) | أنشئ مثيلًا جديدًا من الفئة `PngImage`، مع تحديد معلمات العرض والارتفاع ونوع اللون المطلوبة. يتيح هذا المُنشئ إنشاء صور PNG بسرعة بأبعاد وتكوينات لون مخصصة، مما يسهل توليد الصور بسلاسة لتطبيقات وسير عمل مختلفة. |
| [PngImage](pngimage/#constructor)(PngOptions, int, int) | قم بتهيئة مثيل جديد للفئة `PngImage`، مع دمج خيارات PNG إلى جانب معلمات العرض والارتفاع. يمنح هذا المُنشئ المطورين القدرة على إنشاء صور PNG بإعدادات وأبعاد قابلة للتخصيص، مما يوفر مرونة في توليد الصور لمجالات استخدام متنوعة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| override [BackgroundColor](../../aspose.imaging.fileformats.png/pngimage/backgroundcolor/) { get; set; } | يسترجع لون الخلفية للصورة، إذا تم تحديده. هذه الخاصية مفيدة للتطبيقات التي تحتاج إلى التعرف على لون خلفية الصورة وربما تعديلها. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.png/pngimage/bitsperpixel/) { get; } | استرجع قيمة البتات لكل بكسل للصورة. توفر هذه الخاصية معلومات حيوية حول عمق ألوان الصورة، مما يمكّن المطورين من فهم مستوى التفاصيل ودقة الألوان الموجودة في بيانات الصورة. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.png/pngimage/fileformat/) { get; } | يسترجع تنسيق الملف المرتبط بمثيل الصورة. توفر هذه الخاصية معلومات أساسية حول نوع الملف، مما يتيح معالجة فعّالة بناءً على متطلبات التنسيق المحددة. |
| override [HasAlpha](../../aspose.imaging.fileformats.png/pngimage/hasalpha/) { get; } | يرجع قيمة منطقية تُظهر ما إذا كانت الصورة تحتوي على قناة ألفا، التي تحدد شفافيتها. هذه الخاصية مفيدة للتطبيقات التي تحتاج إلى التعامل مع الشفافية، مما يسمح للمطورين بتحديد ما إذا كانت هناك حاجة لمعالجة إضافية للتعامل مع المناطق الشفافة في الصورة. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.png/pngimage/hasbackgroundcolor/) { get; set; } | يسترجع قيمة منطقية تُظهر ما إذا كانت الصورة تحتوي على لون خلفية. هذه الخاصية مفيدة للتطبيقات التي تحتاج إلى معرفة ما إذا كانت الصورة تشمل لون خلفية، وهو ما قد يكون مهمًا لمهام معالجة مختلفة مثل التركيب، التصيير، أو التصدير. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.png/pngimage/hastransparentcolor/) { get; set; } | يوفر قيمة منطقية تُظهر ما إذا كانت الصورة تحتوي على لون شفاف. هذه الخاصية حاسمة للتطبيقات التي تحتاج إلى التعامل مع الشفافية، مما يسمح للمطورين بتحديد ما إذا كانت هناك حاجة لمعالجة إضافية للتعامل مع المناطق الشفافة في الصورة. |
| override [Height](../../aspose.imaging.fileformats.png/pngimage/height/) { get; } | احصل على ارتفاع الصورة. تُرجع هذه الخاصية البُعد العمودي للصورة، مما يتيح للمطورين تحديد حجمها بالبكسل على المحور العمودي. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.png/pngimage/horizontalresolution/) { get; set; } | استرجع أو عدّل الدقة الأفقية للصورة. تمثل هذه الخاصية عدد البكسلات لكل بوصة على المحور الأفقي للصورة. تعديل هذه الدقة يمكن أن يؤثر على الحجم الفعلي للصورة عند طباعتها أو عرضها. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | الحصول على شفافية هذه الصورة. |
| [Interlaced](../../aspose.imaging.fileformats.png/pngimage/interlaced/) { get; } | يسترجع قيمة منطقية تُظهر ما إذا كان `PngImage` متشابكًا، مما يحدد ما إذا كانت بيانات الصورة مخزنة بطريقة تدريجية لتحميل أو نقل أسرع. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsInterlaced](../../aspose.imaging.fileformats.png/pngimage/isinterlaced/) { get; } | يرجع قيمة منطقية تُظهر ما إذا كان مثيل الصورة متشابكًا. هذه الخاصية حاسمة لتحسين استراتيجيات التحميل وضمان أداء فعّال أثناء مهام معالجة أو عرض الصور. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | يحصل على بيانات تعريف الصورة. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | يحصل أو يعيّن محول الألوان المخصص |
| override [RawDataFormat](../../aspose.imaging.fileformats.png/pngimage/rawdataformat/) { get; } | يصل إلى تنسيق البيانات الخام للصورة. توفر هذه الخاصية نظرة على كيفية تنظيم بيانات الصورة داخليًا، وهو ما يمكن أن يكون مفيدًا لمهام معالجة الصور المتقدمة أو تحويل الصيغ. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات بدون تحويل. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | يحصل أو يعيّن فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق. |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | يحصل أو يعيّن محول الألوان المفهرسة |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | يحصل على حجم السطر الخام بالبايت. |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| override [TransparentColor](../../aspose.imaging.fileformats.png/pngimage/transparentcolor/) { get; set; } | يسترجع اللون الشفاف للصورة، إذا كان موجودًا. هذه الخاصية ذات قيمة للتطبيقات التي تتطلب معالجة دقيقة للمناطق الشفافة داخل الصور، مما يتيح للمطورين الوصول إلى اللون الشفاف المحدد واستخدامه. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات التعريف XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| override [VerticalResolution](../../aspose.imaging.fileformats.png/pngimage/verticalresolution/) { get; set; } | يوفر إمكانية الوصول إلى الدقة العمودية للصورة. يمكن للمطورين استخدام هذه الخاصية لاسترجاع أو تعديل إعداد الدقة، والذي يشير إلى عدد البكسلات لكل بوصة (PPI) على المحور العمودي للصورة. |
| override [Width](../../aspose.imaging.fileformats.png/pngimage/width/) { get; } | يسمح باسترجاع عرض الصورة، موفرًا معلومات أساسية حول أبعادها. تُستخدم هذه الخاصية بشكل متكرر من قبل المطورين لتحديد عرض الصورة، مما يمكنهم من تنفيذ عمليات مختلفة بناءً على حجمها. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness/)(int) | ضبط السطوع للصورة. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast/)(float) | تباين الصورة |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma/)(float) | تصحيح جاما للصورة. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma/)(float, float, float) | تصحيح جاما للصورة. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedimage/analyzepercentagedigitalsignature/)(string) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | ينفّذ تعديلًا تلقائيًا متكيفًا للسطوع والتباين عبر الصورة بأكملها. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | يقوم بتدوير الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من بيانات Exif. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح، مما يعزز تجربة المستخدم ويقضي على الحاجة إلى التعديلات اليدوية. من خلال تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، مما يوفر تجربة مشاهدة سلسة عبر مختلف المنصات والأجهزة. تبسط عملية التدوير الآلية معالجة الصور وتحسن قابلية الاستخدام العامة، خاصةً عند التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المتنوعة. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley/)(double) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley/)(double, int) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed/)(byte) | تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu/)() | تحويل الصورة إلى ثنائية باستخدام عتبة Otsu |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [Blend](../../aspose.imaging/rastercachedimage/blend/)(Point, RasterImage, Rectangle, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) الأساسي. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| override [Crop](../../aspose.imaging/rastercachedimage/crop/)(Rectangle) | قص الصورة. |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | قص الصورة مع إزاحات. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | يقوم بأداء التمويه على الصورة الحالية. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | يقوم بأداء التمويه على الصورة الحالية. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedimage/embeddigitalsignature/)(string) | إدراج توقيع رقمي بناءً على كلمة المرور المقدمة داخل الصورة باستخدام تقنية التضمين. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter/)(Rectangle, FilterOptionsBase) | يفلتر المستطيل المحدد. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | يحصل على بكسل صورة 32-بت ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | يحصل على مصفوفة بكسلات 32-بت ARGB الافتراضية. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.png/pngimage/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| override [GetModifyDate](../../aspose.imaging.fileformats.png/pngimage/getmodifydate/)(bool) | يسترجع الطابع الزمني الذي يشير إلى أحدث تعديل للصور المصدرية. توفر هذه الطريقة إمكانية الوصول إلى بيانات التعريف الحيوية، مما يمكّن التطبيقات من معرفة متى تم تعديل الصورة آخر مرة، ويساعد في تتبع الإصدارات وإدارة المحتوى. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.png/pngimage/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.imaging/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [`Save`](../../aspose.imaging/image/save/) كمعامل ثاني. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | يحصل على بكسل صورة. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | يحصل على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف عند المسح. |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale/)() | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| override [IsDigitalSigned](../../aspose.imaging/rastercachedimage/isdigitalsigned/)(string, int) | يُجري فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والحدّ المحدد. |
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
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle/)(bool, Color) | يضبط الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئياً للتخلص من الانحراف. تستخدم هذه الطريقة [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) و[`Rotate`](../../aspose.imaging/rasterimage/rotate/) الطرق. |
| override [NormalizeHistogram](../../aspose.imaging/rastercachedimage/normalizehistogram/)() | يضبط هيستوجرام الصورة — يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | يزيل بيانات التعريف الخاصة بهذه الصورة عن طريق تعيين قيمة [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) إلى `null`. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(int, byte, int) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(int) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize/)(int, int, ImageResizeSettings) | تغيير حجم الصورة. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize/)(int, int, ResizeType) | تغيير حجم الصورة. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | يُعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | دوّر الصورة حول المركز. |
| override [Rotate](../../aspose.imaging/rastercachedimage/rotate/)(float, bool, Color) | دوّر الصورة حول المركز. |
| override [RotateFlip](../../aspose.imaging/rastercachedimage/rotateflip/)(RotateFlipType) | يدور أو يقلب أو يدور ويقلب الصورة. |
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
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | يضبط بكسل الصورة للموقع المحدد. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | يعيّن الدقة لهذا [`RasterImage`](../../aspose.imaging/rasterimage/). |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | يحوّل الصورة النقطية إلى bitmap. هذه الطريقة غير مدعومة في الإصدارات بدءًا من .Net7.0 وما فوق. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة PNG من ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة PNG من ملف.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // حوّل الصورة إلى تمثيل تدرج الرمادي.
    pngImage.Grayscale();

    // احفظ إلى ملف.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### انظر أيضًا

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* namespace [Aspose.Imaging.FileFormats.Png](../../aspose.imaging.fileformats.png/)
* assembly [Aspose.Imaging](../../)


