---
title: Class EmfPlusDrawPath
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawPath class. The EmfPlusDrawPath record specifies drawing a graphics path
type: docs
weight: 6110
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
## EmfPlusDrawPath class

The EmfPlusDrawPath record specifies drawing a graphics path.

```csharp
public sealed class EmfPlusDrawPath : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusDrawPath](emfplusdrawpath/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusDrawPath` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/objectid/) { get; set; } | Gets or sets the object identifier. The index of the EmfPlusPath object (section 2.2.1.6) to draw, in the EMF+ Object Table. The value MUST be zero to 63, inclusive. |
| [PenId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/penid/) { get; set; } | Gets or sets the pen identifier A 32-bit unsigned integer that specifies an index in the EMF+ Object Table for an EmfPlusPen object (section 2.2.1.7) to use for drawing the EmfPlusPath. The value MUST be zero to 63, inclusive |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


