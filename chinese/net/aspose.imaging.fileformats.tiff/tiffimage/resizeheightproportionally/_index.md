---
title: "TiffImage.ResizeHeightProportionally"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。对图像高度进行比例调整，保持宽高比，以确保视觉完整性的一致性。使用此方法在您的应用程序中动态调整图像大小，确保在各种平台和设备上实现最佳显示，而不影响内容质量。"
type: docs
weight: 340
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/resizeheightproportionally/
---
## TiffImage.ResizeHeightProportionally method

对图像高度进行比例调整，保持宽高比以确保视觉一致性。使用此方法在应用程序中动态调整图像大小，确保在各种平台和设备上实现最佳显示且不影响内容质量。

```csharp
public override void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 调整的类型。 |

## 示例

此示例加载 TIFF 图像，并使用多种缩放方法按比例调整大小。仅指定高度，宽度会自动计算。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


