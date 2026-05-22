---
title: "JpegImage.JpegOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "JpegImage 属性。轻松获取在创建或加载此 JpegImage 实例期间使用的 JPEG 选项。此属性提供有关所使用的特定设置的宝贵细节，使用户能够有效地理解和复现图像处理工作流。无论是压缩级别、质量设置还是其他参数，此属性都提供了实现无缝图像操作所必需的关键洞察。"
type: docs
weight: 130
url: /zh/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions/
---
## JpegImage.JpegOptions property

轻松获取在创建或加载此 [`JpegImage`](../) 实例时使用的 JPEG 选项。此属性提供有关所使用的特定设置的有价值细节，使用户能够有效地理解和复现图像处理工作流。无论是压缩级别、质量设置还是其他参数，此属性都提供了实现无缝图像操作的关键洞察。

```csharp
public JpegOptions JpegOptions { get; }
```

### Property Value

JPEG 选项。

## 示例

以下示例展示了如何从 JPEG 图像中提取头部信息。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage image = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)Image.Load(dir + "original.jpg"))
{
    Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = image.JpegOptions;

    System.Console.WriteLine("The number of bits per channel: {0}", jpegOptions.BitsPerChannel);
    System.Console.WriteLine("The max allowed size for all internal buffers: {0}", jpegOptions.BufferSizeHint);
    System.Console.WriteLine("The color type: {0}", jpegOptions.ColorType);
    System.Console.WriteLine("The compression type: {0}", jpegOptions.CompressionType);
    System.Console.WriteLine("The image quality: {0}", jpegOptions.Quality);

    if (jpegOptions.ResolutionSettings != null)
    {
        System.Console.WriteLine("The horizontal resolution: {0}", jpegOptions.ResolutionSettings.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution: {0}", jpegOptions.ResolutionSettings.VerticalResolution);
    }

    for (int i = 0; i < jpegOptions.HorizontalSampling.Length; i++)
    {
        System.Console.WriteLine("The sampling for component {0}: {1}x{2}", i, jpegOptions.HorizontalSampling[i], jpegOptions.VerticalSampling[i]);
    }
}

//输出如下：
//每通道位数: 8
//所有内部缓冲区的最大允许大小: 0
//颜色类型: YCbCr
//压缩类型: Baseline
//图像质量: 75
//组件 0 的采样: 1x1
//组件 1 的采样: 1x1
//组件 2 的采样: 1x1
```

### 另请参见

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions/)
* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


