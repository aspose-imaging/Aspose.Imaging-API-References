---
title: AdaptiveWhiteStretchFilterOptions Class
type: docs
weight: 10
url: /python-net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---

**Summary:** Provides options for configuring the Adaptive White Stretch filter.<br/>            Allows customization of histogram stretch parameters to enhance the white level<br/>            and improve the readability of faint-text or low-contrast document images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AdaptiveWhiteStretchFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale)](#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1) | Initializes a new instance of the [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| high_percentile | int | r | Gets the upper percentile for white point calculation.<br/>            Pixel values above this percentile are considered as white during stretching. |
| is_grayscale | bool | r | Gets a value indicating whether the filter operates in grayscale mode. |
| low_percentile | int | r | Gets the lower percentile for black point calculation.<br/>            Pixel values below this percentile are considered as black during stretching. |
| max_scale | float | r | Gets the maximum allowed brightness scale.<br/>            The actual stretching will not exceed this factor, to avoid over-brightening. |
| target_white | int | r | Gets the target white value the stretch aims to achieve. |


### Constructor: AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) {#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1}


```
 AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) 
```

Initializes a new instance of the [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| is_grayscale | bool | Indicates whether the filter should operate in grayscale mode. |
| low_percentile | int | Lower percentile for black point (e.g. 10). |
| high_percentile | int | Upper percentile for white point (e.g. 90). |
| target_white | int | Target white value (e.g. 240). |
| max_scale | float | Maximum allowed brightness scale (e.g. 1.7). |

