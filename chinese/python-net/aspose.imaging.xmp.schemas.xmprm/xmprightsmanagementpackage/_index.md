---
title: "XmpRightsManagementPackage 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.imaging.xmp.schemas.xmprm](/imaging/python-net/aspose.imaging.xmp.schemas.xmprm/)

**Full Name:** aspose.imaging.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | 初始化 [XmpRightsManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/) 类的新实例。 |
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
| [set_certificate(certificate)](#set_certificate_certificate_7) | 设置证书。 |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_8) | 标记为受版权管理的内容 |
| [set_owners(owners)](#set_owners_owners_9) | 设置所有者。 |
| [set_prop_value(key, value)](#set_prop_value_key_value_10) | 获取或设置具有指定键的对象。 |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_11) | 设置使用条款。 |
| [set_value(key, value)](#set_value_key_value_12) | 设置值。 |
| [set_value(key, value)](#set_value_key_value_13) | 设置值。 |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_14) | 设置网页声明。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_15) | 设置 XMP 类型值。 |
| [try_get_value(key, value)](#try_get_value_key_value_16) | 获取通过 _key_ 的值。 |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

初始化 [XmpRightsManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmprm/xmprightsmanagementpackage/) 类的新实例。

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


### Method: set_certificate(certificate) {#set_certificate_certificate_7}


```
 set_certificate(certificate) 
```

设置证书。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 证书 | string | 该证书。 |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_8}


```
 set_marked_as_right_management(value) 
```

标记为受版权管理的内容

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| value | bool | 如果设置为 <c>true</c>，则此为受版权管理的资源。 |

### Method: set_owners(owners) {#set_owners_owners_9}


```
 set_owners(owners) 
```

设置所有者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 所有者 | string[] | 所有者。 |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_10}


```
 set_prop_value(key, value) 
```

获取或设置具有指定键的对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识值的键。 |
| value | System.Object | 具有指定键的对象。 |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_11}


```
 set_usage_terms(usage_terms) 
```

设置使用条款。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| usage_terms | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | 使用条款。 |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | 要添加到的值。 |

### Method: set_value(key, value) {#set_value_key_value_13}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | 要添加到的值。 |

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_14}


```
 set_web_statement(web_statement_url) 
```

设置网页声明。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| web_statement_url | string | 网页声明 URL。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_15}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 已设置值对应键的字符串表示。 |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | 要设置的值。 |

### Method: try_get_value(key, value) {#try_get_value_key_value_16}


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


