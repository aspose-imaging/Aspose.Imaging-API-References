---
title: EmfPolygon Class
type: docs
weight: 870
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/
---

The EMR_POLYGON record specifies a polygon consisting of two or more vertexes connected by <br/>            straight lines.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolygon

**Inheritance:** EmfDrawingRecordType

**Aspose.Imaging Version:** 23.6

The EmfPolygon type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPolygon(source)](#EmfPolygon_source_0) | Initializes a new instance of the [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) class. |
| [EmfPolygon()](#EmfPolygon__1) | Initializes a new instance of the [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies <br/>            the bounding rectangle in device units. |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point) | r/w | Gets or sets a Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) <br/>            that specifies the vertexes of the polygon in logical units. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfPolygon(source) {#EmfPolygon_source_0}


```
 EmfPolygon(source) 
```

Initializes a new instance of the [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolygon() {#EmfPolygon__1}


```
 EmfPolygon() 
```

Initializes a new instance of the [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) class.

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


