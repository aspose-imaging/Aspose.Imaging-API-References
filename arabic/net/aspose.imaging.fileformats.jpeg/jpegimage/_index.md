---
title: "فئة JpegImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.FileFormats.Jpeg.JpegImage. قم بالتعامل بفعالية مع صور JPEG النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا التي تدعم ملفات تعريف الألوان المتنوعة مثل RGB و CMYK، وتتيح تخصيص عدد البتات لكل بكسل، ومعالجة حاويات البيانات الوصفية EXIF و JFIF و XMP. استمتع بالدوران التلقائي بناءً على بيانات الاتجاه واختر من مستويات ضغط مختلفة بما في ذلك JPEG غير الفاقد لتحقيق توازن مثالي بين جودة الصورة وحجم الملف لمشاريعك."
type: docs
weight: 6880
url: /ar/net/aspose.imaging.fileformats.jpeg/jpegimage/
---
## JpegImage class

قم بالتعامل بفعالية مع صور JPEG النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا، حيث نوفر دعمًا لمختلف ملفات تعريف الألوان مثل RGB وCMYK، وإمكانية تخصيص عدد البتات لكل بكسل، ومعالجة حاويات البيانات الوصفية EXIF وJFIF وXMP. استمتع بالدوران التلقائي بناءً على بيانات الاتجاه واختر من مستويات ضغط مختلفة، بما في ذلك JPEG غير الفاقد، لتحقيق توازن مثالي بين جودة الصورة وحجم الملف لمشاريعك.

