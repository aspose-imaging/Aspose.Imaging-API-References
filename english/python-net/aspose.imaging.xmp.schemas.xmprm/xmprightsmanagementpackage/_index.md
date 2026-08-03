---
title: XmpRightsManagementPackage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.imaging.xmp.schemas.xmprm](/imaging/python-net/aspose.imaging.xmp.schemas.xmprm/)

**Full Name:** aspose.imaging.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | Initializes a new instance of the [XmpRightsManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/) class. |
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
| [set_certificate(certificate)](#set_certificate_certificate_6) | Sets the certificate. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_7) | Marks as right management content |
| [set_owners(owners)](#set_owners_owners_8) | Sets owners. |
| [set_prop_value(key, value)](#set_prop_value_key_value_9) | Sets the first XMP attribute or element value with by specified _key_. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_10) | Sets the usage terms. |
| [set_value(key, value)](#set_value_key_value_11) | Sets the value. |
| [set_value(key, value)](#set_value_key_value_12) | Sets the value. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_13) | Sets the web statement. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_14) | Sets the XMP type value. |
| [try_get_value(key, value)](#try_get_value_key_value_15) | Gets the value by the _key_. |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

Initializes a new instance of the [XmpRightsManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/) class.

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


### Method: set_certificate(certificate) {#set_certificate_certificate_6}


```
 set_certificate(certificate) 
```

Sets the certificate.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| certificate | string | The certificate. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_7}


```
 set_marked_as_right_management(value) 
```

Marks as right management content

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | bool | if set to <c>true</c> that this is a rights-managed resource. |

### Method: set_owners(owners) {#set_owners_owners_8}


```
 set_owners(owners) 
```

Sets owners.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| owners | string[] | The owners. |

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

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_10}


```
 set_usage_terms(usage_terms) 
```

Sets the usage terms.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| usage_terms | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | The usage terms. |

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

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_13}


```
 set_web_statement(web_statement_url) 
```

Sets the web statement.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| web_statement_url | string | The web statement URL. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_14}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | The value to set to. |

### Method: try_get_value(key, value) {#try_get_value_key_value_15}


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


