---
title: "WebPFrameBlock.HasAlpha"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WebPFrameBlock 属性。获取一个值，指示此实例是否具有 Alpha 通道"
type: docs
weight: 80
url: /zh/net/aspose.imaging.fileformats.webp/webpframeblock/hasalpha/
---
## WebPFrameBlock.HasAlpha property

获取一个值，指示此实例是否具有 alpha。

```csharp
public override bool HasAlpha { get; }
```

### Property Value

`true` 如果此实例具有 alpha；否则为 `false`。

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

* class [WebPFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpframeblock/)
* assembly [Aspose.Imaging](../../../)


