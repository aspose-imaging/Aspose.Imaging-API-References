---
title: "XmpMeta"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示 XMP 元数据。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.xmp/xmpmeta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging/xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

表示 xmp 元数据。可选。此元素的目的是在可能包含其他非 XMP RDF 用法的通用 XML 文本中识别 XMP 元数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | 初始化 `XmpMeta` 类的新实例。 |
| [XmpMeta()](#XmpMeta--) | 初始化 `XmpMeta` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | 获取或设置 Adobe Xmp 工具包版本。 |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | 获取或设置 Adobe Xmp 工具包版本。 |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | 添加属性。 |
| [getXmlValue()](#getXmlValue--) | 将 XMP 值转换为 XML 表示形式。 |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.imaging.xmp.XmpMeta-) | 指示当前对象是否等于同类型的另一个对象。 |
| [equals(Object other)](#equals-java.lang.Object-) | 确定指定的 `System.Object` 是否等于此实例。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


初始化 `XmpMeta` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Adobe XMP 工具包版本。 |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


初始化 `XmpMeta` 类的新实例。

### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


获取或设置 Adobe Xmp 工具包版本。

**Returns:**
java.lang.String
### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


获取或设置 Adobe Xmp 工具包版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


添加属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性。 |
| value | java.lang.String | 值。 |

### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


将 XMP 值转换为 XML 表示形式。

**Returns:**
java.lang.String - 返回转换为 XML 表示形式的 XMP 值。
### isEquals(XmpMeta other) {#isEquals-com.aspose.imaging.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


指示当前对象是否等于同类型的另一个对象。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.imaging.xmp/xmpmeta) | 用于与此对象比较的对象。 |

**Returns:**
boolean - 如果当前对象等于 `other` 参数则为 true；否则为 false。
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


确定指定的 `System.Object` 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | java.lang.Object | 与此实例比较的 `System.Object`。 |

**Returns:**
boolean - 如果指定的 `System.Object` 等于此实例，则为 `true`；否则，为 `false`。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
