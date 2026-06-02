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
| [XmpHeaderPi()](#XmpHeaderPi--) | ينشئ مثيلاً جديدًا للفئة `XmpHeaderPi`. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | ينشئ مثيلاً جديدًا للفئة `XmpHeaderPi`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getGuid()](#getGuid--) | يمثل معرف رأس (Guid). |
| [setGuid(String value)](#setGuid-java.lang.String-) | يمثل معرف رأس (Guid). |
| [getXmlValue()](#getXmlValue--) | يحوّل قيمة XMP إلى تمثيل XML. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-) | يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان `System.Object` المحدد يساوي هذه المثيلة. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash code) لهذه المثيل. |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


ينشئ مثيلاً جديدًا للفئة `XmpHeaderPi`.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


ينشئ مثيلاً جديدًا للفئة `XmpHeaderPi`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| guid | java.lang.String | المعرف الفريد. |

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
| القيمة | java.lang.String |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يحوّل قيمة XMP إلى تمثيل XML.

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
boolean - true إذا كان الكائن الحالي مساويًا للمعامل `other`؛ وإلا، false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان `System.Object` المحدد يساوي هذه المثيلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الـ `System.Object` للمقارنة مع هذا المثيل. |

**Returns:**
منطقي - `true` إذا كان الـ `System.Object` المحدد يساوي هذا المثيل؛ وإلا، `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة (hash code) لهذه المثيل.

**Returns:**
int - رمز تجزئة (hash code) لهذه المثيل، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
