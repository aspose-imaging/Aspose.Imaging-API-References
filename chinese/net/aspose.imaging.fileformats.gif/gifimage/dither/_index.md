---
title: Dither
second_title: Aspose.Imaging for .NET API 参考
description: 对当前图像执行抖动
type: docs
weight: 310
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/dither/
---
## GifImage.Dither method

对当前图像执行抖动。

```csharp
public override void Dither(DitheringMethod ditheringMethod, int bitsCount, 
    IColorPalette customPalette)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ditheringMethod | DitheringMethod | 抖动方法。 |
| bitsCount | Int32 | 最后的比特数用于抖动。 |
| customPalette | IColorPalette | 用于抖动的自定义调色板。 |

### 例子

以下示例加载 GIF 图像并使用不同的调色板深度执行阈值和弗洛伊德抖动。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 使用包含 16 种颜色的 4 位调色板执行阈值抖动。
    // 指定的位数越多，输出图像的质量越高，尺寸越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    gifImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // 使用仅包含 2 种颜色（黑色和白色）的 1 位调色板执行弗洛伊德抖动。
    // 指定的位数越多，输出图像的质量越高，尺寸越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    gifImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 也可以看看

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* 命名空间 [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
