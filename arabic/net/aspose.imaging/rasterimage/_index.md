---
title: "فئة RasterImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.RasterImage. تمثل صورة نقطية تدعم عمليات الرسومات النقطية"
type: docs
weight: 11390
url: /ar/net/aspose.imaging/rasterimage/
---
## RasterImage class

يمثل صورة نقطية تدعم عمليات الرسومات النقطية.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يتم تعديل اللوحة تلقائيًا. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية. |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel/) { get; } | الحصول على عدد البتات لكل بكسل في الصورة. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | الحصول على حدود الصورة. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي يحدد الحد الأقصى المسموح به لجميع المخازن الداخلية. |
| [Container](../../aspose.imaging/image/container/) { get; } | يحصل على حاوية [`Image`](../image/). |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | الحصول على تدفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثال تم التخلص منه. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | الحصول على أو تعيين بيانات Exif. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat/) { get; } | يحصل على قيمة تنسيق الملف |
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت هذه المثيلة `RasterImage` لها لون شفاف. |
| abstract [Height](../../aspose.imaging/image/height/) { get; } | الحصول على ارتفاع الصورة. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | يحصل أو يعيّن الدقة الأفقية، بوحدة البكسل لكل بوصة، لهذه `RasterImage`. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | الحصول على شفافية هذه الصورة. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | الحصول على أو تعيين مراقب المقاطعة. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | الحصول على قيمة تشير إلى ما إذا كان تحميل البيانات الخام متاحًا. |
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
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution/) { get; set; } | يحصل أو يعيّن الدقة العمودية، بوحدة البكسل لكل بوصة، لهذه `RasterImage`. |
| abstract [Width](../../aspose.imaging/image/width/) { get; } | يحصل على عرض الصورة. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | يحصل أو يعيّن بيانات Xmp. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [AdjustBrightness](../../aspose.imaging/rasterimage/adjustbrightness/)(int) | ضبط السطوع للصورة. |
| virtual [AdjustContrast](../../aspose.imaging/rasterimage/adjustcontrast/)(float) | تباين الصورة |
| virtual [AdjustGamma](../../aspose.imaging/rasterimage/adjustgamma/#adjustgamma)(float) | تصحيح جاما للصورة. |
| virtual [AdjustGamma](../../aspose.imaging/rasterimage/adjustgamma/#adjustgamma_1)(float, float, float) | تصحيح جاما للصورة. |
| virtual [AnalyzePercentageDigitalSignature](../../aspose.imaging/rasterimage/analyzepercentagedigitalsignature/)(string) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| virtual [AutoBrightnessContrast](../../aspose.imaging/rasterimage/autobrightnesscontrast/)() | تطبيع تلقائي متكيف للسطوع والتباين لكامل الصورة. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | يقوم بتدوير الصورة تلقائيًا بناءً على بيانات الاتجاه المستخرجة من بيانات Exif. تضمن هذه الطريقة عرض الصور بالاتجاه الصحيح، مما يعزز تجربة المستخدم ويقضي على الحاجة إلى التعديلات اليدوية. من خلال تحليل معلومات Exif، يتم تدوير الصورة وفقًا لذلك، مما يوفر تجربة مشاهدة سلسة عبر مختلف المنصات والأجهزة. تبسط عملية التدوير الآلية معالجة الصور وتحسن قابلية الاستخدام العامة، خاصةً عند التعامل مع دفعات كبيرة من الصور ذات الاتجاهات المتنوعة. |
| virtual [BinarizeBradley](../../aspose.imaging/rasterimage/binarizebradley/#binarizebradley)(double) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| virtual [BinarizeBradley](../../aspose.imaging/rasterimage/binarizebradley/#binarizebradley_1)(double, int) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة. |
| virtual [BinarizeFixed](../../aspose.imaging/rasterimage/binarizefixed/)(byte) | تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا |
| virtual [BinarizeOtsu](../../aspose.imaging/rasterimage/binarizeotsu/)() | تحويل الصورة إلى ثنائية باستخدام عتبة Otsu |
| [Blend](../../aspose.imaging/rasterimage/blend/#blend_1)(Point, RasterImage, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| virtual [Blend](../../aspose.imaging/rasterimage/blend/#blend)(Point, RasterImage, Rectangle, byte) | يمزج هذه النسخة من الصورة مع الصورة *overlay*. |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) الأساسي. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة. |
| virtual [Crop](../../aspose.imaging/image/crop/)(Rectangle) | يقص المستطيل المحدد. |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | قص الصورة مع إزاحات. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| [Dither](../../aspose.imaging/rasterimage/dither/#dither)(DitheringMethod, int) | يقوم بأداء التمويه على الصورة الحالية. |
| abstract [Dither](../../aspose.imaging/rasterimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | يقوم بأداء التمويه على الصورة الحالية. |
| virtual [EmbedDigitalSignature](../../aspose.imaging/rasterimage/embeddigitalsignature/)(string) | إدراج توقيع رقمي بناءً على كلمة المرور المقدمة داخل الصورة باستخدام تقنية التضمين. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter/)(Rectangle, FilterOptionsBase) | يفلتر المستطيل المحدد. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | يحصل على بكسل صورة 32-بت ARGB. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | يحصل على مصفوفة بكسلات 32-بت ARGB الافتراضية. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | يحصل على الخيارات الافتراضية. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | يحصل على مصفوفة البكسلات الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/#getdefaultrawdata)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/#getdefaultrawdata_1)(Rectangle, IPartialRawDataLoader, RawDataSettings) | يحصل على مصفوفة البيانات الخام الافتراضية باستخدام محمل البكسل الجزئي. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | يحصل على تاريخ ووقت آخر تعديل لصورة المورد. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق اللون والمعلمات الأخرى للصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [`Save`](../datastreamsupporter/save/)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومرّرها إلى طريقة [`Save`](../image/save/) كمعامل ثانٍ. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | يحصل على بكسل صورة. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | يحول إلى aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | يحصل على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا، لتحديد زاوية الانحراف عند المسح. |
| virtual [Grayscale](../../aspose.imaging/rasterimage/grayscale/)() | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| virtual [IsDigitalSigned](../../aspose.imaging/rasterimage/isdigitalsigned/)(string, int) | يُجري فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والحدّ المحدد. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels/)(Rectangle) | يحمّل بكسلات ARGB 32‑بت. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels/)(Rectangle) | يحمّل بكسلات ARGB 64‑بت. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels/)(Rectangle) | يحمّل بكسلات بتنسيق CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | يحمّل بكسلات ARGB 32‑بت جزئيًا عن طريق الحزم. |
| [LoadPartialArgb64Pixels](../../aspose.imaging/rasterimage/loadpartialargb64pixels/)(Rectangle, IPartialArgb64PixelLoader) | يحمّل بكسلات ARGB 64‑بت جزئيًا عن طريق الحزم. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | يحمّل البكسلات جزئيًا عن طريق الحزم. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels/)(Rectangle) | يحمّل البكسلات. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata/#loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | يحمّل البيانات الخام. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata/#loadrawdata_1)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | يحمّل البيانات الخام. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle/#normalizeangle)() | يُطبع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئيًا للتخلص من الانحراف. تستخدم هذه الطريقة الأساليب [`GetSkewAngle`](./getskewangle/) و[`Rotate`](./rotate/). |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle/#normalizeangle_1)(bool, Color) | يُطبع الزاوية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئيًا للتخلص من الانحراف. تستخدم هذه الطريقة الأساليب [`GetSkewAngle`](./getskewangle/) و[`Rotate`](./rotate/). |
| virtual [NormalizeHistogram](../../aspose.imaging/rasterimage/normalizehistogram/)() | يضبط هيستوجرام الصورة — يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | يقرأ كامل سطر المسح وفقًا لفهرس سطر المسح المحدد. |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | يزيل بيانات التعريف الخاصة بهذه الصورة عن طريق تعيين قيمة [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) إلى `null`. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/#replacecolor)(Color, byte, Color) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/#replacecolor_1)(int, byte, int) | يستبدل لونًا بآخر مع فرق مسموح ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/#replacenontransparentcolors)(Color) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية لحفظ الحواف السلسة. ملاحظة: إذا استخدمتها على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | يُعيد تحجيم الصورة. يتم استخدام NearestNeighbourResample الافتراضي. |
| override [Resize](../../aspose.imaging/rasterimage/resize/#resize_1)(int, int, ImageResizeSettings) | يعيد تحجيم الصورة باستخدام خيارات موسعة. |
| virtual [Resize](../../aspose.imaging/image/resize/)(int, int, ResizeType) | تغيير حجم الصورة. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | يُعيد تحجيم الارتفاع بنسبية. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | يُعيد تحجيم الارتفاع بنسبية. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | يُعيد تحجيم الارتفاع بنسبية. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | يقوم بتغيير عرض الصورة بشكل متناسب. يتم استخدام NearestNeighbourResample الافتراضي. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | يقوم بتغيير عرض الصورة بشكل متناسب. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/#rotate)(float) | دوّر الصورة حول المركز. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate/#rotate_1)(float, bool, Color) | دوّر الصورة حول المركز. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip/)(RotateFlipType) | يدور أو يقلب أو يدور ويقلب الصورة. |
| [Save](../../aspose.imaging/image/save/)() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| override [Save](../../aspose.imaging/image/save/)(string) | يحفظ الصورة إلى موقع الملف المحدد. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.imaging/rasterimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels/)(Rectangle, int[]) | يحفظ بكسلات ARGB 32 بت. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | يحفظ البكسلات. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels/)(Rectangle, Color[]) | يحفظ البكسلات. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | يحفظ البيانات الخام. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel/)(int, int, int) | يضبط بكسل صورة ARGB 32 بت للموقع المحدد. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | يضبط لوحة ألوان الصورة. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | يضبط بكسل الصورة للموقع المحدد. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | يعيّن الدقة لهذه `RasterImage`. |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | يحوّل الصورة النقطية إلى bitmap. هذه الطريقة غير مدعومة في الإصدارات بدءًا من .Net7.0 وما فوق. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | يحاول تعيين مثيل *metadata*، إذا كان هذا المثيل [`Image`](../image/) يدعم ويطبق النوع [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/). |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | يكتب كامل سطر المسح إلى فهرس سطر المسح المحدد. |

## أمثلة

يوضح هذا المثال كيفية تحميل معلومات البكسل في مصفوفة من النوع Color، تعديل المصفوفة وإعادتها إلى الصورة. لتنفيذ هذه العمليات، ينشئ هذا المثال ملف صورة جديد (بتنسيق GIF) باستخدام كائن MemoryStream.

```csharp
[C#]

//إنشاء مثيل من MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //إنشاء مثيل من GifOptions وتعيين خصائصه المتنوعة بما في ذلك خاصية Source
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //إنشاء مثيل من Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //احصل على بكسلات الصورة عن طريق تحديد المنطقة كحدود الصورة
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //التكرار عبر المصفوفة وتعيين لون البكسل المفهرس البديل
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //تعيين لون البكسل المفهرس إلى الأصفر
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //تعيين لون البكسل المفهرس إلى الأزرق
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //تطبيق تغييرات البكسل على الصورة
        image.SavePixels(image.Bounds, pixels);

        // احفظ جميع التغييرات.
        image.Save();
    }

    // كتابة MemoryStream إلى ملف
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### انظر أيضًا

* class [Image](../image/)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


