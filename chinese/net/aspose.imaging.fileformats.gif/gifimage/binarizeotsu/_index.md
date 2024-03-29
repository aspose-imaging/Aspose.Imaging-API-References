---
title: BinarizeOtsu
second_title: Aspose.Imaging for .NET API 参考
description: 使用 Otsu 阈值对图像进行二值化
type: docs
weight: 280
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/binarizeotsu/
---
## GifImage.BinarizeOtsu method

使用 Otsu 阈值对图像进行二值化

```csharp
public override void BinarizeOtsu()
```

### 例子

以下示例使用 Otsu 阈值对 GIF 图像进行二值化。二值化图像仅包含 2 种颜色 - 黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 使用 Otsu 阈值对图像进行二值化。
    gifImage.BinarizeOtsu();
    gifImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 也可以看看

* class [GifImage](../../gifimage)
* 命名空间 [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
