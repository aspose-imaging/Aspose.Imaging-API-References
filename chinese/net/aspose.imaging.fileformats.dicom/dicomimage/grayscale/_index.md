---
title: "DicomImage.Grayscale"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。轻松将图像转换为灰度表示，简化视觉分析和处理任务。对于希望提升图像清晰度、降低复杂度并在各种应用中实现高效基于灰度的算法的开发者而言，是完美的选择。"
type: docs
weight: 210
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/grayscale/
---
## DicomImage.Grayscale method

轻松将图像转换为灰度表示，简化视觉分析和处理任务。非常适合希望提升图像清晰度、降低复杂度并促进高效基于灰度的算法在各种应用中使用的开发者。

```csharp
public override void Grayscale()
```

## 示例

以下示例将彩色 DICOM 图像转换为灰度表示。灰度图像仅由灰色阴影组成，仅携带强度信息。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    dicomImage.Grayscale();
    dicomImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


