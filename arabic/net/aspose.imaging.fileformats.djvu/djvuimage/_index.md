---
title: "الفئة DjvuImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Djvu.DjvuImage. تدعم فئة مستند DjVu تنسيق ملفات الرسومات وتسهّل الإدارة السلسة للمستندات الممسوحة والكتب التي تدمج النصوص والرسومات والصور والملفات الفوتوغرافية في تنسيق واحد. بدعم عمليات متعددة الصفحات يمكنك الوصول بفعالية إلى معرفات المستند الفريدة، وعدّ الصفحات، وتعيين الصفحات النشطة، واسترجاع صفحات المستند المحددة. مع ميزات لتغيير الحجم، والدوران، والتخفيض، والقص، والتحويل إلى تدرجات الرمادي، وتحويل gamma، وتصحيحات، وتعديلات وتطبيق الفلاتر، تمكّن هذه الفئة من التلاعب الدقيق وتعزيز صور DjVu لتلبية احتياجات التطبيقات المتنوعة بسهولة ودقة."
type: docs
weight: 2530
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/
---
## DjvuImage class

تدعم فئة مستند DjVu تنسيق ملفات الرسومات وتسهّل إدارة المستندات والكتب الممسوحة ضوئياً بسلاسة، حيث تدمج النصوص والرسومات والصور والصور الفوتوغرافية في تنسيق واحد. تدعم عمليات متعددة الصفحات، ويمكنك الوصول بكفاءة إلى معرفات المستند الفريدة، وعدّ الصفحات، وتعيين الصفحات النشطة، واسترجاع صفحات مستند محددة. مع ميزات تغيير الحجم، والتدوير، والتخفيض المتدرج (dithering)، والقص، وتحويل إلى تدرج الرمادي، وتصحيحات gamma، والتعديلات، وتطبيق الفلاتر، تمكّن هذه الفئة من التلاعب الدقيق وتعزيز صور DjVu لتلبية احتياجات التطبيقات المتنوعة بسهولة ودقة.

