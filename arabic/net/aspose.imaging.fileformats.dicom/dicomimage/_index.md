---
title: "الفئة DicomImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Dicom.DicomImage. هذه الفئة تنفّذ دعم تنسيق صورة DICOM النقطية للصور الرقمية والاتصالات في الطب وتقدّم حلاً شاملاً لمعالجة صور DICOM بدقة ومرونة. يمكنك معالجة صفحات الصورة بسلاسة بما في ذلك عمليات الحصول على الصفحات وإضافتها أو إزالتها والتحكم في الصفحات الافتراضية والنشطة. مع إمكانيات العمل مع قنوات ألفا وتضمين بيانات XMP الوصفية وتغيير الحجم والدوران والقص والتحويل إلى ثنائي وتعديل وتطبيق الفلاتر والتحويل إلى تنسيقات نقطية أخرى. هذه الواجهة البرمجية تمكّن المطورين من التعامل مع صور DICOM بفعالية مع تلبية متطلبات التطبيقات المتنوعة في سياق التصوير الطبي."
type: docs
weight: 2500
url: /ar/net/aspose.imaging.fileformats.dicom/dicomimage/
---
## DicomImage class

هذه الفئة تنفّذ دعم تنسيق صورة نقطية للطب الرقمي والاتصالات في الطب (DICOM) وتقدّم حلاً شاملاً لمعالجة صور DICOM بدقة ومرونة. يمكنك معالجة صفحات الصورة بسلاسة، بما في ذلك عمليات الحصول على الصفحات أو إضافتها أو إزالتها، والتحكم في الصفحات الافتراضية والنشطة. مع إمكانيات العمل مع قنوات ألفا، وإدراج بيانات تعريف XMP، وتغيير الحجم، وتدوير، واقتصاص، وتحويل إلى ثنائي، وتعديل، وتطبيق الفلاتر، وتحويل إلى تنسيقات نقطية أخرى. تمكّن هذه الواجهة البرمجية المطورين من التعامل مع صور DICOM بفعالية مع تلبية متطلبات التطبيقات المتنوعة في سياق التصوير الطبي.

