---
title: "DjvuImage.Filter"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 方法。对图像中指定的矩形区域应用滤镜，以增强或修改其外观。通过针对特定区域，此方法可实现精确的调整，如模糊、锐化或应用艺术效果，以达到期望的视觉效果。在选定区域微调滤镜，使用户能够自定义图像美感、提升清晰度并创建符合个人偏好的艺术效果。"
type: docs
weight: 240
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/filter/
---
## DjvuImage.Filter method

在图像的指定矩形区域内应用滤镜，以增强或修改其外观。通过针对特定区域，此方法可进行精确调整，如模糊、锐化或应用艺术效果，以实现期望的视觉效果。对选定区域的滤镜进行微调，使用户能够自定义图像美感、提升清晰度，并创建符合个人偏好的艺术效果。

```csharp
public override void Filter(Rectangle rectangle, FilterOptionsBase options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 矩形。 |
| 选项 | FilterOptionsBase | 选项。 |

## 示例

以下示例对 DJVU 图像应用了多种类型的滤镜。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 对整幅图像应用矩形大小为 5 的中值滤波器。
    djvuImage.Filter(djvuImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    djvuImage.Save(dir + "sample.MedianFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 对整幅图像应用核大小为 5 的双边平滑滤波器。
    djvuImage.Filter(djvuImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    djvuImage.Save(dir + "sample.BilateralSmoothingFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 对整幅图像应用半径为 5、σ 值为 4.0 的高斯模糊滤波器。
    djvuImage.Filter(djvuImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    djvuImage.Save(dir + "sample.GaussianBlurFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 对整幅图像应用半径为 5、平滑值为 4.0 的 Gauss-Wiener 滤波器。
    djvuImage.Filter(djvuImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    djvuImage.Save(dir + "sample.GaussWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 对整幅图像应用长度为 5、平滑值为 4.0、角度为 90.0 度的运动 Wiener 滤波器。
    djvuImage.Filter(djvuImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    djvuImage.Save(dir + "sample.MotionWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 对整幅图像应用核大小为 5、σ 值为 4.0 的锐化滤波器。
    djvuImage.Filter(djvuImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    djvuImage.Save(dir + "sample.SharpenFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [FilterOptionsBase](../../../aspose.imaging.imagefilters.filteroptions/filteroptionsbase/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


