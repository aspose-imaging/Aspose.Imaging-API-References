---
title: EmfPlusInterpolationMode
second_title: Aspose.Imaging for Java API Reference
description: The InterpolationMode enumeration defines ways to perform scaling including stretching and shrinking.
type: docs
weight: 29
url: /java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusInterpolationMode extends System.Enum
```

The InterpolationMode enumeration defines ways to perform scaling, including stretching and shrinking.
## Fields

| Field | Description |
| --- | --- |
| [InterpolationModeDefault](#InterpolationModeDefault) | Specifies the default interpolation mode, which is defined as InterpolationModeBilinear. |
| [InterpolationModeLowQuality](#InterpolationModeLowQuality) | Specifies a low-quality interpolation mode, which is defined as InterpolationModeNearestNeighbor. |
| [InterpolationModeHighQuality](#InterpolationModeHighQuality) | Specifies a high-quality interpolation mode, which is defined as InterpolationModeHighQualityBicubic. |
| [InterpolationModeBilinear](#InterpolationModeBilinear) | Specifies bilinear interpolation, which uses the closest 2x2 neighborhood of known pixels surrounding the interpolated pixel. |
| [InterpolationModeBicubic](#InterpolationModeBicubic) | Specifies bicubic interpolation, which uses the closest 4x4 neighborhood of known pixels surrounding the interpolated pixel. |
| [InterpolationModeNearestNeighbor](#InterpolationModeNearestNeighbor) | Specifies nearest-neighbor interpolation, which uses only the value of the pixel that is closest to the interpolated pixel. |
| [InterpolationModeHighQualityBilinear](#InterpolationModeHighQualityBilinear) | Specifies bilinear interpolation with prefiltering. |
| [InterpolationModeHighQualityBicubic](#InterpolationModeHighQualityBicubic) | Specifies bicubic interpolation with prefiltering, which produces the highest-quality result among these options. |
### InterpolationModeDefault {#InterpolationModeDefault}
```
public static final byte InterpolationModeDefault
```


Specifies the default interpolation mode, which is defined as InterpolationModeBilinear.

### InterpolationModeLowQuality {#InterpolationModeLowQuality}
```
public static final byte InterpolationModeLowQuality
```


Specifies a low-quality interpolation mode, which is defined as InterpolationModeNearestNeighbor.

### InterpolationModeHighQuality {#InterpolationModeHighQuality}
```
public static final byte InterpolationModeHighQuality
```


Specifies a high-quality interpolation mode, which is defined as InterpolationModeHighQualityBicubic.

### InterpolationModeBilinear {#InterpolationModeBilinear}
```
public static final byte InterpolationModeBilinear
```


Specifies bilinear interpolation, which uses the closest 2x2 neighborhood of known pixels surrounding the interpolated pixel. The weighted average of these 4 known pixel values determines the value to assign to the interpolated pixel. The result is smoother looking than InterpolationModeNearestNeighbor.

### InterpolationModeBicubic {#InterpolationModeBicubic}
```
public static final byte InterpolationModeBicubic
```


Specifies bicubic interpolation, which uses the closest 4x4 neighborhood of known pixels surrounding the interpolated pixel. The weighted average of these 16 known pixel values determines the value to assign to the interpolated pixel. Because the known pixels are likely to be at varying distances from the interpolated pixel, closer pixels are given a higher weight in the calculation. The result is smoother looking than InterpolationModeBilinear.

### InterpolationModeNearestNeighbor {#InterpolationModeNearestNeighbor}
```
public static final byte InterpolationModeNearestNeighbor
```


Specifies nearest-neighbor interpolation, which uses only the value of the pixel that is closest to the interpolated pixel. This mode simply duplicates or removes pixels, producing the lowest-quality result among these options.

### InterpolationModeHighQualityBilinear {#InterpolationModeHighQualityBilinear}
```
public static final byte InterpolationModeHighQualityBilinear
```


Specifies bilinear interpolation with prefiltering.

### InterpolationModeHighQualityBicubic {#InterpolationModeHighQualityBicubic}
```
public static final byte InterpolationModeHighQualityBicubic
```


Specifies bicubic interpolation with prefiltering, which produces the highest-quality result among these options.

