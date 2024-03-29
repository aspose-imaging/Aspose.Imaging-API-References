---
title: AdjustGamma
second_title: Aspose.Imaging for .NET API 参考
description: 图像的 Gamma 校正
type: docs
weight: 190
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

图像的 Gamma 校正。

```csharp
public override void AdjustGamma(float gamma)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| gamma | Single | 红色、绿色和蓝色通道系数的 Gamma |

### 例子

以下示例执行 TIFF 图像的伽马校正。

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

### 也可以看看

* class [TiffImage](../../tiffimage)
* 命名空间 [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* 部件 [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

图像的 Gamma 校正。

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| gammaRed | Single | 红色通道系数的 Gamma |
| gammaGreen | Single | 绿色通道系数的 Gamma |
| gammaBlue | Single | 蓝色通道系数的 Gamma |

### 例子

以下示例对 TIFF 图像执行伽马校正，并对颜色分量应用不同的系数。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 为红色、绿色和蓝色通道设置单独的伽马系数。
    tiffImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 也可以看看

* class [TiffImage](../../tiffimage)
* 命名空间 [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
