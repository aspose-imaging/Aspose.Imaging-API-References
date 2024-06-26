---
title: EmfPlusDrawClosedCurve.PointData
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusDrawClosedCurve property. Gets or sets the point data An array of Count points that specify the endpoints of the lines that define the spline. In a closed cardinal spline the curve continues through the last point in the PointData array and connects with the first point in the array. The type of data in this array is specified by the Flags field as follows Data Type Meaning EmfPlusPointR object section 2.2.2.37 If the P flag is set in the Flags the points specify relative locations. EmfPlusPointF object section 2.2.2.36 If the P and C bits are set in the Flags field the points specify absolute locations. EmfPlusPoint object section 2.2.2.35 If the P bit is clear and the C bit is set in the Flags field the points specify relative locations
type: docs
weight: 40
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata/
---
## EmfPlusDrawClosedCurve.PointData property

Gets or sets the point data An array of Count points that specify the endpoints of the lines that define the spline. In a closed cardinal spline, the curve continues through the last point in the PointData array and connects with the first point in the array. The type of data in this array is specified by the Flags field, as follows: Data Type Meaning EmfPlusPointR object (section 2.2.2.37) If the P flag is set in the Flags, the points specify relative locations. EmfPlusPointF object (section 2.2.2.36) If the P and C bits are set in the Flags field, the points specify absolute locations. EmfPlusPoint object (section 2.2.2.35) If the P bit is clear and the C bit is set in the Flags field, the points specify relative locations.

```csharp
public PointF[] PointData { get; set; }
```

### See Also

* struct [PointF](../../../aspose.imaging/pointf/)
* class [EmfPlusDrawClosedCurve](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawclosedcurve/)
* assembly [Aspose.Imaging](../../../)


