---
title: EmfPlusDrawLines.Relative
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusDrawLines property. Gets or sets a value indicating whether this EmfPlusDrawClosedCurve is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData a previous location at coordinates 00 is assumed. If clear PointData specifies absolute locations according to the C flag. Note If this flag is set the Compressed flag above is undefined and MUST be ignored
type: docs
weight: 60
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/relative/
---
## EmfPlusDrawLines.Relative property

Gets or sets a value indicating whether this [`EmfPlusDrawClosedCurve`](../../emfplusdrawclosedcurve/) is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the Compressed flag (above) is undefined and MUST be ignored

```csharp
public bool Relative { get; set; }
```

### Property Value

`true` if relative; otherwise, `false`.

### See Also

* class [EmfPlusDrawLines](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawlines/)
* assembly [Aspose.Imaging](../../../)


