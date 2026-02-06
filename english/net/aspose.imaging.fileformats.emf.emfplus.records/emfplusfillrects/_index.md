---
title: Class EmfPlusFillRects
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillRects class. The EmfPlusFillRects record specifies filling the interiors of a series of rectangles
type: docs
weight: 6230
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
## EmfPlusFillRects class

The EmfPlusFillRects record specifies filling the interiors of a series of rectangles

```csharp
public sealed class EmfPlusFillRects : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusFillRects](emfplusfillrects/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusFillRects` class. |

## Properties

| Name | Description |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/brushid/) { get; set; } | Gets or sets the brush identifier A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/compressed/) { get; set; } | Gets or sets a value indicating whether this `EmfPlusFillRects` is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39) object |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/iscolor/) { get; set; } | Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/rectdata/) { get; set; } | Gets or sets the rectangle data An array of either an EmfPlusRect or EmfPlusRectF objects of Count length that defines the rectangle data. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


