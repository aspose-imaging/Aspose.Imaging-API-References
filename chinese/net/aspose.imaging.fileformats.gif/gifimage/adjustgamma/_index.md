---
title: "GifImage.AdjustGamma"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。通过应用伽马校正来提升图像质量。此方法调整图像的颜色伽马，以实现最佳视觉清晰度。它修改每个像素的伽马值，从而改善颜色呈现和整体图像外观。"
type: docs
weight: 230
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

通过应用伽马校正提升图像质量。此方法调整图像的颜色伽马以获得最佳视觉清晰度。它修改每个像素的伽马值，从而改善颜色呈现和整体图像外观。

```csharp
public override void AdjustGamma(float gamma)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gamma | 单精度 | 红、绿、蓝通道的伽马系数 |

## 示例

以下示例对 GIF 图像执行伽马校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 设置红、绿、蓝通道的伽马系数。
    gifImage.AdjustGamma(2.5f);
    gifImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

图像的伽马校正对像素值进行非线性调整，根据红、绿、蓝通道的指定系数增强或降低亮度。此方法有助于微调图像的色彩平衡和亮度，提升整体外观和视觉质量。

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gammaRed | 单精度 | 红色通道的伽马系数 |
| gammaGreen | 单精度 | 绿色通道的伽马系数 |
| gammaBlue | 单精度 | 蓝色通道的伽马系数 |

## 示例

以下示例对 GIF 图像执行伽马校正，针对颜色分量应用不同的系数。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 为红、绿、蓝通道设置各自的伽马系数。
    gifImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


