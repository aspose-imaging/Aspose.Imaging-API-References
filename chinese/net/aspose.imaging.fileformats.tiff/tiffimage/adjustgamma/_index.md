---
title: "TiffImage.AdjustGamma"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。对图像应用伽马校正，调整像素强度以实现所需的色彩平衡。将此方法整合到您的图像处理工作流中，以提升视觉质量并提高后续分析或显示任务的准确性。"
type: docs
weight: 180
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

对图像进行伽马校正，调整像素强度以实现期望的色彩平衡。将此方法纳入图像处理工作流，以提升视觉质量并提高后续分析或显示任务的准确性。

```csharp
public override void AdjustGamma(float gamma)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gamma | 单精度 | 红、绿、蓝通道的伽马系数 |

## 示例

以下示例对 TIFF 图像执行伽马校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 设置红、绿、蓝通道的伽马系数。
    tiffImage.AdjustGamma(2.5f);
    tiffImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

使用红、绿、蓝通道的独立系数对图像进行伽马校正，实现对色彩平衡和对比度的细致调节。将此方法集成到图像处理管线中，以实现对颜色渲染的精确控制并提升视觉保真度。

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gammaRed | 单精度 | 红色通道的伽马系数 |
| gammaGreen | 单精度 | 绿色通道的伽马系数 |
| gammaBlue | 单精度 | 蓝色通道的伽马系数 |

## 示例

以下示例对 TIFF 图像执行伽马校正，并对颜色分量使用不同的系数。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 为红、绿、蓝通道设置各自的伽马系数。
    tiffImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


