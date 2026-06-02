---
title: "GifImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "توفر واجهة برمجة التطبيقات (API) لتنسيق تبادل الرسومات GIF أدوات متعددة للمطورين لمعالجة الصور النقطية المضغوطة وصور GIF المتحركة."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.gif/gifimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifImage extends RasterCachedMultipageImage implements IMultipageImageExt, IInterlaced
```

توفر واجهة برمجة التطبيقات (API) لتنسيق تبادل الرسومات (GIF) ملف الصورة أدوات متعددة للمطورين لمعالجة الصور النقطية المضغوطة وصور GIF المتحركة. وتقدم ميزات مثل معالجة بيانات التعريف XMP، إعدادات لوحة الألوان، التحكم في لون الخلفية والشفافية، إعدادات الشفافية، تغيير الحجم، القص، تطبيق الفلاتر، تصحيح غاما، تعديل التباين، التحويل إلى تدرج الرمادي، والتحويل إلى صيغ أخرى. تمكّن هذه الواجهة البرمجية (API) من التلاعب السلس وتعزيز صور GIF لمجموعة واسعة من التطبيقات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-) | ابدأ كائنًا جديدًا من [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) مع المعلمات المحددة للإطار الأول ولوحة الألوان العامة. |
| [GifImage(GifFrameBlock firstFrame)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | تصميم صور GIF يصبح سهلاً مع مُنشئ [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-) | ابدأ بسهولة مع مُنشئ [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | استرجع تنسيق الملف بسهولة باستخدام هذه الخاصية. |
| [hasTrailer()](#hasTrailer--) | تحكم في وجود مقطع إضافي في ملفات GIF الخاصة بك باستخدام هذه الخاصية. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | تحكم في وجود مقطع إضافي في ملفات GIF الخاصة بك باستخدام هذه الخاصية. |
| [isPaletteSorted()](#isPaletteSorted--) | تحكم في ترتيب لوحة الألوان في صور GIF الخاصة بك باستخدام هذه الخاصية. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | تحكم في ترتيب لوحة الألوان في صور GIF الخاصة بك باستخدام هذه الخاصية. |
| [getLoopsCount()](#getLoopsCount--) | استرجع عدد مرات التكرار بسهولة باستخدام هذه الخاصية. |
| [setLoopsCount(int value)](#setLoopsCount-int-) | استرجع عدد مرات التكرار بسهولة باستخدام هذه الخاصية. |
| [getPaletteColorResolutionBits()](#getPaletteColorResolutionBits--) | تحكم في دقة ألوان لوحة الألوان لصور GIF الخاصة بك باستخدام هذه الخاصية. |
| [setPaletteColorResolutionBits(byte value)](#setPaletteColorResolutionBits-byte-) | تحكم في دقة ألوان لوحة الألوان لصور GIF الخاصة بك باستخدام هذه الخاصية. |
| [getPageCount()](#getPageCount--) | استرجع العدد الإجمالي للصفحات الموجودة داخل الصورة باستخدام هذه الخاصية البسيطة. |
| [getPages()](#getPages--) | احصل على الوصول إلى الصفحات داخل الصورة عبر هذه الخاصية المريحة، مما يتيح التنقل السلس وتعديل الصفحات الفردية حسب الحاجة. |
| [getBlocks()](#getBlocks--) | احصل على الوصول إلى كتل GIF بسهولة باستخدام هذه الخاصية، مما يسهل استرجاع وتعديل هياكل البيانات الأساسية للصورة. |
| [isInterlaced()](#isInterlaced--) | يحدد ما إذا كانت الصورة متشابكة، مما يؤثر على عرضها أثناء التحميل. |
| [getOriginalOptions()](#getOriginalOptions--) | استرجع الخيارات المستندة إلى إعدادات الملف الأصلي، وهي ضرورية للحفاظ على الدقة والاتساق في معالجة وتعديل الصور. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | أدمج صفحة جديدة بسلاسة في الصورة الحالية، مما يعزز محتواها ويوسع نطاقها. |
| [getActiveFrame()](#getActiveFrame--) | تحكم وتعديل الإطارات باستخدام هذه الخاصية، مما يتيح التنقل السلس وتعديل الإطار النشط داخل صورة GIF. |
| [setActiveFrame(GifFrameBlock value)](#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | تحكم وتعديل الإطارات باستخدام هذه الخاصية، مما يتيح التنقل السلس وتعديل الإطار النشط داخل صورة GIF. |
| [getBackgroundColor()](#getBackgroundColor--) | تحكم في لون الخلفية لصورة GIF باستخدام هذه الخاصية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | تحكم في لون الخلفية لصورة GIF باستخدام هذه الخاصية. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | تحكم في فهرس لون الخلفية لصورة GIF باستخدام هذه الخاصية. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | تحكم في فهرس لون الخلفية لصورة GIF باستخدام هذه الخاصية. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | تحكم في نسبة أبعاد البكسل لصورة GIF باستخدام هذه الخاصية. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | تحكم في نسبة أبعاد البكسل لصورة GIF باستخدام هذه الخاصية. |
| [hasTransparentColor()](#hasTransparentColor--) | حدد ما إذا كان الإطار النشط لصورة GIF يحتوي على لون شفاف. |
| [getTransparentColor()](#getTransparentColor--) | استرجع اللون الشفاف للإطار النشط في صورة GIF. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | حدد ما إذا كان الإطار النشط لصورة GIF يحتوي على لون شفاف. |
| [hasBackgroundColor()](#hasBackgroundColor--) | تحدد هذه الخاصية ما إذا كانت صورة GIF تحتوي على لون خلفية. |
| [getImageOpacity()](#getImageOpacity--) | استرجع شفافية الإطار النشط داخل الصورة، مما يوفر نظرة على مستوى الشفافية. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | يعيد تحجيم هذه [Image](../../com.aspose.imaging/image) المثيل. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | يعيد تحجيم هذه [Image](../../com.aspose.imaging/image) المثيل. |
| [resizeFullFrame(int newWidth, int newHeight, int resizeType)](#resizeFullFrame-int-int-int-) | إعادة تحجيم الصورة مع مراعاة الإطارات الكاملة لكل صفحة في GIF، وبالتالي منع ظهور العيوب المحتملة. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | قم بإجراء دوران أو انعكاس أو كليهما على الإطار النشط فقط. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | طبق التمويه على الصورة الحالية. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | قص الصورة باستخدام منطقة مستطيلة محددة. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | حسّن جودة الصورة بتطبيق تصحيح جاما. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | طبق مرشحًا محددًا على المنطقة المخصصة من الصورة، مما يعزز جودتها البصرية أو يغيّر مظهرها حسب الرغبة. |
| [setFrameTime(int time)](#setFrameTime-int-) | يضبط مدة كل إطار بالمللي ثانية، مما يضمن توقيتًا ثابتًا طوال تسلسل الصور. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | يضبط سطوع الصورة وفقًا للمعامل المحدد `brightness`. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | يضبط تباين الصورة، معززًا أو مخفضًا الفرق في السطوع بين البكسلات. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | تصحيح جاما للصورة يطبق تعديلًا غير خطي على قيم البكسل، معززًا أو مخفضًا السطوع بناءً على المعاملات المحددة للقنوات الحمراء والخضراء والزرقاء. |
| [grayscale()](#grayscale--) | تحويل الصورة إلى تمثيلها بالدرجات الرمادية يحول الصورة الملونة إلى نسخة بالدرجات الرمادية عن طريق إزالة معلومات اللون مع الحفاظ على الإضاءة. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا يحول صورة رمادية أو ملونة إلى صورة ثنائية، حيث يتم تصنيف كل بكسل إما أسود أو أبيض بناءً على ما إذا كانت قيمة شدته تتجاوز العتبة المحددة. |
| [binarizeOtsu()](#binarizeOtsu--) | تحويل الصورة إلى ثنائية باستخدام طريقة أوتسو لتحديد العتبة هو أسلوب يُستخدم لتحديد قيمة العتبة المثلى تلقائيًا لتحويل صورة رمادية إلى صورة ثنائية. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | تحويل الصورة إلى ثنائية باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة هو أسلوب لتحويل صورة رمادية إلى صورة ثنائية. |
| [orderBlocks()](#orderBlocks--) | ترتيب كتل GIF وفقًا لمواصفات GIF يضمن تخطيطًا صحيحًا للـ GIF والامتثال للمعيار. |
| [clearBlocks()](#clearBlocks--) | مسح جميع كتل GIF يزيل أي بيانات موجودة مخزنة داخل الصورة. |
| [insertBlock(int index, IGifBlock block)](#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-) | إدراج كتلة GIF جديدة يتيح لك إضافة بيانات مخصصة في موضع محدد داخل الصورة. |
| [addBlock(IGifBlock block)](#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | إضافة كتلة GIF جديدة يتيح لك تضمين بيانات إضافية داخل الصورة. |
| [removeBlock(IGifBlock block)](#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | إزالة كتلة GIF تزيل بيانات محددة من الصورة، مما يوفر القدرة على تنظيف أو تعديل بنية الصورة. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | تغيير الحجم بشكل متناسب يحافظ على نسبة أبعاد الصورة أثناء تعديل حجمها، مما يضمن عدم ظهور الصورة مشوهة أو ممدودة. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | هذه الطريقة تدور الصورة حول نقطة مركزها. |

## Example: This example shows how to create a GIF image and save it to a file.

``` java
String dir = "c:\\temp\\";

