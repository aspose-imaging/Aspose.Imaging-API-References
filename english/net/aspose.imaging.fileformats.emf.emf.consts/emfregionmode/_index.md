---
title: Enum EmfRegionMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfRegionMode enum. The RegionMode enumeration defines values that are used with EMR_SELECTCLIPPATH and EMR_EXTSELECTCLIPRGN specifying the current path or a new region that is being combined with the current clip region
type: docs
weight: 2920
url: /net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
## EmfRegionMode enumeration

The RegionMode enumeration defines values that are used with EMR_SELECTCLIPPATH and EMR_EXTSELECTCLIPRGN, specifying the current path or a new region that is being combined with the current clip region.

```csharp
public enum EmfRegionMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| RGN_AND | `1` | The new clipping region includes the intersection (overlapping areas) of the current clipping region and the current path (or new region). |
| RGN_OR | `2` | The new clipping region includes the union (combined areas) of the current clipping region and the current path (or new region). |
| RGN_XOR | `3` | The new clipping region includes the union of the current clipping region and the current path (or new region) but without the overlapping areas |
| RGN_DIFF | `4` | The new clipping region includes the areas of the current clipping region with those of the current path (or new region) excluded. |
| RGN_COPY | `5` | The new clipping region is the current path (or the new region). |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


