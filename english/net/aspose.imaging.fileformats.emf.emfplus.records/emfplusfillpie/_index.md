---
title: Class EmfPlusFillPie
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillPie class. The EmfPlusFillPie record specifies filling a section of the interior of an ellipse
type: docs
weight: 6210
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---
## EmfPlusFillPie class

The EmfPlusFillPie record specifies filling a section of the interior of an ellipse

```csharp
public sealed class EmfPlusFillPie : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusFillPie](emfplusfillpie/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusFillPie` class. |

## Properties

| Name | Description |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/brushid/) { get; set; } | Gets or sets the brush identifier A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/compressed/) { get; set; } | Gets or sets a value indicating whether the PointData is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/iscolor/) { get; set; } | Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/rectdata/) { get; set; } | Gets or sets the rectangle datas Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse that contains the pie wedge. This rectangle defines the position, size, and shape of the pie. The type of object in this field is specified by the value of the Flags field. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [StartAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/startangle/) { get; set; } | Gets or sets the start angle A 32-bit, non-negative floating-point value that specifies the angle between the x-axis and the starting point of the pie wedge. Any value is acceptable, but it MUST be interpreted modulo 360, with the result that is used being in the range 0.0 inclusive to 360.0 exclusive. |
| [SweepAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/sweepangle/) { get; set; } | Gets or sets the sweep angle A 32-bit floating-point value that specifies the extent of the arc that defines the pie wedge to draw, as an angle in degrees measured from the starting point defined by the StartAngle value. Any value is acceptable, but it MUST be clamped to -360.0 to 360.0 inclusive. A positive value indicates that the sweep is defined in a clockwise direction, and a negative value indicates that the sweep is defined in a counter-clockwise direction. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


