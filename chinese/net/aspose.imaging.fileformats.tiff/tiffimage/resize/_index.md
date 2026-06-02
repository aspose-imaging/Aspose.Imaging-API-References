---
title: "TiffImage.Resize"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。根据指定的缩放类型调整图像大小，以灵活地改变图像尺寸，同时保持宽高比或应用特定的缩放算法。将此方法集成到您的图像处理工作流中，以在应用程序内实现对缩放操作的精确控制。"
type: docs
weight: 330
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

根据指定的缩放类型调整图像大小，在保持宽高比或使用特定缩放算法的同时，实现图像尺寸的灵活调整。将此方法纳入图像处理工作流，以在应用程序中实现对缩放操作的精确控制。

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 缩放类型。 |

## 示例

此示例加载 TIFF 图像并使用各种缩放方法对其进行大小调整。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

根据指定设置调整图像大小，实现对尺寸、宽高比和缩放行为的精确控制。将此方法集成到图像处理工作流中，以实现符合应用程序特定需求的自定义缩放操作。

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| 设置 | ImageResizeSettings | 缩放设置。 |

## 示例

此示例加载 TIFF 图像并使用各种缩放设置对其进行大小调整。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageResizeSettings resizeSettings = new Aspose.Imaging.ImageResizeSettings();

// 基于加权和混合有理函数以及 Lanczos3 插值的自适应算法。
resizeSettings.Mode = Aspose.Imaging.ResizeType.AdaptiveResample;

// 小矩形滤波器
resizeSettings.FilterType = Aspose.Imaging.ImageFilterType.SmallRectangular;

// 调色板中的颜色数量。
resizeSettings.EntriesCount = 256;

// 未使用颜色量化
resizeSettings.ColorQuantizationMethod = ColorQuantizationMethod.None;

// 欧几里得方法
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

using (Aspose.Imaging.Image image = (Aspose.Imaging.Image)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 使用自适应重采样将尺寸缩小两倍。
    tiffImage.Resize(image.Width / 2, image.Height / 2, resizeSettings);

    // 保存为 PNG
    tiffImage.Save(dir + "downsample.adaptive.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


