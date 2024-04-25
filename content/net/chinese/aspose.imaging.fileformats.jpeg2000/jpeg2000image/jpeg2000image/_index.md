---
title: Jpeg2000Image
second_title: Aspose.Imaging for .NET API 参考
description: 初始化Jpeg2000Imageaspose.imaging.fileformats.jpeg2000/jpeg2000image类.
type: docs
weight: 10
url: /zh/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image(string) {#constructor_7}

初始化[`Jpeg2000Image`](../../jpeg2000image)类.

```csharp
public Jpeg2000Image(string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 从中加载图像和初始化像素和调色板数据的路径。 |

### 例子

此示例说明如何从文件加载 JPEG2000 图像并将其保存为 PNG。

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

### 也可以看看

* class [Jpeg2000Image](../../jpeg2000image)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* 部件 [Aspose.Imaging](../../../)

---

## Jpeg2000Image(string, int) {#constructor_8}

初始化[`Jpeg2000Image`](../../jpeg2000image)类.

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 从中加载图像并初始化像素和调色板数据的路径 |
| bitsPerPixel | Int32 | 每像素位数。 |

### 也可以看看

* class [Jpeg2000Image](../../jpeg2000image)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* 部件 [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream) {#constructor_5}

初始化[`Jpeg2000Image`](../../jpeg2000image)类.

```csharp
public Jpeg2000Image(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于从中加载图像并用于初始化像素和调色板数据的流。 |

### 例子

此示例说明如何从文件流加载 JPEG2000 图像并将其保存为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从流中加载 JPEG2000 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jp2"))
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(stream))
{
    // 保存为 PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 也可以看看

* class [Jpeg2000Image](../../jpeg2000image)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* 部件 [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream, int) {#constructor_6}

初始化[`Jpeg2000Image`](../../jpeg2000image)类.

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于从中加载图像并用于初始化像素和调色板数据的流。 |
| bitsPerPixel | Int32 | 每像素位数。 |

### 也可以看看

* class [Jpeg2000Image](../../jpeg2000image)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* 部件 [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int) {#constructor_2}

初始化[`Jpeg2000Image`](../../jpeg2000image)类.

```csharp
public Jpeg2000Image(int width, int height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 图像宽度 |
| height | Int32 | 图像高度 |

### 例子

此示例说明如何创建 JPEG2000 图像并将其保存到文件中。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 JPEG2000 图像。
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // 用红色填充整个图像。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // 保存到文件
    jpeg2000Image.Save(dir + "sample.output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
}
```

### 也可以看看

* class [Jpeg2000Image](../../jpeg2000image)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* 部件 [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, Jpeg2000Options) {#constructor_3}

初始化[`Jpeg2000Image`](../../jpeg2000image)类.

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 图像宽度 |
| height | Int32 | 图像高度 |
| options | Jpeg2000Options | 选项。 |

### 例子

此示例显示如何创建 PNG 图像并将其保存为 JPEG2000 并使用所需的选项。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // 用红色填充整个图像。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // 使用不可逆离散小波变换 9-7
    saveOptions.Irreversible = true;

    // JP2 是 JPEG 2000 码流的“容器”格式。
    // J2K 是原始压缩数据，没有包装器。
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // 保存到文件
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

此示例说明如何使用所需选项创建 JPEG2000 图像并将其保存到文件中。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// 使用不可逆离散小波变换 9-7
createOptions.Irreversible = true;

// JP2 是 JPEG 2000 码流的“容器”格式。
// J2K 是原始压缩数据，没有包装器。
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// 创建一个 100x100 像素的 JPEG2000 图像。
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // 用红色填充整个图像。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // 保存到文件
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### 也可以看看

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options)
* class [Jpeg2000Image](../../jpeg2000image)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* 部件 [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, int) {#constructor_4}

初始化[`Jpeg2000Image`](../../jpeg2000image)类.

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 图像宽度 |
| height | Int32 | 图像高度 |
| bitsCount | Int32 | 位计数。 |

### 也可以看看

* class [Jpeg2000Image](../../jpeg2000image)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* 部件 [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage) {#constructor}

初始化[`Jpeg2000Image`](../../jpeg2000image)类.

```csharp
public Jpeg2000Image(RasterImage image)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 图片。 |

### 例子

此示例说明如何使用另一个光栅图像创建 JPEG2000 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // 用红色填充整个图像。
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // 基于PNG图像创建JPEG2000图像。
    using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(pngImage))
    {
        // 保存到文件
        jpeg2000Image.Save(dir + "output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
    }
}
```

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* 部件 [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage, int) {#constructor_1}

初始化[`Jpeg2000Image`](../../jpeg2000image)类.

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 用于初始化像素和调色板数据的图像。 |
| bitsPerPixel | Int32 | 每像素位数。 |

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* 命名空间 [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
