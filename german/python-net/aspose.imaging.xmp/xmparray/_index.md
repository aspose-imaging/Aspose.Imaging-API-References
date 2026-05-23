---
title: "XmpArray Klasse"
type: docs
weight: 310
url: /de/python-net/aspose.imaging.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/imaging/python-net/aspose.imaging.xmp/xmppackage/).

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpArray

**Inheritance:** IXmpType, XmpCollection

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XmpArray(type, items)](#XmpArray_type_items_1) | Initialisiert eine neue Instanz der [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| values | string[] | r | Gibt das Array von Werten innerhalb von [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(item)](#add_item_1) | Fügt ein neues Element hinzu. |
| [add_item(item)](#add_item_item_2) | Fügt ein neues Element hinzu. |
| [get_xml_value()](#get_xml_value__3) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [get_xmp_representation()](#get_xmp_representation__4) | Liest den XMP-Stringwert dieses Objekts. |


### Constructor: XmpArray(type, items) {#XmpArray_type_items_1}


```
 XmpArray(type, items) 
```

Initialisiert eine neue Instanz der [XmpArray](/imaging/python-net/aspose.imaging.xmp/xmparray/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [XmpArrayType](/imaging/python-net/aspose.imaging.xmp/xmparraytype/) | Der Typ des Arrays. |
| Elemente | string[] | Die Elementliste. |

### Method: add(item) {#add_item_1}


```
 add(item) 
```

Fügt ein neues Element hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Element | System.Object | Das Element, das zur Liste der Elemente hinzugefügt werden soll. |

### Method: add_item(item) {#add_item_item_2}


```
 add_item(item) 
```

Fügt ein neues Element hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Element | string | Das Element, das zur Liste der Elemente hinzugefügt werden soll. |

### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den XMP-Wert zurück, konvertiert in die XML-Darstellung. |


### Method: get_xmp_representation() {#get_xmp_representation__4}


```
 get_xmp_representation() 
```

Liest den XMP-Stringwert dieses Objekts.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den im XMP-Format enthaltenen Zeichenkettenwert zurück. |


