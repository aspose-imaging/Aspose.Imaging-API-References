---
title: Class EmfPlusFillPath
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillPath class. Fill path record FLAGS 16bit unsigned integer that provides information about how the operation is to be performed and about the structure of the record. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X  ObjectId  S 1 bit This bit indicates the type of data in the BrushId field. If set BrushId specifies a color as an EmfPlusARGB object section 2.2.2.1. If clear BrushId contains the index of an EmfPlusBrush object section 2.2.1.1 in the EMF Object Table. X 1 bit Reserved and MUST be ignored. ObjectId 1 byte The index of the EmfPlusPath object section 2.2.1.6 to fill in the EMF Object Table. The value MUST be zero to 63 inclusive
type: docs
weight: 6200
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
## EmfPlusFillPath class

Fill path record FLAGS: 16-bit unsigned integer that provides information about how the operation is to be performed, and about the structure of the record. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X &#x7C; ObjectId &#x7C; S (1 bit): This bit indicates the type of data in the BrushId field. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table. X (1 bit): Reserved and MUST be ignored. ObjectId (1 byte): The index of the EmfPlusPath object (section 2.2.1.6) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

```csharp
public sealed class EmfPlusFillPath : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusFillPath](emfplusfillpath/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusFillPath` class. |

## Properties

| Name | Description |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/brushid/) { get; set; } | Gets or sets the Brush ID A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/iscolor/) { get; set; } | Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/objectid/) { get; set; } | Gets or sets the object identifier. The index of the EmfPlusPath object (section 2.2.1.6) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


