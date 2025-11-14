---
title: XmpMeta Class
type: docs
weight: 440
url: /python-net/aspose.imaging.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | Initializes a new instance of the [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) class. |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | Initializes a new instance of the [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Gets or set Adobe Xmp toolkit version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Adds the attribute. |
| clear_attributes() | Removes all attributes. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Gets the attribute. |
| [get_xml_value()](#get_xml_value__3) | Converts XMP value to the XML representation. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

Initializes a new instance of the [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) class.

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

Initializes a new instance of the [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| toolkit_version | string | Adobe XMP toolkit version. |

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


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Converts XMP value to the XML representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the XMP value converted to the XML representation. |


