---
title: WebPImage
second_title: Aspose.Imaging for .NET API 参考
description: 初始化WebPImageaspose.imaging.fileformats.webp/webpimage class 来自流.
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.webp/webpimage/webpimage/
---
## WebPImage(Stream) {#constructor_4}

初始化[`WebPImage`](../../webpimage) class 来自流.

```csharp
public WebPImage(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流 WebP 图像。 |

### 例子

此示例说明如何从文件流加载 WebP 图像并将其保存为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流中加载 WebP 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.webp"))
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(stream))
{
    // 保存为 PNG
    // 请注意，只有活动帧将存储到 PNG，因为 PNG 不是多页格式。
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 也可以看看

* class [WebPImage](../../webpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* 部件 [Aspose.Imaging](../../../)

---

## WebPImage(Stream, LoadOptions) {#constructor_5}

初始化[`WebPImage`](../../webpimage)流中的类.

```csharp
public WebPImage(Stream stream, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流 WebP 图像。 |
| loadOptions | LoadOptions | 负载选项。 |

### 也可以看看

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* 部件 [Aspose.Imaging](../../../)

---

## WebPImage(string) {#constructor_6}

初始化[`WebPImage`](../../webpimage)文件中的类.

```csharp
public WebPImage(string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | WebP 图像文件的路径 |

### 例子

此示例说明如何从文件加载 WebP 图像并将其保存为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件中加载 WebP 图像。
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // 保存为 PNG
    // 请注意，只有活动帧将存储到 PNG，因为 PNG 不是多页格式。
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 也可以看看

* class [WebPImage](../../webpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* 部件 [Aspose.Imaging](../../../)

---

## WebPImage(string, LoadOptions) {#constructor_7}

初始化[`WebPImage`](../../webpimage)文件中的类.

```csharp
public WebPImage(string path, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | WebP 图像文件的路径 |
| loadOptions | LoadOptions | 负载选项。 |

### 也可以看看

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* 部件 [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage) {#constructor}

初始化[`WebPImage`](../../webpimage)rasterImage. 中的类

```csharp
public WebPImage(RasterImage rasterImage)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 光栅图像。 |

### 例子

此示例说明如何从另一个光栅图像创建 WebP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 加载一个 100x100 像素的 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // 用红色填充整个图像。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // 基于PNG图片创建WebP图片。
    using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(pngImage))
    {
        // 使用默认选项保存到 WebP 文件
        webPImage.Save(dir + "output.webp", new Aspose.Imaging.ImageOptions.WebPOptions());
    }
}
```

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [WebPImage](../../webpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* 部件 [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage, LoadOptions) {#constructor_1}

初始化[`WebPImage`](../../webpimage)rasterImage. 中的类

```csharp
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 光栅图像。 |
| loadOptions | LoadOptions | 负载选项。 |

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* 部件 [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions) {#constructor_2}

初始化[`WebPImage`](../../webpimage)具有空图像的类。

```csharp
public WebPImage(int width, int height, WebPOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 图像宽度 |
| height | Int32 | 图像高度。 |
| options | WebPOptions | 选项。 |

### 例子

此示例说明如何从头开始创建具有指定选项的 WebP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
//createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.webp");

// 创建一个 100x100 像素的 WebP 图像。
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(webPImage);

    // 用红色填充整个图像。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, webPImage.Bounds);

    // 保存到 WebP 文件
    webPImage.Save(dir + "output.webp");
}
```

此示例说明如何使用指定选项创建多帧动画 WebP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// 默认帧加上 36 + 36 个附加帧。
createOptions.AnimLoopCount = 36 + 36 + 1;

// 创建一个 100x100 像素的 WebP 图像。
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // 第一个圆圈是红色的
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    //第二个圆圈是黑色的
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // 逐渐增加红色弧形的角度。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // 逐渐增加黑色弧线的角度，将红色弧线抹去。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // 保存到 WebP 文件
    webPImage.Save(dir + "output.webp");
}
```

### 也可以看看

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [WebPImage](../../webpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* 部件 [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions, LoadOptions) {#constructor_3}

初始化[`WebPImage`](../../webpimage)具有空图像的类。

```csharp
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 图像宽度 |
| height | Int32 | 图像高度。 |
| options | WebPOptions | 选项。 |
| loadOptions | LoadOptions | 负载选项。 |

### 也可以看看

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
