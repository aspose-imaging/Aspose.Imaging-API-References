---
title: "DjvuImage.AdjustContrast"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage method. 此方法可增强图像对比度，以提升视觉清晰度并突出细节，调整亮部与暗部之间的亮度差异。通过微调对比度水平，用户可以获得更鲜明、更有冲击力的图像，提升整体图像质量并最大化细节可见性。此调整有助于展现色彩和纹理的细微差别，使图像更具动感和视觉吸引力。"
type: docs
weight: 160
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/adjustcontrast/
---
## DjvuImage.AdjustContrast method

使用此方法增强[`Image`](../../../aspose.imaging/image/) 对比度，以提升视觉清晰度并突出细节，该方法会调整亮部与暗部之间的亮度差异。通过微调对比度水平，用户可以获得更鲜明、更有冲击力的图像，提升整体图像质量并最大化细节可见性。此调整有助于展现色彩和纹理的细微差别，使图像更具动感和视觉吸引力。

```csharp
public override void AdjustContrast(float contrast)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contrast | 单精度 | 对比度值（范围为 [-100; 100]） |

## 示例

以下示例对 DJVU 图像执行对比度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 设置对比度值。对比度的接受范围为 [-100f, 100f]。
    djvuImage.AdjustContrast(50f);
    djvuImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


