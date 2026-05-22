---
title: "TiffImage.BinarizeFixed"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。使用预定义阈值对图像进行二值化，将其转换为前景和背景区域明确的二进制图像。将此方法整合到您的图像处理工作流中，以促进分割和特征提取任务，提高应用程序中图像分析的准确性和效率。"
type: docs
weight: 210
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/binarizefixed/
---
## TiffImage.BinarizeFixed method

使用预定义阈值对图像进行二值化，将其转换为前景与背景区域明确的二值图像。将此方法纳入图像处理工作流，以促进分割和特征提取任务，提高图像分析的准确性和效率。

```csharp
public override void BinarizeFixed(byte threshold)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | Byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为255，否则为0。 |

## 示例

以下示例使用预定义阈值对 TIFF 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 使用阈值 127 对图像进行二值化。
    // 如果像素的对应灰度值大于 127，则赋值为255，否则为0。
    tiffImage.BinarizeFixed(127);
    tiffImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


