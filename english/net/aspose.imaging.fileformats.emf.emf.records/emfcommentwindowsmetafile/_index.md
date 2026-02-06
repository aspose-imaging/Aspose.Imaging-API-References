---
title: Class EmfCommentWindowsMetaFile
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCommentWindowsMetaFile class. The EMR_COMMENT_WINDOWS_METAFILE record specifies an image in an embedded WMF metafile
type: docs
weight: 3540
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/
---
## EmfCommentWindowsMetaFile class

The EMR_COMMENT_WINDOWS_METAFILE record specifies an image in an embedded WMF metafile.

```csharp
public sealed class EmfCommentWindowsMetaFile : EmfCommentPublicRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCommentWindowsMetaFile](emfcommentwindowsmetafile/)(EmfRecord) | Initializes a new instance of the `EmfCommentWindowsMetaFile` class. |

## Properties

| Name | Description |
| --- | --- |
| [Checksum](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/checksum/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the checksum for this record. |
| override [CommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/commentidentifier/) { get; set; } | Gets or sets a 32-bit unsigned integer that identifies this comment record as specifying public data. The value 0x43494447, which is the ASCII string "CIDG", identifies this as an EMR_COMMENT_PUBLIC record. |
| [DataSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the CommentIdentifier and CommentRecordParm fields in the RecordBuffer field that follows. It MUST NOT include the size of itself or the size of the AlignmentPadding field, if present |
| [Flags](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/flags/) { get; set; } | Gets or sets a 32-bit value that MUST be 0x00000000 and MUST be ignored. |
| [PublicCommentIdentifier](../../aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/publiccommentidentifier/) { get; set; } | Gets or sets a 32-bit unsigned integer that identifies the type of public comment record. This SHOULD be one of the values listed in the preceding table, which are specified in the EmrComment enumeration (section 2.1.10), unless additional public comment record types have been implemented on the print server. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [Version](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/version/) { get; set; } | Gets or sets a 16-bit unsigned integer that specifies the WMF metafile version in terms of support for device-independent bitmaps (DIBs), from the WMF MetafileVersion enumeration ([MS-WMF] section 2.1.1.19). |
| [WinMetafile](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/winmetafile/) { get; set; } | Gets or sets a buffer that contains the WMF metafile. |
| [WinMetafileSize](../../aspose.imaging.fileformats.emf.emf.records/emfcommentwindowsmetafile/winmetafilesize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the WMF metafile in the WinMetafile field. |

### See Also

* class [EmfCommentPublicRecordType](../emfcommentpublicrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


