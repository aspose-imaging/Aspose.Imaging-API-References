---
title: "PngImage.RawDataFormat"
second_title: "Aspose.Imaging for .NET API 参考"
description: "PngImage 属性。访问图像的原始数据格式。此属性提供对图像数据内部结构的洞察，可用于高级图像处理任务或格式转换。"
type: docs
weight: 120
url: /zh/net/aspose.imaging.fileformats.png/pngimage/rawdataformat/
---
## PngImage.RawDataFormat property

访问图像的原始数据格式。此属性提供对图像数据内部结构的洞察，可用于高级图像处理任务或格式转换。

```csharp
public override PixelDataFormat RawDataFormat { get; }
```

## 示例

以下示例加载 PNG 图像并打印原始数据格式和 alpha 通道的信息。

```csharp
[C#]

// 要加载的 PNG 图像。
string[] fileNames = new string[]
{
    @"c:\temp\sample.png",
    @"c:\temp\alpha.png",
};

foreach (string fileName in fileNames)
{
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
    {
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;
        System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, pngImage.RawDataFormat, pngImage.HasAlpha);
    }
}

// 输出可能如下所示：
// ImageFile=c:\\temp\\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\\temp\\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### 另请参见

* class [PixelDataFormat](../../../aspose.imaging/pixeldataformat/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


