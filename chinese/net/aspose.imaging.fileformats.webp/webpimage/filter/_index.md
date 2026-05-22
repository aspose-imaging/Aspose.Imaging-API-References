---
title: "WebPImage.Filter"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WebPImage 方法。对指定矩形内的内容进行过滤，应用指定的图像处理滤镜以增强或修改所选区域。将此方法集成到您的图像操作工作流中，以在应用程序中实现针对性的增强或转换。"
type: docs
weight: 180
url: /zh/net/aspose.imaging.fileformats.webp/webpimage/filter/
---
## WebPImage.Filter method

在指定的矩形内过滤内容，应用指定的图像处理滤镜以增强或修改所选区域。将此方法集成到图像操作工作流，以在应用程序中实现针对性的增强或转换。

```csharp
public override void Filter(Rectangle rectangle, FilterOptionsBase options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 矩形。 |
| 选项 | FilterOptionsBase | 选项。 |

## 示例

以下示例对 WEBP 图像应用了多种类型的滤镜。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // 对整幅图像应用矩形大小为 5 的中值滤波器。
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    webpImage.Save(dir + "sample.MedianFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // 对整幅图像应用核大小为 5 的双边平滑滤波器。
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    webpImage.Save(dir + "sample.BilateralSmoothingFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // 对整幅图像应用半径为 5、σ 值为 4.0 的高斯模糊滤波器。
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.Save(dir + "sample.GaussianBlurFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // 对整幅图像应用半径为 5、平滑值为 4.0 的 Gauss-Wiener 滤波器。
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.Save(dir + "sample.GaussWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // 对整幅图像应用长度为 5、平滑值为 4.0、角度为 90.0 度的运动 Wiener 滤波器。
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.Save(dir + "sample.MotionWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // 对整幅图像应用核大小为 5、σ 值为 4.0 的锐化滤波器。
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    webpImage.Save(dir + "sample.SharpenFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [FilterOptionsBase](../../../aspose.imaging.imagefilters.filteroptions/filteroptionsbase/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


