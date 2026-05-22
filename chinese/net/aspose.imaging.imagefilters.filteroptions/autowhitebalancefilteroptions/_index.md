---
title: "类 AutoWhiteBalanceFilterOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageFilters.FilterOptions.AutoWhiteBalanceFilterOptions 类。提供 Auto White Balance 滤镜的配置选项。允许调节对比度拉伸参数和通道缩放，以改善数字图像的外观。"
type: docs
weight: 9950
url: /zh/net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
## AutoWhiteBalanceFilterOptions class

提供自动白平衡滤镜的配置选项。允许调节对比度拉伸参数和通道缩放，以提升数字图像的外观。

```csharp
public class AutoWhiteBalanceFilterOptions : FilterOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AutoWhiteBalanceFilterOptions](autowhitebalancefilteroptions/)(int, int, int, float, int) | 初始化 `AutoWhiteBalanceFilterOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [LowPercentile](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/lowpercentile/) { get; } | 低百分位用于黑点，作为暗部保护（默认：3）。 |
| [MaxScale](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/maxscale/) { get; } | 获取每个通道的最大缩放因子。限制任何通道的放大，以避免过度的颜色偏移。 |
| [ProtectedDarkOffset](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/protecteddarkoffset/) { get; } | 低百分位以下的偏移量，暗像素不被拉伸（保护）。 |
| [TargetHighPercentile](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/targethighpercentile/) { get; } | 获取对比度拉伸的目标高百分位。确定哪个亮度百分位将映射到目标值。 |
| [TargetValue](../../aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/targetvalue/) { get; } | 获取高百分位的目标值。该值将用作对比度拉伸的白色参考。 |

### 另请参见

* class [FilterOptionsBase](../filteroptionsbase/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


