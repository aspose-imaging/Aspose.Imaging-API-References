---
title: Class EmfPlusSetClipRegion
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetClipRegion class. The EmfPlusSetClipRegion record combines the current clipping region with another graphics region. The new current clipping region is set to the result of performing the CombineMode operation on the previous current clipping region and the specified EmfPlusRegion object
type: docs
weight: 6430
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---
## EmfPlusSetClipRegion class

The EmfPlusSetClipRegion record combines the current clipping region with another graphics region. The new current clipping region is set to the result of performing the CombineMode operation on the previous current clipping region and the specified EmfPlusRegion object.

```csharp
public sealed class EmfPlusSetClipRegion : EmfPlusClippingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSetClipRegion](emfplussetclipregion/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSetClipRegion` class. |

## Properties

| Name | Description |
| --- | --- |
| [Cm](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/cm/) { get; set; } | Gets or sets the CM (4 bits): Specifies the logical operation for combining two regions. See the CombineMode enumeration (section 2.1.1.4) for the meanings of the values. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/objectid/) { get; set; } | Gets or sets the index of an EmfPlusRegion object (section 2.2.1.8) in the EMF+ Object Table.The value MUST be zero to 63, inclusive. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusClippingRecordType](../emfplusclippingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


