---
title: AdaptiveWhiteStretchFilterOptions.AdaptiveWhiteStretchFilterOptions
second_title: Aspose.Imaging for .NET API Reference
description: AdaptiveWhiteStretchFilterOptions constructor. Initializes a new instance of the AdaptiveWhiteStretchFilter class
type: docs
weight: 10
url: /net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/adaptivewhitestretchfilteroptions/
---
## AdaptiveWhiteStretchFilterOptions constructor

Initializes a new instance of the AdaptiveWhiteStretchFilter class.

```csharp
public AdaptiveWhiteStretchFilterOptions(bool isGrayscale = false, int lowPercentile = 10, 
    int highPercentile = 90, int targetWhite = 240, float maxScale = 1.7)
```

| Parameter | Type | Description |
| --- | --- | --- |
| isGrayscale | Boolean | Indicates whether the filter should operate in grayscale mode. |
| lowPercentile | Int32 | Lower percentile for black point (e.g. 10). |
| highPercentile | Int32 | Upper percentile for white point (e.g. 90). |
| targetWhite | Int32 | Target white value (e.g. 240). |
| maxScale | Single | Maximum allowed brightness scale (e.g. 1.7). |

## Remarks

The algorithm stretches the histogram so that the white percentile approaches *targetWhite*, but without exceeding *maxScale* to avoid over-brightening.

### See Also

* class [AdaptiveWhiteStretchFilterOptions](../)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../adaptivewhitestretchfilteroptions/)
* assembly [Aspose.Imaging](../../../)


