---
title: "الفئة WebPImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Webp.WebPImage. قم بمعالجة صور WebP النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا باستخدام ميزاتها الحديثة لكل من الضغط غير الفاقد والفقدان، مما يضمن جودة صورة مثالية مع تقليل حجم الملفات. تعامل بسلاسة مع صيغ الملفات الموسعة والرسوم المتحركة وقنوات ألفا مع تحديث الأبعاد بسهولة، وإعادة التحجيم بشكل متناسب، والقص، والدوران، وتطبيق الفلاتر، وضبط معلمات الصورة، والتحويل إلى صيغ صور أخرى لتحسين صور الويب المتعددة الاستخدامات"
type: docs
weight: 8260
url: /ar/net/aspose.imaging.fileformats.webp/webpimage/
---
## WebPImage class

قم بالتعامل مع صور WebP النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا، مستفيدًا من ميزاتها الحديثة للضغط بدون فقدان أو مع فقدان، لضمان جودة صورة مثالية مع تقليل حجم الملفات. تعامل بسلاسة مع تنسيقات الملفات الموسعة، والرسوم المتحركة، وقنوات ألفا، مع إمكانية تحديث الأبعاد بسهولة، وإعادة التحجيم بشكل متناسب، والقص، والدوران، وتطبيق الفلاتر، وضبط معلمات الصورة، وتحويلها إلى تنسيقات صور أخرى لتحسين صور الويب بمرونة.

