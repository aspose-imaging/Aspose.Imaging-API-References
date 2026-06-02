---
title: "PsdOptions.Version"
second_title: "Aspose.Imaging for .NET API 参考"
description: "PsdOptions 属性。获取或设置 PSD 文件版本"
type: docs
weight: 100
url: /zh/net/aspose.imaging.imageoptions/psdoptions/version/
---
## PsdOptions.Version property

获取或设置 psd 文件版本。

```csharp
public int Version { get; set; }
```

### Property Value

PSD 文件版本。

## 示例

此示例展示了如何使用各种 PSD 特定选项将 PNG 图像保存为 PSD 格式。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha))
{
    // 定义线性蓝色透明渐变。
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // 使用线性蓝色透明渐变填充 PNG 图像。
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // 以下选项将用于将 PNG 图像保存为 PSD 格式。
    Aspose.Imaging.ImageOptions.PsdOptions saveOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    // 每通道的位数
    saveOptions.ChannelBitsCount = 8;

    // 通道数。每个颜色分量 R、G、B、A 各占一个通道。
    saveOptions.ChannelsCount = 4;

    // 颜色模式
    saveOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Rgb;

    // 无压缩
    saveOptions.CompressionMethod = Imaging.FileFormats.Psd.CompressionMethod.Raw;

    // 默认版本为 6
    saveOptions.Version = 6;            

    using (System.IO.FileStream stream = System.IO.File.Create(dir + "saveoptions.psd"))
    {
        pngImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the PSD image with RAW compression: {0}", stream.Length);
    }

    using (System.IO.FileStream stream = System.IO.File.Create(dir + "saveoptions.RLE.psd"))
    {
        // RLE 压缩可以减小输出图像的大小
        saveOptions.CompressionMethod = Imaging.FileFormats.Psd.CompressionMethod.RLE;

        pngImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the PSD image with RLE compression: {0}", stream.Length);
    }

    // 输出可能如下所示：
    // 使用 RAW 压缩的 PSD 图像大小：40090
    // 使用 RLE 压缩的 PSD 图像大小：16185
}
```

### 另请参见

* class [PsdOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../psdoptions/)
* assembly [Aspose.Imaging](../../../)


