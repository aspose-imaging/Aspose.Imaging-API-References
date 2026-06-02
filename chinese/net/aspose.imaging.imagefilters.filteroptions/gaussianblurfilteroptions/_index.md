---
title: "类 GaussianBlurFilterOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions 类。高斯模糊过滤器选项"
type: docs
weight: 10040
url: /zh/net/aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---
## GaussianBlurFilterOptions class

高斯模糊滤镜选项。

```csharp
public class GaussianBlurFilterOptions : ConvolutionFilterOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GaussianBlurFilterOptions](gaussianblurfilteroptions/#constructor)() | 初始化 `GaussianBlurFilterOptions` 类的新实例。 |
| [GaussianBlurFilterOptions](gaussianblurfilteroptions/#constructor_1)(int, double) | 初始化 `GaussianBlurFilterOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bias](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/bias/) { get; set; } | 获取或设置偏置。 |
| [BordersProcessing](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/bordersprocessing/) { get; set; } | 获取或设置一个值，指示是否进行 [borders processing]。 |
| [Factor](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/factor/) { get; set; } | 获取或设置因子。 |
| [IgnoreAlpha](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/ignorealpha/) { get; set; } | 获取或设置一个值，指示是否 [ignore alpha]。 |
| override [Kernel](../../aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/kernel/) { get; } | 获取高斯核。 |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/radius/) { get; set; } | 获取高斯 ISquareConvolutionKernel 的半径。 |
| virtual [Sigma](../../aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/sigma/) { get; set; } | 获取高斯核的 sigma（平滑度）。必须为正的非零值。 |
| virtual [Size](../../aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/size/) { get; set; } | 获取高斯核的大小。必须为正的非零奇数值。 |

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

* class [ConvolutionFilterOptions](../convolutionfilteroptions/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


