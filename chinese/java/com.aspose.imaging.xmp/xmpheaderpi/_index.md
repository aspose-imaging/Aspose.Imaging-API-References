---
title: "XmpHeaderPi"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示 XMP 头部处理指令。"
type: docs
weight: 17
url: /zh/java/com.aspose.imaging.xmp/xmpheaderpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

表示 XMP 头部处理指令。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | 初始化 `XmpHeaderPi` 类的新实例。 |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | 初始化 `XmpHeaderPi` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getGuid()](#getGuid--) | 表示 Header Guid。 |
| [setGuid(String value)](#setGuid-java.lang.String-) | 表示 Header Guid。 |
| [getXmlValue()](#getXmlValue--) | 将 XMP 值转换为 XML 表示形式。 |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-) | 指示当前对象是否等于同类型的另一个对象。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 `System.Object` 是否等于此实例。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


初始化 `XmpHeaderPi` 类的新实例。

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


初始化 `XmpHeaderPi` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| guid | java.lang.String | 唯一标识符。 |

### getGuid() {#getGuid--}
```
public String getGuid()
```


表示 Header Guid。

标题 PI 的文本包含 GUID，这使得它不太可能在数据流中意外出现。

**Returns:**
java.lang.String
### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


表示 Header Guid。

标题 PI 的文本包含 GUID，这使得它不太可能在数据流中意外出现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


将 XMP 值转换为 XML 表示形式。

**Returns:**
java.lang.String - 返回转换为 XML 表示形式的 XMP 值。
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.imaging.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


指示当前对象是否等于同类型的另一个对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | 用于与此对象比较的对象。 |

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
