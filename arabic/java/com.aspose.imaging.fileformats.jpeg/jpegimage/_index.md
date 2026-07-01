---
title: "JpegImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "قم بالتلاعب بفعالية بصور JPEG النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا التي تدعم ملفات تعريف الألوان المتنوعة مثل RGB وCMYK، وتسمح بتخصيص عدد البتات لكل بكسل ودقة الصورة ومعالجة حاويات البيانات الوصفية EXIF وJFIF وXMP."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.jpeg/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public final class JpegImage extends RasterCachedImage implements IHasJpegExifData
```

قم بالتلاعب بفعالية بصور JPEG النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا، التي تدعم ملفات تعريف الألوان المتنوعة مثل RGB وCMYK، وتسمح بتخصيص عدد البتات لكل بكسل ودقة الصورة، ومعالجة حاويات البيانات الوصفية EXIF وJFIF وXMP. استمتع بالدوران التلقائي بناءً على بيانات الاتجاه واختر من مستويات ضغط مختلفة، بما في ذلك JPEG غير الفاقد، لتحقيق توازن مثالي بين جودة الصورة وحجم الملف لمشاريعك.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [JpegImage(String path)](#JpegImage-java.lang.String-) | تقوم فئة [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) بالبدء بسهولة عن طريق استدعاء المُنشئ الخاص بها مع معامل المسار المحدد. |
| [JpegImage(InputStream stream)](#JpegImage-java.io.InputStream-) | قم بتهيئة كائن صورة JPEG باستخدام فئة [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) مع معامل تدفق. |
| [JpegImage(RasterImage rasterImage)](#JpegImage-com.aspose.imaging.RasterImage-) | قم بتهيئة نسخة جديدة من فئة [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) باستخدام معامل صورة نقطية. |
| [JpegImage(int width, int height)](#JpegImage-int-int-) | أنشئ نسخة جديدة من فئة [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) باستخدام معاملات العرض والارتفاع المحددة. |
| [JpegImage(JpegOptions jpegOptions, int width, int height)](#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-) | قم بتهيئة كائن [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) جديد باستخدام خيارات JPEG المقدمة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | استرجع تنسيق الصورة بسهولة باستخدام هذه الخاصية. |
| [getJpegOptions()](#getJpegOptions--) | احصل على الوصول إلى خيارات JPEG المستخدمة أثناء إنشاء أو تحميل هذه النسخة من [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) بسهولة. |
| [getBitsPerPixel()](#getBitsPerPixel--) | استرجع عمق البكسل للصورة بسهولة باستخدام هذه الخاصية، مما يوفر نظرة على غنى تمثيل اللون أو التدرج الرمادي. |
| [getComment()](#getComment--) | قم بإدارة تعليقات ملف JPEG باستخدام هذه الخاصية، مما يتيح لك إضافة أو استرجاع التعليقات الوصفية المرتبطة بالصورة. |
| [setComment(String value)](#setComment-java.lang.String-) | قم بإدارة تعليقات ملف JPEG باستخدام هذه الخاصية، مما يتيح لك إضافة أو استرجاع التعليقات الوصفية المرتبطة بالصورة. |
| [getJpegExifData()](#getJpegExifData--) | يحصل على نسخة Exif. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | قم بإدارة بيانات EXIF باستخدام هذه الخاصية، مما يتيح لك إضافة أو استرجاع البيانات الوصفية المرتبطة بالصورة. |
| [getExifData()](#getExifData--) | يحصل على بيانات Exif؛ |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | يضبط بيانات Exif؛ |
| [getHeight()](#getHeight--) | استرجع ارتفاع الصورة بسهولة باستخدام هذه الخاصية. |
| [getHorizontalResolution()](#getHorizontalResolution--) | تمنحك هذه الخاصية الوصول إلى الدقة الأفقية لـ [RasterImage](../../com.aspose.imaging/rasterimage)، المقاسة بالبكسل لكل بوصة. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | تمنحك هذه الخاصية الوصول إلى الدقة الأفقية لـ [RasterImage](../../com.aspose.imaging/rasterimage)، المقاسة بالبكسل لكل بوصة. |
| [getJfif()](#getJfif--) | تتيح لك هذه الخاصية الوصول إلى بيانات JFIF (تنسيق تبادل ملفات JPEG) المرتبطة بصورة JPEG أو تعديلها. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | تتيح لك هذه الخاصية الوصول إلى بيانات JFIF (تنسيق تبادل ملفات JPEG) المرتبطة بصورة JPEG أو تعديلها. |
| [getRawDataFormat()](#getRawDataFormat--) | تسترجع هذه الخاصية تنسيق البيانات الخام للصورة، والذي يوضح كيفية هيكلة وترميز بيانات الصورة. |
| [getVerticalResolution()](#getVerticalResolution--) | تدير هذه الخاصية الدقة العمودية، المعبر عنها بالبكسل لكل بوصة، لـ [RasterImage](../../com.aspose.imaging/rasterimage) المرتبط. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | تدير هذه الخاصية الدقة العمودية، المعبر عنها بالبكسل لكل بوصة، لـ [RasterImage](../../com.aspose.imaging/rasterimage) المرتبط. |
| [getWidth()](#getWidth--) | تسترجع هذه الخاصية عرض الصورة، معبرًا عنه بالبكسل. |
| [getRgbColorProfile()](#getRgbColorProfile--) | ملف تعريف اللون RGB لصور JPEG بنظام CMYK وYCCK يضمن تحويلًا دقيقًا للألوان وتمثيلًا صحيحًا. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | ملف تعريف اللون RGB لصور JPEG بنظام CMYK وYCCK يضمن تحويلًا دقيقًا للألوان وتمثيلًا صحيحًا. |
| [getCmykColorProfile()](#getCmykColorProfile--) | ملف تعريف اللون CMYK المرتبط بصور JPEG بنظام CMYK وYCCK يضمن تحويلًا دقيقًا للألوان وموثوقية عالية. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | ملف تعريف اللون CMYK المرتبط بصور JPEG بنظام CMYK وYCCK يضمن تحويلًا دقيقًا للألوان وموثوقية عالية. |
| [getDestinationRgbColorProfile()](#getDestinationRgbColorProfile--) | يعد RGBColorProfile ضروريًا للتحويل الدقيق للألوان لصور JPEG بنظام CMYK وYCCK أثناء عملية الحفظ. |
| [setDestinationRgbColorProfile(StreamSource value)](#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | يعد RGBColorProfile ضروريًا للتحويل الدقيق للألوان لصور JPEG بنظام CMYK وYCCK أثناء عملية الحفظ. |
| [getDestinationCmykColorProfile()](#getDestinationCmykColorProfile--) | ملف تعريف اللون CMYK حيوي للتحويل الدقيق للألوان لصور JPEG بنظام CMYK وYCCK أثناء عملية الحفظ. |
| [setDestinationCmykColorProfile(StreamSource value)](#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | ملف تعريف اللون CMYK حيوي للتحويل الدقيق للألوان لصور JPEG بنظام CMYK وYCCK أثناء عملية الحفظ. |
| [getIgnoreEmbeddedColorProfile()](#getIgnoreEmbeddedColorProfile--) | يسترجع أو يعدل العلامة التي تشير إلى ما إذا كان ملف تعريف اللون المضمّن يتم تجاهله. |
| [setIgnoreEmbeddedColorProfile(boolean value)](#setIgnoreEmbeddedColorProfile-boolean-) | يسترجع أو يعدل العلامة التي تشير إلى ما إذا كان ملف تعريف اللون المضمّن يتم تجاهله. |
| [getOriginalOptions()](#getOriginalOptions--) | يحصل على خيارات الصورة الأصلية لهذا الكائن [Image](../../com.aspose.imaging/image). |
| [removeMetadata()](#removeMetadata--) | يزيل بيانات التعريف لهذا الكائن الصورة عن طريق تعيين قيم `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) و `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) إلى `null`. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | يحدد الدقة للصورة [RasterImage](../../com.aspose.imaging/rasterimage) المحددة، مما يضمن التحجيم والطباعة بدقة. |

## Example: The example shows how to load a JpegImage from a file.

``` java
String dir = "c:\\temp\\";

