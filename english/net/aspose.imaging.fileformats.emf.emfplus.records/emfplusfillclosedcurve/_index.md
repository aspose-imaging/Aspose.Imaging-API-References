---
title: Class EmfPlusFillClosedCurve
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillClosedCurve class. The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline
type: docs
weight: 6180
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
## EmfPlusFillClosedCurve class

The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline

```csharp
public sealed class EmfPlusFillClosedCurve : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusFillClosedCurve](emfplusfillclosedcurve/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusFillClosedCurve` class. |

## Properties

| Name | Description |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/brushid/) { get; set; } | Gets or sets the brush identifier A 32-bit unsigned integer that specifies the EmfPlusBrush, the content of which is determined by the S bit in the Flags field. This brush is used to fill the interior of the closed cardinal spline. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/compressed/) { get; set; } | Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. ---------------------- A "winding" fill operation fills areas according to the "even-odd parity" rule. According to this rule, a test point can be determined to be inside or outside a closed curve as follows: Draw a line from the test point to a point that is distant from the curve. If that line crosses the curve an odd number of times, the test point is inside the curve; otherwise, the test point is outside the curve. --------------------- An "alternate" fill operation fills areas according to the "non-zero" rule. According to this rule, a test point can be determined to be inside or outside a closed curve as follows: Draw a line from a test point to a point that is distant from the curve. Count the number of times the curve crosses the test line from left to right, and count the number of times the curve crosses the test line from right to left. If those two numbers are the same, the test point is outside the curve; otherwise, the test point is inside the curve. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/iscolor/) { get; set; } | Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/pointdata/) { get; set; } | Gets or sets the point data An array of Count points that specify the endpoints of the lines that define the spline. In a closed cardinal spline, the curve continues through the last point in the PointData array and connects with the first point in the array |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/relative/) { get; set; } | Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the C flag (above) is undefined and MUST be ignored. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/tension/) { get; set; } | Gets or sets the tension A 32-bit floating point value that specifies how tightly the spline bends as it passes through the points. A value of 0.0 specifies that the spline is a sequence of straight lines. As the value increases, the curve becomes more rounded. For more information, see [SPLINE77] and [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |
| [Winding](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/winding/) { get; set; } | Gets or sets a value indicating whether this `EmfPlusFillClosedCurve` is winding. This bit indicates how to perform the fill operation. If set, the fill is a "winding" fill. If clear, the fill is an "alternate" fill. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


