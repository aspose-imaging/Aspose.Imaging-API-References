---
title: "RasterCachedImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل صورة نقطية تدعم عمليات الرسومات النقطية."
type: docs
weight: 89
url: /ar/java/com.aspose.imaging/rastercachedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage)
```
public abstract class RasterCachedImage extends RasterImage
```

يمثل صورة نقطية تدعم عمليات الرسومات النقطية. تقوم هذه الصورة بتخزين بيانات البكسل مؤقتًا عند الحاجة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isCached()](#isCached--) | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [cacheData()](#cacheData--) | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من `DataStreamSupporter.DataStreamContainer` الأساسي. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | يمزج هذه النسخة من الصورة مع صورة `overlay`. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | يُعيد تحجيم الصورة. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | يُعيد تحجيم الصورة. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | يدور، يقلب، أو يدور ويقلب الصورة. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | دوّر الصورة حول المركز. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | قص الصورة. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | ينفّذ تمويهًا (dithering) على الصورة الحالية. |
| [grayscale()](#grayscale--) | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [normalizeHistogram()](#normalizeHistogram--) | يُعَدِّل هيستوغرام الصورة \\u2014 يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | ينفّذ تعديلًا تلقائيًا متكيفًا للسطوع والتباين لكامل الصورة. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا |
| [binarizeOtsu()](#binarizeOtsu--) | تحويل الصورة إلى ثنائية باستخدام عتبة Otsu |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة المتكيفة لبرايدلي مع عتبة الصورة المتكاملة |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة المتكيفة لبرايدلي مع عتبة الصورة المتكاملة |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | ضبط السطوع للصورة. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | تحسين التباين في الصورة |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | تصحيح جاما للصورة. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | تصحيح جاما للصورة. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | إدراج توقيع رقمي يعتمد على كلمة المرور المقدمة داخل الصورة باستخدام تقنية إخفاء المعلومات (steganography). |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | ينفّذ فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والعتبة المقدمة. |

## Example: The following example transforms a colored raster cached image to its grayscale representation.
المثال التالي يحول صورة نقطية ملونة مخزنة مؤقتًا إلى تمثيلها بتدرج الرمادي. صور تدرج الرمادي تتكون حصريًا من ظلال اللون الرمادي وتحمل معلومات الشدة فقط.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### isCached() {#isCached--}
```
public boolean isCached()
```


يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا.

**Returns:**
منطقي - `true` إذا كانت بيانات الصورة مخزنة مؤقتًا؛ وإلا `false`.
### cacheData() {#cacheData--}
```
public void cacheData()
```


يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من `DataStreamSupporter.DataStreamContainer` الأساسي.


**Example: The following example shows how raster image caching affects performance.**
المثال التالي يوضح كيف يؤثر تخزين الصور النقطية مؤقتًا على الأداء. في الحالة العامة، قراءة البيانات المخزنة مؤقتًا يتم بسرعة أكبر من قراءة البيانات غير المخزنة.
``` java
String dir = "c:\\temp\\";

// حمّل صورة من ملف PNG.
com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // خزن جميع بيانات البكسل بحيث لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // قراءة جميع البكسلات سريعة إلى حد كبير.
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all cached pixels took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// تحميل صورة من ملف PNG
image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // قراءة جميع البكسلات ليست سريعة كما هو الحال عند التخزين المؤقت
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all pixels without preliminary caching took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
//استغرق قراءة جميع البكسلات المخزنة مؤقتًا 2923 مللي ثانية.
//    java.lang.OutOfMemoryError
//في com.aspose.imaging.internal.G.be.b(مصدر غير معروف)
//في com.aspose.imaging.internal.G.be.a(مصدر غير معروف)
//في com.aspose.imaging.internal.G.be.a(مصدر غير معروف)
//في com.aspose.imaging.internal.G.be.a(مصدر غير معروف)
//في com.aspose.imaging.internal.G.aB.a(مصدر غير معروف)
//في com.aspose.imaging.RasterImage.a(مصدر غير معروف)
//في com.aspose.imaging.RasterImage.getArgb32Pixel(مصدر غير معروف)
//في com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:54)
```

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


يمزج هذه النسخة من الصورة مع صورة `overlay`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | أصل دمج صورة الخلفية. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | صورة التراكب. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | منطقة التراكب. |
| overlayAlpha | byte | قيمة ألفا للتراكب. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


يُعيد تحجيم الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |


**Example: This example loads a raster cached image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // حفظ إلى PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // حفظ إلى PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // حفظ إلى PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // حفظ إلى PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


يُعيد تحجيم الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير الحجم. |


**Example: This example loads a raster cached image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// الخوارزمية التكيفية المستندة إلى الدالة الكسرية الموزونة والمختلطة واستيفاء lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// المرشح المستطيل الصغير
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// عدد الألوان في لوحة الألوان.
resizeSettings.setEntriesCount(256);

// لم يتم استخدام تقليل ألوان الصورة
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// طريقة إقليدية
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // قُم بتقليل الحجم بمقدار مرتين باستخدام إعادة أخذ عينات تكيفية.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | نوع القلب الدوراني. |


**Example: This example loads a raster cached image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// هذه فئة مساعدة.
class LocalHelper {
    // يحصل على تمثيل نصي لنوع القلب الدوراني.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// إليك المثال الرئيسي
int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

LocalHelper localHelper = new LocalHelper();
for (int rotateFlipType : rotateFlipTypes) {
    // قم بالدوران، والقلّب، واحفظ إلى ملف الإخراج.
    com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + localHelper.rotateFlipTypeToString(rotateFlipType) + ".bmp");
    } finally {
        image.dispose();
    }
}
```

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


دوّر الصورة حول المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resizeProportionally | boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا) وإلا سيبقى الأبعاد دون تغيير وتُدوَّر محتويات الصورة الداخلية فقط. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


قص الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |


**Example: The following example crops a raster cached image.**
المثال التالي يقتطع صورة مخزنة كراستر. يتم تحديد منطقة القص عبر com.aspose.imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // قص الصورة. منطقة القص هي المنطقة المركزية المستطيلة للصورة.
    int width = rasterImage.getWidth();
    int height = rasterImage.getHeight();
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(width / 4, height / 4, width / 2, height / 2);
    rasterImage.crop(area);

    // احفظ الصورة المقتطعة بصيغة PNG
    rasterImage.save(dir + "sample.Crop.png");
} finally {
    image.dispose();
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


ينفّذ تمويهًا (dithering) على الصورة الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | int | طريقة التمويه. |
| bitsCount | int | عدد البتات النهائي للتمويه. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان المخصصة للتمويه. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


تحويل الصورة إلى تمثيلها بتدرج الرمادي


**Example: The following example transforms a colored raster cached image to its grayscale representation.**
المثال التالي يحول صورة نقطية ملونة مخزنة مؤقتًا إلى تمثيلها بتدرج الرمادي. صور تدرج الرمادي تتكون حصريًا من ظلال اللون الرمادي وتحمل معلومات الشدة فقط.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


يُعَدِّل هيستوغرام الصورة \\u2014 يضبط قيم البكسل لاستخدام كامل النطاق المتاح.

### autoBrightnessContrast() {#autoBrightnessContrast--}
```
public void autoBrightnessContrast()
```


ينفّذ تعديلًا تلقائيًا متكيفًا للسطوع والتباين لكامل الصورة.

--------------------

> ```
> // Example usage in image pre-processing:
>  image.AutoBrightnessContrast();
> ```

--------------------

تطبق هذه الطريقة خط أنابيب من المرشحات التكيفية المتقدمة (CLAHE، التمدد الأبيض التكيفي، وتوازن اللون الأبيض التلقائي) لتحسين الجودة البصرية للصورة من خلال تعزيز التباين، الإضاءة المحلية، ودقة الألوان.

`**خط أنابيب الفلتر:**`

1.  تعديل التباين المحدود للهيستوجرام التكيفي (CLAHE) – يحسن التباين المحلي ويعزز التفاصيل الباهتة.
2.  التمدد الأبيض التكيفي – يزيد مستوى الأبيض الفعال مع حماية الميزات الداكنة.
3.  توازن اللون الأبيض التلقائي – يصحح الانحرافات اللونية عبر موازنة هيستوجرامات القنوات.

`**ملاحظة:**`

 *  
 *  

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | byte | قيمة العتبة. إذا كانت قيمة الرمادي المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة 255 لها، وإلا 0. |


**Example: The following example binarizes a raster cached image with the predefined threshold.**
المثال التالي يحول صورة مخزنة كراستر إلى ثنائية باستخدام العتبة المحددة مسبقًا. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // حوّل الصورة إلى ثنائية باستخدام قيمة العتبة 127.
    // إذا كانت قيمة الرمادي المقابلة للبكسل أكبر من 127، سيتم تعيين قيمة 255 له، وإلا ستكون 0.
    rasterImage.binarizeFixed((byte) 127);
    rasterImage.save(dir + "sample.BinarizeFixed.png");
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


تحويل الصورة إلى ثنائية باستخدام عتبة Otsu


**Example: The following example binarizes a raster cached image with Otsu thresholding.**
المثال التالي يحول صورة مخزنة كراستر إلى ثنائية باستخدام عتبة أوتسو. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // حوّل الصورة إلى ثنائية باستخدام عتبة أوتسو.
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة المتكيفة لبرايدلي مع عتبة الصورة المتكاملة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s من البكسلات المتمركزة حول هذا البكسل. |
| windowSize | int | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm with the specified window size.**
المثال التالي يحول صورة مخزنة كراستر إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرادلي مع حجم النافذة المحدد. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // حوّل الصورة إلى ثنائية باستخدام فرق سطوع قدره 5.
    // السطوع هو فرق بين البكسل ومتوسط نافذة 10 × 10 من البكسلات المتمركزة حول هذا البكسل.
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة المتكيفة لبرايدلي مع عتبة الصورة المتكاملة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s من البكسلات المتمركزة حول هذا البكسل. |


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm.**
المثال التالي يحول صورة مخزنة كراستر إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرادلي. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // حوّل الصورة إلى ثنائية باستخدام فرق سطوع قدره 5.
    // السطوع هو فرق بين البكسل ومتوسط نافذة s × s من البكسلات المتمركزة حول هذا البكسل.
    // سيتم ضبط حجم النافذة تلقائيًا.
    rasterImage.binarizeBradley(5);
    rasterImage.save(dir + "sample.BinarizeBradley5.png");
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


ضبط السطوع للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightness | int | قيمة السطوع. |


**Example: The following example performs brightness correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // حدد قيمة السطوع. القيم المقبولة للسطوع تقع في النطاق [-255، 255].
    rasterImage.adjustBrightness(50);
    rasterImage.save(dir + "sample.AdjustBrightness.png");
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


تحسين التباين في الصورة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| contrast | float | قيمة التباين (في النطاق [-100؛ 100]) |


**Example: The following example performs contrast correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // حدد قيمة التباين. القيم المقبولة للتباين تقع في النطاق [-100f، 100f].
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


تصحيح جاما للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | float | معامل غاما للقناة الحمراء |
| gammaGreen | float | معامل غاما للقناة الخضراء |
| gammaBlue | float | معامل غاما للقناة الزرقاء |


**Example: The following example performs gamma-correction of a raster cached image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // تعيين معاملات غاما الفردية للقنوات الحمراء والخضراء والزرقاء.
    rasterImage.adjustGamma(1.5f, 2.5f, 3.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


تصحيح جاما للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| غاما | float | معامل غاما للقنوات الحمراء والخضراء والزرقاء |


**Example: The following example performs gamma-correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // تعيين معامل غاما للقنوات الحمراء والخضراء والزرقاء.
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


إدراج توقيع رقمي يعتمد على كلمة المرور المقدمة داخل الصورة باستخدام تقنية إخفاء المعلومات (steganography).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | java.lang.String | كلمة المرور (الحد الأدنى 4 رموز) المستخدمة لتوليد بيانات التوقيع الرقمي |


**Example: The example shows how to embed digital signature based on provided password into image pixel data.**

``` java
String imageFilePath = "ball.png";
String password = "veryStr0ngPassword";
try (Image image = Image.load(imageFilePath))
{
    image.embedDigitalSignature(password);
    image.save(outputPath);
}
```

### analyzePercentageDigitalSignature(String password) {#analyzePercentageDigitalSignature-java.lang.String-}
```
public int analyzePercentageDigitalSignature(String password)
```


يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | java.lang.String | كلمة المرور المستخدمة لاستخراج البيانات المدمجة. |

**Returns:**
int - قيمة النسبة المئوية للتشابه.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


ينفّذ فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والعتبة المقدمة.

--------------------

توفر هذه الطريقة أسرع كشف عن طريق الاستفادة من `GetSignPercentage`. بمجرد أن تفي البيانات المستخرجة بالحد المحدد، يتم تخطي خطوات الاستخراج الإضافية الهادفة إلى تحسين دقة الكشف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | java.lang.String | كلمة المرور للتحقق من التوقيع. |
| percentageThreshold | int | الحد (بالنسبة المئوية)[0-100] الذي يحدد ما إذا كانت الصورة تعتبر موقعة. إذا لم يتم تحديده، سيُطبق الحد الافتراضي (`75`). |

**Returns:**
boolean - صحيح إذا كانت الصورة موقعة، وإلا خاطئ.