// حمّل صورة JPEG من ملف.
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(dir + "sample.jpg");
try {
    // قم ببعض معالجة الصورة.
    // احفظ إلى ملف JPEG آخر.
    jpegImage.save(dir + "sample.output.jpg");
} finally {
    jpegImage.dispose();
}
```


## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### JpegImage(String path) {#JpegImage-java.lang.String-}
```
public JpegImage(String path)
```


تبدأ فئة [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) بسهولة عن طريق استدعاء المُنشئ مع معامل المسار المحدد. يتيح هذا المُنشئ إنشاء صور JPEG بسلاسة، مما يضمن دمجًا سريعًا في مشاريعك بسهولة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مسار | java.lang.String | المسار لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

### JpegImage(InputStream stream) {#JpegImage-java.io.InputStream-}
```
public JpegImage(InputStream stream)
```


قم بتهيئة كائن صورة JPEG باستخدام فئة [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) مع معامل تدفق. يبسط هذا المُنشئ عملية التعامل مع صور JPEG، مقدماً نهجًا مباشرًا لدمجها في مشاريعك بسهولة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | التدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

### JpegImage(RasterImage rasterImage) {#JpegImage-com.aspose.imaging.RasterImage-}
```
public JpegImage(RasterImage rasterImage)
```


قم بتهيئة نسخة جديدة من فئة [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) باستخدام معامل صورة نقطية. يوفر هذا المُنشئ طريقة مريحة لإنشاء صور JPEG مباشرةً من الصور النقطية، مما يُبسّط سير العمل للتعامل مع صور JPEG في تطبيقاتك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة التي سيتم تهيئة بيانات البكسل واللوحة اللونية بها. |

### JpegImage(int width, int height) {#JpegImage-int-int-}
```
public JpegImage(int width, int height)
```


أنشئ نسخة جديدة من فئة [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) باستخدام معامل العرض والارتفاع المحددين. يتيح لك هذا المُنشئ إنشاء صور JPEG بأبعاد مخصصة، مما يمنحك مرونة في إدارة أحجام الصور في تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | عرض الصورة. |
| height | int | ارتفاع الصورة. |

### JpegImage(JpegOptions jpegOptions, int width, int height) {#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-}
```
public JpegImage(JpegOptions jpegOptions, int width, int height)
```


قم بتهيئة كائن [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) جديد باستخدام خيارات JPEG المقدمة. يمنحك هذا المُنشئ القدرة على تخصيص إعدادات مختلفة لصورة JPEG، مثل مستوى الضغط، الجودة، والمعلمات الإضافية، مما يوفر تحكمًا دقيقًا في تنسيق الصورة الناتج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | خيارات JPEG. |
| width | int | عرض الصورة. |
| height | int | ارتفاع الصورة. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


استرجع تنسيق الصورة بسهولة باستخدام هذه الخاصية. توفر نظرة قيمة على تنسيق الملف، مما يساعد في دمج سلس وفحوصات التوافق عبر مختلف المنصات والتطبيقات.

**Returns:**
long
### getJpegOptions() {#getJpegOptions--}
```
public JpegOptions getJpegOptions()
```


احصل على إمكانية الوصول إلى خيارات JPEG المستخدمة أثناء إنشاء أو تحميل هذا الكائن [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) بسهولة. تقدم هذه الخاصية تفاصيل قيمة حول الإعدادات المحددة المستخدمة، مما يمكّن المستخدمين من فهم وتكرار سير عمل معالجة الصور بفعالية. سواء كانت مستويات الضغط، إعدادات الجودة، أو معلمات أخرى، توفر هذه الخاصية رؤى أساسية لتعديل الصور بسلاسة.

**Returns:**
[JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) - The JPEG options.

**Example: The following example shows how to extract the header information from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = image.getJpegOptions();

    System.out.println("The number of bits per channel: " + jpegOptions.getBitsPerChannel());
    System.out.println("The max allowed size for all internal buffers: " + jpegOptions.getBufferSizeHint());
    System.out.println("The color type: " + jpegOptions.getColorType());
    System.out.println("The compression type: " + jpegOptions.getCompressionType());
    System.out.println("The image quality: " + jpegOptions.getQuality());

    if (jpegOptions.getResolutionSettings() != null) {
        System.out.println("The horizontal resolution: " + jpegOptions.getResolutionSettings().getHorizontalResolution());
        System.out.println("The vertical resolution: " + jpegOptions.getResolutionSettings().getVerticalResolution());
    }

    for (int i = 0; i < jpegOptions.getHorizontalSampling().length; i++) {
        System.out.printf("The sampling for component %s: %sx%s\r\n", i, jpegOptions.getHorizontalSampling()[i], jpegOptions.getVerticalSampling()[i]);
    }
} finally {
    image.dispose();
}

//المخرجات تبدو هكذا:
//عدد البتات لكل قناة: 8
//الحد الأقصى المسموح لحجم جميع المخازن الداخلية: 0
//نوع اللون: YCbCr
//نوع الضغط: Baseline
//جودة الصورة: 75
//العينة للمكوّن 0: 1x1
//العينة للمكوّن 1: 1x1
//العينة للمكوّن 2: 1x1
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


استرجع عمق البكسل للصورة بسهولة باستخدام هذه الخاصية، مما يوفر رؤى حول غنى تمثيل اللون أو التدرج الرمادي. سواء كانت صورة فوتوغرافية نابضة بالحياة أو توضيح أحادي اللون، تقدم هذه الخاصية معلومات حيوية حول تعقيد الصورة البصري.

**Returns:**
int - عدد بتات الصورة لكل بكسل.
### getComment() {#getComment--}
```
public String getComment()
```


إدارة تعليقات ملفات JPEG باستخدام هذه الخاصية، مما يتيح لك إضافة أو استرجاع تعليقات وصفية مرتبطة بالصورة. سواء كان ذلك بوضع وسوم للصور مع بيانات التعريف أو إلحاق سياق إضافي، توفر هذه الخاصية مرونة في تنظيم وتصنيف ملفات JPEG الخاصة بك.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


إدارة تعليقات ملفات JPEG باستخدام هذه الخاصية، مما يتيح لك إضافة أو استرجاع تعليقات وصفية مرتبطة بالصورة. سواء كان ذلك بوضع وسوم للصور مع بيانات التعريف أو إلحاق سياق إضافي، توفر هذه الخاصية مرونة في تنظيم وتصنيف ملفات JPEG الخاصة بك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegExifData() {#getJpegExifData--}
```
public JpegExifData getJpegExifData()
```


يحصل على نسخة Exif.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif instance.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


إدارة بيانات EXIF باستخدام هذه الخاصية، مما يتيح لك إضافة أو استرجاع بيانات التعريف المرتبطة بالصورة. سواء كان ذلك باستخراج معلومات حول إعدادات الكاميرا أو تعديل بيانات التعريف الحالية، توفر هذه الخاصية مرونة في إدارة حاوية بيانات EXIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


يحصل على بيانات Exif؛

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data;

**Example: The following example shows how to extract EXIF tags from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.exif.ExifData exifData = image.getExifData();

    System.out.println("The general EXIF data");
    System.out.println("------------------------------------------");
    if (exifData != null) {
        System.out.println("The EXIF version: " + exifData.getExifVersion());
        System.out.println("The camera serial number: " + exifData.getBodySerialNumber());
        System.out.println("The color space: " + exifData.getColorSpace());
        System.out.println("The brightness: " + exifData.getBrightnessValue());
        System.out.println("The contrast: " + exifData.getContrast());
        System.out.println("The gamma: " + exifData.getGamma());
        System.out.println("The sharpness: " + exifData.getSharpness());
        System.out.println("The aperture: " + exifData.getApertureValue());
        System.out.println("The exposure mode: " + exifData.getExposureMode());
        System.out.println("The exposure bias: " + exifData.getExposureBiasValue());
        System.out.println("The exposure time: " + exifData.getExposureTime());
        System.out.println("The focal length: " + exifData.getFocalLength());
        System.out.println("The focal plane resolution unit: " + exifData.getFocalPlaneResolutionUnit());
        System.out.println("The lens model: " + exifData.getLensModel());
        System.out.println("The shutter speed: " + exifData.getShutterSpeedValue());
    }

    System.out.println("The JPEG EXIF data");
    System.out.println("------------------------------------------");
    if (exifData instanceof com.aspose.imaging.exif.JpegExifData) {
        com.aspose.imaging.exif.JpegExifData jpegExifData = (com.aspose.imaging.exif.JpegExifData) exifData;

        System.out.println("The camera manufacturer: " + jpegExifData.getMake());
        System.out.println("The camera model: " + jpegExifData.getModel());
        System.out.println("The photometric interpretation: " + jpegExifData.getPhotometricInterpretation());
        System.out.println("The artist: " + jpegExifData.getArtist());
        System.out.println("The copyright: " + jpegExifData.getCopyright());
        System.out.println("The image description: " + jpegExifData.getImageDescription());
        System.out.println("The orientation: " + jpegExifData.getOrientation());
        System.out.println("The software: " + jpegExifData.getSoftware());
    }
} finally {
    image.dispose();
}

//المخرجات تبدو هكذا:
//بيانات EXIF العامة
//------------------------------------------
//إصدار EXIF: [B@163e4e87
//الرقم التسلسلي للكاميرا: 7100536
//مساحة اللون: SRgb
//السطوع:
//التباين: طبيعي
//جاما:
//الحدة: 0
//فتحة العدسة: 4.64(4643856 / 1000000)
//وضع التعرض: يدوي
//انحياز التعرض: 0.67(4 / 6)
//وقت التعرض: 0.01(1 / 160)
//البعد البؤري: 145.00(1450 / 10)
//وحدة دقة المستوى البؤري: سم
//نموذج العدسة: 70.0 - 200.0 مم f/ 4.0
//سرعة الغالق: 7.32(7321928 / 1000000)
//بيانات JPEG EXIF
//------------------------------------------
//شركة تصنيع الكاميرا: NIKON CORPORATION
//طراز الكاميرا: NIKON D5
//التفسير الضوئي: 0
//الفنان:
//حقوق النشر:
//وصف الصورة:
//الاتجاه: أعلى-يسار
//البرنامج: Adobe Photoshop Camera Raw 9.9 (Macintosh)
```

### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


يضبط بيانات Exif؛

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | بيانات Exif؛ |

### getHeight() {#getHeight--}
```
public int getHeight()
```


استرجع ارتفاع الصورة بسهولة باستخدام هذه الخاصية. فهي توفر وصولًا سريعًا إلى البُعد العمودي للصورة، مما يتيح لك تحديد حجمها ونسبة أبعادها بكفاءة دون الحاجة إلى حسابات معقدة أو طرق إضافية.

**Returns:**
int - ارتفاع الصورة بالبكسل.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


تتيح لك هذه الخاصية الوصول إلى الدقة الأفقية لـ [RasterImage](../../com.aspose.imaging/rasterimage)، المقاسة بالبكسل لكل بوصة. من خلال تعيين أو استرجاع هذه القيمة، يمكنك التحكم بدقة في دقة الصورة، وضمان توافقها مع متطلباتك الخاصة للجودة والوضوح.

**Returns:**
مزدوج - الدقة الأفقية.

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // احصل على الدقة الأفقية والعمودية لـ BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// الدقة الأفقية، بوحدة البكسل لكل بوصة: 300.0
// الدقة العمودية، بوحدة البكسل لكل بوصة: 300.0
// عيّن قيم الدقة إلى 96 نقطة في البوصة
// الدقة الأفقية، بوحدة البكسل لكل بوصة: 96.0
// الدقة العمودية، بوحدة البكسل لكل بوصة: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


