---
title: "类 AdaptiveWhiteStretchFilterOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageFilters.FilterOptions.AdaptiveWhiteStretchFilterOptions 类。提供配置 Adaptive White Stretch 滤镜的选项。允许自定义直方图拉伸参数，以提升白色水平并改善淡文本或低对比度文档图像的可读性。"
type: docs
weight: 9940
url: /zh/net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
## AdaptiveWhiteStretchFilterOptions class

提供配置自适应白色拉伸滤镜的选项。允许自定义直方图拉伸参数，以提升白色水平并改善淡文字或低对比度文档图像的可读性。

```csharp
public class AdaptiveWhiteStretchFilterOptions : FilterOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions](adaptivewhitestretchfilteroptions/)(bool, int, int, int, float) | 初始化 AdaptiveWhiteStretchFilter 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [HighPercentile](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/highpercentile/) { get; } | 获取白点计算的上百分位。该百分位以上的像素值在拉伸时被视为白色。 |
| [IsGrayscale](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/isgrayscale/) { get; } | 获取一个值，指示滤镜是否在灰度模式下运行。 |
| [LowPercentile](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/lowpercentile/) { get; } | 获取黑点计算的下百分位。该百分位以下的像素值在拉伸时被视为黑色。 |
| [MaxScale](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/maxscale/) { get; } | 获取允许的最大亮度比例。实际拉伸不会超过此因子，以避免过度增亮。 |
| [TargetWhite](../../aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/targetwhite/) { get; } | 获取拉伸目标的白色值。 |

### 另请参见

* class [FilterOptionsBase](../filteroptionsbase/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


