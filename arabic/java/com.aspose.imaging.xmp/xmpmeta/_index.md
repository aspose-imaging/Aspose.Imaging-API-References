---
title: "XmpMeta"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل ميتا XMP."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.xmp/xmpmeta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

يمثل xmp meta. اختياري. الغرض من هذا العنصر هو تحديد بيانات XMP الوصفية داخل نص XML عام قد يحتوي على استخدامات غير XMP لـ RDF.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | ينشئ مثلاً جديدًا من الفئة `XmpMeta`. |
| [XmpMeta()](#XmpMeta--) | ينشئ مثلاً جديدًا من الفئة `XmpMeta`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | يحصل أو يضبط إصدار مجموعة أدوات Adobe Xmp. |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | يحصل أو يضبط إصدار مجموعة أدوات Adobe Xmp. |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | يضيف السمة. |
| [getXmlValue()](#getXmlValue--) | يحوّل قيمة XMP إلى تمثيل XML. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.imaging.xmp.XmpMeta-) | يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع. |
| [equals(Object other)](#equals-java.lang.Object-) | يحدد ما إذا كان `System.Object` المحدد يساوي هذه المثيلة. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash code) لهذه المثيل. |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


ينشئ مثلاً جديدًا من الفئة `XmpMeta`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| toolkitVersion | java.lang.String | إصدار مجموعة أدوات Adobe XMP. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


ينشئ مثلاً جديدًا من الفئة `XmpMeta`.

### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


يحصل أو يضبط إصدار مجموعة أدوات Adobe Xmp.

**Returns:**
java.lang.String
### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


يحصل أو يضبط إصدار مجموعة أدوات Adobe Xmp.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


يضيف السمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السمة | java.lang.String | السمة. |
| القيمة | java.lang.String | القيمة. |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يحوّل قيمة XMP إلى تمثيل XML.

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
boolean - true إذا كان الكائن الحالي مساويًا للمعامل `other`؛ وإلا، false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


يحدد ما إذا كان `System.Object` المحدد يساوي هذه المثيلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| أخرى | java.lang.Object | الـ `System.Object` للمقارنة مع هذا المثيل. |

**Returns:**
منطقي - `true` إذا كان الـ `System.Object` المحدد يساوي هذا المثيل؛ وإلا، `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة (hash code) لهذه المثيل.

**Returns:**
int - رمز تجزئة (hash code) لهذه المثيل، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
