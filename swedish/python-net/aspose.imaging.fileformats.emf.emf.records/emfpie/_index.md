---
title: "EmfPie klass"
type: docs
weight: 730
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/
---

**Summary:** The EMR_PIE record specifies a pie-shaped wedge bounded by the intersection of an ellipse and two <br/>            radials. The pie is outlined by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPie

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPie()](#EmfPie__1) | Initialiserar en ny instans av klassen [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) klass. |
| [EmfPie(source)](#EmfPie_source_2) | Initialiserar en ny instans av klassen [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som <br/>            specificerar den inklusiva‑inklusiva omgivande rektangeln. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Hämtar eller anger ett 64-bitars PointL-objekt som specificerar koordinaterna, i logiska enheter, för <br/>            slutpunkten av den andra radien. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Hämtar eller anger ett 64-bitars WMF PointL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.15, som <br/>            specificerar koordinaterna, i logiska enheter, för slutpunkten av den första radien. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPie() {#EmfPie__1}


```
 EmfPie() 
```

Initialiserar en ny instans av klassen [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) klass.

### Constructor: EmfPie(source) {#EmfPie_source_2}


```
 EmfPie(source) 
```

Initialiserar en ny instans av klassen [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/) klass.

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