// إنشاء كتلة إطار GIF بحجم 100×100 بكسل.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
try {
    // املأ الكتلة بالكامل باللون الأحمر.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(firstBlock);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    gr.fillRectangle(brush, firstBlock.getBounds());

    com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
    try {
        gifImage.save(dir + "output.gif");
    } finally {
        gifImage.dispose();
    }
} finally {
    firstBlock.dispose();
}
```


## Example: Create multipage GIF image using single page raster images.

``` java
static void main(String[] args)
{
    // تحميل الإطارات
    RasterImage[] frames = loadFrames("Animation frames");

    // إنشاء صورة GIF باستخدام الإطار الأول
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // إضافة إطارات إلى صورة GIF باستخدام طريقة AddPage
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // حفظ صورة GIF
        image.save("Multipage.gif");
    }

    // تحرير الموارد
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```


## Example: Export of part of animation from GIF image based on time interval.

``` java
try (Image image = Image.load("Animation.gif"))
{
    GifOptions options = new GifOptions();
    options.setFullFrame(true);
    final MultiPageOptions multiPageOptions = new MultiPageOptions();
    multiPageOptions.setMode(MultiPageMode.TimeInterval);
    multiPageOptions.setTimeInterval(new TimeInterval(0, 400));
    options.setMultiPageOptions(multiPageOptions);

    image.save("PartOfAnimation.gif", options);
}
```

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```


