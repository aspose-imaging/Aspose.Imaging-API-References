---
title: Class EmfCommentMultiFormats
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentMultiFormats class. The EMR_COMMENT_MULTIFORMATS record specifies an image in multiple graphics formats
type: docs
weight: 3500
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
## EmfCommentMultiFormats class

The EMR_COMMENT_MULTIFORMATS record specifies an image in multiple graphics formats.

```csharp
public sealed class EmfCommentMultiFormats : EmfCommentPublicRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCommentMultiFormats](emfcommentmultiformats/)(EmfRecord) | Initializes a new instance of the `EmfCommentMultiFormats` class. |

## Properties

| Name | Description |
| --- | --- |
| [AFormats](../../aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/aformats/) { get; set; } | Gets or sets a CountFormats length array of graphics formats, specified by EmrFormat objects (section 2.2.4), in order of preference |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier/) { get; set; } | Gets or sets a 32-bit unsigned integer that identifies this comment record as specifying public data. The value 0x43494447, which is the ASCII string "CIDG", identifies this as an EMR_COMMENT_PUBLIC record. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if present |
| [FormatData](../../aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/formatdata/) { get; set; } | Gets or sets a variable-length array of bytes of image data for all graphics formats contained in this record. The size of the data for each image is provided by the DataSize field in the corresponding EmrFormat object. Thus, the total size of this field is the sum of DataSize values in all EmrFormat objects. The graphics format of the data for each image is specified by the Signature field in the corresponding EmrFormat object. |
| [OutputRect](../../aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/outputrect/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the output rectangle, in logical coordinates. |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier/) { get; set; } | Gets or sets a 32-bit unsigned integer that identifies the type of public comment record. This SHOULD be one of the values listed in the preceding table, which are specified in the EmrComment enumeration (section 2.1.10), unless additional public comment record types have been implemented on the print server. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


