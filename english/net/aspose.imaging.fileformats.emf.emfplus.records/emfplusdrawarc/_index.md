---
title: Class EmfPlusDrawArc
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawArc class. The EmfPlusDrawArc record specifies drawing the arc of an ellipse
type: docs
weight: 6020
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
## EmfPlusDrawArc class

The EmfPlusDrawArc record specifies drawing the arc of an ellipse.

```csharp
public sealed class EmfPlusDrawArc : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusDrawArc](emfplusdrawarc/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusDrawArc` class. |

## Properties

| Name | Description |
| --- | --- |
| override [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/datasize/) { get; set; } | Gets or sets the size of the data. A 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes of record-specific data that follows. For this record type, the value MUST be one of the following: 0x00000010 If the C bit is set in the Flags field. 0x00000018 If the C bit is clear in the Flags field. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/objectid/) { get; set; } | Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the arc. The value MUST be zero to 63, inclusive. |
| [RectangleData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/rectangledata/) { get; set; } | Gets or sets the rectangle data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse that is collinear with the arc. This rectangle defines the position, size, and shape of the arc. The type of object in this field is specified by the value of the Flags field. |
| [RectFloat](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/rectfloat/) { get; set; } | Gets or sets a value indicating whether the data contains EmfPlusRectF or EmfPlusRect records This bit indicates whether the data in the RectData field is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39). |
| override [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/size/) { get; set; } | Gets or sets the size. A 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. For this record type, the value MUST be one of the following: 0x0000001C If the C bit is set in the Flags field. 0x00000024 If the C bit is clear in the Flags field |
| [StartAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/startangle/) { get; set; } | Gets or sets the start angle A 32-bit non-negative floating-point value that specifies the angle between the x-axis and the starting point of the arc. Any value is acceptable, but it MUST be interpreted modulo 360, with the result that is used being in the range 0.0 inclusive to 360.0 exclusive. |
| [SweepAngle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/sweepangle/) { get; set; } | Gets or sets the sweep angle A 32-bit floating-point value that specifies the extent of the arc to draw, as an angle in degrees measured from the starting point defined by the StartAngle value. Any value is acceptable, but it MUST be clamped to -360.0 to 360.0 inclusive. A positive value indicates that the sweep is defined in a clockwise direction, and a negative value indicates that the sweep is defined in a counter-clockwise direction. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


