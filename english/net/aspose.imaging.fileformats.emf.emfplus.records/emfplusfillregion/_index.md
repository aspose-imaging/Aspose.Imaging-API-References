---
title: Class EmfPlusFillRegion
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillRegion class. The EmfPlusFillRegion record specifies filling the interior of a graphics region
type: docs
weight: 6240
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---
## EmfPlusFillRegion class

The EmfPlusFillRegion record specifies filling the interior of a graphics region

```csharp
public sealed class EmfPlusFillRegion : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusFillRegion](emfplusfillregion/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusFillRegion` class. |

## Properties

| Name | Description |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/brushid/) { get; set; } | Gets or sets the brush identifier A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/iscolor/) { get; set; } | Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/objectid/) { get; set; } | Gets or sets the object identifier. The index of the EmfPlusRegion object (section 2.2.1.8) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


