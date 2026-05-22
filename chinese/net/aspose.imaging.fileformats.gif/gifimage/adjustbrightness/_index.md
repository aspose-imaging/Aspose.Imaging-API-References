---
title: "GifImage.AdjustBrightness"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。根据指定的亮度参数调整图像的亮度。此方法统一地修改整幅图像的亮度，增强或降低整体光照，以实现所需效果。"
type: docs
weight: 210
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/adjustbrightness/
---
## GifImage.AdjustBrightness method

根据指定的 *brightness* 参数调整图像的亮度。此方法统一地修改整幅图像的亮度，增强或降低整体光照以实现所需效果。

```csharp
public override void AdjustBrightness(int brightness)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | Int32 | 亮度值。 |

## 示例

以下示例对 GIF 图像执行亮度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 设置亮度值。亮度的接受范围为 [-255, 255]。
    gifImage.AdjustBrightness(50);
    gifImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


