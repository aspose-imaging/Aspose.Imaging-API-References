---
title: Class EmfPlusDrawClosedCurve
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawClosedCurve class. The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline
type: docs
weight: 6040
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
## EmfPlusDrawClosedCurve class

The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline

```csharp
public sealed class EmfPlusDrawClosedCurve : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusDrawClosedCurve](emfplusdrawclosedcurve/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusDrawClosedCurve` class. RecordType - A 16-bit unsigned integer that identifies this record type as EmfPlusDrawClosedCurve from the RecordType enumeration (section 2.1.1.1). The value MUST be 0x4017. |

## Properties

| Name | Description |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/compressed/) { get; set; } | Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/objectid/) { get; set; } | Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the closed curve. The value MUST be zero to 63, inclusive. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata/) { get; set; } | Gets or sets the point data An array of Count points that specify the endpoints of the lines that define the spline. In a closed cardinal spline, the curve continues through the last point in the PointData array and connects with the first point in the array. The type of data in this array is specified by the Flags field, as follows: Data Type Meaning EmfPlusPointR object (section 2.2.2.37) If the P flag is set in the Flags, the points specify relative locations. EmfPlusPointF object (section 2.2.2.36) If the P and C bits are set in the Flags field, the points specify absolute locations. EmfPlusPoint object (section 2.2.2.35) If the P bit is clear and the C bit is set in the Flags field, the points specify relative locations. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/relative/) { get; set; } | Gets or sets a value indicating whether this `EmfPlusDrawClosedCurve` is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the Compressed flag (above) is undefined and MUST be ignored |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/tension/) { get; set; } | Gets or sets the tension A 32-bit floating point number that specifies how tightly the spline bends as it passes through the points. A value of 0 specifies that the spline is a sequence of straight lines. As the value increases, the curve becomes more rounded. For more information, see [SPLINE77] and [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


