---
title: Class EmfPlusFillPolygon
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusFillPolygon class. The EmfPlusFillPolygon record specifies filling the interior of a polygon
type: docs
weight: 6220
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
## EmfPlusFillPolygon class

The EmfPlusFillPolygon record specifies filling the interior of a polygon.

```csharp
public sealed class EmfPlusFillPolygon : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusFillPolygon](emfplusfillpolygon/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusFillPolygon` class. |

## Properties

| Name | Description |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/brushid/) { get; set; } | Gets or sets the brush identifier A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscolor/) { get; set; } | Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table. |
| [IsCompressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscompressed/) { get; set; } | Gets or sets a value indicating whether this instance is compressed. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates |
| [IsRelative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/isrelative/) { get; set; } | Gets or sets a value indicating whether this instance is relative. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/pointdata/) { get; set; } | Gets or sets the point data An array of Count points that define the vertices of the polygon. The first two points in the array specify the first side of the polygon. Each additional point specifies a new side, the vertices of which include the point and the previous point. If the last point and the first point do not coincide, they specify the last side of the polygon. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


