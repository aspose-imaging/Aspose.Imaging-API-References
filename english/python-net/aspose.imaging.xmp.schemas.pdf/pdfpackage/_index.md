---
title: PdfPackage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.imaging.xmp.schemas.pdf](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/)

**Full Name:** aspose.imaging.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.Imaging Version:** 23.10.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Initializes a new instance of the [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Gets the namespace URI. |
| prefix | string | r | Gets the prefix. |
| xml_namespace | string | r | Gets the XML namespace. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Adds string property. |
| clear() | Clears this instance. |
| [contains_key(key)](#contains_key_key_2) | Determines whether the specified key contains key. |
| [get_prop_value(key)](#get_prop_value_key_3) | Gets the object with the specified key. |
| [get_xml_value()](#get_xml_value__4) | Converts XMP value to the XML representation. |
| [remove(key)](#remove_key_5) | Remove the value with the specified key. |
| [set_keywords(keywords)](#set_keywords_keywords_6) | Sets the keywords. |
| [set_pdf_version(version)](#set_pdf_version_version_7) | Sets the PDF version. |
| [set_producer(producer)](#set_producer_producer_8) | Sets the name of the tool that created Pdf. |
| [set_prop_value(key, value)](#set_prop_value_key_value_9) | Gets or sets the object with the specified key. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_10) | Sets the trapped. |
| [set_value(key, value)](#set_value_key_value_11) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_12) | Sets the XMP type value. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Initializes a new instance of the [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/) class.

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Adds string property.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | string | The string value. |

### Method: contains_key(key) {#contains_key_key_2}


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


### Method: get_prop_value(key) {#get_prop_value_key_3}


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


### Method: get_xml_value() {#get_xml_value__4}


```
 get_xml_value() 
```

Converts XMP value to the XML representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the XMP value converted to the XML representation. |


### Method: remove(key) {#remove_key_5}


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


### Method: set_keywords(keywords) {#set_keywords_keywords_6}


```
 set_keywords(keywords) 
```

Sets the keywords.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| keywords | string | The keywords. |

### Method: set_pdf_version(version) {#set_pdf_version_version_7}


```
 set_pdf_version(version) 
```

Sets the PDF version.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| version | string | Pdf version, for example: 1.0, 1.3 etc. |

### Method: set_producer(producer) {#set_producer_producer_8}


```
 set_producer(producer) 
```

Sets the name of the tool that created Pdf.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| producer | string | The producer name. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_9}


```
 set_prop_value(key, value) 
```

Gets or sets the object with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |
| value | object | The object with the specified key. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_10}


```
 set_trapped(is_trapped) 
```

Sets the trapped.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| is_trapped | bool | if set to <c>true</c> the document has been trapped. |

### Method: set_value(key, value) {#set_value_key_value_11}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue) | The value to add to. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_12}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | The value to set to. |

