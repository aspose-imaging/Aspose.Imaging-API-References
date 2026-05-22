---
title: "BmpOptions.Compression"
second_title: "Aspose.Imaging for .NET API 参考"
description: "BmpOptions 属性。获取或设置压缩类型。默认压缩类型是 Bitfields，可用于保存具有透明度的 BmpImage"
type: docs
weight: 30
url: /zh/net/aspose.imaging.imageoptions/bmpoptions/compression/
---
## BmpOptions.Compression property

获取或设置压缩类型。默认压缩类型是 Bitfields，可用于保存具有透明度的 [`BmpImage`](../../../aspose.imaging.fileformats.bmp/bmpimage/)。

```csharp
public BitmapCompression Compression { get; set; }
```

### Property Value

压缩类型。

## 示例

解压缩先前使用 DXT1 压缩算法压缩的 BMP 图像。

```csharp
[C#]

using (var image = Image.Load("CompressedTiger.bmp"))
{
    image.Save("DecompressedTiger.bmp", new BmpOptions());
}
```

使用 DXT1 压缩算法压缩 BMP 图像。

```csharp
[C#]

using (var image = Image.Load("Tiger.bmp"))
{
    image.Save("CompressedTiger.bmp", new BmpOptions { Compression = BitmapCompression.Dxt1 });
}
```

示例展示了如何使用 Rgb 压缩类型导出 BmpImage。

```csharp
[C#]

string sourcePath = "input.png";
// 从文件加载 PNG 图像。
using (Image pngImage = Image.Load(sourcePath))
{
    // BMP 图像默认以透明度支持保存，这是通过使用 BitmapCompression.Bitfields 压缩方法实现的。
    // 要使用 Rgb 压缩方法保存 BMP 图像，应指定 Compression 属性设置为 BitmapCompression.Rgb 的 BmpOptions。
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Rgb });
}
```

示例展示了如何从 Png 文件导出 BmpImage 并保留 alpha 通道，以透明度保存 Bmp 文件。

```csharp
[C#]

string sourcePath = "input.png";
// 从文件加载 PNG 图像。
using (Image pngImage = Image.Load(sourcePath))
{
    // BMP 图像默认以透明度支持保存。
    // 如果您想显式指定此模式，应将 BmpOptions 的 Compression 属性设置为 BitmapCompression.Bitfields。
    // BitmapCompression.Bitfields 压缩方法是 BmpOptions 中的默认压缩方法。
    // 因此，通过以下任一方式都可以实现导出带透明度的 Bmp 图像的相同结果。
    // 使用隐式默认选项：
    pngImage.Save(outputPath);
    // 使用显式默认选项：
    pngImage.Save(outputPath, new BmpOptions());
    // 指定 BitmapCompression.Bitfields 压缩方法：
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Bitfields });
}
```

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

### 另请参见

* enum [BitmapCompression](../../../aspose.imaging.fileformats.bmp/bitmapcompression/)
* class [BmpOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../bmpoptions/)
* assembly [Aspose.Imaging](../../../)


