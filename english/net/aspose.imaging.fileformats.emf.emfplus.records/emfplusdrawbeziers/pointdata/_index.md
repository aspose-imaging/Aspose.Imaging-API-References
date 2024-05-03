---
title: EmfPlusDrawBeziers.PointData
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusDrawBeziers property. Gets or sets the point data An array of Count points that specify the starting ending and control points of the Bezier curves. The ending coordinate of one Bezier curve is the starting coordinate of the next. The control points are used for producing the Bezier effect. The type of data in this array is specified by the Flags field as follows Data Type Meaning EmfPlusPointR object section 2.2.2.37 If the P flag is set in the Flags the points specify relative locations. EmfPlusPointF object section 2.2.2.36 If the P and C bits are clear in the Flags field the points specify absolute locations. EmfPlusPoint object section 2.2.2.35 If the P bit is clear and the C bit is set in the Flags field the points specify relative locations. A Bezier curve does not pass through its control points. The control points act as
type: docs
weight: 40
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/pointdata/
---
## EmfPlusDrawBeziers.PointData property

Gets or sets the point data An array of Count points that specify the starting, ending, and control points of the Bezier curves. The ending coordinate of one Bezier curve is the starting coordinate of the next. The control points are used for producing the Bezier effect. The type of data in this array is specified by the Flags field, as follows: Data Type Meaning EmfPlusPointR object (section 2.2.2.37) If the P flag is set in the Flags, the points specify relative locations. EmfPlusPointF object (section 2.2.2.36) If the P and C bits are clear in the Flags field, the points specify absolute locations. EmfPlusPoint object (section 2.2.2.35) If the P bit is clear and the C bit is set in the Flags field, the points specify relative locations. A Bezier curve does not pass through its control points. The control points act as

```csharp
public PointF[] PointData { get; set; }
```

### See Also

* struct [PointF](../../../aspose.imaging/pointf/)
* class [EmfPlusDrawBeziers](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawbeziers/)
* assembly [Aspose.Imaging](../../../)


