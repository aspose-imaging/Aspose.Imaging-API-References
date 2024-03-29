---
title: Dither
second_title: Aspose.Imaging for .NET API 参考
description: 对当前图像执行抖动
type: docs
weight: 260
url: /zh/net/aspose.imaging/rasterimage/dither/
---
## Dither(DitheringMethod, int, IColorPalette) {#dither_1}

对当前图像执行抖动。

```csharp
public abstract void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | 抖动方法。 |
| bitsCount | Int32 | 最后的比特数用于抖动。 |
| customPalette | IColorPalette | 用于抖动的自定义调色板。 |

### 也可以看看

* enum [DitheringMethod](../../ditheringmethod)
* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* 命名空间 [Aspose.Imaging](../../rasterimage)
* 部件 [Aspose.Imaging](../../../)

---

## Dither(DitheringMethod, int) {#dither}

对当前图像执行抖动。

```csharp
public void Dither(DitheringMethod ditheringMethod, int bitsCount)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | 抖动方法。 |
| bitsCount | Int32 | 最后的比特数用于抖动。 |

### 例子

以下示例加载光栅图像并使用不同的调色板深度执行阈值和弗洛伊德抖动。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 使用包含 16 种颜色的 4 位调色板执行阈值抖动。
    // 指定的位数越多，输出图像的质量越高，尺寸越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.Save(dir + "sample.ThresholdDithering4.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 使用仅包含 2 种颜色（黑色和白色）的 1 位调色板执行弗洛伊德抖动。
    // 指定的位数越多，输出图像的质量越高，尺寸越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.Save(dir + "sample.FloydSteinbergDithering1.png");
}
```

### 也可以看看

* enum [DitheringMethod](../../ditheringmethod)
* class [RasterImage](../../rasterimage)
* 命名空间 [Aspose.Imaging](../../rasterimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
