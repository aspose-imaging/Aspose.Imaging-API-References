---
title: "EmfArc-klass"
type: docs
weight: 40
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/
---

**Summary:** The EMR_ARC record specifies an elliptical arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfArc()](#EmfArc__1) | Initierar en ny instans av klassen [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/). |
| [EmfArc(source)](#EmfArc_source_2) | Initierar en ny instans av klassen [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som <br/>            specificerar den inklusiva‑inklusiva omgivande rektangeln. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Hämtar eller anger ett 64-bitars WMF PointL-objekt som specificerar koordinaterna, i logiska enheter, för <br/>            slutpunkten på den radiella linjen som definierar arcens slutpunkt. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som <br/>            specificerar koordinaterna, i logiska enheter, för slutpunkten på den radiella linjen som definierar <br/>            startpunkten för bågen. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfArc() {#EmfArc__1}


```
 EmfArc() 
```

Initierar en ny instans av klassen [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/).

### Constructor: EmfArc(source) {#EmfArc_source_2}


```
 EmfArc(source) 
```

Initierar en ny instans av klassen [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/).

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


