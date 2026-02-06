---
title: Class EmfPlusSave
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSave class. The EmfPlusSave record saves the graphics state identified by a specified index on a stack of saved graphics states
type: docs
weight: 6370
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---
## EmfPlusSave class

The EmfPlusSave record saves the graphics state, identified by a specified index, on a stack of saved graphics states.

```csharp
public sealed class EmfPlusSave : EmfPlusStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSave](emfplussave/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSave` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussave/stackindex/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies a level to associate with the graphics state. The level value can be used by a subsequent EmfPlusRestore record (section 2.3.7.4) operation to retrieve the graphics state. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusStateRecordType](../emfplusstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


