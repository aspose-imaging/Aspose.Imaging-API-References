---
title: XmpMediaManagementPackage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpmm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** XmpPackage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Initializes a new instance of the [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/) class. |
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
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_6) | Sets the derived from. |
| [set_document_id(guid)](#set_document_id_guid_7) | Sets the document identifier. |
| [set_document_id(guid)](#set_document_id_guid_8) | Sets the document identifier. |
| [set_document_id_as_guid(guid)](#set_document_id_as_guid_guid_9) | Sets the document identifier. |
| [set_instance_id(guid)](#set_instance_id_guid_10) | Sets instance id. |
| [set_instance_id(guid)](#set_instance_id_guid_11) | Sets instance id. |
| [set_instance_id_as_guid(guid)](#set_instance_id_as_guid_guid_12) | Sets instance id. |
| [set_original_document_id(guid)](#set_original_document_id_guid_13) | Sets the original document id. |
| [set_original_document_id(guid)](#set_original_document_id_guid_14) | Sets the original document id. |
| [set_original_document_id_as_guid(guid)](#set_original_document_id_as_guid_guid_15) | Sets the original document id. |
| [set_prop_value(key, value)](#set_prop_value_key_value_16) | Sets the first XMP attribute or element value with by specified _key_. |
| [set_value(key, value)](#set_value_key_value_17) | Sets the value. |
| [set_value(key, value)](#set_value_key_value_18) | Sets the value. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_19) | Sets the XMP type value. |
| [try_get_value(key, value)](#try_get_value_key_value_20) | Gets the value by the _key_. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Initializes a new instance of the [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/) class.

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_6}


```
 set_derived_from(resource_ref) 
```

Sets the derived from.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| resource_ref | [ResourceRef](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceref/resourceref/) | The resource reference. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

Sets the document identifier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | System.Guid | The unique identifier. |

### Method: set_document_id(guid) {#set_document_id_guid_8}


```
 set_document_id(guid) 
```

Sets the document identifier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | string | The unique identifier. |

### Method: set_document_id_as_guid(guid) {#set_document_id_as_guid_guid_9}


```
 set_document_id_as_guid(guid) 
```

Sets the document identifier.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | System.Guid | The unique identifier. |

### Method: set_instance_id(guid) {#set_instance_id_guid_10}


```
 set_instance_id(guid) 
```

Sets instance id.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | System.Guid | The unique identifier. |

### Method: set_instance_id(guid) {#set_instance_id_guid_11}


```
 set_instance_id(guid) 
```

Sets instance id.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | string | The unique identifier. |

### Method: set_instance_id_as_guid(guid) {#set_instance_id_as_guid_guid_12}


```
 set_instance_id_as_guid(guid) 
```

Sets instance id.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | System.Guid | The unique identifier. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_13}


```
 set_original_document_id(guid) 
```

Sets the original document id.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | System.Guid | The unique identifier. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_14}


```
 set_original_document_id(guid) 
```

Sets the original document id.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | string | The unique identifier. |

### Method: set_original_document_id_as_guid(guid) {#set_original_document_id_as_guid_guid_15}


```
 set_original_document_id_as_guid(guid) 
```

Sets the original document id.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| guid | System.Guid | The unique identifier. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_16}


```
 set_prop_value(key, value) 
```

Sets the first XMP attribute or element value with by specified _key_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The key that identifies value. |
| value | [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) | The [XmpValue](/imaging/python-net/aspose.imaging.xmp.types/xmpvalue/) value. |

### Method: set_value(key, value) {#set_value_key_value_17}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | The value to add to. |

### Method: set_value(key, value) {#set_value_key_value_18}


```
 set_value(key, value) 
```

Sets the value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with added value. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | The value to add to. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_19}


```
 set_xmp_type_value(key, value) 
```

Sets the XMP type value.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| key | string | The string representation of key that is identified with set value. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | The value to set to. |

### Method: try_get_value(key, value) {#try_get_value_key_value_20}


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