تتيح لك هذه الخاصية الوصول إلى الدقة الأفقية لـ [RasterImage](../../com.aspose.imaging/rasterimage)، المقاسة بالبكسل لكل بوصة. من خلال تعيين أو استرجاع هذه القيمة، يمكنك التحكم بدقة في دقة الصورة، وضمان توافقها مع متطلباتك الخاصة للجودة والوضوح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الدقة الأفقية. |

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة `setResolution` لتحديث قيم الدقةتين في استدعاء واحد. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


تتيح لك هذه الخاصية الوصول إلى بيانات JFIF (تنسيق تبادل ملفات JPEG) المرتبطة بصورة JPEG أو تعديلها. JFIF هو تنسيق قياسي لتبادل الصور المضغوطة بتنسيق JPEG بين الحواسيب والأجهزة الأخرى. من خلال الحصول على هذه الخاصية أو تعيينها، يمكنك التفاعل مع بيانات JFIF، والتي قد تشمل معلومات مثل دقة الصورة، نسبة الأبعاد، والصورة المصغرة.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


تتيح لك هذه الخاصية الوصول إلى بيانات JFIF (تنسيق تبادل ملفات JPEG) المرتبطة بصورة JPEG أو تعديلها. JFIF هو تنسيق قياسي لتبادل الصور المضغوطة بتنسيق JPEG بين الحواسيب والأجهزة الأخرى. من خلال الحصول على هذه الخاصية أو تعيينها، يمكنك التفاعل مع بيانات JFIF، والتي قد تشمل معلومات مثل دقة الصورة، نسبة الأبعاد، والصورة المصغرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


