---
title: Class EmfPlusHeader
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusHeader class. The EmfPlusHeader record specifies the start of EMF data in the metafile. The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record which MUST be the record immediately following the EMF header in the metafile. The EMR_COMMENT_EMFPLUS record is specified in MSEMF section 2.3.3.2
type: docs
weight: 6260
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
## EmfPlusHeader class

The EmfPlusHeader record specifies the start of EMF+ data in the metafile. The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record, which MUST be the record immediately following the EMF header in the metafile. The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.

```csharp
public sealed class EmfPlusHeader : EmfPlusControlRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusHeader](emfplusheader/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusHeader` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| [DualMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode/) { get; set; } | Gets or sets a value indicating whether [dual mode]. If set, this flag indicates that this metafile is "dual-mode", which means that it contains two sets of records, each of which completely specifies the graphics content. If clear, the graphics content is specified by EMF+ records, and possibly EMF records that are preceded by an EmfPlusGetDC record. If this flag is set, EMF records alone SHOULD suffice to define the graphics content. Note that whether the "dual-mode" flag is set or not, some EMF records are always present, namely EMF control records and the EMF records that contain EMF+ records. EMF control records are specified in [MS-EMF] section 2.3.4. |
| [EmfPlusFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/emfplusflags/) { get; set; } | Gets or sets the EMF plus flags. A 32-bit unsigned integer that contains information about how this metafile was recorded. if 31-st bit of the field is set, this flag indicates that the metafile was recorded with a reference device context for a video display. If clear, the metafile was recorded with a reference device context for a printer. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [IsValid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/isvalid/) { get; } | Gets a value indicating whether this instance is valid. |
| [LogicalDpiX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpix/) { get; set; } | Gets or sets the logical dpi x. A 32-bit unsigned integer that specifies the horizontal resolution for which the metafile was recorded, in units of pixels per inch. |
| [LogicalDpiY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpiy/) { get; set; } | Gets or sets the logical dpi y. A 32-bit unsigned integer that specifies the vertical resolution for which the metafile was recorded, in units of lines per inch |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/version/) { get; set; } | Gets or sets the version. An EmfPlusGraphicsVersion object (section 2.2.2.19) that specifies the version of operating system graphics that was used to create this metafile. |
| [VideoDisplay](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/videodisplay/) { get; set; } | Gets or sets a value indicating whether video display. if set, this flag indicates that the metafile was recorded with a reference device context for a video display. If clear, the metafile was recorded with a reference device context for a printer. |

### See Also

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


