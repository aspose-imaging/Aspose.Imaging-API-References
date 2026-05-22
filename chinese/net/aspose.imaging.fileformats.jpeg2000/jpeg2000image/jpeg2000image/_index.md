---
title: "Jpeg2000Image.Jpeg2000Image"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Jpeg2000Image 构造函数。通过使用要加载的图像路径初始化一个新实例，开始使用 Jpeg2000Image 类。此构造函数可轻松访问 JPEG2000 图像，简化加载和处理图像文件的过程。提供文件路径后，您可以快速在应用程序中开始处理和操作 JPEG2000 图像。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image(string) {#constructor_7}

开始使用[`Jpeg2000Image`](../)类，通过使用要加载的图像路径初始化一个新实例。此构造函数可轻松访问 JPEG2000 图像，简化加载和处理图像文件的过程。提供文件路径后，您可以快速开始在应用程序中处理和操作 JPEG2000 图像。

```csharp
public Jpeg2000Image(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 加载图像的路径，并使用该路径初始化像素和调色板数据。 |

## 示例

此示例展示了如何从文件加载 JPEG2000 图像并将其保存为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 加载 JPEG2000 图像。
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
    // 保存为 PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(string, int) {#constructor_8}

通过创建包含文件路径和所需每像素位数参数的新实例，轻松入门[`Jpeg2000Image`](../)类。此构造函数允许对图像加载过程进行微调，确保与各种图像格式和质量设置兼容。凭借此灵活性，您可以高效地管理和操作符合特定需求的 JPEG2000 图像。

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 用于加载图像的路径以及用于初始化像素和调色板数据的路径 |
| bitsPerPixel | Int32 | 每像素位数。 |

### 另请参见

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream) {#constructor_5}

通过提供流对象，轻松初始化[`Jpeg2000Image`](../)类的新实例。此构造函数简化了直接从流加载 JPEG2000 图像的过程，为处理来自各种来源的图像数据提供了灵活性和便利性。

```csharp
public Jpeg2000Image(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像并初始化像素和调色板数据的流。 |

## 示例

此示例展示了如何从文件流加载 JPEG2000 图像并将其保存为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从流加载 JPEG2000 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jp2"))
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(stream))
{
    // 保存为 PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream, int) {#constructor_6}

使用流加载图像并提供每像素位数参数来初始化[`Jpeg2000Image`](../)类的新实例。此构造函数通过允许您指定图像数据源和所需的每像素位数，提供了更细致的图像加载过程控制。

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像并初始化像素和调色板数据的流。 |
| bitsPerPixel | Int32 | 每像素位数。 |

### 另请参见

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int) {#constructor_2}

创建[`Jpeg2000Image`](../)类的新实例，指定宽度和高度参数。此构造函数允许您使用特定尺寸初始化 JPEG2000 图像，对于需要以编程方式创建特定大小图像的场景非常有用。

```csharp
public Jpeg2000Image(int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 图像宽度 |
| 高度 | Int32 | 图像高度 |

## 示例

此示例展示了如何创建 JPEG2000 图像并将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建 100x100 像素的 JPEG2000 图像。
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // 将整幅图像填充为红色。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // 保存到文件
    jpeg2000Image.Save(dir + "sample.output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
}
```

### 另请参见

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, Jpeg2000Options) {#constructor_3}

实例化一个新的[`Jpeg2000Image`](../)对象，提供宽度、高度和图像选项参数。此构造函数允许创建具有特定尺寸和附加选项的 JPEG2000 图像，提供了图像生成的灵活性。

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 图像宽度 |
| 高度 | Int32 | 图像高度 |
| 选项 | Jpeg2000Options | 选项。 |

## 示例

此示例展示了如何创建 PNG 图像并使用所需选项将其保存为 JPEG2000。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // 将整幅图像填充为红色。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // 使用不可逆离散小波变换 9-7
    saveOptions.Irreversible = true;

    // JP2 是 JPEG 2000 码流的“容器”格式。
    // J2K 是未包装的原始压缩数据。
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // 保存到文件
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

此示例展示了如何创建具有所需选项的 JPEG2000 图像并将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// 使用不可逆离散小波变换 9-7
createOptions.Irreversible = true;

// JP2 是 JPEG 2000 码流的“容器”格式。
// J2K 是未包装的原始压缩数据。
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// 创建 100x100 像素的 JPEG2000 图像。
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // 将整幅图像填充为红色。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // 保存到文件
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### 另请参见

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options/)
* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, int) {#constructor_4}

使用宽度、高度和位计数参数创建[`Jpeg2000Image`](../)类的新实例。此构造函数允许创建具有特定尺寸和位深度的 JPEG2000 图像，为各种成像需求提供灵活性。

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 图像宽度 |
| 高度 | Int32 | 图像高度 |
| bitsCount | Int32 | 位计数。 |

### 另请参见

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage) {#constructor}

实例化一个新的[`Jpeg2000Image`](../)类，使用栅格图像。此构造函数便于从现有栅格图像创建 JPEG2000 图像，实现不同图像格式之间的无缝集成和转换。

```csharp
public Jpeg2000Image(RasterImage image)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 图像。 |

## 示例

此示例展示了如何从另一个栅格图像创建 JPEG2000 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // 将整幅图像填充为红色。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // 基于 PNG 图像创建 JPEG2000 图像。
    using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(pngImage))
    {
        // 保存到文件
        jpeg2000Image.Save(dir + "output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
    }
}
```

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage, int) {#constructor_1}

使用栅格图像和每像素位数参数初始化全新的[`Jpeg2000Image`](../)实例。此构造函数能够对生成的 JPEG2000 图像的质量和大小进行精确控制，非常适合对定制化要求严格的场景。

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 用于初始化像素和调色板数据的图像。 |
| bitsPerPixel | Int32 | 每像素位数。 |

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)


