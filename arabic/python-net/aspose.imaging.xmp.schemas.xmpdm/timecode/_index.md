---
title: "الفئة Timecode"
type: docs
weight: 60
url: /ar/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/
---

**Summary:** Represents timecode value in video.

**Module:** [aspose.imaging.xmp.schemas.xmpdm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpdm.Timecode

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Timecode(format, time_value)](#Timecode_format_time_value_1) | ينشئ مثلاً جديداً من الفئة [Timecode](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| format | [TimeFormat](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timeformat/) | r/w | يحصل أو يضبط التنسيق المستخدم في [Timecode.time_value](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/). |
| time_value | string | r/w | يحصل أو يضبط قيمة الوقت بالتنسيق المحدد. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينسخ هذه المثيلة. |
| [get_xmp_representation()](#get_xmp_representation__2) | يرجع القيمة النصية المحتواة بتنسيق XMP. |


### Constructor: Timecode(format, time_value) {#Timecode_format_time_value_1}


```
 Timecode(format, time_value) 
```

ينشئ مثلاً جديداً من الفئة [Timecode](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| format | [TimeFormat](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timeformat/) | تنسيق الوقت. |
| time_value | string | قيمة الوقت. |

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

يرجع القيمة النصية المحتواة بتنسيق XMP.

**Returns**

| نوع | الوصف |
| :- | :- |
| string | يرجع السلسلة التي تحتوي على تمثيل xmp. |


