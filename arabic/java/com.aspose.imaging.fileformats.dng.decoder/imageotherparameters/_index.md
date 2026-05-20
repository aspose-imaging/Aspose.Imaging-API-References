---
title: "ImageOtherParameters"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "معلمات صورة أخرى."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageOtherParameters
```

معلمات صورة أخرى.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDescription()](#getDescription--) | يحصل على وصف الصورة. |
| [getArtist()](#getArtist--) | يحصل على مؤلف الصورة. |
| [getTimestamp()](#getTimestamp--) | يحصل على تاريخ التصوير. |
| [getShotOrder()](#getShotOrder--) | يحصل على الرقم التسلسلي للصورة. |
| [getAperture()](#getAperture--) | يحصل على الفتحة. |
| [getShutterSpeed()](#getShutterSpeed--) | يحصل على سرعة الغالق. |
| [getGpsData()](#getGpsData--) | يحصل على بيانات GPS. |
| [getFocalLength()](#getFocalLength--) | يحصل على طول البؤري. |
| [getIsoSpeed()](#getIsoSpeed--) | يحصل على حساسية ISO. |

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
        // حوّل الطابع الزمني إلى سلسلة قابلة للقراءة البشرية.
        //java.text.SimpleDateFormat sf = new java.text.SimpleDateFormat(\"yyyy-MM-dd\");
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

### getDescription() {#getDescription--}
```
public String getDescription()
```


يحصل على وصف الصورة.

القيمة: الوصف.

**Returns:**
java.lang.String
### getArtist() {#getArtist--}
```
public String getArtist()
```


يحصل على مؤلف الصورة.

القيمة: الفنان.

**Returns:**
java.lang.String
### getTimestamp() {#getTimestamp--}
```
public long getTimestamp()
```


يحصل على تاريخ التصوير.

القيمة: الطابع الزمني.

**Returns:**
long
### getShotOrder() {#getShotOrder--}
```
public long getShotOrder()
```


يحصل على الرقم التسلسلي للصورة.

القيمة: ترتيب اللقطة.

**Returns:**
long
### getAperture() {#getAperture--}
```
public float getAperture()
```


يحصل على الفتحة.

القيمة: الفتحة.

**Returns:**
float
### getShutterSpeed() {#getShutterSpeed--}
```
public float getShutterSpeed()
```


يحصل على سرعة الغالق.

القيمة: الغالق.

**Returns:**
float
### getGpsData() {#getGpsData--}
```
public long[] getGpsData()
```


يحصل على بيانات GPS.

القيمة: بيانات GPS.

**Returns:**
long[]
### getFocalLength() {#getFocalLength--}
```
public float getFocalLength()
```


يحصل على طول البؤري.

القيمة: طول البؤري.

**Returns:**
float
### getIsoSpeed() {#getIsoSpeed--}
```
public float getIsoSpeed()
```


يحصل على حساسية ISO.

القيمة: سرعة ISO.

**Returns:**
float
