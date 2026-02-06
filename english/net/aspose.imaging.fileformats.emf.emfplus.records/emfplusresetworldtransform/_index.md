---
title: Class EmfPlusResetWorldTransform
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusResetWorldTransform class. The EmfPlusResetWorldTransform record resets the current world space transform to the identify matrix
type: docs
weight: 6340
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusresetworldtransform/
---
## EmfPlusResetWorldTransform class

The EmfPlusResetWorldTransform record resets the current world space transform to the identify matrix.

```csharp
public sealed class EmfPlusResetWorldTransform : EmfPlusTerminalServerRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusResetWorldTransform](emfplusresetworldtransform/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusResetWorldTransform` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


