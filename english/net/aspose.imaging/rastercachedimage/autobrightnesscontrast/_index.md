---
title: RasterCachedImage.AutoBrightnessContrast
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedImage method. Performs automatic adaptive brightness and contrast normalization for the entire image
type: docs
weight: 60
url: /net/aspose.imaging/rastercachedimage/autobrightnesscontrast/
---
## RasterCachedImage.AutoBrightnessContrast method

Performs automatic adaptive brightness and contrast normalization for the entire image.

```csharp
public override void AutoBrightnessContrast()
```

## Remarks

This method applies a pipeline of advanced adaptive filters (CLAHE, adaptive white stretch, and auto white balance) to improve the visual quality of the image by enhancing contrast, local brightness, and color fidelity.

**Filter pipeline:**

1. Contrast-Limited Adaptive Histogram Equalization (CLAHE) – improves local contrast and enhances faint details.
2. Adaptive White Stretch – increases effective white level while protecting dark features.
3. Auto White Balance – corrects color casts by balancing channel histograms.

**Note:**

* Each filter stage uses its default settings. For custom parameters, apply filters individually.
* The method is intended for use in automated normalization scenarios (e.g., scan preprocessing, document pipelines).

## Examples

```csharp
// Example usage in image pre-processing:
image.AutoBrightnessContrast();
```

### See Also

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


