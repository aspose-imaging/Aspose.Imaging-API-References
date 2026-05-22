---
title: "JpegImage.JpegImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "JpegImage 构造函数。JpegImage 类通过调用带有指定路径参数的构造函数轻松初始化。此构造函数实现了 JPEG 图像的无缝创建，确保快速将其集成到您的项目中。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegimage/
---
## JpegImage(string) {#constructor_4}

[`JpegImage`](../) 类通过调用带有指定路径参数的构造函数轻松初始化。此构造函数实现了 JPEG 图像的无缝创建，确保快速将其集成到您的项目中。

```csharp
public JpegImage(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 加载图像的路径，并使用该路径初始化像素和调色板数据。 |

## 示例

示例展示了如何从文件加载 JpegImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件加载 JPEG 图像。
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // 进行一些图像处理。
    // 保存为另一个 JPEG 文件。
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### 另请参见

* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)

---

## JpegImage(Stream) {#constructor_3}

使用 [`JpegImage`](../) 类并通过流参数初始化 JPEG 图像对象。此构造函数简化了处理 JPEG 图像的过程，提供了一种直接将其集成到项目中的简便方法。

```csharp
public JpegImage(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像并初始化像素和调色板数据的流。 |

## 示例

示例展示了如何从文件流加载 JpegImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 JPEG 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jpg"))
{
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(stream))
    {
        // 进行一些图像处理。
        // 保存为另一个 JPEG 文件。
        jpegImage.Save(dir + "sample.output.jpg");
    }
}
```

### 另请参见

* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)

---

## JpegImage(RasterImage) {#constructor_1}

使用带有栅格图像参数的 [`JpegImage`](../) 类初始化新实例。此构造函数提供了一种便捷方式，可直接从栅格图像创建 JPEG 图像，简化了在应用程序中使用 JPEG 图像的工作流。

```csharp
public JpegImage(RasterImage rasterImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 用于初始化像素和调色板数据的图像。 |

## 示例

示例展示了如何从另一个 RasterImage 加载 JpegImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从另一个光栅图像加载 JPEG 图像。
// 首先，创建一个临时 PNG 图像，它将作为构建 JPEG 图像的基础。
// 您也可以从文件加载 PNG 图像，或使用任何其他光栅格式的图像。
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), false);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // 将整个 PNG 图像填充为红色。
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, rasterImage.Bounds);

    // 基于 PNG 图像创建 JPEG 图像。
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(rasterImage))
    {
        // 保存为 JPEG 文件
        jpegImage.Save(dir + "output.jpg");
    }
}
```

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)

---

## JpegImage(int, int) {#constructor_2}

使用指定的宽度和高度参数创建 [`JpegImage`](../) 类的新实例。此构造函数允许您创建具有自定义尺寸的 JPEG 图像，为在应用程序中管理图像大小提供灵活性。

```csharp
public JpegImage(int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 图像宽度。 |
| 高度 | Int32 | 图像高度。 |

## 示例

以下示例展示了如何创建指定尺寸的 JPEG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 JPEG 图像。
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(100, 100))
{
    // 进行一些图像处理。
    // 保存到文件。
    jpegImage.Save(dir + "output.jpg");
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

### 另请参见

* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)

---

## JpegImage(JpegOptions, int, int) {#constructor}

使用提供的 JPEG 选项初始化一个新的 [`JpegImage`](../) 对象。此构造函数使您能够定制 JPEG 图像的各种设置，例如压缩级别、质量和其他参数，从而对生成的图像格式实现精确控制。

```csharp
public JpegImage(JpegOptions jpegOptions, int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| jpegOptions | JpegOptions | jpeg 选项。 |
| 宽度 | Int32 | 图像宽度。 |
| 高度 | Int32 | 图像高度。 |

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

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions/)
* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


