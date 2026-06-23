---
title: "RasterCachedMultippageImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "صورة نقطية متعددة الصفحات"
type: docs
weight: 90
url: /ar/java/com.aspose.imaging/rastercachedmultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class RasterCachedMultipageImage extends RasterCachedImage implements IMultipageImage
```

صورة نقطية متعددة الصفحات
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة. |
| [getWidth()](#getWidth--) | يحصل على عرض الصورة. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد بتات الصورة لكل بكسل. |
| [isCached()](#isCached--) | يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا. |
| [hasAlpha()](#hasAlpha--) | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا. |
| [hasTransparentColor()](#hasTransparentColor--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [getImageOpacity()](#getImageOpacity--) | يحصل على شفافية هذه الصورة. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على قيمة للون الخلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | يضبط قيمة للون الخلفية. |
| [getMetadata()](#getMetadata--) | يحصل على بيانات XMP من الإطار. |
| [getPageExportingAction()](#getPageExportingAction--) | يحصل على إجراء تصدير الصفحة. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | يضبط إجراء تصدير الصفحة. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | ضبط `brightness` للصورة. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | [Image](../../com.aspose.imaging/image) متباين |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | تصحيح جاما للصورة. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | تصحيح جاما للصورة. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | يمزج هذه النسخة من الصورة مع صورة `overlay`. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | إدراج توقيع رقمي بناءً على كلمة المرور المقدمة في كل صفحة من الصورة. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | يحسب نسبة التشابه بين البيانات المستخرجة وكلمة المرور الأصلية. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | ينفّذ فحصًا سريعًا لتحديد ما إذا كانت الصورة موقعة رقمياً، باستخدام كلمة المرور والعتبة المقدمة. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة المتكيفة لبرايدلي مع عتبة الصورة المتكاملة |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة المتكيفة لبرايدلي مع عتبة الصورة المتكاملة |
| [binarizeOtsu()](#binarizeOtsu--) | تحويل الصورة إلى ثنائية باستخدام عتبة Otsu |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | قص الصورة. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | قص الصورة مع الإزاحات. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | ينفّذ تمويهًا (dithering) على الصورة الحالية. |
| [grayscale()](#grayscale--) | تحويل الصورة إلى تمثيلها بتدرج الرمادي |
| [normalizeHistogram()](#normalizeHistogram--) | يُعَدِّل هيستوغرام الصورة \\u2014 يضبط قيم البكسل لاستخدام كامل النطاق المتاح. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | `RasterCachedMultipageImage.rotate` الصورة حول المركز. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | يدور، يقلب، أو يدور ويقلب جميع الصفحات. |
| [rotateFlipAll(int rotateFlip)](#rotateFlipAll-int-) | يدور ويقلب الكل. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | يُعيد تحجيم الصورة. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | يُعيد تحجيم الصورة. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | يستبدل جميع الألوان غير الشفافة بلون جديد ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | يفلتر المستطيل المحدد. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | يُعَدِّل الزاوية. |
| [cacheData()](#cacheData--) | يخزن البيانات بشكل خاص. |

## Example: The following example shows batch conversion before saving (exporting) Tiff images.

``` java
String fileName = "10MB_Tif.tif";
String inputFileName = fileName;

String outputFileNameTif = "output.tif";

//تم تنفيذ إمكانية التحويل الجماعي قبل حفظ (تصدير) صور Tiff.

try(com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(inputFileName))
{
    // تعيين عملية تحويل جماعي للصفحات
    tiffImage.setPageExportingAction(new PageExportingAction()
    {
        @Override
        public void invoke(int pageIndex, Image page)
        {
            // يشغّل جمع القمامة لتجنب تخزين القمامة غير الضرورية من الصفحات السابقة
            System.gc();

            ((com.aspose.imaging.RasterImage) page).rotate(90);
        }
    });

    tiffImage.save(outputFileNameTif);

    /* Attention! In batch mode all pages will be released in this line!
     If you want to further perform operations on the original image, you should reload it from the source to another instance. */
}
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على ارتفاع الصورة.

القيمة: ارتفاع الصورة.

**Returns:**
int - ارتفاع الصورة.
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض الصورة.

القيمة: عرض الصورة.

**Returns:**
int - عرض الصورة.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد بتات الصورة لكل بكسل.

القيمة: عدد البتات لكل بكسل في الصورة.

**Returns:**
int - عدد البتات لكل بكسل في الصورة.
### isCached() {#isCached--}
```
public boolean isCached()
```


يحصل على قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا.

القيمة: `true` إذا تم تخزين بيانات الصورة مؤقتًا؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت بيانات الصورة مخزنة مؤقتًا حاليًا.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على ألفا.

القيمة: `true` إذا كان لهذا الكائن ألفا؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان لهذا الكائن ألفا.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف.

--------------------

