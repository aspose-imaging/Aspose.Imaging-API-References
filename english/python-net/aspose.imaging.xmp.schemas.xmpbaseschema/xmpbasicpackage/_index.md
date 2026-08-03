---
title: XmpBasicPackage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpbaseschema](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.imaging.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Initializes a new instance of the [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) class. |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Initializes a new instance of the [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Rating max value. |
| RATING_MIN [static] | int | r | Rating min value. |
| RATING_REJECTED [static] | int | r | Rating rejected value. |
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
| [set_created_date(created_date)](#set_created_date_created_date_6) | Adds resource created date. |
| [set_created_date(created_date)](#set_created_date_created_date_7) | Adds resource created date. |
| [set_created_date_str(created_date)](#set_created_date_str_created_date_8) | Adds resource created date. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_9) | Sets the creator tool. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_10) | Sets the identifier. |
| [set_label(label)](#set_label_label_11) | Sets the label. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_12) | Adds metadata last changed date. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_13) | Adds metadata last changed date. |
| [set_metadata_date_str(metadata_date)](#set_metadata_date_str_metadata_date_14) | Adds metadata last changed date. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_15) | Adds resource last modified date. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_16) | Adds resource last modified date. |
| [set_modify_date_str(modified_date)](#set_modify_date_str_modified_date_17) | Adds resource last modified date. |
| [set_prop_value(key, value)](#set_prop_value_key_value_18) | Sets the first XMP attribute or element value with by specified _key_. |
| [set_rating(choise)](#set_rating_choise_19) | Sets rating. |
| [set_value(key, value)](#set_value_key_value_20) | Sets the value. |
| [set_value(key, value)](#set_value_key_value_21) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_22) | Sets the XMP type value. |
| [try_get_value(key, value)](#try_get_value_key_value_23) | Gets the value by the _key_. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Initializes a new instance of the [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) class.

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Initializes a new instance of the [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| prefix | string | The prefix. |
| namespace_uri | string | The namespace URI. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

Adds resource created date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| created_date | System.DateTime | Created date. |

### Method: set_created_date(created_date) {#set_created_date_created_date_7}


```
 set_created_date(created_date) 
```

Adds resource created date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| created_date | string | Created date. |

### Method: set_created_date_str(created_date) {#set_created_date_str_created_date_8}


```
 set_created_date_str(created_date) 
```

Adds resource created date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| created_date | string | Created date. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_9}


```
 set_creator_tool(creator_tool) 
```

Sets the creator tool.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| creator_tool | string | Name of tool. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_10}


```
 set_identifier(idenfifier) 
```

Sets the identifier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| idenfifier | string[] | The idenfifier. |

### Method: set_label(label) {#set_label_label_11}


```
 set_label(label) 
```

Sets the label.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| label | string | The label. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_12}


```
 set_metadata_date(metadata_date) 
```

Adds metadata last changed date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| metadata_date | System.DateTime | Metadata date. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_13}


```
 set_metadata_date(metadata_date) 
```

Adds metadata last changed date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| metadata_date | string | Metadata date. |

### Method: set_metadata_date_str(metadata_date) {#set_metadata_date_str_metadata_date_14}


```
 set_metadata_date_str(metadata_date) 
```

Adds metadata last changed date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| metadata_date | string | Metadata date. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_15}


```
 set_modify_date(modified_date) 
```

Adds resource last modified date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| modified_date | System.DateTime | Last modified date. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_16}


```
 set_modify_date(modified_date) 
```

Adds resource last modified date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| modified_date | string | Last modified date. |

### Method: set_modify_date_str(modified_date) {#set_modify_date_str_modified_date_17}


```
 set_modify_date_str(modified_date) 
```

Adds resource last modified date.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| modified_date | string | Last modified date. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_18}


```
 set_prop_value(key, value) 
```

Sets the first XMP attribute or element value with by specified _key_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |
| value | [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) | The [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) value. |

### Method: set_rating(choise) {#set_rating_choise_19}


```
 set_rating(choise) 
```

Sets rating.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| choise | int | From -1 till 5 |

### Method: set_value(key, value) {#set_value_key_value_20}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | The value to add to. |

### Method: set_value(key, value) {#set_value_key_value_21}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | The value to add to. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_22}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | The value to set to. |

### Method: try_get_value(key, value) {#try_get_value_key_value_23}


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


