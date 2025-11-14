---
title: EmfPolyPolyline16 Class
type: docs
weight: 860
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/
---

**Summary:** The EMR_POLYPOLYLINE16 record specifies multiple series of connected line segments.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolyline16

**Inheritance:** EmfPolyPolyShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolyPolyline16()](#EmfPolyPolyline16__1) | Initializes a new instance of the [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/) class. |
| [EmfPolyPolyline16(source)](#EmfPolyPolyline16_source_2) | Initializes a new instance of the [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Gets or sets an array of WMF PointS objects, specified in [MS-WMF] <br/>            section 2.2.2.16, which specifies the array of points. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets an 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfPolyPolyline16() {#EmfPolyPolyline16__1}


```
 EmfPolyPolyline16() 
```

Initializes a new instance of the [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/) class.

### Constructor: EmfPolyPolyline16(source) {#EmfPolyPolyline16_source_2}


```
 EmfPolyPolyline16(source) 
```

Initializes a new instance of the [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | The source. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | The source. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


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
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


