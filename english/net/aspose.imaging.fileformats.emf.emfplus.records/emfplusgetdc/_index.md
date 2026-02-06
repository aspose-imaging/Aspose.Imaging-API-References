---
title: Class EmfPlusGetDc
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusGetDc class. The EmfPlusGetDC record specifies that subsequent EMF records encountered in the metafile SHOULD be processed
type: docs
weight: 6250
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/
---
## EmfPlusGetDc class

The EmfPlusGetDC record specifies that subsequent EMF records encountered in the metafile SHOULD be processed.

```csharp
public sealed class EmfPlusGetDc : EmfPlusControlRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusGetDc](emfplusgetdc/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusGetDc` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusgetdc/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that is not used. This field SHOULD be set to zero and MUST be ignored upon receipt |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


