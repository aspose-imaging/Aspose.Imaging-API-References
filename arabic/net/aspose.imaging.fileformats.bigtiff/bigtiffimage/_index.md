---
title: "الفئة BigTiffImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.BigTiff.BigTiffImage. باستخدام الفئة BigTiffImage يمكنك معالجة ملفات تنسيق صورة BigTiff بسهولة. توفر واجهة برمجة التطبيقات الخاصة بنا معالجة سلسة وخيارات تخصيص تضمن معالجة مثالية لبيانات الصور ذات النطاق الواسع مع ميزات متعددة تناسب متطلباتك المحددة"
type: docs
weight: 1370
url: /ar/net/aspose.imaging.fileformats.bigtiff/bigtiffimage/
---
## BigTiffImage class

باستخدام الفئة `BigTiffImage` يمكنك معالجة ملفات تنسيق صورة BigTiff بسهولة. توفر واجهة برمجة التطبيقات الخاصة بنا معالجة سلسة وخيارات تخصيص، مما يضمن معالجة مثالية لبيانات الصور ذات النطاق الواسع مع ميزات متعددة تناسب متطلباتك المحددة.

```csharp
public sealed class BigTiffImage : TiffImage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [BigTiffImage](bigtiffimage/#constructor)(TiffFrame) | أنشئ مثيلًا جديدًا للفئة `BigTiffImage` بتهيئته باستخدام معامل TiffFrame. مثالي للمطورين الذين يبحثون عن طريقة مريحة للعمل مع كائنات BigTiffImage، مما يضمن المرونة وسهولة التكامل في مشاريعهم. |
| [BigTiffImage](bigtiffimage/#constructor_1)(TiffFrame[]) | ابدأ باستخدام الفئة `BigTiffImage` بسلاسة بإنشاء مثيل جديد باستخدام معامل قائمة TiffFrames. مثالي للمطورين الذين يبحثون عن طريقة مباشرة للعمل مع كائنات BigTiffImage التي تحتوي على إطارات متعددة، مما يضمن كفاءة مشاريعهم. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/activeframe/) { get; set; } | قم بإدارة الإطار النشط بسلاسة، مما يسهل التنقل الديناميكي والتلاعب داخل السياق المحدد. مكن تطبيقك من التفاعل بفعالية مع المحتوى المتعدد الوسائط، مما يعزز تفاعل المستخدم والإنتاجية. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | الحصول على عدد البتات لكل بكسل في الصورة. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [ByteOrder](../../aspose.imaging.fileformats.tiff/tiffimage/byteorder/) { get; set; } | قم بتبديل ترتيب البايت لملفات TIFF بسلاسة، مع ضمان تحكم دقيق في تفسير البيانات. مكن تطبيقاتك من المرونة للتكيف مع مواصفات الملفات المتنوعة، مما يعزز التوافق والكفاءة في معالجة البيانات. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.bigtiff/bigtiffimage/fileformat/) { get; } | يحصل على تنسيق الملف لهذه الحالة من [`Image`](../../aspose.imaging/image/). |
| [Frames](../../aspose.imaging.fileformats.tiff/tiffimage/frames/) { get; } | استرجع مصفوفة من حالات [`TiffFrame`](../../aspose.imaging.fileformats.tiff/tiffframe/)، مما يتيح وصولًا شاملاً ومعالجة للإطارات الفردية داخل صورة TIFF. استغل قوة هذه المصفوفة لتبسيط سير عمل معالجة الصور، مع ضمان تحكم دقيق وتحسين المحتوى البصري. |
| override [HasAlpha](../../aspose.imaging.fileformats.tiff/tiffimage/hasalpha/) { get; } | حدد ما إذا كانت الصورة تحتوي على قناة ألفا، مما يوفر معلومات حاسمة لعمليات العرض والتجميع. دمج هذه الميزة لتحسين سير عمل المعالجة البصرية، وضمان تمثيل دقيق ومعالجة للعناصر الشفافة. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت الصورة لها لون شفاف. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | الحصول على ارتفاع الصورة. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/horizontalresolution/) { get; set; } | استرجع الدقة الأفقية للـ[`Image`](../../aspose.imaging/image/) المحدد بوحدة بكسل لكل بوصة، مما يسهل الضبط الدقيق وقدرات العرض. احصل على بيانات التعريف الأساسية للصورة بسهولة، مما يتيح سير عمل معالجة صور مبسط لتجربة مستخدم محسنة. |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | الحصول على شفافية هذه الصورة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | الحصول على أو تعيين بيانات XMP من الإطار. |
| override [PageCount](../../aspose.imaging.fileformats.tiff/tiffimage/pagecount/) { get; } | استرجع العدد الإجمالي للصفحات داخل المستند المحدد، مما يسهل التنقل الفعال وإدارة المحتوى متعدد الصفحات. دمج هذه الوظيفة لتعزيز تجربة المستخدم، مما يتيح الوصول السلس إلى هياكل المستند الشاملة. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | يحصل أو يعيّن إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرةً قبل حفظ كل صفحة. |
| override [Pages](../../aspose.imaging.fileformats.tiff/tiffimage/pages/) { get; } | الوصول إلى صفحات المستند بسلاسة، مما يتيح التنقل الديناميكي والتعامل داخل هيكل المحتوى. مكن تطبيقك من وصول فعال إلى الصفحات الفردية، مما يسهل معالجة المستندات بشكل مبسط وتعزيز تفاعل المستخدم. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| override [PremultiplyComponents](../../aspose.imaging.fileformats.tiff/tiffimage/premultiplycomponents/) { get; set; } | أشر إذا كانت المكونات تحتاج إلى الضرب المسبق، لضمان معالجة فعّالة للعناصر البصرية. حسّن عمليات العرض عن طريق تبديل هذه الخاصية، مما يبسط سير عمل الرسومات لأداء محسن. |
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
| override [VerticalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/verticalresolution/) { get; set; } | الوصول إلى الدقة العمودية للـ[`Image`](../../aspose.imaging/image/) المحدد بوحدة بكسل لكل بوصة، مما يتيح ضبطًا دقيقًا وتحسينات في العرض. استخدم بيانات الصورة الأساسية بسهولة لتبسيط سير عمل معالجة الصور، وضمان جودة وأداء فائق في تطبيقاتك. |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width/) { get; } | يحصل على عرض الصورة. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.imaging.fileformats.tiff/tiffimage/add/)(TiffImage) | أضف الإطارات من الصورة المحددة بسلاسة إلى الإطار الحالي، مدمجًا محتواها ومعززًا مرونة التركيب. دمج هذه الطريقة لتبسيط إدارة الإطارات ومعالجتها داخل تطبيقك، مما يسهل التعامل الفعال مع الصور متعددة الإطارات. |
| [AddFrame](../../aspose.imaging.fileformats.tiff/tiffimage/addframe/)(TiffFrame) | دمج الإطار المحدد بسلاسة في الصورة، موسعًا محتواها وتنوعها. استخدم هذه الطريقة لتعزيز تركيب الصورة وإدارتها، مما يتيح معالجة فعّالة للصور متعددة الإطارات داخل تطبيقك. |
| [AddFrames](../../aspose.imaging.fileformats.tiff/tiffimage/addframes/)(TiffFrame[]) | دمج مصفوفة الإطارات بسلاسة في الصورة، مُثريًا محتواها وتنوعها. استخدم هذه الطريقة لتعزيز تركيب الصورة وإدارتها، مما يتيح معالجة فعّالة للصور متعددة الإطارات داخل تطبيقك. |
| override [AddPage](../../aspose.imaging.fileformats.bigtiff/bigtiffimage/addpage/)(RasterImage) | قم بتوسيع صورة BigTiff الخاصة بك بسهولة بإضافة صفحة جديدة باستخدام هذه الطريقة البديهية. مثالية للمطورين الذين يرغبون في تعزيز محتوى صورهم متعددة الصفحات ديناميكيًا. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.tiff/tiffimage/adjustbrightness/)(int) | تنفيذ تعديل *السطوع* للصورة، مما يسمح بتعديل مستويات الإضاءة العامة. دمج هذه الطريقة في سير عمل معالجة الصور لتعزيز الرؤية وتحسين الجودة البصرية للصور داخل تطبيقك. |
| override [AdjustContrast](../../aspose.imaging.fileformats.tiff/tiffimage/adjustcontrast/)(float) | حسّن تباين حالة [`Image`](../../aspose.imaging/image/)، معززًا الفروق بين المناطق الفاتحة والداكنة. دمج هذه الوظيفة لتحسين وضوح الصورة البصري وجودتها العامة داخل تطبيقك. |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma/)(float) | طبق تصحيح جاما على الصورة، معدلاً شدة البكسلات لتحقيق توازن لوني مطلوب. دمج هذه الطريقة في سير عمل معالجة الصور لتحسين الجودة البصرية وزيادة دقة التحليل أو مهام العرض اللاحقة داخل تطبيقك. |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma/)(float, float, float) | نفّذ تصحيح جاما على الصورة باستخدام معاملات فردية لقنوات الأحمر والأخضر والأزرق، مما يسمح بضبط دقيق لتوازن الألوان والتباين. دمج هذه الطريقة في خط أنابيب معالجة الصور لتحقيق تحكم دقيق في عرض الألوان وتعزيز الدقة البصرية داخل تطبيقك. |
| [AlignResolutions](../../aspose.imaging.fileformats.tiff/tiffimage/alignresolutions/)() | نفّذ طريقة المساعدة AlignResolutions لمزامنة الدقة الأفقية والعمودية، مما يضمن تجانس أبعاد الصورة. تسهّل هذه الوظيفة سير عمل معالجة الصور المبسط من خلال توحيد معلمات الدقة، محسّنةً الجودة البصرية والاتساق عبر مختلف المنصات والأجهزة. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | ينفّذ تعديلًا تلقائيًا متكيفًا للسطوع والتباين عبر الصورة بأكملها. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | يقوم بتدوير الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من بيانات Exif. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح، مما يعزز تجربة المستخدم ويقضي على الحاجة إلى التعديلات اليدوية. من خلال تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، مما يوفر تجربة مشاهدة سلسة عبر مختلف المنصات والأجهزة. تبسط عملية التدوير الآلية معالجة الصور وتحسن قابلية الاستخدام العامة، خاصةً عند التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المتنوعة. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.tiff/tiffimage/binarizebradley/)(double, int) | نفّذ التحويل إلى ثنائي على الصورة باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة. يحسب هذا النهج عتبات محلية ديناميكيًا بناءً على جوار الصورة، معززًا القدرة على التكيف مع ظروف الإضاءة المتغيرة وضمان تجزئة قوية للمهام اللاحقة داخل تطبيقك. |
| override [BinarizeFixed](../../aspose.imaging.fileformats.tiff/tiffimage/binarizefixed/)(byte) | طبق التحويل إلى ثنائي على الصورة باستخدام عتبة محددة مسبقًا، محولًا إياها إلى صورة ثنائية ذات مناطق أمامية وخلفية متميزة. دمج هذه الطريقة في سير عمل معالجة الصور لتسهيل مهام التجزئة واستخراج الميزات، معززًا دقة وكفاءة تحليل الصور داخل تطبيقك. |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu/)() | استخدم عتبة أوتسو لإجراء التحويل إلى ثنائي على الصورة، محددًا تلقائيًا قيمة العتبة المثلى بناءً على هيستوغرام الصورة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تجزئة فعّالة واستخراج ميزات، معززًا دقة وموثوقية مهام تحليل الصور داخل تطبيقك. |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata/)() | يخزن البيانات بشكل خاص. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop/)(Rectangle) | قم بقص الصورة باستخدام منطقة مستطيلة محددة، مما يتيح اختيارًا دقيقًا للمحتوى المطلوب. دمج هذه الطريقة في سير عمل معالجة الصور لإزالة المناطق غير المرغوبة بفعالية والتركيز على التفاصيل الأساسية، معززًا الوضوح والتركيب العام للصورة. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop/)(int, int, int, int) | قم بقص الصورة عن طريق تحديد إزاحات في الاتجاهات اليسرى، اليمنى، العليا والسفلى. تمكّن هذه الطريقة من اختيار دقيق للجزء المطلوب من الصورة، مسهلةً إزالة المناطق غير المرغوبة بفعالية والتركيز على المحتوى الأساسي. دمج هذه الوظيفة في خط أنابيب معالجة الصور لتعزيز الوضوح والتركيب حسب الحاجة داخل تطبيقك. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | يقوم بأداء التمويه على الصورة الحالية. |
| override [Dither](../../aspose.imaging.fileformats.tiff/tiffimage/dither/)(DitheringMethod, int, IColorPalette) | نفّذ التدرج الضبابي على الصورة الحالية لتحسين جودتها البصرية وتقليل آثار تدرج الألوان. دمج هذه الطريقة في سير عمل معالجة الصور لضمان انتقالات أكثر سلاسة بين الألوان، مما ينتج مظهرًا عامًّا محسّنًا للصورة ووضوحًا أعلى. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | أدمج توقيعًا رقميًا بناءً على كلمة المرور المقدمة في كل صفحة من الصورة. |
| override [Filter](../../aspose.imaging.fileformats.tiff/tiffimage/filter/)(Rectangle, FilterOptionsBase) | تصفية المحتوى داخل المستطيل المحدد، مع تطبيق مرشح معالجة صورة مخصص لتعزيز أو تعديل المنطقة المختارة. دمج هذه الطريقة في سير عمل تعديل الصور لتحقيق تحسينات أو تحويلات مستهدفة داخل تطبيقك. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | يحصل على بكسل صورة 32-بت ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | يحصل على مصفوفة بكسلات 32-بت ARGB الافتراضية. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.tiff/tiffimage/getoriginaloptions/)() | استرجع الخيارات المستمدة من إعدادات الملف الأصلي، مما يسهل الحفاظ السلس على المعلمات الرئيسية مثل عمق البت وغيرها من السمات الأساسية للصورة الأصلية. استخدم هذه الطريقة للحفاظ على الدقة والاتساق في مهام معالجة الصور، وضمان نتائج مثالية دون تغييرات غير ضرورية. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.imaging/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومرّرها إلى طريقة [`Save`](../../aspose.imaging/image/save/) كمعامل ثانٍ. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | يحصل على بكسل صورة. |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | يحصل على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف عند المسح. |
| override [Grayscale](../../aspose.imaging.fileformats.tiff/tiffimage/grayscale/)() | حوّل الصورة إلى تمثيلها الرمادي، محولًا إياها إلى صورة ذات قناة واحدة حيث يمثل كل بكسل الشدة. دمج هذه الطريقة في خط أنابيب معالجة الصور لتبسيط التحليل وتعزيز التوافق مع الخوارزميات القائمة على التدرج الرمادي، مسهلاً مختلف مهام الرؤية الحاسوبية وتحليل الصور داخل تطبيقك. |
| [InsertFrame](../../aspose.imaging.fileformats.tiff/tiffimage/insertframe/)(int, TiffFrame) | أدرج الإطار الجديد في الفهرس المحدد داخل تسلسل الإطارات، مما يضمن تحكمًا دقيقًا في ترتيب الإطارات. استخدم هذه الطريقة لإدارة تسلسلات الإطارات بفعالية، مسهلاً التلاعب الديناميكي وتنظيم محتوى الصورة داخل تطبيقك. |
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
| override [NormalizeAngle](../../aspose.imaging.fileformats.tiff/tiffimage/normalizeangle/)(bool, Color) | استخدم طريقة NormalizeAngle المصممة خصيصًا لمستندات النص الممسوحة ضوئيًا لتصحيح المسحات المائلة، مما يضمن محاذاة دقيقة. دمج هذه الوظيفة بسلاسة في سير عمل معالجة النصوص لتعزيز قابلية قراءة الوثائق وجودتها، وتحسين الكفاءة العامة في مهام التعرف على النص وتحليلها. تستخدم هذه الطريقة [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) و[`Rotate`](../../aspose.imaging.fileformats.tiff/tiffimage/rotate/). |
| override [NormalizeHistogram](../../aspose.imaging/rastercachedmultipageimage/normalizehistogram/)() | يضبط هيستوجرام الصورة — يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe/)(int) | قم بإزالة الإطار المحدد بواسطة فهرسه من تسلسل الصور بسهولة، مما يبسط إدارة الإطارات داخل تطبيقك. دمج هذه الوظيفة لتعزيز الكفاءة والدقة في معالجة الإطارات، وتسهيل تنظيم وعرض محتوى الصورة بسلاسة. |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe/)(TiffFrame) | قم بإزالة الإطار المحدد من تسلسل الصور بفعالية، مما يسهل إدارة الإطارات داخل تطبيقك. دمج هذه الوظيفة لتعزيز الدقة والمرونة في معالجة الإطارات، وضمان تنظيم وعرض محتوى الصورة بسلاسة. |
| override [RemoveMetadata](../../aspose.imaging.fileformats.tiff/tiffimage/removemetadata/)() | يزيل بيانات التعريف لهذا الكائن الصورة عن طريق تعيين قيم [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) و[`ExifData`](../../aspose.imaging.exif/ihasexifdata/exifdata/) إلى `null`. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [ReplaceFrame](../../aspose.imaging.fileformats.tiff/tiffimage/replaceframe/)(int, TiffFrame) | استبدل الإطار في الموضع المحدد بإطار آخر بسلاسة، مما يسهل إدارة الإطارات الديناميكية داخل تسلسل الصور. دمج هذه الطريقة لتعزيز المرونة والدقة في معالجة الإطارات، وضمان تنظيم وعرض محتوى الصورة بأفضل شكل داخل تطبيقك. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize/)(int, int, ImageResizeSettings) | اضبط حجم الصورة بناءً على الإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد ونسبة العرض إلى الارتفاع وسلوك التحجيم. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق عمليات تغيير حجم مخصصة وفقًا لمتطلبات تطبيقك المحددة. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize/)(int, int, ResizeType) | غيّر حجم الصورة وفقًا لنوع تغيير الحجم المحدد، مما يسهل تعديل أبعاد الصورة بمرونة مع الحفاظ على نسبة العرض إلى الارتفاع أو تطبيق خوارزميات تحجيم محددة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تحكم دقيق في عمليات تغيير الحجم داخل تطبيقك. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizeheightproportionally/)(int, ResizeType) | قم بإجراء تعديل نسبي لارتفاع الصورة، مع الحفاظ على نسبة العرض إلى الارتفاع لضمان تكامل بصري ثابت. استخدم هذه الطريقة لتغيير حجم الصور ديناميكيًا داخل تطبيقك، وضمان عرض مثالي عبر منصات وأجهزة متنوعة دون الإضرار بجودة المحتوى. |
| [ResizeProportional](../../aspose.imaging.fileformats.tiff/tiffimage/resizeproportional/)(int, int, ResizeType) | قم بإجراء تغيير حجم نسبي على الصورة، مع الحفاظ على نسبة العرض إلى الارتفاع أثناء تعديل أبعادها. استخدم هذه الطريقة لتكبير الصور ديناميكيًا داخل تطبيقك، وضمان تمثيل بصري ثابت لتكامل المحتوى. سيقوم تغيير الحجم النسبي بتغيير حجم كل إطار وفقًا للنسبة *newWidth*/العرض و*newHeight*/الارتفاع. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizewidthproportionally/)(int, ResizeType) | اضبط عرض الصورة مع الحفاظ على نسبة العرض إلى الارتفاع، مما يضمن تغيير حجم نسبي لتقديم بصري مثالي. استخدم هذه الطريقة لتكبير الصور ديناميكيًا داخل تطبيقك، مما يسهل عرضًا ثابتًا وجذابًا عبر مختلف سياقات العرض. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | دوّر الصورة حول المركز. |
| override [Rotate](../../aspose.imaging.fileformats.tiff/tiffimage/rotate/)(float, bool, Color) | دوّر الصورة حول نقطة مركزها بزاوية محددة، مما يتيح تعديلًا دقيقًا للاتجاه. دمج هذه الوظيفة في خط أنابيب معالجة الصور لتسهيل التحولات الدقيقة، وضمان محاذاة وعرض مثالي للمحتوى البصري داخل تطبيقك. |
| override [RotateFlip](../../aspose.imaging.fileformats.tiff/tiffimage/rotateflip/)(RotateFlipType) | قم بأداء تدوير أو عكس أو مزيج من العمليتين حصريًا على الإطار النشط. تسمح هذه الطريقة بالتلاعب الدقيق بالإطارات الفردية داخل تسلسل الصور، مما يعزز المرونة في تحرير وتكوين الصور داخل تطبيقك. |
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
| override [SetResolution](../../aspose.imaging.fileformats.tiff/tiffimage/setresolution/)(double, double) | يحدد الدقة لـ [`RasterImage`](../../aspose.imaging/rasterimage/) المحدد، مما يتيح تحكمًا دقيقًا في عرض الصورة وخصائصها. دمج هذه الوظيفة لتحسين المخرجات البصرية وضمان التوافق مع أجهزة ومنصات الإخراج المتنوعة، مما يعزز تجربة المستخدم العامة. |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | يحوّل الصورة النقطية إلى bitmap. هذه الطريقة غير مدعومة في الإصدارات بدءًا من .Net7.0 وما فوق. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |

### انظر أيضًا

* class [TiffImage](../../aspose.imaging.fileformats.tiff/tiffimage/)
* namespace [Aspose.Imaging.FileFormats.BigTiff](../../aspose.imaging.fileformats.bigtiff/)
* assembly [Aspose.Imaging](../../)


