---
title: "JpegOptions.JpegOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "JpegOptions 构造函数。初始化 JpegOptions 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.imaging.imageoptions/jpegoptions/jpegoptions/
---
## JpegOptions() {#constructor}

初始化一个新的 [`JpegOptions`](../) 类的实例。

```csharp
public JpegOptions()
```

## 示例

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

* class [JpegOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../jpegoptions/)
* assembly [Aspose.Imaging](../../../)

---

## JpegOptions(JpegOptions) {#constructor_1}

初始化一个新的 [`JpegOptions`](../) 类的实例。

```csharp
public JpegOptions(JpegOptions jpegOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| jpegOptions | JpegOptions | JPEG 选项。 |

### 另请参见

* class [JpegOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../jpegoptions/)
* assembly [Aspose.Imaging](../../../)


