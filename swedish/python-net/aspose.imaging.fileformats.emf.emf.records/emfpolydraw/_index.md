---
title: "EmfPolyDraw klass"
type: docs
weight: 800
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---

**Summary:** The EMR_POLYDRAW record specifies a set of line segments and Bezier curves.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyDraw

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyDraw()](#EmfPolyDraw__1) | Initierar en ny instans av klassen [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/). |
| [EmfPolyDraw(source)](#EmfPolyDraw_source_2) | Initierar en ny instans av klassen [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Hämtar eller anger en matris av WMF PointL‑objekt ([MS-WMF] avsnitt 2.2.2.15) som specificerar punktdata i logiska enheter. |
| ab_types | [EmfPointEnum[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpointenum/) | r/w | Hämtar eller anger en array av bytevärden med längden Count som specificerar hur varje punkt i <br/>            aPoints-arrayen används. Detta värde MÅSTE vara i Point (avsnitt 2.1.26) uppräkning. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar den omgivande rektangeln, i enhetsenheter. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyDraw() {#EmfPolyDraw__1}


```
 EmfPolyDraw() 
```

Initierar en ny instans av klassen [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/).

### Constructor: EmfPolyDraw(source) {#EmfPolyDraw_source_2}


```
 EmfPolyDraw(source) 
```

Initierar en ny instans av klassen [EmfPolyDraw](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/).

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


