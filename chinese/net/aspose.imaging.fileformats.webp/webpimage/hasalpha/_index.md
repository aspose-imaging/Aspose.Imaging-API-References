---
title: HasAlpha
second_title: Aspose.Imaging for .NET API 参考
description: 获取有 alpha 通道
type: docs
weight: 30
url: /zh/net/aspose.imaging.fileformats.webp/webpimage/hasalpha/
---
## WebPImage.HasAlpha property

获取有 alpha 通道。

```csharp
public override bool HasAlpha { get; }
```

### 适当的价值

有 alpha 通道。

### 例子

以下示例加载 WEBP 图像并打印有关原始数据格式和 Alpha 通道的信息。

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.webp";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // 如果活动 TIFF 帧有 alpha 通道，则认为整个 TIFF 图像有 alpha 通道。
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, webpImage.RawDataFormat, webpImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Webp.IFrame frame in webpImage.Blocks)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock frameBlock = frame as Aspose.Imaging.FileFormats.Webp.WebPFrameBlock;
        if (frameBlock != null)
        {
            System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", i++, frameBlock.RawDataFormat, frameBlock.HasAlpha);
        }
    }
}

// 输出可能如下所示：
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### 也可以看看

* class [WebPImage](../../webpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
