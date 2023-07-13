---
title: XmpRightsManagementPackage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

Represents XMP Rights Management namespace.

**Module:** [aspose.imaging.xmp.schemas.xmprm](/imaging/python-net/aspose.imaging.xmp.schemas.xmprm/)

**Full Name:** aspose.imaging.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.Imaging Version:** 23.6

The XmpRightsManagementPackage type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__0) | Initializes a new instance of the [XmpRightsManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/) class. |
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
| [set_certificate(certificate)](#set_certificate_certificate_9) | Sets the certificate. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_10) | Marks as right management content |
| [set_owners(owners)](#set_owners_owners_11) | Sets owners. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_12) | Sets the usage terms. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_13) | Sets the web statement. |

### XmpRightsManagementPackage() {#XmpRightsManagementPackage__0}


```
 XmpRightsManagementPackage() 
```

Initializes a new instance of the [XmpRightsManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/) class.

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


### set_certificate(certificate) {#set_certificate_certificate_9}


```
 set_certificate(certificate) 
```

Sets the certificate.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| certificate | string | The certificate. |

### set_marked_as_right_management(value) {#set_marked_as_right_management_value_10}


```
 set_marked_as_right_management(value) 
```

Marks as right management content

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| value | bool | if set to <c>true</c> that this is a rights-managed resource. |

### set_owners(owners) {#set_owners_owners_11}


```
 set_owners(owners) 
```

Sets owners.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| owners | string | The owners. |

### set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_12}


```
 set_usage_terms(usage_terms) 
```

Sets the usage terms.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| usage_terms | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt) | The usage terms. |

### set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_13}


```
 set_web_statement(web_statement_url) 
```

Sets the web statement.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| web_statement_url | string | The web statement URL. |