ابدأ كائنًا جديدًا [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) مع معلمات محددة للإطار الأول واللوحة العامة. ابدأ إدارة صور GIF بسرعة، مع ضمان تمثيل دقيق بإعدادات قابلة للتخصيص للحصول على أفضل النتائج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | الإطار الأول لبدء إنشاء صورة GIF به. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | اللوحة العامة للاستخدام. لاحظ أنه إذا كان كل من `firstFrame` و `globalPalette` فارغين (null) فسيتم استخدام اللوحة العامة الافتراضية. |

### GifImage(GifFrameBlock firstFrame) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public GifImage(GifFrameBlock firstFrame)
```


إنشاء صور GIF يصبح سهلًا مع مُنشئ [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). باستخدام معلمة firstFrame فقط، تدخل عالمًا من التواصل البصري الديناميكي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | الإطار الأول لبدء إنشاء صورة GIF به. |

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)
```


ابدأ بسهولة مع مُنشئ [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). باستخدام هذه الطريقة البسيطة، يمكنك الغوص في إنشاء صور GIF متحركة بسهولة. فقط قدم firstFrame وglobalPalette وpaletteColorResolution وaspectRatio وغيرها من المعلمات، وستكون جاهزًا لإحياء مرئياتك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | الإطار الأول لبدء إنشاء صورة GIF به. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | اللوحة العامة للاستخدام. لاحظ أنه إذا كان كل من `firstFrame` و `globalPalette` فارغين (null) فسيتم استخدام اللوحة العامة الافتراضية. |
| isPaletteSorted | boolean | إذا تم تعيينه إلى `true` يتم فرز اللوحة. لاحظ أن المعلمة تُستخدم عندما يكون `globalPalette` غير فارغ. |
| paletteColorResolution | byte | دقة ألوان اللوحة. لاحظ أن المعلمة تُستخدم عندما يكون `globalPalette` غير فارغ. |
| paletteBackgroundColorIndex | byte | فهرس لون خلفية اللوحة. |
| aspectRatio | byte | نسبة العرض إلى الارتفاع. |
| hasTrailer | boolean | إذا تم تعيينه إلى `true` تحتوي صورة GIF على مقطع تمهيدي، وإلا لن يتم كتابة أي مقطع تمهيدي في نهاية الدفق. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


استرجع تنسيق الملف بسهولة باستخدام هذه الخاصية. إنها مصدرُك الأساسي لتحديد تنسيق ملفاتك. مدمجة بسلاسة في سير عملك، توفر معلومات حيوية دون أي عناء.

**Returns:**
long
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


إدارة وجود مقطع تمهيدي في ملفات GIF الخاصة بك باستخدام هذه الخاصية. سواء كنت تحتاج إلى التحقق مما إذا كان هناك مقطع تمهيدي أو ضبط وجوده، فإن هذه الخاصية تبسط العملية. حافظ على هيكلة ملفات GIF الخاصة بك والامتثال باستخدام هذه الميزة البديهية.

**Returns:**
منطقي - `true` إذا كان GIF يحتوي على ذيل؛ وإلا `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


إدارة وجود مقطع تمهيدي في ملفات GIF الخاصة بك باستخدام هذه الخاصية. سواء كنت تحتاج إلى التحقق مما إذا كان هناك مقطع تمهيدي أو ضبط وجوده، فإن هذه الخاصية تبسط العملية. حافظ على هيكلة ملفات GIF الخاصة بك والامتثال باستخدام هذه الميزة البديهية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا كان GIF يحتوي على ذيل؛ وإلا `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


تحكم في فرز اللوحة في صور GIF الخاصة بك باستخدام هذه الخاصية. سواء كنت تحتاج إلى التحقق مما إذا كانت اللوحة مرتبة أو ضبط سلوك الفرز، فإن هذه الخاصية توفر طريقة مباشرة لإدارة تنظيم اللوحة في ملفات GIF.