تسترجع هذه الخاصية تنسيق البيانات الخام للصورة، والذي يوضح كيفية تنظيم البيانات المشفرة للصورة. فهم تنسيق البيانات الخام أمر أساسي لمعالجة أو تعديل بيانات الصورة بفعالية. فهو يوفر رؤى حول التمثيل الأساسي للصورة، مثل ما إذا كانت مضغوطة، أو مشفرة في مساحة لون معينة، أو مخزنة بتنسيق ملف محدد. يتيح لك الوصول إلى هذه الخاصية الحصول على معلومات قيمة حول بنية بيانات الصورة، مما يمكنك من تنفيذ عمليات أو تحسينات مختلفة مخصصة لتنسيقها المحدد.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


تدير هذه الخاصية الدقة العمودية، المعبر عنها بالبكسل لكل بوصة، لـ [RasterImage](../../com.aspose.imaging/rasterimage) المرتبط. تعديل هذه الدقة يؤثر على حجم وجودة الصورة عند طباعتها أو عرضها بحجم مادي ثابت. من خلال تعيين هذه الخاصية، تتحكم في كثافة تجميع بكسلات الصورة عموديًا، مما يؤثر على حدتها ووضوحها العام.

**Returns:**
مزدوج - الدقة العمودية.

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 72 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقةتين في استدعاء واحد.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // احصل على الدقة الأفقية والعمودية لـ BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// الدقة الأفقية، بوحدة البكسل لكل بوصة: 300.0
// الدقة العمودية، بوحدة البكسل لكل بوصة: 300.0
// عيّن قيم الدقة إلى 96 نقطة في البوصة
// الدقة الأفقية، بوحدة البكسل لكل بوصة: 96.0
// الدقة العمودية، بوحدة البكسل لكل بوصة: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


