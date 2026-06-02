---
title: "XmpArray-klass"
type: docs
weight: 310
url: /sv/python-net/aspose.imaging.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/).

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpArray

**Inheritance:** IXmpType, XmpCollection

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpArray(type, items)](#XmpArray_type_items_1) | Initierar en ny instans av klassen [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| values | string[] | r | Hämtar en matris med värden i [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(item)](#add_item_1) | Lägger till nytt objekt. |
| [add_item(item)](#add_item_item_2) | Lägger till nytt objekt. |
| [get_xml_value()](#get_xml_value__3) | Konverterar XMP‑värde till XML‑representationen. |
| [get_xmp_representation()](#get_xmp_representation__4) | Hämtar XMP-strängvärdet för detta. |


### Constructor: XmpArray(type, items) {#XmpArray_type_items_1}


```
 XmpArray(type, items) 
```

Initierar en ny instans av klassen [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [XmpArrayType](/imaging/python-net/aspose.imaging.xmp/xmparraytype/) | Typen av matris. |
| objekt | string[] | Listan med objekt. |

### Method: add(item) {#add_item_1}


```
 add(item) 
```

Lägger till nytt objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| objekt | System.Object | Objektet som ska läggas till i listan med objekt. |

### Method: add_item(item) {#add_item_item_2}


```
 add_item(item) 
```

Lägger till nytt objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| objekt | string | Objektet som ska läggas till i listan med objekt. |

### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Konverterar XMP‑värde till XML‑representationen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar XMP‑värdet konverterat till XML‑representationen. |


### Method: get_xmp_representation() {#get_xmp_representation__4}


```
 get_xmp_representation() 
```

Hämtar XMP-strängvärdet för detta.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar det strängvärde som finns i XMP-format. |


