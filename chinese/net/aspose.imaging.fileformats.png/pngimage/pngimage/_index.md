---
title: "PngImage.PngImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "PngImage 构造函数。通过提供宽度和高度参数来初始化 PngImage 类的新对象。此构造函数通过允许开发者直接指定尺寸，简化了 PNG 图像的创建，从而在应用程序中高效管理 PNG 图像数据。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.png/pngimage/pngimage/
---
## PngImage(int, int) {#constructor_3}

通过提供宽度和高度参数来初始化 [`PngImage`](../) 类的新对象。此构造函数通过允许开发者直接指定尺寸，简化了 PNG 图像的创建，从而在应用程序中高效管理 PNG 图像数据。

```csharp
public PngImage(int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 宽度。 |
| 高度 | Int32 | 高度。 |

## 示例

此示例展示了如何创建指定尺寸的 PNG 图像，填充纯色并将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    // 进行一些图像处理，例如将整幅图像填充为红色。
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // 保存到文件。
    pngImage.Save(dir + "output.png");
}
```

### 另请参见

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(string) {#constructor_6}

使用 path 参数指定要加载的图像文件位置，构造 [`PngImage`](../) 类的新实例。此构造函数使开发者能够方便地通过从文件加载来创建 PNG 图像，简化了在应用程序中使用 PNG 图像的过程。

```csharp
public PngImage(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 用于加载图像的路径。 |

## 示例

此示例展示了如何从文件加载 PNG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件加载 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // 将图像转换为灰度表示
    pngImage.Grayscale();

    // 保存到文件。
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### 另请参见

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(RasterImage) {#constructor_1}

通过提供光栅图像作为参数，创建 [`PngImage`](../) 类的新实例。此构造函数允许开发者直接使用现有光栅图像初始化 PNG 图像对象，简化了在应用程序中使用 PNG 图像的流程。

```csharp
public PngImage(RasterImage rasterImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 栅格图像。 |

## 示例

此示例展示了如何从 BMP 图像加载 PNG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从 BMP 图像加载 TrueColor PNG 图像。
// 首先，创建一个临时 BMP 图像，它将作为构建 PNG 图像的基础。
// 您也可以从文件加载 BMP 图像，或使用任何其他光栅格式的图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // 将整个 BMP 图像填充为红色。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage))
    {
        System.Console.WriteLine("The PNG color type: {0}", pngImage.GetOriginalOptions());
        pngImage.Save(dir + "output.png");
    }
}
```

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(string, PngColorType) {#constructor_7}

通过指定图像文件路径和颜色类型，初始化 [`PngImage`](../) 类的新实例。此构造函数便于从不同颜色类型的文件创建 PNG 图像，提供了处理各种图像格式的灵活性。

```csharp
public PngImage(string path, PngColorType colorType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 用于加载图像的路径。 |
| colorType | PngColorType | 颜色类型。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException |  |

## 示例

此示例展示了如何使用指定的颜色类型从文件加载 PNG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件加载 PNG 图像。
// 请注意，彩色图像将自动转换为灰度图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png", Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // 保存到文件。
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### 另请参见

* enum [PngColorType](../../pngcolortype/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(RasterImage, PngColorType) {#constructor_2}

通过指定光栅图像和颜色类型，创建 [`PngImage`](../) 类的新实例。此构造函数使开发者能够在指定所需颜色类型的同时，将光栅图像直接转换为 PNG 格式，提供了颜色表示的灵活性。

```csharp
public PngImage(RasterImage rasterImage, PngColorType colorType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 栅格图像。 |
| colorType | PngColorType | 颜色类型。 |

## 示例

此示例展示了如何使用指定的颜色类型从 BMP 图像加载 PNG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从彩色 BMP 图像加载灰度 PNG 图像。
// 首先，创建一个临时 BMP 图像，它将作为构建 PNG 图像的基础。
// 您也可以从文件加载 BMP 图像，或使用任何其他光栅格式的图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // 将整个 BMP 图像填充为红色。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // 图像像素的颜色将被转换为对应的灰度值。
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
    {
        pngImage.Save(dir + "output.grayscale.png");
    }
}
```

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* enum [PngColorType](../../pngcolortype/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(Stream) {#constructor_5}

通过使用流进行初始化，创建 [`PngImage`](../) 类的新实例。此构造函数允许开发者直接从流加载 PNG 图像，提供了从不同来源获取图像的灵活性。

```csharp
public PngImage(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像的流。 |

## 示例

此示例展示了如何从文件或文件流加载 PNG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 PNG 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.png"))
{
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(stream))
    {
        // 将图像转换为灰度表示
        pngImage.Grayscale();

        // 保存到文件。
        pngImage.Save(dir + "sample.grayscale.png");
    }
}
```

### 另请参见

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(int, int, PngColorType) {#constructor_4}

实例化一个新的 [`PngImage`](../) 类，指定所需的宽度、高度和颜色类型参数。此构造函数能够快速创建具有定制尺寸和颜色配置的 PNG 图像，促进在各种应用和工作流中实现简化的图像生成。

```csharp
public PngImage(int width, int height, PngColorType colorType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 宽度。 |
| 高度 | Int32 | 高度。 |
| colorType | PngColorType | 颜色类型。 |

## 示例

此示例展示了如何创建具有指定尺寸和颜色类型的 PNG 图像，填充为纯色并将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的灰度 PNG 图像。
// 所有颜色将自动转换为灰度格式。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // 进行一些图像处理，例如将整幅图像填充为红色。
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // 保存到文件。
    pngImage.Save(dir + "output.grayscale.png");
}
```

### 另请参见

* enum [PngColorType](../../pngcolortype/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(PngOptions, int, int) {#constructor}

初始化一个新的 [`PngImage`](../) 类实例，结合 PNG 选项以及宽度和高度参数。此构造函数使开发者能够创建具有可自定义设置和尺寸的 PNG 图像，为多种使用场景提供灵活的图像生成能力。

```csharp
public PngImage(PngOptions pngOptions, int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pngOptions | PngOptions | PNG 选项。 |
| 宽度 | Int32 | 宽度。 |
| 高度 | Int32 | 高度。 |

## 示例

此示例展示了如何使用指定的选项创建 PNG 图像，填充线性渐变颜色并将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// 每个颜色通道的位数
createOptions.BitDepth = 8;

// 每个像素是一个 (红, 绿, 蓝) 三元组，后跟 alpha 分量。
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// 最大压缩级别。
createOptions.CompressionLevel = 9;

// 使用过滤器可以更有效地压缩连续色调图像。
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// 使用渐进式加载
createOptions.Progressive = true;

// 使用自定义参数创建 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // 用半透明渐变填充图像。
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // 保存到文件。
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

### 另请参见

* class [PngOptions](../../../aspose.imaging.imageoptions/pngoptions/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


