---
title: Class EmfCommentPublicRecordType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentPublicRecordType class. The EMR_COMMENT_PUBLIC record types specify extensions to EMF processing
type: docs
weight: 3510
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
## EmfCommentPublicRecordType class

The EMR_COMMENT_PUBLIC record types specify extensions to EMF processing.

```csharp
public abstract class EmfCommentPublicRecordType : EmfCommentRecordType
```

## Properties

| Name | Description |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier/) { get; set; } | Gets or sets a 32-bit unsigned integer that identifies this comment record as specifying public data. The value 0x43494447, which is the ASCII string "CIDG", identifies this as an EMR_COMMENT_PUBLIC record. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if present |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier/) { get; set; } | Gets or sets a 32-bit unsigned integer that identifies the type of public comment record. This SHOULD be one of the values listed in the preceding table, which are specified in the EmrComment enumeration (section 2.1.10), unless additional public comment record types have been implemented on the print server. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfCommentRecordType](../emfcommentrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


