---
title: Class EmfPlusEndContainer
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusEndContainer class. The EmfPlusEndContainer record closes a graphics state container that was previously opened by a begin container operation
type: docs
weight: 6160
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
## EmfPlusEndContainer class

The EmfPlusEndContainer record closes a graphics state container that was previously opened by a begin container operation.

```csharp
public sealed class EmfPlusEndContainer : EmfPlusStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusEndContainer](emfplusendcontainer/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusEndContainer` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/stackindex/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the index of a graphics state container. The index MUST must match the value associated with a graphics state container opened by a previous EmfPlusBeginContainer (section 2.3.7.1) or EmfPlusBeginContainerNoParams record (section 2.3.7.2). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusStateRecordType](../emfplusstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


