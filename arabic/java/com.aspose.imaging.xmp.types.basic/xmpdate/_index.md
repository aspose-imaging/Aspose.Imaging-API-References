---
title: "XmpDate"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل التاريخ في حزمة XMP."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.xmp.types.basic/xmpdate/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

يمثل التاريخ في حزمة XMP.

يتم تمثيل قيمة التاريخ والوقت باستخدام مجموعة فرعية من الصيغ كما هو معرف في صيغ التاريخ والوقت: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | يُنشئ مثيلاً جديدًا من الفئة `XmpDate`. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | يُنشئ مثيلاً جديدًا من الفئة `XmpDate`. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [ISO_8601_FORMAT](#ISO-8601-FORMAT) | سلسلة الصيغة ISO 8601 (دورة كاملة). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValue()](#getValue--) | يحصل أو يضبط قيمة التاريخ. |
| [setValue(Date value)](#setValue-java.util.Date-) | يحصل أو يضبط قيمة التاريخ. |
| [getFormat()](#getFormat--) | يحصل على سلسلة الصيغة للقيمة الحالية. |
| [getXmpRepresentation()](#getXmpRepresentation--) | يرجع القيمة المحتواة كسلسلة بصيغة XMP. |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


يُنشئ مثيلاً جديدًا من الفئة `XmpDate`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dateTime | java.util.Date | قيمة تاريخ ووقت يتم تمثيلها باستخدام مجموعة فرعية من تنسيق ISO RFC 8601. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


يُنشئ مثيلاً جديدًا من الفئة `XmpDate`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dateString | java.lang.String | التمثيل النصي للتاريخ. |

### ISO_8601_FORMAT {#ISO-8601-FORMAT}
```
public static final String ISO_8601_FORMAT
```


سلسلة الصيغة ISO 8601 (دورة كاملة).

انظر المزيد: [ here ][here].


[here]: https://en.wikipedia.org/wiki/ISO_8601

### getValue() {#getValue--}
```
public Date getValue()
```


يحصل أو يضبط قيمة التاريخ.

القيمة: قيمة التاريخ.

**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


يحصل أو يضبط قيمة التاريخ.

القيمة: قيمة التاريخ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getFormat() {#getFormat--}
```
public String getFormat()
```


يحصل على سلسلة الصيغة للقيمة الحالية.

القيمة: سلسلة الصيغة للقيمة الحالية.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


يرجع القيمة المحتواة كسلسلة بصيغة XMP.

**Returns:**
java.lang.String - يُرجع سلسلة تحتوي على تمثيل xmp
