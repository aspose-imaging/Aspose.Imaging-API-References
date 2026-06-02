---
title: "TiffFrame.HasAlpha"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffFrame 属性。获取一个值，指示此实例是否具有 alpha 通道"
type: docs
weight: 70
url: /zh/net/aspose.imaging.fileformats.tiff/tiffframe/hasalpha/
---
## TiffFrame.HasAlpha property

获取一个值，指示此实例是否具有 alpha。

```csharp
public override bool HasAlpha { get; }
```

### Property Value

`true` 如果此实例具有 alpha；否则为 `false`。

## 示例

以下示例加载 TIFF 图像并打印原始数据格式和 alpha 通道的信息。

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.tif";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 如果活动 TIFF 帧具有 Alpha 通道，则整个 TIFF 图像被视为具有 Alpha 通道。
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, tiffImage.RawDataFormat, tiffImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Tiff.TiffFrame frame in tiffImage.Frames)
    {
        System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", ++i, frame.RawDataFormat, frame.HasAlpha);
    }
}

// 输出可能如下所示：
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### 另请参见

* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


