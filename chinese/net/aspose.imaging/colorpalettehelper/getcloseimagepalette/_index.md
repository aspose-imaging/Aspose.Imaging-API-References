---
title: GetCloseImagePalette
second_title: Aspose.Imaging for .NET API 参考
description: 从光栅图像获取调色板对图像进行调色板以防图像没有调色板如果调色板存在它将被用来代替执行计算
type: docs
weight: 60
url: /zh/net/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_3}

从光栅图像获取调色板（对图像进行调色板），以防图像没有调色板。如果调色板存在，它将被用来代替执行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 光栅图像。 |
| entriesCount | Int32 | 所需的条目计数。 |

### 返回值

调色板，从*image*中最常见的颜色开始，并包含*entriesCount*条目。

### 例子

以下示例加载 BMP 图像并使用各种保存选项将其保存回 BMP。

```csharp
[C#]

    // 创建一个 BMP 图像 100 x 100 px.
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

        // 获取覆盖尽可能多像素的最接近的 8 位调色板，以便调色板化的 image
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
    // 调色后的图片大小为11078字节.
// 非调色图像大小为 40054 字节。
```

以下示例显示如何对 BMP 图像进行托盘化以减小其输出大小。

```csharp
[C#]

    // 创建一个 BMP 图像 100 x 100 px.
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

        // 获取覆盖尽可能多像素的最接近的 8 位调色板，以便调色板化的 image
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
    // 调色后的图片大小为11078字节.
// 非调色图像大小为 40054 字节。
```

### 也可以看看

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* class [ColorPaletteHelper](../../colorpalettehelper)
* 命名空间 [Aspose.Imaging](../../colorpalettehelper)
* 部件 [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, int, PaletteMiningMethod) {#getcloseimagepalette_4}

从光栅图像获取调色板（对图像进行调色板），以防图像没有调色板。当使用 PaletteMiningMethod.UseCurrentPalette 时，Palette 即将进行优化以获得更好的索引图像质量或“按原样”拍摄。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 光栅图像。 |
| entriesCount | Int32 | 所需的条目计数。 |
| paletteMiningMethod | PaletteMiningMethod | 调色板挖掘方法。 |

### 返回值

调色板，从*image*中最常见的颜色开始，并包含*entriesCount*条目。

### 例子

以下示例显示如何使用索引颜色和最适合的调色板压缩 PNG 图像

```csharp
[C#]

    // 加载 png 图片 
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
                 // 使用索引颜色 type
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
                 // 使用最大压缩
         CompressionLevel = 9,
          // 获取覆盖尽可能多像素的最接近的 8 位调色板，以便调色板化的 image
             // 在视觉上几乎与非托盘化的没有区别。
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // 输出文件的大小应该会显着减小
```

### 也可以看看

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* enum [PaletteMiningMethod](../../paletteminingmethod)
* class [ColorPaletteHelper](../../colorpalettehelper)
* 命名空间 [Aspose.Imaging](../../colorpalettehelper)
* 部件 [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

从光栅图像获取调色板（对图像进行调色板），以防图像没有调色板。如果调色板存在，它将被用来代替执行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 光栅图像。 |
| destBounds | Rectangle | 目标图像边界。 |
| entriesCount | Int32 | 所需的条目计数。 |

### 返回值

调色板，从*image*中最常见的颜色开始，并包含*entriesCount*条目。

### 也可以看看

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* 命名空间 [Aspose.Imaging](../../colorpalettehelper)
* 部件 [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

从光栅图像获取调色板（对图像进行调色板），以防图像没有调色板。如果调色板存在，它将被用来代替执行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 光栅图像。 |
| destBounds | Rectangle | 目标图像边界。 |
| entriesCount | Int32 | 所需的条目计数。 |
| useImagePalette | Boolean | 如果设置，它将使用自己的图像调色板（如果可用） |

### 返回值

调色板，从*image*中最常见的颜色开始，并包含*entriesCount*条目。

### 也可以看看

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* 命名空间 [Aspose.Imaging](../../colorpalettehelper)
* 部件 [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color) {#getcloseimagepalette_2}

从光栅图像获取调色板（对图像进行调色板），以防图像没有调色板。如果调色板存在，它将被用来代替执行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 光栅图像。 |
| destBounds | Rectangle | 目标图像边界。 |
| entriesCount | Int32 | 所需的条目计数。 |
| useImagePalette | Boolean | 如果设置，它将使用自己的图像调色板（如果可用） |
| alphaBlendInColor | Color | 颜色应该用作半透明 alpha 替换的背景颜色。 |

### 返回值

调色板，从*image*中最常见的颜色开始，并包含*entriesCount*条目。

### 也可以看看

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* struct [Color](../../color)
* class [ColorPaletteHelper](../../colorpalettehelper)
* 命名空间 [Aspose.Imaging](../../colorpalettehelper)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
