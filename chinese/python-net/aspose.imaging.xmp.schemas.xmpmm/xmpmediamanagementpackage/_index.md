---
title: "XmpMediaManagementPackage 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpmm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | 初始化一个新的 [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| count | int | r | 获取 XMP 键的计数。 |
| namespace_uri | string | r | 获取命名空间 URI。 |
| prefix | string | r | 获取前缀。 |
| xml_namespace | string | r | 获取 XML 命名空间。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | 添加字符串属性。 |
| [add_value(key, value)](#add_value_key_value_2) | 添加字符串属性。 |
| clear() | 清除此实例。 |
| [contains_key(key)](#contains_key_key_3) | 确定此集合是否指定了键。 |
| [get_prop_value(key)](#get_prop_value_key_4) | 获取具有指定键的对象。 |
| [get_xml_value()](#get_xml_value__5) | 将 XMP 值转换为 XML 表示。 |
| [remove(key)](#remove_key_6) | 移除具有指定键的值。 |
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_7) | 设置派生自。 |
| [set_document_id(guid)](#set_document_id_guid_8) | 设置文档标识符。 |
| [set_document_id(guid)](#set_document_id_guid_9) | 设置文档标识符。 |
| [set_document_id_as_guid(guid)](#set_document_id_as_guid_guid_10) | 设置文档标识符。 |
| [set_instance_id(guid)](#set_instance_id_guid_11) | 设置实例 ID。 |
| [set_instance_id(guid)](#set_instance_id_guid_12) | 设置实例 ID。 |
| [set_instance_id_as_guid(guid)](#set_instance_id_as_guid_guid_13) | 设置实例 ID。 |
| [set_original_document_id(guid)](#set_original_document_id_guid_14) | 设置原始文档 ID。 |
| [set_original_document_id(guid)](#set_original_document_id_guid_15) | 设置原始文档 ID。 |
| [set_original_document_id_as_guid(guid)](#set_original_document_id_as_guid_guid_16) | 设置原始文档 ID。 |
| [set_prop_value(key, value)](#set_prop_value_key_value_17) | 获取或设置具有指定键的对象。 |
| [set_value(key, value)](#set_value_key_value_18) | 设置值。 |
| [set_value(key, value)](#set_value_key_value_19) | 设置值。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_20) | 设置 XMP 类型值。 |
| [try_get_value(key, value)](#try_get_value_key_value_21) | 获取通过 _key_ 的值。 |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

初始化一个新的 [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/) 类实例。

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

添加字符串属性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | string | 字符串值。 |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

添加字符串属性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | System.Object | 字符串值。 |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

确定此集合是否指定了键。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 要检查的键。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True** 如果包含指定键；否则，**False**。 |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

获取具有指定键的对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识值的键。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Object | 返回具有指定键的对象。 |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

将 XMP 值转换为 XML 表示。

**Returns**

| Type | Description |
| :- | :- |
| string | 返回转换为 XML 表示形式的 XMP 值。 |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

移除具有指定键的值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 已删除值对应键的字符串表示。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果已删除具有指定键的值，则返回 true。 |


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_7}


```
 set_derived_from(resource_ref) 
```

设置派生自。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| resource_ref | [ResourceRef](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceref/resourceref/) | 资源引用。 |

### Method: set_document_id(guid) {#set_document_id_guid_8}


```
 set_document_id(guid) 
```

设置文档标识符。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| guid | System.Guid | 唯一标识符。 |

### Method: set_document_id(guid) {#set_document_id_guid_9}


```
 set_document_id(guid) 
```

设置文档标识符。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| guid | string | 唯一标识符。 |

### Method: set_document_id_as_guid(guid) {#set_document_id_as_guid_guid_10}


```
 set_document_id_as_guid(guid) 
```

设置文档标识符。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| guid | System.Guid | 唯一标识符。 |

### Method: set_instance_id(guid) {#set_instance_id_guid_11}


```
 set_instance_id(guid) 
```

设置实例 ID。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| guid | System.Guid | 唯一标识符。 |

### Method: set_instance_id(guid) {#set_instance_id_guid_12}


```
 set_instance_id(guid) 
```

设置实例 ID。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| guid | string | 唯一标识符。 |

### Method: set_instance_id_as_guid(guid) {#set_instance_id_as_guid_guid_13}


```
 set_instance_id_as_guid(guid) 
```

设置实例 ID。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| guid | System.Guid | 唯一标识符。 |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_14}


```
 set_original_document_id(guid) 
```

设置原始文档 ID。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| guid | System.Guid | 唯一标识符。 |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_15}


```
 set_original_document_id(guid) 
```

设置原始文档 ID。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| guid | string | 唯一标识符。 |

### Method: set_original_document_id_as_guid(guid) {#set_original_document_id_as_guid_guid_16}


```
 set_original_document_id_as_guid(guid) 
```

设置原始文档 ID。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| guid | System.Guid | 唯一标识符。 |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_17}


```
 set_prop_value(key, value) 
```

获取或设置具有指定键的对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识值的键。 |
| value | System.Object | 具有指定键的对象。 |

### Method: set_value(key, value) {#set_value_key_value_18}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | 要添加到的值。 |

### Method: set_value(key, value) {#set_value_key_value_19}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | 要添加到的值。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_20}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 已设置值对应键的字符串表示。 |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | 要设置的值。 |

### Method: try_get_value(key, value) {#try_get_value_key_value_21}


```
 try_get_value(key, value) 
```

获取通过 _key_ 的值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | XMP 元素键。 |
| value | System.Object | XMP 值。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True**，如果该  包含 _key_；否则为 **False**。 |


