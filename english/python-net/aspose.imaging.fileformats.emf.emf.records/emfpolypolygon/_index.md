---
title: EmfPolyPolygon Class
type: docs
weight: 810
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/
---

The EMR_POLYPOLYGON record specifies a series of closed polygons.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolygon

**Inheritance:** EmfDrawingRecordType

**Aspose.Imaging Version:** 23.6

The EmfPolyPolygon type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPolyPolygon(source)](#EmfPolyPolygon_source_0) | Initializes a new instance of the [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) class. |
| [EmfPolyPolygon()](#EmfPolyPolygon__1) | Initializes a new instance of the [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the <br/>            bounding rectangle, in device units. |
| a_points | Point[] | r/w | Gets or sets an array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that <br/>            specifies the points for all polygons in logical units. The number of points is specified by the <br/>            Count field value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfPolyPolygon(source) {#EmfPolyPolygon_source_0}


```
 EmfPolyPolygon(source) 
```

Initializes a new instance of the [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolyPolygon() {#EmfPolyPolygon__1}


```
 EmfPolyPolygon() 
```

Initializes a new instance of the [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) class.

### create_from_record(source)  [static] {#create_from_record_source_2}


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


### create_from_type(type)  [static] {#create_from_type_type_3}


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


