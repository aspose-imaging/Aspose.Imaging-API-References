---
title: "EmfCreatePen-klass"
type: docs
weight: 320
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---

**Summary:** The EMR_CREATEPEN record defines a logical pen for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreatePen

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCreatePen()](#EmfCreatePen__1) | Initierar en ny instans av klassen [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/). |
| [EmfCreatePen(source)](#EmfCreatePen_source_2) | Initierar en ny instans av klassen [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ih_pen | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för det logiska pennobjektet i<br/>            EMF Object Table (avsnitt 3.1.1.1). Detta index MÅSTE sparas så att detta objekt kan<br/>            återanvändas eller modifieras. |
| log_pen | [EmfLogPen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpen/) | r/w | Hämtar eller anger ett LogPen-objekt (avsnitt 2.2.19) som specificerar stil, bredd och färg<br/>            på den logiska pennan. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreatePen() {#EmfCreatePen__1}


```
 EmfCreatePen() 
```

Initierar en ny instans av klassen [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/).

### Constructor: EmfCreatePen(source) {#EmfCreatePen_source_2}


```
 EmfCreatePen(source) 
```

Initierar en ny instans av klassen [EmfCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepen/).

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


