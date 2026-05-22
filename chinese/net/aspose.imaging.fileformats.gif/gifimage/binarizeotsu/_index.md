---
title: "GifImage.BinarizeOtsu"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。使用 Otsu 阈值法对图像进行二值化是一种用于自动确定将灰度图像转换为二值图像的最佳阈值的方法。Otsu 阈值算法计算能够最小化前景和背景两类像素强度内部方差的阈值。当最佳阈值未知且需要根据图像直方图自适应确定时，此技术尤为有用。"
type: docs
weight: 260
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/binarizeotsu/
---
## GifImage.BinarizeOtsu method

使用 Otsu 阈值法对图像进行二值化是一种自动确定将灰度图像转换为二值图像的最佳阈值的方法。Otsu 阈值算法计算使前景和背景两类像素强度的类内方差最小的阈值。当最佳阈值未知且需要根据图像直方图自适应确定时，此技术尤为有用。

```csharp
public override void BinarizeOtsu()
```

## 示例

以下示例使用 Otsu 阈值法对 GIF 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 使用 Otsu 阈值化对图像进行二值化。
    gifImage.BinarizeOtsu();
    gifImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


