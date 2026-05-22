---
title: "TiffImage.ResizeWidthProportionally"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。调整图像的宽度，同时保持其宽高比，确保比例缩放以获得最佳视觉呈现。使用此方法可在应用程序中动态缩放图像，促进在各种显示环境下实现一致且美观的渲染。"
type: docs
weight: 360
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/resizewidthproportionally/
---
## TiffImage.ResizeWidthProportionally method

在保持宽高比的前提下调整图像宽度，确保比例缩放以获得最佳视觉呈现。利用此方法在应用程序中动态缩放图像，实现跨各种显示环境的一致且美观的渲染。

```csharp
public override void ResizeWidthProportionally(int newWidth, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| resizeType | ResizeType | 调整的类型。 |

## 示例

此示例加载 TIFF 图像并使用多种缩放方法按比例调整大小。仅指定宽度，高度会自动计算。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


