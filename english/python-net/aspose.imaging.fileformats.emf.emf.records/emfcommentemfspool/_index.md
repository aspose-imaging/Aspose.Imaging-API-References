---
title: EmfCommentEmfSpool Class
type: docs
weight: 180
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---

The EMR_COMMENT_EMFSPOOL record contains embedded EMFSPOOL records. <br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEmfSpool

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfCommentEmfSpool type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfCommentEmfSpool(source)|Initializes a new instance of the EmfCommentEmfSpool class|
|EmfCommentEmfSpool()|Initializes a new instance of the [EmfCommentEmfSpool](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/) class.|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|data_size|Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the <br/>            CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that <br/>            follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if <br/>            present|
|comment_identifier|Gets or sets a 32-bit unsigned integer that identifies this comment record <br/>            as containing EMFSPOOL records. The value 0x00000000 identifies this as an <br/>            EMR_COMMENT_EMFSPOOL record.|
|emf_spool_record_identifier|Gets or sets a 32-bit unsigned integer that identifies the type of <br/>            EMR_COMMENT_EMFSPOOL record.|
|emf_spool_records|Gets or sets a variable-length array of bytes that contains one or more <br/>            EMFSPOOL font definition records ([MS-EMFSPOOL] section 2.2.3.3).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
