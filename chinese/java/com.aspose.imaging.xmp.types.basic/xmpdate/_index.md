---
title: "XmpDate"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 XMP 包中的日期。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.xmp.types.basic/xmpdate/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

表示 XMP 包中的日期。

日期时间值使用以下日期和时间格式子集表示：YYYY、YYYY-MM、YYYY-MM-DD、YYYY-MM-DDThh:mmTZD、YYYY-MM-DDThh:mm:ssTZD、YYYY-MM-DDThh:mm:ss.sTZD。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | 初始化 `XmpDate` 类的新实例。 |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | 初始化 `XmpDate` 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [ISO_8601_FORMAT](#ISO-8601-FORMAT) | ISO 8601（往返）格式字符串。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue()](#getValue--) | 获取或设置日期值。 |
| [setValue(Date value)](#setValue-java.util.Date-) | 获取或设置日期值。 |
| [getFormat()](#getFormat--) | 获取当前值的格式字符串。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 返回 XMP 格式中包含的字符串值。 |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


初始化 `XmpDate` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dateTime | java.util.Date | 日期时间值使用 ISO RFC 8601 格式的子集表示。 |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


初始化 `XmpDate` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dateString | java.lang.String | 日期的字符串表示形式。 |

### ISO_8601_FORMAT {#ISO-8601-FORMAT}
```
public static final String ISO_8601_FORMAT
```


ISO 8601（往返）格式字符串。

查看更多：[ here ][here].


[here]: https://en.wikipedia.org/wiki/ISO_8601

### getValue() {#getValue--}
```
public Date getValue()
```


获取或设置日期值。

值：日期值。

**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


获取或设置日期值。

值：日期值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### getFormat() {#getFormat--}
```
public String getFormat()
```


获取当前值的格式字符串。

值：当前值的格式字符串。

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


返回 XMP 格式中包含的字符串值。

**Returns:**
java.lang.String - 返回包含 xmp 表示的字符串
