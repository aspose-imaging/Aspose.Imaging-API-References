---
title: "AutoWhiteBalanceFilterOptions 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---

**Summary:** Provides configuration options for the Auto White Balance filter.<br/>            Allows tuning of contrast stretching parameters and channel scaling<br/>            to improve the appearance of digital images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AutoWhiteBalanceFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset)](#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1) | 初始化 [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| low_percentile | int | r | 黑点的低百分位，用于暗部保护（默认值：3）。 |
| max_scale | float | r | 获取每个通道的最大缩放因子。<br/>限制任何通道的放大，以避免过度的色彩偏移。 |
| protected_dark_offset | int | r | 低百分位以下的偏移量，低于此值的暗像素不被拉伸（保护）。 |
| target_high_percentile | int | r | 获取对比度拉伸的目标高百分位。<br/>            确定哪个亮度百分位将映射到目标值。 |
| target_value | int | r | 获取高百分位的目标值。<br/>            此值将用作对比度拉伸的白色参考。 |


### Constructor: AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) {#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1}


```
 AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) 
```

初始化 [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| low_percentile | int | 黑点的低百分位，用于暗部保护（默认值：3）。 |
| target_high_percentile | int | 对比度拉伸的目标高百分位（默认 97）。 |
| target_value | int | 高百分位的目标值（默认 255）。 |
| max_scale | float | 每个通道的最大缩放因子（默认 1.4f）。 |
| protected_dark_offset | int | 低百分位以下的偏移量，低于此值的暗像素不被拉伸（保护）。 |

