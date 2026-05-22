---
title: "RasterImage.HasAlpha"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 属性。获取一个值，指示此实例是否具有 alpha"
type: docs
weight: 10
url: /zh/net/aspose.imaging/rasterimage/hasalpha/
---
## RasterImage.HasAlpha property

获取一个值，指示此实例是否具有 alpha。

```csharp
public virtual bool HasAlpha { get; }
```

### Property Value

`true` 如果此实例具有 alpha；否则为 `false`。

## 示例

以下示例加载光栅图像并打印原始数据格式和 Alpha 通道的信息。

```csharp
[C#]

// 要加载的图像文件。
string[] fileNames = new string[]
{
    @"c:\temp\sample.bmp",
    @"c:\temp\alpha.png",
};

foreach (string fileName in fileNames)
{
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
    {
        Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
        System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, rasterImage.RawDataFormat, rasterImage.HasAlpha);
    }
}

// 输出可能如下所示：
// ImageFile=c:\\temp\\sample.bmp, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\\temp\\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

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

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


