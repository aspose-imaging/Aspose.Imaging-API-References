---
title: "DjvuImage.ResizeHeightProportionally"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 方法。ResizeHeightProportionally 方法允许您在保持宽高比的同时调整图像高度。这确保图像保持比例，防止失真并保持视觉完整性。无论是为网页、移动应用还是印刷媒体优化图像，此方法都能确保图像在不同平台和设备上呈现最佳效果。"
type: docs
weight: 270
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/resizeheightproportionally/
---
## DjvuImage.ResizeHeightProportionally method

`ResizeHeightProportionally` 方法允许您在保持宽高比的前提下调整图像的高度。这确保图像保持比例，防止失真并保持视觉完整性。无论是为网页、移动应用还是印刷媒体优化图像，此方法都能确保图像在不同平台和设备上呈现最佳效果。

```csharp
public override void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 调整的类型。 |

## 示例

此示例加载 DJVU 图像，并使用多种缩放方法按比例调整大小。仅指定高度，宽度会自动计算。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


