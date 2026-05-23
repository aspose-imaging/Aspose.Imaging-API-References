---
title: "XmpDate Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.imaging.xmp.types.basic](/imaging/python-net/aspose.imaging.xmp.types.basic/)

**Full Name:** aspose.imaging.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | Initialisiert eine neue Instanz der [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) Klasse. |
| [XmpDate(date_time)](#XmpDate_date_time_2) | Initialisiert eine neue Instanz der [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [static] | string | r | Der ISO 8601 (Roundtrip)-Formatstring. |
| Format | string | r | Ruft den Formatstring für den aktuellen Wert ab. |
| Wert | System.DateTime | r/w | Ruft den Datumswert ab oder legt ihn fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klont diese Instanz. |
| [get_xmp_representation()](#get_xmp_representation__2) | Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück. |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

Initialisiert eine neue Instanz der [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| date_string | string | Die Zeichenkettenrepräsentation des Datums. |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

Initialisiert eine neue Instanz der [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| date_time | System.DateTime | Ein Datum-Uhrzeit-Wert, der mit einem Teil der ISO RFC 8601-Formatierung dargestellt wird. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klont diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Object | Ein Memberwise-Klon. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Gibt den enthaltenen Zeichenkettenwert im XMP-Format zurück.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt eine Zeichenkette zurück, die die xmp-Darstellung enthält. |


