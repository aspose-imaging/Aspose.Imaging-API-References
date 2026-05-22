---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ColorPaletteHelper 方法。获取栅格图像的颜色调色板；如果图像没有调色板，则为图像进行调色板化。如果调色板已存在，则直接使用它，而不进行计算。"
type: docs
weight: 70
url: /zh/net/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_4}

当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则使用现有调色板而不进行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 栅格图像。 |
| entriesCount | Int32 | 所需的条目数量。 |

### 返回值

颜色调色板，以 *image* 中最常见的颜色开始，并包含 *entriesCount* 条目。

## 示例

以下示例加载 BMP 图像并使用各种保存选项将其保存回 BMP。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 创建 BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // 使用每像素 8 位来减小输出图像的大小。
    saveOptions.BitsPerPixel = 8;

    // 设置最接近的 8 位颜色调色板，以覆盖最大数量的图像像素，从而得到调色后的图像
    // 几乎在视觉上与非调色板图像无差别。
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // 保存时不使用压缩。
    // 您也可以使用 RLE-8 压缩来减小输出图像的大小。
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // 将水平和垂直分辨率设置为 96 dpi。
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
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

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, int, PaletteMiningMethod) {#getcloseimagepalette_5}

当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。调色板将被优化以获得更好的索引图像质量，或在使用 PaletteMiningMethod.UseCurrentPalette 时保持"AS IS"。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 栅格图像。 |
| entriesCount | Int32 | 所需的条目数量。 |
| paletteMiningMethod | PaletteMiningMethod | 调色板挖掘方法。 |

### 返回值

颜色调色板，以 *image* 中最常见的颜色开始，并包含 *entriesCount* 条目。

## 示例

以下示例展示了如何压缩 PNG 图像，使用带最佳匹配调色板的索引颜色

```csharp
[C#]

// 加载 PNG 图像
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // 使用索引颜色类型
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // 使用最大压缩
         CompressionLevel = 9,
      // 获取最接近的 8 位颜色调色板，覆盖尽可能多的像素，以便调色板图像
         // 几乎在视觉上与非调色板图像无差别。
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // 输出文件大小应显著减小
```

### 另请参见

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* enum [PaletteMiningMethod](../../paletteminingmethod/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则使用现有调色板而不进行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 栅格图像。 |
| destBounds | Rectangle | 目标图像的边界。 |
| entriesCount | Int32 | 所需的条目数量。 |

### 返回值

颜色调色板，以 *image* 中最常见的颜色开始，并包含 *entriesCount* 条目。

### 另请参见

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则使用现有调色板而不进行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 栅格图像。 |
| destBounds | Rectangle | 目标图像的边界。 |
| entriesCount | Int32 | 所需的条目数量。 |
| useImagePalette | Boolean | 如果设置，则在可用时使用其自身的图像调色板 |

### 返回值

颜色调色板，以 *image* 中最常见的颜色开始，并包含 *entriesCount* 条目。

### 另请参见

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color) {#getcloseimagepalette_2}

当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则使用现有调色板而不进行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 栅格图像。 |
| destBounds | Rectangle | 目标图像的边界。 |
| entriesCount | Int32 | 所需的条目数量。 |
| useImagePalette | Boolean | 如果设置，则在可用时使用其自身的图像调色板 |
| alphaBlendInColor | 颜色 | 应作为半透明 alpha 替换的背景颜色使用的颜色。 |

### 返回值

颜色调色板，以 *image* 中最常见的颜色开始，并包含 *entriesCount* 条目。

### 另请参见

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color, bool) {#getcloseimagepalette_3}

当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则使用现有调色板而不进行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor, bool keepTransparency)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 栅格图像。 |
| destBounds | Rectangle | 目标图像的边界。 |
| entriesCount | Int32 | 所需的条目数量。 |
| useImagePalette | Boolean | 如果设置，则在可用时使用其自身的图像调色板 |
| alphaBlendInColor | 颜色 | 应作为半透明 alpha 替换的背景颜色使用的颜色。 |
| keepTransparency | Boolean | 如果设置，它将考虑图像颜色的 alpha 通道位。 |

### 返回值

颜色调色板，以 *image* 中最常见的颜色开始，并包含 *entriesCount* 条目。

### 另请参见

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)


