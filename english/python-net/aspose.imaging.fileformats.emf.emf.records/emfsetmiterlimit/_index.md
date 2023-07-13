---
title: EmfSetMiterLimit Class
type: docs
weight: 1210
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmiterlimit/
---

The EMR_SETMITERLIMIT record specifies the limit for the length of miter joins for the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetMiterLimit

**Inheritance:** EmfStateRecordType

**Aspose.Imaging Version:** 23.6

The EmfSetMiterLimit type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfSetMiterLimit(source)](#EmfSetMiterLimit_source_0) | Initializes a new instance of the [EmfSetMiterLimit](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmiterlimit/) class. |
| [EmfSetMiterLimit()](#EmfSetMiterLimit__1) | Initializes a new instance of the [EmfSetMiterLimit](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmiterlimit/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| miter_limit | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the new miter length limit. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfSetMiterLimit(source) {#EmfSetMiterLimit_source_0}


```
 EmfSetMiterLimit(source) 
```

Initializes a new instance of the [EmfSetMiterLimit](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmiterlimit/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetMiterLimit() {#EmfSetMiterLimit__1}


```
 EmfSetMiterLimit() 
```

Initializes a new instance of the [EmfSetMiterLimit](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmiterlimit/) class.

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