تدير هذه الخاصية الدقة العمودية، المعبر عنها بالبكسل لكل بوصة، لـ [RasterImage](../../com.aspose.imaging/rasterimage) المرتبط. تعديل هذه الدقة يؤثر على حجم وجودة الصورة عند طباعتها أو عرضها بحجم مادي ثابت. من خلال تعيين هذه الخاصية، تتحكم في كثافة تجميع بكسلات الصورة عموديًا، مما يؤثر على حدتها ووضوحها العام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | double | الدقة العمودية. |

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 72 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيم الدقةتين في استدعاء واحد. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


تسترجع هذه الخاصية عرض الصورة، معبرًا عنه بالبكسل. فهي توفر معلومات أساسية حول أبعاد الصورة، مما يتيح عرضًا، تعديلًا أو عرضًا دقيقًا لبيانات الصورة.

**Returns:**
int - عرض الصورة بالبكسل.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


ملف تعريف اللون RGB لصور JPEG بنظام CMYK وYCCK يضمن تحويلًا دقيقًا للألوان وتمثيلًا صحيحًا. يجب إقرانه بملف تعريف اللون CMYKColorProfile للحفاظ على التناسق والصدق في عرض الألوان. هذا الاقتران ضروري للتطبيقات التي تتطلب إدارة ألوان دقيقة وإعادة إنتاج الصور، مما يضمن تفسير بيانات RGB وعرضها بشكل صحيح.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


