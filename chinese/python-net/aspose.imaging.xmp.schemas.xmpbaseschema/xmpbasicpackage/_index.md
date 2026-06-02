---
title: "XmpBasicPackage 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpbaseschema](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.imaging.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | 初始化 [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) 类的新实例。 |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | 初始化 [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | 评级最大值。 |
| RATING_MIN [static] | int | r | 评级最小值。 |
| RATING_REJECTED [static] | int | r | 评级拒绝值。 |
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
| [set_created_date(created_date)](#set_created_date_created_date_7) | 添加资源创建日期。 |
| [set_created_date(created_date)](#set_created_date_created_date_8) | 添加资源创建日期。 |
| [set_created_date_str(created_date)](#set_created_date_str_created_date_9) | 添加资源创建日期。 |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_10) | 设置创建工具。 |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_11) | 设置标识符。 |
| [set_label(label)](#set_label_label_12) | 设置标签。 |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_13) | 添加元数据最后更改日期。 |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_14) | 添加元数据最后更改日期。 |
| [set_metadata_date_str(metadata_date)](#set_metadata_date_str_metadata_date_15) | 添加元数据最后更改日期。 |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_16) | 添加资源最后修改日期。 |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_17) | 添加资源最后修改日期。 |
| [set_modify_date_str(modified_date)](#set_modify_date_str_modified_date_18) | 添加资源最后修改日期。 |
| [set_prop_value(key, value)](#set_prop_value_key_value_19) | 获取或设置具有指定键的对象。 |
| [set_rating(choise)](#set_rating_choise_20) | 设置评级。 |
| [set_value(key, value)](#set_value_key_value_21) | 设置值。 |
| [set_value(key, value)](#set_value_key_value_22) | 设置值。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_23) | 设置 XMP 类型值。 |
| [try_get_value(key, value)](#try_get_value_key_value_24) | 获取通过 _key_ 的值。 |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

初始化 [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) 类的新实例。

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

初始化 [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| prefix | string | 前缀。 |
| namespace_uri | string | 命名空间 URI。 |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_7}


```
 set_created_date(created_date) 
```

添加资源创建日期。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| created_date | System.DateTime | 创建日期。 |

### Method: set_created_date(created_date) {#set_created_date_created_date_8}


```
 set_created_date(created_date) 
```

添加资源创建日期。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| created_date | string | 创建日期。 |

### Method: set_created_date_str(created_date) {#set_created_date_str_created_date_9}


```
 set_created_date_str(created_date) 
```

添加资源创建日期。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| created_date | string | 创建日期。 |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_10}


```
 set_creator_tool(creator_tool) 
```

设置创建工具。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| creator_tool | string | 工具名称。 |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_11}


```
 set_identifier(idenfifier) 
```

设置标识符。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 标识符 | string[] | 该标识符。 |

### Method: set_label(label) {#set_label_label_12}


```
 set_label(label) 
```

设置标签。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 标签 | string | 标签。 |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_13}


```
 set_metadata_date(metadata_date) 
```

添加元数据最后更改日期。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| metadata_date | System.DateTime | 元数据日期。 |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_14}


```
 set_metadata_date(metadata_date) 
```

添加元数据最后更改日期。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| metadata_date | string | 元数据日期。 |

### Method: set_metadata_date_str(metadata_date) {#set_metadata_date_str_metadata_date_15}


```
 set_metadata_date_str(metadata_date) 
```

添加元数据最后更改日期。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| metadata_date | string | 元数据日期。 |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_16}


```
 set_modify_date(modified_date) 
```

添加资源最后修改日期。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| modified_date | System.DateTime | 最后修改日期。 |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_17}


```
 set_modify_date(modified_date) 
```

添加资源最后修改日期。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| modified_date | string | 最后修改日期。 |

### Method: set_modify_date_str(modified_date) {#set_modify_date_str_modified_date_18}


```
 set_modify_date_str(modified_date) 
```

添加资源最后修改日期。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| modified_date | string | 最后修改日期。 |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_19}


```
 set_prop_value(key, value) 
```

获取或设置具有指定键的对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识值的键。 |
| value | System.Object | 具有指定键的对象。 |

### Method: set_rating(choise) {#set_rating_choise_20}


```
 set_rating(choise) 
```

设置评级。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 选择 | int | 从 -1 到 5 |

### Method: set_value(key, value) {#set_value_key_value_21}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | 要添加到的值。 |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | 要添加到的值。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_23}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 已设置值对应键的字符串表示。 |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | 要设置的值。 |

### Method: try_get_value(key, value) {#try_get_value_key_value_24}


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


