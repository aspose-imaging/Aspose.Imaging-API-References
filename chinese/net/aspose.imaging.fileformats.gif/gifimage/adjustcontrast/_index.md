---
title: "GifImage.AdjustContrast"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。调整图像的对比度，增强或降低像素之间的亮度差异。此方法修改图像的整体色调范围，使暗部更暗、亮部更亮，以提升视觉清晰度和细节。"
type: docs
weight: 220
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/adjustcontrast/
---
## GifImage.AdjustContrast method

调整图像的对比度，增强或降低像素之间的亮度差异。此方法修改图像的整体色调范围，使暗部更暗、亮部更亮，以提升视觉清晰度和细节。

```csharp
public override void AdjustContrast(float contrast)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contrast | 单精度 | 对比度值（范围为 [-100; 100]） |

### 异常

| 异常 | 条件 |
| --- | --- |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | 无法更改对比度。帧索引: " + frameIndex |

## 示例

以下示例对 GIF 图像执行对比度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 设置对比度值。对比度的接受范围为 [-100f, 100f]。
    gifImage.AdjustContrast(50f);
    gifImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


