---
title: "DjvuImage.Dither"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 方法。Dither 功能为图像应用抖动效果，通过降低条纹并改善颜色过渡来提升视觉质量。无论是从事数字艺术、摄影还是平面设计项目，此特性都为图像增添专业感，使其看起来更平滑、更精致。"
type: docs
weight: 230
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/dither/
---
## DjvuImage.Dither method

\"Dither\"功能对图像应用抖动效果，通过降低条带现象和改善色彩过渡来提升视觉质量。无论您从事数字艺术、摄影还是平面设计项目，此功能都能为图像增添专业感，使其看起来更平滑、更精致。

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

以下示例加载 DJVU 图像，并使用不同的调色板深度执行阈值和 Floyd 抖动。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage dicomImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 使用包含 16 种颜色的 4 位颜色调色板执行阈值抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，当前仅支持 1 位、4 位和 8 位调色板。
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage dicomImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 使用仅包含黑白两色的 1 位颜色调色板执行 Floyd 抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，当前仅支持 1 位、4 位和 8 位调色板。
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.Save(dir + "sample.FloydSteinbergDithering1.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [DitheringMethod](../../../aspose.imaging/ditheringmethod/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


