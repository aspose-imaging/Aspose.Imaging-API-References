---
title: "OdgImage.Resize"
second_title: "Aspose.Imaging for .NET API 参考"
description: "OdgImage 方法。此方法帮助开发者以编程方式调整图像大小。调用此函数后，可根据应用中的特定需求或约束动态调整图像的尺寸。"
type: docs
weight: 50
url: /zh/net/aspose.imaging.fileformats.opendocument/odgimage/resize/
---
## Resize(int, int, ImageResizeSettings) {#resize_1}

此方法帮助开发者以编程方式调整图像大小。调用此函数后，可根据应用中的特定需求或约束动态调整图像的尺寸。

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
* class [OdgImage](../)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

此方法通过对宽度、高度和缩放类型参数的精确控制来实现图像大小调整。您可以指定所需尺寸，并从不同的缩放算法或类型中选择，以根据应用需求获得最佳效果。

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 缩放类型。 |

## 示例

此示例加载多页 ODG 图像并使用各种缩放方法调整大小。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [OdgImage](../)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage/)
* assembly [Aspose.Imaging](../../../)


