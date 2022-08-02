---
title: PngImage
second_title: Aspose.Imaging for .NET API 参考
description: 初始化PngImageaspose.imaging.fileformats.png/pngimage类.
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.png/pngimage/pngimage/
---
## PngImage(int, int) {#constructor_3}

初始化[`PngImage`](../../pngimage)类.

```csharp
public PngImage(int width, int height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 宽度. |
| height | Int32 | 高度。 |

### 例子

此示例说明如何创建指定大小的 PNG 图像，用纯色填充并将其保存到文件中。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    // 做一些图像处理，例如用红色填充整个图像。
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // 保存到文件。
    pngImage.Save(dir + "output.png");
}
```

### 也可以看看

* class [PngImage](../../pngimage)
* 命名空间 [Aspose.Imaging.FileFormats.Png](../../pngimage)
* 部件 [Aspose.Imaging](../../../)

---

## PngImage(string) {#constructor_6}

初始化[`PngImage`](../../pngimage)类.

```csharp
public PngImage(string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 加载图片的路径。 |

### 例子

此示例显示如何从文件加载 PNG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件中加载 PNG 图像。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // 将图像转换为灰度表示
    pngImage.Grayscale();

    // 保存到文件。
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### 也可以看看

* class [PngImage](../../pngimage)
* 命名空间 [Aspose.Imaging.FileFormats.Png](../../pngimage)
* 部件 [Aspose.Imaging](../../../)

---

## PngImage(RasterImage) {#constructor_1}

初始化[`PngImage`](../../pngimage)类.

```csharp
public PngImage(RasterImage rasterImage)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 光栅图像。 |

### 例子

此示例显示如何从 BMP 图像加载 PNG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从 BMP 图像加载 TrueColor PNG 图像。
// 首先，创建一个临时 BMP 图像，作为构建 PNG 图像的基础。
// 您也可以从文件中加载 BMP 图像或使用任何其他光栅格式的图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // 用红色填充整个 BMP 图像。
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

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [PngImage](../../pngimage)
* 命名空间 [Aspose.Imaging.FileFormats.Png](../../pngimage)
* 部件 [Aspose.Imaging](../../../)

---

## PngImage(string, PngColorType) {#constructor_7}

初始化[`PngImage`](../../pngimage)类.

```csharp
public PngImage(string path, PngColorType colorType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 加载图片的路径。 |
| colorType | PngColorType | 颜色类型。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException |  |

### 例子

此示例说明如何从具有指定颜色类型的文件加载 PNG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件中加载 PNG 图像。
// 注意彩色图像会自动转换为灰度。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png", Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // 保存到文件。
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### 也可以看看

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* 命名空间 [Aspose.Imaging.FileFormats.Png](../../pngimage)
* 部件 [Aspose.Imaging](../../../)

---

## PngImage(RasterImage, PngColorType) {#constructor_2}

初始化[`PngImage`](../../pngimage)类.

```csharp
public PngImage(RasterImage rasterImage, PngColorType colorType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 光栅图像。 |
| colorType | PngColorType | 颜色类型。 |

### 例子

此示例说明如何从具有指定颜色类型的 BMP 图像加载 PNG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从彩色 BMP 图像加载灰度 PNG 图像。
// 首先，创建一个临时 BMP 图像，作为构建 PNG 图像的基础。
// 您也可以从文件中加载 BMP 图像或使用任何其他光栅格式的图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // 用红色填充整个 BMP 图像。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // 图像像素的颜色将转换为对应的灰度。
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
    {
        pngImage.Save(dir + "output.grayscale.png");
    }
}
```

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* 命名空间 [Aspose.Imaging.FileFormats.Png](../../pngimage)
* 部件 [Aspose.Imaging](../../../)

---

## PngImage(Stream) {#constructor_5}

初始化[`PngImage`](../../pngimage)类.

```csharp
public PngImage(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 加载图像的流。 |

### 例子

此示例说明如何从文件或文件流加载 PNG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流中加载 PNG 图像。
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

### 也可以看看

* class [PngImage](../../pngimage)
* 命名空间 [Aspose.Imaging.FileFormats.Png](../../pngimage)
* 部件 [Aspose.Imaging](../../../)

---

## PngImage(int, int, PngColorType) {#constructor_4}

初始化[`PngImage`](../../pngimage)类.

```csharp
public PngImage(int width, int height, PngColorType colorType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 宽度. |
| height | Int32 | 高度。 |
| colorType | PngColorType | 颜色类型。 |

### 例子

此示例说明如何使用指定颜色类型创建指定大小的 PNG 图像，用纯色填充它并将其保存到文件中。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的灰度 PNG 图像。
// 所有颜色都会自动转换为灰度格式。
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // 做一些图像处理，例如用红色填充整个图像。
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // 保存到文件。
    pngImage.Save(dir + "output.grayscale.png");
}
```

### 也可以看看

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* 命名空间 [Aspose.Imaging.FileFormats.Png](../../pngimage)
* 部件 [Aspose.Imaging](../../../)

---

## PngImage(PngOptions, int, int) {#constructor}

初始化[`PngImage`](../../pngimage)类.

```csharp
public PngImage(PngOptions pngOptions, int width, int height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pngOptions | PngOptions | png 选项. |
| width | Int32 | 宽度. |
| height | Int32 | 高度。 |

### 例子

这个例子展示了如何使用指定的选项创建一个 PNG 图像，用线性渐变颜色填充它并将其保存到文件中。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// 每个颜色通道的位数
createOptions.BitDepth = 8;

// 每个像素是一个（红、绿、蓝）三元组，后跟 alpha 分量。
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

### 也可以看看

* class [PngOptions](../../../aspose.imaging.imageoptions/pngoptions)
* class [PngImage](../../pngimage)
* 命名空间 [Aspose.Imaging.FileFormats.Png](../../pngimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
