---
title: "DicomImage.AdjustContrast"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。使用此用户友好方法提升图像对比度，该方法调节明暗区域的差异。轻松改善视觉清晰度和细节，为开发者提供直观的对比度控制，以实现最佳渲染。"
type: docs
weight: 120
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/adjustcontrast/
---
## DicomImage.AdjustContrast method

使用此用户友好方法增强[`Image`](../../../aspose.imaging/image/)的对比度，该方法调节明暗区域的差异。轻松提升视觉清晰度和细节，为开发者提供直观的对比度控制，以实现最佳渲染。

```csharp
public override void AdjustContrast(float contrast)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contrast | 单精度 | 对比度值（范围为 [-100; 100]） |

## 示例

以下示例对 DICOM 图像执行对比度校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // 设置对比度值。对比度的接受范围为 [-100f, 100f]。
    dicomImage.AdjustContrast(50f);
    dicomImage.Save(dir + "sample.AdjustContrast.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


