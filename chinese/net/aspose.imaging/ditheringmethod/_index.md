---
title: DitheringMethod
second_title: Aspose.Imaging for .NET API 参考
description: 抖动方法
type: docs
weight: 840
url: /zh/net/aspose.imaging/ditheringmethod/
---
## DitheringMethod enumeration

抖动方法。

```csharp
public enum DitheringMethod
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| ThresholdDithering | `0` | 阈值抖动。最简单最快的抖动算法。 |
| FloydSteinbergDithering | `1` | Floyd-Steinberg 抖动。一种更复杂的抖动算法，使用最近邻强度值。 |

### 例子

以下示例加载光栅图像并使用不同的调色板深度执行阈值和弗洛伊德抖动。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 使用包含 16 种颜色的 4 位调色板执行阈值抖动。
           // 指定的位数越多，输出图像的质量和尺寸就越大。
           // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.Save(dir + "sample.ThresholdDithering4.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

        // 使用仅包含 2 种颜色的 1 位调色板执行弗洛伊德抖动 - 黑色和白色。
           // 指定的位数越多，输出图像的质量和尺寸就越大。
           // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.Save(dir + "sample.FloydSteinbergDithering1.png");
}
```

### 也可以看看

* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->