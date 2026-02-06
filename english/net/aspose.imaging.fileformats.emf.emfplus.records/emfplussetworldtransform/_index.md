---
title: Class EmfPlusSetWorldTransform
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetWorldTransform class. The EmfPlusSetWorldTransform record sets the world transform according to the values in a specified transform matrix
type: docs
weight: 6540
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---
## EmfPlusSetWorldTransform class

The EmfPlusSetWorldTransform record sets the world transform according to the values in a specified transform matrix.

```csharp
public sealed class EmfPlusSetWorldTransform : EmfPlusTerminalServerRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSetWorldTransform](emfplussetworldtransform/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSetWorldTransform` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [MatrixData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/matrixdata/) { get; set; } | Gets or sets an EmfPlusTransformMatrix object (section 2.2.2.47) that defines the new current world transform. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


