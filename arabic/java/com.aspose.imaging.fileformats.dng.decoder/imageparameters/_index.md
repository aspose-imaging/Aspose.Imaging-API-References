---
title: "ImageParameters"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "معلمات صورة DNG"
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.dng.decoder/imageparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageParameters
```

معلمات صورة DNG
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDngVersion()](#getDngVersion--) | يحصل على نسخة DNG. |
| [getDescription()](#getDescription--) | يحصل على وصف الألوان (RGBG,RGBE,GMCY, أو GBTG). |
| [getModel()](#getModel--) | يحصل على طراز الكاميرا. |
| [getCameraManufacturer()](#getCameraManufacturer--) | يحصل على شركة تصنيع الكاميرا. |
| [isFoveon()](#isFoveon--) | يحصل على ما إذا كانت مصفوفة فوفون. |
| [getSoftware()](#getSoftware--) | يحصل على البرنامج. |
| [getRawCount()](#getRawCount--) | يحصل على عدد صور RAW في الملف (0 يعني أن الملف لم يتم التعرف عليه). |
| [getFilters()](#getFilters--) | يحصل على قناع البت الذي يصف ترتيب بكسلات اللون في المصفوفة. |
| [getColorsCount()](#getColorsCount--) | يحصل على الألوان. |
| [getXmpData()](#getXmpData--) | يحصل على بيانات XMP. |
| [getTranslationCfaDng()](#getTranslationCfaDng--) | يحصل على مصفوفة الترجمة لتنسيق CFA mosaic DNG. |

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

### getDngVersion() {#getDngVersion--}
```
public long getDngVersion()
```


يحصل على نسخة DNG.

القيمة: إصدار DNG.

**Returns:**
long
### getDescription() {#getDescription--}
```
public String getDescription()
```


يحصل على وصف الألوان (RGBG,RGBE,GMCY, أو GBTG).

القيمة: cdesc.

**Returns:**
java.lang.String
### getModel() {#getModel--}
```
public String getModel()
```


يحصل على طراز الكاميرا.

القيمة: الطراز.

**Returns:**
java.lang.String
### getCameraManufacturer() {#getCameraManufacturer--}
```
public String getCameraManufacturer()
```


يحصل على شركة تصنيع الكاميرا.

القيمة: الصانع.

**Returns:**
java.lang.String
### isFoveon() {#isFoveon--}
```
public long isFoveon()
```


يحصل على ما إذا كانت مصفوفة فوفون.

القيمة: الـ هو foveon.

**Returns:**
long
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


يحصل على البرنامج.

القيمة: البرنامج.

**Returns:**
java.lang.String
### getRawCount() {#getRawCount--}
```
public long getRawCount()
```


يحصل على عدد صور RAW في الملف (0 يعني أن الملف لم يتم التعرف عليه).

القيمة: العدد الخام.

**Returns:**
long
### getFilters() {#getFilters--}
```
public long getFilters()
```


يحصل على قناع البت الذي يصف ترتيب بكسلات اللون في المصفوفة.

القيمة: الفلاتر.

**Returns:**
long
### getColorsCount() {#getColorsCount--}
```
public int getColorsCount()
```


يحصل على الألوان.

القيمة: الألوان.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public String getXmpData()
```


يحصل على بيانات XMP.

القيمة: بيانات XMP.

**Returns:**
java.lang.String
### getTranslationCfaDng() {#getTranslationCfaDng--}
```
public String[] getTranslationCfaDng()
```


يحصل على مصفوفة الترجمة لتنسيق CFA mosaic DNG.

القيمة: xtrans.

**Returns:**
java.lang.String[]
