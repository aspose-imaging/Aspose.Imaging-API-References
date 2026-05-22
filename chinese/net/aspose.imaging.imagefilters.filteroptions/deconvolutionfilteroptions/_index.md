---
title: "类 DeconvolutionFilterOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageFilters.FilterOptions.DeconvolutionFilterOptions 类。反卷积过滤器选项抽象类"
type: docs
weight: 10010
url: /zh/net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---
## DeconvolutionFilterOptions class

去卷积滤镜选项，抽象类

```csharp
public class DeconvolutionFilterOptions : FilterOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DeconvolutionFilterOptions](deconvolutionfilteroptions/#constructor)(Complex[]) |  |
| [DeconvolutionFilterOptions](deconvolutionfilteroptions/#constructor_1)(double[]) |  |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness/) { get; set; } | 获取或设置亮度。推荐范围 1 - 1.5，默认值 = 1.15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale/) { get; set; } | 获取或设置一个值，指示此 `DeconvolutionFilterOptions` 是否为灰度。返回灰度模式或 RGB 模式。 |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded/) { get; } | 获取一个值，指示此实例是否为部分加载。 |
| virtual [Kernel](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/kernel/) { get; } | 获取核。 |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr/) { get; set; } | 获取或设置信噪比（SNR），推荐范围 0.002 - 0.009，默认值 = 0.007 |

### 另请参见

* class [FilterOptionsBase](../filteroptionsbase/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


