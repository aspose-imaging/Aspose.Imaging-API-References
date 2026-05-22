---
title: "PdfPackage 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.imaging.xmp.schemas.pdf](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/)

**Full Name:** aspose.imaging.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | 初始化一个新的 [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/) 类实例。 |
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
| [set_keywords(keywords)](#set_keywords_keywords_7) | 设置关键字。 |
| [set_pdf_version(version)](#set_pdf_version_version_8) | 设置 PDF 版本。 |
| [set_producer(producer)](#set_producer_producer_9) | 设置创建 PDF 的工具名称。 |
| [set_prop_value(key, value)](#set_prop_value_key_value_10) | 获取或设置具有指定键的对象。 |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_11) | 设置 trapped。 |
| [set_value(key, value)](#set_value_key_value_12) | 设置值。 |
| [set_value(key, value)](#set_value_key_value_13) | 设置值。 |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_14) | 设置 XMP 类型值。 |
| [try_get_value(key, value)](#try_get_value_key_value_15) | 获取通过 _key_ 的值。 |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

初始化一个新的 [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/) 类实例。

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


### Method: set_keywords(keywords) {#set_keywords_keywords_7}


```
 set_keywords(keywords) 
```

设置关键字。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 关键字 | string | 关键字。 |

### Method: set_pdf_version(version) {#set_pdf_version_version_8}


```
 set_pdf_version(version) 
```

设置 PDF 版本。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 版本 | string | Pdf 版本，例如：1.0、1.3 等。 |

### Method: set_producer(producer) {#set_producer_producer_9}


```
 set_producer(producer) 
```

设置创建 PDF 的工具名称。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 生产者 | string | 生产者名称。 |

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

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_11}


```
 set_trapped(is_trapped) 
```

设置 trapped。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| is_trapped | bool | 如果设置为 <c>true</c>，文档已被捕获。 |

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

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_14}


```
 set_xmp_type_value(key, value) 
```

设置 XMP 类型值。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| key | string | 已设置值对应键的字符串表示。 |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | 要设置的值。 |

### Method: try_get_value(key, value) {#try_get_value_key_value_15}


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