```csharp
public sealed class DjvuImage : RasterCachedMultipageImage, INotifyPropertyChanged
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DjvuImage](djvuimage/#constructor)(Stream) | ابدأ العمل مع صور DjVu بإنشاء نسخة جديدة من الفئة `DjvuImage` باستخدام معامل Stream. مثالي للمطورين الذين يرغبون في دمج سلس لمعالجة صور DjVu في مشاريعهم. |
| [DjvuImage](djvuimage/#constructor_1)(Stream, LoadOptions) | ابدأ العمل مع صور DjVu بسلاسة باستخدام هذا المُنشئ، الذي يُنشئ نسخة جديدة من الفئة `DjvuImage` باستخدام معاملَي Stream وLoadOptions. مثالي للمطورين الذين يرغبون في تحكم دقيق في خيارات تحميل صور DjVu مع الحفاظ على البساطة والكفاءة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ActivePage](../../aspose.imaging.fileformats.djvu/djvuimage/activepage/) { get; set; } | تجول في مستند DjVu الخاص بك عن طريق الوصول إلى الصفحة النشطة الحالية أو تعيينها باستخدام هذه الخاصية. انتقل بين الصفحات بسلاسة للتركيز على المحتوى المحدد وتحسين تجربة عرض المستند. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | الحصول على عدد البتات لكل بكسل في الصورة. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [DjvuPages](../../aspose.imaging.fileformats.djvu/djvuimage/djvupages/) { get; } | استرجع بسرعة جميع الصفحات الموجودة في مستند DjVu الخاص بك باستخدام هذه الخاصية. بسط سير عمل معالجة المستندات عن طريق الوصول السهل وإدارة الصفحات الفردية داخل ملفات DjVu. حسّن الكفاءة ونظم مهامك باستخدام استرجاع الصفحات المريح. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.djvu/djvuimage/fileformat/) { get; } | احصل على معلومات تنسيق الملف المرتبط بملف صورة DjVu الخاص بك. حدّد بسرعة تنسيق ملفك لتكامل سلس في سير عملك. |
| [FirstPage](../../aspose.imaging.fileformats.djvu/djvuimage/firstpage/) { get; } | الوصول إلى الصفحة الأولى من مستند DjVu الخاص بك باستخدام هذه الخاصية. استرجع بسرعة الصفحة الأولية لبدء عرض أو معالجة المستند بفعالية. |
| override [HasAlpha](../../aspose.imaging.fileformats.djvu/djvuimage/hasalpha/) { get; } | حدّد بسرعة ما إذا كان ملف صورة DjVu الخاص بك يحتوي على قناة ألفا. بسط سير عملك بالتحقق من وجود معلومات الشفافية في صورك. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت الصورة لها لون شفاف. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | الحصول على ارتفاع الصورة. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | الحصول على أو تعيين الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذه [`RasterImage`](../../aspose.imaging/rasterimage/). |
| [Identifier](../../aspose.imaging.fileformats.djvu/djvuimage/identifier/) { get; } | يحصل على المعرف الفريد للمستند |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | الحصول على شفافية هذه الصورة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| [LastPage](../../aspose.imaging.fileformats.djvu/djvuimage/lastpage/) { get; } | استرجع الصفحة الأخيرة من مستند DjVu الخاص بك باستخدام هذه الخاصية. وصول سريع إلى الصفحة النهائية للعرض أو المعالجة بسهولة. |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | الحصول على أو تعيين بيانات XMP من الإطار. |
| [NextPage](../../aspose.imaging.fileformats.djvu/djvuimage/nextpage/) { get; } | تجول في مستند DjVu الخاص بك عن طريق الوصول إلى الصفحة التالية باستخدام هذه الخاصية المريحة. تحرّك بسرعة إلى الأمام في مهام عرض أو معالجة المستند. |
| override [PageCount](../../aspose.imaging.fileformats.djvu/djvuimage/pagecount/) { get; } | استرجع العدد الكلي للصفحات في مجموعة صور DjVu الخاصة بك باستخدام هذه الخاصية. مثالي لتقييم سريع لحجم المستند أو الكتاب المخزن بتنسيق DjVu. حسّن كفاءة سير العمل بمعلومات دقيقة عن عدد الصفحات. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | يحصل أو يعيّن إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرةً قبل حفظ كل صفحة. |
| override [Pages](../../aspose.imaging.fileformats.djvu/djvuimage/pages/) { get; } | الوصول إلى الصفحات الفردية في مجموعة صور DjVu الخاصة بك باستخدام هذه الخاصية. بسط التنقل والتعامل مع مستندك أو كتابك المخزن بتنسيق DjVu عبر الوصول المباشر إلى كل صفحة. حسّن كفاءة سير العمل باسترجاع الصفحات بسهولة. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [PreviousPage](../../aspose.imaging.fileformats.djvu/djvuimage/previouspage/) { get; } | تحرّك بسرعة إلى الخلف في مهام عرض أو معالجة مستند DjVu الخاص بك عبر الوصول إلى الصفحة السابقة باستخدام هذه الخاصية المريحة. تنقل بكفاءة عبر المستند بسهولة. |
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
| static [LoadDocument](../../aspose.imaging.fileformats.djvu/djvuimage/loaddocument/#loaddocument)(Stream) | حمّل مستند DjVu الخاص بك باستخدام هذه الطريقة. بسط عمليتك عبر الوصول السريع واستيراد ملفات DjVu إلى تطبيقك. |
| static [LoadDocument](../../aspose.imaging.fileformats.djvu/djvuimage/loaddocument/#loaddocument_1)(Stream, LoadOptions) | استورد مستند DjVu الخاص بك باستخدام هذه الطريقة مع معلمات stream و loadOptions. سهل عمليتك من خلال الوصول السريع واستيراد ملفات DjVu إلى تطبيقك، مما يوفر مرونة وخيارات تخصيص لتلبية احتياجاتك. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.djvu/djvuimage/adjustbrightness/)(int) | قم بضبط *السطوع* للصورة باستخدام معلمة محددة، مما يوفر تحكمًا في مستويات الإضاءة لتحقيق وضوح بصري مثالي. تقوم هذه الطريقة بزيادة أو تقليل السطوع الكلي للصورة، مما يسمح بإجراء تعديلات دقيقة لتحقيق تأثيرات الإضاءة المطلوبة. من خلال تعديل السطوع، يمكن للمستخدمين تحسين رؤية الصورة وتعزيز إعادة إنتاج التفاصيل لتحسين تجربة المشاهدة. |
| override [AdjustContrast](../../aspose.imaging.fileformats.djvu/djvuimage/adjustcontrast/)(float) | حسّن تباين [`Image`](../../aspose.imaging/image/) لتحسين الوضوح البصري وإبراز التفاصيل باستخدام هذه الطريقة، التي تضبط الفرق في السطوع بين المناطق الفاتحة والداكنة. من خلال ضبط مستويات التباين بدقة، يمكن للمستخدمين الحصول على صور أكثر حيوية وتأثيرًا، مما يعزز جودة الصورة العامة ويزيد من وضوح التفاصيل. يساعد هذا الضبط على إظهار الفروق الدقيقة في اللون والملمس، مما ينتج صورًا أكثر ديناميكية وجاذبية بصريًا. |
| override [AdjustGamma](../../aspose.imaging.fileformats.djvu/djvuimage/adjustgamma/#adjustgamma)(float) | تصحيح جاما، خاصةً لقنوات الأحمر والأخضر والأزرق، يتضمن ضبط سطوع كل مكوّن لوني بشكل منفصل. من خلال تطبيق معاملات جاما مختلفة على قنوات RGB، يمكنك ضبط السطوع والتباين الكلي للصورة بدقة. تضمن هذه التقنية تمثيلًا دقيقًا للألوان وتحسين جودة الصورة البصرية عبر مختلف أجهزة العرض. |
| override [AdjustGamma](../../aspose.imaging.fileformats.djvu/djvuimage/adjustgamma/#adjustgamma_1)(float, float, float) | يتم تطبيق تصحيح الجاما على الصورة باستخدام معلمات قابلة للتخصيص لقنوات الأحمر والأخضر والأزرق، مما يسمح بضبط دقيق لتوازن الألوان والسطوع. تعزز هذه الطريقة جودة الصورة من خلال ضبط تمثيل الألوان بدقة، مما يضمن عرضًا مثاليًا عبر مختلف أجهزة العرض. يؤدي تعديل قيم الجاما لكل قناة إلى تحسين توازن الألوان والجاذبية البصرية. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | ينفّذ تعديلًا تلقائيًا متكيفًا للسطوع والتباين عبر الصورة بأكملها. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | يقوم بتدوير الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من بيانات Exif. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح، مما يعزز تجربة المستخدم ويقضي على الحاجة إلى التعديلات اليدوية. من خلال تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، مما يوفر تجربة مشاهدة سلسة عبر مختلف المنصات والأجهزة. تبسط عملية التدوير الآلية معالجة الصور وتحسن قابلية الاستخدام العامة، خاصةً عند التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المتنوعة. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.djvu/djvuimage/binarizebradley/#binarizebradley_1)(double, int) | التصنيف الثنائي باستخدام خوارزمية العتبة التكيفية لبرايدلي مع عتبة الصورة المتكاملة هو طريقة تحسب عتبة محلية لكل بكسل بناءً على الجوار المحلي. تتكيف مع تغيرات الإضاءة عبر الصورة، مما يجعلها مناسبة للصور ذات ظروف إضاءة غير متساوية. من خلال حساب العتبة باستخدام الصور المتكاملة، تتعامل بكفاءة مع أجواء كبيرة، مما يجعلها قابلة للتطبيق في التطبيقات الفورية. تُستخدم هذه التقنية عادةً في معالجة المستندات، والتعرف الضوئي على الأحرف (OCR)، ومهام تجزئة الصور حيث يكون التصنيف الثنائي الدقيق ضروريًا للتحليل اللاحق. |
| override [BinarizeFixed](../../aspose.imaging.fileformats.djvu/djvuimage/binarizefixed/)(byte) | التصنيف الثنائي باستخدام عتبة محددة مسبقًا يبسط الصور المعقدة إلى تمثيلات ثنائية، حيث يتم تصنيف البكسلات إما كالسوداء أو الأبيض بناءً على شدة إضاءةها مقارنةً بقيمة العتبة المحددة. تُستخدم هذه التقنية عادةً في معالجة الصور لتعزيز الوضوح، وتبسيط التحليل، وإعداد الصور للخطوات اللاحقة مثل التعرف الضوئي على الأحرف (OCR). من خلال تطبيق عتبة ثابتة، يمكنك تحويل الصور ذات التدرج الرمادي إلى شكل ثنائي بسرعة، مما يجعلها أسهل في الفهم واستخراج المعلومات ذات الأهمية. |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.djvu/djvuimage/binarizeotsu/)() | التصنيف الثنائي باستخدام عتبة أوتسو هو تقنية تحسب تلقائيًا قيمة عتبة مثالية بناءً على هيستوجرام الصورة. تفصل الصورة إلى المقدمة والخلفية عن طريق تقليل التباين داخل الفئة. تُستخدم طريقة أوتسو على نطاق واسع لتجزئة الصور إلى شكل ثنائي، خاصةً عندما يكون توزيع شدة البكسلات ثنائي القمة أو متعدد القمم. هذا النهج مفيد لمهام مثل اكتشاف الكائنات، وتجزئة الصور، واستخراج الميزات، حيث يكون التحديد الدقيق بين المقدمة والخلفية أمرًا حاسمًا. |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| override [CacheData](../../aspose.imaging.fileformats.djvu/djvuimage/cachedata/)() | قم بتخزين البيانات مؤقتًا بشكل خاص لتحسين الأداء وتقليل الحاجة إلى استرجاع البيانات المتكرر من المصادر الخارجية. يساعد هذا النهج أيضًا في الحفاظ على الموارد، خاصةً في السيناريوهات التي يكون فيها الوصول إلى البيانات متكررًا أو الموارد محدودة. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| override [Crop](../../aspose.imaging.fileformats.djvu/djvuimage/crop/#crop)(Rectangle) | \"Crop\" يقتطع صورتك للتركيز على تفاصيل محددة أو إزالة العناصر غير المرغوبة، مما يعزز تركيبتها وتأثيرها البصري. سواءً كنت تعدل الصور لوسائل التواصل الاجتماعي، أو تنشئ لافتات مواقع ويب، أو تصمم مواد مطبوعة، فإن هذه الأداة تساعدك على صقل صورك بدقة ووضوح. |
| override [Crop](../../aspose.imaging.fileformats.djvu/djvuimage/crop/#crop_1)(int, int, int, int) | يتيح لك Crop with shifts ضبط موضع وأبعاد المنطقة المقتطعة داخل الصورة بدقة. هذه الميزة لا تقدر بثمن لتصحيح التركيبات، ومحاذاة العناصر، وتأكيد نقاط التركيز في مرئياتك. من خلال دمج الإزاحات في عملية القص، يمكنك تحقيق دقة بكسلية مثالية وضبط إطار صورك بسهولة. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | يقوم بأداء التمويه على الصورة الحالية. |
| override [Dither](../../aspose.imaging.fileformats.djvu/djvuimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | وظيفة \"Dither\" تطبق تأثير التدرج المتناثر على صورتك، مما يعزز جودتها البصرية عن طريق تقليل التدرجات الحادة وتحسين انتقالات الألوان. سواءً كنت تعمل على فن رقمي، أو تصوير فوتوغرافي، أو مشاريع تصميم جرافيكي، فإن هذه الميزة تضيف لمسة احترافية لصورك، تجعلها تبدو أكثر سلاسة وتفصيلًا. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | أدمج توقيعًا رقميًا بناءً على كلمة المرور المقدمة في كل صفحة من الصورة. |
| override [Filter](../../aspose.imaging.fileformats.djvu/djvuimage/filter/)(Rectangle, FilterOptionsBase) | طبق الفلاتر على منطقة مستطيلة محددة داخل الصورة لتحسين أو تعديل مظهرها. من خلال استهداف مناطق معينة، تسمح هذه الطريقة بإجراء تعديلات دقيقة، مثل التشويش، أو الشحذ، أو تطبيق تأثيرات فنية، لتحقيق النتائج البصرية المطلوبة. يتيح ضبط الفلاتر على المناطق المختارة للمستخدمين تخصيص جمالية الصورة، تحسين الوضوح، وإنشاء تأثيرات فنية تتناسب مع تفضيلاتهم. |
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
| override [Grayscale](../../aspose.imaging.fileformats.djvu/djvuimage/grayscale/)() | تحويل إلى تدرج الرمادي يحول الصورة إلى تمثيل أبيض وأسود، حيث يتم تمثيل شدة كل بكسل بقيمة واحدة تتراوح بين الأسود والأبيض. يزيل هذا العملية معلومات اللون، مما ينتج صورة أحادية اللون. تُستخدم صور التدرج الرمادي عادةً في التطبيقات التي لا تكون فيها الألوان ضرورية أو حيث يُفضَّل البساطة، مثل مسح المستندات، والطباعة، وبعض أنواع تحليل الصور. |
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
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging.fileformats.djvu/djvuimage/resize/#resize_1)(int, int, ImageResizeSettings) | غيّر حجم الصورة إلى العرض والارتفاع المحددين مع تطبيق إعدادات إضافية حسب الحاجة. تمكّن هذه الطريقة المستخدمين من ضبط أبعاد الصورة مع الحفاظ على الخصائص المطلوبة مثل نسبة الأبعاد، جودة الصورة، وإعدادات الضغط. من خلال توفير مرونة في خيارات تغيير الحجم، يمكن للمستخدمين تعديل الصورة لتلبية المتطلبات المحددة وتحسين مظهرها لتطبيقات ومنصات مختلفة. |
| override [Resize](../../aspose.imaging.fileformats.djvu/djvuimage/resize/#resize_2)(int, int, ResizeType) | غيّر حجم الصورة باستخدام طريقة `Resize`، مما يوفر طريقة بسيطة وفعّالة لضبط أبعاد صورك وفقًا لمتطلباتك. تمكنك هذه الوظيفة المتعددة الاستخدامات من تكبير أو تصغير الصور بسهولة إلى الحجم المطلوب، مما يعزز قابلية استخدامها عبر مختلف المنصات والتطبيقات. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.djvu/djvuimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | تتيح لك طريقة `ResizeHeightProportionally` ضبط ارتفاع صورتك مع الحفاظ على نسبة أبعادها. يضمن ذلك بقاء الصورة على نسبها، مما يمنع التشويه ويحافظ على سلامتها البصرية. سواءً كنت تُحسّن الصور لصفحات الويب، أو تطبيقات الهواتف المحمولة، أو الوسائط المطبوعة، فإن هذه الطريقة تضمن أن تبدو صورك بأفضل شكل عبر مختلف المنصات والأجهزة. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.djvu/djvuimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | توفر طريقة `ResizeWidthProportionally` حلاً مريحًا لضبط عرض صورتك مع الحفاظ على نسبة أبعادها. من خلال تغيير عرض الصورة بشكل متناسب، يمكنك التأكد من أن صورك تظل جذابة بصريًا ومتسقة عبر مختلف الأجهزة وأحجام الشاشات، مما يعزز مرونتها وقابليتها للاستخدام في سياقات متعددة. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | دوّر الصورة حول المركز. |
| override [Rotate](../../aspose.imaging.fileformats.djvu/djvuimage/rotate/#rotate_1)(float, bool, Color) | دوّر الصورة حول مركزها باستخدام طريقة Rotate في فئة RasterCachedMultipageImage. تتيح لك هذه الميزة المريحة ضبط اتجاه الصور بسهولة مع الحفاظ على موقع مركزها، مما يعزز قدراتك على تعديل الصور. |
| override [RotateFlip](../../aspose.imaging.fileformats.djvu/djvuimage/rotateflip/)(RotateFlipType) | توفر طريقة `RotateFlip` خيارات تعديل متعددة لصورتك، مما يتيح لك تدويرها، أو عكسها، أو تنفيذ العمليتين معًا على الإطار النشط بشكل مستقل. سواءً كنت تعدل الصور، أو تنشئ رسومات، أو تحسن الفن الرقمي، فإن هذه الطريقة توفر تحكمًا دقيقًا في اتجاه وتكوين صورك، مما يضمن تحقيق رؤيتك الإبداعية بسهولة وكفاءة. |
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

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [PropertyChanged](../../aspose.imaging.fileformats.djvu/djvuimage/propertychanged/) | يحدث عندما يتغير قيمة الخاصية. |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة DJVU من تدفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة DJVU من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        // احفظ كل صفحة كصورة PNG منفردة.
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // أنشئ اسم ملف استنادًا إلى رقم الصفحة.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### انظر أيضًا

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../aspose.imaging.fileformats.djvu/)
* assembly [Aspose.Imaging](../../)


