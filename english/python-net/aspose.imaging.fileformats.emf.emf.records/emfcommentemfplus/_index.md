---
title: EmfCommentEmfPlus Class
type: docs
weight: 170
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---

The EMR_COMMENT_EMFPLUS record contains embedded EMF+ records. <br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentEmfPlus

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfCommentEmfPlus type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfCommentEmfPlus(source)|Initializes a new instance of the EmfCommentEmfPlus class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|data_size|Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the <br/>            CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that <br/>            follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if <br/>            present|
|comment_identifier|Gets or sets a 32-bit unsigned integer that identifies this comment record <br/>            as containing EMF+ records. The value 0x2B464D45, which is the ASCII string "+FME", <br/>            identifies this as an EMR_COMMENT_EMFPLUS record.|
|emf_plus_records|Gets or sets an array of bytes that contains one or more EMF+ records ([MS-EMFPLUS] section 2.3.1).|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
