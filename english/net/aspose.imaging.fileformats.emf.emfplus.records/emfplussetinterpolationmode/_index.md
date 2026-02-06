---
title: Class EmfPlusSetInterpolationMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetInterpolationMode class. The EmfPlusSetInterpolationMode record specifies how image scaling including stretching and shrinking is performed
type: docs
weight: 6460
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/
---
## EmfPlusSetInterpolationMode class

The EmfPlusSetInterpolationMode record specifies how image scaling, including stretching and shrinking, is performed.

```csharp
public sealed class EmfPlusSetInterpolationMode : EmfPlusPropertyRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSetInterpolationMode](emfplussetinterpolationmode/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSetInterpolationMode` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [InterpolationMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetinterpolationmode/interpolationmode/) { get; set; } | Gets or sets the interpolation mode value, from the InterpolationMode enumeration (section 2.1.1.16). |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


