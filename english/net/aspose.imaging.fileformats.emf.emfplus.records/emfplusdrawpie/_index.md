---
title: Class EmfPlusDrawPie
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawPie class. The EmfPlusDrawPie record specifies drawing a section of the interior of an ellipse
type: docs
weight: 6120
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---
## EmfPlusDrawPie class

The EmfPlusDrawPie record specifies drawing a section of the interior of an ellipse.

```csharp
public sealed class EmfPlusDrawPie : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusDrawPie](emfplusdrawpie/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusDrawPie` class. |

## Properties

| Name | Description |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/compressed/) { get; set; } | Gets or sets a value indicating whether the PointData is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/objectid/) { get; set; } | Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the pie. The value MUST be zero to 63, inclusive. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/rectdata/) { get; set; } | Gets or sets the rectangle datas Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse that contains the pie wedge. This rectangle defines the position, size, and shape of the pie. The type of object in this field is specified by the value of the Flags field. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [StartAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/startangle/) { get; set; } | Gets or sets the start angle A 32-bit, non-negative floating-point value that specifies the angle between the x-axis and the starting point of the pie wedge. Any value is acceptable, but it MUST be interpreted modulo 360, with the result that is used being in the range 0.0 inclusive to 360.0 exclusive. |
| [SweepAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/sweepangle/) { get; set; } | Gets or sets the sweep angle A 32-bit floating-point value that specifies the extent of the arc that defines the pie wedge to draw, as an angle in degrees measured from the starting point defined by the StartAngle value. Any value is acceptable, but it MUST be clamped to -360.0 to 360.0 inclusive. A positive value indicates that the sweep is defined in a clockwise direction, and a negative value indicates that the sweep is defined in a counter-clockwise direction. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


