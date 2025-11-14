---
title: EmfPlusInterpolationMode Enumeration
type: docs
weight: 200
url: /python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---

The InterpolationMode enumeration defines ways to perform scaling, including stretching and shrinking.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusInterpolationMode

## **Members**
| **Member name** | **Description** |
| :- | :- |
| INTERPOLATION_MODE_BICUBIC | Specifies bicubic interpolation, which uses the closest 4x4 neighborhood of known pixels surrounding the interpolated pixel. The weighted average of these 16 known pixel values determines the value to assign to the interpolated pixel. Because the known pixels are likely to be at varying distances from the interpolated pixel, closer pixels are given a higher weight in the calculation. The result is smoother looking than InterpolationModeBilinear. |
| INTERPOLATION_MODE_BILINEAR | Specifies bilinear interpolation, which uses the closest 2x2 neighborhood of known pixels surrounding the interpolated pixel. The weighted average of these 4 known pixel values determines the value to assign to the interpolated pixel. The result is smoother looking than InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_DEFAULT | Specifies the default interpolation mode, which is defined as InterpolationModeBilinear. |
| INTERPOLATION_MODE_HIGH_QUALITY | Specifies a high-quality interpolation mode, which is defined as InterpolationModeHighQualityBicubic. |
| INTERPOLATION_MODE_HIGH_QUALITY_BICUBIC | Specifies bicubic interpolation with prefiltering, which produces the highest-quality result among these options. |
| INTERPOLATION_MODE_HIGH_QUALITY_BILINEAR | Specifies bilinear interpolation with prefiltering. |
| INTERPOLATION_MODE_LOW_QUALITY | Specifies a low-quality interpolation mode, which is defined as InterpolationModeNearestNeighbor. |
| INTERPOLATION_MODE_NEAREST_NEIGHBOR | Specifies nearest-neighbor interpolation, which uses only the value of the pixel that is closest to the interpolated pixel. This mode simply duplicates or removes pixels, producing the lowest-quality result among these options. |
