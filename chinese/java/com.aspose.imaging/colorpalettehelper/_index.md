---
title: "ColorPaletteHelper"
second_title: "Aspose.Imaging for Java API 参考"
description: "用于颜色调色板操作的辅助类。"
type: docs
weight: 29
url: /zh/java/com.aspose.imaging/colorpalettehelper/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

用于颜色调色板操作的辅助类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMonochrome()](#createMonochrome--) | 创建仅包含 2 种颜色的单色调色板。 |
| [create4Bit()](#create4Bit--) | 创建 4 位颜色调色板。 |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | 创建 4 位灰度调色板。 |
| [create8Bit()](#create8Bit--) | 创建 8 位颜色调色板。 |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | 创建 8 位灰度调色板。 |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-) | 在图像没有调色板的情况下，从光栅图像获取调色板（对图像进行调色）。 |
| [getCloseTransparentImagePalette(RasterImage image, int entriesCount)](#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-) | 在图像没有调色板的情况下，从光栅图像获取调色板（对图像进行调色）。 |
| [getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-) | 在图像没有调色板的情况下，从光栅图像获取调色板（对图像进行调色）。 |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-) | 在图像没有调色板的情况下，从光栅图像获取调色板（对图像进行调色）。 |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-) | 在图像没有调色板的情况下，从光栅图像获取调色板（对图像进行调色）。 |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-) | 在图像没有调色板的情况下，从光栅图像获取调色板（对图像进行调色）。 |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-) | 在图像没有调色板的情况下，从光栅图像获取调色板（对图像进行调色）。 |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.imaging.RasterImage-) | 获取统一的 256 色调色板。 |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.imaging.RasterImage-) | 获取 256 色调色板，由初始图像颜色值的高位组成。 |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.imaging.IColorPalette-) | 确定指定的调色板是否包含透明颜色。 |
| [createGrayscale(int bits)](#createGrayscale-int-) | 获取指定位数的灰度调色板。 |
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


创建仅包含 2 种颜色的单色调色板。

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Color palette for monochrome images.
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


创建 4 位颜色调色板。

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


创建 4 位灰度调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| minIsWhite | boolean | 如果设置为 `true`，调色板将以白色开始，否则以黑色开始。 |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


创建 8 位颜色调色板。

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


创建 8 位灰度调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| minIsWhite | boolean | 如果设置为 `true`，调色板将以白色开始，否则以黑色开始。 |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8 bit grayscale palette.

**Example: The following example creates a palettized grayscale BMP image and then saves it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.BmpOptions createOptions = new com.aspose.imaging.imageoptions.BmpOptions();

// 保存到文件
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.palette8bit.bmp", false));

// 使用每像素 8 位以减小输出图像的大小。
createOptions.setBitsPerPixel(8);

// 设置覆盖所有灰度颜色的标准 8 位灰度调色板。
// 如果处理后的图像仅包含灰度颜色，则其调色板化版本
// 在视觉上与未调色板化的图像没有区别。
createOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

// 保存时不使用压缩。
// 您还可以使用 RLE-8 压缩来减小输出图像的大小。
createOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

// 将水平和垂直分辨率设置为 96 dpi。
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

// 创建一个 100 x 100 像素的 BMP 图像并将其保存到文件。
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlack(),
            com.aspose.imaging.Color.getWhite());

    // 用灰度渐变填充图像
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save();
} finally {
    image.dispose();
}
```

### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


如果图像没有调色板，则从光栅图像获取颜色调色板（对图像进行调色板化）。如果调色板已存在，则直接使用它，而不进行计算。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |
| entriesCount | int | 所需的条目计数。 |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// 创建一个 100 x 100 像素的 BMP 图像。
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // 图像左上角到右下角的线性渐变。
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // 使用线性渐变画笔填充整个图像。
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // 获取最接近的 8 位颜色调色板，以覆盖尽可能多的像素，从而得到调色板图像
    // 几乎在视觉上与非调色的图像没有区别。
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // 8 位调色板最多包含 256 种颜色。
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();
    saveOptions.setPalette(palette);
    saveOptions.setBitsPerPixel(8);

    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream, saveOptions);
        System.out.println("The palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }

    stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream);
        System.out.println("The non-palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}

// 输出如下：
// 调色后的图像大小为 11078 字节。
// 非调色的图像大小为 40054 字节。
```

### getCloseTransparentImagePalette(RasterImage image, int entriesCount) {#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseTransparentImagePalette(RasterImage image, int entriesCount)
```


如果图像没有调色板，则从光栅图像获取颜色调色板（对图像进行调色板化）。如果调色板已存在，则直接使用它，而不进行计算。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |
| entriesCount | int | 所需的条目计数。 |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)
```


如果图像没有调色板，则从光栅图像获取颜色调色板（对图像进行调色板化）。调色板将被优化以获得更好的索引图像质量，或者在使用 PaletteMiningMethod.UseCurrentPalette 时保持"AS IS"。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |
| entriesCount | int | 所需的条目计数。 |
| paletteMiningMethod | int | 调色板挖掘方法。 |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// 加载 png 图像        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // 使用索引颜色类型
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // 使用最大压缩
    options.setCompressionLevel(9);
    // 获取最接近的 8 位颜色调色板，以覆盖尽可能多的像素，从而得到调色板图像
    // 几乎在视觉上与非调色的图像没有区别。
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// 输出文件大小应显著减小
```

### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


如果图像没有调色板，则从光栅图像获取颜色调色板（对图像进行调色板化）。如果调色板已存在，则直接使用它，而不进行计算。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | 目标图像的边界。 |
| entriesCount | int | 所需的条目计数。 |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


如果图像没有调色板，则从光栅图像获取颜色调色板（对图像进行调色板化）。如果调色板已存在，则直接使用它，而不进行计算。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | 目标图像的边界。 |
| entriesCount | int | 所需的条目计数。 |
| useImagePalette | boolean | 如果设置，则在可用时使用其自身的图像调色板 |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)
```


如果图像没有调色板，则从光栅图像获取颜色调色板（对图像进行调色板化）。如果调色板已存在，则直接使用它，而不进行计算。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | 目标图像的边界。 |
| entriesCount | int | 所需的条目计数。 |
| useImagePalette | boolean | 如果设置，则在可用时使用其自身的图像调色板 |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | 用于半透明 alpha 替换的背景颜色。 |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)
```


如果图像没有调色板，则从光栅图像获取颜色调色板（对图像进行调色板化）。如果调色板已存在，则直接使用它，而不进行计算。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 光栅图像。 |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | 目标图像的边界。 |
| entriesCount | int | 所需的条目计数。 |
| useImagePalette | boolean | 如果设置，则在可用时使用其自身的图像调色板 |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | 用于半透明 alpha 替换的背景颜色。 |
| keepTransparency | boolean | 如果设置，则会考虑图像颜色的 alpha 通道位。 |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


获取统一的 256 色调色板。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 图像。 |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


获取 256 色调色板，由初始图像颜色值的高位组成。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 图像。 |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.imaging.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


确定指定的调色板是否包含透明颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | 调色板。 |

**Returns:**
布尔值 - `true` 表示指定的调色板具有透明颜色；否则为 `false`。
### createGrayscale(int bits) {#createGrayscale-int-}
```
public static IColorPalette createGrayscale(int bits)
```


获取指定位数的灰度调色板。允许的位值为 1、2、4、8。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 位 | int | 位计数。 |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Grayscale palette.
