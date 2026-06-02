---
title: "XmpMeta Klasse"
type: docs
weight: 440
url: /de/python-net/aspose.imaging.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | Initialisiert eine neue Instanz der [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) Klasse. |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | Initialisiert eine neue Instanz der [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Liest oder setzt die Adobe Xmp Toolkit-Version. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Fügt das Attribut hinzu. |
| clear_attributes() | Entfernt alle Attribute. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Liest das Attribut. |
| [get_xml_value()](#get_xml_value__3) | Konvertiert den XMP-Wert in die XML-Darstellung. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

Initialisiert eine neue Instanz der [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) Klasse.

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

Initialisiert eine neue Instanz der [XmpMeta](/imaging/python-net/aspose.imaging.xmp/xmpmeta/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| toolkit_version | string | Adobe XMP Toolkit-Version. |

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Fügt das Attribut hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Attribut | string | Das Attribut. |
| Wert | string | Der Wert. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Liest das Attribut.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Attribut | string | Das Attribut. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt das Attribut für den angegebenen Attributnamen zurück. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den XMP-Wert zurück, konvertiert in die XML-Darstellung. |


