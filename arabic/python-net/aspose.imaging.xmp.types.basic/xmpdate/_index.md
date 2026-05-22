---
title: "فئة XmpDate"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.imaging.xmp.types.basic](/imaging/python-net/aspose.imaging.xmp.types.basic/)

**Full Name:** aspose.imaging.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | يُنشئ مثيلاً جديدًا من الفئة [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/). |
| [XmpDate(date_time)](#XmpDate_date_time_2) | يُنشئ مثيلاً جديدًا من الفئة [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [ثابت] | string | r | سلسلة تنسيق ISO 8601 (دورة كاملة). |
| تنسيق | string | r | يحصل على سلسلة التنسيق للقيمة الحالية. |
| القيمة | System.DateTime | r/w | يحصل أو يعيّن قيمة التاريخ. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينسخ هذه المثيلة. |
| [get_xmp_representation()](#get_xmp_representation__2) | يرجع قيمة السلسلة المحتواة بتنسيق XMP. |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

يُنشئ مثيلاً جديدًا من الفئة [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| date_string | string | تمثيل السلسلة للتاريخ. |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

يُنشئ مثيلاً جديدًا من الفئة [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| date_time | System.DateTime | قيمة تاريخ-وقت يتم تمثيلها باستخدام جزء من تنسيق ISO RFC 8601. |

### Method: clone() {#clone__1}


```
 clone() 
```

ينسخ هذه المثيلة.

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Object | نسخة عضوية. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

يرجع قيمة السلسلة المحتواة بتنسيق XMP.

**Returns**

| نوع | الوصف |
| :- | :- |
| string | يعيد سلسلة تحتوي على تمثيل xmp |


