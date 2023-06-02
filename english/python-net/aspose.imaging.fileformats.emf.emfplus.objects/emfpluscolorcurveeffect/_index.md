---
title: EmfPlusColorCurveEffect Class
type: docs
weight: 180
url: /python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---

The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorCurveEffect

**Assembly:**  Aspose.Imaging Version: 23.5.0

The EmfPlusColorCurveEffect type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusColorCurveEffect()|Initializes a new instance of the EmfPlusColorCurveEffect class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|curve_adjustment|Gets or sets a 32-bit unsigned integer that specifies the curve adjustment to<br/>            apply to the colors in bitmap. This value MUST be defined in the CurveAdjustments<br/>            enumeration (section 2.1.1.7).|
|curve_channel|Gets or sets a 32-bit unsigned integer that specifies the color channel to which<br/>            the curve adjustment applies. This value MUST be defined in the CurveChannel<br/>            enumeration (section 2.1.1.8).|
|adjustment_intensity|Gets or sets a 32-bit signed integer that specifies the intensity of the<br/>            curve adjustment to the color channel specified by CurveChannel. The ranges of meaningful<br/>            values for this field vary according to the CurveAdjustment value, as follows:<br/>            Exposure adjustment range:<br/>            -255 ≤ value < 0 As the value decreases, the exposure of the image SHOULD decrease.<br/>            0 A value of 0 specifies that the exposure MUST NOT change.<br/>            0 < value ≤ 255 As the value increases, the exposure of the image SHOULD increase.<br/>            Density adjustment range:<br/>            -255 ≤ value < 0<br/>            As the value decreases, the density of the image SHOULD decrease, resulting in<br/>            a darker image.<br/>            0 A value of 0 specifies that the density MUST NOT change.<br/>            0 < value ≤ 255<br/>            As the value increases, the density of the image SHOULD increase.<br/>            Contrast adjustment range:<br/>            -100 ≤ value < 0 As the value decreases, the contrast of the image SHOULD decrease.<br/>            0 A value of 0 specifies that the contrast MUST NOT change.<br/>            0 < value ≤ 100 As the value increases, the contrast of the image SHOULD increase.<br/>            Highlight adjustment range:<br/>            -100 ≤ value < 0 As the value decreases, the light areas of the image SHOULD appear darker.<br/>            0 A value of 0 specifies that the highlight MUST NOT change.<br/>            0 < value ≤ 100 As the value increases, the light areas of the image SHOULD appear lighter.<br/>            Shadow adjustment range:<br/>            -100 ≤ value < 0 As the value decreases, the dark areas of the image SHOULD appear darker.<br/>            0 A value of 0 specifies that the shadow MUST NOT change.<br/>            0 < value ≤ 100 As the value increases, the dark areas of the image SHOULD appear lighter.<br/>            White saturation adjustment range:<br/>            0 — 255 As the value increases, the upper limit of the range of color channel intensities increases.<br/>            Black saturation adjustment range:<br/>            0 — 255 As the value increases, the lower limit of the range of color channel intensities increases.|
