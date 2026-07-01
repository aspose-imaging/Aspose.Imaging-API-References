---
title: "PsdOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "使用我们的 API 创建 Photoshop 文档（PSD）图像，提供多种选项，包括不同的格式版本、压缩方式、颜色模式以及每个颜色通道的位数。"
type: docs
weight: 40
url: /zh/java/com.aspose.imaging.imageoptions/psdoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

使用我们的 API 创建 Photoshop 文档（PSD）图像，提供多种选项，包括不同的格式版本、压缩方式、颜色模式以及每个颜色通道的位数。无缝处理 XMP 元数据容器，确保通过 PSD 格式的图层、图层蒙版和文件信息等强大功能，实现全面的图像处理，为您的设计提供定制和创意的可能。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | 初始化 `PsdOptions` 类的新实例。 |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-) | 初始化 `PsdOptions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | 获取或设置 XMP 数据容器 |
| [getVersion()](#getVersion--) | 获取或设置 PSD 文件版本。 |
| [setVersion(int value)](#setVersion-int-) | 获取或设置 PSD 文件版本。 |
| [getCompressionMethod()](#getCompressionMethod--) | 获取或设置 PSD 压缩方法。 |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | 获取或设置 PSD 压缩方法。 |
| [getPsdVersion()](#getPsdVersion--) | 获取文件格式版本。 |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | 设置文件格式版本。 |
| [getColorMode()](#getColorMode--) | 获取或设置 PSD 颜色模式。 |
| [setColorMode(short value)](#setColorMode-short-) | 获取或设置 PSD 颜色模式。 |
| [getChannelBitsCount()](#getChannelBitsCount--) | 获取或设置每个颜色通道的位数。 |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | 获取或设置每个颜色通道的位数。 |
| [getChannelsCount()](#getChannelsCount--) | 获取颜色通道的数量。 |
| [setChannelsCount(short value)](#setChannelsCount-short-) | 设置颜色通道的数量。 |
| [isRemoveGlobalTextEngineResource()](#isRemoveGlobalTextEngineResource--) | 获取一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本层的 PSD 文件，仅在处理后无法在 Adobe Photoshop 中打开时（主要与缺失字体的文本层相关）。 |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | 设置一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本层的 PSD 文件，仅在处理后无法在 Adobe Photoshop 中打开时（主要与缺失字体的文本层相关）。 |
| [isRefreshImagePreviewData()](#isRefreshImagePreviewData--) | 获取一个值，指示是否 [刷新图像预览数据] - 该选项用于最大化与其他 PSD 图像查看器的兼容性。 |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | 设置一个值，指示是否 [刷新图像预览数据] - 该选项用于最大化与其他 PSD 图像查看器的兼容性。 |
| [getVectorizationOptions()](#getVectorizationOptions--) | 获取 PSD 矢量化选项。 |
| [setVectorizationOptions(PsdVectorizationOptions value)](#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-) | 设置 PSD 矢量化选项。 |

## Example: This example demonstrates the use of Aspose.
此示例演示了使用 Aspose.Imaging for Java API 将图像转换为 PSD 格式。为实现此目标，示例加载现有图像，然后将其保存回 PSD 格式。
``` java

// 创建 image 类的实例，并通过文件路径使用现有文件进行初始化
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // 创建 PsdOptions 类的实例
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // 将 CompressionMethod 设置为 RLE
    // 注意：其他支持的 CompressionMethod 为 CompressionMethod.RAW【无压缩】
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // 将 ColorMode 设置为 GrayScale
    // 注意：其他支持的 ColorModes 为 ColorModes.Bitmap 和 ColorModes.RGB
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // 使用提供的 PsdOptions 设置将图像保存到磁盘
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to PSD format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.psd";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PsdOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // 仅导出前两页。这些页面将在输出的 PSD 中作为图层呈现。
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
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

### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


初始化 `PsdOptions` 类的新实例。

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.imaging.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


