---
title: "LoadOptions.BufferSizeHint"
second_title: "Aspose.Imaging for .NET API 参考"
description: "LoadOptions 属性。获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小"
type: docs
weight: 20
url: /zh/net/aspose.imaging/loadoptions/buffersizehint/
---
## LoadOptions.BufferSizeHint property

获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

```csharp
public int BufferSizeHint { get; set; }
```

### Property Value

缓冲区大小提示，单位为兆字节。非正值表示内部缓冲区没有内存限制

## 示例

以下示例展示了在加载 CMX 图像时如何设置内存限制。内存限制是所有内部缓冲区的最大允许大小（以兆字节为单位）。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3419\\";
    
// 为目标加载的图像设置 10 兆字节的内存限制。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "example.cmx", new Aspose.Imaging.LoadOptions() { BufferSizeHint = 10 }))
{
    image.Save(dir + "output.png",
        new Aspose.Imaging.ImageOptions.PngOptions()
        {
            VectorRasterizationOptions =
                    new Aspose.Imaging.ImageOptions.CmxRasterizationOptions
                    {
                        TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel,
                        SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias,
                        Positioning = Aspose.Imaging.ImageOptions.PositioningTypes.DefinedByDocument
                    }
        });
}
```

以下示例展示了在加载 JPEG 图像时如何设置内存限制。内存限制是所有内部缓冲区的最大允许大小（以兆字节为单位）。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3404\\";

// 为目标加载的图像设置 50 兆字节的内存限制
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "inputFile.jpg", new Aspose.Imaging.LoadOptions() { BufferSizeHint = 50 }))
{
    image.Save(dir + "outputFile_Baseline.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Baseline,
            Quality = 100
        });

    image.Save(dir + "outputFile_Progressive.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive
        });

    image.Save(dir + "outputFile_Lossless.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr,
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Lossless,
            BitsPerChannel = 4
        });

    image.Save(dir + "outputFile_JpegLs.jpg",
        new Aspose.Imaging.ImageOptions.JpegOptions
        {
            ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr,
            CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.JpegLs,
            JpegLsInterleaveMode = Aspose.Imaging.FileFormats.Jpeg.JpegLsInterleaveMode.None,
            JpegLsAllowedLossyError = 3,
            JpegLsPreset = null
        });
}
```

### 另请参见

* class [LoadOptions](../)
* namespace [Aspose.Imaging](../../loadoptions/)
* assembly [Aspose.Imaging](../../../)


