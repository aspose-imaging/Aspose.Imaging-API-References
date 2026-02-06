---
title: Class EmfPlusColorCurveEffect
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusColorCurveEffect class. The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image
type: docs
weight: 5420
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---
## EmfPlusColorCurveEffect class

The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.

```csharp
public sealed class EmfPlusColorCurveEffect : EmfPlusImageEffectsObjectType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusColorCurveEffect](emfpluscolorcurveeffect/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AdjustmentIntensity](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/adjustmentintensity/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the intensity of the curve adjustment to the color channel specified by CurveChannel. The ranges of meaningful values for this field vary according to the CurveAdjustment value, as follows: Exposure adjustment range: -255 ≤ value &lt; 0 As the value decreases, the exposure of the image SHOULD decrease. 0 A value of 0 specifies that the exposure MUST NOT change. 0 &lt; value ≤ 255 As the value increases, the exposure of the image SHOULD increase. Density adjustment range: -255 ≤ value &lt; 0 As the value decreases, the density of the image SHOULD decrease, resulting in a darker image. 0 A value of 0 specifies that the density MUST NOT change. 0 &lt; value ≤ 255 As the value increases, the density of the image SHOULD increase. Contrast adjustment range: -100 ≤ value &lt; 0 As the value decreases, the contrast of the image SHOULD decrease. 0 A value of 0 specifies that the contrast MUST NOT change. 0 &lt; value ≤ 100 As the value increases, the contrast of the image SHOULD increase. Highlight adjustment range: -100 ≤ value &lt; 0 As the value decreases, the light areas of the image SHOULD appear darker. 0 A value of 0 specifies that the highlight MUST NOT change. 0 &lt; value ≤ 100 As the value increases, the light areas of the image SHOULD appear lighter. Shadow adjustment range: -100 ≤ value &lt; 0 As the value decreases, the dark areas of the image SHOULD appear darker. 0 A value of 0 specifies that the shadow MUST NOT change. 0 &lt; value ≤ 100 As the value increases, the dark areas of the image SHOULD appear lighter. White saturation adjustment range: 0 — 255 As the value increases, the upper limit of the range of color channel intensities increases. Black saturation adjustment range: 0 — 255 As the value increases, the lower limit of the range of color channel intensities increases. |
| [CurveAdjustment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/curveadjustment/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the curve adjustment to apply to the colors in bitmap. This value MUST be defined in the CurveAdjustments enumeration (section 2.1.1.7). |
| [CurveChannel](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/curvechannel/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the color channel to which the curve adjustment applies. This value MUST be defined in the CurveChannel enumeration (section 2.1.1.8). |

### See Also

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


