---
title: "Timecode"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示视频中的时间码值。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.xmp.schemas.xmpdm/timecode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public final class Timecode extends XmpTypeBase implements System.IEquatable<Timecode>
```

表示视频中的时间码值。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Timecode(TimeFormat format, String timeValue)](#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-) | 初始化 `Timecode` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) | 获取或设置在 `TimeValue` 中使用的格式。 |
| [setFormat(TimeFormat value)](#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-) | 获取或设置在 `TimeValue` 中使用的格式。 |
| [getTimeValue()](#getTimeValue--) | 获取或设置指定格式下的时间值。 |
| [setTimeValue(String value)](#setTimeValue-java.lang.String-) | 获取或设置指定格式下的时间值。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 返回 XMP 格式中包含的字符串值。 |
| [isEquals(Timecode other)](#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-) | 指示当前对象是否等于同类型的另一个对象。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 `System.Object` 是否等于此实例。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
### Timecode(TimeFormat format, String timeValue) {#Timecode-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-java.lang.String-}
```
public Timecode(TimeFormat format, String timeValue)
```


初始化 `Timecode` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) | 时间格式。 |
| timeValue | java.lang.String | 时间值。 |

### getFormat() {#getFormat--}
```
public TimeFormat getFormat()
```


获取或设置在 `TimeValue` 中使用的格式。

值：在 `TimeValue` 中使用的格式。

**Returns:**
[TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat)
### setFormat(TimeFormat value) {#setFormat-com.aspose.imaging.xmp.schemas.xmpdm.TimeFormat-}
```
public void setFormat(TimeFormat value)
```


获取或设置在 `TimeValue` 中使用的格式。

值：在 `TimeValue` 中使用的格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TimeFormat](../../com.aspose.imaging.xmp.schemas.xmpdm/timeformat) |  |

### getTimeValue() {#getTimeValue--}
```
public String getTimeValue()
```


获取或设置指定格式下的时间值。

值：指定格式下的时间值。

**Returns:**
java.lang.String
### setTimeValue(String value) {#setTimeValue-java.lang.String-}
```
public void setTimeValue(String value)
```


获取或设置指定格式下的时间值。

值：指定格式下的时间值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


返回 XMP 格式中包含的字符串值。

**Returns:**
java.lang.String - 返回包含 xmp 表示的字符串。
### isEquals(Timecode other) {#isEquals-com.aspose.imaging.xmp.schemas.xmpdm.Timecode-}
```
public boolean isEquals(Timecode other)
```


指示当前对象是否等于同类型的另一个对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [Timecode](../../com.aspose.imaging.xmp.schemas.xmpdm/timecode) | 用于与此对象比较的对象。 |

**Returns:**
boolean - 如果当前对象等于 `other` 参数则为 true；否则为 false。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 `System.Object` 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 与此实例比较的 `System.Object`。 |

**Returns:**
boolean - 如果指定的 `System.Object` 等于此实例，则为 `true`；否则，为 `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
