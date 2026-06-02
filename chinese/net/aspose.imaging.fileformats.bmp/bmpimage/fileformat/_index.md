---
title: "BmpImage.FileFormat"
second_title: "Aspose.Imaging for .NET API 参考"
description: "BmpImage 属性。使用此用户友好的属性轻松检索文件格式值。适用于希望快速获取文件格式信息的开发者。"
type: docs
weight: 50
url: /zh/net/aspose.imaging.fileformats.bmp/bmpimage/fileformat/
---
## BmpImage.FileFormat property

使用此友好属性轻松获取文件格式值。非常适合希望快速获取文件格式信息的开发人员。

```csharp
public override FileFormat FileFormat { get; }
```

## 示例

以下示例展示如何从 BMP 图像中提取原始数据格式和 Alpha 通道的信息。

```csharp
[C#]

// 创建一个 100 x 100 像素的 32 位 BMP 图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 32, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// 创建一个 100 x 100 像素的 24 位 BMP 图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 24, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// 通常，BMP 不支持 Alpha 通道，因此输出将如下所示：
// FileFormat = Bmp, RawDataFormat = Rgb32Bpp, used channels: 8,8,8,8, HasAlpha = False
// FileFormat = Bmp, RawDataFormat = Rgb24Bpp, used channels: 8,8,8, HasAlpha = False
```

### 另请参见

* enum [FileFormat](../../../aspose.imaging/fileformat/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


