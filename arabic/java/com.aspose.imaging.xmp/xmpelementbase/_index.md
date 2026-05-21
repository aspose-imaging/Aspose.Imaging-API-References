---
title: "XmpElementBase"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل عنصر XMP الأساسي الذي يحتوي على سمات."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.xmp/xmpelementbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class XmpElementBase implements System.IEquatable<XmpElementBase>
```

يمثل عنصر XMP الأساسي الذي يحتوي على سمات.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | يضيف السمة. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | يحصل على السمة. |
| [clearAttributes()](#clearAttributes--) | يزيل جميع السمات. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.imaging.xmp.XmpElementBase-) | يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان `Object` المحدد يساوي هذه المثيلة. |
| [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash code) لهذه المثيل. |
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

### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


يحصل على السمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| السمة | java.lang.String | السمة. |

**Returns:**
java.lang.String - يُرجع السمة للاسم المحدد للخاصية.
### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


يزيل جميع السمات.

### isEquals(XmpElementBase other) {#isEquals-com.aspose.imaging.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase) | كائن للمقارنة مع هذا الكائن. |

**Returns:**
boolean - true إذا كان الكائن الحالي مساويًا للمعامل `other`؛ وإلا، false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان `Object` المحدد يساوي هذه المثيلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | ال `Object` للمقارنة مع هذه الحالة. |

**Returns:**
منطقي - `true` إذا كان الـ `Object` المحدد يساوي هذه الحالة؛ وإلا `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة (hash code) لهذه المثيل.

**Returns:**
int - رمز تجزئة (hash code) لهذه المثيل، مناسب للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.
