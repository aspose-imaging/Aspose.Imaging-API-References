---
title: "EmfPolyBezier16 klass"
type: docs
weight: 770
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/
---

**Summary:** The EMR_POLYBEZIER16 record specifies one or more Bezier curves. The curves are drawn using<br/>            the current pen.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyBezier16

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyBezier16()](#EmfPolyBezier16__1) | Initierar en ny instans av klassen [EmfPolyBezier16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/) klass. |
| [EmfPolyBezier16(source)](#EmfPolyBezier16_source_2) | Initierar en ny instans av klassen [EmfPolyBezier16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Hämtar eller anger en matris av WMF PointL‑objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar punktdata i logiska enheter. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar den omgivande rektangeln, i enhetsenheter. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyBezier16() {#EmfPolyBezier16__1}


```
 EmfPolyBezier16() 
```

Initierar en ny instans av klassen [EmfPolyBezier16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/) klass.

### Constructor: EmfPolyBezier16(source) {#EmfPolyBezier16_source_2}


```
 EmfPolyBezier16(source) 
```

Initierar en ny instans av klassen [EmfPolyBezier16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/) klass.

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


