---
title: Enum EmfPlusInterpolationMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusInterpolationMode enum. The InterpolationMode enumeration defines ways to perform scaling including stretching and shrinking
type: docs
weight: 4990
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
## EmfPlusInterpolationMode enumeration

The InterpolationMode enumeration defines ways to perform scaling, including stretching and shrinking.

```csharp
public enum EmfPlusInterpolationMode : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| InterpolationModeDefault | `0` | Specifies the default interpolation mode, which is defined as InterpolationModeBilinear. |
| InterpolationModeLowQuality | `1` | Specifies a low-quality interpolation mode, which is defined as InterpolationModeNearestNeighbor. |
| InterpolationModeHighQuality | `2` | Specifies a high-quality interpolation mode, which is defined as InterpolationModeHighQualityBicubic. |
| InterpolationModeBilinear | `3` | Specifies bilinear interpolation, which uses the closest 2x2 neighborhood of known pixels surrounding the interpolated pixel. The weighted average of these 4 known pixel values determines the value to assign to the interpolated pixel. The result is smoother looking than InterpolationModeNearestNeighbor. |
| InterpolationModeBicubic | `4` | Specifies bicubic interpolation, which uses the closest 4x4 neighborhood of known pixels surrounding the interpolated pixel. The weighted average of these 16 known pixel values determines the value to assign to the interpolated pixel. Because the known pixels are likely to be at varying distances from the interpolated pixel, closer pixels are given a higher weight in the calculation. The result is smoother looking than InterpolationModeBilinear. |
| InterpolationModeNearestNeighbor | `5` | Specifies nearest-neighbor interpolation, which uses only the value of the pixel that is closest to the interpolated pixel. This mode simply duplicates or removes pixels, producing the lowest-quality result among these options. |
| InterpolationModeHighQualityBilinear | `6` | Specifies bilinear interpolation with prefiltering. |
| InterpolationModeHighQualityBicubic | `7` | Specifies bicubic interpolation with prefiltering, which produces the highest-quality result among these options. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


