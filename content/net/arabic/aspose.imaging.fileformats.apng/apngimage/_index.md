---
title: ApngImage
second_title: Aspose.Imaging لمرجع NET API
description: صورة PNG المتحركة .
type: docs
weight: 1320
url: /ar/aspose.imaging.fileformats.apng/apngimage/
---
## ApngImage class

صورة PNG المتحركة .

```csharp
public sealed class ApngImage : RasterCachedMultipageImage, IMultipageImageExt
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ApngImage](apngimage)(ApngOptions, int, int) | يقوم بتهيئة مثيل جديد لملف[`ApngImage`](../apngimage) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت لوحة الضبط التلقائي. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية . |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | الحصول على عدد بتات الصورة لكل بكسل . |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | يحصل على حدود الصورة . |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [Container](../../aspose.imaging/image/container) { get; } | يحصل على ملف[`Image`](../../aspose.imaging/image) حاوية . |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | يحصل على دفق بيانات الكائن. |
| [DefaultFrameTime](../../aspose.imaging.fileformats.apng/apngimage/defaultframetime) { get; set; } | الحصول على أو تعيين مدة الإطار الافتراضية . يُستخدم عند إنشاء إطارات جديدة . |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| override [FileFormat](../../aspose.imaging.fileformats.apng/apngimage/fileformat) { get; } | يحصل على قيمة تنسيق الملف |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على alpha. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | يحصل على قيمة تشير إلى ما إذا كانت الصورة ذات لون شفاف. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | الحصول على ارتفاع الصورة . |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | الحصول على أو تعيين الدقة الأفقية ، بالبكسل في البوصة ، لهذا[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | يحصل على عتامة هذه الصورة . |
| [Interlaced](../../aspose.imaging.fileformats.apng/apngimage/interlaced) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا[`PngImage`](../../aspose.imaging.fileformats.png/pngimage) متشابك. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | الحصول على أو تعيين شاشة المقاطعة. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الأولية متاحًا. |
| [NumPlays](../../aspose.imaging.fileformats.apng/apngimage/numplays) { get; set; } | الحصول على أو تعيين عدد مرات تكرار الرسوم المتحركة. 0 يشير إلى التكرار اللانهائي. |
| override [PageCount](../../aspose.imaging.fileformats.apng/apngimage/pagecount) { get; } | الحصول على عدد الصفحات . |
| override [PageExportingAction](../../aspose.imaging.fileformats.apng/apngimage/pageexportingaction) { get; set; } | الحصول على إجراء تصدير الصفحة أو تعيينه . يرجى ملاحظة أن تعيين هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها قبل حفظ كل صفحة مباشرةً. |
| override [Pages](../../aspose.imaging.fileformats.apng/apngimage/pages) { get; } | الحصول على الصفحات . |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها. لا يتم استخدام لوحة الألوان عندما يتم تمثيل وحدات البكسل مباشرةً. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب مضاعفة مكونات الصورة مسبقًا. |
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
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | الحصول على أو تحديد الدقة الرأسية ، بالبكسل في البوصة ، لهذا[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | الحصول على عرض الصورة . |
| override [XmpData](../../aspose.imaging.fileformats.apng/apngimage/xmpdata) { get; set; } | الحصول على بيانات تعريف XMP أو تعيينها. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe)() | يضيف إطارًا جديدًا إلى نهاية مجموعة الإطارات الخاصة . سيتم إنشاء إطار جديد وفقًا لحجم الصورة الحالية. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe_1)(RasterImage) | يضيف إطارًا جديدًا إلى نهاية مجموعة الإطارات الخاصة . سيتم ملء محتويات الإطار الجديد من الصورة المحددة. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe_2)(RasterImage, uint) | يضيف إطارًا جديدًا إلى نهاية مجموعة الإطارات الخاصة . سيتم ملء محتويات الإطار الجديد من الصورة المحددة. |
| [AddPage](../../aspose.imaging.fileformats.apng/apngimage/addpage)(RasterImage) | يضيف صفحة للصورة. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.apng/apngimage/adjustbrightness)(int) | ضبط أ*brightness* للصورة . |
| override [AdjustContrast](../../aspose.imaging.fileformats.apng/apngimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) التباين |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma#adjustgamma)(float) | تصحيح جاما لصورة . |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma#adjustgamma_1)(float, float, float) | تصحيح جاما لصورة . |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | ثنائية الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeBradley](../../aspose.imaging.fileformats.apng/apngimage/binarizebradley#binarizebradley_1)(double, int) | ثنائية الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeFixed](../../aspose.imaging.fileformats.apng/apngimage/binarizefixed)(byte) | ثنائية الصورة مع عتبة محددة مسبقًا |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.apng/apngimage/binarizeotsu)() | ثنائية الصورة مع عتبة Otsu |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | تخزين البيانات الخاصة. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بتنسيق الملف المحدد الذي تم تمثيله بواسطة خيارات الحفظ التي تم تمريرها. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop#crop)(Rectangle) | اقتصاص الصورة . |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop#crop_1)(int, int, int, int) | اقتصاص الصورة مع التحولات . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | يقوم بالتردد على الصورة الحالية. |
| override [Dither](../../aspose.imaging.fileformats.apng/apngimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | يقوم بالتردد على الصورة الحالية. |
| override [Filter](../../aspose.imaging.fileformats.apng/apngimage/filter)(Rectangle, FilterOptionsBase) | يقوم بتصفية المستطيل المحدد . |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | الحصول على صورة ARGB بكسل 32 بت . |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | الحصول على صفيف ARGB بكسل الافتراضي 32 بت. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.apng/apngimage/getdefaultoptions)(object[]) | يحصل على الخيارات الافتراضية . |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | الحصول على مصفوفة البكسل الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الأولية الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | الحصول على مصفوفة البيانات الأولية الافتراضية باستخدام محمل البكسل الجزئي. |
| override [GetModifyDate](../../aspose.imaging.fileformats.apng/apngimage/getmodifydate)(bool) | الحصول على تاريخ ووقت آخر تعديل لصورة المورد. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.apng/apngimage/getoriginaloptions)() | الحصول على الخيارات بناءً على إعدادات الملف الأصلية. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت والمعلمات الأخرى للصورة الأصلية دون تغيير . على سبيل المثال ، إذا قمنا بتحميل صورة PNG أبيض وأسود مع 1 بت لكل بكسل ثم احفظه باستخدام the [`Save`](../../aspose.imaging/datastreamsupporter/save) الطريقة ، سيتم إنتاج صورة PNG الناتجة بمعدل 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بمعدل 1 بت لكل بكسل ، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى[`Save`](../../aspose.imaging/image/save) الطريقة كمعامل ثاني. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | الحصول على بكسل صورة . |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | الحصول على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا ، لتحديد زاوية الانحراف عند المسح. |
| override [Grayscale](../../aspose.imaging.fileformats.apng/apngimage/grayscale)() | تحويل الصورة إلى تمثيلها بالتدرج الرمادي |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe)(int) | إدراج إطار جديد في مجموعة الإطارات الخاصة في الفهرس المحدد . سيتم إنشاء إطار جديد وفقًا لحجم الصورة الحالية. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe_1)(int, RasterImage) | إدراج إطار جديد في مجموعة الإطارات الخاصة في الفهرس المحدد. سيتم ملء محتويات الإطار الجديد من الصورة المحددة. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe_2)(int, RasterImage, uint) | إدراج إطار جديد في مجموعة الإطارات الخاصة في الفهرس المحدد. سيتم ملء محتويات الإطار الجديد من الصورة المحددة. |
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
| [PopFrameAt](../../aspose.imaging.fileformats.apng/apngimage/popframeat)(int) | يزيل ويعيد الإطار بالفهرس المحدد لمجموعة الإطارات الخاصة. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | يقرأ خط المسح بالكامل بواسطة فهرس خط المسح المحدد. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | يقرأ خط المسح بالكامل بواسطة فهرس خط المسح المحدد. |
| [RemoveAllFrames](../../aspose.imaging.fileformats.apng/apngimage/removeallframes)() | يزيل كل الإطارات من مجموعة الإطارات الخاصة . |
| [RemoveFrameAt](../../aspose.imaging.fileformats.apng/apngimage/removeframeat)(int) | يزيل الإطار في الفهرس المحدد لمجموعة الإطارات الخاصة . سيتم التخلص من الإطار المراد حذفه . |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | يستبدل لونًا بآخر بالاختلاف المسموح به ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف المتجانسة. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | يستبدل لونًا بآخر بالاختلاف المسموح به ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف المتجانسة. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | يستبدل كل الألوان غير الشفافة بلون جديد ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف الناعمة . ملاحظة: إذا كنت تستخدمها على صور بدون شفافية ، فسيتم استبدال كل الألوان بواحد. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | يستبدل كل الألوان غير الشفافة بلون جديد ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف الناعمة . ملاحظة: إذا كنت تستخدمها على صور بدون شفافية ، فسيتم استبدال كل الألوان بأخرى. |
| [ResetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/resetdefaultimage)() | حذف صورة افتراضية تم تعيينها مسبقًا . بعد ذلك ، تكون الصورة الافتراضية هي الإطار الأول في مجموعة الإطارات الخاصة (لا يمكن حذفها باستخدام هذه الطريقة) . |
| [Resize](../../aspose.imaging/image/resize)(int, int) | يغير حجم الصورة. الافتراضيNearestNeighbourResample يستخدم . |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize#resize_1)(int, int, ImageResizeSettings) | يغير حجم الصورة. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize#resize_2)(int, int, ResizeType) | يغير حجم الصورة. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | يغير حجم الارتفاع بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | يغير حجم الارتفاع بشكل متناسب . |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | يغير حجم العرض بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | يغير حجم العرض بشكل متناسب . |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | تدوير الصورة حول المركز . |
| override [Rotate](../../aspose.imaging.fileformats.apng/apngimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate الصورة حول المركز . |
| override [RotateFlip](../../aspose.imaging.fileformats.apng/apngimage/rotateflip)(RotateFlipType) | يقوم بتدوير الإطار النشط فقط أو قلبه أو تدويره وقلبه. |
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
| [SetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/setdefaultimage)(RasterImage) | يضبط الصورة النقطية المحددة كصورة افتراضية للرسوم المتحركة الحالية. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | يضبط لوحة الصور . |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | يضبط بكسل الصورة للوضع المحدد. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | يضبط الدقة لهذا الغرض[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | تحويل الصورة النقطية إلى الصورة النقطية. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | يكتب خط المسح بالكامل إلى فهرس خط المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | يكتب خط المسح بالكامل إلى فهرس خط المسح المحدد. |

### أمثلة

يوضح المثال التالي كيفية تصدير تنسيق ملف APNG من تنسيق آخر متعدد الصفحات غير متحرك.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // إعداد مدة الإطار الافتراضية
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 مللي ثانية
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 مللي ثانية
}
```

يوضح المثال التالي كيفية التصدير إلى تنسيق ملف APNG.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // تصدير إلى رسوم متحركة APNG مع دورات رسوم متحركة غير محدودة كإعداد افتراضي
    image.Save("Animation1.webp.png", new ApngOptions());
    // إعداد دورات الرسوم المتحركة
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 دورات
}
```

يوضح المثال التالي كيفية إنشاء صورة APNG من صورة نقطية أخرى أحادية الصفحة.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 ثانية
const int FrameDuration = 70; // 70 مللي ثانية
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // من الممكن ضبط وقت الإطار الافتراضي للصورة هناك: apngImage.DefaultFrameTime = (uint) FrameDuration ;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // التنظيف لأن الصورة تحتوي على إطار واحد افتراضيًا
        apngImage.RemoveAllFrames();

        // إضافة الإطار الأول
        apngImage.AddFrame(sourceImage);

        // إضافة إطارات وسيطة
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // إضافة الإطار الأخير
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### أنظر أيضا

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* مساحة الاسم [Aspose.Imaging.FileFormats.Apng](../../aspose.imaging.fileformats.apng)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
