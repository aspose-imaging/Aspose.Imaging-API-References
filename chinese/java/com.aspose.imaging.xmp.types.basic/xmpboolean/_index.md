---
title: "XmpBoolean"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 XMP 布尔基本类型。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.xmp.types.basic/xmpboolean/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)
```
public final class XmpBoolean extends XmpTypeBase
```

表示 XMP 布尔基本类型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpBoolean(boolean value)](#XmpBoolean-boolean-) | 基于布尔值初始化 `XmpBoolean` 类的新实例。 |
| [XmpBoolean()](#XmpBoolean--) | 使用默认值初始化 `XmpBoolean` 类的新实例。 |
| [XmpBoolean(String value)](#XmpBoolean-java.lang.String-) | 初始化 `XmpBoolean` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue()](#getValue--) | 获取或设置一个值，指示此 `XmpBoolean` 是否有值。 |
| [setValue(boolean value)](#setValue-boolean-) | 获取或设置一个值，指示此 `XmpBoolean` 是否有值。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 返回 XMP 格式中包含的字符串值。 |
### XmpBoolean(boolean value) {#XmpBoolean-boolean-}
```
public XmpBoolean(boolean value)
```


基于布尔值初始化 `XmpBoolean` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 布尔值。允许的值为 True 或 False。 |

### XmpBoolean() {#XmpBoolean--}
```
public XmpBoolean()
```


使用默认值初始化 `XmpBoolean` 类的新实例。

### XmpBoolean(String value) {#XmpBoolean-java.lang.String-}
```
public XmpBoolean(String value)
```


初始化 `XmpBoolean` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 值。 |

### getValue() {#getValue--}
```
public boolean getValue()
```


获取或设置一个值，指示此 `XmpBoolean` 是否有值。

值：如果有值则为 `true`，否则为 `false`。

**Returns:**
boolean
### setValue(boolean value) {#setValue-boolean-}
```
public void setValue(boolean value)
```


获取或设置一个值，指示此 `XmpBoolean` 是否有值。

值：如果有值则为 `true`，否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


返回 XMP 格式中包含的字符串值。

**Returns:**
java.lang.String - 返回包含 xmp 表示的字符串。
