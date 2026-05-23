---
title: "EmfRoundRect klass"
type: docs
weight: 1020
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---

**Summary:** The EMR_ROUNDRECT record specifies a rectangle with rounded corners. The rectangle is outlined <br/>            by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRoundRect

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfRoundRect()](#EmfRoundRect__1) | Initierar en ny instans av klassen [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/). |
| [EmfRoundRect(source)](#EmfRoundRect_source_2) | Initierar en ny instans av klassen [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett 128-bitars WMF RectL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.19, som <br/>            specificerar den inklusiva-inklusiva rektangeln som ska ritas. |
| corner | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Hämtar eller anger ett 64-bitars WMF SizeL-objekt, specificerat i [MS-WMF] avsnitt 2.2.2.22, som <br/>            specificerar bredden och höjden, i logiska koordinater, för ellipsen som används för att rita de avrundade hörnen. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfRoundRect() {#EmfRoundRect__1}


```
 EmfRoundRect() 
```

Initierar en ny instans av klassen [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/).

### Constructor: EmfRoundRect(source) {#EmfRoundRect_source_2}


```
 EmfRoundRect(source) 
```

Initierar en ny instans av klassen [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/).

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


