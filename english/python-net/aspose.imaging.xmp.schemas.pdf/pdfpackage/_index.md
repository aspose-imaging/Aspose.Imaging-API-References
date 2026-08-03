---
title: PdfPackage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.imaging.xmp.schemas.pdf](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/)

**Full Name:** aspose.imaging.xmp.schemas.pdf.PdfPackage

**Inheritance:** XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Initializes a new instance of the [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Gets the XMP key count. |
| keys | System.Collections.Generic.ICollection`1[[System.String]] | r | Gets the keys in XMP package. |
| namespace_uri | string | r | Gets the namespace URI. |
| prefix | string | r | Gets the prefix. |
| xml_namespace | string | r | Gets the XML namespace. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Adds string property. |
| [add_value(key, value)](#add_value_key_value_2) | Adds string property. |
| clear() | Clears this instance. |
| [contains_key(key)](#contains_key_key_3) | Determines whether this collection specified key. |
| [get_prop_value(key)](#get_prop_value_key_4) | Gets the first XMP attribute or element value with by specified _key_. |
| [remove(key)](#remove_key_5) | Removes the first element or attribute value with the specified key. |
| [set_keywords(keywords)](#set_keywords_keywords_6) | Sets the keywords. |
| [set_pdf_version(version)](#set_pdf_version_version_7) | Sets the PDF version. |
| [set_producer(producer)](#set_producer_producer_8) | Sets the name of the tool that created Pdf. |
| [set_prop_value(key, value)](#set_prop_value_key_value_9) | Sets the first XMP attribute or element value with by specified _key_. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_10) | Sets the trapped. |
| [set_value(key, value)](#set_value_key_value_11) | Sets the value. |
| [set_value(key, value)](#set_value_key_value_12) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | Sets the XMP type value. |
| [try_get_value(key, value)](#try_get_value_key_value_14) | Gets the value by the _key_. |


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

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Adds string property.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | System.Object | The string value. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Determines whether this collection specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key to be checked. |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True** if the  contains the specified key; otherwise, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Gets the first XMP attribute or element value with by specified _key_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |

**Returns**

| Type | Description |
| :- | :- |
| [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) | Returns the [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) by the specified key. |


### Method: remove(key) {#remove_key_5}


```
 remove(key) 
```

Removes the first element or attribute value with the specified key.

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

Sets the first XMP attribute or element value with by specified _key_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |
| value | [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) | The [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) value. |

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
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | The value to add to. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | The value to add to. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | The value to set to. |

### Method: try_get_value(key, value) {#try_get_value_key_value_14}


```
 try_get_value(key, value) 
```

Gets the value by the _key_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The XMP element key. |
| value | [XmpValue[]](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) | The XMP value. |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True**, if the  contains the _key_; otherwise, **False**. |


