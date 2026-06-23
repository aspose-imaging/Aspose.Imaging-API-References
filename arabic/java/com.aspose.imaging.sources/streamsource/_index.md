---
title: "StreamSource"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل مصدر تدفق."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.sources/streamsource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source)
```
public final class StreamSource extends Source
```

يمثل مصدر تدفق.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [StreamSource(System.IO.Stream stream)](#StreamSource-com.aspose.ms.System.IO.Stream-) | يُنشئ مثلاً جديدًا من الفئة `StreamSource`. |
| [StreamSource(InputStream stream)](#StreamSource-java.io.InputStream-) | يُنشئ مثلاً جديدًا من الفئة `StreamSource`. |
| [StreamSource(byte[] data)](#StreamSource-byte---) | يُنشئ مثلاً جديدًا من الفئة `StreamSource`. |
| [StreamSource(ByteBuffer buffer)](#StreamSource-java.nio.ByteBuffer-) | يُنشئ مثلاً جديدًا من الفئة `StreamSource`. |
| [StreamSource()](#StreamSource--) | يُنشئ مثلاً جديدًا من الفئة `StreamSource` مع تدفق Null. |
| [StreamSource(RandomAccessFile file)](#StreamSource-java.io.RandomAccessFile-) | يُنشئ مثلاً جديدًا من الفئة `StreamSource`. |
| [StreamSource(RandomAccessFile file, boolean disposeStream)](#StreamSource-java.io.RandomAccessFile-boolean-) | يُنشئ مثلاً جديدًا من الفئة `StreamSource`. |
| [StreamSource(System.IO.Stream stream, boolean disposeStream)](#StreamSource-com.aspose.ms.System.IO.Stream-boolean-) | يُنشئ مثلاً جديدًا من الفئة `StreamSource`. |
| [StreamSource(InputStream stream, boolean disposeStream)](#StreamSource-java.io.InputStream-boolean-) | يُنشئ مثلاً جديدًا من الفئة `StreamSource`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getStream()](#getStream--) | يحصل على التدفق. |
| [getDisposeStream()](#getDisposeStream--) | يحصل على قيمة تشير إلى ما إذا كان يجب التخلص من stream كلما تم التخلص من container. |
| [getStreamContainer()](#getStreamContainer--) | يحصل على حاوية الدفق. |

## Example: This example demonstrates how to use StreamSource to create a new Image file (a JPEG type)

``` java

//ينشئ مثلاً من JpegOptions ويضبط خصائصه المتنوعة
com.aspose.imaging.imageoptions.JpegOptions jpegOptions = new com.aspose.imaging.imageoptions.JpegOptions();

//أنشئ مثلاً من System.IO.Stream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.jpeg");

// عرّف خاصية source للمثيل من JpegOptions
// المعامل المنطقي الثاني يحدد ما إذا كان Stream يُتخلص منه بمجرد الخروج من النطاق
jpegOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream, true));

// ينشئ مثلاً من Image ويستدعي طريقة Create مع JpegOptions كمعامل لتهيئة كائن Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(jpegOptions, 500, 500);
try {
    // قم ببعض معالجة الصورة.
} finally {
    image.dispose();
}
```

### StreamSource(System.IO.Stream stream) {#StreamSource-com.aspose.ms.System.IO.Stream-}
```
public StreamSource(System.IO.Stream stream)
```


يُنشئ مثلاً جديدًا من الفئة `StreamSource`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | com.aspose.ms.System.IO.Stream | التدفق للفتح. |

### StreamSource(InputStream stream) {#StreamSource-java.io.InputStream-}
```
public StreamSource(InputStream stream)
```


يُنشئ مثلاً جديدًا من الفئة `StreamSource`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | التدفق للفتح. |

### StreamSource(byte[] data) {#StreamSource-byte---}
```
public StreamSource(byte[] data)
```


يُنشئ مثلاً جديدًا من الفئة `StreamSource`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | مصفوفة byte التي تُخزن الصورة |

### StreamSource(ByteBuffer buffer) {#StreamSource-java.nio.ByteBuffer-}
```
public StreamSource(ByteBuffer buffer)
```


يُنشئ مثلاً جديدًا من الفئة `StreamSource`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | java.nio.ByteBuffer | مخزن ByteBuffer لتخزين الصورة |

### StreamSource() {#StreamSource--}
```
public StreamSource()
```


يقوم بإنشاء نسخة جديدة من الفئة `StreamSource` مع تدفق Null. يتيح هذا المُنشئ إنشاء صور جديدة بدون تدفق إدخال، تُخزن الصور فقط في الذاكرة.

### StreamSource(RandomAccessFile file) {#StreamSource-java.io.RandomAccessFile-}
```
public StreamSource(RandomAccessFile file)
```


يُنشئ مثلاً جديدًا من الفئة `StreamSource`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملف | java.io.RandomAccessFile | الملف للفتح. |

### StreamSource(RandomAccessFile file, boolean disposeStream) {#StreamSource-java.io.RandomAccessFile-boolean-}
```
public StreamSource(RandomAccessFile file, boolean disposeStream)
```


يُنشئ مثلاً جديدًا من الفئة `StreamSource`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملف | java.io.RandomAccessFile | الملف للفتح. |
| disposeStream | boolean | إذا تم تعيينه إلى `true` سيتم التخلص من التدفق. |

### StreamSource(System.IO.Stream stream, boolean disposeStream) {#StreamSource-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamSource(System.IO.Stream stream, boolean disposeStream)
```


يُنشئ مثلاً جديدًا من الفئة `StreamSource`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | com.aspose.ms.System.IO.Stream | التدفق |
| disposeStream | boolean | إذا تم تعيينه إلى `true` سيتم التخلص من التدفق. |

### StreamSource(InputStream stream, boolean disposeStream) {#StreamSource-java.io.InputStream-boolean-}
```
public StreamSource(InputStream stream, boolean disposeStream)
```


يُنشئ مثلاً جديدًا من الفئة `StreamSource`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | التدفق للفتح. |
| disposeStream | boolean | إذا تم تعيينه إلى `true` سيتم التخلص من التدفق. |

### getStream() {#getStream--}
```
public System.IO.Stream getStream()
```


يحصل على التدفق.

**Returns:**
com.aspose.ms.System.IO.Stream - التدفق.
### getDisposeStream() {#getDisposeStream--}
```
public boolean getDisposeStream()
```


يحصل على قيمة تشير إلى ما إذا كان يجب التخلص من stream كلما تم التخلص من container.

**Returns:**
منطقي - `true` إذا يجب التخلص من التدفق؛ وإلا `false`.
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


يحصل على حاوية الدفق.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

استخدم بحذر. سيتعين عليك تحرير حاوية الدفق بعد الاسترجاع.
