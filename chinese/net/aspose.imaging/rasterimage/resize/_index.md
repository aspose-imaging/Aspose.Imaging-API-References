---
title: "RasterImage.Resize"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。使用扩展选项调整图像大小。"
type: docs
weight: 550
url: /zh/net/aspose.imaging/rasterimage/resize/
---
## RasterImage.Resize method

使用扩展选项调整图像大小。

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| 设置 | ImageResizeSettings | 缩放设置。 |

## 示例

此示例加载栅格图像并使用各种调整大小设置对其进行缩放。

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

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // 使用自适应重采样将尺寸缩小两倍。
    image.Resize(image.Width / 2, image.Height / 2, resizeSettings);
    image.Save(dir + "downsample.adaptive.gif");
}
```

### 另请参见

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


