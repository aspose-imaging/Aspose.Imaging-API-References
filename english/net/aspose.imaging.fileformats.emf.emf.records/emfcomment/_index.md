---
title: Class EmfComment
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfComment class. The EMR_COMMENT record contains arbitrary private data. Note Fields that are not described in this section are specified in section 2.3.3
type: docs
weight: 3440
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
## EmfComment class

The EMR_COMMENT record contains arbitrary private data. Note Fields that are not described in this section are specified in section 2.3.3.

```csharp
public sealed class EmfComment : EmfCommentRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfComment](emfcomment/)(EmfRecord) | Initializes a new instance of the `EmfComment` class. |

## Properties

| Name | Description |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcomment/commentidentifier/) { get; set; } | Gets or sets the comment identifier. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if present |
| [PrivateData](../../aspose.imaging.fileformats.emf.emf.records/emfcomment/privatedata/) { get; set; } | Gets or sets an optional array of bytes that specifies the private data. The first DWORD of this data MUST NOT be one of the predefined comment identifier values specified in section 2.3.3. Private data is unknown to EMF; it is meaningful only to applications that know the format of the data and how to use it. EMR_COMMENT private data records MAY be ignored. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfCommentRecordType](../emfcommentrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


