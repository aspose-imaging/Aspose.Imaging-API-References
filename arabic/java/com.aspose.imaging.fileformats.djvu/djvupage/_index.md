---
title: "DjvuPage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة صفحة Djvu"
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.djvu/djvupage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DjvuPage extends RasterCachedImage
```

فئة صفحة Djvu
## الحقول

| حقل | الوصف |
| --- | --- |
| [PageExportedAction](#PageExportedAction) | يحدث عندما [page exported action]. |
| [PropertyChanged](#PropertyChanged) | يحدث عندما تتغير قيمة الخاصية. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد بتات الصورة لكل بكسل. |
| [getParentImage()](#getParentImage--) | يحصل على الصورة الأصلية التي تنتمي إليها الصفحة |
| [getWidth()](#getWidth--) | يحصل على عرض الصفحة |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصفحة |
| [getImage()](#getImage--) | يحصل على الصورة. |
| [getThumbnailImage()](#getThumbnailImage--) | يحصل أو يضبط صورة المصغرة للصفحة |
| [setThumbnailImage(DjvuRaster value)](#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-) | يحصل أو يضبط صورة المصغرة للصفحة |
| [getPageNumber()](#getPageNumber--) | يحصل على رقم الصفحة. |
| [isColor()](#isColor--) | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة ملونة. |
| [getTextForLocation(Rectangle rect)](#getTextForLocation-com.aspose.imaging.Rectangle-) | يحصل على النص لموقع المستطيل |
| [getForegroundImage()](#getForegroundImage--) | يحصل على صورة المقدمة للصفحة |
| [getForegroundImage(int subsample)](#getForegroundImage-int-) | يحصل على صورة المقدمة للصفحة |
| [getTextImage()](#getTextImage--) | يحصل على صورة النص. |
| [getTextImage(int subsample)](#getTextImage-int-) | يحصل على صورة النص. |
| [getBackgroundImage()](#getBackgroundImage--) | يحصل على صورة الخلفية. |
| [extractThumbnailImage()](#extractThumbnailImage--) | يستخرج صورة المصغرة من صفحة Djvu. |
### PageExportedAction {#PageExportedAction}
```
public static final DefEvent<OnPageExportedAction> PageExportedAction
```


يحدث عندما [page exported action].

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


يحدث عندما تتغير قيمة الخاصية.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد بتات الصورة لكل بكسل.

القيمة: عدد البتات لكل بكسل في الصورة.

**Returns:**
int
### getParentImage() {#getParentImage--}
```
public DjvuImage getParentImage()
```


يحصل على الصورة الأصلية التي تنتمي إليها الصفحة

القيمة: المستند.

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)
### getWidth() {#getWidth--}
```
public int getWidth()
```


يحصل على عرض الصفحة

القيمة: العرض.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


يحصل على ارتفاع الصفحة

القيمة: الارتفاع.

**Returns:**
int
### getImage() {#getImage--}
```
public DjvuRaster getImage()
```


يحصل على الصورة.

القيمة: الصورة.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### getThumbnailImage() {#getThumbnailImage--}
```
public DjvuRaster getThumbnailImage()
```


يحصل أو يضبط صورة المصغرة للصفحة

القيمة: صورة المصغرة.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### setThumbnailImage(DjvuRaster value) {#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-}
```
public void setThumbnailImage(DjvuRaster value)
```


يحصل أو يضبط صورة المصغرة للصفحة

القيمة: صورة المصغرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


يحصل على رقم الصفحة.

القيمة: رقم الصفحة.

**Returns:**
int

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// تحميل صورة DJVU من تدفق ملف.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//قد يبدو الإخراج هكذا:
//إجمالي عدد الصفحات: 2
//رقم الصفحة النشطة:    1
//رقم الصفحة الأولى:     1
//رقم الصفحة الأخيرة:      2
//--------------------------------------------------
//رقم الصفحة:     1
//حجم الصفحة:       { Width = 2481, Height = 3508}
//تنسيق الصفحة الخام: RgbIndexed1Bpp, القنوات المستخدمة: 1
//--------------------------------------------------
//رقم الصفحة:     2
//حجم الصفحة:       { Width = 2481, Height = 3508}
//تنسيق الصفحة الخام: RgbIndexed1Bpp, القنوات المستخدمة: 1
```

### isColor() {#isColor--}
```
public boolean isColor()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة ملونة.

القيمة: `true` إذا كانت هذه الحالة ملونة؛ وإلا `false`.

**Returns:**
boolean
### getTextForLocation(Rectangle rect) {#getTextForLocation-com.aspose.imaging.Rectangle-}
```
public String getTextForLocation(Rectangle rect)
```


يحصل على النص لموقع المستطيل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | مستطيل الموقع. |

**Returns:**
java.lang.String - النص الموجود في الموقع
### getForegroundImage() {#getForegroundImage--}
```
public DjvuRaster getForegroundImage()
```


يحصل على صورة المقدمة للصفحة

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getForegroundImage(int subsample) {#getForegroundImage-int-}
```
public DjvuRaster getForegroundImage(int subsample)
```


يحصل على صورة المقدمة للصفحة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| subsample | int | العينة الفرعية. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getTextImage() {#getTextImage--}
```
public DjvuRaster getTextImage()
```


يحصل على صورة النص.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getTextImage(int subsample) {#getTextImage-int-}
```
public DjvuRaster getTextImage(int subsample)
```


يحصل على صورة النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| subsample | int | العينة الفرعية. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getBackgroundImage() {#getBackgroundImage--}
```
public DjvuRaster getBackgroundImage()
```


يحصل على صورة الخلفية.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### extractThumbnailImage() {#extractThumbnailImage--}
```
public DjvuRaster extractThumbnailImage()
```


يستخرج صورة المصغرة من صفحة Djvu.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The DjVu raster image.
