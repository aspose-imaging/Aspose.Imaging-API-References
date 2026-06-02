---
title: "TiffImage.BinarizeOtsu"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。利用 Otsu 阈值法对图像进行二值化，自动根据图像直方图确定最佳阈值。将此方法集成到图像处理工作流中，以实现有效的分割和特征提取，提升应用程序内图像分析任务的准确性和可靠性。"
type: docs
weight: 220
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu/
---
## TiffImage.BinarizeOtsu method

利用 Otsu 阈值法对图像进行二值化，自动依据图像直方图确定最佳阈值。将此方法集成到图像处理工作流中，实现有效的分割和特征提取，提升图像分析任务的准确性和可靠性。

```csharp
public override void BinarizeOtsu()
```

## 示例

以下示例使用 Otsu 阈值法对 TIFF 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 使用 Otsu 阈值化对图像进行二值化。
    tiffImage.BinarizeOtsu();
    tiffImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