初始化 `PsdOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.imaging.imageoptions/psdoptions) | 选项。 |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


获取或设置 XMP 数据容器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


获取或设置 PSD 文件版本。

值：PSD 文件版本。

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


获取或设置 PSD 文件版本。

值：PSD 文件版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // 定义线性蓝色透明渐变。
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // 使用线性蓝色透明渐变填充 PNG 图像。
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // 以下选项将用于将 PNG 图像保存为 PSD 格式。
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // 每个通道的位数
    saveOptions.setChannelBitsCount((byte) 8);

    // 通道数量。每个颜色分量 R、G、B、A 各占一个通道
    saveOptions.setChannelsCount((short) 4);

    // 颜色模式
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // 无压缩
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // 默认版本为 6
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // RLE 压缩可以减小输出图像的大小
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // 输出可能如下所示：
    // 使用 RAW 压缩的 PSD 图像大小：40090
    // 使用 RLE 压缩的 PSD 图像大小：16185
} finally {
    pngImage.dispose();
}
```

### getCompressionMethod() {#getCompressionMethod--}
```
public short getCompressionMethod()
```


获取或设置 PSD 压缩方法。

值：压缩方法。

**Returns:**
短
### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public void setCompressionMethod(short value)
```


获取或设置 PSD 压缩方法。

值：压缩方法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |


**Example: This example demonstrates the use of Aspose.**
此示例演示了使用 Aspose.Imaging for Java API 将图像转换为 PSD 格式。为实现此目标，示例加载现有图像，然后将其保存回 PSD 格式。
``` java

// 创建 image 类的实例，并通过文件路径使用现有文件进行初始化
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // 创建 PsdOptions 类的实例
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // 将 CompressionMethod 设置为 RLE
    // 注意：其他支持的 CompressionMethod 为 CompressionMethod.RAW【无压缩】
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // 将 ColorMode 设置为 GrayScale
    // 注意：其他支持的 ColorModes 为 ColorModes.Bitmap 和 ColorModes.RGB
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // 使用提供的 PsdOptions 设置将图像保存到磁盘
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


获取文件格式版本。它可以是 PSD 或 PSB。

值：文件格式版本。

**Returns:**
byte - 文件格式版本。
### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


设置文件格式版本。它可以是 PSD 或 PSB。

值：文件格式版本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte | 文件格式版本。 |

### getColorMode() {#getColorMode--}
```
public short getColorMode()
```


获取或设置 PSD 颜色模式。

值：颜色模式。

**Returns:**
短
### setColorMode(short value) {#setColorMode-short-}
```
public void setColorMode(short value)
```


获取或设置 PSD 颜色模式。

值：颜色模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |


**Example: This example demonstrates the use of Aspose.**
此示例演示了使用 Aspose.Imaging for Java API 将图像转换为 PSD 格式。为实现此目标，示例加载现有图像，然后将其保存回 PSD 格式。
``` java

// 创建 image 类的实例，并通过文件路径使用现有文件进行初始化
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // 创建 PsdOptions 类的实例
    com.aspose.imaging.imageoptions.PsdOptions psdOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // 将 CompressionMethod 设置为 RLE
    // 注意：其他支持的 CompressionMethod 为 CompressionMethod.RAW【无压缩】
    psdOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

    // 将 ColorMode 设置为 GrayScale
    // 注意：其他支持的 ColorModes 为 ColorModes.Bitmap 和 ColorModes.RGB
    psdOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Grayscale);

    // 使用提供的 PsdOptions 设置将图像保存到磁盘
    image.save("C:\\temp\\output.psd", psdOptions);
} finally {
    image.dispose();
}
```

### getChannelBitsCount() {#getChannelBitsCount--}
```
public short getChannelBitsCount()
```


获取或设置每个颜色通道的位数。

值：每个颜色通道的位数。

**Returns:**
短
### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public void setChannelBitsCount(short value)
```


获取或设置每个颜色通道的位数。

值：每个颜色通道的位数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 |  |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // 定义线性蓝色透明渐变。
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // 使用线性蓝色透明渐变填充 PNG 图像。
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // 以下选项将用于将 PNG 图像保存为 PSD 格式。
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // 每个通道的位数
    saveOptions.setChannelBitsCount((byte) 8);

    // 通道数量。每个颜色分量 R、G、B、A 各占一个通道
    saveOptions.setChannelsCount((short) 4);

    // 颜色模式
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // 无压缩
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // 默认版本为 6
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // RLE 压缩可以减小输出图像的大小
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // 输出可能如下所示：
    // 使用 RAW 压缩的 PSD 图像大小：40090
    // 使用 RLE 压缩的 PSD 图像大小：16185
} finally {
    pngImage.dispose();
}
```

### getChannelsCount() {#getChannelsCount--}
```
public short getChannelsCount()
```


