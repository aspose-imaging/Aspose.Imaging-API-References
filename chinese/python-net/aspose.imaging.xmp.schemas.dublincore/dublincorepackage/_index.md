---
title: "DublinCorePackage 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.xmp.schemas.dublincore/dublincorepackage/
---

**Summary:** Represents Dublic Core schema.

**Module:** [aspose.imaging.xmp.schemas.dublincore](/imaging/python-net/aspose.imaging.xmp.schemas.dublincore/)

**Full Name:** aspose.imaging.xmp.schemas.dublincore.DublinCorePackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [DublinCorePackage()](#DublinCorePackage__1) | 初始化 [DublinCorePackage](/imaging/python-net/aspose.imaging.xmp.schemas.dublincore/dublincorepackage/) 类的新实例。 |
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
| [set_author(author)](#set_author_author_7) | 添加作者。 |
| [set_author(author)](#set_author_author_8) | 添加作者。 |
| [set_author_array(author)](#set_author_array_author_9) | 添加作者。 |
| [set_description(desc)](#set_description_desc_10) | 添加描述。 |
| [set_description(desc)](#set_description_desc_11) | 添加描述。 |
| [set_description_lang_alt(desc)](#set_description_lang_alt_desc_12) | 添加描述。 |
| [set_description_str(desc)](#set_description_str_desc_13) | 添加描述。 |
| [set_prop_value(key, value)](#set_prop_value_key_value_14) | 获取或设置具有指定键的对象。 |
| [set_publisher(publisher)](#set_publisher_publisher_15) | 添加出版者。 |
| [set_publisher(publisher)](#set_publisher_publisher_16) | 添加出版者。 |
| [set_publisher_array(publisher)](#set_publisher_array_publisher_17) | 添加出版者。 |
| [set_subject(subject)](#set_subject_subject_18) | 添加主题。 |
| [set_subject(subject)](#set_subject_subject_19) | 添加主题。 |
| [set_subject_array(subject)](#set_subject_array_subject_20) | 添加主题。 |
| [set_title(title)](#set_title_title_21) | 添加 Dublin Core 标题。 |
| [set_title(title)](#set_title_title_22) | 添加 Dublin Core 标题。 |
| [set_title_lang_alt(title)](#set_title_lang_alt_title_23) | 为不同语言添加 Dublin Core 标题。 |
| [set_title_str(title)](#set_title_str_title_24) | 添加 Dublin Core 标题。 |
| [set_value(key, value)](#set_value_key_value_25) | 设置值。 |
| [set_value(key, value)](#set_value_key_value_26) | 设置值。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_27) | 设置 XMP 类型值。 |
| [try_get_value(key, value)](#try_get_value_key_value_28) | 获取通过 _key_ 的值。 |


### Constructor: DublinCorePackage() {#DublinCorePackage__1}


```
 DublinCorePackage() 
```

初始化 [DublinCorePackage](/imaging/python-net/aspose.imaging.xmp.schemas.dublincore/dublincorepackage/) 类的新实例。

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


### Method: set_author(author) {#set_author_author_7}


```
 set_author(author) 
```

添加作者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 作者 | string | 作者。 |

### Method: set_author(author) {#set_author_author_8}


```
 set_author(author) 
```

添加作者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 作者 | string[] | 作者。 |

### Method: set_author_array(author) {#set_author_array_author_9}


```
 set_author_array(author) 
```

添加作者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 作者 | string[] | 作者。 |

### Method: set_description(desc) {#set_description_desc_10}


```
 set_description(desc) 
```

添加描述。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 描述 | string | 描述。 |

### Method: set_description(desc) {#set_description_desc_11}


```
 set_description(desc) 
```

添加描述。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| desc | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | 描述。 |

### Method: set_description_lang_alt(desc) {#set_description_lang_alt_desc_12}


```
 set_description_lang_alt(desc) 
```

添加描述。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| desc | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | 描述。 |

### Method: set_description_str(desc) {#set_description_str_desc_13}


```
 set_description_str(desc) 
```

添加描述。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 描述 | string | 描述。 |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_14}


```
 set_prop_value(key, value) 
```

获取或设置具有指定键的对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识值的键。 |
| value | System.Object | 具有指定键的对象。 |

### Method: set_publisher(publisher) {#set_publisher_publisher_15}


```
 set_publisher(publisher) 
```

添加出版者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 出版商 | string | 出版商。 |

### Method: set_publisher(publisher) {#set_publisher_publisher_16}


```
 set_publisher(publisher) 
```

添加出版者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 出版商 | string[] | 出版商。 |

### Method: set_publisher_array(publisher) {#set_publisher_array_publisher_17}


```
 set_publisher_array(publisher) 
```

添加出版者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 出版商 | string[] | 出版商。 |

### Method: set_subject(subject) {#set_subject_subject_18}


```
 set_subject(subject) 
```

添加主题。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 主题 | string | 主题。 |

### Method: set_subject(subject) {#set_subject_subject_19}


```
 set_subject(subject) 
```

添加主题。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 主题 | string[] | 主题。 |

### Method: set_subject_array(subject) {#set_subject_array_subject_20}


```
 set_subject_array(subject) 
```

添加主题。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 主题 | string[] | 主题。 |

### Method: set_title(title) {#set_title_title_21}


```
 set_title(title) 
```

添加 Dublin Core 标题。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 标题 | string | 标题。 |

### Method: set_title(title) {#set_title_title_22}


```
 set_title(title) 
```

添加 Dublin Core 标题。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| title | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | 标题。 |

### Method: set_title_lang_alt(title) {#set_title_lang_alt_title_23}


```
 set_title_lang_alt(title) 
```

为不同语言添加 Dublin Core 标题。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| title | [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/) | 实例为 [LangAlt](/imaging/python-net/aspose.imaging.xmp/langalt/)。 |

### Method: set_title_str(title) {#set_title_str_title_24}


```
 set_title_str(title) 
```

添加 Dublin Core 标题。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 标题 | string | 标题。 |

### Method: set_value(key, value) {#set_value_key_value_25}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | 要添加到的值。 |

### Method: set_value(key, value) {#set_value_key_value_26}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | 要添加到的值。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_27}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 已设置值对应键的字符串表示。 |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | 要设置的值。 |

### Method: try_get_value(key, value) {#try_get_value_key_value_28}


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


