---
title: "كود الوقت"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل قيمة رمز الوقت في الفيديو."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.xmp.schemas.xmpdm/timecode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

يمثل قيمة رمز الوقت في الفيديو.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | ينشئ مثيلاً جديدًا للفئة `Timecode`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormat()](#getFormat--) | يحصل أو يضبط التنسيق المستخدم في `TimeValue`. |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-) | يحصل أو يضبط التنسيق المستخدم في `TimeValue`. |
| [getTimeValue()](#getTimeValue--) | يحصل أو يضبط قيمة الوقت بالتنسيق المحدد. |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | يحصل أو يضبط قيمة الوقت بالتنسيق المحدد. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يرجع القيمة النصية المحتواة بتنسيق XMP. |
| [isEquals(Timecode other)](#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-) | يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان `System.Object` المحدد يساوي هذه النسخة. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


ينشئ مثيلاً جديدًا للفئة `Timecode`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) | تنسيق الوقت. |
| timeValue | java.lang.String | قيمة الوقت. |

### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


يحصل أو يضبط التنسيق المستخدم في `TimeValue`.

القيمة: الصيغة المستخدمة في `TimeValue`.

**Returns:**
[TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat)
### setFormat(TimeFormat value) {#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


يحصل أو يضبط التنسيق المستخدم في `TimeValue`.

القيمة: الصيغة المستخدمة في `TimeValue`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) |  |

### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


يحصل أو يضبط قيمة الوقت بالتنسيق المحدد.

القيمة: قيمة الوقت بالتنسيق المحدد.

**Returns:**
java.lang.String
### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


يحصل أو يضبط قيمة الوقت بالتنسيق المحدد.

القيمة: قيمة الوقت بالتنسيق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


يرجع القيمة النصية المحتواة بتنسيق XMP.

**Returns:**
java.lang.String - يُرجع السلسلة التي تحتوي على تمثيل xmp.
### isEquals(Timecode other) {#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.imaging.xmp.schemas.xmpdm/timecode) | كائن للمقارنة مع هذا الكائن. |

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