ملف تعريف اللون RGB لصور JPEG بنظام CMYK وYCCK يضمن تحويلًا دقيقًا للألوان وتمثيلًا صحيحًا. يجب إقرانه بملف تعريف اللون CMYKColorProfile للحفاظ على التناسق والصدق في عرض الألوان. هذا الاقتران ضروري للتطبيقات التي تتطلب إدارة ألوان دقيقة وإعادة إنتاج الصور، مما يضمن تفسير بيانات RGB وعرضها بشكل صحيح.

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


ملف تعريف اللون CMYK المرتبط بصور JPEG بنظام CMYK وYCCK يضمن تحويلًا دقيقًا للألوان وموثوقية. يعمل بالتعاون مع RGBColorProfile لضمان تمثيل ألوان دقيق عبر مختلف الأجهزة والتطبيقات. هذا الاقتران أساسي للحفاظ على التناسق في عرض الألوان وتحقيق جودة صورة مثالية.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


ملف تعريف اللون CMYK المرتبط بصور JPEG بنظام CMYK وYCCK يضمن تحويلًا دقيقًا للألوان وموثوقية. يعمل بالتعاون مع RGBColorProfile لضمان تمثيل ألوان دقيق عبر مختلف الأجهزة والتطبيقات. هذا الاقتران أساسي للحفاظ على التناسق في عرض الألوان وتحقيق جودة صورة مثالية.

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

### getDestinationRgbColorProfile() {#getDestinationRgbColorProfile--}
```
public StreamSource getDestinationRgbColorProfile()
```


