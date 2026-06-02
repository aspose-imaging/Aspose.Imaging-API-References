---
title: "XmpMediaManagementPackage Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.imaging.xmp.schemas.xmpmm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Initialisiert eine neue Instanz der Klasse [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/). |
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
| [add_value(key, value)](#add_value_key_value_1) | Fügt eine Zeichenketten‑Eigenschaft hinzu. |
| [add_value(key, value)](#add_value_key_value_2) | Fügt eine Zeichenketten‑Eigenschaft hinzu. |
| clear() | Löscht diese Instanz. |
| [contains_key(key)](#contains_key_key_3) | Bestimmt, ob diese Sammlung den angegebenen Schlüssel enthält. |
| [get_prop_value(key)](#get_prop_value_key_4) | Gibt das Objekt mit dem angegebenen Schlüssel zurück. |
| [get_xml_value()](#get_xml_value__5) | Konvertiert den XMP-Wert in die XML-Darstellung. |
| [remove(key)](#remove_key_6) | Entfernt den Wert mit dem angegebenen Schlüssel. |
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_7) | Setzt das „derived from“. |
| [set_document_id(guid)](#set_document_id_guid_8) | Setzt die Dokumentenkennung. |
| [set_document_id(guid)](#set_document_id_guid_9) | Setzt die Dokumentenkennung. |
| [set_document_id_as_guid(guid)](#set_document_id_as_guid_guid_10) | Setzt die Dokumentenkennung. |
| [set_instance_id(guid)](#set_instance_id_guid_11) | Setzt die Instanz-ID. |
| [set_instance_id(guid)](#set_instance_id_guid_12) | Setzt die Instanz-ID. |
| [set_instance_id_as_guid(guid)](#set_instance_id_as_guid_guid_13) | Setzt die Instanz-ID. |
| [set_original_document_id(guid)](#set_original_document_id_guid_14) | Setzt die ursprüngliche Dokumenten-ID. |
| [set_original_document_id(guid)](#set_original_document_id_guid_15) | Setzt die ursprüngliche Dokumenten-ID. |
| [set_original_document_id_as_guid(guid)](#set_original_document_id_as_guid_guid_16) | Setzt die ursprüngliche Dokumenten-ID. |
| [set_prop_value(key, value)](#set_prop_value_key_value_17) | Liest oder setzt das Objekt mit dem angegebenen Schlüssel. |
| [set_value(key, value)](#set_value_key_value_18) | Setzt den Wert. |
| [set_value(key, value)](#set_value_key_value_19) | Setzt den Wert. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_20) | Setzt den XMP‑Typwert. |
| [try_get_value(key, value)](#try_get_value_key_value_21) | Gibt den Wert anhand des _key_ zurück. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Initialisiert eine neue Instanz der Klasse [XmpMediaManagementPackage](/imaging/python-net/aspose.imaging.xmp.schemas.xmpmm/xmpmediamanagementpackage/).

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_7}


```
 set_derived_from(resource_ref) 
```

Setzt das „derived from“.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| resource_ref | [ResourceRef](/imaging/python-net/aspose.imaging.xmp.types.complex.resourceref/resourceref/) | Die Ressourcenreferenz. |

### Method: set_document_id(guid) {#set_document_id_guid_8}


```
 set_document_id(guid) 
```

Setzt die Dokumentenkennung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | System.Guid | Der eindeutige Bezeichner. |

### Method: set_document_id(guid) {#set_document_id_guid_9}


```
 set_document_id(guid) 
```

Setzt die Dokumentenkennung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | string | Der eindeutige Bezeichner. |

### Method: set_document_id_as_guid(guid) {#set_document_id_as_guid_guid_10}


```
 set_document_id_as_guid(guid) 
```

Setzt die Dokumentenkennung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | System.Guid | Der eindeutige Bezeichner. |

### Method: set_instance_id(guid) {#set_instance_id_guid_11}


```
 set_instance_id(guid) 
```

Setzt die Instanz-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | System.Guid | Der eindeutige Bezeichner. |

### Method: set_instance_id(guid) {#set_instance_id_guid_12}


```
 set_instance_id(guid) 
```

Setzt die Instanz-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | string | Der eindeutige Bezeichner. |

### Method: set_instance_id_as_guid(guid) {#set_instance_id_as_guid_guid_13}


```
 set_instance_id_as_guid(guid) 
```

Setzt die Instanz-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | System.Guid | Der eindeutige Bezeichner. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_14}


```
 set_original_document_id(guid) 
```

Setzt die ursprüngliche Dokumenten-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | System.Guid | Der eindeutige Bezeichner. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_15}


```
 set_original_document_id(guid) 
```

Setzt die ursprüngliche Dokumenten-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | string | Der eindeutige Bezeichner. |

### Method: set_original_document_id_as_guid(guid) {#set_original_document_id_as_guid_guid_16}


```
 set_original_document_id_as_guid(guid) 
```

Setzt die ursprüngliche Dokumenten-ID.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| guid | System.Guid | Der eindeutige Bezeichner. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_17}


```
 set_prop_value(key, value) 
```

Liest oder setzt das Objekt mit dem angegebenen Schlüssel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Der Schlüssel, der den Wert identifiziert. |
| Wert | System.Object | Das Objekt mit dem angegebenen Schlüssel. |

### Method: set_value(key, value) {#set_value_key_value_18}


```
 set_value(key, value) 
```

Setzt den Wert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Der Wert, zu dem hinzugefügt wird. |

### Method: set_value(key, value) {#set_value_key_value_19}


```
 set_value(key, value) 
```

Setzt den Wert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Der Wert, zu dem hinzugefügt wird. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_20}


```
 set_xmp_type_value(key, value) 
```

Setzt den XMP‑Typwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Der Wert, auf den gesetzt werden soll. |

### Method: try_get_value(key, value) {#try_get_value_key_value_21}


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


