---
title: "DicomImage.AdjustGamma"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。通过伽马校正提升图像质量并进行调整，这是一种用于微调视觉外观的强大技术。非常适合希望优化图像呈现、调整色彩平衡并确保在不同设备和环境中实现一致渲染的开发者。"
type: docs
weight: 130
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

通过伽马校正提升图像质量并进行调整，这是一种用于细调视觉外观的强大技术。非常适合旨在优化图像呈现、调整色彩平衡并确保在不同设备和环境中实现一致渲染的开发者。

```csharp
public override void AdjustGamma(float gamma)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gamma | 单精度 | 红、绿、蓝通道的伽马系数 |

## 示例

以下示例对 DICOM 图像执行伽马校正。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // 设置红、绿、蓝通道的伽马系数。
    dicomImage.AdjustGamma(2.5f);
    dicomImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

通过对图像的红、绿、蓝分量独立应用伽马校正，实现精确的颜色调整。此方法确保准确的色彩平衡和最佳的视觉输出，满足寻求对图像渲染和颜色精度进行细粒度控制的开发者需求。

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gammaRed | 单精度 | 红色通道的伽马系数 |
| gammaGreen | 单精度 | 绿色通道的伽马系数 |
| gammaBlue | 单精度 | 蓝色通道的伽马系数 |

## 示例

以下示例对 DICOM 图像执行伽马校正，并为颜色分量应用不同的系数。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // 为红、绿、蓝通道设置各自的伽马系数。
    dicomImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