**Returns:**
boolean - `true` إذا تم فرز اللوحة؛ وإلا `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


تحكم في فرز اللوحة في صور GIF الخاصة بك باستخدام هذه الخاصية. سواء كنت تحتاج إلى التحقق مما إذا كانت اللوحة مرتبة أو ضبط سلوك الفرز، فإن هذه الخاصية توفر طريقة مباشرة لإدارة تنظيم اللوحة في ملفات GIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا تم فرز اللوحة؛ وإلا `false`. |

### getLoopsCount() {#getLoopsCount--}
```
public int getLoopsCount()
```


استرجع عدد مرات التكرار بسهولة باستخدام هذه الخاصية. إذا كانت صورة GIF الخاصة بك تتضمن معلومات التكرار، فإن هذه الخاصية تمنحك وصولًا سريعًا إلى عدد التكرارات، مما يتيح لك إدارة سلوك التكرار في ملفات GIF بسلاسة.

**Returns:**
int - عدد الحلقات أو 1 (القيمة الافتراضية)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public void setLoopsCount(int value)
```


استرجع عدد مرات التكرار بسهولة باستخدام هذه الخاصية. إذا كانت صورة GIF الخاصة بك تتضمن معلومات التكرار، فإن هذه الخاصية تمنحك وصولًا سريعًا إلى عدد التكرارات، مما يتيح لك إدارة سلوك التكرار في ملفات GIF بسلاسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | عدد الحلقات أو 1 (القيمة الافتراضية) |

### getPaletteColorResolutionBits() {#getPaletteColorResolutionBits--}
```
public byte getPaletteColorResolutionBits()
```


إدارة دقة ألوان لوحة GIF الخاصة بك باستخدام هذه الخاصية. اضبط عدد البتات المستخدمة لتمثيل الألوان في اللوحة، مما يوفر تحكمًا دقيقًا في عمق اللون وجودة الصورة.

**Returns:**
byte - بتات دقة ألوان اللوحة.
### setPaletteColorResolutionBits(byte value) {#setPaletteColorResolutionBits-byte-}
```
public void setPaletteColorResolutionBits(byte value)
```


إدارة دقة ألوان لوحة GIF الخاصة بك باستخدام هذه الخاصية. اضبط عدد البتات المستخدمة لتمثيل الألوان في اللوحة، مما يوفر تحكمًا دقيقًا في عمق اللون وجودة الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | بتات دقة ألوان اللوحة. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


استرجع العدد الإجمالي للصفحات المحتواة داخل الصورة باستخدام هذه الخاصية المباشرة. مثالية لتقييم سريع لمدى محتوى الصورة.

**Returns:**
int - عدد الصفحات.
### getPages() {#getPages--}
```
public Image[] getPages()
```


احصل على الوصول إلى الصفحات داخل الصورة عبر هذه الخاصية المريحة، مما يتيح التنقل السلس وتعديل الصفحات الفردية حسب الحاجة.

**Returns:**
com.aspose.imaging.Image[] - الصفحات.
### getBlocks() {#getBlocks--}
```
public IGifBlock[] getBlocks()
```


احصل على الوصول إلى كتل GIF بسهولة باستخدام هذه الخاصية، مما يسهل استرجاع وتعديل هياكل البيانات الأساسية للصورة.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlock[] - كتل GIF.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


يحدد ما إذا كانت الصورة متشابكة، مما يؤثر على عرضها أثناء التحميل. توفر هذه الخاصية نظرة على سلوك عرض الصورة، وهو أمر أساسي لتحسين استراتيجيات التحميل وتعزيز تجربة المشاهدة العامة.

**Returns:**
منطقي - `true` إذا كان هذا الكائن الصورة متشابكًا؛ وإلا `false`.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


استرجع الخيارات المستندة إلى إعدادات الملف الأصلية، وهي ضرورية للحفاظ على الدقة والاتساق في معالجة الصور وتعديلها. تسمح هذه الطريقة بدمج سلس للمعلمات الخاصة بالملف في العمليات اللاحقة، مما يضمن تمثيلًا دقيقًا والالتزام بخصائص الصورة الجوهرية. يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت ومعلمات أخرى للصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومرّرها إلى طريقة [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) كمعامل ثانٍ.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


أدمج صفحة جديدة بسلاسة في الصورة الحالية، معززًا محتواها وموسعًا نطاقها. تُضيف هذه الطريقة مجموعات الصور محتوى إضافيًا، مما يعزز الإبداع والمرونة في إدارة الصور وتكوينها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | الصفحة التي سيتم إضافتها. |


**Example: Create multipage GIF image using single page raster images.**

``` java
static void main(String[] args)
{
    // تحميل الإطارات
    RasterImage[] frames = loadFrames("Animation frames");

    // إنشاء صورة GIF باستخدام الإطار الأول
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // إضافة إطارات إلى صورة GIF باستخدام طريقة AddPage
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // حفظ صورة GIF
        image.save("Multipage.gif");
    }

    // تحرير الموارد
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```

