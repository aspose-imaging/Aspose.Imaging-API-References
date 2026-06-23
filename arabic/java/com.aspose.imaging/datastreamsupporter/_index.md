---
title: "DataStreamSupporter"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "حاوية تدفق البيانات."
type: docs
weight: 39
url: /ar/java/com.aspose.imaging/datastreamsupporter/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

حاوية تدفق البيانات.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDataStreamContainer()](#getDataStreamContainer--) | يحصل على تدفق بيانات الكائن. |
| [isCached()](#isCached--) | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات. |
| [cacheData()](#cacheData--) | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من `DataStreamSupporter.DataStreamContainer` الأساسي. |
| [save()](#save--) | يحفظ بيانات الكائن إلى `DataStreamSupporter` الحالي. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | يحفظ بيانات الكائن إلى التدفق المحدد. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | يحفظ بيانات الكائن إلى التدفق المحدد. |
| [save(String filePath)](#save-java.lang.String-) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


يحصل على تدفق بيانات الكائن.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The object's data stream.
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات.
### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من `DataStreamSupporter.DataStreamContainer` الأساسي.


**Example: The following example shows how image caching affects performance.**
يوضح المثال التالي كيف يؤثر تخزين الصور مؤقتًا على الأداء. بشكل عام، قراءة البيانات المخزنة مؤقتًا يتم تنفيذها أسرع من قراءة البيانات غير المخزنة.
``` java
String dir = "c:\\temp\\";

// حمّل صورة من ملف PNG.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // خزن جميع بيانات البكسل بحيث لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // قراءة جميع البكسلات سريعة إلى حد كبير.
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = rasterImage.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedTime = stopTime - startTime;
    System.out.println("Reading all cached pixels took " + elapsedTime + " ms.");
} finally {
    image.dispose();
}

// تحميل صورة من ملف PNG
image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // قراءة جميع البكسلات ليست سريعة كما هو الحال عند التخزين المؤقت
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = rasterImage.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedTime = stopTime - startTime;
    System.out.println("Reading all pixels without preliminary caching took " + elapsedTime + " ms.");
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
//استغرق قراءة جميع البكسلات المخزنة مؤقتًا 2954 مللي ثانية.
//    java.lang.OutOfMemoryError
//في com.aspose.imaging.internal.G.be.b(مصدر غير معروف)
//في com.aspose.imaging.internal.G.be.a(مصدر غير معروف)
//في com.aspose.imaging.internal.G.be.a(مصدر غير معروف)
//في com.aspose.imaging.internal.G.be.a(مصدر غير معروف)
//في com.aspose.imaging.internal.G.aB.a(مصدر غير معروف)
//في com.aspose.imaging.RasterImage.a(مصدر غير معروف)
//في com.aspose.imaging.RasterImage.getArgb32Pixel(مصدر غير معروف)
//في com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:58)
```

### save() {#save--}
```
public void save()
```


يحفظ بيانات الكائن إلى `DataStreamSupporter` الحالي.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


يحفظ بيانات الكائن إلى التدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.OutputStream | التدفق لحفظ بيانات الكائن إليه. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


يحفظ بيانات الكائن إلى التدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملف | java.io.RandomAccessFile | التدفق لحفظ بيانات الكائن إليه. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


يحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لحفظ بيانات الكائن إليه. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


يحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لحفظ بيانات الكائن إليه. |
| overWrite | boolean | إذا تم ضبطه على `true` سيُستبدل محتوى الملف، وإلا سيُضاف المحتوى. |

