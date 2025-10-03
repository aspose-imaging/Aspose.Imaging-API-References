---
title: XmpArray Class
type: docs
weight: 310
url: /python-net/aspose.imaging.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/).

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpArray

**Inheritance:** IXmpType, XmpCollection

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpArray(type, items)](#XmpArray_type_items_1) | Initializes a new instance of the [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| values | string[] | r | Gets array of values inside [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(item)](#add_item_1) | Adds new item. |
| [add_item(item)](#add_item_item_2) | Adds new item. |
| [get_xml_value()](#get_xml_value__3) | Converts XMP value to the XML representation. |
| [get_xmp_representation()](#get_xmp_representation__4) | Gets the XMP string value of this. |


### Constructor: XmpArray(type, items) {#XmpArray_type_items_1}


```
 XmpArray(type, items) 
```

Initializes a new instance of the [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [XmpArrayType](/imaging/python-net/aspose.imaging.xmp/xmparraytype/) | The type of array. |
| items | string[] | The items list. |

### Method: add(item) {#add_item_1}


```
 add(item) 
```

Adds new item.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| item | System.Object | The item to be added to list of items. |

### Method: add_item(item) {#add_item_item_2}


```
 add_item(item) 
```

Adds new item.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| item | string | The item to be added to list of items. |

### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Converts XMP value to the XML representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the XMP value converted to the XML representation. |


### Method: get_xmp_representation() {#get_xmp_representation__4}


```
 get_xmp_representation() 
```

Gets the XMP string value of this.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the string contained value in XMP format. |


