---
title: Class EmfPlusBeginContainerNoParams
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusBeginContainerNoParams class. The EmfPlusBeginContainerNoParams record opens a new graphics state container
type: docs
weight: 5970
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
## EmfPlusBeginContainerNoParams class

The EmfPlusBeginContainerNoParams record opens a new graphics state container.

```csharp
public sealed class EmfPlusBeginContainerNoParams : EmfPlusStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusBeginContainerNoParams](emfplusbegincontainernoparams/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusBeginContainerNoParams` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/stackindex/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies an index to associate with the graphics state container. The index MUST be referenced by a subsequent EmfPlusEndContainer record (section 2.3.7.3) to close the graphics state container. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusStateRecordType](../emfplusstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


