---
title: "AdaptiveWhiteStretchFilterOptions 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---

**Summary:** Provides options for configuring the Adaptive White Stretch filter.<br/>            Allows customization of histogram stretch parameters to enhance the white level<br/>            and improve the readability of faint-text or low-contrast document images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AdaptiveWhiteStretchFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale)](#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1) | 初始化 [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| high_percentile | int | r | 获取用于白点计算的上限百分位。<br/>            拉伸过程中，高于此百分位的像素值被视为白色。 |
| is_grayscale | bool | r | 获取一个值，指示过滤器是否在灰度模式下运行。 |
| low_percentile | int | r | 获取用于黑点计算的下限百分位。<br/>            拉伸过程中，低于此百分位的像素值被视为黑色。 |
| max_scale | float | r | 获取允许的最大亮度比例。<br/>            实际拉伸不会超过此因子，以避免过度增亮。 |
| target_white | int | r | 获取拉伸目标的白色值。 |


### Constructor: AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) {#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1}


```
 AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) 
```

初始化 [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| is_grayscale | bool | 指示过滤器是否应在灰度模式下运行。 |
| low_percentile | int | 黑点的下限百分位（例如 10）。 |
| high_percentile | int | 白点的上限百分位（例如 90）。 |
| target_white | int | 目标白色值（例如 240）。 |
| max_scale | float | 允许的最大亮度比例（例如 1.7）。 |

