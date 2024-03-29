---
title: FileFormat
second_title: Aspose.Imaging for .NET API 参考
description: 获取文件格式的值
type: docs
weight: 50
url: /zh/net/aspose.imaging.fileformats.bmp/bmpimage/fileformat/
---
## BmpImage.FileFormat property

获取文件格式的值

```csharp
public override FileFormat FileFormat { get; }
```

### 例子

以下示例展示了如何从 BMP 图像中提取有关原始数据格式和 Alpha 通道的信息。

```csharp
[C#]

// 创建一个 100 x 100 像素的 32-bpp BMP 图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 32, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// 创建一个 100 x 100 像素的 24-bpp BMP 图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 24, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// 通常，BMP 不支持 alpha 通道，因此输出将如下所示：
// FileFormat = Bmp, RawDataFormat = Rgb32Bpp, 使用的通道：8,8,8,8, HasAlpha = False
// FileFormat = Bmp, RawDataFormat = Rgb24Bpp, 使用的通道：8,8,8, HasAlpha = False
```

### 也可以看看

* enum [FileFormat](../../../aspose.imaging/fileformat)
* class [BmpImage](../../bmpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
