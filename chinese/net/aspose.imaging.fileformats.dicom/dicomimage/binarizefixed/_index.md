---
title: "DicomImage.BinarizeFixed"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。使用此简洁方法通过预定义阈值轻松将图像转换为二值格式。适用于希望通过基于指定强度水平将图像分割为前景和背景组件来简化图像处理任务的开发者。"
type: docs
weight: 150
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/binarizefixed/
---
## DicomImage.BinarizeFixed method

使用此简便方法通过预定义阈值轻松将图像转换为二进制格式。适用于希望通过根据指定强度水平将图像分割为前景和背景来简化图像处理任务的开发者。

```csharp
public override void BinarizeFixed(byte threshold)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | Byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为255，否则为0。 |

## 示例

以下示例使用预定义阈值对 DICOM 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // 使用阈值 127 对图像进行二值化。
    // 如果像素的对应灰度值大于 127，则赋值为255，否则为0。
    dicomImage.BinarizeFixed(127);
    dicomImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


