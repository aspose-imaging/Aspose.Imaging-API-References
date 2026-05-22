---
title: "WebPImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WebPImage 方法。使用 Bradley 的自适应阈值算法结合积分图进行图像二值化。该方法根据图像邻域动态计算局部阈值，提升对不同光照条件的适应性，并确保在应用程序中后续处理任务的稳健分割。"
type: docs
weight: 120
url: /zh/net/aspose.imaging.fileformats.webp/webpimage/binarizebradley/
---
## WebPImage.BinarizeBradley method

使用 Bradley 的自适应阈值算法结合积分图阈值，对图像进行二值化。此方法根据图像邻域动态计算局部阈值，增强对不同光照条件的适应性，并确保后续处理任务的稳健分割。

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | Double | 像素与围绕该像素中心的 s × s 窗口像素平均值之间的亮度差。 |
| windowSize | Int32 | 围绕该像素中心的 s × s 窗口像素的大小。 |

### 另请参见

* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