```csharp
public sealed class DicomImage : RasterCachedMultipageImage, IMultipageImageExt
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DicomImage](dicomimage/#constructor_1)(Stream) | إنشاء نسخة جديدة من الفئة DicomImage باستخدام معامل stream في هذا المُنشئ. مثالي للمطورين الذين يبحثون عن طريقة مبسطة لتهيئة كائنات `DicomImage` من تدفقات البيانات الموجودة في مشاريعهم. |
| [DicomImage](dicomimage/#constructor_2)(Stream, LoadOptions) | ابدأ نسخة جديدة من الفئة DicomImage بسلاسة باستخدام معاملَي stream و loadOptions في هذا المُنشئ. مثالي للمطورين المتحمسين للبدء في العمل مع كائنات `DicomImage` بسرعة وفعالية في مشاريعهم. |
| [DicomImage](dicomimage/#constructor)(DicomOptions, int, int) | قم بتهيئة نسخة جديدة من فئة DicomImage بسهولة باستخدام هذا المُنشئ، مع تمرير معلمات dicomOptions. مثالي للمطورين الذين يرغبون في الغوص في كائنات `DicomImage` بسرعة وكفاءة في مشاريعهم. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActivePage](../../aspose.imaging.fileformats.dicom/dicomimage/activepage/) { get; set; } | إدارة الصفحة النشطة للصورة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يسعون لتبديل الصفحات ديناميكياً داخل الصور متعددة الصفحات، مما يضمن تنقلاً ومعالجةً فعالين. |
| [ActivePageIndex](../../aspose.imaging.fileformats.dicom/dicomimage/activepageindex/) { get; } | استرجاع فهرس الصفحة النشطة بسهولة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يحتاجون إلى وصول سريع إلى فهرس الصفحة الحالية داخل الصور متعددة الصفحات، مما يضمن تنقلاً ومعالجةً فعالين. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | الحصول على عدد البتات لكل بكسل في الصورة. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [DicomPages](../../aspose.imaging.fileformats.dicom/dicomimage/dicompages/) { get; } | الوصول إلى صفحات الصورة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يرغبون في التفاعل مع الصفحات الفردية داخل الصورة، مما يضمن تنقلاً وتلاعبًا سلسًا. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.dicom/dicomimage/fileformat/) { get; } | استرجاع قيمة تنسيق الملف بسهولة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يحتاجون إلى وصول سريع إلى تنسيق ملف الصورة، مما يضمن معالجة فعالة بناءً على نوع الملف. |
| [FileInfo](../../aspose.imaging.fileformats.dicom/dicomimage/fileinfo/) { get; } | استرجاع معلومات رأسية قيمة من ملف DICOM بسهولة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يحتاجون إلى وصول سريع إلى التفاصيل الأساسية المضمنة في ملف DICOM، مما يضمن استخراجًا وتحليلًا فعالًا للبيانات. |
| override [HasAlpha](../../aspose.imaging.fileformats.dicom/dicomimage/hasalpha/) { get; } | استرجاع ما إذا كانت الصورة تحتوي على قناة ألفا بسهولة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يرغبون في تحديد ما إذا كانت الصورة تحتوي على معلومات شفافية، مما يضمن معالجة دقيقة لبيانات قناة ألفا في مهام معالجة الصور. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت الصورة لها لون شفاف. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | الحصول على ارتفاع الصورة. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | الحصول على أو تعيين الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذه [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | الحصول على شفافية هذه الصورة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | الحصول على أو تعيين بيانات XMP من الإطار. |
| override [PageCount](../../aspose.imaging.fileformats.dicom/dicomimage/pagecount/) { get; } | استرجاع العدد الإجمالي للصفحات في الصورة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يحتاجون إلى وصول سريع إلى عدد الصفحات داخل الصورة، مما يضمن تنقلاً وإدارةً فعالين. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | يحصل أو يعيّن إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرةً قبل حفظ كل صفحة. |
| override [Pages](../../aspose.imaging.fileformats.dicom/dicomimage/pages/) { get; } | الوصول إلى صفحات الصورة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يرغبون في التفاعل مع الصفحات الفردية داخل الصورة، مما يضمن تنقلاً وتلاعبًا سلسًا. |
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
| [AddPage](../../aspose.imaging.fileformats.dicom/dicomimage/addpage/#addpage)() | أضف صفحة جديدة إلى نهاية قائمة صفحات الصورة باستخدام هذه الطريقة البسيطة. مثالية للمطورين الذين يرغبون في توسيع الصور متعددة الصفحات ديناميكيًا، مع ضمان دمج وتنظيم محتوى الصورة بسلاسة. |
| [AddPage](../../aspose.imaging.fileformats.dicom/dicomimage/addpage/#addpage_1)(RasterImage) | وسّع مجموعة صورك بإضافة صفحة جديدة باستخدام هذه الطريقة البديهية. مثالية للمطورين الذين يرغبون في إلحاق صفحات ديناميكيًا بالصور متعددة الصفحات، مع ضمان توسيع وتنظيم محتوى الصورة بسلاسة. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.dicom/dicomimage/adjustbrightness/)(int) | حسّن إضاءة الصورة من خلال تعديل *السطوع*، وهي طريقة معلمة تسمح للمطورين بضبط إضاءة الصور بدقة. تمكّن هذه الدالة سهلة الاستخدام المطورين من تعديل سطوع الصورة بسلاسة، مقدمةً مرونة وتحكمًا في الجماليات البصرية. |
| override [AdjustContrast](../../aspose.imaging.fileformats.dicom/dicomimage/adjustcontrast/)(float) | حسّن تباين [`Image`](../../aspose.imaging/image/) باستخدام هذه الطريقة السهلة، التي تعدل الفارق بين المناطق الفاتحة والداكنة. حسّن الوضوح البصري والتعريف بسهولة، مما يوفّر للمطورين تحكمًا بديهيًا في تباين الصورة لتحقيق عرض مثالي. |
| override [AdjustGamma](../../aspose.imaging.fileformats.dicom/dicomimage/adjustgamma/#adjustgamma)(float) | حسّن جودة الصورة واضبطها باستخدام تصحيح جاما، وهي تقنية قوية لضبط المظهر البصري بدقة. مثالية للمطورين الذين يهدفون إلى تحسين عرض الصورة، وضبط توازن الألوان، وضمان عرض متسق عبر مختلف الأجهزة والبيئات. |
| override [AdjustGamma](../../aspose.imaging.fileformats.dicom/dicomimage/adjustgamma/#adjustgamma_1)(float, float, float) | تحقق من تعديلات ألوان دقيقة من خلال تطبيق تصحيح جاما بشكل مستقل على مكونات الأحمر والأخضر والأزرق في الصورة. تضمن هذه الطريقة توازنًا لونيًا دقيقًا ومخرجات بصرية مثالية، لتلبية احتياجات المطورين الذين يسعون إلى تحكم دقيق في عرض الصورة ودقة الألوان. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | ينفّذ تعديلًا تلقائيًا متكيفًا للسطوع والتباين عبر الصورة بأكملها. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | يقوم بتدوير الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من بيانات Exif. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح، مما يعزز تجربة المستخدم ويقضي على الحاجة إلى التعديلات اليدوية. من خلال تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، مما يوفر تجربة مشاهدة سلسة عبر مختلف المنصات والأجهزة. تبسط عملية التدوير الآلية معالجة الصور وتحسن قابلية الاستخدام العامة، خاصةً عند التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المتنوعة. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.dicom/dicomimage/binarizebradley/#binarizebradley_1)(double, int) | تحويل الصور إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي، مستفيدًا من عتبة الصورة المتكاملة لتحسين الأداء. مثالي للمطورين الذين يرغبون في تقسيم الصور تلقائيًا بناءً على التباينات المحلية في السطوع، مما يضمن اكتشافًا واستخراجًا دقيقًا للكائنات في ظروف إضاءة متغيرة. |
| override [BinarizeFixed](../../aspose.imaging.fileformats.dicom/dicomimage/binarizefixed/)(byte) | قم بتحويل الصورة إلى صيغة ثنائية بسهولة باستخدام عتبة محددة مسبقًا مع هذه الطريقة البسيطة. مثالي للمطورين الذين يرغبون في تبسيط مهام معالجة الصور عن طريق تقسيم الصورة إلى مكوّنات المقدمة والخلفية بناءً على مستويات الشدة المحددة. |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.dicom/dicomimage/binarizeotsu/)() | طبق عتبة أوتو لتثبيت الصورة، مع تحديد القيمة المثلى للعتبة تلقائيًا بناءً على هيستوجرام الصورة. مثالي للمطورين الباحثين عن طريقة موثوقة لتقسيم الصور إلى مناطق المقدمة والخلفية بأقل تدخل يدوي. |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [CacheData](../../aspose.imaging.fileformats.dicom/dicomimage/cachedata/)() | تقوم هذه الطريقة بتخزين البيانات مؤقتًا بكفاءة، مما يحسن الأداء ويضمن وصولًا سريعًا عند الحاجة. مثالي للمطورين الذين يرغبون في تعزيز سرعة وكفاءة تطبيقاتهم من خلال إدارة موارد البيانات بذكاء. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| override [Crop](../../aspose.imaging.fileformats.dicom/dicomimage/crop/#crop)(Rectangle) | قم بقص الصورة لإزالة المناطق غير المرغوب فيها والتركيز على المحتوى الأساسي باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يرغبون في تخصيص التركيب البصري للصور، لضمان نقل الرسالة المطلوبة بفعالية. |
| override [Crop](../../aspose.imaging.fileformats.dicom/dicomimage/crop/#crop_1)(int, int, int, int) | اضبط منطقة القص في الصورة عن طريق تطبيق إزاحات باستخدام هذه الطريقة المتعددة الاستخدامات. مثالي للمطورين الذين يحتاجون إلى تحكم دقيق في عملية القص، لضمان الاحتفاظ بالتفاصيل المهمة مع حذف العناصر غير الضرورية. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | يقوم بأداء التمويه على الصورة الحالية. |
| override [Dither](../../aspose.imaging.fileformats.dicom/dicomimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | قم بتحسين الصورة الحالية بتطبيق تأثيرات التمويه باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يهدفون إلى إضافة نسيج وعمق للصور، مما يحسن جودتها البصرية وجاذبيتها العامة. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | أدمج توقيعًا رقميًا بناءً على كلمة المرور المقدمة في كل صفحة من الصورة. |
| override [Filter](../../aspose.imaging.fileformats.dicom/dicomimage/filter/)(Rectangle, FilterOptionsBase) | قم بتحسين مناطق محددة من صورتك بسهولة عن طريق تطبيق فلاتر على المستطيلات المحددة. توفر هذه الطريقة للمطورين تحكمًا دقيقًا في تعديل الصورة، مما يسمح بإجراء تعديلات مستهدفة لتحقيق التأثيرات البصرية المطلوبة بسهولة. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | يحصل على بكسل صورة 32-بت ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | يحصل على مصفوفة بكسلات 32-بت ARGB الافتراضية. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.imaging/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [`Save`](../../aspose.imaging/image/save/) كمعامل ثاني. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | يحصل على بكسل صورة. |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | يحصل على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف عند المسح. |
| override [Grayscale](../../aspose.imaging.fileformats.dicom/dicomimage/grayscale/)() | حوّل الصور بسهولة إلى تمثيلها بتدرج الرمادي، مما يبسط تحليل الصور ومعالجة المهام. مثالي للمطورين الذين يسعون لتحسين وضوح الصورة، تقليل التعقيد، وتسهيل الخوارزميات القائمة على التدرج الرمادي لتطبيقات متنوعة. |
| [InsertPage](../../aspose.imaging.fileformats.dicom/dicomimage/insertpage/)(int) | أدرج صفحة جديدة في قائمة صفحات الصورة عند فهرس محدد باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في التحكم الدقيق في ترتيب الصفحات في الصور متعددة الصفحات، مما يضمن تنظيمًا سلسًا وتخصيصًا لمحتوى الصورة. |
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
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | يزيل بيانات التعريف الخاصة بهذه الصورة عن طريق تعيين قيمة [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) إلى `null`. |
| [RemovePage](../../aspose.imaging.fileformats.dicom/dicomimage/removepage/)(int) | أزل الصفحة عند الفهرس المحدد من قائمة الصفحات باستخدام هذه الطريقة المريحة. مثالي للمطورين الذين يسعون للتحكم الدقيق في إدارة الصور متعددة الصفحات، مما يضمن تنظيمًا سلسًا وتخصيصًا لمحتوى الصورة. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging.fileformats.dicom/dicomimage/resize/#resize_1)(int, int, ImageResizeSettings) | قم بضبط حجم صورتك باستخدام طريقة التحجيم البسيطة هذه. سواء كنت بحاجة لتصغير أو تكبير صورتك، تضمن هذه الدالة تلبية احتياجات التحجيم بكفاءة ودقة، مما يجعلها مثالية للمطورين الذين يبحثون عن تعديلات سريعة وسهلة لحجم الصورة. |
| override [Resize](../../aspose.imaging.fileformats.dicom/dicomimage/resize/#resize_2)(int, int, ResizeType) | قم بضبط حجم الصورة باستخدام هذه الطريقة المباشرة. مثالي للمطورين الذين يرغبون في تغيير حجم الصور ديناميكيًا، مما يضمن توافقها بسلاسة مع مختلف السياقات والتصاميم داخل تطبيقاتهم. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.dicom/dicomimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | قم بضبط ارتفاع الصورة مع الحفاظ على نسبة العرض إلى الارتفاع باستخدام هذه الطريقة السهلة الاستخدام. مثالي للمطورين الذين يسعون لتغيير حجم الصور ديناميكيًا مع الحفاظ على نسبها، مما يضمن عرضًا مثاليًا وقابلية استخدام في تطبيقاتهم. |
| [ResizeProportional](../../aspose.imaging.fileformats.dicom/dicomimage/resizeproportional/)(int, int, ResizeType) | قم بتغيير حجم الصورة مع الحفاظ على نسبة العرض إلى الارتفاع باستخدام هذه الطريقة المريحة. مثالي للمطورين الذين يسعون لضبط أبعاد الصورة بشكل متناسب، مع ضمان التناسق والحفاظ على نسب المحتوى الأصلي. سيقوم تغيير الحجم المتناسب بتغيير حجم كل إطار وفقًا للنسبة بين *newWidth*/العرض و *newHeight*/الارتفاع. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.dicom/dicomimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | قم بضبط عرض الصورة مع الحفاظ على نسبة العرض إلى الارتفاع باستخدام هذه الطريقة المريحة. مثالي للمطورين الذين يرغبون في تغيير حجم الصور بشكل متناسب، مع ضمان نتائج متسقة وجذابة بصريًا عبر بيئات العرض المختلفة. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | دوّر الصورة حول المركز. |
| override [Rotate](../../aspose.imaging.fileformats.dicom/dicomimage/rotate/#rotate_1)(float, bool, Color) | دوّر الصورة حول مركزها باستخدام هذه الطريقة المريحة. مثالي للمطورين الذين يرغبون في ضبط اتجاه الصورة ديناميكيًا، مع ضمان عرض ومحاذاة مثالية داخل تطبيقاتهم. |
| override [RotateFlip](../../aspose.imaging.fileformats.dicom/dicomimage/rotateflip/)(RotateFlipType) | قم بالتلاعب بسهولة بالإطار النشط عن طريق الدوران أو القلب، أو تنفيذ كلا الإجراءين معًا باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يحتاجون إلى ضبط اتجاه إطارات محددة داخل تسلسلات الصور ديناميكيًا، مع ضمان عرض ومحاذاة مثالية. |
| [Save](../../aspose.imaging/image/save/)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| override [Save](../../aspose.imaging/image/save/)(string) | يحفظ الصورة إلى موقع الملف المحدد. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.imaging.fileformats.dicom/dicomimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | احفظ بيانات صورتك بسهولة إلى دفق محدد بالتنسيق الملف المطلوب باستخدام هذه الطريقة المريحة. سواء كنت تعمل مع JPEG أو PNG أو أي تنسيق آخر، تضمن هذه الدالة حفظ بيانات الصورة بكفاءة ودقة، مما يجعلها مثالية للمطورين الذين يرغبون في تبسيط عمليات حفظ الملفات. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [SaveAll](../../aspose.imaging.fileformats.dicom/dicomimage/saveall/)(string, ImageOptionsBase) | احفظ بيانات الكائن عن طريق تخزينها في موقع الملف المحدد (المؤشر + اسم الملف) مع تنسيق الملف المحدد والخيارات. مثالي للمطورين الذين يسعون لتخزين البيانات بأمان في صيغ متعددة مع الحفاظ على المرونة والتحكم في معلمات الحفظ. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels/)(Rectangle, int[]) | يحفظ بكسلات ARGB 32 بت. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | يحفظ البكسلات. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels/)(Rectangle, Color[]) | يحفظ البكسلات. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | يحفظ البيانات الخام. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel/)(int, int, int) | يضبط بكسل صورة ARGB 32 بت للموقع المحدد. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | يضبط بكسل الصورة للموقع المحدد. |
| override [SetResolution](../../aspose.imaging.fileformats.dicom/dicomimage/setresolution/)(double, double) | قم بضبط دقة هذه [`RasterImage`](../../aspose.imaging/rasterimage/) بدقة باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يرغبون في تعديل دقة الصورة لتلبية متطلبات محددة، مع ضمان جودة عرض مثالية وإدارة حجم الملف. |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | يحوّل الصورة النقطية إلى bitmap. هذه الطريقة غير مدعومة في الإصدارات بدءًا من .Net7.0 وما فوق. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |

## أمثلة

تغيير نوع اللون في ضغط DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

استخدام ضغط RLE في صورة DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression { Type = CompressionType.Rle }
    };

    inputImage.Save("original_RLE.dcm", options);
}
```

