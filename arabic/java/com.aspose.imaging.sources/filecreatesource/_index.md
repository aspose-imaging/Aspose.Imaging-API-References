---
title: "FileCreateSource"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل مصدر ملف لإنشاء."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.sources/filecreatesource/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.Source](../../com.aspose.imaging/source)، [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

يمثل مصدر ملف لإنشاء.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | يقوم بإنشاء نسخة جديدة من الفئة `FileCreateSource`. |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | يقوم بإنشاء نسخة جديدة من الفئة `FileCreateSource`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFilePath()](#getFilePath--) | يحصل على مسار الملف لإنشائه. |
| [isTemporal()](#isTemporal--) | يحصل على قيمة تشير إلى ما إذا كان الملف مؤقتًا. |
| [getStreamContainer()](#getStreamContainer--) | يحصل على حاوية الدفق. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
يوضح هذا المثال استخدام فئة Font و SolidBrush لرسم سلاسل نصية على سطح Image. ينشئ المثال Image جديدًا ويرسم أشكالًا باستخدام Figures و GraphicsPath.
``` java
//ينشئ مثيلاً من BmpOptions ويضبط خصائصه المتنوعة.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//إنشاء مثيل من FileCreateSource وتعيينه كقيمة Source لمثيل BmpOptions.
//المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//ينشئ مثيلًا من Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //ينشئ ويُهيئ مثيلًا من فئة Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //يمسح سطح Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //ينشئ مثيلًا من Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //إنشاء مثيل من SolidBrush بلون أحمر
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //رسم سلسلة نصية
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // احفظ جميع التغييرات
    image.save();
} finally {
    image.dispose();
}
```

### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


يقوم بإنشاء نسخة جديدة من الفئة `FileCreateSource`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لإنشائه. |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


يقوم بإنشاء نسخة جديدة من الفئة `FileCreateSource`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لإنشائه. |
| isTemporal | boolean | إذا تم تعيينه إلى `true` فإن الملف الذي تم إنشاؤه سيكون مؤقتًا. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


يحصل على مسار الملف لإنشائه.

القيمة: مسار الملف لإنشائه.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


يحصل على قيمة تشير إلى ما إذا كان الملف مؤقتًا.

القيمة: `true` إذا كان الملف مؤقتًا؛ وإلا `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


يحصل على حاوية الدفق.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

استخدم بحذر. سيتعين عليك تحرير حاوية الدفق بعد الاسترجاع.
