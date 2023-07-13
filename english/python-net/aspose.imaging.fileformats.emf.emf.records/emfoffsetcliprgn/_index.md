---
title: EmfOffsetClipRgn Class
type: docs
weight: 680
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/
---

The EMR_OFFSETCLIPRGN record moves the current clipping region in the playback device context <br/>            by the specified offsets.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfOffsetClipRgn

**Inheritance:** EmfClippingRecordType

**Aspose.Imaging Version:** 23.6

The EmfOffsetClipRgn type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfOffsetClipRgn(source)](#EmfOffsetClipRgn_source_0) | Initializes a new instance of the [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) class. |
| [EmfOffsetClipRgn()](#EmfOffsetClipRgn__1) | Initializes a new instance of the [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| offset | [Point](/imaging/python-net/aspose.imaging/point) | r/w | Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the <br/>            horizontal and vertical offsets in logical units. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfOffsetClipRgn(source) {#EmfOffsetClipRgn_source_0}


```
 EmfOffsetClipRgn(source) 
```

Initializes a new instance of the [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfOffsetClipRgn() {#EmfOffsetClipRgn__1}


```
 EmfOffsetClipRgn() 
```

Initializes a new instance of the [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) class.

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


