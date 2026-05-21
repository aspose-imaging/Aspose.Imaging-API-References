---
title: "FileStreamContainer"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "مساعدة لمعالجة تدفق الملفات."
type: docs
weight: 46
url: /ar/java/com.aspose.imaging/filestreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public final class FileStreamContainer extends StreamContainer
```

مساعدة لمعالجة تدفق الملفات.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [to_Stream(FileStreamContainer fileStreamContainer)](#to-Stream-com.aspose.imaging.FileStreamContainer-) | يؤدي تحويلًا صريحًا من `com.aspose.imaging.FileStreamContainer` إلى `System.IO.Stream`. |
| [to_FileStream(FileStreamContainer fileStreamContainer)](#to-FileStream-com.aspose.imaging.FileStreamContainer-) | يؤدي تحويلًا صريحًا من `com.aspose.imaging.FileStreamContainer` إلى `System.IO.FileStream`. |
| [createFileStream(String fileLocation, boolean isTemporal)](#createFileStream-java.lang.String-boolean-) | ينشئ تدفق ملف جديد. |
| [openFileStream(String fileLocation)](#openFileStream-java.lang.String-) | يفتح تدفق ملف موجود. |
| [isTemporal()](#isTemporal--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان التدفق مؤقتًا. |
| [setTemporal(boolean value)](#setTemporal-boolean-) | يضبط قيمة تشير إلى ما إذا كان التدفق مؤقتًا. |
| [isCreated()](#isCreated--) | يحصل على قيمة تشير إلى ما إذا كان التدفق قد تم إنشاؤه صراحةً. |
| [getFilePath()](#getFilePath--) | يحصل على مسار الملف. |
### to_Stream(FileStreamContainer fileStreamContainer) {#to-Stream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.Stream to_Stream(FileStreamContainer fileStreamContainer)
```


يؤدي تحويلًا صريحًا من `com.aspose.imaging.FileStreamContainer` إلى `System.IO.Stream`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | حاوية تدفق الملف. |

**Returns:**
com.aspose.ms.System.IO.Stream - نتيجة التحويل.
### to_FileStream(FileStreamContainer fileStreamContainer) {#to-FileStream-com.aspose.imaging.FileStreamContainer-}
```
public static System.IO.FileStream to_FileStream(FileStreamContainer fileStreamContainer)
```


يؤدي تحويلًا صريحًا من `com.aspose.imaging.FileStreamContainer` إلى `System.IO.FileStream`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileStreamContainer | [FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) | حاوية تدفق الملف. |

**Returns:**
com.aspose.ms.System.IO.FileStream - نتيجة التحويل.
### createFileStream(String fileLocation, boolean isTemporal) {#createFileStream-java.lang.String-boolean-}
```
public static FileStreamContainer createFileStream(String fileLocation, boolean isTemporal)
```


ينشئ تدفق ملف جديد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileLocation | java.lang.String | موقع الملف. |
| isTemporal | boolean | إذا تم تعيينه إلى `true` يكون حاوية تدفق الملف مؤقتة. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### openFileStream(String fileLocation) {#openFileStream-java.lang.String-}
```
public static FileStreamContainer openFileStream(String fileLocation)
```


يفتح تدفق ملف موجود. إذا لم يكن تدفق الملف موجودًا يتم إلقاء الاستثناء المناسب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileLocation | java.lang.String | موقع الملف. |

**Returns:**
[FileStreamContainer](../../com.aspose.imaging/filestreamcontainer) - The file stream container.
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان التدفق مؤقتًا.

**Returns:**
منطقي - `true` إذا كان التدفق مؤقتًا؛ وإلا `false`.

سيقوم التدفق المؤقت بإزالة نفسه عند التخلص منه. إذا كان التدفق قائمًا على الذاكرة فإن هذه الخاصية ليس لها تأثير. يمكن وضع علامة على التدفق كـ مؤقت أو دائم في حال تم إنشاؤه صراحةً وإلا يتم إلقاء الاستثناء المناسب.
### setTemporal(boolean value) {#setTemporal-boolean-}
```
public void setTemporal(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان التدفق مؤقتًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | `true` إذا كان التدفق مؤقتًا؛ وإلا `false`. |

سيقوم التدفق المؤقت بإزالة نفسه عند التخلص منه. إذا كان التدفق قائمًا على الذاكرة فإن هذه الخاصية ليس لها تأثير. يمكن وضع علامة على التدفق كـ مؤقت أو دائم في حال تم إنشاؤه صراحةً وإلا يتم إلقاء الاستثناء المناسب. |

### isCreated() {#isCreated--}
```
public boolean isCreated()
```


يحصل على قيمة تشير إلى ما إذا كان التدفق قد تم إنشاؤه صراحةً.

**Returns:**
منطقي - `true` إذا تم إنشاء التدفق صراحةً؛ وإلا `false`.
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


يحصل على مسار الملف.

**Returns:**
java.lang.String - مسار الملف.
