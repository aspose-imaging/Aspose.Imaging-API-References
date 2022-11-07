---
title: EmfPlusCurveAdjustments
second_title: Aspose.Imaging for Java API Reference
description: The CurveAdjustments enumeration defines adjustments that can be applied to the color curve of an image.
type: docs
weight: 16
url: /java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCurveAdjustments extends System.Enum
```

The CurveAdjustments enumeration defines adjustments that can be applied to the color curve of an image.
## Fields

| Field | Description |
| --- | --- |
| [AdjustExposure](#AdjustExposure) | Specifies the simulation of increasing or decreasing the exposure of an image. |
| [AdjustDensity](#AdjustDensity) | Specifies the simulation of increasing or decreasing the density of an image. |
| [AdjustContrast](#AdjustContrast) | Specifies an increase or decrease of the contrast of an image. |
| [AdjustHighlight](#AdjustHighlight) | Specifies an increase or decrease of the value of a color channel of an image, if that channel already has a value that is above half intensity. |
| [AdjustShadow](#AdjustShadow) | Specifies an increase or decrease of the value of a color channel of an image, if that channel already has a value that is below half intensity. |
| [AdjustMidtone](#AdjustMidtone) | Specifies an adjustment that lightens or darkens an image. |
| [AdjustWhiteSaturation](#AdjustWhiteSaturation) | Specifies an adjustment to the white saturation of an image, defined as the maximum value in the range of intensities for a given color channel, whose range is typically 0 to 255. |
| [AdjustBlackSaturation](#AdjustBlackSaturation) | Specifies an adjustment to the black saturation of an image, which is the minimum value in the range of intensities for a given color channel, which is typically 0 to 255. |
### AdjustExposure {#AdjustExposure}
```
public static final int AdjustExposure
```


Specifies the simulation of increasing or decreasing the exposure of an image.

### AdjustDensity {#AdjustDensity}
```
public static final int AdjustDensity
```


Specifies the simulation of increasing or decreasing the density of an image.

### AdjustContrast {#AdjustContrast}
```
public static final int AdjustContrast
```


Specifies an increase or decrease of the contrast of an image.

### AdjustHighlight {#AdjustHighlight}
```
public static final int AdjustHighlight
```


Specifies an increase or decrease of the value of a color channel of an image, if that channel already has a value that is above half intensity. This adjustment can be used to increase definition in the light areas of an image without affecting the dark areas.

### AdjustShadow {#AdjustShadow}
```
public static final int AdjustShadow
```


Specifies an increase or decrease of the value of a color channel of an image, if that channel already has a value that is below half intensity. This adjustment can be used to increase definition in the dark areas of an image without affecting the light areas.

### AdjustMidtone {#AdjustMidtone}
```
public static final int AdjustMidtone
```


Specifies an adjustment that lightens or darkens an image. Color channel values in the middle of the intensity range are altered more than color channel values near the minimum or maximum extremes of intensity. This adjustment can be used to lighten or darken an image without losing the contrast between the darkest and lightest parts of the image.

### AdjustWhiteSaturation {#AdjustWhiteSaturation}
```
public static final int AdjustWhiteSaturation
```


Specifies an adjustment to the white saturation of an image, defined as the maximum value in the range of intensities for a given color channel, whose range is typically 0 to 255.

--------------------

For example, a white saturation adjustment value of 240 specifies that color channel values in the range 0 to 240 are adjusted so that they spread out over the range 0 to 255, with color channel values greater than 240 set to 255.

### AdjustBlackSaturation {#AdjustBlackSaturation}
```
public static final int AdjustBlackSaturation
```


Specifies an adjustment to the black saturation of an image, which is the minimum value in the range of intensities for a given color channel, which is typically 0 to 255.

--------------------

For example, a black saturation adjustment value of 15 specifies that color channel values in the range 15 to 255 are adjusted so that they spread out over the range 0 to 255, with color channel values less than 15 set to 0.

