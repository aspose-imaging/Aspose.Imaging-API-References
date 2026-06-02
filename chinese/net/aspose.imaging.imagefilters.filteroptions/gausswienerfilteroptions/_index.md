---
title: "类 GaussWienerFilterOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions 类。用于图像去模糊的 Gauss Wiener 过滤器选项"
type: docs
weight: 10030
url: /zh/net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---
## GaussWienerFilterOptions class

用于图像去模糊的高斯维纳滤镜选项。

```csharp
public class GaussWienerFilterOptions : GaussianDeconvolutionFilterOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GaussWienerFilterOptions](gausswienerfilteroptions/#constructor)() | 初始化 `GaussWienerFilterOptions` 类的新实例。 |
| [GaussWienerFilterOptions](gausswienerfilteroptions/#constructor_1)(int, double) | 初始化 `GaussWienerFilterOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness/) { get; set; } | 获取或设置亮度。推荐范围 1 - 1.5，默认值 = 1.15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale/) { get; set; } | 获取或设置一个值，指示此 [`DeconvolutionFilterOptions`](../deconvolutionfilteroptions/) 是否为灰度。返回灰度模式或 RGB 模式。 |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded/) { get; } | 获取一个值，指示此实例是否为部分加载。 |
| override [Kernel](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/kernel/) { get; } | 获取核。 |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/radius/) { get; set; } | 获取高斯 ISquareConvolutionKernel 的半径。 |
| [Sigma](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/sigma/) { get; set; } | 获取高斯核的 sigma（平滑度）。必须为正的非零值。 |
| [Size](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/size/) { get; set; } | 获取高斯核的大小。必须为正的非零奇数值。 |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr/) { get; set; } | 获取或设置信噪比（SNR），推荐范围 0.002 - 0.009，默认值 = 0.007 |

## 示例

以下示例对光栅图像应用各种类型的过滤器。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 对整幅图像应用矩形大小为 5 的中值滤波器。
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    rasterImage.Save(dir + "sample.MedianFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 对整幅图像应用核大小为 5 的双边平滑滤波器。
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    rasterImage.Save(dir + "sample.BilateralSmoothingFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 对整幅图像应用半径为 5、σ 值为 4.0 的高斯模糊滤波器。
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussianBlurFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 对整幅图像应用半径为 5、平滑值为 4.0 的 Gauss-Wiener 滤波器。
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 对整幅图像应用长度为 5、平滑值为 4.0、角度为 90.0 度的运动 Wiener 滤波器。
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.Save(dir + "sample.MotionWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 对整幅图像应用核大小为 5、σ 值为 4.0 的锐化滤波器。
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.SharpenFilter.png");
}
```

### 另请参见

* class [GaussianDeconvolutionFilterOptions](../gaussiandeconvolutionfilteroptions/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


