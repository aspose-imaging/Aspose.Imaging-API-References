---
title: Class EmfPlusDrawBeziers
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawBeziers class. The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. The order for Bezier data points is the start point control point 1 control point 2 and end point. For more information see MSDNDrawBeziers
type: docs
weight: 6030
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
## EmfPlusDrawBeziers class

The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. The order for Bezier data points is the start point, control point 1, control point 2 and end point. For more information see [MSDN-DrawBeziers].

```csharp
public sealed class EmfPlusDrawBeziers : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusDrawBeziers](emfplusdrawbeziers/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusDrawBeziers` class. |

## Properties

| Name | Description |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/compressed/) { get; set; } | Gets or sets a value indicating whether the PointData is compressed. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/objectid/) { get; set; } | Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the Bezier curves. The value MUST be zero to 63, inclusive. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/pointdata/) { get; set; } | Gets or sets the point data An array of Count points that specify the starting, ending, and control points of the Bezier curves. The ending coordinate of one Bezier curve is the starting coordinate of the next. The control points are used for producing the Bezier effect. The type of data in this array is specified by the Flags field, as follows: Data Type Meaning EmfPlusPointR object (section 2.2.2.37) If the P flag is set in the Flags, the points specify relative locations. EmfPlusPointF object (section 2.2.2.36) If the P and C bits are clear in the Flags field, the points specify absolute locations. EmfPlusPoint object (section 2.2.2.35) If the P bit is clear and the C bit is set in the Flags field, the points specify relative locations. A Bezier curve does not pass through its control points. The control points act as |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/relative/) { get; set; } | Gets or sets a value indicating whether the PointData is relative. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the C flag (above) is undefined and MUST be ignored. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