```csharp
public sealed class WebPImage : RasterCachedMultipageImage, IMultipageImageExt
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WebPImage](webpimage/#constructor)(RasterImage) | أنشئ مثيلًا جديدًا من الفئة `WebPImage`، مُهيأً من كائن rasterImage المقدم. يتيح هذا المُنشئ تحويل الصور النقطية إلى صيغة WebP بسلاسة، مما يمكّن من معالجة البيانات الصورية بكفاءة داخل تطبيقك. |
| [WebPImage](webpimage/#constructor_4)(Stream) | أنشئ مثيلًا جديدًا من الفئة `WebPImage`، مُهيأً من مصدر تدفق (stream) مقدم. استخدم هذا المُنشئ لإنشاء كائنات صورة WebP مباشرةً من التدفقات بسلاسة، مما يمكّن من معالجة البيانات الصورية لـ WebP بكفاءة داخل تطبيقك. |
| [WebPImage](webpimage/#constructor_6)(string) | أنشئ مثيلًا جديدًا من الفئة `WebPImage`، مُهيأً من مصدر ملف مقدم. استخدم هذا المُنشئ لإنشاء كائنات صورة WebP مباشرةً من الملفات بسلاسة، مما يبسط عملية تحميل ومعالجة بيانات صورة WebP داخل تطبيقك. |
| [WebPImage](webpimage/#constructor_1)(RasterImage, LoadOptions) | أنشئ مثيلًا جديدًا من الفئة `WebPImage` باستخدام كائن rasterImage وخيارات التحميل المحددة، مما يتيح معالجة مرنة للبيانات الصورية. استخدم هذا المُنشئ لتهيئة كائنات صورة WebP من الصور النقطية بسلاسة مع تخصيص معلمات التحميل وفقًا لمتطلبات تطبيقك. |
| [WebPImage](webpimage/#constructor_5)(Stream, LoadOptions) | أنشئ مثيلًا جديدًا من الفئة `WebPImage` من تدفق، مع دمج خيارات التحميل المحددة وإعدادات إدارة الذاكرة. يوفر هذا المُنشئ مرونة في تحميل صور WebP من التدفقات مع إدارة موارد الذاكرة بكفاءة، مما يضمن أداءً مثاليًا واستخدامًا فعالًا للموارد داخل تطبيقك. |
| [WebPImage](webpimage/#constructor_7)(string, LoadOptions) | أنشئ مثيلًا جديدًا من الفئة `WebPImage` باستخدام ملف وخيارات تحميل محددة، مما يسهل معالجة مرنة لبيانات صورة WebP. استخدم هذا المُنشئ لتهيئة كائنات صورة WebP من الملفات بسلاسة مع تخصيص معلمات التحميل وفقًا لمتطلبات تطبيقك. |
| [WebPImage](webpimage/#constructor_2)(int, int, WebPOptions) | أنشئ مثيلًا جديدًا من الفئة `WebPImage` بصورة فارغة بأبعاد العرض والارتفاع المحددة. يتيح هذا المُنشئ إنشاء صور WebP فارغة، مما يوفر أساسًا لمعالجة الصور لاحقًا وتوليد المحتوى داخل تطبيقك. |
| [WebPImage](webpimage/#constructor_3)(int, int, WebPOptions, LoadOptions) | أنشئ مثيلًا جديدًا من الفئة `WebPImage` بصورة فارغة وخيارات تحميل محددة. يتيح هذا المُنشئ تهيئة صور WebP مع معلمات تحميل قابلة للتخصيص، مما يوفر مرونة في إنشاء الصور ومعالجتها داخل تطبيقك. |

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
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.webp/webpimage/fileformat/) { get; } | الوصول إلى قيمة تنسيق الملف المرتبط بالصورة، لتوفير معلومات حول الصيغة التي تُخزن بها الصورة. استخدم هذه الخاصية لتحديد تنسيق ملف الصورة، مما يسهل فحوصات التوافق والمعالجة الخاصة بالتنسيق داخل تطبيقك. |
| override [HasAlpha](../../aspose.imaging.fileformats.webp/webpimage/hasalpha/) { get; } | استرجع ما إذا كانت الصورة تحتوي على قناة ألفا، مما يشير إلى وجود معلومات الشفافية. استخدم هذه الخاصية لتحديد ما إذا كانت الصورة تشمل الشفافية، مما يتيح المعالجة المناسبة للعمليات المتعلقة بالألفا داخل تطبيقك. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت الصورة لها لون شفاف. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | الحصول على ارتفاع الصورة. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | الحصول على أو تعيين الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذه [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | الحصول على شفافية هذه الصورة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | الحصول على أو تعيين بيانات XMP من الإطار. |
| [Options](../../aspose.imaging.fileformats.webp/webpimage/options/) { get; } | استرجع أو عدل الخيارات المرتبطة بالخاصية المحددة، مما يتيح تخصيصًا دقيقًا للسلوك والإعدادات. استخدم هذه الخاصية للوصول السلس إلى المعلمات القابلة للتكوين وتعديلها، مما يسهل التحكم المتنوع وتحسين وظائف تطبيقك. |
| override [PageCount](../../aspose.imaging.fileformats.webp/webpimage/pagecount/) { get; } | استرجع العدد الإجمالي للصفحات داخل المستند المحدد، مما يسهل التنقل الفعال وإدارة المحتوى متعدد الصفحات. دمج هذه الوظيفة لتعزيز تجربة المستخدم، مما يتيح الوصول السلس إلى هياكل المستند الشاملة. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | يحصل أو يعيّن إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرةً قبل حفظ كل صفحة. |
| override [Pages](../../aspose.imaging.fileformats.webp/webpimage/pages/) { get; } | الوصول إلى كتل WebP داخل الصورة، مما يسمح بفحص مفصل أو تعديل بنية الكتل الأساسية. استخدم هذه الخاصية لتحليل أو تعديل الكتل الفردية داخل بيانات صورة WebP، مما يسهل تقنيات معالجة الصور المتقدمة داخل تطبيقك. |
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
| [AddBlock](../../aspose.imaging.fileformats.webp/webpimage/addblock/)(IFrame) | دمج كتلة WebP جديدة في الصورة، مما يثري محتواها ويسهل معالجة الصور المتقدمة. استخدم هذه الطريقة لتعزيز بنية وتعقيد بيانات صورة WebP داخل تطبيقك بشكل ديناميكي، مما يتيح تحكمًا دقيقًا وتحسينًا لتصيير الصورة. |
| [AddPage](../../aspose.imaging.fileformats.webp/webpimage/addpage/)(RasterImage) | إضافة صفحة جديدة إلى الصورة، مما يوسع محتواها ويستوعب عناصر بصرية إضافية. دمج هذه الطريقة لتسهيل إدارة الصفحات الديناميكية داخل تطبيقك، مما يتيح إنشاء وتوسيع مستندات أو صور متعددة الصفحات بسلاسة. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.webp/webpimage/adjustbrightness/)(int) | تنفيذ تعديل *السطوع* للصورة، مما يسمح بتعديل مستويات الإضاءة العامة. دمج هذه الطريقة في سير عمل معالجة الصور لتعزيز الرؤية وتحسين الجودة البصرية للصور داخل تطبيقك. |
| override [AdjustContrast](../../aspose.imaging.fileformats.webp/webpimage/adjustcontrast/)(float) | تحسين التباين للـ[`Image`](../../aspose.imaging/image/)، مع تضخيم الفروق بين المناطق الفاتحة والداكنة. دمج هذه الطريقة في سير عمل معالجة الصور لتحسين الوضوح البصري وجودة الصورة العامة داخل تطبيقك. |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma/#adjustgamma)(float) | تطبيق تصحيح جاما على الصورة، مع تعديل شدة البكسل لتحقيق السطوع وتوازن الألوان المطلوبين. دمج هذه الطريقة في سير عمل معالجة الصور لتعزيز الجودة البصرية وتحسين دقة التحليل أو مهام العرض اللاحقة داخل تطبيقك. |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma/#adjustgamma_1)(float, float, float) | إجراء تصحيح جاما على الصورة باستخدام معاملات فردية لقنوات الأحمر والأخضر والأزرق، مما يسمح بتعديلات دقيقة لتوازن الألوان والتباين. دمج هذه الطريقة في خط أنابيب معالجة الصور لتحقيق تحكم دقيق في عرض الألوان وتعزيز الدقة البصرية داخل تطبيقك. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | ينفّذ تعديلًا تلقائيًا متكيفًا للسطوع والتباين عبر الصورة بأكملها. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | يقوم بتدوير الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من بيانات Exif. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح، مما يعزز تجربة المستخدم ويقضي على الحاجة إلى التعديلات اليدوية. من خلال تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، مما يوفر تجربة مشاهدة سلسة عبر مختلف المنصات والأجهزة. تبسط عملية التدوير الآلية معالجة الصور وتحسن قابلية الاستخدام العامة، خاصةً عند التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المتنوعة. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.webp/webpimage/binarizebradley/#binarizebradley_1)(double, int) | تطبيق التحويل إلى ثنائي على الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي مع عتبة الصورة المتكاملة. تقوم هذه الطريقة بحساب عتبات محلية ديناميكيًا بناءً على جوار الصورة، مما يعزز القدرة على التكيف مع ظروف الإضاءة المتغيرة ويضمن تجزئة قوية للمهام اللاحقة داخل تطبيقك. |
| override [BinarizeFixed](../../aspose.imaging.fileformats.webp/webpimage/binarizefixed/)(byte) | إجراء التحويل إلى ثنائي على الصورة باستخدام قيمة عتبة محددة مسبقًا، وتحويلها إلى صورة ثنائية حيث يتم تصنيف البكسلات كخلفية أو مقدمة بناءً على شدتها مقارنةً بالعتبة. دمج هذه الطريقة في سير عمل معالجة الصور لتسهيل مهام التجزئة واستخراج الميزات، مما يعزز دقة وكفاءة التحليل اللاحق داخل تطبيقك. |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.webp/webpimage/binarizeotsu/)() | إجراء التحويل إلى ثنائي على الصورة باستخدام طريقة عتبة أوتسو، التي تحدد تلقائيًا قيمة العتبة المثلى بناءً على هيستوجرام الصورة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تجزئة واستخراج ميزات فعالين، مما يعزز دقة وموثوقية مهام تحليل الصور داخل تطبيقك. |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata/)() | يخزن البيانات بشكل خاص. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| [ClearBlocks](../../aspose.imaging.fileformats.webp/webpimage/clearblocks/)() | مسح جميع كتل WebP الموجودة من الصورة، مما يوفر قاعدة نظيفة للتعديلات أو الإضافات اللاحقة. استخدم هذه الطريقة لإعادة ضبط بنية الكتل داخل بيانات صورة WebP بفعالية، وضمان إدارة وتنظيم مثالي لمحتوى الصورة داخل تطبيقك. |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop/#crop)(Rectangle) | قص الصورة باستخدام منطقة مستطيلة محددة، مع إزالة الأجزاء غير المرغوب فيها مع الاحتفاظ بالمحتوى المطلوب. دمج هذه الطريقة في سير عمل معالجة الصور لاستخراج وتركيز المناطق المحددة بدقة داخل الصورة، مما يعزز الوضوح والتكوين لتطبيقات مختلفة. |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop/#crop_1)(int, int, int, int) | قص الصورة عن طريق تطبيق إزاحات إلى اليسار واليمين والأعلى والأسفل، مما يحدد بفعالية منطقة الاهتمام داخل الصورة. استخدم هذه الطريقة لاستخراج الأجزاء المطلوبة من الصورة ديناميكيًا مع تعديل تكوينها وتركيزها وفقًا لمتطلبات تطبيقك. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | يقوم بأداء التمويه على الصورة الحالية. |
| override [Dither](../../aspose.imaging.fileformats.webp/webpimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | إجراء التمويه على الصورة الحالية لتقليل تدرج الألوان وتحسين الجودة البصرية. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق انتقالات ألوان أكثر سلاسة وتحسين المظهر العام للصورة داخل تطبيقك. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | أدمج توقيعًا رقميًا بناءً على كلمة المرور المقدمة في كل صفحة من الصورة. |
| override [Filter](../../aspose.imaging.fileformats.webp/webpimage/filter/)(Rectangle, FilterOptionsBase) | تصفية المحتوى داخل المستطيل المحدد، مع تطبيق مرشح معالجة صورة مخصص لتعزيز أو تعديل المنطقة المختارة. دمج هذه الطريقة في سير عمل تعديل الصور لتحقيق تحسينات أو تحويلات مستهدفة داخل تطبيقك. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | يحصل على بكسل صورة 32-بت ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | يحصل على مصفوفة بكسلات 32-بت ARGB الافتراضية. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.webp/webpimage/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.imaging/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [`Save`](../../aspose.imaging/image/save/) كمعامل ثاني. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | يحصل على بكسل صورة. |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | يحصل على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف عند المسح. |
| override [Grayscale](../../aspose.imaging.fileformats.webp/webpimage/grayscale/)() | تحويل الصورة إلى تمثيلها بالدرجات الرمادية، حيث تتحول إلى صورة ذات قناة واحدة حيث يمثل كل بكسل الشدة أو الإضاءة. دمج هذه الطريقة في خط أنابيب معالجة الصور لتبسيط التحليل وتعزيز التوافق مع الخوارزميات القائمة على الدرجات الرمادية، مما يسهل مهام الرؤية الحاسوبية وتحليل الصور داخل تطبيقك. |
| [InsertBlock](../../aspose.imaging.fileformats.webp/webpimage/insertblock/)(int, IFrame) | إدراج كتلة WebP جديدة في الفهرس المحدد داخل الصورة، مما يتيح تحكمًا دقيقًا في تسلسل الكتل. دمج هذه الطريقة لدمج كتل WebP إضافية بسلاسة في بنية بيانات الصورة، مما يسهل معالجة الصور المتقدمة وتحسينها داخل تطبيقك. |
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
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [RemoveBlock](../../aspose.imaging.fileformats.webp/webpimage/removeblock/)(IFrame) | إزالة كتلة WebP المحددة من الصورة، مما يسهل إدارة بنية بيانات الصورة بفعالية. استخدم هذه الطريقة لتبسيط سير عمل معالجة الصور عن طريق حذف الكتل أو المكونات غير الضرورية داخل تطبيقك. |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | يزيل بيانات التعريف الخاصة بهذه الصورة عن طريق تعيين قيمة [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) إلى `null`. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize/#resize_1)(int, int, ImageResizeSettings) | تغيير حجم الصورة وفقًا للإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد ونسبة العرض إلى الارتفاع وسلوك التحجيم. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق عمليات تعديل حجم مخصصة وفقًا لمتطلبات تطبيقك المحددة. |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize/#resize_2)(int, int, ResizeType) | تغيير حجم الصورة، مع تعديل أبعادها مع الحفاظ على نسبة العرض إلى الارتفاع. دمج هذه الطريقة في سير عمل معالجة الصور لتكبير الصور ديناميكيًا لتتناسب مع متطلبات العرض أو التخزين المختلفة داخل تطبيقك. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | ضبط ارتفاع الصورة بشكل نسبي، مع الحفاظ على نسبة العرض إلى الارتفاع لضمان تعديل حجم متسق. دمج هذه الطريقة في سير عمل معالجة الصور لتغيير حجم الصور ديناميكيًا بنسب موحدة، مما يضمن عرضًا أو تخزينًا مثاليًا داخل تطبيقك. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | ضبط عرض الصورة بشكل نسبي مع الحفاظ على نسبة العرض إلى الارتفاع. دمج هذه الطريقة في سير عمل معالجة الصور لتغيير حجم الصور ديناميكيًا بنسب متسقة، مما يضمن عرضًا أو تخزينًا مثاليًا داخل تطبيقك. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | دوّر الصورة حول المركز. |
| override [Rotate](../../aspose.imaging.fileformats.webp/webpimage/rotate/#rotate_1)(float, bool, Color) | قم بتدوير الصورة حول مركزها بزاوية محددة، مع تغيير حجمها بشكل متناسب وتطبيق معلمات لون الخلفية المحددة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تحويلات دقيقة مع ألوان خلفية قابلة للتخصيص، مما يضمن عرضًا بصريًا مثاليًا داخل تطبيقك. |
| override [RotateFlip](../../aspose.imaging.fileformats.webp/webpimage/rotateflip/)(RotateFlipType) | طبق التدوير أو القلب أو كلا العمليتين حصريًا على الإطار النشط داخل الصورة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تعديل دقيق للإطارات الفردية، مما يعزز المرونة والتحكم في تحويلات الإطارات داخل تطبيقك. |
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

يوضح هذا المثال كيفية تحميل صورة WebP من ملف وحفظها كـ PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة WebP من ملف.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // حفظ إلى PNG
    // لاحظ أن الإطار النشط فقط سيتم تخزينه كـ PNG، لأن PNG ليس تنسيقًا متعدد الصفحات.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Webp](../../aspose.imaging.fileformats.webp/)
* assembly [Aspose.Imaging](../../)