ملف تعريف اللون RGBColorProfile ضروري للتحويل الدقيق للألوان في صور JPEG بنظام CMYK وYCCK أثناء عملية الحفظ. عند إقرانه بملف تعريف اللون CMYKColorProfile، يضمن عرض الألوان بشكل صحيح ويحافظ على التناسق عبر مختلف الأجهزة والتطبيقات. هذا الجمع أساسي للحفاظ على تمثيل الألوان المقصود وتحقيق مخرجات صورة عالية الجودة.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationRgbColorProfile(StreamSource value) {#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationRgbColorProfile(StreamSource value)
```


ملف تعريف اللون RGBColorProfile ضروري للتحويل الدقيق للألوان في صور JPEG بنظام CMYK وYCCK أثناء عملية الحفظ. عند إقرانه بملف تعريف اللون CMYKColorProfile، يضمن عرض الألوان بشكل صحيح ويحافظ على التناسق عبر مختلف الأجهزة والتطبيقات. هذا الجمع أساسي للحفاظ على تمثيل الألوان المقصود وتحقيق مخرجات صورة عالية الجودة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getDestinationCmykColorProfile() {#getDestinationCmykColorProfile--}
```
public StreamSource getDestinationCmykColorProfile()
```


ملف تعريف اللون CMYK ضروري للتحويل الدقيق للألوان في صور JPEG بنظام CMYK وYCCK أثناء عملية الحفظ. يعمل بالتوازي مع RGBColorProfile لضمان تمثيل صحيح للألوان، مع الحفاظ على التناسق والجودة عبر مختلف الأجهزة والبرمجيات. هذا التزامن أساسي لتحقيق عرض ألوان دقيق وموثوق في الصور المحفوظة نهائيًا.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationCmykColorProfile(StreamSource value) {#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationCmykColorProfile(StreamSource value)
```


ملف تعريف اللون CMYK ضروري للتحويل الدقيق للألوان في صور JPEG بنظام CMYK وYCCK أثناء عملية الحفظ. يعمل بالتوازي مع RGBColorProfile لضمان تمثيل صحيح للألوان، مع الحفاظ على التناسق والجودة عبر مختلف الأجهزة والبرمجيات. هذا التزامن أساسي لتحقيق عرض ألوان دقيق وموثوق في الصور المحفوظة نهائيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getIgnoreEmbeddedColorProfile() {#getIgnoreEmbeddedColorProfile--}
```
public boolean getIgnoreEmbeddedColorProfile()
```


تسترجع أو تعدل العلامة التي تشير إلى ما إذا كان ملف تعريف اللون المدمج سيتم تجاهله. من خلال تعيين هذه العلامة، يمكن للمستخدمين تحديد ما إذا كان يجب استخدام ملف تعريف اللون الافتراضي بدلاً من المدمج. يضمن هذا الخيار تحكمًا أكبر في إدارة الألوان، مما يسهل ضبط التناسق والتوافق عبر مختلف المنصات والتطبيقات.

**Returns:**
boolean
### setIgnoreEmbeddedColorProfile(boolean value) {#setIgnoreEmbeddedColorProfile-boolean-}
```
public void setIgnoreEmbeddedColorProfile(boolean value)
```


تسترجع أو تعدل العلامة التي تشير إلى ما إذا كان ملف تعريف اللون المدمج سيتم تجاهله. من خلال تعيين هذه العلامة، يمكن للمستخدمين تحديد ما إذا كان يجب استخدام ملف تعريف اللون الافتراضي بدلاً من المدمج. يضمن هذا الخيار تحكمًا أكبر في إدارة الألوان، مما يسهل ضبط التناسق والتوافق عبر مختلف المنصات والتطبيقات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


يحصل على خيارات الصورة الأصلية لهذا الكائن [Image](../../com.aspose.imaging/image).

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - A clone of original image options.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


يزيل بيانات التعريف لهذا الكائن الصورة عن طريق تعيين قيم `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) و `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) إلى `null`.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


يحدد الدقة لـ [RasterImage](../../com.aspose.imaging/rasterimage) المحدد، مما يضمن قدرة دقيقة على التحجيم والطباعة. تمكّن هذه الطريقة المستخدمين من تعديل دقة الصورة لتتناسب مع متطلباتهم الخاصة، سواء للعرض الرقمي أو النسخ المادي. من خلال تعيين الدقة، يمكن للمستخدمين تحسين جودة الصورة وضمان التوافق مع مختلف أجهزة الإخراج والوسائط، مما يعزز التجربة البصرية العامة وقابلية استخدام الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dpiX | double | الدقة الأفقية، بوحدة النقاط لكل بوصة، لـ `RasterImage`. |
| dpiY | double | الدقة العمودية، بوحدة النقاط لكل بوصة، لـ `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // احصل على الدقة الأفقية والعمودية لـ BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// الدقة الأفقية، بوحدة البكسل لكل بوصة: 300.0
// الدقة العمودية، بوحدة البكسل لكل بوصة: 300.0
// عيّن قيم الدقة إلى 96 نقطة في البوصة
// الدقة الأفقية، بوحدة البكسل لكل بوصة: 96.0
// الدقة العمودية، بوحدة البكسل لكل بوصة: 96.0
```

