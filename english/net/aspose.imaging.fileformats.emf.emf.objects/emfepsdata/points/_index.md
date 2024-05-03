---
title: EmfEpsData.Points
second_title: Aspose.Imaging for .NET API Reference
description: EmfEpsData property. Gets or sets an array of three Point28_4 objects section 2.2.23 that defines the coordinates of the output parallelogram using 28.4 bit FIX notation
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/points/
---
## EmfEpsData.Points property

Gets or sets an array of three Point28_4 objects (section 2.2.23) that defines the coordinates of the output parallelogram using 28.4 bit FIX notation

```csharp
public EmfPoint28To4[] Points { get; set; }
```

## Remarks

The upper-left corner of the parallelogram is the first point in this array, the upper-right corner is the second point, and the lower-left corner is the third point. The lower-right corner of the parallelogram is computed from the first three points (A, B, and C) by treating them as vectors.

### See Also

* class [EmfPoint28To4](../../emfpoint28to4/)
* class [EmfEpsData](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../emfepsdata/)
* assembly [Aspose.Imaging](../../../)