### getActiveFrame() {#getActiveFrame--}
```
public GifFrameBlock getActiveFrame()
```


تحكم وتعديل الإطارات باستخدام هذه الخاصية، مما يتيح التنقل السلس وتعديل الإطار النشط داخل صورة GIF.

**Returns:**
[GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) - the active frame.

**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// المخرجات تبدو هكذا:
// حجم الإطار النشط: { Width = 100, Height = 100}
// امسح جميع الكتل
// الإطار النشط غير مُحدد
```

### setActiveFrame(GifFrameBlock value) {#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public void setActiveFrame(GifFrameBlock value)
```


تحكم وتعديل الإطارات باستخدام هذه الخاصية، مما يتيح التنقل السلس وتعديل الإطار النشط داخل صورة GIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | الإطار النشط. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


تحكم في لون الخلفية لصورة GIF باستخدام هذه الخاصية. يمكنك تعيين أو استرجاع لون الخلفية لضمان الاتساق وتعزيز الجاذبية البصرية.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


تحكم في لون الخلفية لصورة GIF باستخدام هذه الخاصية. يمكنك تعيين أو استرجاع لون الخلفية لضمان الاتساق وتعزيز الجاذبية البصرية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


تحكم في فهرس لون الخلفية لصورة GIF باستخدام هذه الخاصية. قم بتعيين أو استرجاع الفهرس للحفاظ على الاتساق أو تحقيق التأثيرات البصرية المطلوبة.

**Returns:**
بايت - فهرس لون الخلفية.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


تحكم في فهرس لون الخلفية لصورة GIF باستخدام هذه الخاصية. قم بتعيين أو استرجاع الفهرس للحفاظ على الاتساق أو تحقيق التأثيرات البصرية المطلوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | فهرس لون الخلفية. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


تحكم في نسبة أبعاد البكسل لصورة GIF باستخدام هذه الخاصية. قم بتعيين أو استرجاع النسبة لضمان عرض دقيق والحفاظ على جودة الصورة البصرية.

**Returns:**
بايت - نسبة أبعاد البكسل.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


تحكم في نسبة أبعاد البكسل لصورة GIF باستخدام هذه الخاصية. قم بتعيين أو استرجاع النسبة لضمان عرض دقيق والحفاظ على جودة الصورة البصرية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | نسبة أبعاد البكسل. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


حدد ما إذا كان الإطار النشط لصورة GIF يحتوي على لون شفاف. توفر هذه الخاصية طريقة مريحة للتحقق من الشفافية داخل الصورة.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان الإطار النشط يحتوي على لون شفاف.
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


استرجع اللون الشفاف للإطار النشط في صورة GIF. تتيح لك هذه الخاصية الوصول إلى اللون المحدد كشفاف داخل الإطار النشط الحالي.

**Returns:**
[Color](../../com.aspose.imaging/color) - active frame transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


حدد ما إذا كان الإطار النشط لصورة GIF يحتوي على لون شفاف. توفر هذه الخاصية طريقة مريحة للتحقق من الشفافية داخل الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان الإطار النشط يحتوي على لون شفاف. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


تحدد هذه الخاصية ما إذا كانت صورة GIF تحتوي على لون خلفية. إذا كانت true، فهذا يعني أن الصورة تشمل لون خلفية.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


استرجع شفافية الإطار النشط داخل الصورة، مما يوفر نظرة على مستوى الشفافية. هذه الخاصية مفيدة بشكل خاص لفهم درجة الشفافية أو العتمة للإطار النشط في الصورة.

قيمة الشفافية بين 0.0 (شفاف تمامًا) و 1.0 (معتم تمامًا).

**Returns:**
عائم - شفافية هذه الصورة (الإطار النشط).
### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


يعيد تحجيم هذه [Image](../../com.aspose.imaging/image) المثيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |


**Example: This example loads a GIF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


يعيد تحجيم هذه [Image](../../com.aspose.imaging/image) المثيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | الإعدادات. |


**Example: This example loads a GIF image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// الخوارزمية التكيفية المستندة إلى الدالة النسبية الموزونة والمختلطة وتداخل lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// المرشح المستطيل الصغير
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// عدد الألوان في لوحة الألوان.
resizeSettings.setEntriesCount(256);

