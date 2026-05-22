---
title: "DicomImage.BinarizeOtsu"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。应用 Otsu 阈值化自动对图像进行二值化，根据图像直方图自动确定最佳阈值。对于希望以最少人工干预将图像分割为前景和背景区域的开发者而言，是可靠的方法。"
type: docs
weight: 160
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/binarizeotsu/
---
## DicomImage.BinarizeOtsu method

应用 Otsu 阈值法对图像进行二值化，自动根据图像直方图确定最佳阈值。非常适合希望以最少人工干预将图像分割为前景和背景区域的开发者。

```csharp
public override void BinarizeOtsu()
```

## 示例

以下示例使用 Otsu 阈值化对 DICOM 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // 使用 Otsu 阈值化对图像进行二值化。
    dicomImage.BinarizeOtsu();
    dicomImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


