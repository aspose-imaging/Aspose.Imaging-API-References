---
title: "TiffImage.Dither"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。对当前图像执行抖动处理，以提升视觉质量并减少颜色带状伪影。将此方法整合到您的图像处理工作流中，确保颜色之间的平滑过渡，从而改善整体图像外观和清晰度。"
type: docs
weight: 240
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/dither/
---
## TiffImage.Dither method

对当前图像执行抖动处理，以提升视觉质量并减少颜色条带伪影。将此方法纳入图像处理工作流，确保颜色过渡更平滑，提升整体图像外观和清晰度。

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

以下示例加载 TIFF 图像，并使用不同的调色板深度执行阈值和 Floyd 抖动。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 使用包含 16 种颜色的 4 位颜色调色板执行阈值抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，当前仅支持 1 位、4 位和 8 位调色板。
    tiffImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 使用仅包含黑白两色的 1 位颜色调色板执行 Floyd 抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，当前仅支持 1 位、4 位和 8 位调色板。
    tiffImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


