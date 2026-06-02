---
title: "EmfDrawEscape klass"
type: docs
weight: 350
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---

**Summary:** The EMR_DRAWESCAPE record passes arbitrary information to a printer driver. The intent is that the<br/>            information will result in drawing being done.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfDrawEscape

**Inheritance:** EmfEscapeRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfDrawEscape(source)](#EmfDrawEscape_source_1) | Initierar en ny instans av klassen [EmfDrawEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cj_in | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar antalet byte som ska skickas till skrivardrivrutinen. |
| data | System.Byte | r/w | Hämtar eller anger data som ska skickas till skrivardrivrutinen. Det MÅSTE finnas cjIn byte tillgängliga. |
| escape | [WmfMetafileEscapes](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/) | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar skrivardrivrutinens escape‑funktion att<br/>            utföra. Detta MÅSTE vara ett av värdena i WMF MetafileEscapes enumeration ([MSWMF] avsnitt 2.1.1.17). |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfDrawEscape(source) {#EmfDrawEscape_source_1}


```
 EmfDrawEscape(source) 
```

Initierar en ny instans av klassen [EmfDrawEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/).

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


