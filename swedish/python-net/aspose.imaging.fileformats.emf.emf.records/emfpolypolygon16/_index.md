---
title: "EmfPolyPolygon16 klass"
type: docs
weight: 840
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/
---

**Summary:** The EMR_POLYPOLYGON16 record specifies a series of closed polygons. Each polygon is outlined <br/>            using the current pen, and filled using the current brush and polygon fill mode. The polygons drawn <br/>            by this record can overlap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolygon16

**Inheritance:** EmfPolyPolyShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyPolygon16()](#EmfPolyPolygon16__1) | Initierar en ny instans av klassen [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) klass. |
| [EmfPolyPolygon16(source)](#EmfPolyPolygon16_source_2) | Initierar en ny instans av klassen [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Hämtar eller anger en matris av WMF PointS-objekt, specificerad i [MS-WMF] <br/>            avsnitt 2.2.2.16, som specificerar matrisen av punkter. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett 128-bitars WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar den omgivande rektangeln, i enhetsenheter. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyPolygon16() {#EmfPolyPolygon16__1}


```
 EmfPolyPolygon16() 
```

Initierar en ny instans av klassen [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) klass.

### Constructor: EmfPolyPolygon16(source) {#EmfPolyPolygon16_source_2}


```
 EmfPolyPolygon16(source) 
```

Initierar en ny instans av klassen [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) klass.

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


