---
title: "EmfGlsBoundedRecord klass"
type: docs
weight: 540
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---

**Summary:** The EMR_GLSBOUNDEDRECORD record specifies an OpenGL function with a bounding rectangle for output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGlsBoundedRecord

**Inheritance:** EmfOpenGlRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfGlsBoundedRecord(source)](#EmfGlsBoundedRecord_source_1) | Initierar en ny instans av klassen [EmfGlsBoundedRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar en avgränsande<br/>            rektangel, i enhetsenheter, för utdata som produceras genom att köra OpenGL‑funktionen. |
| cb_data | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, för Data‑fältet.<br/>            Om detta värde är noll, bifogas ingen data till denna post. |
| data | System.Byte | r/w | Hämtar eller anger en valfri bytearray med längden cbData som specificerar data för OpenGL‑funktionen. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfGlsBoundedRecord(source) {#EmfGlsBoundedRecord_source_1}


```
 EmfGlsBoundedRecord(source) 
```

Initierar en ny instans av klassen [EmfGlsBoundedRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/).

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


