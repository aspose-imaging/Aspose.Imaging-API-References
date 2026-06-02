---
title: "TiffImage.AdjustContrast"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。增强 Image 实例的对比度，放大其明暗区域之间的差异。集成此功能可提升图像的视觉清晰度和整体质量。"
type: docs
weight: 170
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/adjustcontrast/
---
## TiffImage.AdjustContrast method

增强 [`Image`](../../../aspose.imaging/image/) 实例的对比度，放大其明暗区域之间的差异。集成此功能可提升图像的视觉清晰度和整体质量。

```csharp
public override void AdjustContrast(float contrast)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contrast | 单精度 | 对比度值（范围为 [-100; 100]） |

## 示例

以下示例执行 TIFF 图像的对比度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 设置对比度值。对比度的接受范围为 [-100f, 100f]。
    tiffImage.AdjustContrast(50f);
    tiffImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


