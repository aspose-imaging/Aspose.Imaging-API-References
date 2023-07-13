---
title: PdfPackage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/
---

Represents Adobe Pdf namespace.

**Module:** [aspose.imaging.xmp.schemas.pdf](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/)

**Full Name:** aspose.imaging.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.Imaging Version:** 23.6

The PdfPackage type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [PdfPackage()](#PdfPackage__0) | Initializes a new instance of the [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| xml_namespace | string | r | Gets the XML namespace. |
| prefix | string | r | Gets the prefix. |
| namespace_uri | string | r | Gets the namespace URI. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [contains_key(key)](#contains_key_key_1) | Determines whether the specified key contains key. |
| [get_prop_value(key)](#get_prop_value_key_2) | Gets the object with the specified key. |
| [set_prop_value(key, value)](#set_prop_value_key_value_3) | Gets or sets the object with the specified key. |
| [add_value(key, value)](#add_value_key_value_4) | Adds string property. |
| [remove(key)](#remove_key_5) | Remove the value with the specified key. |
| clear() | Clears this instance. |
| [set_value(key, value)](#set_value_key_value_6) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_7) | Sets the XMP type value. |
| [get_xml_value()](#get_xml_value__8) | Converts XMP value to the XML representation. |
| [set_keywords(keywords)](#set_keywords_keywords_9) | Sets the keywords. |
| [set_pdf_version(version)](#set_pdf_version_version_10) | Sets the PDF version. |
| [set_producer(producer)](#set_producer_producer_11) | Sets the name of the tool that created Pdf. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_12) | Sets the trapped. |

### PdfPackage() {#PdfPackage__0}


```
 PdfPackage() 
```

Initializes a new instance of the [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/) class.

### contains_key(key) {#contains_key_key_1}


```
 contains_key(key) 
```

Determines whether the specified key contains key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key to be checked. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Returns true if the specified key contains key. |


### get_prop_value(key) {#get_prop_value_key_2}


```
 get_prop_value(key) 
```

Gets the object with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |

**Returns**

| Type | Description |
| :- | :- |
| object | Returns the object with the specified key. |


### set_prop_value(key, value) {#set_prop_value_key_value_3}


```
 set_prop_value(key, value) 
```

Gets or sets the object with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |
| value | object | The object with the specified key. |

### add_value(key, value) {#add_value_key_value_4}


```
 add_value(key, value) 
```

Adds string property.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | string | The string value. |

### remove(key) {#remove_key_5}


```
 remove(key) 
```

Remove the value with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with removed value. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Returns true if the value with the specified key was removed. |


### set_value(key, value) {#set_value_key_value_6}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue) | The value to add to. |

### set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_7}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | The value to set to. |

### get_xml_value() {#get_xml_value__8}


```
 get_xml_value() 
```

Converts XMP value to the XML representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the XMP value converted to the XML representation. |


### set_keywords(keywords) {#set_keywords_keywords_9}


```
 set_keywords(keywords) 
```

Sets the keywords.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| keywords | string | The keywords. |

### set_pdf_version(version) {#set_pdf_version_version_10}


```
 set_pdf_version(version) 
```

Sets the PDF version.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| version | string | Pdf version, for example: 1.0, 1.3 etc. |

### set_producer(producer) {#set_producer_producer_11}


```
 set_producer(producer) 
```

Sets the name of the tool that created Pdf.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| producer | string | The producer name. |

### set_trapped(is_trapped) {#set_trapped_is_trapped_12}


```
 set_trapped(is_trapped) 
```

Sets the trapped.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| is_trapped | bool | if set to <c>true</c> the document has been trapped. |

