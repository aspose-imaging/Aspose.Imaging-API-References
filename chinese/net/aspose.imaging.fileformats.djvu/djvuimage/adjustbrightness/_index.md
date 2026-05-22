---
title: "DjvuImage.AdjustBrightness"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage method. 此方法使用指定参数调整图像亮度，提供对亮度水平的控制，以获得最佳视觉清晰度。该方法可以增强或降低图像的整体亮度，允许进行细微调节以实现所需的光照效果。通过调节亮度，用户可以优化图像可见性并提升细节再现，从而改善观看体验。"
type: docs
weight: 150
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/adjustbrightness/
---
## DjvuImage.AdjustBrightness method

使用指定参数调整图像的 *brightness*，提供对亮度水平的控制以获得最佳视觉清晰度。此方法可以增强或降低图像的整体亮度，允许进行细微调整以实现所需的光照效果。通过调节亮度，用户可以优化图像可见性并提升细节再现，从而改善观看体验。

```csharp
public override void AdjustBrightness(int brightness)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | Int32 | 亮度值。 |

## 示例

以下示例对 DJVU 图像执行亮度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 设置亮度值。亮度的接受范围为 [-255, 255]。
    djvuImage.AdjustBrightness(50);
    djvuImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