يتحقق هذا التنفيذ من قيمة `RasterImage.HasTransparentColor`([RasterImage.hasTransparentColor](../../com.aspose.imaging/rasterimage\#hasTransparentColor)/[RasterImage.setTransparentColor(boolean)](../../com.aspose.imaging/rasterimage\#setTransparentColor-boolean-)) للـ `DefaultPage`(\#getDefaultPage\_internalized.getDefaultPage\_internalized).

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت الصورة لها لون شفاف.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


يحصل على شفافية هذه الصورة.

القيمة: قيمة الشفافية بين 0.0 (شفافة تمامًا) و 1.0 (معتمة تمامًا).

**Returns:**
float - شفافية هذه الصورة.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل على قيمة للون الخلفية.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


يضبط قيمة للون الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | قيمة للون الخلفية. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


يحصل على بيانات XMP من الإطار.

القيمة: غلاف بيانات حزمة XMP

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - XMP data from frame.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


يحصل على إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرةً قبل حفظ كل صفحة.

القيمة: إجراء تصدير الصفحة.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


يضبط إجراء تصدير الصفحة. يرجى ملاحظة أن ضبط هذه الطريقة سيؤدي تلقائيًا إلى تحرير موارد الصفحة بعد تنفيذها. سيتم تنفيذها مباشرةً قبل حفظ كل صفحة.

القيمة: إجراء تصدير الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | إجراء تصدير الصفحة. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


ضبط `brightness` للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightness | int | قيمة السطوع. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) contrasting

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| contrast | float | قيمة التباين (في النطاق [-100؛ 100]) |

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

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


تصحيح جاما للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| غاما | float | معامل غاما للقنوات الحمراء والخضراء والزرقاء |

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

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


إدراج توقيع رقمي بناءً على كلمة المرور المقدمة في كل صفحة من الصورة.

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

--------------------

نظرًا لوجود صور متعددة الصفحات، النتيجة تمثل `MIDDLE AVERAGED signing percentage` المحسوبة

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

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كلمة المرور | java.lang.String | كلمة المرور للتحقق من التوقيع. |
|  | percentageThreshold | int | الحد (بالنسبة المئوية)[0-100] الذي يحدد ما إذا كانت الصورة تعتبر موقعة. إذا لم يتم تحديده، سيُطبق الحد الافتراضي (`75`). |

--------------------

توفر هذه الطريقة أسرع كشف عن طريق الاستفادة من `GetSignPercentage`. بمجرد أن تفي البيانات المستخرجة بالحد المحدد، يتم تخطي خطوات الاستخراج الإضافية الهادفة إلى تحسين دقة الكشف.

النتيجة هي `true` فقط إذا تم التعرف على جميع صفحات الصورة متعددة الصفحات كـ موقعة؛ وإلا تُعتبر الصورة غير موقعة. |

**Returns:**
boolean - صحيح إذا كانت الصورة موقعة، وإلا خاطئ.
### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | byte | قيمة العتبة. إذا كانت قيمة الرمادي المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة 255 لها، وإلا 0. |

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

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة المتكيفة لبرايدلي مع عتبة الصورة المتكاملة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s من البكسلات المتمركزة حول هذا البكسل. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


تحويل الصورة إلى ثنائية باستخدام عتبة Otsu

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


قص الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


قص الصورة مع الإزاحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | int | الإزاحة اليسرى. |
| rightShift | int | الإزاحة اليمنى. |
| topShift | int | الإزاحة العلوية. |
| bottomShift | int | الإزاحة السفلية. |

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

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


يُعَدِّل هيستوغرام الصورة \\u2014 يضبط قيم البكسل لاستخدام كامل النطاق المتاح.

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


`RasterCachedMultipageImage.rotate` الصورة حول المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resizeProportionally | boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى تُترك الأبعاد دون تغيير وتُدور فقط `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


يدور، يقلب، أو يدور ويقلب جميع الصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | نوع تدوير القليب. |

### rotateFlipAll(int rotateFlip) {#rotateFlipAll-int-}
```
public void rotateFlipAll(int rotateFlip)
```


يدور ويقلب الكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlip | int | قلب التدوير. |

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

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


يعيد تحجيم العرض بنسبة متناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| resizeType | int | نوع التحجيم. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


يعيد تحجيم العرض بنسبة متناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع التحجيم. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


يستبدل لونًا بآخر مع فرق مسموح به ويحافظ على قيمة ألفا الأصلية للحفاظ على حواف ناعمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| oldColorArgb | int | قيمة ARGB للون القديم التي سيتم استبدالها. |
| oldColorDiff | byte | الفرق المسموح به في اللون القديم لتمكين توسيع نغمة اللون المستبدل. |
| newColorArgb | int | قيمة ARGB للون الجديد لاستبدال اللون القديم به. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


يستبدل جميع الألوان غير الشفافة باللون الجديد ويحافظ على قيمة ألفا الأصلية لتجنب الحواف الخشنة. ملاحظة: إذا استخدمته على صور بدون شفافية، سيتم استبدال جميع الألوان بلون واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newColorArgb | int | قيمة ARGB للون الجديد لاستبدال الألوان غير الشفافة به. |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


يفلتر المستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | الخيارات. |

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


يُعَدِّل الزاوية إلى قيمتها الطبيعية. هذه الطريقة قابلة للتطبيق على مستندات النص الممسوحة ضوئيًا للتخلص من الانحراف في المسح. تستخدم هذه الطريقة الأساليب [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) و [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resizeProportionally | boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا) وإلا سيبقى الأبعاد دون تغيير وتُدوَّر محتويات الصورة الداخلية فقط. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### cacheData() {#cacheData--}
```
public void cacheData()
```


يخزن البيانات بشكل خاص.

