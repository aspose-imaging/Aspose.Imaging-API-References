---
title: "DjvuImage.ResizeWidthProportionally"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 方法。ResizeWidthProportionally 方法提供了一种便捷的解决方案，可在保持宽高比的同时调整图像的宽度。通过按比例调整宽度，您可以确保图像在不同设备和屏幕尺寸上保持视觉吸引力和一致性，从而提升其在各种场景中的多功能性和可用性。"
type: docs
weight: 280
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/resizewidthproportionally/
---
## DjvuImage.ResizeWidthProportionally method

`ResizeWidthProportionally` 方法提供了一种便捷的解决方案，在保持宽高比的同时调整图像宽度。通过按比例调整宽度，您可以确保图像在不同设备和屏幕尺寸上保持视觉吸引力和一致性，提升其在各种场景中的多样性和可用性。

```csharp
public override void ResizeWidthProportionally(int newWidth, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| resizeType | ResizeType | 调整的类型。 |

## 示例

此示例加载 DJVU 图像并使用各种缩放方法按比例调整其大小。仅指定宽度，自动计算高度。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


