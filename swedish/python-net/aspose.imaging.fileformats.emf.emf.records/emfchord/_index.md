---
title: "EmfChord-klass"
type: docs
weight: 110
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/
---

**Summary:** The EMR_CHORD record specifies a chord, which is a region bounded by the intersection of an <br/>            ellipse and a line segment, called a secant. The chord is outlined by using the current pen and filled <br/>            by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfChord

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfChord()](#EmfChord__1) | Initierar en ny instans av klassen [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/). |
| [EmfChord(source)](#EmfChord_source_2) | Initierar en ny instans av klassen [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som <br/>            specificerar den inklusiva‑inklusiva omgivande rektangeln. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Hämtar eller anger ett 64-bitars WMF PointL-objekt som specificerar de logiska koordinaterna för <br/>            slutpunkten av radien som definierar chordens slut. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som <br/>            specificerar de logiska koordinaterna för slutpunkten av radien som definierar chordens början. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfChord() {#EmfChord__1}


```
 EmfChord() 
```

Initierar en ny instans av klassen [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/).

### Constructor: EmfChord(source) {#EmfChord_source_2}


```
 EmfChord(source) 
```

Initierar en ny instans av klassen [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/).

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


