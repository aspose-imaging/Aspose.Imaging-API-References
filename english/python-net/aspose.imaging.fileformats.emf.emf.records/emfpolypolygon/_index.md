---
title: EmfPolyPolygon Class
type: docs
weight: 830
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/
---

**Summary:** The EMR_POLYPOLYGON record specifies a series of closed polygons.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolygon

**Inheritance:** EmfPolyPolyShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyPolygon()](#EmfPolyPolygon__1) | Initializes a new instance of the [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) class. |
| [EmfPolyPolygon(source)](#EmfPolyPolygon_source_2) | Initializes a new instance of the [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_points | Point[] | r/w | Gets or sets an array of WMF PointS objects, specified in [MS-WMF] <br/>            section 2.2.2.16, which specifies the array of points. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets an 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfPolyPolygon() {#EmfPolyPolygon__1}


```
 EmfPolyPolygon() 
```

Initializes a new instance of the [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) class.

### Constructor: EmfPolyPolygon(source) {#EmfPolyPolygon_source_2}


```
 EmfPolyPolygon(source) 
```

Initializes a new instance of the [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | The record type. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) |  |


