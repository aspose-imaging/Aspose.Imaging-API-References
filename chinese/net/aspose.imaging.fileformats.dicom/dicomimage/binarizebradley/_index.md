---
title: "DicomImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。使用 Bradley 自适应阈值算法对图像进行二值化，利用积分图阈值实现更高性能。非常适合希望根据局部亮度变化自动分割图像，以确保在不同光照条件下实现准确的目标检测和提取的开发者。"
type: docs
weight: 140
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/binarizebradley/
---
## DicomImage.BinarizeBradley method

使用 Bradley 自适应阈值算法进行图像二值化，利用积分图阈值提升性能。适用于希望根据局部亮度变化自动分割图像的开发者，确保在不同光照条件下实现准确的目标检测和提取。

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | Double | 像素与围绕该像素中心的 s × s 窗口像素平均值之间的亮度差。 |
| windowSize | Int32 | 围绕该像素中心的 s × s 窗口像素的大小。 |

## 示例

以下示例使用 Bradley 自适应阈值算法和指定的窗口大小对 DICOM 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // 使用亮度差为 5 对图像进行二值化。亮度是指像素与以该像素为中心的 10×10 窗口像素平均值之间的差异。
    dicomImage.BinarizeBradley(5, 10);
    dicomImage.Save(dir + "sample.BinarizeBradley5_10x10.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


