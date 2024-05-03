---
title: EmfPlusColorCurveEffect.AdjustmentIntensity
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusColorCurveEffect property. Gets or sets a 32bit signed integer that specifies the intensity of the curve adjustment to the color channel specified by CurveChannel. The ranges of meaningful values for this field vary according to the CurveAdjustment value as follows Exposure adjustment range 255  value  0 As the value decreases the exposure of the image SHOULD decrease. 0 A value of 0 specifies that the exposure MUST NOT change. 0  value  255 As the value increases the exposure of the image SHOULD increase. Density adjustment range 255  value  0 As the value decreases the density of the image SHOULD decrease resulting in a darker image. 0 A value of 0 specifies that the density MUST NOT change. 0  value  255 As the value increases the density of the image SHOULD increase. Contrast adjustment range 100  value  0 As the value decreases the contrast of the image SHOULD decrease. 0 A value of 0 specifies that the contrast MUST NOT change. 0  value  100 As the value increases the contrast of the image SHOULD increase. Highlight adjustment range 100  value  0 As the value decreases the light areas of the image SHOULD appear darker. 0 A value of 0 specifies that the highlight MUST NOT change. 0  value  100 As the value increases the light areas of the image SHOULD appear lighter. Shadow adjustment range 100  value  0 As the value decreases the dark areas of the image SHOULD appear darker. 0 A value of 0 specifies that the shadow MUST NOT change. 0  value  100 As the value increases the dark areas of the image SHOULD appear lighter. White saturation adjustment range 0  255 As the value increases the upper limit of the range of color channel intensities increases. Black saturation adjustment range 0  255 As the value increases the lower limit of the range of color channel intensities increases
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/adjustmentintensity/
---
## EmfPlusColorCurveEffect.AdjustmentIntensity property

Gets or sets a 32-bit signed integer that specifies the intensity of the curve adjustment to the color channel specified by CurveChannel. The ranges of meaningful values for this field vary according to the CurveAdjustment value, as follows: Exposure adjustment range: -255 ≤ value &lt; 0 As the value decreases, the exposure of the image SHOULD decrease. 0 A value of 0 specifies that the exposure MUST NOT change. 0 &lt; value ≤ 255 As the value increases, the exposure of the image SHOULD increase. Density adjustment range: -255 ≤ value &lt; 0 As the value decreases, the density of the image SHOULD decrease, resulting in a darker image. 0 A value of 0 specifies that the density MUST NOT change. 0 &lt; value ≤ 255 As the value increases, the density of the image SHOULD increase. Contrast adjustment range: -100 ≤ value &lt; 0 As the value decreases, the contrast of the image SHOULD decrease. 0 A value of 0 specifies that the contrast MUST NOT change. 0 &lt; value ≤ 100 As the value increases, the contrast of the image SHOULD increase. Highlight adjustment range: -100 ≤ value &lt; 0 As the value decreases, the light areas of the image SHOULD appear darker. 0 A value of 0 specifies that the highlight MUST NOT change. 0 &lt; value ≤ 100 As the value increases, the light areas of the image SHOULD appear lighter. Shadow adjustment range: -100 ≤ value &lt; 0 As the value decreases, the dark areas of the image SHOULD appear darker. 0 A value of 0 specifies that the shadow MUST NOT change. 0 &lt; value ≤ 100 As the value increases, the dark areas of the image SHOULD appear lighter. White saturation adjustment range: 0 — 255 As the value increases, the upper limit of the range of color channel intensities increases. Black saturation adjustment range: 0 — 255 As the value increases, the lower limit of the range of color channel intensities increases.

```csharp
public int AdjustmentIntensity { get; set; }
```

### See Also

* class [EmfPlusColorCurveEffect](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfpluscolorcurveeffect/)
* assembly [Aspose.Imaging](../../../)


