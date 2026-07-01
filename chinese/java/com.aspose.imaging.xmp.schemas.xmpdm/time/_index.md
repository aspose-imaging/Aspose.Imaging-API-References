---
title: "时间"
second_title: "Aspose.Imaging for Java API 参考"
description: "以秒为单位的时间值表示。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.xmp.schemas.xmpdm/time/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

以秒为单位的时间值表示。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.imaging.xmp.types.derived.Rational-int-) | 初始化 `Time` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getScale()](#getScale--) | 获取或设置时间值的比例。 |
| [setScale(Rational value)](#setScale-com.aspose.imaging.xmp.types.derived.Rational-) | 获取或设置时间值的比例。 |
| [getValue()](#getValue--) | 获取或设置指定比例下的时间值。 |
| [setValue(int value)](#setValue-int-) | 获取或设置指定比例下的时间值。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
### Time(Rational scale, int value) {#Time-com.aspose.imaging.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


初始化 `Time` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) | 比例。 |
| 值 | int | 值。 |

### getScale() {#getScale--}
```
public Rational getScale()
```


获取或设置时间值的比例。

对于 NTSC，使用 1001/30000，或不太精确的 100/2997。对于 PAL，使用 1/25。值：时间值的比例。

**Returns:**
[Rational](../../com.aspose.imaging.xmp.types.derived/rational)
### setScale(Rational value) {#setScale-com.aspose.imaging.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


获取或设置时间值的比例。

对于 NTSC，使用 1001/30000，或不太精确的 100/2997。对于 PAL，使用 1/25。值：时间值的比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rational](../../com.aspose.imaging.xmp.types.derived/rational) |  |

### getValue() {#getValue--}
```
public int getValue()
```


获取或设置指定比例下的时间值。

值：指定比例下的时间值。

**Returns:**
int
### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


获取或设置指定比例下的时间值。

值：指定比例下的时间值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式中包含的字符串值。
