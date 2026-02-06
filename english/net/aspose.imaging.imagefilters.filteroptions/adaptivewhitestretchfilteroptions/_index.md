---
title: Class AdaptiveWhiteStretchFilterOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageFilters.FilterOptions.AdaptiveWhiteStretchFilterOptions class. Provides options for configuring the Adaptive White Stretch filter. Allows customization of histogram stretch parameters to enhance the white level and improve the readability of fainttext or lowcontrast document images
type: docs
weight: 9940
url: /net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
## AdaptiveWhiteStretchFilterOptions class

Provides options for configuring the Adaptive White Stretch filter. Allows customization of histogram stretch parameters to enhance the white level and improve the readability of faint-text or low-contrast document images.

```csharp
public class AdaptiveWhiteStretchFilterOptions : FilterOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions](adaptivewhitestretchfilteroptions/)(bool, int, int, int, float) | Initializes a new instance of the AdaptiveWhiteStretchFilter class. |

## Properties

| Name | Description |
| --- | --- |
| [HighPercentile](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/highpercentile/) { get; } | Gets the upper percentile for white point calculation. Pixel values above this percentile are considered as white during stretching. |
| [IsGrayscale](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/isgrayscale/) { get; } | Gets a value indicating whether the filter operates in grayscale mode. |
| [LowPercentile](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/lowpercentile/) { get; } | Gets the lower percentile for black point calculation. Pixel values below this percentile are considered as black during stretching. |
| [MaxScale](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/maxscale/) { get; } | Gets the maximum allowed brightness scale. The actual stretching will not exceed this factor, to avoid over-brightening. |
| [TargetWhite](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/targetwhite/) { get; } | Gets the target white value the stretch aims to achieve. |

### See Also

* class [FilterOptionsBase](../filteroptionsbase/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


