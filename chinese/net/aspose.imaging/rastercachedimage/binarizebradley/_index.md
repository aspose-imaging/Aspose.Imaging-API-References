---
title: "RasterCachedImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterCachedImage 方法。使用 Bradley 的自适应阈值算法和积分图阈值进行图像二值化"
type: docs
weight: 70
url: /zh/net/aspose.imaging/rastercachedimage/binarizebradley/
---
## BinarizeBradley(double, int) {#binarizebradley_1}

使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | Double | 像素与围绕该像素中心的 s × s 窗口像素平均值之间的亮度差。 |
| windowSize | Int32 | 围绕该像素中心的 s × s 窗口像素的大小。 |

## 示例

以下示例使用指定窗口大小的 Bradley 自适应阈值算法对栅格缓存图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // 使用亮度差为 5 对图像进行二值化。
    // 亮度是指像素与以该像素为中心的 10×10 窗口像素平均值之间的差异。
    rasterImage.BinarizeBradley(5, 10);
    rasterImage.Save(dir + "sample.BinarizeBradley5_10x10.png");
}
```

### 另请参见

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)

---

## BinarizeBradley(double) {#binarizebradley}

使用 Bradley 自适应阈值算法和积分图阈值对图像进行二值化

```csharp
public override void BinarizeBradley(double brightnessDifference)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightnessDifference | Double | 像素与围绕该像素中心的 s × s 窗口像素平均值之间的亮度差。 |

## 示例

以下示例使用 Bradley 自适应阈值算法对栅格缓存图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // 使用亮度差为 5 对图像进行二值化。
    // 亮度是指像素与以该像素为中心的 s×s 窗口像素平均值之间的差异。
    // 窗口大小将自动校准。
    rasterImage.BinarizeBradley(5);
    rasterImage.Save(dir + "sample.BinarizeBradley5.png");
}
```

### 另请参见

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


