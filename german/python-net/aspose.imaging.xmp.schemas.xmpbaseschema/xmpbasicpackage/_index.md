---
title: "XmpBasicPackage Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpbaseschema](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.imaging.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Initialisiert eine neue Instanz der [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) Klasse. |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Initialisiert eine neue Instanz der [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| RATING_MAX [statisch] | int | r | Rating maximaler Wert. |
| RATING_MIN [statisch] | int | r | Rating minimaler Wert. |
| RATING_REJECTED [statisch] | int | r | Rating abgelehnter Wert. |
| count | int | r | Liest die XMP‑Schlüsselanzahl. |
| namespace_uri | string | r | Gibt den Namespace-URI zurück. |
| prefix | string | r | Gibt das Präfix zurück. |
| xml_namespace | string | r | Gibt den XML-Namespace zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Fügt eine Zeichenketten‑Eigenschaft hinzu. |
| [add_value(key, value)](#add_value_key_value_2) | Fügt eine Zeichenketten‑Eigenschaft hinzu. |
| clear() | Löscht diese Instanz. |
| [contains_key(key)](#contains_key_key_3) | Bestimmt, ob diese Sammlung den angegebenen Schlüssel enthält. |
| [get_prop_value(key)](#get_prop_value_key_4) | Gibt das Objekt mit dem angegebenen Schlüssel zurück. |
| [get_xml_value()](#get_xml_value__5) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [remove(key)](#remove_key_6) | Entfernt den Wert mit dem angegebenen Schlüssel. |
| [set_created_date(created_date)](#set_created_date_created_date_7) | Fügt das Erstellungsdatum der Ressource hinzu. |
| [set_created_date(created_date)](#set_created_date_created_date_8) | Fügt das Erstellungsdatum der Ressource hinzu. |
| [set_created_date_str(created_date)](#set_created_date_str_created_date_9) | Fügt das Erstellungsdatum der Ressource hinzu. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_10) | Setzt das Erstellungswerkzeug. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_11) | Setzt den Bezeichner. |
| [set_label(label)](#set_label_label_12) | Setzt das Etikett. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_13) | Fügt das Datum der letzten Änderung der Metadaten hinzu. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_14) | Fügt das Datum der letzten Änderung der Metadaten hinzu. |
| [set_metadata_date_str(metadata_date)](#set_metadata_date_str_metadata_date_15) | Fügt das Datum der letzten Änderung der Metadaten hinzu. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_16) | Fügt das Datum der letzten Änderung der Ressource hinzu. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_17) | Fügt das Datum der letzten Änderung der Ressource hinzu. |
| [set_modify_date_str(modified_date)](#set_modify_date_str_modified_date_18) | Fügt das Datum der letzten Änderung der Ressource hinzu. |
| [set_prop_value(key, value)](#set_prop_value_key_value_19) | Liest oder setzt das Objekt mit dem angegebenen Schlüssel. |
| [set_rating(choise)](#set_rating_choise_20) | Setzt die Bewertung. |
| [set_value(key, value)](#set_value_key_value_21) | Setzt den Wert. |
| [set_value(key, value)](#set_value_key_value_22) | Setzt den Wert. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_23) | Setzt den XMP‑Typwert. |
| [try_get_value(key, value)](#try_get_value_key_value_24) | Gibt den Wert anhand des _key_ zurück. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Initialisiert eine neue Instanz der [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) Klasse.

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Initialisiert eine neue Instanz der [XmpBasicPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| prefix | string | Das Präfix. |
| namespace_uri | string | Der Namespace-URI. |

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Fügt eine Zeichenketten‑Eigenschaft hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | string | Der Zeichenkettenwert. |

### Method: add_value(key, value) {#add_value_key_value_2}


```
 add_value(key, value) 
```

Fügt eine Zeichenketten‑Eigenschaft hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| Wert | System.Object | Der Zeichenkettenwert. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_7}


```
 set_created_date(created_date) 
```

Fügt das Erstellungsdatum der Ressource hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| created_date | System.DateTime | Erstellungsdatum. |

### Method: set_created_date(created_date) {#set_created_date_created_date_8}


```
 set_created_date(created_date) 
```

Fügt das Erstellungsdatum der Ressource hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| created_date | string | Erstellungsdatum. |

### Method: set_created_date_str(created_date) {#set_created_date_str_created_date_9}


```
 set_created_date_str(created_date) 
```

Fügt das Erstellungsdatum der Ressource hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| created_date | string | Erstellungsdatum. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_10}


```
 set_creator_tool(creator_tool) 
```

Setzt das Erstellungswerkzeug.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| creator_tool | string | Name des Werkzeugs. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_11}


```
 set_identifier(idenfifier) 
```

Setzt den Bezeichner.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| idenfifier | string[] | Der idenfifier. |

### Method: set_label(label) {#set_label_label_12}


```
 set_label(label) 
```

Setzt das Etikett.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Bezeichnung | string | Das Etikett. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_13}


```
 set_metadata_date(metadata_date) 
```

Fügt das Datum der letzten Änderung der Metadaten hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| metadata_date | System.DateTime | Metadaten-Datum. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_14}


```
 set_metadata_date(metadata_date) 
```

Fügt das Datum der letzten Änderung der Metadaten hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| metadata_date | string | Metadaten-Datum. |

### Method: set_metadata_date_str(metadata_date) {#set_metadata_date_str_metadata_date_15}


```
 set_metadata_date_str(metadata_date) 
```

Fügt das Datum der letzten Änderung der Metadaten hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| metadata_date | string | Metadaten-Datum. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_16}


```
 set_modify_date(modified_date) 
```

Fügt das Datum der letzten Änderung der Ressource hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| modified_date | System.DateTime | Datum der letzten Änderung. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_17}


```
 set_modify_date(modified_date) 
```

Fügt das Datum der letzten Änderung der Ressource hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| modified_date | string | Datum der letzten Änderung. |

### Method: set_modify_date_str(modified_date) {#set_modify_date_str_modified_date_18}


```
 set_modify_date_str(modified_date) 
```

Fügt das Datum der letzten Änderung der Ressource hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| modified_date | string | Datum der letzten Änderung. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_19}


```
 set_prop_value(key, value) 
```

Liest oder setzt das Objekt mit dem angegebenen Schlüssel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Der Schlüssel, der den Wert identifiziert. |
| Wert | System.Object | Das Objekt mit dem angegebenen Schlüssel. |

### Method: set_rating(choise) {#set_rating_choise_20}


```
 set_rating(choise) 
```

Setzt die Bewertung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Auswahl | int | Von -1 bis 5 |

### Method: set_value(key, value) {#set_value_key_value_21}


```
 set_value(key, value) 
```

Setzt den Wert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Der Wert, zu dem hinzugefügt wird. |

### Method: set_value(key, value) {#set_value_key_value_22}


```
 set_value(key, value) 
```

Setzt den Wert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Der Wert, zu dem hinzugefügt wird. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_23}


```
 set_xmp_type_value(key, value) 
```

Setzt den XMP‑Typwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Der Wert, auf den gesetzt werden soll. |

### Method: try_get_value(key, value) {#try_get_value_key_value_24}


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


