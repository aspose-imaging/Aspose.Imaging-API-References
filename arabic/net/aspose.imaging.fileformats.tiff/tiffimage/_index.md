---
title: TiffImage
second_title: Aspose.Imaging لمرجع NET API
description: الصورة المشاجرة .
type: docs
weight: 7880
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/
---
## TiffImage class

الصورة المشاجرة .

```csharp
public sealed class TiffImage : RasterCachedMultipageImage, IMultipageImageExt
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TiffImage](tiffimage#constructor)(TiffFrame) | يقوم بتهيئة مثيل جديد لملف[`TiffImage`](../tiffimage) فئة . |
| [TiffImage](tiffimage#constructor_1)(TiffFrame[]) | يقوم بتهيئة مثيل جديد لملف[`TiffImage`](../tiffimage) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/activeframe) { get; set; } | الحصول على أو تحديد الإطار النشط. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت لوحة الضبط التلقائي. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية . |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | الحصول على عدد بتات الصورة لكل بكسل . |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | يحصل على حدود الصورة . |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [ByteOrder](../../aspose.imaging.fileformats.tiff/tiffimage/byteorder) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ترتيب tiff بايت. |
| [Container](../../aspose.imaging/image/container) { get; } | يحصل على ملف[`Image`](../../aspose.imaging/image) حاوية . |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | يحصل على دفق بيانات الكائن. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [ExifData](../../aspose.imaging.fileformats.tiff/tiffimage/exifdata) { get; set; } | الحصول على أو تعيين بيانات EXIF للإطار النشط. |
| override [FileFormat](../../aspose.imaging.fileformats.tiff/tiffimage/fileformat) { get; } | يحصل على قيمة تنسيق الملف |
| [Frames](../../aspose.imaging.fileformats.tiff/tiffimage/frames) { get; } | يحصل على مجموعة إطارات للصورة. |
| override [HasAlpha](../../aspose.imaging.fileformats.tiff/tiffimage/hasalpha) { get; } | يحصل على قناة ألفا . |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الصورة ذات لون شفاف. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | الحصول على ارتفاع الصورة . |
| override [HorizontalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/horizontalresolution) { get; set; } | الحصول على الدقة الأفقية ، بالبكسل في البوصة ، لهذا[`Image`](../../aspose.imaging/image) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | يحصل على عتامة هذه الصورة . |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | الحصول على أو تعيين شاشة المقاطعة. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الأولية متاحًا. |
| override [PageCount](../../aspose.imaging.fileformats.tiff/tiffimage/pagecount) { get; } | الحصول على عدد الصفحات . |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction) { get; set; } | الحصول على إجراء تصدير الصفحة أو تعيينه . يرجى ملاحظة أن تعيين هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها قبل حفظ كل صفحة مباشرةً. |
| override [Pages](../../aspose.imaging.fileformats.tiff/tiffimage/pages) { get; } | الحصول على الصفحات . |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها. لا يتم استخدام لوحة الألوان عندما يتم تمثيل وحدات البكسل مباشرةً. |
| override [PremultiplyComponents](../../aspose.imaging.fileformats.tiff/tiffimage/premultiplycomponents) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب مضاعفة المكونات مسبقًا. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | الحصول على أو تعيين محول الألوان المخصص |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | يحصل على تنسيق البيانات الأولية. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | يحصل على إعدادات البيانات الأولية الحالية. ملاحظة عند استخدام هذه الإعدادات ، يتم تحميل البيانات بدون تحويل. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | الحصول على الفهرس الاحتياطي أو تعيينه لاستخدامه عندما يكون فهرس اللوحة خارج الحدود |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | الحصول على أو تعيين محول الألوان المفهرس |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | الحصول على حجم الخط الخام بالبايت. |
| [Size](../../aspose.imaging/image/size) { get; } | يحصل على حجم الصورة . |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | الحصول على لون شفاف للصورة . |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان سيتم تحديث بيانات تعريف XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة الصور مستخدمة. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان سيتم استخدام تحميل البيانات الأولية عند توفر تحميل البيانات الأولية. |
| override [VerticalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/verticalresolution) { get; set; } | الحصول على الدقة الرأسية ، بالبكسل في البوصة ، لهذا[`Image`](../../aspose.imaging/image) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | الحصول على عرض الصورة . |
| override [XmpData](../../aspose.imaging/rastercachedmultipageimage/xmpdata) { get; set; } | الحصول على أو تعيين بيانات XMP من الإطار . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Add](../../aspose.imaging.fileformats.tiff/tiffimage/add)(TiffImage) | يضيف إطارات الصور المحددة إلى الإطار الحالي. |
| [AddFrame](../../aspose.imaging.fileformats.tiff/tiffimage/addframe)(TiffFrame) | يضيف الإطار إلى image |
| [AddFrames](../../aspose.imaging.fileformats.tiff/tiffimage/addframes)(TiffFrame[]) | يضيف مجموعة الإطارات إلى image |
| [AddPage](../../aspose.imaging.fileformats.tiff/tiffimage/addpage)(RasterImage) | يضيف صفحة للصورة. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.tiff/tiffimage/adjustbrightness)(int) | ضبط أ*brightness* للصورة . |
| override [AdjustContrast](../../aspose.imaging.fileformats.tiff/tiffimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) التباين |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma#adjustgamma)(float) | تصحيح جاما لصورة . |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma#adjustgamma_1)(float, float, float) | تصحيح جاما لصورة . |
| [AlignResolutions](../../aspose.imaging.fileformats.tiff/tiffimage/alignresolutions)() | طريقة مساعدة لجعل الدقة الأفقية والعمودية متساوية. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | ثنائية الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeBradley](../../aspose.imaging.fileformats.tiff/tiffimage/binarizebradley#binarizebradley_1)(double, int) | ثنائية الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeFixed](../../aspose.imaging.fileformats.tiff/tiffimage/binarizefixed)(byte) | ثنائية الصورة مع عتبة محددة مسبقًا |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu)() | ثنائية الصورة مع عتبة Otsu |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | تخزين البيانات الخاصة. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بتنسيق الملف المحدد الذي تم تمثيله بواسطة خيارات الحفظ التي تم تمريرها. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop#crop)(Rectangle) | اقتصاص الصورة . |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop#crop_1)(int, int, int, int) | اقتصاص الصورة مع التحولات . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | يقوم بالتردد على الصورة الحالية. |
| override [Dither](../../aspose.imaging.fileformats.tiff/tiffimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | يقوم بالتردد على الصورة الحالية. |
| override [Filter](../../aspose.imaging.fileformats.tiff/tiffimage/filter)(Rectangle, FilterOptionsBase) | يقوم بتصفية المستطيل المحدد . |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | الحصول على صورة ARGB بكسل 32 بت . |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | الحصول على صفيف ARGB بكسل الافتراضي 32 بت. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | يحصل على الخيارات الافتراضية . |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | الحصول على مصفوفة البكسل الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الأولية الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | الحصول على مصفوفة البيانات الأولية الافتراضية باستخدام محمل البكسل الجزئي. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | الحصول على تاريخ ووقت آخر تعديل لصورة المورد. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.tiff/tiffimage/getoriginaloptions)() | الحصول على الخيارات بناءً على إعدادات الملف الأصلية. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت والمعلمات الأخرى للصورة الأصلية دون تغيير . على سبيل المثال ، إذا قمنا بتحميل صورة PNG أبيض وأسود مع 1 بت لكل بكسل ثم احفظه باستخدام the [`Save`](../../aspose.imaging/datastreamsupporter/save) الطريقة ، سيتم إنتاج صورة PNG الناتجة بمعدل 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بمعدل 1 بت لكل بكسل ، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى[`Save`](../../aspose.imaging/image/save) الطريقة كمعامل ثاني. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | الحصول على بكسل صورة . |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | الحصول على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا ، لتحديد زاوية الانحراف عند المسح. |
| override [Grayscale](../../aspose.imaging.fileformats.tiff/tiffimage/grayscale)() | تحويل الصورة إلى تمثيلها بالتدرج الرمادي |
| [InsertFrame](../../aspose.imaging.fileformats.tiff/tiffimage/insertframe)(int, TiffFrame) | إطار الإدخال . |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | تحميل 32 بت ARGB بكسل . |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | تحميل 64 بت ARGB بكسل . |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | تحميل وحدات البكسل بتنسيق CMYK . |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | تحميل 32 بت ARGB بكسل جزئيًا بواسطة الحزم. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | يتم تحميل وحدات البكسل جزئيًا بالحزم . |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | تحميل بكسل . |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | تحميل البيانات الأولية . |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | تحميل البيانات الأولية . |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | تطبيع الزاوية. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من المسح المنحرف. تستخدم هذه الطريقة[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) و[`Rotate`](../../aspose.imaging/rasterimage/rotate) الطرق . |
| override [NormalizeAngle](../../aspose.imaging.fileformats.tiff/tiffimage/normalizeangle#normalizeangle_1)(bool, Color) | تطبيع الزاوية. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من المسح المنحرف. تستخدم هذه الطريقة[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) و[`Rotate`](./rotate) الطرق . |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | يقرأ خط المسح بالكامل بواسطة فهرس خط المسح المحدد. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | يقرأ خط المسح بالكامل بواسطة فهرس خط المسح المحدد. |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe#removeframe)(int) | يزيل الإطار بفهرسه. |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe#removeframe_1)(TiffFrame) | يزيل الإطار المحدد. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | يستبدل لونًا بآخر بالاختلاف المسموح به ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف المتجانسة. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | يستبدل لونًا بآخر بالاختلاف المسموح به ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف المتجانسة. |
| [ReplaceFrame](../../aspose.imaging.fileformats.tiff/tiffimage/replaceframe)(int, TiffFrame) | يستبدل الإطار في الموضع المحدد. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | يستبدل كل الألوان غير الشفافة بلون جديد ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف الناعمة . ملاحظة: إذا كنت تستخدمها على صور بدون شفافية ، فسيتم استبدال كل الألوان بواحد. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | يستبدل كل الألوان غير الشفافة بلون جديد ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف الناعمة . ملاحظة: إذا كنت تستخدمها على صور بدون شفافية ، فسيتم استبدال كل الألوان بأخرى. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | يغير حجم الصورة. الافتراضيNearestNeighbourResample يستخدم . |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize#resize_1)(int, int, ImageResizeSettings) | يغير حجم الصورة. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize#resize_2)(int, int, ResizeType) | يغير حجم الصورة. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | يغير حجم الارتفاع بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | يغير حجم الارتفاع بشكل متناسب . |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| [ResizeProportional](../../aspose.imaging.fileformats.tiff/tiffimage/resizeproportional)(int, int, ResizeType) | يؤدي تغيير الحجم النسبي على الصورة. سيؤدي تغيير الحجم النسبي إلى تغيير حجم كل إطار وفقًا لنسبة*newWidth* العرض و*newHeight* / ارتفاع . |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | يغير حجم العرض بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | يغير حجم العرض بشكل متناسب . |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | تدوير الصورة حول المركز . |
| override [Rotate](../../aspose.imaging.fileformats.tiff/tiffimage/rotate#rotate_1)(float, bool, Color) | تدوير الصورة حول المركز . |
| override [RotateFlip](../../aspose.imaging.fileformats.tiff/tiffimage/rotateflip)(RotateFlipType) | يقوم بتدوير الإطار النشط فقط أو قلبه أو تدويره وقلبه. |
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
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | يضبط لوحة الصور . |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | يضبط بكسل الصورة للوضع المحدد. |
| override [SetResolution](../../aspose.imaging.fileformats.tiff/tiffimage/setresolution)(double, double) | يضبط الدقة لهذا الغرض[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | تحويل الصورة النقطية إلى الصورة النقطية. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | يكتب خط المسح بالكامل إلى فهرس خط المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | يكتب خط المسح بالكامل إلى فهرس خط المسح المحدد. |

### أمثلة

قم بإنشاء مسار رسومي من Path Resources في صورة TIFF.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // أنشئ مسار الرسومات باستخدام PathResources من صورة TIFF
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // ارسم خطًا أحمر واحفظ الصورة
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

إنشاء مسار الموارد باستخدام مسار الرسومات.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // إنشاء شكل مستطيل لـ GraphicsPath
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // إنشاء GraphicsPath باستخدام الشكل الخاص بنا
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // تعيين PathResources باستخدام GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // احفظ الصورة
        image.Save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape CreateBezierShape(params float[] coordinates)
{
    var bezierPoints = CoordinatesToBezierPoints(coordinates).ToArray();
    return new BezierShape(bezierPoints, true);
}

private static IEnumerable<PointF> CoordinatesToBezierPoints(float[] coordinates)
{
    for (var coordinateIndex = 0; coordinateIndex < coordinates.Length; coordinateIndex += 2)
        for (var index = 0; index < 3; index++)
            yield return new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
}
```

### أنظر أيضا

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../aspose.imaging.fileformats.tiff)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