استخدام ضغط JPEG 2000 في صورة DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg2000,
            Jpeg2000 = new Jpeg2000Options
            {
                Codec = Jpeg2000Codec.Jp2,
                Irreversible = false
            }
        }
    };

    inputImage.Save("original_JPEG2000.dcm", options);
}
```

استخدام ضغط JPEG في صورة DICOM.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg,
            Jpeg = new JpegOptions
            {
                CompressionType = JpegCompressionMode.Baseline,
                SampleRoundingMode = SampleRoundingMode.Truncate,
                Quality = 50
            }
        }
    };

    inputImage.Save("original_JPEG.dcm", options);
}
```

يوضح هذا المثال كيفية تحميل صورة DICOM من تدفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة DICOM من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // احفظ كل صفحة كصورة PNG منفصلة.
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // إنشاء اسم ملف بناءً على فهرس الصفحة.
            string fileName = string.Format("sample.{0}.png", dicomPage.Index);

            // صفحة DICOM هي صورة نقطية، لذا جميع العمليات المسموح بها مع الصورة النقطية قابلة للتطبيق على صفحة DICOM.
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

إنشاء صورة DICOM متعددة الصفحات.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // ارسم شيئًا باستخدام الرسومات المتجهة
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // احفظ بكسلات الصورة المرسومة. الآن هي على الصفحة الأولى من صورة DICOM.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // أضف بعض الصفحات بعد ذلك، لتجعلها أغمق
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // أضف بعض الصفحات أمام الصفحة الرئيسية، لتجعلها أكثر سطوعًا
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // احفظ الصورة المتعددة الصفحات التي تم إنشاؤها إلى ملف الإخراج
    image.Save("MultiPage.dcm");
}
```

### انظر أيضًا

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../aspose.imaging.fileformats.dicom/)
* assembly [Aspose.Imaging](../../)


