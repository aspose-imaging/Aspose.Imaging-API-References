---
title: "PhotoshopPackage 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.xmp.schemas.photoshop/photoshoppackage/
---

**Summary:** Represents Adobe Photoshop namespace.

**Module:** [aspose.imaging.xmp.schemas.photoshop](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/)

**Full Name:** aspose.imaging.xmp.schemas.photoshop.PhotoshopPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [PhotoshopPackage()](#PhotoshopPackage__1) | 初始化一个新的 [PhotoshopPackage](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/photoshoppackage/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| URGENCY_MAX [静态] | int | r | 紧急程度最大值。 |
| URGENCY_MIN [静态] | int | r | 紧急程度最小值。 |
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
| [set_authors_position(authors_position)](#set_authors_position_authors_position_7) | 设置作者的位置。 |
| [set_caption_writer(caption_writer)](#set_caption_writer_caption_writer_8) | 设置标题编写者。 |
| [set_category(category)](#set_category_category_9) | 设置类别。 |
| [set_city(city)](#set_city_city_10) | 设置城市。 |
| [set_color_mode(color_mode)](#set_color_mode_color_mode_11) | 设置颜色模式。 |
| [set_country(country)](#set_country_country_12) | 设置国家。 |
| [set_created_date(created_date)](#set_created_date_created_date_13) | 设置创建日期。 |
| [set_credit(credit)](#set_credit_credit_14) | 设置署名。 |
| [set_document_ancestors(ancestors)](#set_document_ancestors_ancestors_15) | 设置文档祖先。 |
| [set_headline(headline)](#set_headline_headline_16) | 设置标题。 |
| [set_history(history)](#set_history_history_17) | 设置历史记录。 |
| [set_icc_profile(icc_profile)](#set_icc_profile_icc_profile_18) | 设置 icc 配置文件。 |
| [set_instructions(instructions)](#set_instructions_instructions_19) | 设置说明。 |
| [set_prop_value(key, value)](#set_prop_value_key_value_20) | 获取或设置具有指定键的对象。 |
| [set_source(source)](#set_source_source_21) | 设置来源。 |
| [set_state(state)](#set_state_state_22) | 设置州。 |
| [set_supplemental_categories(supplemental_categories)](#set_supplemental_categories_supplemental_categories_23) | 设置补充类别。 |
| [set_transmission_reference(transmission_reference)](#set_transmission_reference_transmission_reference_24) | 设置传输参考。 |
| [set_urgency(urgency)](#set_urgency_urgency_25) | 设置紧急程度。 |
| [set_value(key, value)](#set_value_key_value_26) | 设置值。 |
| [set_value(key, value)](#set_value_key_value_27) | 设置值。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_28) | 设置 XMP 类型值。 |
| [try_get_value(key, value)](#try_get_value_key_value_29) | 获取通过 _key_ 的值。 |


### Constructor: PhotoshopPackage() {#PhotoshopPackage__1}


```
 PhotoshopPackage() 
```

初始化一个新的 [PhotoshopPackage](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/photoshoppackage/) 类实例。

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


### Method: set_authors_position(authors_position) {#set_authors_position_authors_position_7}


```
 set_authors_position(authors_position) 
```

设置作者的位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| authors_position | string | 作者的位置。 |

### Method: set_caption_writer(caption_writer) {#set_caption_writer_caption_writer_8}


```
 set_caption_writer(caption_writer) 
```

设置标题编写者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| caption_writer | string | 字幕编写器。 |

### Method: set_category(category) {#set_category_category_9}


```
 set_category(category) 
```

设置类别。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| category | string | 类别。 |

### Method: set_city(city) {#set_city_city_10}


```
 set_city(city) 
```

设置城市。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| city | string | 城市名称。 |

### Method: set_color_mode(color_mode) {#set_color_mode_color_mode_11}


```
 set_color_mode(color_mode) 
```

设置颜色模式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| color_mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.schemas.photoshop/colormode/) | 颜色模式。 |

### Method: set_country(country) {#set_country_country_12}


```
 set_country(country) 
```

设置国家。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| country | string | 国家。 |

### Method: set_created_date(created_date) {#set_created_date_created_date_13}


```
 set_created_date(created_date) 
```

设置创建日期。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| created_date | System.DateTime | 创建日期。 |

### Method: set_credit(credit) {#set_credit_credit_14}


```
 set_credit(credit) 
```

设置署名。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| credit | string | 信用。 |

### Method: set_document_ancestors(ancestors) {#set_document_ancestors_ancestors_15}


```
 set_document_ancestors(ancestors) 
```

设置文档祖先。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| ancestors | string[] | 祖先。 |

### Method: set_headline(headline) {#set_headline_headline_16}


```
 set_headline(headline) 
```

设置标题。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| headline | string | 标题。 |

### Method: set_history(history) {#set_history_history_17}


```
 set_history(history) 
```

设置历史记录。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| history | string | 历史。 |

### Method: set_icc_profile(icc_profile) {#set_icc_profile_icc_profile_18}


```
 set_icc_profile(icc_profile) 
```

设置 icc 配置文件。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| icc_profile | string | icc 配置文件。 |

### Method: set_instructions(instructions) {#set_instructions_instructions_19}


```
 set_instructions(instructions) 
```

设置说明。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| instructions | string | 说明。 |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_20}


```
 set_prop_value(key, value) 
```

获取或设置具有指定键的对象。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识值的键。 |
| value | System.Object | 具有指定键的对象。 |

### Method: set_source(source) {#set_source_source_21}


```
 set_source(source) 
```

设置来源。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 源 | string | 来源。 |

### Method: set_state(state) {#set_state_state_22}


```
 set_state(state) 
```

设置州。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 状态 | string | 状态。 |

### Method: set_supplemental_categories(supplemental_categories) {#set_supplemental_categories_supplemental_categories_23}


```
 set_supplemental_categories(supplemental_categories) 
```

设置补充类别。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| supplemental_categories | string[] | 补充类别。 |

### Method: set_transmission_reference(transmission_reference) {#set_transmission_reference_transmission_reference_24}


```
 set_transmission_reference(transmission_reference) 
```

设置传输参考。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| transmission_reference | string | 传输参考。 |

### Method: set_urgency(urgency) {#set_urgency_urgency_25}


```
 set_urgency(urgency) 
```

设置紧急程度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 紧急程度 | int | 紧急程度。 |

### Method: set_value(key, value) {#set_value_key_value_26}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | 要添加到的值。 |

### Method: set_value(key, value) {#set_value_key_value_27}


```
 set_value(key, value) 
```

设置值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 标识已添加值的键的字符串表示形式。 |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | 要添加到的值。 |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_28}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 已设置值对应键的字符串表示。 |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | 要设置的值。 |

### Method: try_get_value(key, value) {#try_get_value_key_value_29}


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


