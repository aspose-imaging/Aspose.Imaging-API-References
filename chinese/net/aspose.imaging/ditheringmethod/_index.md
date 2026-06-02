---
title: "枚举 DitheringMethod"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.DitheringMethod 枚举。抖动方法"
type: docs
weight: 850
url: /zh/net/aspose.imaging/ditheringmethod/
---
## DitheringMethod enumeration

抖动方法。

```csharp
public enum DitheringMethod
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| ThresholdDithering | `0` | 阈值抖动。最简单且最快的抖动算法。 |
| FloydSteinbergDithering | `1` | Floyd-Steinberg 抖动。更复杂的抖动算法，使用最近邻强度值。 |

## 示例

以下示例加载栅格图像，并使用不同的调色板深度执行阈值和 Floyd 抖动。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 使用包含 16 种颜色的 4 位颜色调色板执行阈值抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，当前仅支持 1 位、4 位和 8 位调色板。
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.Save(dir + "sample.ThresholdDithering4.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 使用仅包含黑白两色的 1 位颜色调色板执行 Floyd 抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，当前仅支持 1 位、4 位和 8 位调色板。
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.Save(dir + "sample.FloydSteinbergDithering1.png");
}
```

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


