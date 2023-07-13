---
title: EmfCommentBeginGroup Class
type: docs
weight: 160
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---

The EMR_COMMENT_BEGINGROUP record specifies the beginning of a group of drawing records.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentBeginGroup

**Inheritance:** EmfCommentPublicRecordType

**Aspose.Imaging Version:** 23.6

The EmfCommentBeginGroup type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfCommentBeginGroup(source)](#EmfCommentBeginGroup_source_0) | Initializes a new instance of the [EmfCommentBeginGroup](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the <br/>            CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that <br/>            follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if <br/>            present |
| comment_identifier | EmfCommentRecordType.CommentIdentifierEnum | r/w | Gets or sets a 32-bit unsigned integer that identifies this comment record <br/>            as specifying public data. The value 0x43494447, which is the ASCII string "CIDG", identifies <br/>            this as an EMR_COMMENT_PUBLIC record. |
| public_comment_identifier | [EmfEmrComment](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfemrcomment/) | r/w | Gets or sets a 32-bit unsigned integer that identifies the type of <br/>            public comment record. This SHOULD be one of the values listed in the preceding table, which <br/>            are specified in the EmrComment enumeration (section 2.1.10), unless additional public <br/>            comment record types have been implemented on the print server. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the<br/>            output rectangle in logical coordinates. |
| n_description | int | r/w | Gets or sets the number of Unicode characters in the optional description string that follows. |
| description | string | r/w | Gets or sets an optional, null-terminated Unicode string that describes this group of records. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfCommentBeginGroup(source) {#EmfCommentBeginGroup_source_0}


```
 EmfCommentBeginGroup(source) 
```

Initializes a new instance of the [EmfCommentBeginGroup](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### create_from_record(source)  [static] {#create_from_record_source_1}


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


### create_from_type(type)  [static] {#create_from_type_type_2}


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


