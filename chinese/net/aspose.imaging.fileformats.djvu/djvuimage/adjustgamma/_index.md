---
title: "DjvuImage.AdjustGamma"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 方法。针对红、绿、蓝通道的伽马校正涉及分别调整每个颜色分量的亮度。通过对 RGB 通道应用不同的伽马系数，您可以微调图像的整体亮度和对比度。此技术确保颜色表现准确，并提升图像在不同显示设备上的视觉质量。"
type: docs
weight: 170
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

伽马校正，特别针对红、绿、蓝通道，涉及分别调整每个颜色分量的亮度。通过对 RGB 通道应用不同的伽马系数，您可以微调图像的整体亮度和对比度。此技术确保颜色表现准确，并提升图像在不同显示设备上的视觉质量。

```csharp
public override void AdjustGamma(float gamma)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gamma | 单精度 | 红、绿、蓝通道的伽马系数 |

## 示例

以下示例对 DJVU 图像执行伽马校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 设置红、绿、蓝通道的伽马系数。
    djvuImage.AdjustGamma(2.5f);
    djvuImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

对图像进行伽马校正时，可为红、绿、蓝通道设置可自定义的参数，从而实现对色彩平衡和亮度的精确调节。此方法通过微调颜色表现提升图像质量，确保在不同显示设备上的最佳渲染。对各通道的伽马值进行调整可改善色彩平衡和视觉吸引力。

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gammaRed | 单精度 | 红色通道的伽马系数 |
| gammaGreen | 单精度 | 绿色通道的伽马系数 |
| gammaBlue | 单精度 | 蓝色通道的伽马系数 |

## 示例

以下示例对 DJVU 图像执行伽马校正，并对颜色分量使用不同的系数。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 为红、绿、蓝通道设置各自的伽马系数。
    djvuImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


