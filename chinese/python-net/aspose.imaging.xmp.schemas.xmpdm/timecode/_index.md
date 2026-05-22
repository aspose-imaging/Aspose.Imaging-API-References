---
title: "Timecode 类"
type: docs
weight: 60
url: /zh/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/
---

**Summary:** Represents timecode value in video.

**Module:** [aspose.imaging.xmp.schemas.xmpdm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpdm.Timecode

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Timecode(format, time_value)](#Timecode_format_time_value_1) | 初始化 [Timecode](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| format | [TimeFormat](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timeformat/) | r/w | 获取或设置在 [Timecode.time_value](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/) 中使用的格式。 |
| time_value | string | r/w | 获取或设置指定格式下的时间值。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |
| [get_xmp_representation()](#get_xmp_representation__2) | 返回 XMP 格式中包含的字符串值。 |


### Constructor: Timecode(format, time_value) {#Timecode_format_time_value_1}


```
 Timecode(format, time_value) 
```

初始化 [Timecode](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| format | [TimeFormat](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timeformat/) | 时间格式。 |
| time_value | string | 时间值。 |

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

返回 XMP 格式中包含的字符串值。

**Returns**

| Type | Description |
| :- | :- |
| string | 返回包含 xmp 表示的字符串。 |


