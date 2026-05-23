---
title: "Timecode-Klasse"
type: docs
weight: 60
url: /de/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/
---

**Summary:** Represents timecode value in video.

**Module:** [aspose.imaging.xmp.schemas.xmpdm](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/)

**Full Name:** aspose.imaging.xmp.schemas.xmpdm.Timecode

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Timecode(format, time_value)](#Timecode_format_time_value_1) | Initialisiert eine neue Instanz der [Timecode](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| format | [TimeFormat](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timeformat/) | r/w | Liest oder setzt das Format, das in [Timecode.time_value](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/) verwendet wird. |
| time_value | string | r/w | Liest oder setzt den Zeitwert im angegebenen Format. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klont diese Instanz. |
| [get_xmp_representation()](#get_xmp_representation__2) | Gibt den im XMP-Format enthaltenen Zeichenkettenwert zurück. |


### Constructor: Timecode(format, time_value) {#Timecode_format_time_value_1}


```
 Timecode(format, time_value) 
```

Initialisiert eine neue Instanz der [Timecode](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timecode/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| format | [TimeFormat](/imaging/python-net/aspose.imaging.xmp.schemas.xmpdm/timeformat/) | Das Zeitformat. |
| time_value | string | Der Zeitwert. |

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

Gibt den im XMP-Format enthaltenen Zeichenkettenwert zurück.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt die Zeichenkette zurück, die die xmp-Darstellung enthält. |


