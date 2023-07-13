---
title: EmfArcTo Class
type: docs
weight: 50
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/
---

The EMR_ARCTO record specifies an elliptical arc. It resets the current position to the end point of the arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArcTo

**Inheritance:** EmfDrawingRecordType

**Aspose.Imaging Version:** 23.6

The EmfArcTo type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfArcTo(source)](#EmfArcTo_source_0) | Initializes a new instance of the [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) class. |
| [EmfArcTo()](#EmfArcTo__1) | Initializes a new instance of the [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which <br/>            specifies the bounding rectangle. |
| start | [Point](/imaging/python-net/aspose.imaging/point) | r/w | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which <br/>            specifies the coordinates of the first radial ending point, in logical units. |
| end | [Point](/imaging/python-net/aspose.imaging/point) | r/w | Gets or sets a 64-bit WMF PointL object that specifies the coordinates of the second radial <br/>            ending point, in logical units. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfArcTo(source) {#EmfArcTo_source_0}


```
 EmfArcTo(source) 
```

Initializes a new instance of the [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfArcTo() {#EmfArcTo__1}


```
 EmfArcTo() 
```

Initializes a new instance of the [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) class.

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


