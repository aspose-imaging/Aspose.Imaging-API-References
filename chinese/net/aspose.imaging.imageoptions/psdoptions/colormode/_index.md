---
title: "PsdOptions.ColorMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "PsdOptions 属性。获取或设置 psd 颜色模式"
type: docs
weight: 40
url: /zh/net/aspose.imaging.imageoptions/psdoptions/colormode/
---
## PsdOptions.ColorMode property

获取或设置 PSD 颜色模式。

```csharp
public ColorModes ColorMode { get; set; }
```

### Property Value

颜色模式。

## 示例

此示例演示了使用 Aspsoe.Imaging 的 .Net API 将图像转换为 PSD 格式。为实现此目标，示例加载现有图像，然后将其保存回 PSD 格式。

```csharp
[C#]

string dir = "c:\\temp\\";

//创建 image 类的实例，并通过文件路径使用现有文件进行初始化
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //创建 PsdOptions 类的实例
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    //将 CompressionMethod 设置为 RLE
    //注意：其他受支持的 CompressionMethod 为 CompressionMethod.RAW【无压缩】
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    //将 ColorMode 设置为 GrayScale
    //注意：其他受支持的 ColorModes 为 ColorModes.Bitmap 和 ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    //使用提供的 PsdOptions 设置将图像保存到磁盘位置
    image.Save(dir + "output.psd", psdOptions);
}
```

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

* enum [ColorModes](../../../aspose.imaging.fileformats.psd/colormodes/)
* class [PsdOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../psdoptions/)
* assembly [Aspose.Imaging](../../../)


