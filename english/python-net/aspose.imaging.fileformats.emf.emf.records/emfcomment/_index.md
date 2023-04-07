---
title: EmfComment Class
type: docs
weight: 150
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfcomment/
---

The EMR_COMMENT record contains arbitrary private data.<br/>            Note  Fields that are not described in this section are specified in section 2.3.3.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfComment

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfComment type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfComment(source)|Initializes a new instance of the EmfComment class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|data_size|Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the <br/>            CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that <br/>            follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if <br/>            present|
|comment_identifier|Gets or sets the comment identifier.|
|private_data|Gets or sets an optional array of bytes that specifies the private data. The first <br/>            DWORD of this data MUST NOT be one of the predefined comment identifier values specified <br/>            in section 2.3.3.<br/>            Private data is unknown to EMF; it is meaningful only to applications that know the format of the <br/>            data and how to use it. EMR_COMMENT private data records MAY be ignored.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
