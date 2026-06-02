---
title: "الفئة DjvuRaster"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Djvu.DjvuRaster. فئة لتمثيل صورة Djvu النقطية حيث يقع نتيجة بعض العملية"
type: docs
weight: 2550
url: /ar/net/aspose.imaging.fileformats.djvu/djvuraster/
---
## DjvuRaster class

فئة لتمثيل صورة نقطية Djvu حيث توجد نتيجة عملية ما

```csharp
public sealed class DjvuRaster : RasterCachedImage
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.djvu/djvuraster/bitsperpixel/) { get; } | الحصول على عدد البتات لكل بكسل في الصورة. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | الحصول على حاوية [`Image`](../../aspose.imaging/image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat/) { get; } | يحصل على قيمة تنسيق الملف |
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [`RasterImage`](../../aspose.imaging/rasterimage/) يحتوي على لون شفاف. |
| override [Height](../../aspose.imaging.fileformats.djvu/djvuraster/height/) { get; } | الحصول على الارتفاع. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | الحصول على أو تعيين الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذه [`RasterImage`](../../aspose.imaging/rasterimage/). |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | الحصول على شفافية هذه الصورة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
| [Length](../../aspose.imaging.fileformats.djvu/djvuraster/length/) { get; } | يحصل على الطول. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | يحصل على بيانات تعريف الصورة. |
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
| override [Width](../../aspose.imaging.fileformats.djvu/djvuraster/width/) { get; } | الحصول على العرض. |
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
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | يعيّن الدقة لهذا [`RasterImage`](../../aspose.imaging/rasterimage/). |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | يحوّل الصورة النقطية إلى bitmap. هذه الطريقة غير مدعومة في الإصدارات بدءًا من .Net7.0 وما فوق. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين كائن *metadata*، إذا كان هذا [`Image`](../../aspose.imaging/image/) يدعم ويطبق نوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |

### انظر أيضًا

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../aspose.imaging.fileformats.djvu/)
* assembly [Aspose.Imaging](../../)


