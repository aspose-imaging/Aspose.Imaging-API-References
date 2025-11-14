---
title: XmpRdfRoot Class
type: docs
weight: 490
url: /python-net/aspose.imaging.xmp/xmprdfroot/
---

**Summary:** Represents rdf:RDF element.<br/>            A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpRdfRoot

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpRdfRoot()](#XmpRdfRoot__1) | Initializes a new instance of the [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) class. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Adds the attribute. |
| clear_attributes() | Removes all attributes. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Gets the attribute. |
| [get_namespace_uri(prefix)](#get_namespace_uri_prefix_3) | Gets namespace URI by specific prefix. Prefix may start without xmlns. |
| [get_xml_value()](#get_xml_value__4) | Converts xmp value to the xml representation. |
| [register_namespace_uri(prefix, namespace_uri)](#register_namespace_uri_prefix_namespace_uri_5) | Adds namespace uri by prefix. Prefix may start without xmlns. |


### Constructor: XmpRdfRoot() {#XmpRdfRoot__1}


```
 XmpRdfRoot() 
```

Initializes a new instance of the [XmpRdfRoot](/imaging/python-net/aspose.imaging.xmp/xmprdfroot/) class.

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Adds the attribute.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| attribute | string | The attribute. |
| value | string | The value. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


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


### Method: get_namespace_uri(prefix) {#get_namespace_uri_prefix_3}


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


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Converts xmp value to the xml representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns XMP value converted to XML string. |


### Method: register_namespace_uri(prefix, namespace_uri) {#register_namespace_uri_prefix_namespace_uri_5}


```
 register_namespace_uri(prefix, namespace_uri) 
```

Adds namespace uri by prefix. Prefix may start without xmlns.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| prefix | string | The prefix. |
| namespace_uri | string | Package schema uri. |

