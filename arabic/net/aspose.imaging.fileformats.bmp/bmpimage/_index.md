---
title: "الفئة BmpImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Bmp.BmpImage. يمكنك بسهولة التعامل مع ملفات Bitmap BMP و Device Independent Bitmap DIB مما يسهل التلاعب الفعال ومعالجة صور الـ raster. من خلال تنفيذ عمليات مختلفة على الصور، يبسط هذا API سير العمل ويقدم للمطورين مجموعة أدوات موثوقة للعمل مع صيغ BMP و DIB في تطبيقاتهم البرمجية"
type: docs
weight: 1430
url: /ar/net/aspose.imaging.fileformats.bmp/bmpimage/
---
## BmpImage class

يمكنك التعامل بسهولة مع ملفات Bitmap (BMP) وDevice Independent Bitmap (DIB)، مما يسهل التلاعب الفعال ومعالجة الصور النقطية. من خلال تنفيذ عمليات مختلفة على الصور، يبسط هذا API سير العمل، ويقدم للمطورين مجموعة أدوات موثوقة للعمل مع صيغ BMP و DIB في تطبيقاتهم البرمجية.

```csharp
public sealed class BmpImage : RasterCachedImage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [BmpImage](bmpimage/#constructor)(RasterImage) | أنشئ بسهولة نسخة جديدة من الفئة `BmpImage` عن طريق تهيئتها بكائن RasterImage. مثالي للمطورين الذين يرغبون في تحويل الصور النقطية الحالية إلى صيغة BmpImage بسلاسة، مما يضمن التوافق وسهولة التكامل في مشاريعهم |
| [BmpImage](bmpimage/#constructor_5)(Stream) | ابدأ باستخدام الفئة `BmpImage` بسهولة عن طريق تهيئة نسخة جديدة باستخدام هذا المُنشئ، مع استخدام تدفق كمدخل. مثالي للمطورين الذين يبحثون عن طريقة مريحة للعمل مع كائنات BmpImage من مصادر بيانات متعددة، مما يضمن المرونة وسهولة التكامل |
| [BmpImage](bmpimage/#constructor_7)(string) | ابدأ باستخدام الفئة BmpImage بسهولة باستخدام هذا المُنشئ الذي يهيئ نسخة جديدة. مثالي للمطورين الذين يرغبون في البدء بسرعة وكفاءة مع كائنات `BmpImage` |
| [BmpImage](bmpimage/#constructor_2)(int, int) | ابدأ باستخدام الفئة `BmpImage` بسهولة عن طريق إنشاء نسخة جديدة مع تحديد معلمات العرض والارتفاع. مثالي للمطورين الذين يبحثون عن طريقة مريحة لإنشاء كائنات BmpImage بأبعاد مخصصة، مما يضمن المرونة وسهولة التكامل في مشاريعهم |
| [BmpImage](bmpimage/#constructor_3)(int, int, ushort, IColorPalette) | ابدأ باستخدام الفئة `BmpImage` بسلاسة عن طريق تهيئة نسخة جديدة مع معلمات مثل العرض، الارتفاع، عمق البت، واللوحة. مثالي للمطورين الذين يبحثون عن طريقة مباشرة لإنشاء كائنات BmpImage بأبعاد وتكوينات ألوان مخصصة، مما يضمن المرونة والكفاءة في مشاريعهم |
| [BmpImage](bmpimage/#constructor_1)(RasterImage, ushort, BitmapCompression, double, double) | ابدأ العمل مع الفئة `BmpImage` بسلاسة عن طريق إنشاء نسخة جديدة باستخدام rasterImage مع معلمات محددة مثل bitsPerPixel والضغط. مثالي للمطورين الذين يبحثون عن طريقة مباشرة للتعامل مع كائنات BmpImage، مما يضمن المرونة والكفاءة في مشاريعهم |
| [BmpImage](bmpimage/#constructor_6)(Stream, ushort, BitmapCompression, double, double) | ابدأ العمل مع الفئة `BmpImage` بسلاسة عن طريق إنشاء نسخة جديدة باستخدام تدفق، مع معلمات محددة مثل bitsPerPixel والضغط. مثالي للمطورين الذين يبحثون عن طريقة مباشرة للتعامل مع كائنات BmpImage، مما يضمن المرونة والكفاءة في مشاريعهم |
| [BmpImage](bmpimage/#constructor_8)(string, ushort, BitmapCompression, double, double) | أنشئ بسهولة نسخة جديدة من الفئة `BmpImage` باستخدام هذا المُنشئ، مع تحديد معلمات مثل المسار، bitsPerPixel، والضغط. مثالي للمطورين الذين يرغبون في تهيئة كائنات BmpImage بسرعة وكفاءة، مع تحكم دقيق في خصائص الصورة |
| [BmpImage](bmpimage/#constructor_4)(int, int, ushort, IColorPalette, BitmapCompression, double, double) | أنشئ بسهولة نسخة جديدة من الفئة `BmpImage` باستخدام هذا المُنشئ، مع تحديد معلمات مثل العرض، الارتفاع، bitsPerPixel، واللوحة. مثالي للمطورين الذين يبحثون عن طريقة مريحة لإنشاء كائنات BmpImage بأبعاد وتكوينات ألوان مخصصة، مما يضمن المرونة وسهولة التكامل في مشاريعهم |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| [BitmapInfoHeader](../../aspose.imaging.fileformats.bmp/bmpimage/bitmapinfoheader/) { get; } | احصل بسرعة على التفاصيل الأساسية حول صورة الـ bitmap الخاصة بك باستخدام هذه الدالة البسيطة. مثالي للمطورين الذين يحتاجون إلى استرجاع معلومات الرأس لصورهم |
| override [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bmpimage/bitsperpixel/) { get; } | احصل بسهولة على عدد البتات لكل بكسل في الصورة باستخدام هذه الخاصية. مثالي للمطورين الذين يبحثون عن معلومات سريعة حول جودة وعمق الصورة |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Compression](../../aspose.imaging.fileformats.bmp/bmpimage/compression/) { get; } | استرجع بسهولة نوع الضغط المستخدم في الصورة باستخدام هذه الخاصية. مثالي للمطورين الذين يحتاجون إلى الوصول السريع إلى معلومات حول ضغط الصورة |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| override [FileFormat](../../aspose.imaging.fileformats.bmp/bmpimage/fileformat/) { get; } | استرجع بسهولة قيمة تنسيق الملف باستخدام هذه الخاصية سهلة الاستخدام. مثالي للمطورين الذين يبحثون عن وصول سريع إلى معلومات حول تنسيق الملف |
| override [HasAlpha](../../aspose.imaging.fileformats.bmp/bmpimage/hasalpha/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [`RasterImage`](../../aspose.imaging/rasterimage/) يحتوي على لون شفاف. |
| override [Height](../../aspose.imaging.fileformats.bmp/bmpimage/height/) { get; } | استرجع بسهولة ارتفاع الصورة باستخدام هذه الخاصية. مثالي للمطورين الذين يحتاجون إلى وصول سريع إلى معلومات حول أبعاد الصورة |
| override [HorizontalResolution](../../aspose.imaging.fileformats.bmp/bmpimage/horizontalresolution/) { get; set; } | تسمح لك هذه الخاصية بالحصول بسهولة أو ضبط الدقة الأفقية، المقاسة بالبكسل لكل بوصة، لكائن [`RasterImage`](../../aspose.imaging/rasterimage/). مثالي للمطورين الذين يحتاجون إلى تحكم دقيق في دقة الصورة لتطبيقاتهم |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | الحصول على شفافية هذه الصورة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | يحصل على بيانات تعريف الصورة. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرةً. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب ضرب مكونات الصورة مسبقًا. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | يحصل أو يعيّن محول الألوان المخصص |
| override [RawDataFormat](../../aspose.imaging.fileformats.bmp/bmpimage/rawdataformat/) { get; } | احصل بسهولة على تنسيق البيانات الخام الخاصة بك باستخدام هذه الدالة سهلة الاستخدام. مثالي للمطورين الذين يرغبون في الوصول السريع إلى معلومات حيوية حول تنسيق بياناتهم |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | يحصل على إعدادات البيانات الخام الحالية. لاحظ أنه عند استخدام هذه الإعدادات يتم تحميل البيانات بدون تحويل. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | يحصل أو يعيّن فهرس الاحتياطي للاستخدام عندما يكون فهرس اللوحة خارج النطاق. |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | يحصل أو يعيّن محول الألوان المفهرسة |
| override [RawLineSize](../../aspose.imaging.fileformats.bmp/bmpimage/rawlinesize/) { get; } | احصل بسرعة على حجم كل سطر خام بالبايت باستخدام هذه الخاصية البسيطة. مثالي للمطورين الذين يحتاجون إلى معالجة فعالة للبيانات الخام للصورة |
| [Size](../../aspose.imaging/image/size/) { get; } | يحصل على حجم الصورة. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor/) { get; set; } | يحصل على لون الشفافية في الصورة. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب تحديث بيانات التعريف XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب استخدام تحميل البيانات الخام عندما يكون تحميل البيانات الخام متاحًا. |
| override [VerticalResolution](../../aspose.imaging.fileformats.bmp/bmpimage/verticalresolution/) { get; set; } | استرجع بسهولة أو اضبط الدقة العمودية، المقاسة بالبكسل لكل بوصة، لهذا الكائن [`RasterImage`](../../aspose.imaging/rasterimage/) باستخدام هذه الخاصية. مثالي للمطورين الذين يتطلبون تحكمًا دقيقًا في دقة الصورة في تطبيقاتهم |
| override [Width](../../aspose.imaging.fileformats.bmp/bmpimage/width/) { get; } | احصل بسهولة على عرض الصورة باستخدام هذه الخاصية. مثالي للمطورين الذين يبحثون عن معلومات سريعة حول أبعاد الصورة |
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
| override [GetDefaultOptions](../../aspose.imaging.fileformats.bmp/bmpimage/getdefaultoptions/)(object[]) | استرجع الخيارات الافتراضية بسهولة باستخدام هذه الطريقة المبسطة. مثالي للمطورين الذين يبحثون عن وصول سريع إلى إعدادات الصورة الافتراضية أو التكوينات. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../../aspose.imaging/datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [`Save`](../../aspose.imaging/image/save/) كمعامل ثاني. |
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
| override [SetResolution](../../aspose.imaging.fileformats.bmp/bmpimage/setresolution/)(double, double) | قم بضبط دقة الـ[`RasterImage`](../../aspose.imaging/rasterimage/) بسهولة باستخدام هذه الطريقة السهلة الاستخدام. مثالي للمطورين الذين يبحثون عن تحكم دقيق في دقة الصورة في تطبيقاتهم. |
| override [ToBitmap](../../aspose.imaging.fileformats.bmp/bmpimage/tobitmap/)() | حوّل صورتك النقطية بسهولة إلى bitmap باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يحتاجون إلى الانتقال بسلاسة بين صيغ الصور المختلفة. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |

## أمثلة

فك ضغط صورة BMP التي تم ضغطها مسبقًا باستخدام خوارزمية ضغط DXT1.

```csharp
[C#]

using (var image = Image.Load("CompressedTiger.bmp"))
{
    image.Save("DecompressedTiger.bmp", new BmpOptions());
}
```

ضغط صورة BMP باستخدام خوارزمية ضغط DXT1.

```csharp
[C#]

using (var image = Image.Load("Tiger.bmp"))
{
    image.Save("CompressedTiger.bmp", new BmpOptions { Compression = BitmapCompression.Dxt1 });
}
```

يوضح المثال كيفية إزالة أي كائن من الصورة باستخدام Graphics Path مع خوارزمية Telea.

```csharp
[C#]

var imageFilePath = "ball.png"; 
using (var image = Image.Load(imageFilePath))
{
    var pngImage = (PngImage)image;

    var mask = new GraphicsPath();
    var firstFigure = new Figure();
    firstFigure.AddShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.AddFigure(firstFigure);

    var options = new TeleaWatermarkOptions(mask);

    var result = WatermarkRemover.PaintOver(pngImage, options);

    result.Save(outputPath);
}
```

يوضح المثال كيفية تصدير BmpImage بنوع الضغط Rgb.

```csharp
[C#]

string sourcePath = "input.png";
// حمِّل صورة PNG من ملف.
using (Image pngImage = Image.Load(sourcePath))
{
    // يتم حفظ صورة BMP بدعم الشفافية افتراضيًا، ويتم ذلك باستخدام طريقة الضغط BitmapCompression.Bitfields.
    // لحفظ صورة BMP باستخدام طريقة الضغط Rgb، يجب تحديد BmpOptions مع خاصية Compression مضبوطة على BitmapCompression.Rgb.
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Rgb });
}
```

يوضح المثال كيفية إزالة أي كائن من الصورة باستخدام Graphics Path مع خوارزمية Content Aware fill.

```csharp
[C#]

var imageFilePath = "ball.png"; 
using (var image = Image.Load(imageFilePath))
{
    var pngImage = (PngImage)image;

    var mask = new GraphicsPath();
    var firstFigure = new Figure();
    firstFigure.AddShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.AddFigure(firstFigure);

    var options = new ContentAwareFillWatermarkOptions(mask) 
    { 
        MaxPaintingAttempts = 4
    };

    var result = WatermarkRemover.PaintOver(pngImage, options);

    result.Save(outputPath);
}
```

يوضح المثال التالي كيفية إنشاء صورة BMP بالحجم المحدد.

```csharp
[C#]

string dir = "c:\\temp\\";

// أنشئ صورة BMP بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // املأ الصورة بتدرج خطي بسيط من الأحمر إلى الأسود.
    int width = bmpImage.Width;
    int height = bmpImage.Height;
    for (int y = 0; y < height; y++)
    {
        for (int x = 0; x < width; x++)
        {
            int hue = (255 * x) / width;
            bmpImage.SetPixel(x, y, Aspose.Imaging.Color.FromArgb(255, hue, 0, 0));
        }
    }

    using (System.IO.FileStream stream = new System.IO.FileStream(dir + "output.bmp", System.IO.FileMode.Create))
    {
        bmpImage.Save(stream);
    }
}
```

يوضح المثال كيفية تصدير BmpImage من ملف Png مع الحفاظ على قناة ألفا، وحفظ ملف Bmp مع الشفافية.

```csharp
[C#]

string sourcePath = "input.png";
// حمِّل صورة PNG من ملف.
using (Image pngImage = Image.Load(sourcePath))
{
    // يتم حفظ صورة BMP بدعم الشفافية افتراضيًا.
    // إذا كنت ترغب في تحديد هذا الوضع صراحةً، يجب ضبط خاصية Compression في BmpOptions على BitmapCompression.Bitfields.
    // طريقة الضغط BitmapCompression.Bitfields هي طريقة الضغط الافتراضية في BmpOptions.
    // لذلك يمكن تحقيق نفس نتيجة تصدير صورة Bmp مع الشفافية إما بإحدى الطرق التالية.
    // مع خيارات افتراضية ضمنية:
    pngImage.Save(outputPath);
    // مع خيارات افتراضية صريحة:
    pngImage.Save(outputPath, new BmpOptions());
    // تحديد طريقة الضغط BitmapCompression.Bitfields:
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Bitfields });
}
```

### انظر أيضًا

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp/)
* assembly [Aspose.Imaging](../../)


