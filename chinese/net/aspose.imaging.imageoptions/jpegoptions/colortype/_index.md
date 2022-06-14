---
title: ColorType
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置 jpeg 图像的颜色类型
type: docs
weight: 40
url: /zh/net/aspose.imaging.imageoptions/jpegoptions/colortype/
---
## JpegOptions.ColorType property

获取或设置 jpeg 图像的颜色类型。

```csharp
public JpegCompressionColorMode ColorType { get; set; }
```

### 例子

以下示例加载 BMP 图像并使用各种保存选项将其保存为 JPEG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 JPEG 图像。
    // 使用附加选项来指定所需的图像参数。
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // 每个通道的位数分别为 8、8、8 对应 Y、Cr、Cb 分量。
createOptions.BitsPerChannel = 8;

    // 设置压缩的渐进类型。
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // 设置图像质量。它是一个介于 1 和 100 之间的值。
createOptions.Quality = 100;

    // 将水平/垂直分辨率设置为每英寸 96 点。
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // 这是 JPEG 图像的标准选项。
    // 两个色度分量（Cb 和 Cr）可以进行带宽缩减、二次采样、压缩。
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

        // 用灰度梯度填充图像 gradient
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

        // 保存到文件.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

以下示例使用自定义 ICC 配置文件加载 PNG 并将其保存为 CMYK JPEG。然后加载 CMYK JPEG 并将其保存回 PNG。从 RGB 到 CMYK 以及从 CMYK 到 RGB 的颜色转换是使用自定义 ICC 配置文件执行的。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 JPEG 图像。
    // 使用附加选项来指定所需的图像参数。
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // 每个通道的位数分别为 8、8、8 对应 Y、Cr、Cb 分量。
createOptions.BitsPerChannel = 8;

    // 设置压缩的渐进类型。
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // 设置图像质量。它是一个介于 1 和 100 之间的值。
createOptions.Quality = 100;

    // 将水平/垂直分辨率设置为每英寸 96 点。
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // 这是 JPEG 图像的标准选项。
    // 两个色度分量（Cb 和 Cr）可以进行带宽缩减、二次采样、压缩。
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

        // 用灰度梯度填充图像 gradient
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

        // 保存到文件.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

以下示例说明如何使用指定参数创建指定大小的 JPEG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 JPEG 图像。
    // 使用附加选项来指定所需的图像参数。
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // 每个通道的位数分别为 8、8、8 对应 Y、Cr、Cb 分量。
createOptions.BitsPerChannel = 8;

    // 设置压缩的渐进类型。
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // 设置图像质量。它是一个介于 1 和 100 之间的值。
createOptions.Quality = 100;

    // 将水平/垂直分辨率设置为每英寸 96 点。
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // 这是 JPEG 图像的标准选项。
    // 两个色度分量（Cb 和 Cr）可以进行带宽缩减、二次采样、压缩。
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

        // 用灰度梯度填充图像 gradient
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

        // 保存到文件.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### 也可以看看

* enum [JpegCompressionColorMode](../../../aspose.imaging.fileformats.jpeg/jpegcompressioncolormode)
* class [JpegOptions](../../jpegoptions)
* 命名空间 [Aspose.Imaging.ImageOptions](../../jpegoptions)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
