---
title: "AdaptiveWhiteStretchFilterOptions.AdaptiveWhiteStretchFilterOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "AdaptiveWhiteStretchFilterOptions 构造函数。初始化 AdaptiveWhiteStretchFilter 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/adaptivewhitestretchfilteroptions/
---
## AdaptiveWhiteStretchFilterOptions constructor

初始化 AdaptiveWhiteStretchFilter 类的新实例。

```csharp
public AdaptiveWhiteStretchFilterOptions(bool isGrayscale = false, int lowPercentile = 10, 
    int highPercentile = 90, int targetWhite = 240, float maxScale = 1.7)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| isGrayscale | Boolean | 指示过滤器是否应在灰度模式下运行。 |
| lowPercentile | Int32 | 黑点的下百分位（例如 10）。 |
| highPercentile | Int32 | 白点的上百分位（例如 90）。 |
| targetWhite | Int32 | 目标白色值（例如 240）。 |
| maxScale | 单精度 | 允许的最大亮度比例（例如 1.7）。 |

## 备注

该算法拉伸直方图，使白色百分位接近 *targetWhite*，但不超过 *maxScale* 以避免过度增亮。

### 另请参见

* class [AdaptiveWhiteStretchFilterOptions](../)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../adaptivewhitestretchfilteroptions/)
* assembly [Aspose.Imaging](../../../)


