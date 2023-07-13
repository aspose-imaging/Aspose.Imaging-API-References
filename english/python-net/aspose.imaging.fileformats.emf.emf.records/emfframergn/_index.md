---
title: EmfFrameRgn Class
type: docs
weight: 520
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/
---

The EMR_FRAMERGN record draws a border around the specified region using the specified brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFrameRgn

**Inheritance:** EmfDrawingRecordType

**Aspose.Imaging Version:** 23.6

The EmfFrameRgn type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfFrameRgn(source)](#EmfFrameRgn_source_0) | Initializes a new instance of the [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) class. |
| [EmfFrameRgn()](#EmfFrameRgn__1) | Initializes a new instance of the [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which <br/>            specifies the bounding rectangle. |
| rgn_data_size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the size of region data, in bytes. |
| ih_brush | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the brush EMF Object Table index. |
| width | int | r/w | Gets or sets a 32-bit signed integer that specifies the width of the vertical brush stroke, in logical units. |
| height | int | r/w | Gets or sets a 32-bit signed integer that specifies the height of the horizontal brush <br/>            stroke, in logical units. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | Gets or sets a RgnDataSize length array of bytes that specifies a RegionData object, <br/>            in logical units |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfFrameRgn(source) {#EmfFrameRgn_source_0}


```
 EmfFrameRgn(source) 
```

Initializes a new instance of the [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfFrameRgn() {#EmfFrameRgn__1}


```
 EmfFrameRgn() 
```

Initializes a new instance of the [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) class.

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


