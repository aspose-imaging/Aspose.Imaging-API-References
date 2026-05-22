---
title: "类 GaussianDeconvolutionFilterOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageFilters.FilterOptions.GaussianDeconvolutionFilterOptions 类。使用高斯模糊的去卷积滤镜选项"
type: docs
weight: 10050
url: /zh/net/aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
## GaussianDeconvolutionFilterOptions class

使用高斯模糊的去卷积滤镜选项。

```csharp
public abstract class GaussianDeconvolutionFilterOptions : DeconvolutionFilterOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GaussianDeconvolutionFilterOptions](gaussiandeconvolutionfilteroptions/)(int, double) | 初始化 `GaussianDeconvolutionFilterOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness/) { get; set; } | 获取或设置亮度。推荐范围 1 - 1.5，默认值 = 1.15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale/) { get; set; } | 获取或设置一个值，指示此 [`DeconvolutionFilterOptions`](../deconvolutionfilteroptions/) 是否为灰度。返回灰度模式或 RGB 模式。 |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded/) { get; } | 获取一个值，指示此实例是否为部分加载。 |
| virtual [Kernel](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/kernel/) { get; } | 获取核。 |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/radius/) { get; set; } | 获取高斯 ISquareConvolutionKernel 的半径。 |
| [Sigma](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/sigma/) { get; set; } | 获取高斯核的 sigma（平滑度）。必须为正的非零值。 |
| [Size](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/size/) { get; set; } | 获取高斯核的大小。必须为正的非零奇数值。 |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr/) { get; set; } | 获取或设置信噪比（SNR），推荐范围 0.002 - 0.009，默认值 = 0.007 |

### 另请参见

* class [DeconvolutionFilterOptions](../deconvolutionfilteroptions/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


