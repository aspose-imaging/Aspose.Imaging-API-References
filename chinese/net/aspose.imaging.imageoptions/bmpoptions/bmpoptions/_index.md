---
title: "BmpOptions.BmpOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "BmpOptions 构造函数。初始化 BmpOptions 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.imaging.imageoptions/bmpoptions/bmpoptions/
---
## BmpOptions() {#constructor}

初始化 [`BmpOptions`](../) 类的新实例。

```csharp
public BmpOptions()
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

* class [BmpOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../bmpoptions/)
* assembly [Aspose.Imaging](../../../)

---

## BmpOptions(BmpOptions) {#constructor_1}

初始化 [`BmpOptions`](../) 类的新实例。

```csharp
public BmpOptions(BmpOptions bmpOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bmpOptions | BmpOptions | BMP 选项。 |

### 另请参见

* class [BmpOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../bmpoptions/)
* assembly [Aspose.Imaging](../../../)


