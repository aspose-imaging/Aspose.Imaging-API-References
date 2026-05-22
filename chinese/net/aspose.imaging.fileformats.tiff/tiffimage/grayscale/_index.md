---
title: "TiffImage.Grayscale"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。将图像转换为灰度表示，转变为单通道图像，每个像素表示强度。将此方法集成到图像处理流水线中，以简化分析并提升对基于灰度算法的兼容性，促进应用程序内的各种计算机视觉和图像分析任务。"
type: docs
weight: 270
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/grayscale/
---
## TiffImage.Grayscale method

将图像转换为灰度表示，转化为单通道图像，每个像素表示强度。将此方法集成到图像处理管线中，以简化分析并提升对基于灰度算法的兼容性，促进应用中各种计算机视觉和图像分析任务的实现。

```csharp
public override void Grayscale()
```

## 示例

以下示例将彩色 TIFF 图像转换为灰度表示。灰度图像仅由灰色阴影组成，仅携带强度信息。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    tiffImage.Grayscale();
    tiffImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


