---
title: "WmfImage.Resize"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WmfImage 方法。使用指定的缩放类型调整图像大小，允许在保持宽高比或应用特定缩放算法的同时灵活调整尺寸。将此方法集成到图像处理工作流中，以实现符合您应用程序需求的精确缩放操作。"
type: docs
weight: 150
url: /zh/net/aspose.imaging.fileformats.wmf/wmfimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

使用指定的缩放类型调整图像大小，允许在保持宽高比或应用特定缩放算法的同时灵活调整尺寸。将此方法集成到图像处理工作流中，以实现符合您应用程序需求的精确缩放操作。

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 缩放类型。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| NotImplementedException |  |

## 示例

此示例加载 WMF 图像并使用各种缩放方法调整大小。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.Resize(image.Width * 2, image.Height * 2, Aspose.Imaging.ResizeType.BilinearResample);
}

using (Aspose.Imaging.FileFormats.Wmf.WmfImage image = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "sample.wmf"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [WmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../wmfimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

根据指定设置调整图像尺寸，实现对尺寸、宽高比和缩放行为的精确控制。将此方法集成到图像处理工作流中，以实现符合您应用程序特定需求的自定义缩放操作。

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| 设置 | ImageResizeSettings | 缩放设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| NotImplementedException |  |

### 另请参见

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [WmfImage](../)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../wmfimage/)
* assembly [Aspose.Imaging](../../../)


