---
title: "TiffImage.AdjustBrightness"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。实现图像的亮度调整，允许修改整体亮度水平。将此方法纳入您的图像处理工作流，以提升可见性并改善应用程序中图像的视觉质量。"
type: docs
weight: 160
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/adjustbrightness/
---
## TiffImage.AdjustBrightness method

实现对图像的 *brightness* 调整，允许修改整体亮度水平。将此方法纳入图像处理工作流，以提升可见性并改善应用程序中图像的视觉质量。

```csharp
public override void AdjustBrightness(int brightness)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | Int32 | 亮度值。 |

## 示例

以下示例执行 TIFF 图像的亮度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 设置亮度值。亮度的接受范围为 [-255, 255]。
    tiffImage.AdjustBrightness(50);
    tiffImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


