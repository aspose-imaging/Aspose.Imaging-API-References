---
title: "XmpDate klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.imaging.xmp.types.basic](/imaging/python-net/aspose.imaging.xmp.types.basic/)

**Full Name:** aspose.imaging.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | Initierar en ny instans av klassen [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/). |
| [XmpDate(date_time)](#XmpDate_date_time_2) | Initierar en ny instans av klassen [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [statisk] | string | r | Den ISO 8601 (rundresa) formatsträngen. |
| format | string | r | Hämtar formatsträngen för det aktuella värdet. |
| värde | System.DateTime | r/w | Hämtar eller anger datumvärdet. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Klonar den här instansen. |
| [get_xmp_representation()](#get_xmp_representation__2) | Returnerar strängens innehållsvärde i XMP-format. |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

Initierar en ny instans av klassen [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| date_string | string | Strängrepresentationen av datumet. |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

Initierar en ny instans av klassen [XmpDate](/imaging/python-net/aspose.imaging.xmp.types.basic/xmpdate/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| date_time | System.DateTime | Ett datum‑tid‑värde som representeras med ett delmängd av ISO RFC 8601‑formatering. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar den här instansen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Object | En medlemsklon. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Returnerar strängens innehållsvärde i XMP-format.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar en sträng som innehåller xmp‑representationen |


