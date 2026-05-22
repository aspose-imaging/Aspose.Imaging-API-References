---
title: "DjvuImage.BinarizeOtsu"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 方法。使用 Otsu 阈值化的二值化是一种技术，它基于图像直方图自动计算最佳阈值。它通过最小化类内方差将图像分为前景和背景。Otsu 方法在将图像分割为二进制形式时被广泛使用，特别是当像素强度分布呈双峰或多峰时。此方法对诸如目标检测、图像分割和特征提取等任务有益，因为在前景与背景之间的准确划分至关重要。"
type: docs
weight: 200
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/binarizeotsu/
---
## DjvuImage.BinarizeOtsu method

使用 Otsu 阈值的二值化是一种基于图像直方图自动计算最佳阈值的技术。它通过最小化类内方差将图像划分为前景和背景。Otsu 方法在将图像分割为二进制形式时被广泛使用，尤其在像素强度分布呈双峰或多峰时。该方法对目标检测、图像分割和特征提取等任务有益，因为在这些任务中前景与背景的准确划分至关重要。

```csharp
public override void BinarizeOtsu()
```

## 示例

以下示例使用 Otsu 阈值化对 DJVU 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 使用 Otsu 阈值化对图像进行二值化。
    djvuImage.BinarizeOtsu();
    djvuImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


