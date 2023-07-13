---
title: EmfPolygon16 Class
type: docs
weight: 880
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/
---

The EMR_POLYGON16 record specifies a polygon consisting of two or more vertexes connected by <br/>            straight lines. The polygon is outlined by using the current pen and filled by using the current brush <br/>            and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolygon16

**Inheritance:** EmfDrawingRecordType

**Aspose.Imaging Version:** 23.6

The EmfPolygon16 type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfPolygon16(source)](#EmfPolygon16_source_0) | Initializes a new instance of the [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) class. |
| [EmfPolygon16()](#EmfPolygon16__1) | Initializes a new instance of the [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, <br/>            which specifies the bounding rectangle, in device units. |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point) | r/w | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] <br/>            section 2.2.2.16, which specifies the array of points. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfPolygon16(source) {#EmfPolygon16_source_0}


```
 EmfPolygon16(source) 
```

Initializes a new instance of the [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfPolygon16() {#EmfPolygon16__1}


```
 EmfPolygon16() 
```

Initializes a new instance of the [EmfPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon16/) class.

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


