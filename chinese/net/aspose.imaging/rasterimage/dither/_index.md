---
title: "RasterImage.Dither"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。对当前图像执行抖动处理"
type: docs
weight: 280
url: /zh/net/aspose.imaging/rasterimage/dither/
---
## Dither(DitheringMethod, int, IColorPalette) {#dither_1}

对当前图像执行抖动处理。

```csharp
public abstract void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | 抖动方法。 |
| bitsCount | Int32 | 抖动的最终位数。 |
| customPalette | IColorPalette | 用于抖动的自定义调色板。 |

### 另请参见

* enum [DitheringMethod](../../ditheringmethod/)
* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## Dither(DitheringMethod, int) {#dither}

对当前图像执行抖动处理。

```csharp
public void Dither(DitheringMethod ditheringMethod, int bitsCount)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | 抖动方法。 |
| bitsCount | Int32 | 抖动的最终位数。 |

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

* enum [DitheringMethod](../../ditheringmethod/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


