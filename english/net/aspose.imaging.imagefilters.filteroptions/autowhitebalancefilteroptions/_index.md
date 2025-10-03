---
title: Class AutoWhiteBalanceFilterOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageFilters.FilterOptions.AutoWhiteBalanceFilterOptions class. Provides configuration options for the Auto White Balance filter. Allows tuning of contrast stretching parameters and channel scaling to improve the appearance of digital images
type: docs
weight: 9910
url: /net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
## AutoWhiteBalanceFilterOptions class

Provides configuration options for the Auto White Balance filter. Allows tuning of contrast stretching parameters and channel scaling to improve the appearance of digital images.

```csharp
public class AutoWhiteBalanceFilterOptions : FilterOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [AutoWhiteBalanceFilterOptions](autowhitebalancefilteroptions/)(int, int, int, float, int) | Initializes a new instance of the `AutoWhiteBalanceFilterOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [LowPercentile](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/lowpercentile/) { get; } | The low percentile for black point, used for darks protection (default: 3). |
| [MaxScale](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/maxscale/) { get; } | Gets the maximum scaling factor for each channel. Restricts the amplification of any channel to avoid excessive color shifts. |
| [ProtectedDarkOffset](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/protecteddarkoffset/) { get; } | Offset from low percentile below which dark pixels are not stretched (protection). |
| [TargetHighPercentile](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/targethighpercentile/) { get; } | Gets the target high percentile for contrast stretching. Determines which brightness percentile will be mapped to the target value. |
| [TargetValue](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/targetvalue/) { get; } | Gets the target value for the high percentile. This value will be used as the white reference for contrast stretching. |

### See Also

* class [FilterOptionsBase](../filteroptionsbase/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


