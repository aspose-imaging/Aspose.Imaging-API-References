---
title: XmpRdfRoot Class
type: docs
weight: 470
url: /python-net/aspose.imaging.xmp/xmprdfroot/
---

Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.Imaging Version:** 23.6

The XmpRdfRoot type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__0) | Initializes a new instance of the [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) class. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Adds the attribute. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Gets the attribute. |
| clear_attributes() | Removes all attributes. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_3) | Adds namespace uri by prefix. Prefix may start without xmlns. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_4) | Gets namespace URI by specific prefix. Prefix may start without xmlns. |
| [get_xml_value()](#get_xml_value__5) | Converts xmp value to the xml representation. |

### XmpRdfRoot() {#XmpRdfRoot__0}


```
 XmpRdfRoot() 
```

Initializes a new instance of the [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) class.

### add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Adds the attribute.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| attribute | string | The attribute. |
| value | string | The value. |

### get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Gets the attribute.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| attribute | string | The attribute. |

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the attribute for specified attribute name. |


### register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_3}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Adds namespace uri by prefix. Prefix may start without xmlns.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| prefix | string | The prefix. |
| namespace_uri | string | Package schema uri. |

### get_namespace_uri(prefix) {#get_namespace_uri_prefix_4}


```
 get_namespace_uri(prefix) 
```

Gets namespace URI by specific prefix. Prefix may start without xmlns.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| prefix | string | The prefix. |

**Returns**

| Type | Description |
| :- | :- |
| string | Returns a package schema URI. |


### get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Converts xmp value to the xml representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns XMP value converted to XML string. |


