---
title: "DicomImage.AdjustBrightness"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。通过调节亮度来增强图像亮度的参数化方法，使开发者能够精细调节图像的光度。此用户友好功能让开发者轻松操作图像亮度，提供灵活性和对视觉美感的控制。"
type: docs
weight: 110
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/adjustbrightness/
---
## DicomImage.AdjustBrightness method

通过调整 *brightness*（亮度）来增强图像亮度，这是一种参数化方法，允许开发者精细调节图像的光度。此用户友好功能使开发者能够无缝操作图像亮度，提供对视觉美感的灵活性和控制。

```csharp
public override void AdjustBrightness(int brightness)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| brightness | Int32 | 亮度值。 |

## 示例

以下示例对 DICOM 图像执行亮度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // 设置亮度值。亮度的接受范围为 [-255, 255]。
    dicomImage.AdjustBrightness(50);
    dicomImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


