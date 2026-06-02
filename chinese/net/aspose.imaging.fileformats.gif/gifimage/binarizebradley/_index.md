---
title: "GifImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。使用 Bradley 自适应阈值算法（基于积分图像阈值）对图像进行二值化，是将灰度图像转换为二进制图像的方法。该算法根据指定窗口内周围像素的平均强度为每个像素计算局部阈值。通过根据局部像素强度自适应调整阈值，Bradley 方法能够有效处理图像中光照和对比度的变化。"
type: docs
weight: 240
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/binarizebradley/
---
## GifImage.BinarizeBradley method

使用 Bradley 自适应阈值算法结合积分图阈值化对图像进行二值化，是将灰度图像转换为二值图像的方法。该算法根据指定窗口内周围像素的平均强度为每个像素计算局部阈值。通过根据局部像素强度自适应地调整阈值，Bradley 方法能够有效处理图像中的光照和对比度变化。

```csharp
public override void BinarizeBradley(double brightnessDifference)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | Double | 像素与围绕该像素中心的 s × s 窗口像素平均值之间的亮度差。 |

### 另请参见

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


