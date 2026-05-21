---
title: "الفئة ApngImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Apng.ApngImage. واجهة برمجة التطبيقات لتنسيق ملف صورة PNG المتحركة (Animated Portable Network Graphics) هي حل متعدد الاستخدامات للمطورين الذين يرغبون في دمج المحتوى المتحرك في تطبيقاتهم. توفر هذه الواجهة تحكمًا واسعًا في إعدادات الإطارات مما يسمح للمستخدمين بتحديد معلمات خاصة بالإطار بما في ذلك مدة الحلقة وإعدادات ملف PNG. باستخدام هذه الأداة الغنية بالميزات يمكنك بسهولة إدارة وتحسين عرض صور APNG واستيراد وتصدير الصور، مما يعزز الجوانب الديناميكية والتفاعلية لتطبيقاتك."
type: docs
weight: 1350
url: /ar/net/aspose.imaging.fileformats.apng/apngimage/
---
## ApngImage class

واجهة برمجة التطبيقات لتنسيق ملف صورة PNG المتحركة (Animated Portable Network Graphics) هي حل متعدد الاستخدامات للمطورين الذين يرغبون في دمج المحتوى المتحرك في تطبيقاتهم. توفر هذه الواجهة تحكمًا واسعًا في إعدادات الإطارات، مما يسمح للمستخدمين بتحديد معلمات خاصة بالإطار، بما في ذلك مدة الحلقة وإعدادات ملف PNG. باستخدام هذه الأداة الغنية بالميزات، يمكنك إدارة وعرض صور APNG بسهولة وتحسينها، واستيراد وتصدير الصور، مما يعزز الجوانب الديناميكية والتفاعلية لتطبيقاتك.