// لم يتم استخدام تقليل ألوان.
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// طريقة إقليدية
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // قُم بتقليل الحجم بمقدار مرتين باستخدام إعادة أخذ عينات متكيفة.
    gifImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // حفظ إلى PNG
    gifImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeFullFrame(int newWidth, int newHeight, int resizeType) {#resizeFullFrame-int-int-int-}
```
public void resizeFullFrame(int newWidth, int newHeight, int resizeType)
```


تغيير حجم الصورة مع مراعاة الإطارات الكاملة لكل صفحة في GIF، مما يمنع ظهور العيوب المحتملة. هذه الطريقة أساسية للحفاظ على سلامة وجودة الصورة، خاصةً عند التعامل مع GIF المتحركة أو تسلسلات الإطارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


قم بأداء تدوير أو قلب أو كليهما على الإطار النشط فقط. يطبق هذا الإجراء التحويلات حصريًا على الإطار النشط حاليًا للصورة، مع الحفاظ على سلامة الإطارات الأخرى في التسلسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | نوع الدوران والقلب. |


**Example: This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java

// فئة المساعدة المستخدمة في المثال الرئيسي أدناه.
class Utils {
    // طريقة المساعدة للحصول على تمثيل نصي لتنسيق الملف.
    public String getRotateFlipTypeString(int rotateFlipType) {
        if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipNone) {
            return "RotateNoneFlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipNone) {
            return "Rotate90FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipNone) {
            return "Rotate180FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipNone) {
            return "Rotate270FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipX) {
            return "RotateNoneFlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipX) {
            return "Rotate90FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipX) {
            return "Rotate180FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipX) {
            return "Rotate270FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipY) {
            return "RotateNoneFlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipY) {
            return "Rotate90FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipY) {
            return "Rotate180FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipY) {
            return "Rotate270FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipXY) {
            return "RotateNoneFlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipXY) {
            return "Rotate90FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipXY) {
            return "Rotate180FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipXY) {
            return "Rotate270FlipXY";
        } else {
            return "UNDEFINED";
        }
    }
}

// هنا المثال الرئيسي
Utils utils = new Utils();

String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // قم بالدوران، القليب وحفظ إلى ملف الإخراج.
    com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.getRotateFlipTypeString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


طبق التمويه على الصورة الحالية. تُحسن هذه العملية جودة الصورة عن طريق تقليل تدرج الألوان وتحسين الانتقالات اللونية، مما ينتج مظهرًا أكثر سلاسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | int | طريقة التمويه. |
| bitsCount | int | عدد البتات النهائي للتمويه. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان المخصصة للتمويه. |


**Example: The following example loads a GIF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // قم بتنفيذ تدرّج العتبة باستخدام لوحة ألوان 4‑بت تحتوي على 16 لونًا.
    // كلما زاد عدد البتات المحددة، ارتفعت الجودة وزاد حجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان ذات 1‑بت، 4‑بت و8‑بت فقط هي المدعومة حاليًا.
    gifImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // قم بتنفيذ تدرّج Floyd باستخدام لوحة ألوان 1‑بت تحتوي فقط على لونين - الأسود والأبيض.
    // كلما زاد عدد البتات المحددة، ارتفعت الجودة وزاد حجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان ذات 1‑بت، 4‑بت و8‑بت فقط هي المدعومة حاليًا.
    gifImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


قم بقص الصورة باستخدام منطقة مستطيلة محددة. يزيل هذا الإجراء الجزء الخارجي من الصورة، ويترك فقط المنطقة المختارة المحددة بالمستطيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |


**Example: The following example crops a GIF image.**
المثال التالي يقتص صورة GIF. يتم تحديد منطقة القص عبر Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // قص الصورة. منطقة القص هي المنطقة المستطيلة المركزية في الصورة.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            gifImage.getWidth() / 4,
            gifImage.getHeight() / 4,
            gifImage.getWidth() / 2,
            gifImage.getHeight() / 2);
    gifImage.crop(area);

    // احفظ الصورة المقتطعة بصيغة PNG
    gifImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


حسّن جودة الصورة بتطبيق تصحيح جاما. يضبط هذا الأسلوب جاما اللون للصورة لتحقيق وضوح بصري أمثل. يغيّر قيمة الجاما لكل بكسل، مما ينتج تحسينًا في تمثيل الألوان ومظهر الصورة العام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| غاما | float | معامل غاما لقنوات الأحمر والأخضر والأزرق |


