---
title: EmfPolyPolygon16 Class
type: docs
weight: 820
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/
---

**Summary:** The EMR_POLYPOLYGON16 record specifies a series of closed polygons. Each polygon is outlined <br/>            using the current pen, and filled using the current brush and polygon fill mode. The polygons drawn <br/>            by this record can overlap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolygon16

**Inheritance:** EmfDrawingRecordType

**Aspose.Imaging Version:** 23.6

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyPolygon16()](#EmfPolyPolygon16__1) | Initializes a new instance of the [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) class. |
| [EmfPolyPolygon16(source)](#EmfPolyPolygon16_source_2) | Initializes a new instance of the [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- |
| a_points | Point[] | r/w | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] <br/>            section 2.2.2.16, which specifies the array of points. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, <br/>            which specifies the bounding rectangle, in device units. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfPolyPolygon16() {#EmfPolyPolygon16__1}


```
 EmfPolyPolygon16() 
```

Initializes a new instance of the [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) class.

### Constructor: EmfPolyPolygon16(source) {#EmfPolyPolygon16_source_2}


```
 EmfPolyPolygon16(source) 
```

Initializes a new instance of the [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) class.

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


