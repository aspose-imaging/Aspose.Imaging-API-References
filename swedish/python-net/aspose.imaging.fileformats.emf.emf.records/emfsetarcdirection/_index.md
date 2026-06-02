---
title: "EmfSetArcDirection klass"
type: docs
weight: 1090
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---

**Summary:** The EMR_SETARCDIRECTION record specifies the drawing direction to be used for arc and rectangle output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetArcDirection

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetArcDirection()](#EmfSetArcDirection__1) | Initierar en ny instans av klassen [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/). |
| [EmfSetArcDirection(source)](#EmfSetArcDirection_source_2) | Initierar en ny instans av klassen [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| arc_direction | [EmfArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfarcdirection/) | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar bågarnas riktning. Värdet<br/>            MÅSTE vara i ArcDirection‑enumerationen (avsnitt 2.1.2).<br/>            Standardriktningen är moturs. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetArcDirection() {#EmfSetArcDirection__1}


```
 EmfSetArcDirection() 
```

Initierar en ny instans av klassen [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/).

### Constructor: EmfSetArcDirection(source) {#EmfSetArcDirection_source_2}


```
 EmfSetArcDirection(source) 
```

Initierar en ny instans av klassen [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/).

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


