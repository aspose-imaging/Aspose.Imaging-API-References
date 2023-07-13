---
title: EmfCommentEmfSpool Class
type: docs
weight: 180
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---

The EMR_COMMENT_EMFSPOOL record contains embedded EMFSPOOL records. <br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEmfSpool

**Inheritance:** EmfCommentRecordType

**Aspose.Imaging Version:** 23.6

The EmfCommentEmfSpool type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfCommentEmfSpool(source)](#EmfCommentEmfSpool_source_0) | Initializes a new instance of the [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) class. |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool__1) | Initializes a new instance of the [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the <br/>            CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that <br/>            follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if <br/>            present |
| comment_identifier | EmfCommentRecordType.CommentIdentifierEnum | r/w | Gets or sets a 32-bit unsigned integer that identifies this comment record <br/>            as containing EMFSPOOL records. The value 0x00000000 identifies this as an <br/>            EMR_COMMENT_EMFSPOOL record. |
| emf_spool_record_identifier | EmfCommentEmfSpool.EmfSpoolRecordIdentifierEnum | r/w | Gets or sets a 32-bit unsigned integer that identifies the type of <br/>            EMR_COMMENT_EMFSPOOL record. |
| emf_spool_records | [EmfSpoolFontDefinitionRecordType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype/) | r/w | Gets or sets a variable-length array of bytes that contains one or more <br/>            EMFSPOOL font definition records ([MS-EMFSPOOL] section 2.2.3.3). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfCommentEmfSpool(source) {#EmfCommentEmfSpool_source_0}


```
 EmfCommentEmfSpool(source) 
```

Initializes a new instance of the [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfCommentEmfSpool() {#EmfCommentEmfSpool__1}


```
 EmfCommentEmfSpool() 
```

Initializes a new instance of the [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) class.

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


