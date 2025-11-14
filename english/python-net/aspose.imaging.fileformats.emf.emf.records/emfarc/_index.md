---
title: EmfArc Class
type: docs
weight: 40
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/
---

**Summary:** The EMR_ARC record specifies an elliptical arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfArc()](#EmfArc__1) | Initializes a new instance of the [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) class. |
| [EmfArc(source)](#EmfArc_source_2) | Initializes a new instance of the [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which <br/>            specifies the inclusive-inclusive bounding rectangle. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Gets or sets a 64-bit WMF PointL object that specifies the coordinates, in logical units, of <br/>            the ending point of the radial line defining the ending point of the arc. |
| size | int | r/w | Gets or sets the size of the record |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which <br/>            specifies the coordinates, in logical units, of the ending point of the radial line defining the <br/>            starting point of the arc. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfArc() {#EmfArc__1}


```
 EmfArc() 
```

Initializes a new instance of the [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) class.

### Constructor: EmfArc(source) {#EmfArc_source_2}


```
 EmfArc(source) 
```

Initializes a new instance of the [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) class.

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


