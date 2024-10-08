---
title: Class EmfPlusComment
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusComment class. The EmfPlusComment record specifies arbitrary private data
type: docs
weight: 5950
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
## EmfPlusComment class

The EmfPlusComment record specifies arbitrary private data.

```csharp
public sealed class EmfPlusComment : EmfPlusRecord
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusComment](emfpluscomment/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusComment` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that is not used. This field SHOULD be set to zero and MUST be ignored upon receipt |
| [PrivateData](../../aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/privatedata/) { get; set; } | Gets or sets a DataSize-length byte array of private data. bytes of record-specific data that follows. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusRecord](../emfplusrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


