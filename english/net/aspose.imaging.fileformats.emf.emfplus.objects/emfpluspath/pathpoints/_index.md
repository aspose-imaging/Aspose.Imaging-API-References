---
title: EmfPlusPath.PathPoints
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusPath property. Gets or sets array of path points An array of PathPointCount points that specify the path. The type of objects in this array are specified by the PathPointFlags field as follows If the P flag is set the points are relative locations that are specified by EmfPlusPointR objects section 2.2.2.37. If the P flag is clear and the C flag is set the points are absolute locations that are specified by EmfPlusPoint objects section 2.2.2.35. If the P flag is clear and the C flag is clear the points are absolute locations that are specified by EmfPlusPointF objects section 2.2.2.36
type: docs
weight: 30
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspath/pathpoints/
---
## EmfPlusPath.PathPoints property

Gets or sets array of path points An array of PathPointCount points that specify the path. The type of objects in this array are specified by the PathPointFlags field, as follows: If the P flag is set, the points are relative locations that are specified by EmfPlusPointR objects (section 2.2.2.37). If the P flag is clear and the C flag is set, the points are absolute locations that are specified by EmfPlusPoint objects (section 2.2.2.35). If the P flag is clear and the C flag is clear, the points are absolute locations that are specified by EmfPlusPointF objects (section 2.2.2.36).

```csharp
public PointF[] PathPoints { get; set; }
```

### See Also

* struct [PointF](../../../aspose.imaging/pointf/)
* class [EmfPlusPath](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfpluspath/)
* assembly [Aspose.Imaging](../../../)


