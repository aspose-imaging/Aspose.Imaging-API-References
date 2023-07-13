---
title: EmfEof Class
type: docs
weight: 380
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---

The EMR_EOF record indicates the end of the metafile and specifies a palette.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEof

**Inheritance:** EmfControlRecordType

**Aspose.Imaging Version:** 23.6

The EmfEof type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfEof(record)](#EmfEof_record_0) | Initializes a new instance of the [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) class. |
| [EmfEof()](#EmfEof__1) | Initializes a new instance of the [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| palette_argb_32_entries | int | r/w | Gets or sets an optional buffer that contains palette data, which is not <br/>            required to be contiguous with the fixed portion of the EMR_EOF <br/>            record. Accordingly, fields in this buffer that are labeled <br/>            "UndefinedSpace" are optional and MUST be ignored. <br/>            The size of this field MUST be a multiple of 4 bytes |
| size_last | int | r/w | Gets or sets a 32-bit unsigned integer that MUST be the same as Size and MUST be the last <br/>            field of the record and hence the metafile. LogPaletteEntry objects, if they <br/>            exist, MUST precede this field. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfEof(record) {#EmfEof_record_0}


```
 EmfEof(record) 
```

Initializes a new instance of the [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The record. |

### EmfEof() {#EmfEof__1}


```
 EmfEof() 
```

Initializes a new instance of the [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) class.

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


