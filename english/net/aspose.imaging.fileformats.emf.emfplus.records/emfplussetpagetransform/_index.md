---
title: Class EmfPlusSetPageTransform
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetPageTransform class. The EmfPlusSetPageTransform record specifies scaling factors and units for converting page space coordinates to device space coordinates
type: docs
weight: 6470
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
## EmfPlusSetPageTransform class

The EmfPlusSetPageTransform record specifies scaling factors and units for converting page space coordinates to device space coordinates.

```csharp
public sealed class EmfPlusSetPageTransform : EmfPlusTerminalServerRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSetPageTransform](emfplussetpagetransform/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSetPageTransform` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [PageScale](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/pagescale/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the scale factor for converting page space coordinates to device space coordinates. |
| [PageUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/pageunit/) { get; } | Gets the unit of measure for page space coordinates, from the UnitType enumeration (section 2.1.1.33). This value SHOULD NOT be UnitTypeDisplay or UnitTypeWorld. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


