---
title: "DicomImage.Resize"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。使用此直接的方法调整图像尺寸。对于希望动态调整图像大小、确保其在应用程序的各种场景和布局中无缝适配的开发者而言，这是理想的选择。"
type: docs
weight: 240
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

使用此直接的方法调整图像尺寸。非常适合希望动态调整图像大小，使其在应用程序的各种上下文和布局中无缝适配的开发者。

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 缩放类型。 |

## 示例

此示例加载 DICOM 图像，并使用多种缩放方法调整大小。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
        
    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
        
    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

使用此简单的调整大小方法调整图像尺寸。无论是需要缩小还是放大图像，此函数都能高效、准确地满足您的调整需求，使其成为寻求快速简便图像尺寸调整的开发者的理想选择。

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| 设置 | ImageResizeSettings | 缩放设置。 |

## 示例

此示例加载 DICOM 图像，并使用多种缩放设置进行调整。

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

using (Aspose.Imaging.Image image = (Aspose.Imaging.Image)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // 使用自适应重采样将尺寸缩小两倍。
    dicomImage.Resize(image.Width / 2, image.Height / 2, resizeSettings);

    // 保存为 PNG
    dicomImage.Save(dir + "downsample.adaptive.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