```csharp
public sealed class JpegImage : RasterCachedImage, IHasJpegExifData
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [JpegImage](jpegimage/#constructor_1)(RasterImage) | قم بإنشاء نسخة جديدة من الفئة `JpegImage` باستخدام معلمة صورة نقطية. يوفر هذا المُنشئ طريقة مريحة لإنشاء صور JPEG مباشرةً من الصور النقطية، مما يبسط سير العمل عند التعامل مع صور JPEG في تطبيقاتك. |
| [JpegImage](jpegimage/#constructor_3)(Stream) | قم بتهيئة كائن صورة JPEG باستخدام الفئة `JpegImage` مع معلمة تدفق. يبسط هذا المُنشئ عملية التعامل مع صور JPEG، مقدماً نهجًا بسيطًا لدمجها في مشاريعك بسهولة. |
| [JpegImage](jpegimage/#constructor_4)(string) | تبدأ الفئة `JpegImage` بسهولة عبر استدعاء مُنشئها مع معلمة المسار المحددة. يتيح هذا المُنشئ إنشاء صور JPEG بسلاسة، مما يضمن دمجًا سريعًا في مشاريعك بسهولة. |
| [JpegImage](jpegimage/#constructor_2)(int, int) | أنشئ نسخة جديدة من الفئة `JpegImage` باستخدام معلمات العرض والارتفاع المحددة. يتيح لك هذا المُنشئ إنشاء صور JPEG بأبعاد مخصصة، مما يمنحك مرونة في إدارة أحجام الصور في تطبيقك. |
| [JpegImage](jpegimage/#constructor)(JpegOptions, int, int) | قم بتهيئة كائن `JpegImage` جديد باستخدام خيارات JPEG المقدمة. يمنحك هذا المُنشئ القدرة على تخصيص إعدادات مختلفة لصورة JPEG، مثل مستوى الضغط، الجودة، ومعلمات إضافية، مما يوفر تحكمًا دقيقًا في تنسيق الصورة الناتج. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.jpeg/jpegimage/bitsperpixel/) { get; } | استرجع عمق البكسل للصورة بسهولة باستخدام هذه الخاصية، مما يوفّر نظرة على غنى تمثيل اللون أو التدرج الرمادي. سواء كانت صورة فوتوغرافية نابضة بالحياة أو رسمًا أحادي اللون، تُقدّم هذه الخاصية معلومات حيوية حول تعقيد الصورة البصري. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [CmykColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/cmykcolorprofile/) { get; set; } | ملف تعريف اللون CMYK المرتبط بصور JPEG بصيغة CMYK و YCCK يضمن تحويلًا دقيقًا للألوان ومطابقة عالية. يعمل بالتنسيق مع RGBColorProfile لضمان تمثيل لون دقيق عبر مختلف الأجهزة والتطبيقات. هذه المجموعة ضرورية للحفاظ على اتساق عرض الألوان وتحقيق جودة صورة مثالية. |
| [Comment](../../aspose.imaging.fileformats.jpeg/jpegimage/comment/) { get; set; } | إدارة تعليقات ملفات JPEG باستخدام هذه الخاصية، مما يتيح لك إضافة أو استرجاع ملاحظات وصفية مرتبطة بالصورة. سواء كان ذلك بوضع وسوم للصور عبر البيانات الوصفية أو إلحاق سياق إضافي، توفر هذه الخاصية مرونة في تنظيم وتصنيف ملفات JPEG الخاصة بك. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [DestinationCmykColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/destinationcmykcolorprofile/) { get; set; } | ملف تعريف اللون CMYK ضروري للتحويل الدقيق للألوان في صور JPEG بصيغة CMYK و YCCK أثناء عملية الحفظ. يعمل بالتوازي مع RGBColorProfile لضمان تمثيل لون صحيح، مع الحفاظ على الاتساق والجودة عبر مختلف الأجهزة والبرمجيات. هذا التزامن أساسي لتحقيق عرض ألوان دقيق وموثوق في الصور المحفوظة نهائيًا. |
| [DestinationRgbColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/destinationrgbcolorprofile/) { get; set; } | ملف تعريف اللون RGBColorProfile أساسي للتحويل الدقيق للألوان في صور JPEG بصيغة CMYK و YCCK أثناء عملية الحفظ. عند اقترانه بـ CMYKColorProfile، يضمن أن الألوان تُعرض بشكل صحيح ويحافظ على الاتساق عبر مختلف الأجهزة والتطبيقات. هذه التركيبة ضرورية للحفاظ على تمثيل اللون المقصود وتحقيق مخرجات صورة عالية الجودة. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging.fileformats.jpeg/jpegimage/exifdata/) { get; set; } | إدارة بيانات EXIF باستخدام هذه الخاصية، مما يتيح لك إضافة أو استرجاع البيانات الوصفية المرتبطة بالصورة. سواء كان ذلك استخراج معلومات حول إعدادات الكاميرا أو تعديل البيانات الوصفية الموجودة، توفر هذه الخاصية مرونة في إدارة حاوية بيانات EXIF. (خاصيتان) |
| override [FileFormat](../../aspose.imaging.fileformats.jpeg/jpegimage/fileformat/) { get; } | استرجع تنسيق الصورة بسهولة باستخدام هذه الخاصية. تُقدّم نظرة قيمة على تنسيق الملف، مما يساعد في دمج سلس وفحوصات توافق عبر مختلف المنصات والتطبيقات. |
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [`RasterImage`](../../aspose.imaging/rasterimage/) يحتوي على لون شفاف. |
| override [Height](../../aspose.imaging.fileformats.jpeg/jpegimage/height/) { get; } | استرجع ارتفاع الصورة بسهولة باستخدام هذه الخاصية. تُوفر وصولًا سريعًا إلى البُعد العمودي للصورة، مما يتيح لك تحديد حجمها ونسبة أبعادها بكفاءة دون الحاجة إلى حسابات معقدة أو طرق إضافية. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/horizontalresolution/) { get; set; } | تمنحك هذه الخاصية الوصول إلى الدقة الأفقية لـ [`RasterImage`](../../aspose.imaging/rasterimage/)، مقاسةً بالبكسل لكل بوصة. من خلال ضبط أو استرجاع هذه القيمة، يمكنك التحكم بدقة في دقة الصورة، مما يضمن تلبية متطلباتك الخاصة للجودة والوضوح. |
| [IgnoreEmbeddedColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/ignoreembeddedcolorprofile/) { get; set; } | تسترجع أو تعدّل العلامة التي تحدد ما إذا كان ملف تعريف اللون المدمج سيتم تجاهله. من خلال ضبط هذه العلامة، يمكن للمستخدمين تحديد ما إذا كان يجب استخدام ملف تعريف اللون الافتراضي بدلاً من المدمج. يضمن هذا الخيار تحكمًا أكبر في إدارة الألوان، مما يسهل التعديلات للحفاظ على الاتساق والتوافق عبر مختلف المنصات والتطبيقات. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | الحصول على شفافية هذه الصورة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| [Jfif](../../aspose.imaging.fileformats.jpeg/jpegimage/jfif/) { get; set; } | تتيح لك هذه الخاصية الوصول إلى بيانات JFIF (تنسيق تبادل ملفات JPEG) المرتبطة بصورة JPEG أو تعديلها. JFIF هو تنسيق قياسي لتبادل الصور المضغوطة بصيغة JPEG بين الحواسيب والأجهزة الأخرى. من خلال الحصول على هذه الخاصية أو ضبطها، يمكنك التفاعل مع بيانات JFIF، التي قد تشمل معلومات مثل دقة الصورة، نسبة الأبعاد، والصورة المصغرة. |
| [JpegOptions](../../aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions/) { get; } | احصل على إمكانية الوصول إلى خيارات JPEG المستخدمة أثناء إنشاء أو تحميل هذا الكائن `JpegImage` بسهولة. توفر هذه الخاصية تفاصيل قيمة حول الإعدادات المحددة المستخدمة، مما يمكّن المستخدمين من فهم وتكرار سير عمل معالجة الصور بفعالية. سواء كانت مستويات الضغط أو إعدادات الجودة أو غيرها من المعلمات، فإن هذه الخاصية تقدم رؤى أساسية لتعديل الصور بسلاسة. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | يحصل على بيانات تعريف الصورة. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | يحصل أو يعيّن محول الألوان المخصص |
| override [RawDataFormat](../../aspose.imaging.fileformats.jpeg/jpegimage/rawdataformat/) { get; } | تسترجع هذه الخاصية تنسيق البيانات الخام للصورة، والذي يوضح كيفية هيكلة البيانات المشفرة للصورة. فهم تنسيق البيانات الخام أمر أساسي لمعالجة أو تعديل بيانات الصورة بفعالية. يوفر رؤى حول التمثيل الأساسي للصورة، مثل ما إذا كانت مضغوطة أو مشفرة في مساحة لون معينة أو مخزنة بتنسيق ملف محدد. يتيح الوصول إلى هذه الخاصية الحصول على معلومات قيمة حول بنية بيانات الصورة، مما يمكنك من تنفيذ عمليات أو تحسينات مختلفة مخصصة لتنسيقها المحدد. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات بدون تحويل. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | يحصل أو يعيّن فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق. |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | يحصل أو يعيّن محول الألوان المفهرسة |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | يحصل على حجم السطر الخام بالبايت. |
| [RgbColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/rgbcolorprofile/) { get; set; } | ملف تعريف اللون RGB لصور JPEG بنظام CMYK وYCCK يضمن تحويل اللون وتمثيله بدقة. يجب إقرانه بـ **CMYKColorProfile** للحفاظ على التناسق والدقة في عرض الألوان. هذا الإقران ضروري للتطبيقات التي تتطلب إدارة لون دقيقة وإعادة إنتاج الصور، مما يضمن تفسير بيانات RGB وعرضها بشكل صحيح. |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor/) { get; set; } | يحصل على لون الشفافية في الصورة. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات التعريف XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| override [VerticalResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/verticalresolution/) { get; set; } | تدير هذه الخاصية الدقة العمودية، المعبر عنها بالبكسل لكل بوصة، للـ [`RasterImage`](../../aspose.imaging/rasterimage/) المرتبط. يؤثر تعديل هذه الدقة على حجم وجودة الصورة عند طباعتها أو عرضها بحجم مادي ثابت. من خلال ضبط هذه الخاصية، تتحكم في كثافة تجميع بكسلات الصورة عمودياً، مما يؤثر على وضوحها وحدة تفاصيلها العامة. |
| override [Width](../../aspose.imaging.fileformats.jpeg/jpegimage/width/) { get; } | تسترجع هذه الخاصية عرض الصورة، معبرًا عنه بالبكسل. توفر معلومات أساسية حول أبعاد الصورة، مما يتيح عرضًا دقيقًا، وتعديلًا، أو إظهارًا لبيانات الصورة. |
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
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| override [GetModifyDate](../../aspose.imaging.fileformats.jpeg/jpegimage/getmodifydate/)(bool) | تسترجع التاريخ والوقت الذي خضعت فيه صورة المورد لأحدث تعديل. توفر هذه الطريقة بيانات وصفية قيمة، مما يمكّن المستخدمين من تتبع وإدارة تحديثات ملف الصورة بفعالية. من خلال الوصول إلى هذه المعلومات، يمكن للمستخدمين ضمان سلامة وحداثة موارد الصور الخاصة بهم، مما يسهل اتخاذ قرارات مستنيرة بشأن استخدام الصورة وصيانتها. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.jpeg/jpegimage/getoriginaloptions/)() | يحصل على خيارات الصورة الأصلية لهذا الكائن [`Image`](../../aspose.imaging/image/). |
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
| override [RemoveMetadata](../../aspose.imaging.fileformats.jpeg/jpegimage/removemetadata/)() | يزيل بيانات التعريف لهذا الكائن الصورة عن طريق تعيين قيم [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) و[`ExifData`](../../aspose.imaging.exif/ihasexifdata/exifdata/) إلى `null`. |
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
| override [SetResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/setresolution/)(double, double) | يحدد الدقة للـ [`RasterImage`](../../aspose.imaging/rasterimage/) المحدد، مما يضمن تحجيمًا وطباعة دقيقة. تمكّن هذه الطريقة المستخدمين من تعديل دقة الصورة لتلبية متطلباتهم الخاصة، سواء للعرض الرقمي أو النسخ المادي. من خلال ضبط الدقة، يمكن للمستخدمين تحسين جودة الصورة وضمان التوافق مع مختلف أجهزة الإخراج والوسائط، مما يعزز التجربة البصرية العامة وقابلية استخدام الصورة. |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | يحوّل الصورة النقطية إلى bitmap. هذه الطريقة غير مدعومة في الإصدارات بدءًا من .Net7.0 وما فوق. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |

## أمثلة

الوصول إلى ملاحظات الصانع للكاميرا في صورة JPEG.

```csharp
[C#]

using (var image = (JpegImage)Image.Load("Sample.jpg"))
{
    foreach (var makerNote in image.ExifData.MakerNotes)
    {
        Console.WriteLine("Name = {0}, Value = {1}", makerNote.Name, makerNote.Value);
    }
}
```

يوضح المثال كيفية تحميل كائن JpegImage من ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة JPEG من ملف.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // قم ببعض معالجة الصورة.
    // احفظ إلى ملف JPEG آخر.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### انظر أيضًا

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* interface [IHasJpegExifData](../../aspose.imaging.exif/ihasjpegexifdata/)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../aspose.imaging.fileformats.jpeg/)
* assembly [Aspose.Imaging](../../)


