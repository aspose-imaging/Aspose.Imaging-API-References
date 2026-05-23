---
title: "PdfPackage Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.imaging.xmp.schemas.pdf](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/)

**Full Name:** aspose.imaging.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Initialisiert eine neue Instanz der [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/) Klasse. |
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
| [set_keywords(keywords)](#set_keywords_keywords_7) | Setzt die Schlüsselwörter. |
| [set_pdf_version(version)](#set_pdf_version_version_8) | Setzt die PDF-Version. |
| [set_producer(producer)](#set_producer_producer_9) | Setzt den Namen des Werkzeugs, das das PDF erstellt hat. |
| [set_prop_value(key, value)](#set_prop_value_key_value_10) | Liest oder setzt das Objekt mit dem angegebenen Schlüssel. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_11) | Setzt das Trapped. |
| [set_value(key, value)](#set_value_key_value_12) | Setzt den Wert. |
| [set_value(key, value)](#set_value_key_value_13) | Setzt den Wert. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_14) | Setzt den XMP‑Typwert. |
| [try_get_value(key, value)](#try_get_value_key_value_15) | Gibt den Wert anhand des _key_ zurück. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Initialisiert eine neue Instanz der [PdfPackage](/imaging/python-net/aspose.imaging.xmp.schemas.pdf/pdfpackage/) Klasse.

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


### Method: set_keywords(keywords) {#set_keywords_keywords_7}


```
 set_keywords(keywords) 
```

Setzt die Schlüsselwörter.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schlüsselwörter | string | Die Schlüsselwörter. |

### Method: set_pdf_version(version) {#set_pdf_version_version_8}


```
 set_pdf_version(version) 
```

Setzt die PDF-Version.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| version | string | Pdf-Version, zum Beispiel: 1.0, 1.3 usw. |

### Method: set_producer(producer) {#set_producer_producer_9}


```
 set_producer(producer) 
```

Setzt den Namen des Werkzeugs, das das PDF erstellt hat.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Ersteller | string | Der Name des Erstellers. |

### Method: set_prop_value(key, value) {#set_prop_value_key_value_10}


```
 set_prop_value(key, value) 
```

Liest oder setzt das Objekt mit dem angegebenen Schlüssel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Der Schlüssel, der den Wert identifiziert. |
| Wert | System.Object | Das Objekt mit dem angegebenen Schlüssel. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_11}


```
 set_trapped(is_trapped) 
```

Setzt das Trapped.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| is_trapped | bool | Wenn auf <c>true</c> gesetzt, ist das Dokument getrappt. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Setzt den Wert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmlValue](/imaging/python-net/aspose.imaging.xmp/ixmlvalue/) | Der Wert, zu dem hinzugefügt wird. |

### Method: set_value(key, value) {#set_value_key_value_13}


```
 set_value(key, value) 
```

Setzt den Wert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, die mit dem hinzugefügten Wert identifiziert wird. |
| value | [IXmpType](/imaging/python-net/aspose.imaging.xmp.types/ixmptype/) | Der Wert, zu dem hinzugefügt wird. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_14}


```
 set_xmp_type_value(key, value) 
```

Setzt den XMP‑Typwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| key | string | Die Zeichenkettenrepräsentation des Schlüssels, der mit dem gesetzten Wert identifiziert wird. |
| value | [XmpTypeBase](/imaging/python-net/aspose.imaging.xmp.types/xmptypebase/) | Der Wert, auf den gesetzt werden soll. |

### Method: try_get_value(key, value) {#try_get_value_key_value_15}


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


