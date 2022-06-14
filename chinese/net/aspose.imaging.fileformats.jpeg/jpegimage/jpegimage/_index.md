---
title: JpegImage
second_title: Aspose.Imaging for .NET API 参考
description: 初始化JpegImageaspose.imaging.fileformats.jpeg/jpegimage类的新实例
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.jpeg/jpegimage/jpegimage/
---
## JpegImage(string) {#constructor_4}

初始化[`JpegImage`](../../jpegimage)类的新实例。

```csharp
public JpegImage(string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 加载图像和初始化像素和调色板数据的路径。 |

### 例子

该示例展示了如何从文件加载 JpegImage。

```csharp
[C#]

string dir = "c:\\temp\\";

    // 从文件中加载 JPEG 图像。
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
        // 做一些图像处理.
        // 保存到另一个 JPEG 文件。
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### 也可以看看

* class [JpegImage](../../jpegimage)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* 部件 [Aspose.Imaging](../../../)

---

## JpegImage(Stream) {#constructor_3}

初始化[`JpegImage`](../../jpegimage)类的新实例。

```csharp
public JpegImage(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像和初始化像素和调色板数据的流。 |

### 例子

该示例展示了如何从文件流中加载 JpegImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流中加载 JPEG 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jpg"))
{
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(stream))
    {
            // 做一些图像处理.
            // 保存到另一个 JPEG 文件。
        jpegImage.Save(dir + "sample.output.jpg");
    }
}
```

### 也可以看看

* class [JpegImage](../../jpegimage)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* 部件 [Aspose.Imaging](../../../)

---

## JpegImage(RasterImage) {#constructor_1}

初始化[`JpegImage`](../../jpegimage)类的新实例。

```csharp
public JpegImage(RasterImage rasterImage)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 用于初始化像素和调色板数据的图像。 |

### 例子

该示例展示了如何从另一个 RasterImage 加载 JpegImage。

```csharp
[C#]

string dir = "c:\\temp\\";

    // 从另一个光栅图像加载 JPEG 图像。
    // 首先，创建一个临时 PNG 图像，作为构建 JPEG 图像的基础。
    // 您也可以从文件中加载 PNG 图像或使用任何其他光栅格式的图像。
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), false);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
        // 用红色填充整个PNG图像。
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, rasterImage.Bounds);

        // 基于PNG图像创建JPEG图像。
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(rasterImage))
    {
            // 保存为 JPEG 文件
        jpegImage.Save(dir + "output.jpg");
    }
}
```

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [JpegImage](../../jpegimage)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* 部件 [Aspose.Imaging](../../../)

---

## JpegImage(int, int) {#constructor_2}

初始化[`JpegImage`](../../jpegimage)类的新实例。

```csharp
public JpegImage(int width, int height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 图像宽度。 |
| height | Int32 | 图像高度。 |

### 例子

以下示例显示了如何创建指定大小的 JPEG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

    // 从文件中加载 BMP 图像。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
        // 做一些图像处理.

        // 使用附加选项来指定所需的图像参数。
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

        // 每个通道的位数是 8.
        // 使用调色板时，颜色索引存储在图像数据中，而不是颜色本身。
    saveOptions.BitsPerChannel = 8;

        // 设置压缩的渐进类型。
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

        // 设置图像质量。它是一个介于 1 和 100 之间的值。
    saveOptions.Quality = 100;

        // 将水平/垂直分辨率设置为每英寸 96 点。
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

        // 如果源图是彩色的，会转成灰度图。
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

        // 使用调色板来减小输出大小。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

以下示例加载 BMP 图像并使用各种保存选项将其保存为 JPEG。

```csharp
[C#]

string dir = "c:\\temp\\";

    // 从文件中加载 BMP 图像。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
        // 做一些图像处理.

        // 使用附加选项来指定所需的图像参数。
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

        // 每个通道的位数是 8.
        // 使用调色板时，颜色索引存储在图像数据中，而不是颜色本身。
    saveOptions.BitsPerChannel = 8;

        // 设置压缩的渐进类型。
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

        // 设置图像质量。它是一个介于 1 和 100 之间的值。
    saveOptions.Quality = 100;

        // 将水平/垂直分辨率设置为每英寸 96 点。
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

        // 如果源图是彩色的，会转成灰度图。
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

        // 使用调色板来减小输出大小。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

### 也可以看看

* class [JpegImage](../../jpegimage)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* 部件 [Aspose.Imaging](../../../)

---

## JpegImage(JpegOptions, int, int) {#constructor}

初始化[`JpegImage`](../../jpegimage)类的新实例。

```csharp
public JpegImage(JpegOptions jpegOptions, int width, int height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| jpegOptions | JpegOptions | jpeg 选项。 |
| width | Int32 | 图像宽度。 |
| height | Int32 | 图像高度。 |

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

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
