---
title: "RasterImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。使用Bradley自适应阈值算法和积分图阈值对图像进行二值化"
type: docs
weight: 240
url: /zh/net/aspose.imaging/rasterimage/binarizebradley/
---
## BinarizeBradley(double, int) {#binarizebradley_1}

使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化

```csharp
public virtual void BinarizeBradley(double brightnessDifference, int windowSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | Double | 像素与围绕该像素中心的 s × s 窗口像素平均值之间的亮度差。 |
| windowSize | Int32 | 围绕该像素中心的 s × s 窗口像素的大小。 |

## 示例

以下示例使用指定窗口大小的Bradley自适应阈值算法对光栅图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 使用亮度差为 5 对图像进行二值化。亮度是指像素与以该像素为中心的 10×10 窗口像素平均值之间的差异。
    rasterImage.BinarizeBradley(5, 10);
    rasterImage.Save(dir + "sample.BinarizeBradley5_10x10.png");
}
```

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## BinarizeBradley(double) {#binarizebradley}

使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化

```csharp
public virtual void BinarizeBradley(double brightnessDifference)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | Double | 像素与围绕该像素中心的 s × s 窗口像素平均值之间的亮度差。 |

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


