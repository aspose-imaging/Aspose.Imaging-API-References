---
title: "FileOpenSource"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل مصدر ملف للفتح."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.sources/fileopensource/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.Source](../../com.aspose.imaging/source)، [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

يمثل مصدر ملف للفتح.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | يقوم بإنشاء نسخة جديدة من الفئة `FileOpenSource`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFilePath()](#getFilePath--) | يحصل على مسار الملف للفتح. |
| [isTemporal()](#isTemporal--) | يحصل على قيمة تشير إلى ما إذا كان الملف مؤقتًا. |
| [getStreamContainer()](#getStreamContainer--) | يحصل على حاوية الدفق. |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


يقوم بإنشاء نسخة جديدة من الفئة `FileOpenSource`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف للفتح. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


يحصل على مسار الملف للفتح.

القيمة: مسار الملف للفتح.

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
