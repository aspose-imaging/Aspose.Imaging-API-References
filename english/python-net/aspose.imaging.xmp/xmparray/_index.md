---
title: XmpArray Class
type: docs
weight: 310
url: /python-net/aspose.imaging.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/). TODO: Array may contain complex data.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpArray

**Inheritance:** IXmlValue

**Aspose.Imaging Version:** 24.6.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpArray(type)](#XmpArray_type_1) | Initializes a new instance of the [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) class. |
| [XmpArray(type, items)](#XmpArray_type_items_2) | Initializes a new instance of the [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| values | string | r | Gets array of values inside [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_item(item)](#add_item_item_1) | Adds new item. |
| [get_xml_value()](#get_xml_value__2) | Converts XMP value to the XML representation. |


### Constructor: XmpArray(type) {#XmpArray_type_1}


```
 XmpArray(type) 
```

Initializes a new instance of the [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [XmpArrayType](/imaging/python-net/aspose.imaging.xmp/xmparraytype) | The type of array. |

### Constructor: XmpArray(type, items) {#XmpArray_type_items_2}


```
 XmpArray(type, items) 
```

Initializes a new instance of the [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [XmpArrayType](/imaging/python-net/aspose.imaging.xmp/xmparraytype) | The type of array. |
| items | string | The items list. |

### Method: add_item(item) {#add_item_item_1}


```
 add_item(item) 
```

Adds new item.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| item | string | The item to be added to list of items. |

### Method: get_xml_value() {#get_xml_value__2}


```
 get_xml_value() 
```

Converts XMP value to the XML representation.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the XMP value converted to the XML representation. |


