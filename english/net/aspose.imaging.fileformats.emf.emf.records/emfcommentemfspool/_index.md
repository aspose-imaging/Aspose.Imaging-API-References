---
title: Class EmfCommentEmfSpool
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentEmfSpool class. The EMR_COMMENT_EMFSPOOL record contains embedded EMFSPOOL records. Note Fields that are not described in this section are specified in section 2.3.3
type: docs
weight: 3470
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
## EmfCommentEmfSpool class

The EMR_COMMENT_EMFSPOOL record contains embedded EMFSPOOL records. Note Fields that are not described in this section are specified in section 2.3.3.

```csharp
public sealed class EmfCommentEmfSpool : EmfCommentRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCommentEmfSpool](emfcommentemfspool/#constructor)() | Initializes a new instance of the `EmfCommentEmfSpool` class. |
| [EmfCommentEmfSpool](emfcommentemfspool/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfCommentEmfSpool` class. |

## Properties

| Name | Description |
| --- | --- |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/commentidentifier/) { get; set; } | Gets or sets a 32-bit unsigned integer that identifies this comment record as containing EMFSPOOL records. The value 0x00000000 identifies this as an EMR_COMMENT_EMFSPOOL record. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if present |
| [EmfSpoolRecordIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/emfspoolrecordidentifier/) { get; set; } | Gets or sets a 32-bit unsigned integer that identifies the type of EMR_COMMENT_EMFSPOOL record. |
| [EmfSpoolRecords](../../aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/emfspoolrecords/) { get; set; } | Gets or sets a variable-length array of bytes that contains one or more EMFSPOOL font definition records ([MS-EMFSPOOL] section 2.2.3.3). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfCommentRecordType](../emfcommentrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


