---
title: AutoWhiteBalanceFilterOptions Class
type: docs
weight: 20
url: /python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---

**Summary:** Provides configuration options for the Auto White Balance filter.<br/>            Allows tuning of contrast stretching parameters and channel scaling<br/>            to improve the appearance of digital images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AutoWhiteBalanceFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset)](#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1) | Initializes a new instance of the [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| low_percentile | int | r | The low percentile for black point, used for darks protection (default: 3). |
| max_scale | float | r | Gets the maximum scaling factor for each channel.<br/>            Restricts the amplification of any channel to avoid excessive color shifts. |
| protected_dark_offset | int | r | Offset from low percentile below which dark pixels are not stretched (protection). |
| target_high_percentile | int | r | Gets the target high percentile for contrast stretching.<br/>            Determines which brightness percentile will be mapped to the target value. |
| target_value | int | r | Gets the target value for the high percentile.<br/>            This value will be used as the white reference for contrast stretching. |


### Constructor: AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) {#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1}


```
 AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) 
```

Initializes a new instance of the [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| low_percentile | int | The low percentile for black point, used for darks protection (default: 3). |
| target_high_percentile | int | The target high percentile for contrast stretching (default 97). |
| target_value | int | The target value for the high percentile (default 255). |
| max_scale | float | The maximum scaling factor for each channel (default 1.4f). |
| protected_dark_offset | int | Offset from low percentile below which dark pixels are not stretched (protection). |

