---
title: "XmpHeaderPi"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل تعليمات معالجة رأس XMP."
type: docs
weight: 17
url: /ar/java/com.aspose.imaging.xmp/xmpheaderpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

يمثل تعليمات معالجة رأس XMP.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | يقوم بتهيئة نسخة جديدة من الفئة `XmpHeaderPi`. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | يقوم بتهيئة نسخة جديدة من الفئة `XmpHeaderPi`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getGuid()](#getGuid--) | يمثل معرف رأس (Guid). |
| [setGuid(String value)](#setGuid-java.lang.String-) | يمثل معرف رأس (Guid). |
| [getXmlValue()](#getXmlValue--) | يقوم بتحويل قيمة XMP إلى تمثيل XML. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-) | يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان `System.Object` المحدد يساوي هذه النسخة. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


يقوم بتهيئة نسخة جديدة من الفئة `XmpHeaderPi`.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


يقوم بتهيئة نسخة جديدة من الفئة `XmpHeaderPi`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| guid | java.lang.String | المعرّف الفريد. |

### getGuid() {#getGuid--}
```
public String getGuid()
```


يمثل معرف رأس (Guid).

نص رأس الـ PI يحتوي على GUID، مما يجعل ظهوره عن طريق الخطأ في تدفق البيانات غير محتمل.

**Returns:**
java.lang.String
### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


يمثل معرف رأس (Guid).

نص رأس الـ PI يحتوي على GUID، مما يجعل ظهوره عن طريق الخطأ في تدفق البيانات غير محتمل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يقوم بتحويل قيمة XMP إلى تمثيل XML.

**Returns:**
java.lang.String - يُعيد قيمة XMP المحوّلة إلى تمثيل XML.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | كائن للمقارنة مع هذا الكائن. |

**Returns:**
boolean - true إذا كان الكائن الحالي يساوي المعامل `other`؛ وإلا false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان `System.Object` المحدد يساوي هذه النسخة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ `System.Object` للمقارنة مع هذه الحالة. |

**Returns:**
منطقي - `true` إذا كان الـ `System.Object` المحدد يساوي هذه الحالة؛ وإلا، `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - قيمة تجزئة (hash code) لهذا الكائن، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
