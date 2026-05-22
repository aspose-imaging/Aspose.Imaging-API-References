---
title: "WebPImage.Resize"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WebPImage 方法。调整图像尺寸，同时保持宽高比。将此方法集成到您的图像处理工作流中，动态缩放图像以满足各种显示或存储需求。"
type: docs
weight: 230
url: /zh/net/aspose.imaging.fileformats.webp/webpimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

调整图像大小，同时保持宽高比。将此方法集成到图像处理工作流，以动态缩放图像以适应各种显示或存储需求。

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 缩放类型。 |

## 示例

此示例加载一个 WEBP 图像，并使用多种缩放方法对其进行大小调整。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

根据指定设置调整图像大小，实现对尺寸、宽高比和缩放行为的精确控制。将此方法集成到图像处理工作流，以实现针对应用程序特定需求的自定义缩放操作。

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| 设置 | ImageResizeSettings | 缩放设置。 |

### 另请参见

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


