---
title: "ImageOptionsBase.ResolutionSettings"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ImageOptionsBase 属性。获取或设置分辨率设置"
type: docs
weight: 80
url: /zh/net/aspose.imaging/imageoptionsbase/resolutionsettings/
---
## ImageOptionsBase.ResolutionSettings property

获取或设置分辨率设置。

```csharp
public virtual ResolutionSetting ResolutionSettings { get; set; }
```

## 示例

以下示例加载 BMP 图像并使用各种保存选项将其保存回 BMP。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 创建 BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 使用每像素 8 位来减小输出图像的大小。
    saveOptions.BitsPerPixel = 8;

    // 设置最接近的 8 位颜色调色板，以覆盖最大数量的图像像素，从而得到调色后的图像
    // 几乎在视觉上与非调色板图像无差别。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // 保存时不使用压缩。
    // 您也可以使用 RLE-8 压缩来减小输出图像的大小。
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // 将水平和垂直分辨率设置为 96 dpi。
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

以下示例加载 BMP 图像并使用各种保存选项将其保存为 JPEG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件加载 BMP 图像。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // 进行一些图像处理。

    // 使用附加选项来指定所需的图像参数。
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // 每个通道的位数为 8。
    // 使用调色板时，颜色索引存储在图像数据中，而不是颜色本身。
    saveOptions.BitsPerChannel = 8;

    // 设置渐进式压缩类型。
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // 设置图像质量。取值范围为 1 到 100。
    saveOptions.Quality = 100;

    // 将水平/垂直分辨率设置为每英寸 96 点。
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // 如果源图像是彩色的，它将被转换为灰度。
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // 使用调色板来减小输出大小。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

以下示例创建一个调色的灰度 BMP 图像，然后将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// 保存到文件
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// 使用每像素 8 位来减小输出图像的大小。
createOptions.BitsPerPixel = 8;

// 设置标准的 8 位灰度颜色调色板，覆盖所有灰度颜色。
// 如果处理后的图像仅包含灰度颜色，则其调色版本
// 在视觉上与未调色的图像无差别。
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// 保存时不使用压缩。
// 您也可以使用 RLE-8 压缩来减小输出图像的大小。
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// 将水平和垂直分辨率设置为 96 dpi。
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// 创建一个 100 x 100 像素的 BMP 图像并保存到文件。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // 用灰度渐变填充图像
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

以下示例展示了如何使用指定的参数创建指定尺寸的 JPEG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 JPEG 图像。
// 使用附加选项来指定所需的图像参数。
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// 各通道的位数分别为 Y、Cr、Cb 组件的 8、8、8 位。
createOptions.BitsPerChannel = 8;

// 设置渐进式压缩类型。
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// 设置图像质量。取值范围为 1 到 100。
createOptions.Quality = 100;

// 将水平/垂直分辨率设置为每英寸 96 点。
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// 这是 JPEG 图像的标准选项。
// 两个色度分量（Cb 和 Cr）可以进行带宽降低、子采样和压缩。
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // 用灰度渐变填充图像
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // 保存到文件。
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### 另请参见

* class [ResolutionSetting](../../resolutionsetting/)
* class [ImageOptionsBase](../)
* namespace [Aspose.Imaging](../../imageoptionsbase/)
* assembly [Aspose.Imaging](../../../)


