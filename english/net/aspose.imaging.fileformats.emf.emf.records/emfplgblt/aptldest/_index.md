---
title: EmfPlgBlt.AptlDest
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlgBlt property. Gets or sets an array of three WMF PointL objects MSWMF section 2.2.2.15 that specifies three corners a parallelogram destination area for the block transfer. The upperleft corner of the source rectangle is mapped to the first point in this array the upperright corner to the second point and the lowerleft corner to the third point. The lowerright corner of the source rectangle is mapped to the implicit fourth point in the parallelogram which is computed from the first three points A B and C by treating them as vectors. D  B  C A
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/aptldest/
---
## EmfPlgBlt.AptlDest property

Gets or sets an array of three WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies three corners a parallelogram destination area for the block transfer. The upper-left corner of the source rectangle is mapped to the first point in this array, the upper-right corner to the second point, and the lower-left corner to the third point. The lower-right corner of the source rectangle is mapped to the implicit fourth point in the parallelogram, which is computed from the first three points (A, B, and C) by treating them as vectors. D = B + C A

```csharp
public Point[] AptlDest { get; set; }
```

### See Also

* struct [Point](../../../aspose.imaging/point/)
* class [EmfPlgBlt](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../emfplgblt/)
* assembly [Aspose.Imaging](../../../)


