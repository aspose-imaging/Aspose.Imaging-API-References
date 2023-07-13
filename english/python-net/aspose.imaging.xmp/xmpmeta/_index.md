---
title: XmpMeta Class
type: docs
weight: 420
url: /python-net/aspose.imaging.xmp/xmpmeta/
---

Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.Imaging Version:** 23.6

The XmpMeta type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_0) | Initializes a new instance of the [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) class. |
| [XmpMeta()](#XmpMeta__1) | Initializes a new instance of the [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Gets or set Adobe Xmp toolkit version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_2) | Adds the attribute. |
| [get_attribute(attribute)](#get_attribute_attribute_3) | Gets the attribute. |
| clear_attributes() | Removes all attributes. |
| [get_xml_value()](#get_xml_value__4) | Converts XMP value to the XML representation. |

### XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_0}


```
 XmpMeta(toolkit_version) 
```

Initializes a new instance of the [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| toolkit_version | string | Adobe XMP toolkit version. |

### XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

Initializes a new instance of the [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) class.

### add_attribute(attribute, value) {#add_attribute_attribute_value_2}


```
 add_attribute(attribute, value) 
```

Adds the attribute.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| attribute | string | The attribute. |
| value | string | The value. |

### get_attribute(attribute) {#get_attribute_attribute_3}


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


### get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Converts XMP value to the XML representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the XMP value converted to the XML representation. |


