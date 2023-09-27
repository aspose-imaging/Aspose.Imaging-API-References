---
title: XmpDate Class
type: docs
weight: 20
url: /python-net/aspose.imaging.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.imaging.xmp.types.basic](/imaging/python-net/aspose.imaging.xmp.types.basic/)

**Full Name:** aspose.imaging.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

**Aspose.Imaging Version:** 23.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | Initializes a new instance of the [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) class. |
| [XmpDate(date_time)](#XmpDate_date_time_2) | Initializes a new instance of the [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [static] | string | r | The ISO 8601 (roundtrip) format string. |
| format | string | r | Gets the format string for current value. |
| value | datetime | r/w | Gets or sets the date value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | Returns string contained value in XMP format. |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

Initializes a new instance of the [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| date_string | string | The string representation of date. |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

Initializes a new instance of the [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| date_time | datetime | A date-time value which is represented using a subset of ISO RFC 8601 formatting. |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

Returns string contained value in XMP format.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns string contained value in XMP format. |


