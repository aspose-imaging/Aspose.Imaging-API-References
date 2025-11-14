---
title: EmfPolylineTo16 Class
type: docs
weight: 950
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/
---

**Summary:** The EMR_POLYLINETO16 record specifies one or more straight lines based upon the current position. <br/>            A line is drawn from the current position to the first point specified by the aPoints field by using the <br/>            current pen. For each additional line, drawing is performed from the ending point of the previous <br/>            line to the next point specified by aPoints.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolylineTo16

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPolylineTo16()](#EmfPolylineTo16__1) | Initializes a new instance of the [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/) class. |
| [EmfPolylineTo16(source)](#EmfPolylineTo16_source_2) | Initializes a new instance of the [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Gets or sets an array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the point data, in logical units. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets an 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfPolylineTo16() {#EmfPolylineTo16__1}


```
 EmfPolylineTo16() 
```

Initializes a new instance of the [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/) class.

### Constructor: EmfPolylineTo16(source) {#EmfPolylineTo16_source_2}


```
 EmfPolylineTo16(source) 
```

Initializes a new instance of the [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/) class.

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


