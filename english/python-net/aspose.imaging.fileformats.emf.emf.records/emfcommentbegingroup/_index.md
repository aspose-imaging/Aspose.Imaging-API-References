---
title: EmfCommentBeginGroup Class
type: docs
weight: 160
url: /python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---

The EMR_COMMENT_BEGINGROUP record specifies the beginning of a group of drawing records.

**Namespace:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/api-reference/aspose.imaging.fileformats.emf.emf.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emf.records.EmfCommentBeginGroup

**Assembly:**  Aspose.Imaging Version: 23.3.0

The EmfCommentBeginGroup type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfCommentBeginGroup(source)|Initializes a new instance of the EmfCommentBeginGroup class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|size|  |
|data_size|  |
|comment_identifier|Gets or sets a 32-bit unsigned integer that identifies this comment record <br/>            as specifying public data. The value 0x43494447, which is the ASCII string "CIDG", identifies <br/>            this as an EMR_COMMENT_PUBLIC record.|
|public_comment_identifier|Gets or sets a 32-bit unsigned integer that identifies the type of <br/>            public comment record. This SHOULD be one of the values listed in the preceding table, which <br/>            are specified in the EmrComment enumeration (section 2.1.10), unless additional public <br/>            comment record types have been implemented on the print server.|
|rectangle|Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the<br/>            output rectangle in logical coordinates.|
|n_description|Gets or sets the number of Unicode characters in the optional description string that follows.|
|description|Gets or sets an optional, null-terminated Unicode string that describes this group of records.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|create_from_record(source)|  |
|create_from_type(type)|  |
