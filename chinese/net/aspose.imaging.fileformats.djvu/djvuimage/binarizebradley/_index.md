---
title: "DjvuImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 方法。使用 Bradley 的自适应阈值算法结合积分图阈值进行二值化，这是一种基于局部邻域为每个像素计算局部阈值的方法。它能够适应图像中光照的变化，适用于光照不均匀的图像。通过使用积分图计算阈值，可高效处理大邻域，使其适用于实时应用。该技术常用于文档处理、OCR（光学字符识别）和图像分割任务，因为准确的二值化对后续分析至关重要。"
type: docs
weight: 180
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/binarizebradley/
---
## DjvuImage.BinarizeBradley method

使用 Bradley 自适应阈值算法结合积分图阈值的二值化方法会根据局部邻域为每个像素计算局部阈值。它能够适应图像中光照的变化，适用于光照不均的图像。通过使用积分图计算阈值，可高效处理大范围邻域，使其适用于实时应用。该技术常用于文档处理、OCR（光学字符识别）和图像分割任务，在这些场景中准确的二值化对后续分析至关重要。

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | Double | 像素与围绕该像素中心的 s × s 窗口像素平均值之间的亮度差。 |
| windowSize | Int32 | 围绕该像素中心的 s × s 窗口像素的大小。 |

## 示例

以下示例使用指定窗口大小的 Bradley 自适应阈值算法对 DJVU 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 使用亮度差为 5 对图像进行二值化。亮度是指像素与以该像素为中心的 10×10 窗口像素平均值之间的差异。
    djvuImage.BinarizeBradley(5, 10);
    djvuImage.Save(dir + "sample.BinarizeBradley5_10x10.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


