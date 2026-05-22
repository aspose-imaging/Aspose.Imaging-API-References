---
title: "Time 类"
type: docs
weight: 40
url: /zh/python-net/aspose.imaging.xmp.schemas.xmpdm/time/
---

**Summary:** Representation of a time value in seconds.

**Module:** [aspose.imaging.xmp.schemas.xmpdm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpdm.Time

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Time(scale, value)](#Time_scale_value_1) | 初始化 [Time](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/time/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| scale | [Rational](/imaging/python-net/aspose.imaging.xmp.types.derived/rational/) | r/w | 获取或设置时间值的比例。 |
| value | int | r/w | 获取或设置指定比例下的时间值。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |
| [get_xmp_representation()](#get_xmp_representation__2) | 获取 XMP 格式中包含的字符串值。 |


### Constructor: Time(scale, value) {#Time_scale_value_1}


```
 Time(scale, value) 
```

初始化 [Time](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/time/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| scale | [Rational](/imaging/python-net/aspose.imaging.xmp.types.derived/rational/) | 比例。 |
| value | int | 值。 |

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

获取 XMP 格式中包含的字符串值。

**Returns**

| Type | Description |
| :- | :- |
| string | 返回 XMP 格式中包含的字符串值。 |


