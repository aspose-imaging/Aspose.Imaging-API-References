---
title: "XmpDate 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.imaging.xmp.types.basic](/imaging/python-net/aspose.imaging.xmp.types.basic/)

**Full Name:** aspose.imaging.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | 初始化 [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) 类的新实例。 |
| [XmpDate(date_time)](#XmpDate_date_time_2) | 初始化 [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [static] | string | r | ISO 8601（往返）格式字符串。 |
| 格式 | string | r | 获取当前值的格式字符串。 |
| value | System.DateTime | r/w | 获取或设置日期值。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |
| [get_xmp_representation()](#get_xmp_representation__2) | 返回 XMP 格式的字符串值。 |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

初始化 [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| date_string | string | 日期的字符串表示形式。 |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

初始化 [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| date_time | System.DateTime | 使用 ISO RFC 8601 格式子集表示的日期时间值。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| Type | Description |
| :- | :- |
| System.Object | 成员逐个克隆。 |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

返回 XMP 格式的字符串值。

**Returns**

| Type | Description |
| :- | :- |
| string | 返回包含 xmp 表示的字符串 |


