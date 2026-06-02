---
title: "PngOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "使用我们的 API 轻松创建高质量的便携式网络图形（PNG）栅格图像，提供可自定义的压缩级别、每像素位深度和 Alpha 位。"
type: docs
weight: 38
url: /zh/java/com.aspose.imaging.imageoptions/pngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

使用我们的 API 轻松创建高质量的便携式网络图形（PNG）栅格图像，提供可自定义的压缩级别、每像素位深度和 Alpha 位。无缝处理 XMP 元数据容器，确保全面的图像元数据管理，并让您轻松根据精确规格定制 PNG 图像。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PngOptions()](#PngOptions--) | 初始化一个新的 `PngOptions` 类实例。 |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.imaging.imageoptions.PngOptions-) | 初始化一个新的 `PngOptions` 类实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | 默认压缩级别。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColorType()](#getColorType--) | 获取颜色的类型。 |
| [setColorType(int value)](#setColorType-int-) | 设置颜色的类型。 |
| [getProgressive()](#getProgressive--) | 获取指示 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 是否为渐进式的值。 |
| [setProgressive(boolean value)](#setProgressive-boolean-) | 设置指示 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 是否为渐进式的值。 |
| [getFilterType()](#getFilterType--) | 获取在 PNG 文件保存过程中使用的过滤器类型。 |
| [setFilterType(int value)](#setFilterType-int-) | 设置在 PNG 文件保存过程中使用的过滤器类型。 |
| [getCompressionLevel()](#getCompressionLevel--) | 获取 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 的压缩级别。 |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | 设置 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 的压缩级别。 |
| [getPngCompressionLevel()](#getPngCompressionLevel--) | 获取 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 的压缩级别。 |
| [setPngCompressionLevel(int value)](#setPngCompressionLevel-int-) | 设置 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 的压缩级别。 |
| [getBitDepth()](#getBitDepth--) | 获取位深度值，范围为 1、2、4、8、16。 |
| [setBitDepth(byte value)](#setBitDepth-byte-) | 设置位深度值，范围为 1、2、4、8、16。 |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
此示例演示了如何使用 SaveOptions 命名空间中的不同类进行导出。将类型为 Gif 的图像加载到 Image 实例中，然后导出为多种格式。
``` java
String dir = "c:\\temp\\";

//在 Image 类的实例中加载现有的（Gif 类型）图像
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //使用默认选项导出为 BMP 文件格式
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //使用默认选项导出为 JPEG 文件格式
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //使用默认选项导出为 PNG 文件格式
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //使用默认选项导出为 TIFF 文件格式
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to PNG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.png");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PngOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // 仅导出前两页。实际上，由于 PNG 不是多页格式，只会光栅化一页。
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### PngOptions() {#PngOptions--}
```
public PngOptions()
```


初始化一个新的 `PngOptions` 类实例。

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.imaging.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


初始化一个新的 `PngOptions` 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | PNG 选项。 |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


默认压缩级别。

### getColorType() {#getColorType--}
```
public final int getColorType()
```


获取颜色的类型。

值：颜色的类型。

**Returns:**
int - 颜色的类型。
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


设置颜色的类型。

值：颜色的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 颜色的类型。 |


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
    // 获取最接近的 8 位颜色调色板，覆盖尽可能多的像素，以便调色板图像
    // 几乎在视觉上与非调色板图像无法区分。
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// 输出文件大小应显著减小
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// 创建 100x100 像素的 PNG 图像。
// 您也可以从文件或流中加载任何受支持格式的图像。
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // 使用蓝色透明渐变填充图像。
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // 使用渐进式加载。
    saveOptions.setProgressive(true);

    // 将水平和垂直分辨率设置为每英寸 96 像素。
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // 每个像素是一个 (红, 绿, 蓝) 三元组，随后是 alpha 通道。
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // 设置最大压缩级别。
    saveOptions.setCompressionLevel(9);

    // 这是最佳压缩，但执行时间最慢。
    // 自适应过滤意味着保存过程会为每行数据选择最合适的过滤器。
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // 每个通道的位数。
    saveOptions.setBitDepth((byte) 8);

    // 保存到文件。
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getProgressive() {#getProgressive--}
```
public final boolean getProgressive()
```


获取指示 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 是否为渐进式的值。

值：`` 如果为渐进式；否则为 ``。

**Returns:**
布尔型 - 指示 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 是否为渐进式的值。
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public final void setProgressive(boolean value)
```


设置指示 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 是否为渐进式的值。

值：`` 如果为渐进式；否则为 ``。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 指示 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 是否为渐进式的值。 |


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
    // 获取最接近的 8 位颜色调色板，覆盖尽可能多的像素，以便调色板图像
    // 几乎在视觉上与非调色板图像无法区分。
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// 输出文件大小应显著减小
```


**Example: This example shows how to create a PNG image with the specified options, fill it with a linear gradient colors and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();

// 每个颜色通道的位数
createOptions.setBitDepth((byte) 8);

// 每个像素是一个 (红, 绿, 蓝) 三元组，随后是 alpha 分量。
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

// 最大压缩级别。
createOptions.setCompressionLevel(9);

// 使用过滤器可以更有效地压缩连续色调图像。
createOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Sub);

// 使用渐进式加载
createOptions.setProgressive(true);

// 使用自定义参数创建 PNG 图像。
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(createOptions, 100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // 用半透明渐变填充图像。
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // 保存到文件。
    pngImage.save(dir + "output.explicitoptions.png");
} finally {
    pngImage.dispose();
}
```

### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


获取在 PNG 文件保存过程中使用的过滤器类型。

**Returns:**
int - 在 png 文件保存过程中使用的过滤器类型。
### setFilterType(int value) {#setFilterType-int-}
```
public final void setFilterType(int value)
```


设置在 PNG 文件保存过程中使用的过滤器类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 在 png 文件保存过程中使用的过滤器类型。 |


**Example: The following example shows how different filter types affect the size of the output PNG image.**

``` java

// 帮助类
class Utils {
    public String getPngFilterTypeString(int filterType) {
        switch (filterType) {
            case com.aspose.imaging.fileformats.png.PngFilterType.None:
                return "None";

            case com.aspose.imaging.fileformats.png.PngFilterType.Up:
                return "Up";

            case com.aspose.imaging.fileformats.png.PngFilterType.Sub:
                return "Sub";

            case com.aspose.imaging.fileformats.png.PngFilterType.Paeth:
                return "Paeth";

            case com.aspose.imaging.fileformats.png.PngFilterType.Avg:
                return "Avg";

            case com.aspose.imaging.fileformats.png.PngFilterType.Adaptive:
                return "Adaptive";

            default:
                throw new IllegalArgumentException("filterType");
        }
    }
}

// 以下是主要示例
Utils utils = new Utils();

int[] filterTypes = new int[]
        {
                com.aspose.imaging.fileformats.png.PngFilterType.None,
                com.aspose.imaging.fileformats.png.PngFilterType.Up,
                com.aspose.imaging.fileformats.png.PngFilterType.Sub,
                com.aspose.imaging.fileformats.png.PngFilterType.Paeth,
                com.aspose.imaging.fileformats.png.PngFilterType.Avg,
                com.aspose.imaging.fileformats.png.PngFilterType.Adaptive,
        };

for (int filterType : filterTypes) {
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
    try {
        // 设置过滤器类型
        options.setFilterType(filterType);

        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            image.save(stream, options);
            System.out.printf("The filter type is %s, the output image size is %s bytes.", utils.getPngFilterTypeString(filterType), stream.size());
        } finally {
            stream.close();
        }
    } finally {
        image.dispose();
    }
}

//输出可能如下所示：
//过滤器类型为 None，输出图像大小为 116845 字节。
//过滤器类型为 Up，输出图像大小为 86360 字节。
//过滤器类型为 Sub，输出图像大小为 94907 字节。
//过滤器类型为 Paeth，输出图像大小为 86403 字节。
//过滤器类型为 Avg，输出图像大小为 89956 字节。
//过滤器类型为 Adaptive，输出图像大小为 97248 字节。
```

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


获取 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 的压缩级别。

**Returns:**
int - [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 的压缩级别。
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


设置 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 的压缩级别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 的压缩级别。 |


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
    // 获取最接近的 8 位颜色调色板，覆盖尽可能多的像素，以便调色板图像
    // 几乎在视觉上与非调色板图像无法区分。
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// 输出文件大小应显著减小
```


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// 创建 100x100 像素的 PNG 图像。
// 您也可以从文件或流中加载任何受支持格式的图像。
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // 使用蓝色透明渐变填充图像。
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // 使用渐进式加载。
    saveOptions.setProgressive(true);

    // 将水平和垂直分辨率设置为每英寸 96 像素。
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // 每个像素是一个 (红, 绿, 蓝) 三元组，随后是 alpha 通道。
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // 设置最大压缩级别。
    saveOptions.setCompressionLevel(9);

    // 这是最佳压缩，但执行时间最慢。
    // 自适应过滤意味着保存过程会为每行数据选择最合适的过滤器。
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // 每个通道的位数。
    saveOptions.setBitDepth((byte) 8);

    // 保存到文件。
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getPngCompressionLevel() {#getPngCompressionLevel--}
```
public final int getPngCompressionLevel()
```


获取 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 的压缩级别。

**Returns:**
int - [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 的压缩级别。
### setPngCompressionLevel(int value) {#setPngCompressionLevel-int-}
```
public final void setPngCompressionLevel(int value)
```


设置 [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 的压缩级别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) 的压缩级别。 |

### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


获取位深度值，范围为 1、2、4、8、16。

注意以下限制：

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Returns:**
byte - 位深度值范围为 1、2、4、8、16。
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public final void setBitDepth(byte value)
```


设置位深度值，范围为 1、2、4、8、16。

注意以下限制：

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte | 位深度值范围为 1、2、4、8、16。 |


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// 创建 100x100 像素的 PNG 图像。
// 您也可以从文件或流中加载任何受支持格式的图像。
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // 使用蓝色透明渐变填充图像。
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // 使用渐进式加载。
    saveOptions.setProgressive(true);

    // 将水平和垂直分辨率设置为每英寸 96 像素。
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // 每个像素是一个 (红, 绿, 蓝) 三元组，随后是 alpha 通道。
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // 设置最大压缩级别。
    saveOptions.setCompressionLevel(9);

    // 这是最佳压缩，但执行时间最慢。
    // 自适应过滤意味着保存过程会为每行数据选择最合适的过滤器。
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // 每个通道的位数。
    saveOptions.setBitDepth((byte) 8);

    // 保存到文件。
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

