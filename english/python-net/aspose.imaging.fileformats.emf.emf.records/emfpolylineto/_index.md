---
title: EmfPolylineTo Class
type: docs
weight: 910
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/
---

**Summary:** The EMR_POLYLINETO record specifies one or more straight lines based upon the current position.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolylineTo

**Inheritance:** EmfDrawingRecordType

**Aspose.Imaging Version:** 23.10.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolylineTo()](#EmfPolylineTo__1) | Initializes a new instance of the [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) class. |
| [EmfPolylineTo(source)](#EmfPolylineTo_source_2) | Initializes a new instance of the [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point) | r/w | Gets or sets a Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) <br/>            that specifies the point data, in logical units. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies <br/>            the bounding rectangle, in device units. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfPolylineTo() {#EmfPolylineTo__1}


```
 EmfPolylineTo() 
```

Initializes a new instance of the [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) class.

### Constructor: EmfPolylineTo(source) {#EmfPolylineTo_source_2}


```
 EmfPolylineTo(source) 
```

Initializes a new instance of the [EmfPolylineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto/) class.

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


