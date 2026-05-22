---
title: "WebPImage.WebPImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WebPImage 构造函数。实例化一个新的 WebPImage 类对象，使用提供的流源进行初始化。利用此构造函数可直接从流中无缝创建 WebP 图像对象，实现对 WebP 图像数据的高效处理和操作。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.webp/webpimage/webpimage/
---
## WebPImage(Stream) {#constructor_4}

实例化一个新的 [`WebPImage`](../) 类对象，使用提供的流源进行初始化。利用此构造函数可直接从流中无缝创建 WebP 图像对象，实现对 WebP 图像数据的高效处理和操作。

```csharp
public WebPImage(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流式 WebP 图像。 |

## 示例

此示例展示了如何从文件流加载 WebP 图像并将其保存为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 WebP 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.webp"))
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(stream))
{
    // 保存为 PNG
    // 请注意，由于 PNG 不是多页格式，仅会将活动帧存储为 PNG。
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(string) {#constructor_6}

实例化一个全新的 [`WebPImage`](../) 类实例，该实例从提供的文件源初始化。利用此构造函数可直接从文件无缝创建 WebP 图像对象，简化在应用程序中加载和操作 WebP 图像数据的过程。

```csharp
public WebPImage(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | WebP 图像文件的路径 |

## 示例

此示例展示了如何从文件加载 WebP 图像并将其保存为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件加载 WebP 图像。
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // 保存为 PNG
    // 请注意，由于 PNG 不是多页格式，仅会将活动帧存储为 PNG。
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(string, LoadOptions) {#constructor_7}

使用文件和指定的加载选项创建一个新的 [`WebPImage`](../) 类实例，以便灵活处理 WebP 图像数据。利用此构造函数可在根据应用程序需求自定义加载参数的同时，无缝地从文件初始化 WebP 图像对象。

```csharp
public WebPImage(string path, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | WebP 图像文件的路径 |
| loadOptions | LoadOptions | 加载选项。 |

### 另请参见

* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage) {#constructor}

实例化一个新的 [`WebPImage`](../) 类实例，该实例从提供的 rasterImage 对象初始化。此构造函数可实现栅格图像到 WebP 格式的无缝转换，提升在应用程序中对图像数据的高效处理和操作。

```csharp
public WebPImage(RasterImage rasterImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 栅格图像。 |

## 示例

此示例展示了如何从另一个栅格图像创建 WebP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 加载一张 100x100 像素的 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // 将整幅图像填充为红色。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // 基于 PNG 图像创建 WebP 图像。
    using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(pngImage))
    {
        // 使用默认选项保存为 WebP 文件
        webPImage.Save(dir + "output.webp", new Aspose.Imaging.ImageOptions.WebPOptions());
    }
}
```

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage, LoadOptions) {#constructor_1}

使用 rasterImage 对象和指定的加载选项创建一个新的 [`WebPImage`](../) 类实例，以实现对图像数据的灵活处理。利用此构造函数可在根据应用程序需求自定义加载参数的同时，无缝地从栅格图像初始化 WebP 图像对象。

```csharp
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 栅格图像。 |
| loadOptions | LoadOptions | 加载选项。 |

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions) {#constructor_2}

实例化一个新的 [`WebPImage`](../) 类实例，使用指定宽度和高度的空白图像。此构造函数可创建空白的 WebP 图像，为后续的图像操作和内容生成提供基础。

```csharp
public WebPImage(int width, int height, WebPOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 图像宽度 |
| 高度 | Int32 | 图像高度。 |
| 选项 | WebPOptions | 选项。 |

## 示例

此示例展示了如何从头创建具有指定选项的 WebP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
//createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + \"output.webp\");

// 创建一个 100x100 像素的 WebP 图像。
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(webPImage);

    // 将整幅图像填充为红色。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, webPImage.Bounds);

    // 保存为 WebP 文件
    webPImage.Save(dir + "output.webp");
}
```

此示例展示了如何使用指定的选项创建多帧动画 WebP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// 默认帧加上 36 + 36 个额外帧。
createOptions.AnimLoopCount = 36 + 36 + 1;

// 创建一个 100x100 像素的 WebP 图像。
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // 第一个圆是红色的
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // 第二个圆是黑色的
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // 逐渐增加红色弧形的角度。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // 逐渐增加黑色弧形的角度并抹去红色弧形。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // 保存为 WebP 文件
    webPImage.Save(dir + "output.webp");
}
```

### 另请参见

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions, LoadOptions) {#constructor_3}

使用空白图像和指定的加载选项创建一个新的 [`WebPImage`](../) 类实例。此构造函数允许使用可自定义的加载参数初始化 WebP 图像，为图像创建和操作提供灵活性。

```csharp
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 图像宽度 |
| 高度 | Int32 | 图像高度。 |
| 选项 | WebPOptions | 选项。 |
| loadOptions | LoadOptions | 加载选项。 |

### 另请参见

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions/)
* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(Stream, LoadOptions) {#constructor_5}

从流创建一个新的 [`WebPImage`](../) 类实例，并结合指定的加载选项和内存管理设置。此构造函数在从流加载 WebP 图像时提供灵活性，同时高效管理内存资源，确保在应用程序中实现最佳性能和资源利用率。

```csharp
public WebPImage(Stream stream, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流式 WebP 图像。 |
| loadOptions | LoadOptions | 加载选项。 |

### 另请参见

* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


