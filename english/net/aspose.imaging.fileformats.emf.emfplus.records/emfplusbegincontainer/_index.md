---
title: Class EmfPlusBeginContainer
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusBeginContainer class. The EmfPlusBeginContainer record opens a new graphics state container and specifies a transform for it
type: docs
weight: 5960
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
## EmfPlusBeginContainer class

The EmfPlusBeginContainer record opens a new graphics state container and specifies a transform for it.

```csharp
public sealed class EmfPlusBeginContainer : EmfPlusStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusBeginContainer](emfplusbegincontainer/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusBeginContainer` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| [DestRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/destrect/) { get; set; } | Gets or sets an EmfPlusRectF object (section 2.2.2.39) that, with SrcRect, specifies a transform for the container. This transformation results in SrcRect when applied to DestRect. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [PageUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/pageunit/) { get; } | Gets the page unit. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/srcrect/) { get; set; } | Gets or sets an EmfPlusRectF rectangle that, with DestRect, specifies a transformation for the container. This transformation results in SrcRect when applied to DestRect. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/stackindex/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies an index to associate with the graphics state container. The index MUST be referenced by a subsequent EmfPlusEndContainer record (section 2.3.7.3) to close the graphics state container. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusStateRecordType](../emfplusstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


