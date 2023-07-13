---
title: XmpBasicPackage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

Represents XMP basic namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpbaseschema](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.imaging.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.Imaging Version:** 23.6

The XmpBasicPackage type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__0) | Initializes a new instance of the [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) class. |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_1) | Initializes a new instance of the [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| xml_namespace | string | r | Gets the XML namespace. |
| prefix | string | r | Gets the prefix. |
| namespace_uri | string | r | Gets the namespace URI. |
| RATING_REJECTED [static] | int | r | Rating rejected value. |
| RATING_MIN [static] | int | r | Rating min value. |
| RATING_MAX [static] | int | r | Rating max value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [set_created_date(created_date)](#set_created_date_created_date_2) | Adds resource created date. |
| [set_created_date(created_date)](#set_created_date_created_date_3) | Adds resource created date. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_4) | Adds metadata last changed date. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_5) | Adds metadata last changed date. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_6) | Adds resource last modified date. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_7) | Adds resource last modified date. |
| [contains_key(key)](#contains_key_key_8) | Determines whether the specified key contains key. |
| [get_prop_value(key)](#get_prop_value_key_9) | Gets the object with the specified key. |
| [set_prop_value(key, value)](#set_prop_value_key_value_10) | Gets or sets the object with the specified key. |
| [add_value(key, value)](#add_value_key_value_11) | Adds string property. |
| [remove(key)](#remove_key_12) | Remove the value with the specified key. |
| clear() | Clears this instance. |
| [set_value(key, value)](#set_value_key_value_13) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_14) | Sets the XMP type value. |
| [get_xml_value()](#get_xml_value__15) | Converts XMP value to the XML representation. |
| [set_created_date_str(created_date)](#set_created_date_str_created_date_16) | Adds resource created date. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_17) | Sets the creator tool. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_18) | Sets the identifier. |
| [set_label(label)](#set_label_label_19) | Sets the label. |
| [set_metadata_date_str(metadata_date)](#set_metadata_date_str_metadata_date_20) | Adds metadata last changed date. |
| [set_modify_date_str(modified_date)](#set_modify_date_str_modified_date_21) | Adds resource last modified date. |
| [set_rating(choise)](#set_rating_choise_22) | Sets rating. |

### XmpBasicPackage() {#XmpBasicPackage__0}


```
 XmpBasicPackage() 
```

Initializes a new instance of the [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) class.

### XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_1}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Initializes a new instance of the [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| prefix | string | The prefix. |
| namespace_uri | string | The namespace URI. |

### set_created_date(created_date) {#set_created_date_created_date_2}


```
 set_created_date(created_date) 
```

Adds resource created date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| created_date | datetime | Created date. |

### set_created_date(created_date) {#set_created_date_created_date_3}


```
 set_created_date(created_date) 
```

Adds resource created date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| created_date | string | Created date. |

### set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_4}


```
 set_metadata_date(metadata_date) 
```

Adds metadata last changed date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| metadata_date | datetime | Metadata date. |

### set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_5}


```
 set_metadata_date(metadata_date) 
```

Adds metadata last changed date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| metadata_date | string | Metadata date. |

### set_modify_date(modified_date) {#set_modify_date_modified_date_6}


```
 set_modify_date(modified_date) 
```

Adds resource last modified date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| modified_date | datetime | Last modified date. |

### set_modify_date(modified_date) {#set_modify_date_modified_date_7}


```
 set_modify_date(modified_date) 
```

Adds resource last modified date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| modified_date | string | Last modified date. |

### contains_key(key) {#contains_key_key_8}


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


### get_prop_value(key) {#get_prop_value_key_9}


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


### set_prop_value(key, value) {#set_prop_value_key_value_10}


```
 set_prop_value(key, value) 
```

Gets or sets the object with the specified key.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |
| value | object | The object with the specified key. |

### add_value(key, value) {#add_value_key_value_11}


```
 add_value(key, value) 
```

Adds string property.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | string | The string value. |

### remove(key) {#remove_key_12}


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


### set_value(key, value) {#set_value_key_value_13}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue) | The value to add to. |

### set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_14}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | The value to set to. |

### get_xml_value() {#get_xml_value__15}


```
 get_xml_value() 
```

Converts XMP value to the XML representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the XMP value converted to the XML representation. |


### set_created_date_str(created_date) {#set_created_date_str_created_date_16}


```
 set_created_date_str(created_date) 
```

Adds resource created date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| created_date | string | Created date. |

### set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_17}


```
 set_creator_tool(creator_tool) 
```

Sets the creator tool.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| creator_tool | string | Name of tool. |

### set_identifier(idenfifier) {#set_identifier_idenfifier_18}


```
 set_identifier(idenfifier) 
```

Sets the identifier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| idenfifier | string | The idenfifier. |

### set_label(label) {#set_label_label_19}


```
 set_label(label) 
```

Sets the label.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| label | string | The label. |

### set_metadata_date_str(metadata_date) {#set_metadata_date_str_metadata_date_20}


```
 set_metadata_date_str(metadata_date) 
```

Adds metadata last changed date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| metadata_date | string | Metadata date. |

### set_modify_date_str(modified_date) {#set_modify_date_str_modified_date_21}


```
 set_modify_date_str(modified_date) 
```

Adds resource last modified date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| modified_date | string | Last modified date. |

### set_rating(choise) {#set_rating_choise_22}


```
 set_rating(choise) 
```

Sets rating.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| choise | int | From -1 till 5 |

