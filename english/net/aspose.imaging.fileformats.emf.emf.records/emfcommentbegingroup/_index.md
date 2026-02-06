---
title: Class EmfCommentBeginGroup
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentBeginGroup class. The EMR_COMMENT_BEGINGROUP record specifies the beginning of a group of drawing records
type: docs
weight: 3450
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---
## EmfCommentBeginGroup class

The EMR_COMMENT_BEGINGROUP record specifies the beginning of a group of drawing records.

```csharp
public sealed class EmfCommentBeginGroup : EmfCommentPublicRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCommentBeginGroup](emfcommentbegingroup/)(EmfRecord) | Initializes a new instance of the `EmfCommentBeginGroup` class. |

## Properties

| Name | Description |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier/) { get; set; } | Gets or sets a 32-bit unsigned integer that identifies this comment record as specifying public data. The value 0x43494447, which is the ASCII string "CIDG", identifies this as an EMR_COMMENT_PUBLIC record. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if present |
| [Description](../../aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/description/) { get; set; } | Gets or sets an optional, null-terminated Unicode string that describes this group of records. |
| [NDescription](../../aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/ndescription/) { get; set; } | Gets or sets the number of Unicode characters in the optional description string that follows. |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier/) { get; set; } | Gets or sets a 32-bit unsigned integer that identifies the type of public comment record. This SHOULD be one of the values listed in the preceding table, which are specified in the EmrComment enumeration (section 2.1.10), unless additional public comment record types have been implemented on the print server. |
| [Rectangle](../../aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/rectangle/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the output rectangle in logical coordinates. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