**Example: The following example performs gamma-correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // تعيين معامل غاما لقنوات الأحمر والأخضر والأزرق.
    gifImage.adjustGamma(2.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


طبق مرشحًا محددًا على المنطقة المخصصة من الصورة، مما يعزز جودتها البصرية أو يغيّر مظهرها حسب الرغبة. يعالج هذا الأسلوب البكسلات داخل المستطيل المحدد بشكل انتقائي، مما يسمح بإجراء تعديلات مستهدفة مع الحفاظ على سلامة بيانات الصورة المحيطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | الخيارات. |


**Example: The following example applies various types of filters to a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // طبق مرشح متوسط بحجم مستطيل 5 على الصورة بأكملها.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    gifImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // طبق مرشح تمهيد ثنائي الجانب بحجم نواة 5 على الصورة بأكملها.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    gifImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // طبق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بأكملها.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // طبق مرشح غاوس-واينر بنصف قطر 5 وقيمة تمهيد 4.0 على الصورة بأكملها.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // طبق مرشح واينر حركي بطول 5، قيمة تمهيد 4.0 وزاوية 90.0 درجة على الصورة بأكملها.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    gifImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // طبق مرشح شحذ بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بأكملها.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### setFrameTime(int time) {#setFrameTime-int-}
```
public void setFrameTime(int time)
```


يضبط مدة كل إطار بالمللي ثانية، مما يضمن توقيتًا ثابتًا عبر تسلسل الصورة. يحدد هذا الأسلوب زمن عرض كل إطار بشكل موحد، مما يتيح تحكمًا دقيقًا في سرعة الرسوم المتحركة. تغيير هذه القيمة سيعيد ضبط التأخير لجميع الإطارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الوقت | int | وقت مدة الإطار بالمللي ثانية. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


يضبط سطوع الصورة وفقًا للمعامل `brightness` المحدد. يغيّر هذا الأسلوب سطوع الصورة بالكامل بشكل موحد، معززًا أو مخفضًا الإضاءة العامة لتحقيق التأثير المطلوب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightness | int | قيمة السطوع. |


**Example: The following example performs brightness correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // حدد قيمة السطوع. القيم المقبولة للسطوع تقع في النطاق [-255, 255].
    gifImage.adjustBrightness(50);
    gifImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


يضبط تباين الصورة، معززًا أو مخفضًا الفرق في السطوع بين البكسلات. يغيّر هذا الأسلوب النطاق النغمي العام للصورة، مما يجعل المناطق الداكنة أكثر ظلامًا والمناطق الفاتحة أكثر إشراقًا لتحسين الوضوح البصري والتفاصيل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| contrast | float | قيمة التباين (في النطاق [-100؛ 100]) |


**Example: The following example performs contrast correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // حدد قيمة التباين. القيم المقبولة للتباين تقع في النطاق [-100f, 100f].
    gifImage.adjustContrast(50f);
    gifImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


تطبيق تصحيح جاما على الصورة يضيف تعديلًا غير خطي لقيم البكسل، معززًا أو مخفضًا السطوع بناءً على المعاملات المحددة لقنوات الأحمر والأخضر والأزرق. يساعد هذا الأسلوب على ضبط توازن الألوان وإضاءة الصورة بدقة، مما يحسن مظهرها العام وجودتها البصرية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | float | معامل غاما لقناة الأحمر |
| gammaGreen | float | معامل غاما لقناة الأخضر |
| gammaBlue | float | معامل غاما لقناة اللون الأزرق |


**Example: The following example performs gamma-correction of a GIF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // تعيين معاملات غاما الفردية لقنوات الأحمر والأخضر والأزرق.
    gifImage.adjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


تحويل الصورة إلى تمثيلها بالأبيض والأسود يحول الصورة الملونة إلى نسخة رمادية عن طريق إزالة معلومات اللون مع الحفاظ على الإضاءة. يبسط هذا العملية إلى درجات من الرمادي، مما يجعلها مناسبة لتطبيقات مختلفة مثل الطباعة، معالجة المستندات، والتحليل الرمادي.


**Example: The following example transforms a colored GIF image to its grayscale representation.**
المثال التالي يحول صورة GIF ملونة إلى تمثيلها بالأبيض والأسود. الصور الرمادية تتكون حصريًا من درجات الرمادي وتحمل فقط معلومات الشدة.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    gifImage.grayscale();
    gifImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا يحول صورة رمادية أو ملونة إلى صورة ثنائية، حيث يتم تصنيف كل بكسل إما أسود أو أبيض بناءً على ما إذا كانت قيمة شدته تتجاوز العتبة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | byte | قيمة العتبة. إذا كانت قيمة الرمادي المقابلة لبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا 0. |


**Example: The following example binarizes a GIF image with the predefined threshold.**
المثال التالي يثنّي صورة GIF باستخدام العتبة المحددة مسبقًا. الصور المثلّية تحتوي فقط على لونين - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage djvuImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // قم بتحويل الصورة إلى ثنائية باستخدام قيمة العتبة 127.
    // إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من 127، سيتم تعيين القيمة 255 له، وإلا ستكون 0.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


تثنّي الصورة باستخدام عتبة أوتسو هو طريقة تُستخدم لتحديد القيمة المثلى للعتبة تلقائيًا لتحويل صورة رمادية إلى صورة ثنائية. يحسب خوارزمية عتبة أوتسو العتبة التي تقلل من التباين داخل الفئات لقيم بكسل الصورتين الناتجتين (المقدمة والخلفية). هذه التقنية مفيدة بشكل خاص عندما تكون قيمة العتبة المثلى غير معروفة وتحتاج إلى تحديدها بشكل تكيفي بناءً على هيستوغرام الصورة.


**Example: The following example binarizes a GIF image with Otsu thresholding.**
المثال التالي يثنّي صورة GIF باستخدام عتبة أوتسو. الصور المثلّية تحتوي فقط على لونين - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // قم بتحويل الصورة إلى ثنائية باستخدام عتبة أوتسو.
    gifImage.binarizeOtsu();
    gifImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


تثنّي الصورة باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة هي طريقة لتحويل صورة رمادية إلى صورة ثنائية. تحسب هذه الخوارزمية عتبة محلية لكل بكسل بناءً على متوسط شدة البكسلات المحيطة داخل نافذة محددة. من خلال تعديل العتبة محليًا بناءً على شدة البكسلات، تكون طريقة برادلي فعّالة في التعامل مع اختلافات الإضاءة والتباين عبر الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s بكسل متمركزة حول هذا البكسل. |

### orderBlocks() {#orderBlocks--}
```
public void orderBlocks()
```


ترتيب كتل GIF وفقًا لمواصفات GIF يضمن تخطيطًا صحيحًا للـ GIF والامتثال للمعيار. تتضمن هذه العملية ترتيب الكتل بالتسلسل الصحيح كما هو معرف في المواصفة. بالإضافة إلى ذلك، قد تشمل إزالة بعض حالات [GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) التي لا تكون ضرورية للتخطيط النهائي. بالالتزام بمواصفات GIF، ستكون الصورة الناتجة مُهيكلة بشكل صحيح ومتوافقة مع تطبيقات عرض GIF.

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


مسح جميع كتل GIF يزيل أي بيانات موجودة مخزنة داخل الصورة. يعيد هذا الإجراء الصورة إلى حالة فارغة، مزيلًا أي كتل مضافة مسبقًا. استخدم هذه الطريقة عندما تحتاج إلى بدء جديد بصفحة نظيفة لإنشاء أو تعديل صورة GIF.


**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// المخرجات تبدو هكذا:
// حجم الإطار النشط: { Width = 100, Height = 100}
// امسح جميع الكتل
// الإطار النشط غير مُحدد
```

### insertBlock(int index, IGifBlock block) {#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void insertBlock(int index, IGifBlock block)
```


إدراج كتلة GIF جديدة يتيح لك إضافة بيانات مخصصة في موقع محدد داخل الصورة. تمكّن هذه الطريقة من وضع كتل مخصصة في الموقع المطلوب في صورة GIF، مما يوفر مرونة في تنظيم وهيكلة بيانات الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | العنصر ذو الفهرس الصفري، الذي سيتم إدراج الكتلة عنده. |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | كتلة GIF المراد إضافتها. |

### addBlock(IGifBlock block) {#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void addBlock(IGifBlock block)
```


إضافة كتلة GIF جديدة يتيح لك تضمين بيانات إضافية داخل الصورة. تمكّن هذه الطريقة من إلحاق كتل مخصصة إلى صورة GIF، والتي يمكن أن تحتوي على أنواع مختلفة من المعلومات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | كتلة GIF المراد إضافتها. |


**Example: The following example shows how to compose an animated GIF image from individual GIF blocks.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة GIF بحجم 100 × 100 بكسل.
// الكتلة الأولى تكون سوداء بالكامل بشكل افتراضي.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    // الدائرة الأولى حمراء
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // الدائرة الثانية سوداء
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // زيادة زاوية الشكل القوسي الأحمر تدريجيًا.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush1, block.getBounds(), 0, angle);

        gifImage.addBlock(block);
    }

    // زيادة زاوية القوس الأسود تدريجيًا ومحو القوس الأحمر.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush2, block.getBounds(), 0, angle);
        gr.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        gifImage.addBlock(block);
    }

    gifImage.save(dir + "animated_radar.gif");
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}
```

### removeBlock(IGifBlock block) {#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void removeBlock(IGifBlock block)
```


إزالة كتلة GIF تزيل بيانات محددة من الصورة، مما يتيح القدرة على تنظيف أو تعديل بنية الصورة. تمكّنك هذه الطريقة من إزالة الكتل غير المرغوب فيها أو غير الضرورية، مما يحسن من تحسين صورة GIF لتخزين فعال. استخدم هذه الوظيفة لإزالة المعلومات القديمة من الصورة مع الحفاظ على سلامتها وجودتها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | الكتلة المراد إزالتها. |

--------------------

ملاحظة: لا تنسَ التخلص من الكتلة إذا لم تقم بإضافتها إلى صورة GifImage أخرى. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


يُحافظ تغيير الحجم النسبي على نسبة أبعاد الصورة أثناء تعديل حجمها، مما يضمن عدم ظهور الصورة مشوّشة أو مُطوَّلة. تقوم هذه الطريقة بتغيير حجم الصورة نسبيًا، حيث يتم تحجيم كل من العرض والارتفاع بنفس العامل. سيُعيد تغيير الحجم النسبي تحجيم كل إطار وفقًا للنسبة بين `newWidth`/العرض و `newHeight`/الارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


تقوم هذه الطريقة بتدوير الصورة حول نقطة مركزها. من خلال تحديد زاوية الدوران، يمكنك تدوير الصورة باتجاه عقارب الساعة أو عكسها لتحقيق الاتجاه المطلوب. يساعد هذا الدوران على تعديل عرض الصورة أو محاذاتها دون تشويه محتواها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resizeProportionally | boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى تُترك الأبعاد دون تعديل وتُدور فقط محتويات الصورة ``. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

