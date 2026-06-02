---
title: "EmfSmallTextOut klass"
type: docs
weight: 1380
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---

**Summary:** The EMR_SMALLTEXTOUT record outputs a string.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSmallTextOut

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSmallTextOut(source)](#EmfSmallTextOut_source_1) | Initierar en ny instans av klassen [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett valfritt, 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som<br/>            specificerar den avgränsande rektangeln i enhetsenheter. |
| c_chars | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet 16-bitars tecken i<br/>            strängen. Strängen är INTE null‑terminerad. |
| ex_scale | float | r/w | Hämtar eller anger ett 32-bitars flyttal som specificerar hur mycket texten ska skalas i x‑riktning. |
| ey_scale | float | r/w | Hämtar eller anger ett 32-bitars flyttal som specificerar hur mycket texten ska skalas i y‑riktning. |
| fu_options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar vilka textutmatningsalternativ som ska användas. Dessa<br/>            alternativ anges av ett eller en kombination av värden från ExtTextOutOptions‑uppräkningen<br/>            (avsnitt 2.1.11). |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar grafikläget, från<br/>            GraphicsMode‑uppräkningen (avsnitt 2.1.16). |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| text_string | string | r/w | Hämtar eller anger en variabel‑längdssträng som innehåller textsträngen som ska ritas, antingen i<br/>            8-bitars eller 16-bitars teckenkoder, enligt värdet i fuOptions‑fältet. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
| x | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar x‑koordinaten för var strängen ska placeras. |
| y | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar y‑koordinaten för var strängen ska placeras. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSmallTextOut(source) {#EmfSmallTextOut_source_1}


```
 EmfSmallTextOut(source) 
```

Initierar en ny instans av klassen [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Källan. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Källan. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Posttypen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


