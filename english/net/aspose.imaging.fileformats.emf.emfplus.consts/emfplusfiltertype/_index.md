---
title: Enum EmfPlusFilterType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusFilterType enum. The FilterType enumeration defines types of filtering algorithms that can be used for text and graphics quality enhancement and image rendering
type: docs
weight: 4920
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
## EmfPlusFilterType enumeration

The FilterType enumeration defines types of filtering algorithms that can be used for text and graphics quality enhancement and image rendering.

```csharp
public enum EmfPlusFilterType : byte
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| FilterTypeNone | `0` | Specifies that filtering is not performed. |
| FilterTypePoint | `1` | Specifies that each destination pixel is computed by sampling the nearest pixel from the source image. |
| FilterTypeLinear | `2` | Specifies that linear interpolation is performed using the weighted average of a 2x2 area of pixels surrounding the source pixel. |
| FilterTypeTriangle | `3` | Specifies that each pixel in the source image contributes equally to the destination image. This is the slowest of filtering algorithms. |
| FilterTypeBox | `4` | Specifies a box filter algorithm, in which each destination pixel is computed by averaging a rectangle of source pixels. This algorithm is useful only when reducing the size of an image. |
| FilterTypePyramidalQuad | `6` | Specifies that a 4-sample tent filter is used. |
| FilterTypeGaussianQuad | `7` | Specifies that a 4-sample Gaussian filter is used, which creates a blur effect on an image. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


