---
title: "XmpArray 类"
type: docs
weight: 310
url: /zh/python-net/aspose.imaging.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/).

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpArray

**Inheritance:** IXmpType, XmpCollection

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [XmpArray(type, items)](#XmpArray_type_items_1) | 初始化 [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| values | string[] | r | 获取 [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) 中的值数组。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add(item)](#add_item_1) | 添加新项。 |
| [add_item(item)](#add_item_item_2) | 添加新项。 |
| [get_xml_value()](#get_xml_value__3) | 将 XMP 值转换为 XML 表示。 |
| [get_xmp_representation()](#get_xmp_representation__4) | 获取此项的 XMP 字符串值。 |


### Constructor: XmpArray(type, items) {#XmpArray_type_items_1}


```
 XmpArray(type, items) 
```

初始化 [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [XmpArrayType](/imaging/python-net/aspose.imaging.xmp/xmparraytype/) | 数组的类型。 |
| 项 | string[] | 项列表。 |

### Method: add(item) {#add_item_1}


```
 add(item) 
```

添加新项。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 项 | System.Object | 要添加到项目列表中的项目。 |

### Method: add_item(item) {#add_item_item_2}


```
 add_item(item) 
```

添加新项。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 项 | string | 要添加到项目列表中的项目。 |

### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

将 XMP 值转换为 XML 表示。

**Returns**

| Type | Description |
| :- | :- |
| string | 返回转换为 XML 表示形式的 XMP 值。 |


### Method: get_xmp_representation() {#get_xmp_representation__4}


```
 get_xmp_representation() 
```

获取此项的 XMP 字符串值。

**Returns**

| Type | Description |
| :- | :- |
| string | 返回 XMP 格式中包含的字符串值。 |


