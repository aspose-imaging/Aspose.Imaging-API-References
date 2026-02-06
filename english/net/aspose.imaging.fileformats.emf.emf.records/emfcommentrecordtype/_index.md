---
title: Class EmfCommentRecordType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentRecordType class. The comment record types define formats for specifying arbitrary private data embedding records in other metafile formats and adding new or specialpurpose commands
type: docs
weight: 3520
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
## EmfCommentRecordType class

The comment record types define formats for specifying arbitrary private data, embedding records in other metafile formats, and adding new or special-purpose commands.

```csharp
public abstract class EmfCommentRecordType : EmfRecord
```

## Properties

| Name | Description |
| --- | --- |
| virtual [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/commentidentifier/) { get; set; } | Gets or sets the comment identifier. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if present |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfRecord](../emfrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


