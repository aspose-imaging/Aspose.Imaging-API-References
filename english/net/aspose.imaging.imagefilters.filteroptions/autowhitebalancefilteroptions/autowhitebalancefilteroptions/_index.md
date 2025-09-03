---
title: AutoWhiteBalanceFilterOptions.AutoWhiteBalanceFilterOptions
second_title: Aspose.Imaging for .NET API Reference
description: AutoWhiteBalanceFilterOptions constructor. Initializes a new instance of the AutoWhiteBalanceFilterOptions class
type: docs
weight: 10
url: /net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/autowhitebalancefilteroptions/
---
## AutoWhiteBalanceFilterOptions constructor

Initializes a new instance of the [`AutoWhiteBalanceFilterOptions`](../) class.

```csharp
public AutoWhiteBalanceFilterOptions(int lowPercentile = 3, int targetHighPercentile = 97, 
    int targetValue = 255, float maxScale = 1.4, int protectedDarkOffset = 10)
```

| Parameter | Type | Description |
| --- | --- | --- |
| lowPercentile | Int32 | The low percentile for black point, used for darks protection (default: 3). |
| targetHighPercentile | Int32 | The target high percentile for contrast stretching (default 97). |
| targetValue | Int32 | The target value for the high percentile (default 255). |
| maxScale | Single | The maximum scaling factor for each channel (default 1.4f). |
| protectedDarkOffset | Int32 | Offset from low percentile below which dark pixels are not stretched (protection). |

### See Also

* class [AutoWhiteBalanceFilterOptions](../)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../autowhitebalancefilteroptions/)
* assembly [Aspose.Imaging](../../../)


