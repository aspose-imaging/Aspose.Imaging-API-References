---
title: "BmpImage.BmpImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "BmpImage 构造函数。使用此构造函数轻松开始使用 BmpImage 类，它会初始化一个新实例。非常适合希望快速高效使用 BmpImage 对象的开发者。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.bmp/bmpimage/bmpimage/
---
## BmpImage(string) {#constructor_7}

使用此构造函数轻松开始使用 BmpImage 类，它会初始化一个新实例。非常适合希望快速高效使用 [`BmpImage`](../) 对象的开发者。

```csharp
public BmpImage(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 加载图像的路径，并使用该路径初始化像素和调色板数据。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 光栅图像为空。 |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | 高度必须为正数。 |
| ArgumentException | 对于每像素 8 位或更少的图像，必须指定调色板。 |

## 示例

示例展示了如何从文件加载 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件加载 BMP 图像。
// 如果需要，源像素将被转换为 32 位每像素 格式。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp"))
{
    // 进行一些图像处理。
    // 保存为另一个 BMP 文件。
    bmpImage.Save(dir + "sample.output.32bpp.bmp");
}
```

### 另请参见

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(string, ushort, BitmapCompression, double, double) {#constructor_8}

使用此构造函数轻松创建 [`BmpImage`](../) 类的新实例，可指定路径、bitsPerPixel 和 compression 等参数。非常适合希望快速高效初始化 BmpImage 对象，并对图像特性进行精确控制的开发者。

```csharp
public BmpImage(string path, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 加载图像的路径，并使用该路径初始化像素和调色板数据。 |
| bitsPerPixel | UInt16 | 每像素位数。 |
| 压缩 | BitmapCompression | 要使用的压缩方式。 |
| horizontalResolution | Double | 水平分辨率。注意，由于四舍五入，得到的分辨率可能与传入的略有差异。 |
| verticalResolution | Double | 垂直分辨率。注意，由于四舍五入，得到的分辨率可能与传入的略有差异。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 光栅图像为空。 |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | 高度必须为正数。 |
| ArgumentException | 对于每像素 8 位或更少的图像，必须指定调色板。 |

## 示例

示例展示了如何使用指定的位深度和分辨率从文件加载 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件加载 BMP 图像。
// 如果需要，源像素将被转换为 24 位每像素 格式。
// 分辨率将设置为 96 dpi。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
    new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp", 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    // 进行一些图像处理。
    // 保存为另一个 BMP 文件。
    bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
}
```

### 另请参见

* enum [BitmapCompression](../../bitmapcompression/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(Stream) {#constructor_5}

通过此构造函数使用流作为输入，轻松初始化一个新实例，开始使用 [`BmpImage`](../) 类。非常适合希望以便捷方式处理来自各种数据源的 BmpImage 对象的开发者，确保灵活性和易于集成。

```csharp
public BmpImage(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像并初始化像素和调色板数据的流。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 光栅图像为空。 |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | 高度必须为正数。 |
| ArgumentException | 对于每像素 8 位或更少的图像，必须指定调色板。 |

## 示例

示例展示了如何从文件流加载 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 BMP 图像。
// 如果需要，源像素将被转换为 32 位每像素 格式。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream))
    {
        // 进行一些图像处理。
        // 保存为另一个 BMP 文件。
        bmpImage.Save(dir + "sample.output.32bpp.bmp");
    }
}
```

### 另请参见

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(Stream, ushort, BitmapCompression, double, double) {#constructor_6}

开始使用 [`BmpImage`](../) 类，通过使用流创建新实例，并指定 bitsPerPixel 和 compression 等参数。非常适合希望以简洁方式处理 BmpImage 对象的开发者，确保项目的灵活性和效率。

```csharp
public BmpImage(Stream stream, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像并初始化像素和调色板数据的流。 |
| bitsPerPixel | UInt16 | 每像素位数。 |
| 压缩 | BitmapCompression | 要使用的压缩方式。 |
| horizontalResolution | Double | 水平分辨率。注意，由于四舍五入，得到的分辨率可能与传入的略有差异。 |
| verticalResolution | Double | 垂直分辨率。注意，由于四舍五入，得到的分辨率可能与传入的略有差异。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 光栅图像为空。 |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | 高度必须为正数。 |
| ArgumentException | 对于每像素 8 位或更少的图像，必须指定调色板。 |

## 示例

示例展示了如何从文件流中加载具有指定位深度和分辨率的 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 BMP 图像。
// 如果需要，源像素将被转换为 24 位每像素 格式。
// 分辨率将设置为 96 dpi。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
        new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // 进行一些图像处理。
        // 保存为另一个 BMP 文件。
        bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
    }
}
```

### 另请参见

* enum [BitmapCompression](../../bitmapcompression/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage) {#constructor}

轻松通过使用 RasterImage 对象初始化来创建 [`BmpImage`](../) 类的新实例。非常适合希望无缝将现有光栅图像转换为 BmpImage 格式的开发者，确保兼容性并便于集成到项目中。

```csharp
public BmpImage(RasterImage rasterImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 用于初始化像素和调色板数据的图像。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 光栅图像为空。 |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | 高度必须为正数。 |
| ArgumentException | 对于每像素 8 位或更少的图像，必须指定调色板。 |

## 示例

示例展示了如何从另一个 RasterImage 实例加载 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个新的 PNG 图像。
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // 将整个 PNG 图像填充为红色。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // 基于 PNG 图像创建 BMP 图像。
    // 如果需要，源像素将被转换为 32 位每像素 格式。
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage))
    {
        // 保存为 BMP 文件
        bmpImage.Save(dir + "output.32bpp.bmp");
    }
}
```

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage, ushort, BitmapCompression, double, double) {#constructor_1}

开始使用 [`BmpImage`](../) 类，通过使用 rasterImage 创建新实例，并指定 bitsPerPixel 和 compression 等参数。非常适合希望以简洁方式处理 BmpImage 对象的开发者，确保项目的灵活性和效率。

```csharp
public BmpImage(RasterImage rasterImage, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 用于初始化像素和调色板数据的图像。 |
| bitsPerPixel | UInt16 | 每像素位数。 |
| 压缩 | BitmapCompression | 要使用的压缩方式。 |
| horizontalResolution | Double | 水平分辨率。注意，由于四舍五入，得到的分辨率可能与传入的略有差异。 |
| verticalResolution | Double | 垂直分辨率。注意，由于四舍五入，得到的分辨率可能与传入的略有差异。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 光栅图像为空。 |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | 高度必须为正数。 |
| ArgumentException | 对于每像素 8 位或更少的图像，必须指定调色板。 |

## 示例

示例展示了如何从另一个 RasterImage 实例加载具有指定位深度和 compression 的 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个新的 PNG 图像。
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // 将整个 PNG 图像填充为红色。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // 基于 PNG 图像创建 BMP 图像。
    // 如果需要，源像素将被转换为 24 位每像素 格式。
    // 分辨率将设置为 96 dpi。
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // 保存为 BMP 文件
        bmpImage.Save(dir + "output.24bpp.96dpi.bmp");
    }
}
```

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* enum [BitmapCompression](../../bitmapcompression/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(int, int) {#constructor_2}

轻松开始使用 [`BmpImage`](../) 类，通过创建具有指定宽度和高度参数的新实例。非常适合希望以便捷方式生成自定义尺寸 BmpImage 对象的开发者，确保项目的灵活性并便于集成。

```csharp
public BmpImage(int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 图像宽度。 |
| 高度 | Int32 | 图像高度。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | 高度必须为正数。 |
| ArgumentException | 对于每像素 8 位或更少的图像，必须指定调色板。 |

## 示例

示例展示了如何创建指定尺寸的 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100 x 100 像素的 32 位 BMP 图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // 将整幅图像填充为红色。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // 保存为 BMP 文件
    bmpImage.Save(dir + "output.bmp");
}
```

以下示例展示如何对 BMP 图像进行调色以减小其输出大小。

```csharp
[C#]

// 创建一个 100 x 100 像素的 BMP 图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // 图像左上角到右下角的线性渐变。
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // 使用线性渐变画刷填充整个图像。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // 获取最接近的 8 位颜色调色板，覆盖尽可能多的像素，以便调色板图像
    // 几乎在视觉上与非调色板图像无差别。
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // 8 位调色板最多包含 256 种颜色。
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// 输出如下：
// 调色后的图像大小为 11078 字节。
// 未调色的图像大小为 40054 字节。
```

### 另请参见

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette) {#constructor_3}

开始使用 [`BmpImage`](../) 类，通过使用宽度、高度、位深度和调色板等参数初始化新实例。非常适合希望以简洁方式创建具有自定义尺寸和颜色配置的 BmpImage 对象的开发者，确保项目的灵活性和效率。

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 图像宽度。 |
| 高度 | Int32 | 图像高度。 |
| bitsPerPixel | UInt16 | 每像素位数。 |
| palette | IColorPalette | 颜色调色板。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | 高度必须为正数。 |
| ArgumentException | 对于每像素 8 位或更少的图像，必须指定调色板。 |

## 示例

示例展示了如何使用指定的调色板创建指定尺寸的 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// 创建仅包含红色和绿色的单色调色板。
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// 创建一个 100 x 100 像素的单色 1-bpp BMP 图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // 将图像的上半部分填充为红色。
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // 将图像的下半部分填充为绿色。
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // 保存为 BMP
    bmpImage.Save(dir + "output.monochrome.bmp");
}
```

### 另请参见

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette, BitmapCompression, double, double) {#constructor_4}

使用此构造函数轻松创建 [`BmpImage`](../) 类的新实例，指定宽度、高度、bitsPerPixel 和调色板等参数。非常适合希望以便捷方式生成具有自定义尺寸和颜色配置的 BmpImage 对象的开发者，确保项目的灵活性并便于集成。

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette, 
    BitmapCompression compression, double horizontalResolution, double verticalResolution)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 图像宽度。 |
| 高度 | Int32 | 图像高度。 |
| bitsPerPixel | UInt16 | 每像素位数。 |
| palette | IColorPalette | 颜色调色板。 |
| 压缩 | BitmapCompression | 要使用的压缩方式。 |
| horizontalResolution | Double | 水平分辨率。注意，由于四舍五入，得到的分辨率可能与传入的略有差异。 |
| verticalResolution | Double | 垂直分辨率。注意，由于四舍五入，得到的分辨率可能与传入的略有差异。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | 高度必须为正数。 |
| ArgumentException | 对于每像素 8 位或更少的图像，必须指定调色板。 |

## 示例

示例展示了如何使用各种选项创建 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// 创建仅包含红色和绿色的单色调色板。
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// 创建一个 100 x 100 像素的单色 1-bpp BMP 图像。
// 水平和垂直分辨率将设置为 96 dpi。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // 将图像的上半部分填充为红色。
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // 将图像的下半部分填充为绿色。
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // 保存为 BMP 文件
    bmpImage.Save(dir + "output.monochrome.96dpi.bmp");
}
```

### 另请参见

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* enum [BitmapCompression](../../bitmapcompression/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


