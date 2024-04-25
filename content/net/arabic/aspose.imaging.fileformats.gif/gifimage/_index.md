---
title: GifImage
second_title: Aspose.Imaging لمرجع NET API
description: صورة gif .
type: docs
weight: 6700
url: /ar/aspose.imaging.fileformats.gif/gifimage/
---
## GifImage class

صورة gif .

```csharp
public sealed class GifImage : RasterCachedMultipageImage, IMultipageImageExt
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [GifImage](gifimage#constructor)(GifFrameBlock) | يقوم بتهيئة مثيل جديد لملف[`GifImage`](../gifimage) فئة . |
| [GifImage](gifimage#constructor_1)(GifFrameBlock, IColorPalette) | يقوم بتهيئة مثيل جديد لملف[`GifImage`](../gifimage) فئة . |
| [GifImage](gifimage#constructor_2)(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) | يقوم بتهيئة مثيل جديد لملف[`GifImage`](../gifimage) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.gif/gifimage/activeframe) { get; set; } | الحصول على أو تحديد الإطار النشط. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت لوحة الضبط التلقائي. |
| override [BackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolor) { get; set; } | الحصول على لون الخلفية أو تعيينه. |
| [BackgroundColorIndex](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolorindex) { get; set; } | الحصول على فهرس لون الخلفية أو تعيينه. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | الحصول على عدد بتات الصورة لكل بكسل . |
| [Blocks](../../aspose.imaging.fileformats.gif/gifimage/blocks) { get; } | يحصل على كتل GIF . |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | يحصل على حدود الصورة . |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [Container](../../aspose.imaging/image/container) { get; } | يحصل على ملف[`Image`](../../aspose.imaging/image) حاوية . |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | يحصل على دفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| override [FileFormat](../../aspose.imaging.fileformats.gif/gifimage/fileformat) { get; } | يحصل على قيمة تنسيق الملف |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على alpha. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/hasbackgroundcolor) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| [HasTrailer](../../aspose.imaging.fileformats.gif/gifimage/hastrailer) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع دعائي . |
| override [HasTransparentColor](../../aspose.imaging.fileformats.gif/gifimage/hastransparentcolor) { get; set; } | يحصل على قيمة تشير إلى ما إذا كان الإطار النشط له لون شفاف. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | الحصول على ارتفاع الصورة . |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | الحصول على أو تعيين الدقة الأفقية ، بالبكسل في البوصة ، لهذا[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging.fileformats.gif/gifimage/imageopacity) { get; } | الحصول على عتامة هذه الصورة (الإطار النشط) . |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | الحصول على أو تعيين شاشة المقاطعة. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsInterlaced](../../aspose.imaging.fileformats.gif/gifimage/isinterlaced) { get; } | يحصل على قيمة تشير إلى ما إذا كان مثيل الصورة هذا متشابكًا. |
| [IsPaletteSorted](../../aspose.imaging.fileformats.gif/gifimage/ispalettesorted) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت اللوحة مرتبة أم لا. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الأولية متاحًا. |
| [LoopsCount](../../aspose.imaging.fileformats.gif/gifimage/loopscount) { get; set; } | الحصول على عدد الحلقات (إذا كانت صورة gif تحتوي على معلومات حول الحلقات) |
| override [PageCount](../../aspose.imaging.fileformats.gif/gifimage/pagecount) { get; } | الحصول على عدد الصفحات . |
| override [PageExportingAction](../../aspose.imaging.fileformats.gif/gifimage/pageexportingaction) { get; set; } | الحصول على إجراء تصدير الصفحة أو تعيينه . يرجى ملاحظة أن تعيين هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها قبل حفظ كل صفحة مباشرةً. |
| override [Pages](../../aspose.imaging.fileformats.gif/gifimage/pages) { get; } | الحصول على الصفحات . |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها. لا يتم استخدام لوحة الألوان عندما يتم تمثيل وحدات البكسل مباشرةً. |
| [PaletteColorResolutionBits](../../aspose.imaging.fileformats.gif/gifimage/palettecolorresolutionbits) { get; set; } | الحصول على بتات دقة ألوان اللوحة أو تعيينها. |
| [PixelAspectRatio](../../aspose.imaging.fileformats.gif/gifimage/pixelaspectratio) { get; set; } | الحصول على أو تعيين نسبة العرض إلى الارتفاع بالبكسل. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب مضاعفة مكونات الصورة مسبقًا. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | الحصول على أو تعيين محول الألوان المخصص |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | يحصل على تنسيق البيانات الأولية. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | يحصل على إعدادات البيانات الأولية الحالية. ملاحظة عند استخدام هذه الإعدادات ، يتم تحميل البيانات بدون تحويل. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | الحصول على الفهرس الاحتياطي أو تعيينه لاستخدامه عندما يكون فهرس اللوحة خارج الحدود |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | الحصول على أو تعيين محول الألوان المفهرس |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | الحصول على حجم الخط الخام بالبايت. |
| [Size](../../aspose.imaging/image/size) { get; } | يحصل على حجم الصورة . |
| override [TransparentColor](../../aspose.imaging.fileformats.gif/gifimage/transparentcolor) { get; } | الحصول على لون شفاف للإطار النشط. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان سيتم تحديث بيانات تعريف XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة الصور مستخدمة. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان سيتم استخدام تحميل البيانات الأولية عند توفر تحميل البيانات الأولية. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | الحصول على أو تحديد الدقة الرأسية ، بالبكسل في البوصة ، لهذا[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | الحصول على عرض الصورة . |
| override [XmpData](../../aspose.imaging.fileformats.gif/gifimage/xmpdata) { get; set; } | الحصول على بيانات تعريف XMP أو تعيينها. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.gif/gifimage/addblock)(IGifBlock) | يضيف كتلة GIF جديدة. |
| [AddPage](../../aspose.imaging.fileformats.gif/gifimage/addpage)(RasterImage) | يضيف صفحة للصورة. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.gif/gifimage/adjustbrightness)(int) | ضبط أ*brightness* للصورة . |
| override [AdjustContrast](../../aspose.imaging.fileformats.gif/gifimage/adjustcontrast)(float) | يضبط التباين . |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma#adjustgamma)(float) | تصحيح جاما لصورة . |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma#adjustgamma_1)(float, float, float) | تصحيح جاما لصورة . |
| override [BinarizeBradley](../../aspose.imaging.fileformats.gif/gifimage/binarizebradley#binarizebradley)(double) | ثنائية الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double, int) | ثنائية الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeFixed](../../aspose.imaging.fileformats.gif/gifimage/binarizefixed)(byte) | ثنائية الصورة مع عتبة محددة مسبقًا |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.gif/gifimage/binarizeotsu)() | ثنائية الصورة مع عتبة Otsu |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | تخزين البيانات الخاصة. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بتنسيق الملف المحدد الذي تم تمثيله بواسطة خيارات الحفظ التي تم تمريرها. |
| [ClearBlocks](../../aspose.imaging.fileformats.gif/gifimage/clearblocks)() | يمسح كل كتل GIF . |
| override [Crop](../../aspose.imaging.fileformats.gif/gifimage/crop#crop)(Rectangle) | اقتصاص الصورة . |
| override [Crop](../../aspose.imaging/rastercachedmultipageimage/crop)(int, int, int, int) | اقتصاص الصورة مع التحولات . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | يقوم بالتردد على الصورة الحالية. |
| override [Dither](../../aspose.imaging.fileformats.gif/gifimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | يقوم بالتردد على الصورة الحالية. |
| override [Filter](../../aspose.imaging.fileformats.gif/gifimage/filter)(Rectangle, FilterOptionsBase) | يقوم بتصفية المستطيل المحدد . |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | الحصول على صورة ARGB بكسل 32 بت . |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | الحصول على صفيف ARGB بكسل الافتراضي 32 بت. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | يحصل على الخيارات الافتراضية . |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | الحصول على مصفوفة البكسل الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الأولية الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | الحصول على مصفوفة البيانات الأولية الافتراضية باستخدام محمل البكسل الجزئي. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | الحصول على تاريخ ووقت آخر تعديل لصورة المورد. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.gif/gifimage/getoriginaloptions)() | الحصول على الخيارات بناءً على إعدادات الملف الأصلية. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت والمعلمات الأخرى للصورة الأصلية دون تغيير . على سبيل المثال ، إذا قمنا بتحميل صورة PNG أبيض وأسود مع 1 بت لكل بكسل ثم احفظه باستخدام the [`Save`](../../aspose.imaging/datastreamsupporter/save) الطريقة ، سيتم إنتاج صورة PNG الناتجة بمعدل 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بمعدل 1 بت لكل بكسل ، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى[`Save`](../../aspose.imaging/image/save) الطريقة كمعامل ثاني. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | الحصول على بكسل صورة . |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | الحصول على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا ، لتحديد زاوية الانحراف عند المسح. |
| override [Grayscale](../../aspose.imaging.fileformats.gif/gifimage/grayscale)() | تحويل الصورة إلى تمثيلها بالتدرج الرمادي |
| [InsertBlock](../../aspose.imaging.fileformats.gif/gifimage/insertblock)(int, IGifBlock) | يضيف كتلة GIF جديدة. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | تحميل 32 بت ARGB بكسل . |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | تحميل 64 بت ARGB بكسل . |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | تحميل وحدات البكسل بتنسيق CMYK . |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | تحميل 32 بت ARGB بكسل جزئيًا بواسطة الحزم. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | يتم تحميل وحدات البكسل جزئيًا بالحزم . |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | تحميل بكسل . |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | تحميل البيانات الأولية . |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | تحميل البيانات الأولية . |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | تطبيع الزاوية. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من المسح المنحرف. تستخدم هذه الطريقة[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) و[`Rotate`](../../aspose.imaging/rasterimage/rotate) الطرق . |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle)(bool, Color) | تطبيع الزاوية. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من المسح المنحرف. تستخدم هذه الطريقة!:GetSkewAngle و[`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate) الطرق . |
| [OrderBlocks](../../aspose.imaging.fileformats.gif/gifimage/orderblocks)() | طلب كتل GIF وفقًا لمواصفات GIF. بعض[`GifGraphicsControlBlock`](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) قد تتم إزالتها لتخطيط GIF المناسب. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | يقرأ خط المسح بالكامل بواسطة فهرس خط المسح المحدد. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | يقرأ خط المسح بالكامل بواسطة فهرس خط المسح المحدد. |
| [RemoveBlock](../../aspose.imaging.fileformats.gif/gifimage/removeblock)(IGifBlock) | يزيل كتلة GIF . |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | يستبدل لونًا بآخر بالاختلاف المسموح به ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف المتجانسة. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | يستبدل لونًا بآخر بالاختلاف المسموح به ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف المتجانسة. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | يستبدل كل الألوان غير الشفافة بلون جديد ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف الناعمة . ملاحظة: إذا كنت تستخدمها على صور بدون شفافية ، فسيتم استبدال كل الألوان بواحد. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | يستبدل كل الألوان غير الشفافة بلون جديد ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف الناعمة . ملاحظة: إذا كنت تستخدمها على صور بدون شفافية ، فسيتم استبدال كل الألوان بأخرى. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | يغير حجم الصورة. الافتراضيNearestNeighbourResample يستخدم . |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize#resize_1)(int, int, ImageResizeSettings) | يغير حجم الصورة. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize#resize_2)(int, int, ResizeType) | يغير حجم الصورة. |
| [ResizeFullFrame](../../aspose.imaging.fileformats.gif/gifimage/resizefullframe)(int, int, ResizeType) | يغير حجم الصورة باستخدام الإطارات الكاملة لكل صفحة GIF. مطلوب لتجنب ظهور القطع الأثرية المحتملة. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | يغير حجم الارتفاع بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | يغير حجم الارتفاع بشكل متناسب . |
| override [ResizeHeightProportionally](../../aspose.imaging/rastercachedmultipageimage/resizeheightproportionally)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| [ResizeProportional](../../aspose.imaging.fileformats.gif/gifimage/resizeproportional)(int, int, ResizeType) | يؤدي تغيير الحجم النسبي على الصورة. سيؤدي تغيير الحجم النسبي إلى تغيير حجم كل إطار وفقًا لنسبة*newWidth* العرض و*newHeight* / ارتفاع . |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | يغير حجم العرض بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | يغير حجم العرض بشكل متناسب . |
| override [ResizeWidthProportionally](../../aspose.imaging/rastercachedmultipageimage/resizewidthproportionally)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | تدوير الصورة حول المركز . |
| override [Rotate](../../aspose.imaging.fileformats.gif/gifimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate الصورة حول المركز . |
| override [RotateFlip](../../aspose.imaging.fileformats.gif/gifimage/rotateflip)(RotateFlipType) | يقوم بتدوير الإطار النشط فقط أو قلبه أو تدويره وقلبه. |
| [Save](../../aspose.imaging/image/save)() | يحفظ بيانات الصورة في التدفق الأساسي. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | يحفظ بيانات الكائن في الدفق المحدد. |
| override [Save](../../aspose.imaging/image/save)(string) | يحفظ الصورة في موقع الملف المحدد. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | يحفظ بيانات الكائن في موقع الملف المحدد. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| override [Save](../../aspose.imaging/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | يحفظ 32 بت ARGB بكسل . |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | يحفظ البكسل . |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | يحفظ البكسل . |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | يحفظ البيانات الأولية . |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | يضبط صورة ARGB بكسل 32 بت للوضع المحدد. |
| [SetFrameTime](../../aspose.imaging.fileformats.gif/gifimage/setframetime)(ushort) | يضبط مدة كل الإطارات بالمللي ثانية. سيؤدي تغيير هذه القيمة إلى إعادة تعيين التأخير لجميع الإطارات . |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | يضبط لوحة الصور . |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | يضبط بكسل الصورة للوضع المحدد. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | يضبط الدقة لهذا الغرض[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | تحويل الصورة النقطية إلى الصورة النقطية. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | يكتب خط المسح بالكامل إلى فهرس خط المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | يكتب خط المسح بالكامل إلى فهرس خط المسح المحدد. |

### أمثلة

تصدير جزء من الرسوم المتحركة من صورة GIF بناءً على الفاصل الزمني.

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

يوضح هذا المثال كيفية إنشاء صورة GIF وحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بإنشاء كتلة إطار GIF بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // املأ الكتلة بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

قم بإنشاء صورة GIF متعددة الصفحات باستخدام صور نقطية من صفحة واحدة.

```csharp
[C#]

static void Main(string[] args)
{
    // تحميل الإطارات
    var frames = LoadFrames("Animation frames").ToArray();

    // إنشاء صورة GIF باستخدام الإطار الأول
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // أضف إطارات إلى صورة GIF باستخدام طريقة AddPage
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // حفظ صورة GIF
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### أنظر أيضا

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
