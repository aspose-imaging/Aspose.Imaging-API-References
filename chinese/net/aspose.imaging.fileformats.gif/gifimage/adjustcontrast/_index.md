---
title: AdjustContrast
second_title: Aspose.Imaging for .NET API 参考
description: 调整对比度
type: docs
weight: 240
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/adjustcontrast/
---
## GifImage.AdjustContrast method

调整对比度。

```csharp
public override void AdjustContrast(float contrast)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| contrast | Single | 对比度值（在 [-100; 100] 范围内） |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception) | 无法更改对比度。帧索引:" + frameIndex |

### 例子

以下示例执行 GIF 图像的对比度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 设置对比度值。可接受的对比度值在 [-100f, 100f].
 范围内
    gifImage.AdjustContrast(50f);
    gifImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 也可以看看

* class [GifImage](../../gifimage)
* 命名空间 [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->