---
title: BmpImage
second_title: Aspose.Imaging for .NET API 参考
description: 初始化BmpImageaspose.imaging.fileformats.bmp/bmpimage类.
type: docs
weight: 10
url: /zh/aspose.imaging.fileformats.bmp/bmpimage/bmpimage/
---
## BmpImage(string) {#constructor_7}

初始化[`BmpImage`](../../bmpimage)类.

```csharp
public BmpImage(string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 从中加载图像和初始化像素和调色板数据的路径。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 光栅图像为空；光栅图像 |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | 高度应该是正数。 |
| ArgumentException | 应为每像素 8 位或更少的图像指定调色板。;调色板 |

### 例子

该示例显示如何从文件加载 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件中加载 BMP 图像。
// 如果需要，源像素将转换为 32-bpp 格式。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp"))
{
    // 做一些图像处理。
    // 保存到另一个 BMP 文件。
    bmpImage.Save(dir + "sample.output.32bpp.bmp");
}
```

### 也可以看看

* class [BmpImage](../../bmpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* 部件 [Aspose.Imaging](../../../)

---

## BmpImage(string, ushort, BitmapCompression, double, double) {#constructor_8}

初始化[`BmpImage`](../../bmpimage)类.

```csharp
public BmpImage(string path, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 从中加载图像和初始化像素和调色板数据的路径。 |
| bitsPerPixel | UInt16 | 每像素位数。 |
| compression | BitmapCompression | 要使用的压缩。 |
| horizontalResolution | Double | 水平分辨率。请注意，由于四舍五入，得到的分辨率可能与通过的略有不同。 |
| verticalResolution | Double | 垂直分辨率。请注意，由于四舍五入，得到的分辨率可能与通过的略有不同。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 光栅图像不能为空；rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | 高度应该是正数。 |
| ArgumentException | 应为每像素 8 位或更少的图像指定调色板。;调色板 |

### 例子

该示例显示如何从具有指定位深度和分辨率的文件加载 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件中加载 BMP 图像。
// 如果需要，源像素将转换为 24-bpp 格式。
// 分辨率将设置为 96 dpi。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
    new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp", 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    // 做一些图像处理。
    // 保存到另一个 BMP 文件。
    bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
}
```

### 也可以看看

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* 部件 [Aspose.Imaging](../../../)

---

## BmpImage(Stream) {#constructor_5}

初始化[`BmpImage`](../../bmpimage)类.

```csharp
public BmpImage(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于从中加载图像并用于初始化像素和调色板数据的流。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 光栅图像不能为空；rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | 高度应该是正数。 |
| ArgumentException | 应为每像素 8 位或更少的图像指定调色板。;调色板 |

### 例子

该示例展示了如何从文件流中加载 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流中加载 BMP 图像。
// 如果需要，源像素将转换为 32-bpp 格式。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream))
    {
        // 做一些图像处理。
        // 保存到另一个 BMP 文件。
        bmpImage.Save(dir + "sample.output.32bpp.bmp");
    }
}
```

### 也可以看看

* class [BmpImage](../../bmpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* 部件 [Aspose.Imaging](../../../)

---

## BmpImage(Stream, ushort, BitmapCompression, double, double) {#constructor_6}

初始化[`BmpImage`](../../bmpimage)类.

```csharp
public BmpImage(Stream stream, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于从中加载图像并用于初始化像素和调色板数据的流。 |
| bitsPerPixel | UInt16 | 每像素位数。 |
| compression | BitmapCompression | 要使用的压缩。 |
| horizontalResolution | Double | 水平分辨率。请注意，由于四舍五入，得到的分辨率可能与通过的略有不同。 |
| verticalResolution | Double | 垂直分辨率。请注意，由于四舍五入，得到的分辨率可能与通过的略有不同。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 光栅图像不能为空；rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | 高度应该是正数。 |
| ArgumentException | 应为每像素 8 位或更少的图像指定调色板。;调色板 |

### 例子

该示例显示如何从具有指定位深度和分辨率的文件流中加载 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流中加载 BMP 图像。
// 如果需要，源像素将转换为 24-bpp 格式。
// 分辨率将设置为 96 dpi。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
        new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // 做一些图像处理。
        // 保存到另一个 BMP 文件。
        bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
    }
}
```

### 也可以看看

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* 部件 [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage) {#constructor}

初始化[`BmpImage`](../../bmpimage)类.

```csharp
public BmpImage(RasterImage rasterImage)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 用于初始化像素和调色板数据的图像。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 光栅图像不能为空；rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | 高度应该是正数。 |
| ArgumentException | 应为每像素 8 位或更少的图像指定调色板。;调色板 |

### 例子

该示例显示如何从 RasterImage 的另一个实例加载 BmpImage。

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

    // 基于PNG图片创建BMP图片。
    // 如果需要，源像素将转换为 32-bpp 格式。
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage))
    {
        // 保存到 BMP 文件
        bmpImage.Save(dir + "output.32bpp.bmp");
    }
}
```

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [BmpImage](../../bmpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* 部件 [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage, ushort, BitmapCompression, double, double) {#constructor_1}

初始化[`BmpImage`](../../bmpimage)类.

```csharp
public BmpImage(RasterImage rasterImage, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 用于初始化像素和调色板数据的图像。 |
| bitsPerPixel | UInt16 | 每像素位数。 |
| compression | BitmapCompression | 要使用的压缩。 |
| horizontalResolution | Double | 水平分辨率。请注意，由于四舍五入，得到的分辨率可能与通过的略有不同。 |
| verticalResolution | Double | 垂直分辨率。请注意，由于四舍五入，得到的分辨率可能与通过的略有不同。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 光栅图像不能为空；rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | 高度应该是正数。 |
| ArgumentException | 应为每像素 8 位或更少的图像指定调色板。;调色板 |

### 例子

该示例显示如何从具有指定位深度和压缩的 RasterImage 的另一个实例加载 BmpImage。

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

    // 基于PNG图片创建BMP图片。
    // 如果需要，源像素将转换为 24-bpp 格式。
    // 分辨率将设置为 96 dpi。
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // 保存到 BMP 文件
        bmpImage.Save(dir + "output.24bpp.96dpi.bmp");
    }
}
```

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* 部件 [Aspose.Imaging](../../../)

---

## BmpImage(int, int) {#constructor_2}

初始化[`BmpImage`](../../bmpimage)类.

```csharp
public BmpImage(int width, int height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 图像宽度。 |
| height | Int32 | 图像高度。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | 高度应该是正数。 |
| ArgumentException | 应为每像素 8 位或更少的图像指定调色板。;调色板 |

### 例子

该示例显示了如何创建指定大小的 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100 x 100 像素的 32-bpp BMP 图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // 用红色填充整个图像。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // 保存到 BMP 文件
    bmpImage.Save(dir + "output.bmp");
}
```

以下示例显示如何对 BMP 图像进行托盘化以减小其输出大小。

```csharp
[C#]

// 创建一个 100 x 100 像素的 BMP 图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // 从图像左上角到右下角的线性渐变。
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // 用线性渐变画笔填充整个图像。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // 获取覆盖尽可能多像素的最接近的 8 位调色板，以便调色图像
    // 在视觉上几乎与非托盘化的没有区别。
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

// 输出如下所示：
// 调色后的图片大小为 11078 字节。
// 非调色图像大小为 40054 字节。
```

### 也可以看看

* class [BmpImage](../../bmpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* 部件 [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette) {#constructor_3}

初始化[`BmpImage`](../../bmpimage)类.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 图像宽度。 |
| height | Int32 | 图像高度。 |
| bitsPerPixel | UInt16 | 每像素位数。 |
| palette | IColorPalette | 调色板。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | 高度应该是正数。 |
| ArgumentException | 应为每像素 8 位或更少的图像指定调色板。;调色板 |

### 例子

该示例展示了如何使用指定的调色板创建指定大小的 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// 创建一个只包含红色和绿色的单色调色板。
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// 创建一个 100 x 100 像素的单色 1-bpp BMP 图像。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // 用红色填充图像的上半部分。
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // 用绿色填充图像的下半部分。
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // 保存到 BMP
    bmpImage.Save(dir + "output.monochrome.bmp");
}
```

### 也可以看看

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [BmpImage](../../bmpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* 部件 [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette, BitmapCompression, double, double) {#constructor_4}

初始化[`BmpImage`](../../bmpimage)类.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette, 
    BitmapCompression compression, double horizontalResolution, double verticalResolution)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | Int32 | 图像宽度。 |
| height | Int32 | 图像高度。 |
| bitsPerPixel | UInt16 | 每像素位数。 |
| palette | IColorPalette | 调色板。 |
| compression | BitmapCompression | 要使用的压缩。 |
| horizontalResolution | Double | 水平分辨率。请注意，由于四舍五入，得到的分辨率可能与通过的略有不同。 |
| verticalResolution | Double | 垂直分辨率。请注意，由于四舍五入，得到的分辨率可能与通过的略有不同。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | 高度应该是正数。 |
| ArgumentException | 应为每像素 8 位或更少的图像指定调色板。;调色板 |

### 例子

该示例展示了如何使用各种选项创建 BmpImage。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// 创建一个只包含红色和绿色的单色调色板。
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// 创建一个 100 x 100 像素的单色 1-bpp BMP 图像。
// 水平和垂直分辨率将设置为 96 dpi。
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // 用红色填充图像的上半部分。
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // 用绿色填充图像的下半部分。
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // 保存到 BMP 文件
    bmpImage.Save(dir + "output.monochrome.96dpi.bmp");
}
```

### 也可以看看

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* 命名空间 [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
