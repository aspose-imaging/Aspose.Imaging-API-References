---
title: Class EmfCommentEmfPlus
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentEmfPlus class. The EMR_COMMENT_EMFPLUS record contains embedded EMF records. Note Fields that are not described in this section are specified in section 2.3.3
type: docs
weight: 3460
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
## EmfCommentEmfPlus class

The EMR_COMMENT_EMFPLUS record contains embedded EMF+ records. Note Fields that are not described in this section are specified in section 2.3.3.

```csharp
public sealed class EmfCommentEmfPlus : EmfCommentRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCommentEmfPlus](emfcommentemfplus/)(EmfRecord) | Initializes a new instance of the `EmfCommentEmfPlus` class. |

## Properties

| Name | Description |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/commentidentifier/) { get; set; } | Gets or sets a 32-bit unsigned integer that identifies this comment record as containing EMF+ records. The value 0x2B464D45, which is the ASCII string "+FME", identifies this as an EMR_COMMENT_EMFPLUS record. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if present |
| [EmfPlusRecords](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/emfplusrecords/) { get; set; } | Gets or sets an array of bytes that contains one or more EMF+ records ([MS-EMFPLUS] section 2.3.1). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfCommentRecordType](../emfcommentrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


