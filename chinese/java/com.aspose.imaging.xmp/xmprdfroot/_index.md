---
title: "XmpRdfRoot"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 rdfRDF 元素。"
type: docs
weight: 22
url: /zh/java/com.aspose.imaging.xmp/xmprdfroot/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.XmpElementBase](../../com.aspose.imaging.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IXmlValue](../../com.aspose.imaging.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

表示 rdf:RDF 元素。单个 XMP 包应使用单个 rdf:RDF XML 元素进行序列化。rdf:RDF 元素的内容应仅包含零个或多个 rdf:Description 元素。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | 初始化 `XmpRdfRoot` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | 通过前缀添加命名空间 uri。 |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | 通过特定前缀获取命名空间 URI。 |
| [getXmlValue()](#getXmlValue--) | 将 xmp 值转换为 xml 表示形式。 |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


初始化 `XmpRdfRoot` 类的新实例。

### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


通过前缀添加命名空间 uri。前缀可以不以 xmlns 开头。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 前缀 | java.lang.String | 前缀。 |
| namespaceUri | java.lang.String | 包架构 URI。 |

### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


通过特定前缀获取命名空间 URI。前缀可以不以 xmlns 开头。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 前缀 | java.lang.String | 前缀。 |

**Returns:**
java.lang.String - 返回包的模式 URI。
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


将 xmp 值转换为 xml 表示形式。

**Returns:**
java.lang.String - 返回转换为 XML 字符串的 XMP 值。
