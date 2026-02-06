---
title: Class EmfPlusDrawLines
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawLines class. The EmfPlusDrawlLines record specifies drawing a series of connected lines
type: docs
weight: 6100
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
## EmfPlusDrawLines class

The EmfPlusDrawlLines record specifies drawing a series of connected lines

```csharp
public sealed class EmfPlusDrawLines : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusDrawLines](emfplusdrawlines/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusDrawLines` class. |

## Properties

| Name | Description |
| --- | --- |
| [ClosedShape](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/closedshape/) { get; set; } | Gets or sets a value indicating whether [closed shape]. |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/compressed/) { get; set; } | Gets or sets a value indicating whether this [`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve/) is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates Note If the Relative flag (below) is set, this flag is undefined and MUST be ignored |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/objectid/) { get; set; } | Gets or sets the object identifier. The index of an EmfPlusPen object (section 2.2.1.7) in the EMF+ Object Table to draw the lines. The value MUST be zero to 63, inclusive. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/pointdata/) { get; set; } | Gets or sets the point data An array of Count points that specify the starting and ending points of the lines to be drawn. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/relative/) { get; set; } | Gets or sets a value indicating whether this [`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve/) is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the Compressed flag (above) is undefined and MUST be ignored |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


