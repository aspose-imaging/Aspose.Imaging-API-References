---
title: "EmfDeleteObject Klass"
type: docs
weight: 340
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/
---

**Summary:** The EMR_DELETEOBJECT record deletes a graphics object, which is specified by its index in the EMF Object Table(section 3.1.1.1).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfDeleteObject

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfDeleteObject()](#EmfDeleteObject__1) | Initierar en ny instans av klassen [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/). |
| [EmfDeleteObject(record)](#EmfDeleteObject_record_2) | Initierar en ny instans av klassen [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| object_handle | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antingen indexet för ett grafikobjekt <br/>            i EMF-objektabellen eller indexet för ett standardobjekt från StockObject‑enumerationen. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfDeleteObject() {#EmfDeleteObject__1}


```
 EmfDeleteObject() 
```

Initierar en ny instans av klassen [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/).

### Constructor: EmfDeleteObject(record) {#EmfDeleteObject_record_2}


```
 EmfDeleteObject(record) 
```

Initierar en ny instans av klassen [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Posten. |

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


