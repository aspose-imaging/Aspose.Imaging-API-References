---
title: "枚举 ResizeType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ResizeType 枚举。指定调整大小的类型"
type: docs
weight: 11450
url: /zh/net/aspose.imaging/resizetype/
---
## ResizeType enumeration

指定调整大小的类型。

```csharp
public enum ResizeType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | `0` | 在调整大小操作期间，像素不会被保留。 |
| LeftTopToLeftTop | `1` | 新图像的左上点将与原始图像的左上点重合。如有需要，将进行裁剪。 |
| RightTopToRightTop | `2` | 新图像的右上点将与原始图像的右上点重合。如有需要，将进行裁剪。 |
| RightBottomToRightBottom | `3` | 新图像的右下点将与原始图像的右下点重合。如有需要，将进行裁剪。 |
| LeftBottomToLeftBottom | `4` | 新图像的左下点将与原始图像的左下点重合。如有需要，将进行裁剪。 |
| CenterToCenter | `5` | 新图像的中心将与原始图像的中心重合。如有需要，将进行裁剪。 |
| LanczosResample | `6` | 使用 a=3 的 Lanczos 算法进行重采样。 |
| NearestNeighbourResample | `7` | 使用最近邻算法进行重采样。 |
| AdaptiveResample | `8` | 使用基于加权和混合有理函数以及 lanczos3 插值算法的自适应算法进行重采样。 |
| BilinearResample | `9` | 使用双线性插值进行重采样。需要时，可进行图像预过滤以在重采样前去除噪声。 |
| HighQualityResample | `10` | 高质量的重采样 |
| CatmullRom | `11` | Catmull-Rom 三次插值方法。 |
| CubicConvolution | `12` | 立方卷积插值方法 |
| CubicBSpline | `13` | CubicBSpline 三次插值方法 |
| Mitchell | `14` | Mitchell 三次插值方法 |
| SinC | `15` | Sinc（Lanczos3）三次插值方法 |
| Bell | `16` | Bell 插值方法 |

## 示例

使用特定的缩放类型调整图像大小。

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

此示例加载图像并使用多种调整大小方法对其进行缩放。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


