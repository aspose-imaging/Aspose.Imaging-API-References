---
title: EmfCommentEmfSpool Class
type: docs
weight: 190
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---

**Summary:** The EMR_COMMENT_EMFSPOOL record contains embedded EMFSPOOL records. <br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEmfSpool

**Inheritance:** EmfCommentRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool__1) | Initializes a new instance of the [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) class. |
| [EmfCommentEmfSpool(source)](#EmfCommentEmfSpool_source_2) | Initializes a new instance of the [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| comment_identifier | [EmfCommentRecordType+CommentIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype+commentidentifierenum/) | r/w | Gets or sets a 32-bit unsigned integer that identifies this comment record <br/>            as containing EMFSPOOL records. The value 0x00000000 identifies this as an <br/>            EMR_COMMENT_EMFSPOOL record. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the <br/>            CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that <br/>            follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if <br/>            present |
| emf_spool_record_identifier | [EmfCommentEmfSpool+EmfSpoolRecordIdentifierEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool+emfspoolrecordidentifierenum/) | r/w | Gets or sets a 32-bit unsigned integer that identifies the type of <br/>            EMR_COMMENT_EMFSPOOL record. |
| emf_spool_records | [EmfSpoolFontDefinitionRecordType[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype/) | r/w | Gets or sets a variable-length array of bytes that contains one or more <br/>            EMFSPOOL font definition records ([MS-EMFSPOOL] section 2.2.3.3). |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfCommentEmfSpool() {#EmfCommentEmfSpool__1}


```
 EmfCommentEmfSpool() 
```

Initializes a new instance of the [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) class.

### Constructor: EmfCommentEmfSpool(source) {#EmfCommentEmfSpool_source_2}


```
 EmfCommentEmfSpool(source) 
```

Initializes a new instance of the [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) class.

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


