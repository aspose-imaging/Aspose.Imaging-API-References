---
title: "DngImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "واجهة برمجة التطبيقات لمعالجة تنسيق ملف الصورة الرقمية السلبية DNG Digital Negative المستخدم في احتياجات التصوير الفوتوغرافي الرقمي من خلال توفير دعم شامل للملفات الخام والبيانات الوصفية."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.dng/dngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DngImage extends RasterCachedImage
```

واجهة برمجة التطبيقات لمعالجة تنسيق ملف الصورة DNG (Digital Negative) المستخدم في احتياجات التصوير الفوتوغرافي الرقمي من خلال توفير دعم شامل للملفات الخام والبيانات الوصفية. صُممت للاستخدام مع الكاميرات الرقمية من مختلف الشركات المصنعة، وتمكن المطورين من تعديل جوانب مثل عدد البتات لكل بكسل، واستخراج البيانات الداخلية، وضبط توازن الصورة بكفاءة. مع إمكانيات تحديث وحفظ بيانات الصورة بسلاسة، تُتيح هذه الواجهة للمطورين العمل مع ملفات DNG، مما يضمن نتائج عالية الجودة وخيارات معالجة متعددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DngImage()](#DngImage--) | أنشئ مثيلاً جديدًا للفئة [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) بسهولة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | اكتشف عدد البتات لكل بكسل في الصورة بسهولة باستخدام هذه الخاصية. |
| [getHeight()](#getHeight--) | احصل على ارتفاع الصورة باستخدام هذه الخاصية. |
| [getWidth()](#getWidth--) | احصل على عرض الصورة باستخدام هذه الخاصية. |
| [getFileFormat()](#getFileFormat--) | حدد تنسيق ملف صورتك باستخدام هذه الخاصية. |
| [getImgData()](#getImgData--) | إدارة بيانات الصورة باستخدام هذه الخاصية. |
| [setImgData(RawData value)](#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-) | إدارة بيانات الصورة باستخدام هذه الخاصية. |

## Example: This example shows how to load a DNG image from a file, print its properties and save it to PNG.

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "test.dng");
try {
    com.aspose.imaging.fileformats.dng.DngImage dngImage = (com.aspose.imaging.fileformats.dng.DngImage) image;
    com.aspose.imaging.fileformats.dng.decoder.RawData rawData = dngImage.getImgData();
    com.aspose.imaging.fileformats.dng.decoder.ImageParameters parameters = rawData.getImageDataParameters();
    if (parameters != null) {
        System.out.println("The camera manufacturer:              " + parameters.getCameraManufacturer());
        System.out.println("The camera model:                     " + parameters.getModel());
        System.out.println("The colors count:                     " + parameters.getColorsCount());
        System.out.println("The colors description:               " + parameters.getDescription());
        System.out.println("The DNG version:                      " + parameters.getDngVersion());
        System.out.println("The number of RAW images in the file: " + parameters.getRawCount());
        System.out.println("The software:                         " + parameters.getSoftware());
        System.out.println("The order of the color pixels:        " + Long.toBinaryString(parameters.getFilters()));

        String[] translationCfaDng = parameters.getTranslationCfaDng();
        if (translationCfaDng != null) {
            System.out.printf("The translation array for CFA mosaic %s:\r\n", translationCfaDng.length);
            for (String s : translationCfaDng) {
                System.out.printf("- %s\r\n", s);
            }
        }
    }

    com.aspose.imaging.fileformats.dng.decoder.ImageOtherParameters otherParameters = rawData.getImageOtherParameters();
    if (otherParameters != null) {
        // تحويل الطابع الزمني إلى سلسلة قابلة للقراءة للإنسان.
        //java.text.SimpleDateFormat sf = new java.text.SimpleDateFormat("yyyy-MM-dd");
        java.util.Date date = new java.util.Date(otherParameters.getTimestamp());
        //System.out.println(sf.format(date));

        System.out.printf("The aperture:                         " + otherParameters.getAperture());
        System.out.printf("The description:                      " + otherParameters.getDescription());
        System.out.printf("The focal length:                     " + otherParameters.getFocalLength());
        System.out.printf("The ISO sensitivity:                  " + otherParameters.getIsoSpeed());
        System.out.printf("The serial number of the image:       " + otherParameters.getShotOrder());
        System.out.printf("The shutter speed:                    " + otherParameters.getShutterSpeed());
        System.out.printf("The date of shooting:                 " + date);
    }

    // تصدير إلى PNG باستخدام الخيارات الافتراضية.
    dngImage.save(dir + "test.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

// شركة تصنيع الكاميرا:              Leica
// طراز الكاميرا:                     M8 Digital Camera
// عدد الألوان:                     3
// وصف الألوان:               RGBG
// إصدار DNG:                      16777216
// عدد صور RAW في الملف: 1
// البرنامج:                         1.107
// ترتيب بكسلات اللون:        10110100101101001011010010110100
// فتحة العدسة:                         0
// الوصف:
// البعد البؤري:                     50
// حساسية ISO:                  160
// الرقم التسلسلي للصورة:       0
// سرعة الغالق:                    12
// تاريخ التصوير:                 8/3/2007 3:13:49 ص
```

### DngImage() {#DngImage--}
```
public DngImage()
```


أنشئ مثيلاً جديدًا للفئة [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) بسهولة. مثالي للمطورين الذين يرغبون في بدء استخدام كائنات DngImage بسرعة وكفاءة في مشاريعهم.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


اكتشف عدد البتات لكل بكسل في الصورة بسهولة باستخدام هذه الخاصية. مثالي لفهم عمق بكسل الصورة بسرعة ودقة.

القيمة: عدد البتات لكل بكسل في الصورة.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


احصل على ارتفاع الصورة باستخدام هذه الخاصية. مثالي لتحديد الحجم العمودي للصورة دون عناء.

القيمة: ارتفاع الصورة.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


احصل على عرض الصورة باستخدام هذه الخاصية. مثالي للحصول على الحجم الأفقي للصورة بسرعة وكفاءة.

القيمة: عرض الصورة.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


حدد تنسيق ملف صورتك باستخدام هذه الخاصية. مثالي لفهم التنسيق - تفاصيل مباشرة وبسيطة.

**Returns:**
long
### getImgData() {#getImgData--}
```
public RawData getImgData()
```


إدارة بيانات الصورة باستخدام هذه الخاصية. سواء كنت تسترجع أو تُحدّث، توفر هذه الخاصية وصولًا سلسًا إلى بيانات الصورة لتعديل فعال.

**Returns:**
[RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) - The img data.
### setImgData(RawData value) {#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-}
```
public void setImgData(RawData value)
```


إدارة بيانات الصورة باستخدام هذه الخاصية. سواء كنت تسترجع أو تُحدّث، توفر هذه الخاصية وصولًا سلسًا إلى بيانات الصورة لتعديل فعال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) | بيانات الصورة. |

