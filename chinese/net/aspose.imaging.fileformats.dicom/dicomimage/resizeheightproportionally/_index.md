---
title: "DicomImage.ResizeHeightProportionally"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。使用此用户友好的方法在保持宽高比的同时调整图像高度。对于希望在动态调整图像大小时保持比例、确保在应用程序中实现最佳显示和可用性的开发者而言，这非常适合。"
type: docs
weight: 250
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/resizeheightproportionally/
---
## DicomImage.ResizeHeightProportionally method

使用此用户友好的方法在保持宽高比的同时调整图像高度。非常适合希望在动态调整图像大小时保持比例的开发者，确保在其应用中实现最佳显示和可用性。

```csharp
public override void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 调整的类型。 |

## 示例

此示例加载 DICOM 图像，并使用多种缩放方法按比例调整大小。仅指定高度，宽度会自动计算。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
        
    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
        
    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


