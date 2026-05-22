---
title: "TiffImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化。该方法根据图像邻域动态计算局部阈值，提升对不同光照条件的适应性，并确保在应用程序中后续处理任务的稳健分割。"
type: docs
weight: 200
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/binarizebradley/
---
## TiffImage.BinarizeBradley method

在图像上实现二值化，采用 Bradley 自适应阈值算法结合积分图阈值。该方法根据图像邻域动态计算局部阈值，提升对不同光照条件的适应性，并确保后续处理任务的稳健分割。

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | Double | 像素与围绕该像素中心的 s × s 窗口像素平均值之间的亮度差。 |
| windowSize | Int32 | 围绕该像素中心的 s × s 窗口像素的大小。 |

## 示例

以下示例使用指定窗口大小的 Bradley 自适应阈值算法对 TIFF 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 使用亮度差为 5 对图像进行二值化。亮度是指像素与以该像素为中心的 10×10 窗口像素平均值之间的差异。
    tiffImage.BinarizeBradley(5, 10);
    tiffImage.Save(dir + "sample.BinarizeBradley5_10x10.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


