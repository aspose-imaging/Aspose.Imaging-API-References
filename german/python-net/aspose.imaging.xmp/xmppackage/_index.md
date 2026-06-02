---
title: "XmpPackage Klasse"
type: docs
weight: 460
url: /de/python-net/aspose.imaging.xmp/xmppackage/
---

**Summary:** Represents base abstraction for XMP package.

**Module:** [aspose.imaging.xmp](/imaging/python-net/aspose.imaging.xmp/)

**Full Name:** aspose.imaging.xmp.XmpPackage

**Inheritance:** IXmlValue

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| count | int | r | Liest die XMP‑Schlüsselanzahl. |
| namespace_uri | string | r | Gibt den Namespace-URI zurück. |
| prefix | string | r | Gibt das Präfix zurück. |
| xml_namespace | string | r | Gibt den XML-Namespace zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Fügt den Wert dem angegebenen Schlüssel hinzu. |
| [add_value(key, value)](#add_value_key_value_2) | Fügt den Wert dem angegebenen Schlüssel hinzu. |
| clear() | Löscht diese Instanz. |
| [contains_key(key)](#contains_key_key_3) | Bestimmt, ob diese Sammlung den angegebenen Schlüssel enthält. |
| [get_prop_value(key)](#get_prop_value_key_4) | Gibt das Objekt mit dem angegebenen Schlüssel zurück. |
| [get_xml_value()](#get_xml_value__5) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [remove(key)](#remove_key_6) | Entfernt den Wert mit dem angegebenen Schlüssel. |
| [set_prop_value(key, value)](#set_prop_value_key_value_7) | Liest oder setzt das Objekt mit dem angegebenen Schlüssel. |
| [set_value(key, value)](#set_value_key_value_8) | Setzt den Wert. |
| [set_value(key, value)](#set_value_key_value_9) | Setzt den Wert. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Setzt den XMP‑Typwert. |
| [try_get_value(key, value)](#try_get_value_key_value_11) | Gibt den Wert anhand des _key_ zurück. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Fügt den Wert dem angegebenen Schlüssel hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | string | Der Wert, zu dem hinzugefügt wird. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Fügt den Wert dem angegebenen Schlüssel hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | System.Object | Der Wert, zu dem hinzugefügt wird. |

### Method: contains_key(key) {#contains_key_key_3}


```
 contains_key(key) 
```

Bestimmt, ob diese Sammlung den angegebenen Schlüssel enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Der zu prüfende Schlüssel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | **True** wenn das  den angegebenen Schlüssel enthält; andernfalls, **False**. |


### Method: get_prop_value(key) {#get_prop_value_key_4}


```
 get_prop_value(key) 
```

Gibt das Objekt mit dem angegebenen Schlüssel zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Der Schlüssel, der den Wert identifiziert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Object | Gibt das Objekt mit dem angegebenen Schlüssel zurück. |


### Method: get_xml_value() {#get_xml_value__5}


```
 get_xml_value() 
```

Konvertiert den XMP-Wert in die XML-Darstellung.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den XMP-Wert zurück, konvertiert in die XML-Darstellung. |


### Method: remove(key) {#remove_key_6}


```
 remove(key) 
```

Entfernt den Wert mit dem angegebenen Schlüssel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem entfernten Wert identifiziert wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Gibt true zurück, wenn der Wert mit dem angegebenen Schlüssel entfernt wurde. |


### Method: set_prop_value(key, value) {#set_prop_value_key_value_7}


```
 set_prop_value(key, value) 
```

Liest oder setzt das Objekt mit dem angegebenen Schlüssel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Der Schlüssel, der den Wert identifiziert. |
| Wert | System.Object | Das Objekt mit dem angegebenen Schlüssel. |

### Method: set_value(key, value) {#set_value_key_value_8}


```
 set_value(key, value) 
```

Setzt den Wert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Der Wert, zu dem hinzugefügt wird. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Setzt den Wert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Der Wert, zu dem hinzugefügt wird. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Setzt den XMP‑Typwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Der Wert, auf den gesetzt werden soll. |

### Method: try_get_value(key, value) {#try_get_value_key_value_11}


```
 try_get_value(key, value) 
```

Gibt den Wert anhand des _key_ zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Der XMP-Elementschlüssel. |
| Wert | System.Object | Der XMP-Wert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | **True**, wenn das  den _key_ enthält; andernfalls **False**. |


