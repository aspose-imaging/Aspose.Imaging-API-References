---
title: "JpegOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "إنشاء صور JPEG عالية الجودة بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا التي توفر مستويات ضغط قابلة للتعديل لتحسين حجم التخزين دون التضحية بجودة الصورة."
type: docs
weight: 26
url: /ar/java/com.aspose.imaging.imageoptions/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public class JpegOptions extends ImageOptionsBase implements IHasJpegExifData
```

إنشاء صور JPEG عالية الجودة بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا، التي توفر مستويات ضغط قابلة للتعديل لتحسين حجم التخزين دون التضحية بجودة الصورة. استفد من الدعم لأنواع مختلفة من الضغط، والترميز شبه غير الفاقد، وملفات تعريف الألوان RGB وCMYK، بالإضافة إلى بيانات الصور EXIF وJFIF، وحاويات XMP، مما يضمن خيارات متعددة وقابلة للتخصيص لاحتياجات إنشاء الصور الخاصة بك.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | يُنشئ مثيلًا جديدًا من الفئة `JpegOptions`. |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-) | يُنشئ مثيلًا جديدًا من الفئة `JpegOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | يحصل على حد تخصيص الذاكرة الافتراضي. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | يضبط حد تخصيص الذاكرة الافتراضي. |
| [getJfif()](#getJfif--) | يحصل على الـ jfif. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | يضبط الـ jfif. |
| [getComment()](#getComment--) | يحصل على تعليق ملف jpeg. |
| [setComment(String value)](#setComment-java.lang.String-) | يضبط تعليق ملف jpeg. |
| [getExifData()](#getExifData--) | يحصل على حاوية بيانات Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | يضبط بيانات Exif. |
| [getJpegExifData()](#getJpegExifData--) | احصل على حاوية بيانات Exif. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | احصل أو اضبط حاوية بيانات Exif |
| [getCompressionType()](#getCompressionType--) | يحصل على نوع الضغط. |
| [setCompressionType(int value)](#setCompressionType-int-) | يضبط نوع الضغط. |
| [getColorType()](#getColorType--) | يحصل على نوع اللون لصورة jpeg. |
| [setColorType(int value)](#setColorType-int-) | يضبط نوع اللون لصورة jpeg. |
| [getBitsPerChannel()](#getBitsPerChannel--) | يحصل على عدد البتات لكل قناة في صورة jpeg غير مضغوطة. |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | يضبط عدد البتات لكل قناة في صورة jpeg غير مضغوطة. |
| [getQuality()](#getQuality--) | يحصل على جودة الصورة. |
| [setQuality(int value)](#setQuality-int-) | يضبط جودة الصورة. |
| [getScaledQuality()](#getScaledQuality--) | الجودة المُقاسة. |
| [getRdOptSettings()](#getRdOptSettings--) | يحصل على إعدادات مُحسّن RD. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-) | يضبط إعدادات مُحسّن RD. |
| [getRgbColorProfile()](#getRgbColorProfile--) | ملف تعريف اللون RGB الوجهة لصور jpeg بنظام CMYK. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | ملف تعريف اللون RGB الوجهة لصور jpeg بنظام CMYK. |
| [getCmykColorProfile()](#getCmykColorProfile--) | ملف تعريف اللون CMYK الوجهة لصور jpeg بنظام CMYK. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | ملف تعريف اللون CMYK الوجهة لصور jpeg بنظام CMYK. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | يحصل على حد الفرق في JPEG-LS للترميز شبه غير فقداني (معامل NEAR من مواصفة JPEG-LS). |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | يضبط حد الفرق في JPEG-LS للترميز شبه غير فقداني (معامل NEAR من مواصفة JPEG-LS). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | يحصل على وضع التداخل في JPEG-LS. |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | يضبط وضع التداخل في JPEG-LS. |
| [getJpegLsPreset()](#getJpegLsPreset--) | يحصل على معلمات الإعداد المسبق لـ JPEG-LS. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-) | يضبط معلمات الإعداد المسبق لـ JPEG-LS. |
| [getHorizontalSampling()](#getHorizontalSampling--) | يحصل على التقسيمات الفرعية الأفقية لكل مكوّن. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | يضبط التقسيمات الفرعية الأفقية لكل مكوّن. |
| [getVerticalSampling()](#getVerticalSampling--) | يحصل على التقسيمات الفرعية العمودية لكل مكوّن. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | يضبط التقسيمات الفرعية العمودية لكل مكوّن. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | يحصل على وضع تقريب العينة لتلائم قيمة 8‑بت مع قيمة n‑بت. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | يضبط وضع تقريب العينة لتلائم قيمة 8‑بت مع قيمة n‑بت. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | يحصل على قيمة تشير إلى ما إذا كان يجب خلط مكوّنات الأحمر والأخضر والأزرق مع لون الخلفية، إذا كان قناة ألفا موجودة. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب خلط مكوّنات الأحمر والأخضر والأزرق مع لون الخلفية، إذا كان قناة ألفا موجودة. |
| [getResolutionUnit()](#getResolutionUnit--) | يحصل على وحدة الدقة. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | يضبط وحدة الدقة. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
يوضح هذا المثال استخدام فئات مختلفة من مساحة الأسماء SaveOptions لأغراض التصدير. يتم تحميل صورة من نوع Gif إلى مثيل من الفئة Image ثم تُصدَّر إلى عدة صيغ.
``` java
String dir = "c:\\temp\\";

//حمّل صورة موجودة (من نوع Gif) في مثيل من الفئة Image.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //تصدير إلى تنسيق ملف BMP باستخدام الخيارات الافتراضية.
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //تصدير إلى تنسيق ملف JPEG باستخدام الخيارات الافتراضية.
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //تصدير إلى تنسيق ملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //تصدير إلى تنسيق ملف TIFF باستخدام الخيارات الافتراضية.
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to JPEG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.jpeg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.JpegOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // تصدير الصفحتين الأوليتين فقط. في الواقع، سيتم تحويل صفحة واحدة فقط إلى نقطية لأن JPEG ليس تنسيقًا متعدد الصفحات.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


يُنشئ مثيلًا جديدًا من الفئة `JpegOptions`.

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


يُنشئ مثيلًا جديدًا من الفئة `JpegOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | خيارات JPEG. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


يحصل على حد تخصيص الذاكرة الافتراضي.

**Returns:**
int - حد تخصيص الذاكرة الافتراضي.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


يضبط حد تخصيص الذاكرة الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | حد تخصيص الذاكرة الافتراضي. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


يحصل على الـ jfif.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


يضبط الـ jfif.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getComment() {#getComment--}
```
public String getComment()
```


يحصل على تعليق ملف jpeg.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


يضبط تعليق ملف jpeg.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


يحصل على حاوية بيانات Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data container.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public final void setExifData(ExifData value)
```


يضبط بيانات Exif.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | بيانات Exif. |

### getJpegExifData() {#getJpegExifData--}
```
public final JpegExifData getJpegExifData()
```


احصل على حاوية بيانات Exif.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data container.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


احصل أو اضبط حاوية بيانات Exif

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


يحصل على نوع الضغط.

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


يضبط نوع الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة JPEG بحجم 100×100 بكسل.
// استخدم خيارات إضافية لتحديد معلمات الصورة المطلوبة.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// عدد البتات لكل قناة هو 8, 8, 8 للمكوّنات Y, Cr, Cb على التوالي.
createOptions.setBitsPerChannel((byte) 8);

// حدد نوع الضغط المتدرج.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// حدد جودة الصورة. إنها قيمة بين 1 و 100.
createOptions.setQuality(100);

// حدد الدقة الأفقية/العمودية إلى 96 نقطة في البوصة.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// هذا خيار قياسي لصور JPEG.
// يمكن تقليل عرض النطاق، تقليل العينات، وضغط مكوّنين اللون (Cb و Cr).
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // املأ الصورة بتدرج رمادي
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // حفظ إلى ملف.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getColorType() {#getColorType--}
```
public int getColorType()
```


يحصل على نوع اللون لصورة jpeg.

**Returns:**
int

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة JPEG بحجم 100×100 بكسل.
// استخدم خيارات إضافية لتحديد معلمات الصورة المطلوبة.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// عدد البتات لكل قناة هو 8, 8, 8 للمكوّنات Y, Cr, Cb على التوالي.
createOptions.setBitsPerChannel((byte) 8);

// حدد نوع الضغط المتدرج.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// حدد جودة الصورة. إنها قيمة بين 1 و 100.
createOptions.setQuality(100);

// حدد الدقة الأفقية/العمودية إلى 96 نقطة في البوصة.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// هذا خيار قياسي لصور JPEG.
// يمكن تقليل عرض النطاق، تقليل العينات، وضغط مكوّنين اللون (Cb و Cr).
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // املأ الصورة بتدرج رمادي
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // حفظ إلى ملف.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


يضبط نوع اللون لصورة jpeg.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// حمّل صورة BMP من ملف.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // قم ببعض معالجة الصورة.

    // استخدم خيارات إضافية لتحديد معلمات الصورة المطلوبة.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // عدد البتات لكل قناة هو 8.
    // عند استخدام لوحة ألوان، يتم تخزين فهرس اللون في بيانات الصورة بدلاً من اللون نفسه.
    saveOptions.setBitsPerChannel((byte) 8);

    // حدد نوع الضغط المتدرج.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // حدد جودة الصورة. إنها قيمة بين 1 و 100.
    saveOptions.setQuality(100);

    // حدد الدقة الأفقية/العمودية إلى 96 نقطة في البوصة.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // إذا كانت الصورة المصدر ملونة، فسيتم تحويلها إلى تدرجات الرمادي.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // استخدم لوحة ألوان لتقليل حجم الإخراج.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


يحصل على عدد البتات لكل قناة لصورة JPEG غير مضغوطة. الآن ندعم من 2 إلى 8 بتات لكل قناة.

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


يضبط عدد البتات لكل قناة لصورة JPEG غير مضغوطة. الآن ندعم من 2 إلى 8 بتات لكل قناة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة JPEG بحجم 100×100 بكسل.
// استخدم خيارات إضافية لتحديد معلمات الصورة المطلوبة.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// عدد البتات لكل قناة هو 8, 8, 8 للمكوّنات Y, Cr, Cb على التوالي.
createOptions.setBitsPerChannel((byte) 8);

// حدد نوع الضغط المتدرج.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// حدد جودة الصورة. إنها قيمة بين 1 و 100.
createOptions.setQuality(100);

// حدد الدقة الأفقية/العمودية إلى 96 نقطة في البوصة.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// هذا خيار قياسي لصور JPEG.
// يمكن تقليل عرض النطاق، تقليل العينات، وضغط مكوّنين اللون (Cb و Cr).
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // املأ الصورة بتدرج رمادي
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // حفظ إلى ملف.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getQuality() {#getQuality--}
```
public int getQuality()
```


يحصل على جودة الصورة.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


يضبط جودة الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة JPEG بحجم 100×100 بكسل.
// استخدم خيارات إضافية لتحديد معلمات الصورة المطلوبة.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// عدد البتات لكل قناة هو 8, 8, 8 للمكوّنات Y, Cr, Cb على التوالي.
createOptions.setBitsPerChannel((byte) 8);

// حدد نوع الضغط المتدرج.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// حدد جودة الصورة. إنها قيمة بين 1 و 100.
createOptions.setQuality(100);

// حدد الدقة الأفقية/العمودية إلى 96 نقطة في البوصة.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// هذا خيار قياسي لصور JPEG.
// يمكن تقليل عرض النطاق، تقليل العينات، وضغط مكوّنين اللون (Cb و Cr).
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // املأ الصورة بتدرج رمادي
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // حفظ إلى ملف.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


الجودة المُقاسة.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


يحصل على إعدادات مُحسّن RD.

**Returns:**
[RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


يضبط إعدادات مُحسّن RD.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) | إعدادات مُحسّن RD. |

### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


ملف تعريف اللون RGB الوجهة لصور JPEG بنظام CMYK. يُستخدم لحفظ الصور. يجب أن يكون مقترناً بـ CMYKColorProfile للتحويل اللوني الصحيح.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


ملف تعريف اللون RGB الوجهة لصور JPEG بنظام CMYK. يُستخدم لحفظ الصور. يجب أن يكون مقترناً بـ CMYKColorProfile للتحويل اللوني الصحيح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
المثال التالي يقوم بتحميل ملف PNG وحفظه كصورة JPEG بنظام CMYK باستخدام ملف ICC مخصص. ثم يقوم بتحميل صورة JPEG بنظام CMYK وحفظها مرة أخرى كملف PNG. يتم تحويل الألوان من RGB إلى CMYK ومن CMYK إلى RGB باستخدام ملفات ICC مخصصة.
``` java
String dir = "c:\\temp\\";

// تحميل PNG وحفظه كـ CMYK JPEG
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // استخدام ملفات ICC مخصصة
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// تحميل CMYK JPEG وحفظه كـ PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // استخدام ملفات ICC مخصصة
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


ملف تعريف اللون CMYK الوجهة لصور JPEG بنظام CMYK. يُستخدم لحفظ الصور. يجب أن يكون مقترناً بـ RGBColorProfile للتحويل اللوني الصحيح.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


ملف تعريف اللون CMYK الوجهة لصور JPEG بنظام CMYK. يُستخدم لحفظ الصور. يجب أن يكون مقترناً بـ RGBColorProfile للتحويل اللوني الصحيح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
المثال التالي يقوم بتحميل ملف PNG وحفظه كصورة JPEG بنظام CMYK باستخدام ملف ICC مخصص. ثم يقوم بتحميل صورة JPEG بنظام CMYK وحفظها مرة أخرى كملف PNG. يتم تحويل الألوان من RGB إلى CMYK ومن CMYK إلى RGB باستخدام ملفات ICC مخصصة.
``` java
String dir = "c:\\temp\\";

// تحميل PNG وحفظه كـ CMYK JPEG
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // استخدام ملفات ICC مخصصة
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// تحميل CMYK JPEG وحفظه كـ PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // استخدام ملفات ICC مخصصة
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


يحصل على حد الفرق في JPEG-LS للترميز شبه غير فقداني (معامل NEAR من مواصفة JPEG-LS).

**Returns:**
int
### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


يضبط حد الفرق في JPEG-LS للترميز شبه غير فقداني (معامل NEAR من مواصفة JPEG-LS).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


يحصل على وضع التداخل في JPEG-LS.

**Returns:**
int
### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


يضبط وضع التداخل في JPEG-LS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


يحصل على معلمات الإعداد المسبق لـ JPEG-LS.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters)
### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


يضبط معلمات الإعداد المسبق لـ JPEG-LS.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


يحصل على التقسيمات الفرعية الأفقية لكل مكوّن.

**Returns:**
byte[]
### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


يضبط التقسيمات الفرعية الأفقية لكل مكوّن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


يحصل على التقسيمات الفرعية العمودية لكل مكوّن.

**Returns:**
byte[]
### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


يضبط التقسيمات الفرعية العمودية لكل مكوّن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


يحصل على وضع تقريب العينة لتناسب قيمة 8-بت مع قيمة n-بت. `P:JpegOptions.BitsPerChannel`

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


يضبط وضع تقريب العينة لتناسب قيمة 8-بت مع قيمة n-بت. `P:JpegOptions.BitsPerChannel`

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


يحصل على قيمة تشير إلى ما إذا كان يجب خلط مكوّنات الأحمر والأخضر والأزرق مع لون الخلفية، إذا كان قناة ألفا موجودة.

**Returns:**
boolean
### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يجب خلط مكوّنات الأحمر والأخضر والأزرق مع لون الخلفية، إذا كان قناة ألفا موجودة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


يحصل على وحدة الدقة.

**Returns:**
byte - وحدة الدقة.

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة JPEG بحجم 100×100 بكسل.
// استخدم خيارات إضافية لتحديد معلمات الصورة المطلوبة.
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// عدد البتات لكل قناة هو 8, 8, 8 للمكوّنات Y, Cr, Cb على التوالي.
createOptions.setBitsPerChannel((byte) 8);

// حدد نوع الضغط المتدرج.
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// حدد جودة الصورة. إنها قيمة بين 1 و 100.
createOptions.setQuality(100);

// حدد الدقة الأفقية/العمودية إلى 96 نقطة في البوصة.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// هذا خيار قياسي لصور JPEG.
// يمكن تقليل عرض النطاق، تقليل العينات، وضغط مكوّنين اللون (Cb و Cr).
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // املأ الصورة بتدرج رمادي
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // حفظ إلى ملف.
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


يضبط وحدة الدقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte | وحدة الدقة. |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// حمّل صورة BMP من ملف.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // قم ببعض معالجة الصورة.

    // استخدم خيارات إضافية لتحديد معلمات الصورة المطلوبة.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // عدد البتات لكل قناة هو 8.
    // عند استخدام لوحة ألوان، يتم تخزين فهرس اللون في بيانات الصورة بدلاً من اللون نفسه.
    saveOptions.setBitsPerChannel((byte) 8);

    // حدد نوع الضغط المتدرج.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // حدد جودة الصورة. إنها قيمة بين 1 و 100.
    saveOptions.setQuality(100);

    // حدد الدقة الأفقية/العمودية إلى 96 نقطة في البوصة.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // إذا كانت الصورة المصدر ملونة، فسيتم تحويلها إلى تدرجات الرمادي.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // استخدم لوحة ألوان لتقليل حجم الإخراج.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

