---
title: "GifOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "用于创建图形交换格式 GIF 栅格图像文件的 API 为开发者提供了生成 GIF 图像的精确控制的全面选项。"
type: docs
weight: 22
url: /zh/java/com.aspose.imaging.imageoptions/gifoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

用于创建图形交换格式 (GIF) 栅格图像文件的 API 为开发者提供了生成 GIF 图像的精确控制的全面选项。该 API 具备设置背景颜色、颜色调色板、分辨率、交错类型、透明颜色、XMP 元数据容器以及图像压缩等功能，确保在创建针对特定应用需求的优化且视觉上吸引人的 GIF 时具备灵活性和高效性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GifOptions()](#GifOptions--) | 初始化 `GifOptions` 类的新实例。 |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.imaging.imageoptions.GifOptions-) | 初始化 `GifOptions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | 获取或设置指示是否应用调色板校正的值。 |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | 获取或设置指示是否应用调色板校正的值。 |
| [getLoopsCount()](#getLoopsCount--) | 获取循环计数（默认 1 次循环） |
| [setLoopsCount(int value)](#setLoopsCount-int-) | 设置循环计数（默认 1 次循环） |
| [getColorResolution()](#getColorResolution--) | 获取或设置 GIF 颜色分辨率。 |
| [setColorResolution(byte value)](#setColorResolution-byte-) | 获取或设置 GIF 颜色分辨率。 |
| [isPaletteSorted()](#isPaletteSorted--) | 获取或设置一个值，指示调色板条目是否已排序。 |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | 获取或设置一个值，指示调色板条目是否已排序。 |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | 获取或设置 GIF 像素宽高比。 |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | 获取或设置 GIF 像素宽高比。 |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | 获取或设置 GIF 背景颜色索引。 |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | 获取或设置 GIF 背景颜色索引。 |
| [hasTrailer()](#hasTrailer--) | 获取或设置一个值，指示 GIF 是否具有尾部。 |
| [setTrailer(boolean value)](#setTrailer-boolean-) | 获取或设置一个值，指示 GIF 是否具有尾部。 |
| [getInterlaced()](#getInterlaced--) | 如果图像应交错，则为 true。 |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | 如果图像应交错，则为 true。 |
| [getMaxDiff()](#getMaxDiff--) | 获取或设置允许的最大像素差异。 |
| [setMaxDiff(int value)](#setMaxDiff-int-) | 获取或设置允许的最大像素差异。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取背景颜色。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | 设置背景颜色。 |
| [hasTransparentColor()](#hasTransparentColor--) | 获取一个值，指示 GIF 图像是否具有透明颜色。 |
| [setTransparentColor(Boolean value)](#setTransparentColor-java.lang.Boolean-) | 设置一个值，指示 GIF 图像是否具有透明颜色。 |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
此示例演示了在导出场景中使用 SaveOptions 命名空间中的不同类。将类型为 Gif 的图像加载到 Image 实例中，然后导出为多种格式。
``` java
String dir = "c:\\temp\\";

//在 Image 类的实例中加载已有的图像（类型为 Gif）
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


## Example: The following example shows how to convert a multipage vector image to GIF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.gif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.GifOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // 仅导出前两页。这些页面将在输出 GIF 中作为动画帧呈现。
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

### GifOptions() {#GifOptions--}
```
public GifOptions()
```


初始化 `GifOptions` 类的新实例。

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.imaging.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


初始化 `GifOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.imaging.imageoptions/gifoptions) | GIF 选项。 |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


获取或设置指示是否应用调色板校正的值。

**Returns:**
布尔 - `true` 表示已应用调色板校正；否则为 `false`。

调色板校正的含义是，每当图像导出为 GIF 时，源图像的颜色将被分析，以构建最匹配的调色板（如果图像的 Palette 不存在或未在选项中指定）。分析过程需要一些时间，但输出图像将拥有最佳匹配的颜色调色板，视觉效果更佳。
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


获取或设置指示是否应用调色板校正的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | `true` 表示已应用调色板校正；否则为 `false`。 |

调色板校正的含义是，每当图像导出为 GIF 时，源图像的颜色将被分析，以构建最匹配的调色板（如果图像的 Palette 不存在或未在选项中指定）。分析过程需要一些时间，但输出图像将拥有最佳匹配的颜色调色板，视觉效果更佳。 |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // 用蓝黄渐变填充整个图像。
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // 存储一种颜色所需的位数减 1。
    saveOptions.setColorResolution((byte) 7);

    // 调色板校正的含义是，每当图像导出为 GIF 时，源图像的颜色将被分析
    // 以构建最匹配的调色板（如果图像的 Palette 不存在或未在选项中指定）
    saveOptions.setDoPaletteCorrection(true);

    // 以渐进方式加载 GIF 图像。
    // 交错的 GIF 不会从上到下线性显示其扫描线，而是重新排序它们
    // 因此，即使在加载完成之前，GIF 的内容也会变得清晰。
    saveOptions.setInterlaced(true);

    // 另存为无损 GIF。
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // 设置允许的最大像素差异。如果大于零，将使用有损压缩。
    // 推荐的最佳有损压缩值为 80。30 表示非常轻的压缩，200 表示较重的压缩。
    saveOptions.setMaxDiff(80);

    // 另存为有损 GIF。
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//输出可能如下所示：
//无损 GIF 的大小：212816 字节。
//有损 GIF 的大小：89726 字节。
```

### getLoopsCount() {#getLoopsCount--}
```
public final int getLoopsCount()
```


获取循环计数（默认 1 次循环）

值：循环计数。

**Returns:**
int - 循环计数（默认 1 次循环）
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public final void setLoopsCount(int value)
```


设置循环计数（默认 1 次循环）

值：循环计数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 循环计数（默认 1 次循环） |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


获取或设置 GIF 颜色分辨率。

**Returns:**
byte - 颜色分辨率。

Color Resolution - 原始图像每个原色可用的位数减 1。该值表示用于选择图形颜色的整个调色板的大小，而不是实际在图形中使用的颜色数量。例如，如果此字段的值为 3，则原始图像的调色板每个原色有 4 位可用于创建图像。即使源机器并未提供整个调色板的所有颜色，也应设置此值以指示原始调色板的丰富程度。
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


获取或设置 GIF 颜色分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | byte | 颜色分辨率。 |

Color Resolution - 原始图像每个原色可用的位数减 1。该值表示用于选择图形颜色的整个调色板的大小，而不是实际在图形中使用的颜色数量。例如，如果此字段的值为 3，则原始图像的调色板每个原色有 4 位可用于创建图像。即使源机器并未提供整个调色板的所有颜色，也应设置此值以指示原始调色板的丰富程度。 |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // 用蓝黄渐变填充整个图像。
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // 存储一种颜色所需的位数减 1。
    saveOptions.setColorResolution((byte) 7);

    // 调色板校正的含义是，每当图像导出为 GIF 时，源图像的颜色将被分析
    // 以构建最匹配的调色板（如果图像的 Palette 不存在或未在选项中指定）
    saveOptions.setDoPaletteCorrection(true);

    // 以渐进方式加载 GIF 图像。
    // 交错的 GIF 不会从上到下线性显示其扫描线，而是重新排序它们
    // 因此，即使在加载完成之前，GIF 的内容也会变得清晰。
    saveOptions.setInterlaced(true);

    // 另存为无损 GIF。
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // 设置允许的最大像素差异。如果大于零，将使用有损压缩。
    // 推荐的最佳有损压缩值为 80。30 表示非常轻的压缩，200 表示较重的压缩。
    saveOptions.setMaxDiff(80);

    // 另存为有损 GIF。
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//输出可能如下所示：
//无损 GIF 的大小：212816 字节。
//有损 GIF 的大小：89726 字节。
```

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


获取或设置一个值，指示调色板条目是否已排序。

**Returns:**
boolean - 如果调色板条目已排序则为 `true`；否则为 `false`。
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


获取或设置一个值，指示调色板条目是否已排序。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | `true` 表示调色板条目已排序；否则为 `false`。 |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


获取或设置 GIF 像素宽高比。

Pixel Aspect Ratio - 用于计算原始图像像素宽高比近似值的因素。如果该字段的值不为 0，则根据公式计算该宽高比近似值：Aspect Ratio = (Pixel Aspect Ratio + 15) / 64。Pixel Aspect Ratio 定义为像素宽度除以高度的商。此字段的取值范围允许以 1/64 为增量指定最宽像素为 4:1 到最窄像素为 1:4。取值：0 - 未提供宽高比信息。1..255 - 用于计算的值。

**Returns:**
byte - GIF 像素宽高比。
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


获取或设置 GIF 像素宽高比。

Pixel Aspect Ratio - 用于计算原始图像像素宽高比近似值的因素。如果该字段的值不为 0，则根据公式计算该宽高比近似值：Aspect Ratio = (Pixel Aspect Ratio + 15) / 64。Pixel Aspect Ratio 定义为像素宽度除以高度的商。此字段的取值范围允许以 1/64 为增量指定最宽像素为 4:1 到最窄像素为 1:4。取值：0 - 未提供宽高比信息。1..255 - 用于计算的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte | GIF 像素宽高比。 |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


获取或设置 GIF 背景颜色索引。

**Returns:**
byte - GIF 背景颜色索引。
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


获取或设置 GIF 背景颜色索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte | GIF 背景颜色索引。 |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


获取或设置一个值，指示 GIF 是否具有尾部。

**Returns:**
boolean - 如果 GIF 有尾部则为 `true`；否则为 `false`。
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


获取或设置一个值，指示 GIF 是否具有尾部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | `true` 表示 GIF 有尾部；否则为 `false`。 |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


如果图像应交错，则为 true。

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


如果图像应交错，则为 true。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // 用蓝黄渐变填充整个图像。
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // 存储一种颜色所需的位数减 1。
    saveOptions.setColorResolution((byte) 7);

    // 调色板校正的含义是，每当图像导出为 GIF 时，源图像的颜色将被分析
    // 以构建最匹配的调色板（如果图像的 Palette 不存在或未在选项中指定）
    saveOptions.setDoPaletteCorrection(true);

    // 以渐进方式加载 GIF 图像。
    // 交错的 GIF 不会从上到下线性显示其扫描线，而是重新排序它们
    // 因此，即使在加载完成之前，GIF 的内容也会变得清晰。
    saveOptions.setInterlaced(true);

    // 另存为无损 GIF。
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // 设置允许的最大像素差异。如果大于零，将使用有损压缩。
    // 推荐的最佳有损压缩值为 80。30 表示非常轻的压缩，200 表示较重的压缩。
    saveOptions.setMaxDiff(80);

    // 另存为有损 GIF。
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//输出可能如下所示：
//无损 GIF 的大小：212816 字节。
//有损 GIF 的大小：89726 字节。
```

### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


获取或设置允许的最大像素差异。如果大于零，将使用有损压缩。推荐的最佳有损压缩值为 80。30 表示非常轻的压缩，200 表示较重的压缩。该设置在仅引入少量损失时效果最佳，由于压缩算法的限制，极高的损失水平并不会带来太多收益。允许的取值范围为 [0, 1000]。

**Returns:**
int - 允许值的范围。
### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


获取或设置允许的最大像素差异。如果大于零，将使用有损压缩。推荐的最佳有损压缩值为 80。30 表示非常轻的压缩，200 表示较重的压缩。该设置在仅引入少量损失时效果最佳，由于压缩算法的限制，极高的损失水平并不会带来太多收益。允许的取值范围为 [0, 1000]。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 允许值的范围。 |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // 用蓝黄渐变填充整个图像。
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // 存储一种颜色所需的位数减 1。
    saveOptions.setColorResolution((byte) 7);

    // 调色板校正的含义是，每当图像导出为 GIF 时，源图像的颜色将被分析
    // 以构建最匹配的调色板（如果图像的 Palette 不存在或未在选项中指定）
    saveOptions.setDoPaletteCorrection(true);

    // 以渐进方式加载 GIF 图像。
    // 交错的 GIF 不会从上到下线性显示其扫描线，而是重新排序它们
    // 因此，即使在加载完成之前，GIF 的内容也会变得清晰。
    saveOptions.setInterlaced(true);

    // 另存为无损 GIF。
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // 设置允许的最大像素差异。如果大于零，将使用有损压缩。
    // 推荐的最佳有损压缩值为 80。30 表示非常轻的压缩，200 表示较重的压缩。
    saveOptions.setMaxDiff(80);

    // 另存为有损 GIF。
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//输出可能如下所示：
//无损 GIF 的大小：212816 字节。
//有损 GIF 的大小：89726 字节。
```

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


获取背景颜色。

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public final void setBackgroundColor(Color value)
```


设置背景颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | 背景颜色。 |

### hasTransparentColor() {#hasTransparentColor--}
```
public final Boolean hasTransparentColor()
```


获取一个值，指示 GIF 图像是否具有透明颜色。如果返回值为 `null`，则此属性被源图像上下文覆盖。

**Returns:**
java.lang.Boolean - 指示 GIF 图像是否具有透明颜色的值。
### setTransparentColor(Boolean value) {#setTransparentColor-java.lang.Boolean-}
```
public final void setTransparentColor(Boolean value)
```


设置一个值，用于指示 GIF 图像是否具有透明颜色。如果返回值为 `null`，此属性将被源图像上下文覆盖。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.Boolean | 一个指示 GIF 图像是否具有透明颜色的值。 |

