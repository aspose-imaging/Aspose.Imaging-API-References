---
title: NormalizeAngle
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 300
url: /net/aspose.imaging.fileformats.tiff/tiffimage/normalizeangle/
---
## TiffImage.NormalizeAngle method

Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](../../../aspose.imaging/rasterimage/getskewangle) and [`Rotate`](../rotate) methods.

```csharp
public override void NormalizeAngle(bool resizeProportionally, Color backgroundColor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resizeProportionally | Boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| backgroundColor | Color | Color of the background. |

### See Also

* struct [Color](../../../aspose.imaging/color)
* class [TiffImage](../../tiffimage)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
