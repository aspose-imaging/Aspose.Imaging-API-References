---
title: "GifImage.Filter"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。对图像的指定区域应用特定滤镜，以提升视觉质量或按需改变外观。此方法在定义的矩形区域内有选择地处理像素，允许进行针对性调整，同时保持周围图像数据的完整性。"
type: docs
weight: 300
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/filter/
---
## GifImage.Filter method

对图像指定区域应用特定滤镜，提升其视觉质量或按需改变外观。此方法在定义的矩形内有选择地处理像素，允许进行针对性调整，同时保持周围图像数据的完整性。

```csharp
public override void Filter(Rectangle rectangle, FilterOptionsBase options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 矩形。 |
| 选项 | FilterOptionsBase | 选项。 |

## 示例

以下示例对 GIF 图像应用了多种滤镜。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 对整幅图像应用矩形大小为 5 的中值滤波器。
    gifImage.Filter(gifImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    gifImage.Save(dir + "sample.MedianFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 对整幅图像应用核大小为 5 的双边平滑滤波器。
    gifImage.Filter(gifImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    gifImage.Save(dir + "sample.BilateralSmoothingFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 对整幅图像应用半径为 5、σ 值为 4.0 的高斯模糊滤波器。
    gifImage.Filter(gifImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    gifImage.Save(dir + "sample.GaussianBlurFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 对整幅图像应用半径为 5、平滑值为 4.0 的 Gauss-Wiener 滤波器。
    gifImage.Filter(gifImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    gifImage.Save(dir + "sample.GaussWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 对整幅图像应用长度为 5、平滑值为 4.0、角度为 90.0 度的运动 Wiener 滤波器。
    gifImage.Filter(gifImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    gifImage.Save(dir + "sample.MotionWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 对整幅图像应用核大小为 5、σ 值为 4.0 的锐化滤波器。
    gifImage.Filter(gifImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    gifImage.Save(dir + "sample.SharpenFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [FilterOptionsBase](../../../aspose.imaging.imagefilters.filteroptions/filteroptionsbase/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