获取颜色通道的数量。

**Returns:**
short - 颜色通道数量。
### setChannelsCount(short value) {#setChannelsCount-short-}
```
public void setChannelsCount(short value)
```


设置颜色通道的数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 | 颜色通道数量。 |


**Example: This example shows how to save a PNG image to PSD format using various PSD-specific options.**

``` java
String dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100, com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
try {
    // 定义线性蓝色透明渐变。
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // 使用线性蓝色透明渐变填充 PNG 图像。
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // 以下选项将用于将 PNG 图像保存为 PSD 格式。
    com.aspose.imaging.imageoptions.PsdOptions saveOptions = new com.aspose.imaging.imageoptions.PsdOptions();

    // 每个通道的位数
    saveOptions.setChannelBitsCount((byte) 8);

    // 通道数量。每个颜色分量 R、G、B、A 各占一个通道
    saveOptions.setChannelsCount((short) 4);

    // 颜色模式
    saveOptions.setColorMode(com.aspose.imaging.fileformats.psd.ColorModes.Rgb);

    // 无压缩
    saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.Raw);

    // 默认版本为 6
    saveOptions.setVersion(6);

    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "saveoptions.psd");
    try {
        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RAW compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    stream = new java.io.FileOutputStream(dir + "saveoptions.RLE.psd");
    try {
        // RLE 压缩可以减小输出图像的大小
        saveOptions.setCompressionMethod(com.aspose.imaging.fileformats.psd.CompressionMethod.RLE);

        pngImage.save(stream, saveOptions);
        System.out.println("The size of the PSD image with RLE compression: " + stream.getChannel().size());
    } finally {
        stream.close();
    }

    // 输出可能如下所示：
    // 使用 RAW 压缩的 PSD 图像大小：40090
    // 使用 RLE 压缩的 PSD 图像大小：16185
} finally {
    pngImage.dispose();
}
```

### isRemoveGlobalTextEngineResource() {#isRemoveGlobalTextEngineResource--}
```
public boolean isRemoveGlobalTextEngineResource()
```


获取一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本层的 PSD 文件，仅在处理后无法在 Adobe Photoshop 中打开的情况下（主要与缺失字体的文本层相关）。使用此选项后，用户需要在 Photoshop 打开的文件中执行以下操作：菜单 "Text" -> "Process absent fonts"。完成该操作后，所有文本将再次出现。请注意，此操作可能导致最终布局的某些更改。

**Returns:**
boolean - 如果 [remove global text engine resource] 为 `true`；否则为 `false`。
### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public void setRemoveGlobalTextEngineResource(boolean value)
```


设置一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本层的 PSD 文件，仅在处理后无法在 Adobe Photoshop 中打开的情况下（主要与缺失字体的文本层相关）。使用此选项后，用户需要在 Photoshop 打开的文件中执行以下操作：菜单 "Text" -> "Process absent fonts"。完成该操作后，所有文本将再次出现。请注意，此操作可能导致最终布局的某些更改。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | `true` 如果 [remove global text engine resource]；否则为 `false`。 |

### isRefreshImagePreviewData() {#isRefreshImagePreviewData--}
```
public boolean isRefreshImagePreviewData()
```


获取一个值，指示是否 [刷新图像预览数据] - 该选项用于最大化与其他 PSD 图像查看器的兼容性。

**Returns:**
boolean - `true` 如果 [refresh image preview data]；否则为 `false`。
### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public void setRefreshImagePreviewData(boolean value)
```


设置一个值，指示是否 [刷新图像预览数据] - 该选项用于最大化与其他 PSD 图像查看器的兼容性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | `true` 如果 [refresh image preview data]；否则为 `false`。 |

### getVectorizationOptions() {#getVectorizationOptions--}
```
public final PsdVectorizationOptions getVectorizationOptions()
```


获取 PSD 矢量化选项。

**Returns:**
[PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) - the PSD vectorization options.
### setVectorizationOptions(PsdVectorizationOptions value) {#setVectorizationOptions-com.aspose.imaging.imageoptions.PsdVectorizationOptions-}
```
public final void setVectorizationOptions(PsdVectorizationOptions value)
```


设置 PSD 矢量化选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PsdVectorizationOptions](../../com.aspose.imaging.imageoptions/psdvectorizationoptions) | PSD 矢量化选项。 |