```csharp
public sealed class ApngImage : RasterCachedMultipageImage, IMultipageImageExt
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ApngImage](apngimage/)(ApngOptions, int, int) | ابدأ العمل مع الفئة `ApngImage` بإنشاء نسخة جديدة بسهولة. مثالي للمطورين الذين يرغبون في بدء استخدام كائنات ApngImage بسرعة وكفاءة في مشاريعهم. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | الحصول على عدد البتات لكل بكسل في الصورة. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [DefaultFrameTime](../../aspose.imaging.fileformats.apng/apngimage/defaultframetime/) { get; set; } | قم بضبط مدة الإطار الافتراضية لإنشاء إطارات جديدة بسهولة باستخدام هذه الخاصية المرنة. مثالي للمطورين الذين يسعون لتخصيص توقيت الإطارات بفعالية في رسوماتهم المتحركة. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.apng/apngimage/fileformat/) { get; } | احصل بسرعة على معلومات حول تنسيق الملف باستخدام هذه الخاصية المريحة. مثالي للمطورين الذين يحتاجون إلى استرجاع تفاصيل حول تنسيق ملفات Apng الخاصة بهم بسهولة. |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت الصورة لها لون شفاف. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | الحصول على ارتفاع الصورة. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | الحصول على أو تعيين الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذه [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | الحصول على شفافية هذه الصورة. |
| [Interlaced](../../aspose.imaging.fileformats.apng/apngimage/interlaced/) { get; } | حدد بسرعة ما إذا كان هذا الكائن [`PngImage`](../../aspose.imaging.fileformats.png/pngimage/) متشابكًا باستخدام هذه الخاصية المريحة. مثالي للمطورين الذين يحتاجون إلى التحقق من حالة التشابك في صور PNG بسهولة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | الحصول على أو تعيين بيانات XMP من الإطار. |
| [NumPlays](../../aspose.imaging.fileformats.apng/apngimage/numplays/) { get; set; } | تحكم بسهولة في عدد مرات تكرار الرسوم المتحركة الخاصة بك باستخدام هذه الخاصية المتعددة الاستخدامات. مثالي للمطورين الذين يسعون إلى تحكم دقيق في سلوك الرسوم المتحركة، مع دعم التكرار اللانهائي في حال كانت القيمة تساوي 0. |
| override [PageCount](../../aspose.imaging.fileformats.apng/apngimage/pagecount/) { get; } | استرجع إجمالي عدد الصفحات في ملف الصورة الخاص بك بسهولة باستخدام هذه الخاصية. مثالي للمطورين الذين يحتاجون إلى وصول سريع إلى معلومات عدد الصفحات. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | يحصل أو يعيّن إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرةً قبل حفظ كل صفحة. |
| override [Pages](../../aspose.imaging.fileformats.apng/apngimage/pages/) { get; } | احصل بسهولة على صفحات صورتك باستخدام هذه الخاصية المريحة. مثالي للمطورين الذين يرغبون في وصول سريع وسهل إلى الصفحات الفردية للتعديل. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | يحصل أو يعيّن محول الألوان المخصص |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat/) { get; } | يحصل على تنسيق البيانات الخام. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات بدون تحويل. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | يحصل أو يعيّن فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق. |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | يحصل أو يعيّن محول الألوان المفهرسة |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | يحصل على حجم السطر الخام بالبايت. |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor/) { get; set; } | يحصل على لون الشفافية في الصورة. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات التعريف XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution/) { get; set; } | يحصل أو يعيّن الدقة العمودية، بوحدة البكسل لكل بوصة، لهذا [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width/) { get; } | يحصل على عرض الصورة. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe/#addframe)() | أضف إطارًا جديدًا بسهولة إلى نهاية مجموعة الإطارات الخاصة بك باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يرغبون في توسيع مجموعة إطاراتهم ديناميكيًا للرسوم المتحركة ذات الصور متعددة الإطارات. سيتم إنشاء إطار جديد وفقًا لحجم الصورة الحالية. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe/#addframe_1)(RasterImage) | قم بتوسيع مجموعة إطاراتك بسهولة بإضافة إطار جديد إلى النهاية باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يسعون لتعزيز رسومهم المتحركة للصور متعددة الإطارات ديناميكيًا. سيتم ملء محتويات الإطار الجديد من الصورة المحددة. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe/#addframe_2)(RasterImage, uint) | قم بتوسيع مجموعة إطاراتك بسلاسة عن طريق إلحاق إطار جديد باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في إثراء رسومهم المتحركة للصور متعددة الإطارات. سيتم ملء محتويات الإطار الجديد من الصورة المحددة. |
| [AddPage](../../aspose.imaging.fileformats.apng/apngimage/addpage/)(RasterImage) | أضف صفحة جديدة إلى الصورة بسهولة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في توسيع محتوى ملفات الصور الخاصة بهم بشكل ديناميكي. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.apng/apngimage/adjustbrightness/)(int) | قم بضبط *السطوع* للصورة بسهولة باستخدام هذه الطريقة البديهية، مع تحديد معامل السطوع المطلوب. مثالي للمطورين الذين يرغبون في تعزيز أو خفض السطوع الكلي للصور بشكل ديناميكي. |
| override [AdjustContrast](../../aspose.imaging.fileformats.apng/apngimage/adjustcontrast/)(float) | حسّن التباين في [`Image`](../../aspose.imaging/image/) لتبرز التفاصيل باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تحسين الوضوح البصري وتأثير صورهم بشكل ديناميكي. |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma/#adjustgamma)(float) | طبق تصحيح غاما على الصورة باستخدام معامل عشري مع هذه الطريقة البديهية. مثالي للمطورين الذين يسعون إلى تحكم دقيق في الألوان داخل صورهم. |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma/#adjustgamma_1)(float, float, float) | قم بإجراء تصحيح غاما على الصورة بشكل منفصل لقنوات الأحمر والأخضر والأزرق باستخدام معاملات فردية مع هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في ضبط توازن الألوان بدقة وتعزيز الجودة البصرية لصورهم. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | ينفّذ تعديلًا تلقائيًا متكيفًا للسطوع والتباين عبر الصورة بأكملها. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | يقوم بتدوير الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من بيانات Exif. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح، مما يعزز تجربة المستخدم ويقضي على الحاجة إلى التعديلات اليدوية. من خلال تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، مما يوفر تجربة مشاهدة سلسة عبر مختلف المنصات والأجهزة. تبسط عملية التدوير الآلية معالجة الصور وتحسن قابلية الاستخدام العامة، خاصةً عند التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المتنوعة. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.apng/apngimage/binarizebradley/#binarizebradley_1)(double, int) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| override [BinarizeFixed](../../aspose.imaging.fileformats.apng/apngimage/binarizefixed/)(byte) | قم بتحويل الصورة إلى ثنائية بسهولة باستخدام عتبة محددة مسبقًا مع هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تحويل الصور إلى صيغة ثنائية، مما يبسطها للمعالجة أو التحليل اللاحق. |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.apng/apngimage/binarizeotsu/)() | قم بتنفيذ التحويل إلى ثنائي على الصورة باستخدام عتبة أوتسو مع هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تحديد العتبة المثلى تلقائيًا لتحويل الصور إلى صيغة ثنائية، مما يعزز وضوحها وملاءمتها للتحليل اللاحق. |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata/)() | يخزن البيانات بشكل خاص. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop/#crop)(Rectangle) | قم بقص الصورة بسهولة للتركيز على مناطق محددة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تحسين تكوين صورهم بشكل ديناميكي. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop/#crop_1)(int, int, int, int) | قم بقص الصورة مع تعديل الإزاحات بسلاسة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يسعون إلى تحكم دقيق في عملية القص للتركيز على مناطق محددة في صور Apng الخاصة بهم. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | يقوم بأداء التمويه على الصورة الحالية. |
| override [Dither](../../aspose.imaging.fileformats.apng/apngimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | طبق تأثيرات التمويه بسهولة على الصورة الحالية باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في إضافة نسيج أو تقليل تدرج الألوان في صورهم. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | أدمج توقيعًا رقميًا بناءً على كلمة المرور المقدمة في كل صفحة من الصورة. |
| override [Filter](../../aspose.imaging.fileformats.apng/apngimage/filter/)(Rectangle, FilterOptionsBase) | طبق الفلاتر بسهولة على المستطيل المحدد في الصورة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تحسين أو تعديل مناطق معينة. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | يحصل على بكسل صورة 32-بت ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | يحصل على مصفوفة بكسلات 32-بت ARGB الافتراضية. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.apng/apngimage/getdefaultoptions/)(object[]) | استرجع الخيارات الافتراضية بسهولة باستخدام هذه الطريقة المبسطة. مثالي للمطورين الذين يحتاجون إلى وصول سريع إلى إعدادات صورة Apng الافتراضية. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| override [GetModifyDate](../../aspose.imaging.fileformats.apng/apngimage/getmodifydate/)(bool) | احصل بسرعة على تاريخ ووقت آخر تعديل للصورة المصدر باستخدام هذه الطريقة السهلة الاستخدام. مثالي للمطورين الذين يحتاجون إلى تتبع التغييرات وإدارة الموارد بفعالية. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.apng/apngimage/getoriginaloptions/)() | استرجع الخيارات بناءً على إعدادات الملف الأصلي بسهولة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في الوصول إلى الإعدادات واستخدامها بما يتوافق مع خصائص الملف الأصلي. يمكن أن يساعد ذلك في الحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.imaging/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [`Save`](../../aspose.imaging/image/save/) كمعامل ثانٍ. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | يحصل على بكسل صورة. |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | يحصل على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف عند المسح. |
| override [Grayscale](../../aspose.imaging.fileformats.apng/apngimage/grayscale/)() | حوّل الصورة بسهولة إلى تمثيلها بالدرجات الرمادية باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تحويل الصور الملونة إلى رمادية، مما يبسط عمليات التصور أو التحليل. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe/#insertframe)(int) | أدرج إطارًا جديدًا بسهولة في مجموعة الإطارات الخاصة بك في الموضع المحدد باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يسعون إلى تحكم دقيق في ترتيب الإطارات في رسومهم المتحركة للصور متعددة الإطارات. سيتم إنشاء إطار جديد وفقًا لحجم الصورة الحالية. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe/#insertframe_1)(int, RasterImage) | يدرج إطارًا جديدًا في مجموعة الإطارات الخاصة بالمستخدم عند الفهرس المحدد. سيتم ملء محتويات الإطار الجديد من الصورة المحددة. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe/#insertframe_2)(int, RasterImage, uint) | يدرج إطارًا جديدًا في مجموعة الإطارات الخاصة بالمستخدم عند الفهرس المحدد. سيتم ملء محتويات الإطار الجديد من الصورة المحددة. |
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
| [PopFrameAt](../../aspose.imaging.fileformats.apng/apngimage/popframeat/)(int) | قم بإزالة واسترجاع الإطار عند الفهرس المحدد من مجموعة الإطارات الخاصة بك باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يبحثون عن إدارة فعّالة للإطارات في رسومهم المتحركة. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [RemoveAllFrames](../../aspose.imaging.fileformats.apng/apngimage/removeallframes/)() | امسح مجموعة الإطارات الخاصة بك بإزالة جميع الإطارات باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في إعادة ضبط أو تحديث رسومهم المتحركة. |
| [RemoveFrameAt](../../aspose.imaging.fileformats.apng/apngimage/removeframeat/)(int) | أزل الإطار عند الفهرس المحدد من مجموعة الإطارات الخاصة بك بسلاسة باستخدام هذه الطريقة. مثالي للمطورين الذين يسعون إلى إدارة مبسطة للإطارات في صورهم متعددة الإطارات. سيتم التخلص من الإطار الذي سيُحذف. |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | يزيل بيانات التعريف الخاصة بهذه الصورة عن طريق تعيين قيمة [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) إلى `null`. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [ResetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/resetdefaultimage/)() | أزل الصورة الافتراضية التي تم تعيينها مسبقًا باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في إعادة ضبط أو مسح الصورة الافتراضية في رسومهم المتحركة. بعد ذلك، تصبح الصورة الافتراضية هي الإطار الأول في مجموعة الإطارات الخاصة بالمستخدم (لا يمكن حذفها باستخدام هذه الطريقة). |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize/#resize_1)(int, int, ImageResizeSettings) | تغيير حجم الصورة. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize/#resize_2)(int, int, ResizeType) | غيّر حجم الصورة بسلاسة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تعديل أبعاد صورهم بشكل ديناميكي. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | قم بضبط ارتفاع صورتك بسهولة مع الحفاظ على نسبها باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تغيير حجم الصور بشكل ديناميكي مع الحفاظ على نسبة العرض إلى الارتفاع. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | غيّر عرض الصورة بنسبية بسهولة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في الحفاظ على نسبة أبعاد صورهم أثناء تعديل أبعادها. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | دوّر الصورة حول المركز. |
| override [Rotate](../../aspose.imaging.fileformats.apng/apngimage/rotate/#rotate_1)(float, bool, Color) | دوّر الصورة حول مركزها بسهولة باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في تعديل اتجاه صورهم بشكل ديناميكي. |
| override [RotateFlip](../../aspose.imaging.fileformats.apng/apngimage/rotateflip/)(RotateFlipType) | قم بالتلاعب بالإطار النشط بسهولة عن طريق الدوران أو القلب أو كليهما باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يسعون لتخصيص اتجاهات إطارات الصور. |
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
| [SetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/setdefaultimage/)(RasterImage) | يضبط "الصورة الافتراضية" التي يتم عرضها بواسطة المفككات التي لا تدعم APNG. فئة `ApngImage` تستخدم العنصر الأول من [`Pages`](./pages/) كصفحة افتراضية (رئيسية). |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | يضبط بكسل الصورة للموقع المحدد. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | يعيّن الدقة لهذا [`RasterImage`](../../aspose.imaging/rasterimage/). |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | يحوّل الصورة النقطية إلى bitmap. هذه الطريقة غير مدعومة في الإصدارات بدءًا من .Net7.0 وما فوق. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |

## أمثلة

المثال التالي يوضح كيفية تصدير تنسيق ملف apng APNG من تنسيق متعدد الصفحات غير متحرك آخر.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // إعداد مدة الإطار الافتراضية
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

المثال التالي يوضح كيفية التصدير إلى تنسيق ملف APNG.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // تصدير إلى رسوم متحركة بصيغة APNG مع دورات رسوم متحركة غير محدودة كإعداد افتراضي
    image.Save("Animation1.webp.png", new ApngOptions());
    // إعداد دورات الرسوم المتحركة
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 cycles
}
```

يوضح المثال التالي كيفية إنشاء صورة APNG من صورة نقطية صفحة واحدة أخرى.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 s
const int FrameDuration = 70; // 70 ms
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // يمكن تعيين الوقت الافتراضي لإطار الصورة هناك: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // جارٍ التنظيف لأن الصورة تحتوي على إطار واحد افتراضيًا
        apngImage.RemoveAllFrames();

        // إضافة الإطار الأول
        apngImage.AddFrame(sourceImage);

        // إضافة إطارات وسطية
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // إضافة الإطار الأخير
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### انظر أيضًا

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Apng](../../aspose.imaging.fileformats.apng/)
* assembly [Aspose.Imaging](../../)


