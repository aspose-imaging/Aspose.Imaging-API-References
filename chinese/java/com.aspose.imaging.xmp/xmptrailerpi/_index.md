---
title: "XmpTrailerPi"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 XMP 尾部处理指令。"
type: docs
weight: 23
url: /zh/java/com.aspose.imaging.xmp/xmptrailerpi/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

表示 XMP 尾部处理指令。

应由数据包扫描处理器使用 end="w" 或 end="r" 部分，以确定 XMP 是否可以就地修改。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | 初始化 `XmpTrailerPi` 类的新实例。 |
| [XmpTrailerPi()](#XmpTrailerPi--) | 初始化 `XmpTrailerPi` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isWritable()](#isWritable--) | 获取或设置指示此实例是否可写的值。 |
| [setWritable(boolean value)](#setWritable-boolean-) | 获取或设置指示此实例是否可写的值。 |
| [getXmlValue()](#getXmlValue--) | 将 xmp 值转换为 xml 表示形式。 |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-) | 指示当前对象是否等于同类型的另一个对象。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 `System.Object` 是否等于此实例。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


初始化 `XmpTrailerPi` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isWritable | boolean | 指示 trailer 是否可写。 |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


初始化 `XmpTrailerPi` 类的新实例。

### isWritable() {#isWritable--}
```
public boolean isWritable()
```


获取或设置指示此实例是否可写的值。

值：如果此实例可写，则为 `true`；否则为 `false`。

**Returns:**
boolean
### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


获取或设置指示此实例是否可写的值。

值：如果此实例可写，则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


将 xmp 值转换为 xml 表示形式。

**Returns:**
java.lang.String - 返回 XMP 的 XML 表示形式。
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.imaging.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


指示当前对象是否等于同类型的另一个对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | 用于与此对象比较的对象。 |

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
| obj | java.lang.Object | 要与此实例比较的 `System.Object`。 |

**Returns:**
boolean - 如果指定的 `System.Object` 等于此实例，则为 `true`；否则，为 `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
