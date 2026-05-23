---
title: "XmpRdfRoot Sınıfı"
type: docs
weight: 490
url: /tr/python-net/aspose.imaging.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | Yeni bir [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) sınıfı örneği başlatır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Özelliği ekler. |
| clear_attributes() | Tüm özellikleri kaldırır. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Özelliği alır. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Belirli bir önek ile ad alanı URI'sını alır. Önek xmlns olmadan başlayabilir. |
| [get_xml_value()](#get_xml_value__4) | xmp değerini xml temsiline dönüştürür. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Önek ile ad alanı URI'sı ekler. Önek xmlns olmadan başlayabilir. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

Yeni bir [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) sınıfı örneği başlatır.

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Özelliği ekler.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| attribute | string | Özellik. |
| değer | string | Değer. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Özelliği alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| attribute | string | Özellik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Belirtilen özellik adı için özelliği döndürür. |


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


```
 get_namespace_uri(prefix) 
```

Belirli bir önek ile ad alanı URI'sını alır. Önek xmlns olmadan başlayabilir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| prefix | string | Önek. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Bir paket şema URI'sı döndürür. |


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

xmp değerini xml temsiline dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | XMP değerini XML dizesine dönüştürülmüş olarak döndürür. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Önek ile ad alanı URI'sı ekler. Önek xmlns olmadan başlayabilir.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| prefix | string | Önek. |
| namespace_uri | string | Paket şema uri'si. |

