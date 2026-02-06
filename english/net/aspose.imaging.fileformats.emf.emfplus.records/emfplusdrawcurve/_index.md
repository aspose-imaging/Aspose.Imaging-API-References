---
title: Class EmfPlusDrawCurve
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawCurve class. The EmfPlusDrawCurve record specifies drawing a cardinal spline NOTE ObjectID 1 byte The index of an EmfPlusPen object section 2.2.1.7 in the EMF Object Table to draw the curve. The value MUST be zero to 63 inclusive
type: docs
weight: 6050
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
## EmfPlusDrawCurve class

The EmfPlusDrawCurve record specifies drawing a cardinal spline NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

```csharp
public sealed class EmfPlusDrawCurve : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusDrawCurve](emfplusdrawcurve/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusDrawCurve` class. |

## Properties

| Name | Description |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/compressed/) { get; set; } | Gets or sets a value indicating whether this [`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve/) is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [NumSegments](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/numsegments/) { get; set; } | Gets or sets the segments count A 32-bit unsigned integer that specifies the number of line segments making up the spline. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/objectid/) { get; set; } | Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/pointdata/) { get; set; } | Gets or sets an array of either 32-bit signed integers or 32-bit floating-point numbers of Count length that defines coordinate values of the endpoints of the lines to be stroked. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/tension/) { get; set; } | Gets or sets the tension A 32-bit floating point number that specifies how tightly the spline bends as it passes through the points. A value of 0 specifies that the spline is a sequence of straight lines. As the value increases, the curve becomes more rounded. For more information, see [SPLINE77] and [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


