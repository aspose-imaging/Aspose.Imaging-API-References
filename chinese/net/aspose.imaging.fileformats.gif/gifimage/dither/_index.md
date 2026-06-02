---
title: "GifImage.Dither"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。对当前图像应用抖动。此过程通过减少颜色条带并改善颜色过渡来提升图像质量，从而获得更平滑的外观"
type: docs
weight: 290
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/dither/
---
## GifImage.Dither method

对当前图像应用抖动处理。此过程通过减少颜色带状现象并改善颜色过渡来提升图像质量，使外观更平滑。

```csharp
public override void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | 抖动方法。 |
| bitsCount | Int32 | 抖动的最终位数。 |
| customPalette | IColorPalette | 用于抖动的自定义调色板。 |

## 示例

以下示例加载 GIF 图像，并使用不同的调色板深度执行阈值和 Floyd 抖动。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 使用包含 16 种颜色的 4 位颜色调色板执行阈值抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，当前仅支持 1 位、4 位和 8 位调色板。
    gifImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 使用仅包含黑白两色的 1 位颜色调色板执行 Floyd 抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，当前仅支持 1 位、4 位和 8 位调色板。
    gifImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


