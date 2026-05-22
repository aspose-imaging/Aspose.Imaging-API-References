---
title: "DicomImage.Dither"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。使用此简便方法通过抖动效果增强当前图像。非常适合希望为图像添加纹理和深度、提升视觉质量和整体吸引力的开发者。"
type: docs
weight: 190
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/dither/
---
## DicomImage.Dither method

使用此简便方法对当前图像应用抖动效果以进行增强。非常适合希望为图像添加纹理和深度、提升视觉质量和整体吸引力的开发者。

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

以下示例加载 DICOM 图像，并使用不同的调色板深度执行阈值抖动和 Floyd 抖动。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // 使用包含 16 种颜色的 4 位颜色调色板执行阈值抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，当前仅支持 1 位、4 位和 8 位调色板。
    dicomImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.Save(dir + "sample.ThresholdDithering4.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

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
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


