---
title: BinarizeOtsu
second_title: Aspose.Imaging for .NET API 参考
description: 使用 Otsu 阈值对图像进行二值化
type: docs
weight: 200
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/binarizeotsu/
---
## DjvuImage.BinarizeOtsu method

使用 Otsu 阈值对图像进行二值化

```csharp
public override void BinarizeOtsu()
```

### 例子

使用 Otsu 阈值处理的 DJVU 图像。二值化图像仅包含 2 种颜色 - 黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

        // 使用 Otsu 阈值对图像进行二值化。
    djvuImage.BinarizeOtsu();
    djvuImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 也可以看看

* class [DjvuImage](../../djvuimage)
* 命名空间 [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->