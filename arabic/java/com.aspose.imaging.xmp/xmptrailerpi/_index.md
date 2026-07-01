---
title: "XmpTrailerPi"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل تعليمات معالجة ذيل XMP."
type: docs
weight: 23
url: /ar/java/com.aspose.imaging.xmp/xmptrailerpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

يمثل تعليمات معالجة ذيل XMP.

يجب أن يُستخدم الجزء end="w" أو end="r" بواسطة معالجات فحص الحزم لتحديد ما إذا كان يمكن تعديل XMP في الموقع.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | يُنشئ مثلاً جديداً من الفئة `XmpTrailerPi`. |
| [XmpTrailerPi()](#XmpTrailerPi--) | يُنشئ مثلاً جديداً من الفئة `XmpTrailerPi`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isWritable()](#isWritable--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل قابلًا للكتابة. |
| [setWritable(boolean value)](#setWritable-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل قابلًا للكتابة. |
| [getXmlValue()](#getXmlValue--) | يحوّل قيمة xmp إلى تمثيل xml. |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-) | يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان `System.Object` المحدد يساوي هذه النسخة. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


يُنشئ مثلاً جديداً من الفئة `XmpTrailerPi`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isWritable | boolean | يشير إلى ما إذا كان المقطوعة قابلة للكتابة. |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


يُنشئ مثلاً جديداً من الفئة `XmpTrailerPi`.

### isWritable() {#isWritable--}
```
public boolean isWritable()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل قابلًا للكتابة.

القيمة: `true` إذا كان هذا المثيل قابلًا للكتابة؛ وإلا `false`.

**Returns:**
boolean
### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل قابلًا للكتابة.

القيمة: `true` إذا كان هذا المثيل قابلًا للكتابة؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


يحوّل قيمة xmp إلى تمثيل xml.

**Returns:**
java.lang.String - يُرجع تمثيل XML لـ XMP.
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | كائن للمقارنة مع هذا الكائن. |

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
