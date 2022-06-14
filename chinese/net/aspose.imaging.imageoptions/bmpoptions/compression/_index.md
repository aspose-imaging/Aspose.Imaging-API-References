---
title: Compression
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置压缩
type: docs
weight: 30
url: /zh/net/aspose.imaging.imageoptions/bmpoptions/compression/
---
## BmpOptions.Compression property

获取或设置压缩。

```csharp
public BitmapCompression Compression { get; set; }
```

### 适当的价值

压缩。

### 例子

解压缩之前使用 DXT1 压缩算法压缩的 BMP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 保存到文件
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
    // 使用每像素 8 位来减小输出图像的大小。
createOptions.BitsPerPixel = 8;

    // 设置标准的 8 位灰度调色板，涵盖所有灰度颜色。
    // 如果处理后的图像只包含灰度颜色，那么它的调色版本
    // 在视觉上与非托盘化的没有区别。
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    // 不压缩保存。
// 也可以使用 RLE-8 压缩来减小输出图像的大小。
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // 设置水平和垂直分辨率为 96 dpi.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // 创建一个 100 x 100 px 的 BMP 图像并将其保存到文件中。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

        // 用灰度梯度填充图像 gradient
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

使用 DXT1 压缩算法压缩 BMP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 保存到文件
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
    // 使用每像素 8 位来减小输出图像的大小。
createOptions.BitsPerPixel = 8;

    // 设置标准的 8 位灰度调色板，涵盖所有灰度颜色。
    // 如果处理后的图像只包含灰度颜色，那么它的调色版本
    // 在视觉上与非托盘化的没有区别。
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    // 不压缩保存。
// 也可以使用 RLE-8 压缩来减小输出图像的大小。
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // 设置水平和垂直分辨率为 96 dpi.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // 创建一个 100 x 100 px 的 BMP 图像并将其保存到文件中。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

        // 用灰度梯度填充图像 gradient
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

以下示例加载 BMP 图像并使用各种保存选项将其保存回 BMP。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 保存到文件
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
    // 使用每像素 8 位来减小输出图像的大小。
createOptions.BitsPerPixel = 8;

    // 设置标准的 8 位灰度调色板，涵盖所有灰度颜色。
    // 如果处理后的图像只包含灰度颜色，那么它的调色版本
    // 在视觉上与非托盘化的没有区别。
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    // 不压缩保存。
// 也可以使用 RLE-8 压缩来减小输出图像的大小。
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // 设置水平和垂直分辨率为 96 dpi.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // 创建一个 100 x 100 px 的 BMP 图像并将其保存到文件中。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

        // 用灰度梯度填充图像 gradient
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

以下示例创建调色板化灰度 BMP 图像，然后将其保存到文件中。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 保存到文件
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
    // 使用每像素 8 位来减小输出图像的大小。
createOptions.BitsPerPixel = 8;

    // 设置标准的 8 位灰度调色板，涵盖所有灰度颜色。
    // 如果处理后的图像只包含灰度颜色，那么它的调色版本
    // 在视觉上与非托盘化的没有区别。
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    // 不压缩保存。
// 也可以使用 RLE-8 压缩来减小输出图像的大小。
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // 设置水平和垂直分辨率为 96 dpi.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // 创建一个 100 x 100 px 的 BMP 图像并将其保存到文件中。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

        // 用灰度梯度填充图像 gradient
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

### 也可以看看

* enum [BitmapCompression](../../../aspose.imaging.fileformats.bmp/bitmapcompression)
* class [BmpOptions](../../bmpoptions)
* 命名空间 [Aspose.Imaging.ImageOptions](../../bmpoptions)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
