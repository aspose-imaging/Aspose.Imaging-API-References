---
title: Enum EmfPlusCurveAdjustments
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusCurveAdjustments enum. The CurveAdjustments enumeration defines adjustments that can be applied to the color curve of an image
type: docs
weight: 4860
url: /net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/
---
## EmfPlusCurveAdjustments enumeration

The CurveAdjustments enumeration defines adjustments that can be applied to the color curve of an image.

```csharp
public enum EmfPlusCurveAdjustments
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| AdjustExposure | `0` | Specifies the simulation of increasing or decreasing the exposure of an image. |
| AdjustDensity | `1` | Specifies the simulation of increasing or decreasing the density of an image. |
| AdjustContrast | `2` | Specifies an increase or decrease of the contrast of an image. |
| AdjustHighlight | `3` | Specifies an increase or decrease of the value of a color channel of an image, if that channel already has a value that is above half intensity. This adjustment can be used to increase definition in the light areas of an image without affecting the dark areas. |
| AdjustShadow | `4` | Specifies an increase or decrease of the value of a color channel of an image, if that channel already has a value that is below half intensity. This adjustment can be used to increase definition in the dark areas of an image without affecting the light areas. |
| AdjustMidtone | `5` | Specifies an adjustment that lightens or darkens an image. Color channel values in the middle of the intensity range are altered more than color channel values near the minimum or maximum extremes of intensity. This adjustment can be used to lighten or darken an image without losing the contrast between the darkest and lightest parts of the image. |
| AdjustWhiteSaturation | `6` | Specifies an adjustment to the white saturation of an image, defined as the maximum value in the range of intensities for a given color channel, whose range is typically 0 to 255. |
| AdjustBlackSaturation | `7` | Specifies an adjustment to the black saturation of an image, which is the minimum value in the range of intensities for a given color channel, which is typically 0 to 255. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


