---
title: "XmpPacketWrapper"
second_title: "Aspose.Imaging for Java API 参考"
description: "包含包括标头和尾部的序列化 XMP 包。"
type: docs
weight: 21
url: /zh/java/com.aspose.imaging.xmp/xmppacketwrapper/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), [com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class XmpPacketWrapper implements IXmlValue, IImageMetadataFormat
```

包含包括标头和尾部的序列化 XMP 包。

一个由一对 XML 处理指令（PIs）组成的包装器可以放置在 rdf:RDF 元素周围。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-) | 初始化 `XmpPacketWrapper` 类的新实例。 |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | 初始化 `XmpPacketWrapper` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeaderPi()](#getHeaderPi--) | 获取头部处理指令。 |
| [getMeta()](#getMeta--) | 获取 XMP 元数据。 |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.imaging.xmp.XmpMeta-) | 设置 XMP 元数据。 |
| [getTrailerPi()](#getTrailerPi--) | 获取尾部处理指令。 |
| [getPackages()](#getPackages--) | 获取 XMP 中的 `XmpPackage` 数组。 |
| [getPackagesCount()](#getPackagesCount--) | 获取 XMP 结构中包的数量。 |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.imaging.xmp.XmpPackage-) | 添加该包。 |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | 通过命名空间 URI 获取包。 |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | 确定包是否存在于 XMP 包装器中。 |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.imaging.xmp.XmpPackage-) | 移除 XMP 包。 |
| [clearPackages()](#clearPackages--) | 移除 XMP 中的所有 `XmpPackage`。 |
| [getXmlValue()](#getXmlValue--) | 将 XMP 值转换为 XML 表示形式。 |
| [toString()](#toString--) | 返回表示当前对象的 XML 字符串。 |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.imaging.xmp.XmpHeaderPi-com.aspose.imaging.xmp.XmpTrailerPi-com.aspose.imaging.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


初始化 `XmpPacketWrapper` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) | 处理指令的 XMP 头部。 |
| trailer | [XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) | 处理指令的 XMP 尾部。 |
| xmpMeta | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | XMP 元数据。 |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


初始化 `XmpPacketWrapper` 类的新实例。

### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


获取头部处理指令。

**Returns:**
[XmpHeaderPi](../../com.aspose.imaging.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


获取 XMP 元数据。可选。

**Returns:**
[XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) - The XMP meta. Optional.
### setMeta(XmpMeta value) {#setMeta-com.aspose.imaging.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


设置 XMP 元数据。可选。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | XMP 元数据。可选。 |

### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


获取尾部处理指令。

**Returns:**
[XmpTrailerPi](../../com.aspose.imaging.xmp/xmptrailerpi) - Trailer processing instruction.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


获取 XMP 中的 `XmpPackage` 数组。

**Returns:**
com.aspose.imaging.xmp.XmpPackage[] - XMP 中的 `XmpPackage` 数组。
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


获取 XMP 结构中包的数量。

**Returns:**
int - XMP 结构中包的数量。
### addPackage(XmpPackage package_) {#addPackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


添加该包。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | 该包。 |

### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


通过命名空间 URI 获取包。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| namespaceUri | java.lang.String | 包的模式 URI。 |

**Returns:**
[XmpPackage](../../com.aspose.imaging.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


确定包是否存在于 XMP 包装器中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| namespaceUri | java.lang.String | 包架构 URI。 |

**Returns:**
boolean - 如果在 XMP 包装器中存在具有指定命名空间 Uri 的包，则返回 true。
### removePackage(XmpPackage package_) {#removePackage-com.aspose.imaging.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


移除 XMP 包。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.imaging.xmp/xmppackage) | 该包。 |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


移除 XMP 中的所有 `XmpPackage`。

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


将 XMP 值转换为 XML 表示形式。

**Returns:**
java.lang.String - 返回转换后的 XMP 值为 XML。
### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的 XML 字符串。

**Returns:**
java.lang.String - 表示当前对象的 XML 字符串。
