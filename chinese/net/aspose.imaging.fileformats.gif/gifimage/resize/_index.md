---
title: "GifImage.Resize"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。调整此 Image 实例的大小"
type: docs
weight: 360
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

调整此 [`Image`](../../../aspose.imaging/image/) 实例的大小。

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 缩放类型。 |

## 示例

此示例加载 GIF 图像并使用多种缩放方法对其进行大小调整。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

调整此 [`Image`](../../../aspose.imaging/image/) 实例的大小。

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| 设置 | ImageResizeSettings | 设置。 |

## 示例

此示例加载 GIF 图像并使用多种缩放设置对其进行大小调整。

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

using (Aspose.Imaging.Image image = (Aspose.Imaging.Image)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 使用自适应重采样将尺寸缩小两倍。
    gifImage.Resize(image.Width / 2, image.Height / 2, resizeSettings);

    // 保存为 PNG
    gifImage.Save(dir + "downsample.adaptive.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


