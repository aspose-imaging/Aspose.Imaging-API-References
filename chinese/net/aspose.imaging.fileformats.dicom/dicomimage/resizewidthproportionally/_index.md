---
title: "DicomImage.ResizeWidthProportionally"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。在保持宽高比的情况下调整图像的宽度，此方法非常方便。对于希望按比例调整图像大小的开发者来说，它能够确保在不同显示环境下获得一致且视觉上令人满意的结果。"
type: docs
weight: 270
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/resizewidthproportionally/
---
## DicomImage.ResizeWidthProportionally method

使用此便捷方法在保持宽高比的情况下调整图像宽度。适用于希望按比例缩放图像的开发者，确保在不同显示环境中获得一致且视觉上令人满意的效果。

```csharp
public override void ResizeWidthProportionally(int newWidth, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| resizeType | ResizeType | 调整的类型。 |

## 示例

此示例加载 DICOM 图像并使用多种缩放方法按比例调整其大小。仅指定宽度，自动计算高度。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 使用双线性重采样将尺寸放大 2 倍。
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // 使用默认选项保存为 PNG。
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 使用双线性重采样将尺寸缩小 2 倍。
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.BilinearResample);                

    // 使用默认选项保存为 PNG。
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


