---
title: HasAlpha
second_title: Aspose.Imaging for .NET API 参考
description: 获取 Has alpha 通道
type: docs
weight: 70
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/hasalpha/
---
## TiffImage.HasAlpha property

获取 Has alpha 通道。

```csharp
public override bool HasAlpha { get; }
```

### 适当的价值

有 alpha 通道。

### 例子

以下示例加载 TIFF 图像并打印有关原始数据格式和 alpha 通道的信息。

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.tif";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

        // 如果活动 TIFF 帧有 alpha 通道，则认为整个 TIFF 图像有 alpha 通道。
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, tiffImage.RawDataFormat, tiffImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Tiff.TiffFrame frame in tiffImage.Frames)
    {
        System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", ++i, frame.RawDataFormat, frame.HasAlpha);
    }
}

// 输出可能如下所示：
    // ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, 使用的通道：1, HasAlpha=False
    // Frame=1，FileFormat=RgbIndexed1Bpp，使用的通道：1，HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### 也可以看看

* class [TiffImage](../../tiffimage)
* 命名空间 [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->