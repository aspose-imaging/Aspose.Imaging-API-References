---
title: "XmpGuid"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 XMP 全局唯一标识符。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.xmp.types.derived/xmpguid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpGuid extends XmpTypeBase
```

表示 XMP 全局唯一标识符。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpGuid(String value)](#XmpGuid-java.lang.String-) | 初始化 `XmpGuid` 类的新实例。 |
| [XmpGuid(UUID guid)](#XmpGuid-java.util.UUID-) | 初始化 `XmpGuid` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPrefix()](#getPrefix--) | 获取或设置类似 uuid 的前缀。 |
| [setPrefix(String value)](#setPrefix-java.lang.String-) | 获取或设置类似 uuid 的前缀。 |
| [getValue()](#getValue--) | 获取或设置该值。 |
| [setValue(UUID value)](#setValue-java.util.UUID-) | 获取或设置该值。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
### XmpGuid(String value) {#XmpGuid-java.lang.String-}
```
public XmpGuid(String value)
```


初始化 `XmpGuid` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 值。 |

### XmpGuid(UUID guid) {#XmpGuid-java.util.UUID-}
```
public XmpGuid(UUID guid)
```


初始化 `XmpGuid` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| guid | java.util.UUID | 唯一标识符。 |

### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


获取或设置类似 uuid 的前缀。

值：类似 uuid 的前缀。

**Returns:**
java.lang.String
### setPrefix(String value) {#setPrefix-java.lang.String-}
```
public void setPrefix(String value)
```


获取或设置类似 uuid 的前缀。

值：类似 uuid 的前缀。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getValue() {#getValue--}
```
public UUID getValue()
```


获取或设置该值。

值：该值。

**Returns:**
java.util.UUID
### setValue(UUID value) {#setValue-java.util.UUID-}
```
public void setValue(UUID value)
```


获取或设置该值。

值：该值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.UUID |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式中包含的字符串值。
