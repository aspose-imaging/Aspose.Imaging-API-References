---
title: "XmpMeta"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل بيانات تعريف xmp."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.xmp/xmpmeta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging/xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

يمثل xmp meta. اختياري. هدف هذا العنصر هو تحديد بيانات XMP الوصفية داخل نص XML عام قد يحتوي على استخدامات غير XMP من RDF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | ينشئ مثيلاً جديدًا من الفئة `XmpMeta`. |
| [XmpMeta()](#XmpMeta--) | ينشئ مثيلاً جديدًا من الفئة `XmpMeta`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | الحصول على أو تعيين إصدار مجموعة أدوات Adobe Xmp. |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | الحصول على أو تعيين إصدار مجموعة أدوات Adobe Xmp. |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | يضيف السمة. |
| [getXmlValue()](#getXmlValue--) | يقوم بتحويل قيمة XMP إلى تمثيل XML. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.imaging.xmp.XmpMeta-) | يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع. |
| [equals(Object other)](#equals-java.lang.Object-) | يحدد ما إذا كان `System.Object` المحدد يساوي هذه النسخة. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


ينشئ مثيلاً جديدًا من الفئة `XmpMeta`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| toolkitVersion | java.lang.String | إصدار مجموعة أدوات Adobe XMP. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


ينشئ مثيلاً جديدًا من الفئة `XmpMeta`.

### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


الحصول على أو تعيين إصدار مجموعة أدوات Adobe Xmp.

**Returns:**
java.lang.String
### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


الحصول على أو تعيين إصدار مجموعة أدوات Adobe Xmp.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


يضيف السمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| attribute | java.lang.String | السمة. |
| value | java.lang.String | القيمة. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يقوم بتحويل قيمة XMP إلى تمثيل XML.

**Returns:**
java.lang.String - يُعيد قيمة XMP المحوّلة إلى تمثيل XML.
### isEquals(XmpMeta other) {#isEquals-com.aspose.imaging.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | كائن للمقارنة مع هذا الكائن. |

**Returns:**
boolean - true إذا كان الكائن الحالي يساوي المعامل `other`؛ وإلا false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


يحدد ما إذا كان `System.Object` المحدد يساوي هذه النسخة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | java.lang.Object | الـ `System.Object` للمقارنة مع هذه الحالة. |

**Returns:**
منطقي - `true` إذا كان الـ `System.Object` المحدد يساوي هذه الحالة؛ وإلا، `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - قيمة تجزئة (hash code) لهذا الكائن، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
