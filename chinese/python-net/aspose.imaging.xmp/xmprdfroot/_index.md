---
title: "XmpRdfRoot 类"
type: docs
weight: 490
url: /zh/python-net/aspose.imaging.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | 初始化 [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) 类的新实例。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | 添加属性。 |
| clear_attributes() | 移除所有属性。 |
| [get_attribute(attribute)](#get_attribute_attribute_2) | 获取属性。 |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | 通过特定前缀获取命名空间 URI。前缀可以不带 xmlns 开头。 |
| [get_xml_value()](#get_xml_value__4) | 将 xmp 值转换为 xml 表示形式。 |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | 通过前缀添加命名空间 uri。前缀可以不带 xmlns 开头。 |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

初始化 [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) 类的新实例。

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

添加属性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 属性 | string | 属性。 |
| value | string | 值。 |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

获取属性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 属性 | string | 属性。 |

**Returns**

| Type | Description |
| :- | :- |
| string | 返回指定属性名称的属性。 |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

通过特定前缀获取命名空间 URI。前缀可以不带 xmlns 开头。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| prefix | string | 前缀。 |

**Returns**

| Type | Description |
| :- | :- |
| string | 返回包模式 URI。 |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

将 xmp 值转换为 xml 表示形式。

**Returns**

| Type | Description |
| :- | :- |
| string | 返回转换为 XML 字符串的 XMP 值。 |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

通过前缀添加命名空间 uri。前缀可以不带 xmlns 开头。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| prefix | string | 前缀。 |
| namespace_uri | string | 包的模式 URI。 |

