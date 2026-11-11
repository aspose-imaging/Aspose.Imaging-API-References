---
title: RasterCachedMultipageImage.ApplyCubeLut
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedMultipageImage method. Applies the specified CubeLut to each page of the image within the given bounds. The operation is performed in parallel across all pages to improve performance. For each page the method loads the ARGB32 pixel data for the specified rectangle applies the LUT processor inplace and then saves the modified pixel data back to the page
type: docs
weight: 180
url: /net/aspose.imaging/rastercachedmultipageimage/applycubelut/
---
## RasterCachedMultipageImage.ApplyCubeLut method

Applies the specified [`CubeLut`](../../../aspose.imaging.lut.cubelut/cubelut/) to each page of the image within the given *bounds*. The operation is performed in parallel across all pages to improve performance. For each page, the method loads the ARGB32 pixel data for the specified rectangle, applies the LUT processor in-place, and then saves the modified pixel data back to the page.

```csharp
public override void ApplyCubeLut(CubeLut cubeLut, Rectangle bounds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cubeLut | CubeLut | The cube lookup table containing the color transformation to apply. |
| bounds | Rectangle | The rectangular region (in pixel coordinates) that defines the area to which the LUT will be applied. The rectangle must be within the bounds of each page; otherwise an exception may be thrown. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *cubeLut* is `null`. |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | Thrown when an error occurs while processing one of the pages. |

## Remarks

This method does not modify pages that are not raster images. It also respects the image's synchronization and disposal state, ensuring thread‑safe execution.

### See Also

* class [CubeLut](../../../aspose.imaging.lut.cubelut/cubelut/)
* struct [Rectangle](../../rectangle/)
* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)


