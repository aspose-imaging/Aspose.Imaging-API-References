---
title: JpegImage
second_title: Aspose.Imaging لمرجع NET API
description: صورة jpeg .
type: docs
weight: 6770
url: /ar/net/aspose.imaging.fileformats.jpeg/jpegimage/
---
## JpegImage class

صورة jpeg .

```csharp
public sealed class JpegImage : RasterCachedImage
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [JpegImage](jpegimage#constructor_1)(RasterImage) | يقوم بتهيئة مثيل جديد لملف[`JpegImage`](../jpegimage) فئة . |
| [JpegImage](jpegimage#constructor_3)(Stream) | يقوم بتهيئة مثيل جديد لملف[`JpegImage`](../jpegimage) فئة . |
| [JpegImage](jpegimage#constructor_4)(string) | يقوم بتهيئة مثيل جديد لملف[`JpegImage`](../jpegimage) فئة . |
| [JpegImage](jpegimage#constructor_2)(int, int) | يقوم بتهيئة مثيل جديد لملف[`JpegImage`](../jpegimage) فئة . |
| [JpegImage](jpegimage#constructor)(JpegOptions, int, int) | يقوم بتهيئة مثيل جديد لملف[`JpegImage`](../jpegimage) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت لوحة الضبط التلقائي. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | الحصول على أو تعيين قيمة للون الخلفية . |
| override [BitsPerPixel](../../aspose.imaging.fileformats.jpeg/jpegimage/bitsperpixel) { get; } | الحصول على عدد بتات الصورة لكل بكسل . |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | يحصل على حدود الصورة . |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | الحصول على أو تعيين تلميح حجم المخزن المؤقت الذي تم تحديده بالحجم الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |
| [CmykColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/cmykcolorprofile) { get; set; } | ملف تعريف الألوان CMYK لصور CMYK و YCCK jpeg. يجب أن يكون مقترنًا بـ RGBColorProfile لتحويل اللون الصحيح. |
| [Comment](../../aspose.imaging.fileformats.jpeg/jpegimage/comment) { get; set; } | الحصول على تعليق ملف jpeg أو تعيينه. |
| [Container](../../aspose.imaging/image/container) { get; } | يحصل على ملف[`Image`](../../aspose.imaging/image) حاوية . |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | يحصل على دفق بيانات الكائن. |
| [DestinationCmykColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/destinationcmykcolorprofile) { get; set; } | ملف تعريف الألوان CMYK لصور CMYK و YCCK jpeg المستخدمة في عملية حفظ الصور. يجب أن يكون مقترنًا بـ RGBColorProfile لتحويل اللون الصحيح. |
| [DestinationRgbColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/destinationrgbcolorprofile) { get; set; } | ملف تعريف الألوان RGB لصور CMYK و YCCK jpeg ، المستخدمة في عملية حفظ الصور. يجب أن يكون في زوج مع CMYKColorProfile لتحويل اللون الصحيح. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [ExifData](../../aspose.imaging.fileformats.jpeg/jpegimage/exifdata) { get; set; } | الحصول على أو تعيين حاوية بيانات exif |
| override [FileFormat](../../aspose.imaging.fileformats.jpeg/jpegimage/fileformat) { get; } | يحصل على قيمة تنسيق الملف |
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على alpha. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الصورة لها لون خلفية. |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor) { get; set; } | يحصل على قيمة تشير إلى ما إذا كانت الصورة ذات لون شفاف. |
| override [Height](../../aspose.imaging.fileformats.jpeg/jpegimage/height) { get; } | الحصول على ارتفاع الصورة . |
| override [HorizontalResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/horizontalresolution) { get; set; } | الحصول على أو تعيين الدقة الأفقية ، بالبكسل في البوصة ، لهذا[`RasterImage`](../../aspose.imaging/rasterimage) . |
| [IgnoreEmbeddedColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/ignoreembeddedcolorprofile) { get; set; } | الحصول على أو تعيين قيمة تشير إلى تجاهل ملف تعريف اللون المضمن. إذا تم تجاهل ملف تعريف اللون المضمّن ، فسيتم استخدام ملف تعريف لون دافولت. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | يحصل على عتامة هذه الصورة . |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | الحصول على أو تعيين شاشة المقاطعة. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | يحصل على قيمة تشير إلى ما إذا كان تحميل البيانات الأولية متاحًا. |
| [Jfif](../../aspose.imaging.fileformats.jpeg/jpegimage/jfif) { get; set; } | الحصول على أو تعيين jfif. |
| [JpegOptions](../../aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions) { get; } | الحصول على خيارات JPEG المستخدمة لإنشاء أو تحميل هذا[`JpegImage`](../jpegimage) المثال. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | الحصول على لوحة الألوان أو تعيينها. لا يتم استخدام لوحة الألوان عندما يتم تمثيل وحدات البكسل مباشرةً. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان يجب مضاعفة مكونات الصورة مسبقًا. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | الحصول على أو تعيين محول الألوان المخصص |
| override [RawDataFormat](../../aspose.imaging.fileformats.jpeg/jpegimage/rawdataformat) { get; } | يحصل على تنسيق البيانات الأولية. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | يحصل على إعدادات البيانات الأولية الحالية. ملاحظة عند استخدام هذه الإعدادات ، يتم تحميل البيانات بدون تحويل. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | الحصول على الفهرس الاحتياطي أو تعيينه لاستخدامه عندما يكون فهرس اللوحة خارج الحدود |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | الحصول على أو تعيين محول الألوان المفهرس |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | الحصول على حجم الخط الخام بالبايت. |
| [RgbColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/rgbcolorprofile) { get; set; } | ملف تعريف الألوان RGB لصور CMYK و YCCK jpeg. يجب أن يكون في زوج مع CMYKColorProfile لتحويل اللون الصحيح. |
| [Size](../../aspose.imaging/image/size) { get; } | يحصل على حجم الصورة . |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | الحصول على لون شفاف للصورة . |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان سيتم تحديث بيانات تعريف XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | يحصل على قيمة تشير إلى ما إذا كانت لوحة الصور مستخدمة. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان سيتم استخدام تحميل البيانات الأولية عند توفر تحميل البيانات الأولية. |
| override [VerticalResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/verticalresolution) { get; set; } | الحصول على أو تحديد الدقة الرأسية ، بالبكسل في البوصة ، لهذا[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging.fileformats.jpeg/jpegimage/width) { get; } | الحصول على عرض الصورة . |
| override [XmpData](../../aspose.imaging.fileformats.jpeg/jpegimage/xmpdata) { get; set; } | الحصول على بيانات تعريف XMP أو تعيينها. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness)(int) | ضبط سطوع الصورة . |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | تباين الصورة |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | تصحيح جاما لصورة . |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | تصحيح جاما لصورة . |
| [AutoRotate](../../aspose.imaging.fileformats.jpeg/jpegimage/autorotate)() | قم بإجراء تدوير تلقائي للصورة بناءً على بيانات الاتجاه المقدمة من Exif. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double) | ثنائية الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double, int) | ثنائية الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي باستخدام عتبة الصورة المتكاملة |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed)(byte) | ثنائية الصورة مع عتبة محددة مسبقًا |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu)() | ثنائية الصورة مع عتبة Otsu |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata)() | يخزن البيانات ويضمن عدم إجراء أي تحميل إضافي للبيانات من الأساس[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | يحدد ما إذا كان يمكن حفظ الصورة بتنسيق الملف المحدد الذي تم تمثيله بواسطة خيارات الحفظ التي تم تمريرها. |
| override [Crop](../../aspose.imaging/rastercachedimage/crop)(Rectangle) | اقتصاص الصورة . |
| virtual [Crop](../../aspose.imaging/rasterimage/crop)(int, int, int, int) | اقتصاص الصورة مع التحولات . |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | التخلص من المثيل الحالي . |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | يقوم بالتردد على الصورة الحالية. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | يقوم بالتردد على الصورة الحالية. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | يقوم بتصفية المستطيل المحدد . |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | الحصول على صورة ARGB بكسل 32 بت . |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | الحصول على صفيف ARGB بكسل الافتراضي 32 بت. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | يحصل على الخيارات الافتراضية . |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | الحصول على مصفوفة البكسل الافتراضية باستخدام محمل البكسل الجزئي. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | يحصل على مصفوفة البيانات الأولية الافتراضية. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | الحصول على مصفوفة البيانات الأولية الافتراضية باستخدام محمل البكسل الجزئي. |
| override [GetModifyDate](../../aspose.imaging.fileformats.jpeg/jpegimage/getmodifydate)(bool) | الحصول على تاريخ ووقت آخر تعديل لصورة المورد. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | الحصول على الخيارات بناءً على إعدادات الملف الأصلية. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت والمعلمات الأخرى للصورة الأصلية دون تغيير . على سبيل المثال ، إذا قمنا بتحميل صورة PNG أبيض وأسود مع 1 بت لكل بكسل ثم احفظه باستخدام the [`Save`](../../aspose.imaging/datastreamsupporter/save) الطريقة ، سيتم إنتاج صورة PNG الناتجة بمعدل 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بمعدل 1 بت لكل بكسل ، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة وتمريرها إلى[`Save`](../../aspose.imaging/image/save) الطريقة كمعامل ثاني. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | الحصول على بكسل صورة . |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | الحصول على زاوية الانحراف. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا ، لتحديد زاوية الانحراف عند المسح. |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale)() | تحويل الصورة إلى تمثيلها بالتدرج الرمادي |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | تحميل 32 بت ARGB بكسل . |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | تحميل 64 بت ARGB بكسل . |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | تحميل وحدات البكسل بتنسيق CMYK . |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | تحميل 32 بت ARGB بكسل جزئيًا بواسطة الحزم. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | يتم تحميل وحدات البكسل جزئيًا بالحزم . |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | تحميل بكسل . |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | تحميل البيانات الأولية . |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | تحميل البيانات الأولية . |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | تطبيع الزاوية. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من المسح المنحرف. تستخدم هذه الطريقة[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) و[`Rotate`](../../aspose.imaging/rasterimage/rotate) الطرق . |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)(bool, Color) | تطبيع الزاوية. هذه الطريقة قابلة للتطبيق على المستندات النصية الممسوحة ضوئيًا للتخلص من المسح المنحرف. تستخدم هذه الطريقة[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) و[`Rotate`](../../aspose.imaging/rasterimage/rotate) الطرق . |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | يقرأ خط المسح بالكامل بواسطة فهرس خط المسح المحدد. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | يقرأ خط المسح بالكامل بواسطة فهرس خط المسح المحدد. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | يستبدل لونًا بآخر بالاختلاف المسموح به ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف المتجانسة. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(int, byte, int) | يستبدل لونًا بآخر بالاختلاف المسموح به ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف المتجانسة. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | يستبدل كل الألوان غير الشفافة بلون جديد ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف الناعمة . ملاحظة: إذا كنت تستخدمها على صور بدون شفافية ، فسيتم استبدال كل الألوان بواحد. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(int) | يستبدل كل الألوان غير الشفافة بلون جديد ويحتفظ بقيمة ألفا الأصلية لحفظ الحواف الناعمة . ملاحظة: إذا كنت تستخدمها على صور بدون شفافية ، فسيتم استبدال كل الألوان بواحد. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | يغير حجم الصورة. الافتراضيNearestNeighbourResample يستخدم . |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ImageResizeSettings) | يغير حجم الصورة. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ResizeType) | يغير حجم الصورة. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | يغير حجم الارتفاع بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | يغير حجم الارتفاع بشكل متناسب . |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | يغير حجم الارتفاع بشكل متناسب . |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | يغير حجم العرض بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم . |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | يغير حجم العرض بشكل متناسب . |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | يغير حجم العرض بشكل متناسب . |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | تدوير الصورة حول المركز . |
| override [Rotate](../../aspose.imaging/rastercachedimage/rotate)(float, bool, Color) | تدوير الصورة حول المركز . |
| override [RotateFlip](../../aspose.imaging/rastercachedimage/rotateflip)(RotateFlipType) | يقوم بتدوير الصورة أو قلبها أو تدويرها وقلبها. |
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
| override [SetResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/setresolution)(double, double) | يضبط الدقة لهذا الغرض[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | تحويل الصورة النقطية إلى الصورة النقطية. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | يكتب خط المسح بالكامل إلى فهرس خط المسح المحدد. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | يكتب خط المسح بالكامل إلى فهرس خط المسح المحدد. |

### أمثلة

الوصول إلى ملاحظات صانع الكاميرا في صورة Jpeg.

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

يوضح المثال كيفية تحميل JpegImage من ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بتحميل صورة JPEG من ملف.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // قم ببعض معالجة الصور.
    // حفظ في ملف JPEG آخر.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### أنظر أيضا

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg](../../aspose.imaging.fileformats.jpeg)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
