---
title: RasterCachedMultipageImage.NormalizeAngle
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedMultipageImage method. Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses GetSkewAngle and Rotate methods
type: docs
weight: 290
url: /net/aspose.imaging/rastercachedmultipageimage/normalizeangle/
---
## RasterCachedMultipageImage.NormalizeAngle method

Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](../../rasterimage/getskewangle/) and [`Rotate`](../rotate/) methods.

```csharp
public override void NormalizeAngle(bool resizeProportionally, Color backgroundColor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resizeProportionally | Boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| backgroundColor | Color | Color of the background. |

### See Also

* struct [Color](../../color/)
* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)


