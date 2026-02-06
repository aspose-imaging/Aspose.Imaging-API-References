---
title: Class EmfPlusPathPointTypeRle
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusPathPointTypeRle class. The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B1RunCount  PointType  B 1 bit If set the path points are on a Bezier curve. If clear the path points are on a graphics line. RunCount 6 bits The run count which is the number of path points to be associated with the type in the PointType field. PointType 1 byte An EmfPlusPathPointType object section 2.2.2.31 that specifies the type to associate with the path points
type: docs
weight: 5770
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
## EmfPlusPathPointTypeRle class

The EmfPlusPathPointTypeRle object specifies type values associated with points on a graphics path using RLE compression. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B&#x7C;1&#x7C;RunCount &#x7C; PointType &#x7C; B (1 bit): If set, the path points are on a Bezier curve. If clear, the path points are on a graphics line. RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field. PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points.

```csharp
public sealed class EmfPlusPathPointTypeRle : EmfPlusBasePointType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusPathPointTypeRle](emfpluspathpointtyperle/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Bezier](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/bezier/) { get; set; } | Gets or sets a value indicating whether this `EmfPlusPathPointTypeRle` is bezier. If set, the path points are on a Bezier curve. If clear, the path points are on a graphics line. |
| [Data](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/data/) { get; set; } | Gets or sets the data. |
| [PointType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/pointtype/) { get; set; } | Gets or sets the type of the point. PointType (1 byte): An EmfPlusPathPointType object (section 2.2.2.31) that specifies the type to associate with the path points. |
| [RunCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/runcount/) { get; set; } | Gets or sets the run count. RunCount (6 bits): The run count, which is the number of path points to be associated with the type in the PointType field |

### See Also

* class [EmfPlusBasePointType](../emfplusbasepointtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


