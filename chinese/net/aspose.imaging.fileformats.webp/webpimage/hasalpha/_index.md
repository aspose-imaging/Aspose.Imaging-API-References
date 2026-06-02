---
title: "WebPImage.HasAlpha"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WebPImage 属性。获取图像是否包含 alpha 通道，以指示透明信息的存在。利用此属性判断图像是否包含透明度，从而在应用程序中进行适当的处理和与 alpha 相关的操作。"
type: docs
weight: 30
url: /zh/net/aspose.imaging.fileformats.webp/webpimage/hasalpha/
---
## WebPImage.HasAlpha property

检索图像是否包含 alpha 通道，以指示是否存在透明度信息。利用此属性确定图像是否包含透明度，从而在应用程序中适当处理和处理与 alpha 相关的操作。

```csharp
public override bool HasAlpha { get; }
```

### Property Value

具有 alpha 通道。

## 示例

以下示例加载 WEBP 图像并打印原始数据格式和 Alpha 通道的信息。

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.webp";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // 如果活动 TIFF 帧具有 Alpha 通道，则整个 TIFF 图像被视为具有 Alpha 通道。
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
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, 使用的通道: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, 使用的通道: 1, HasAlpha=False
```

### 另请参见

* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


