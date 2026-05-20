---
title: "JpegOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "使用我们的 API 轻松创建高质量 JPEG 图像，提供可调节的压缩级别，以在不影响图像质量的情况下优化存储大小。"
type: docs
weight: 26
url: /zh/java/com.aspose.imaging.imageoptions/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public class JpegOptions extends ImageOptionsBase implements IHasJpegExifData
```

使用我们的 API 轻松创建高质量 JPEG 图像，提供可调节的压缩级别，以在不影响图像质量的情况下优化存储大小。受益于对多种压缩类型、近无损编码、RGB 和 CMYK 色彩配置文件以及 EXIF、JFIF 图像数据和 XMP 容器的支持，确保为您的图像创建需求提供多样且可定制的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | 初始化 `JpegOptions` 类的新实例。 |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-) | 初始化 `JpegOptions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | 获取默认的内存分配限制。 |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | 设置默认内存分配限制。 |
| [getJfif()](#getJfif--) | 获取 jfif。 |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | 设置 jfif。 |
| [getComment()](#getComment--) | 获取 jpeg 文件注释。 |
| [setComment(String value)](#setComment-java.lang.String-) | 设置 jpeg 文件注释。 |
| [getExifData()](#getExifData--) | 获取 Exif 数据容器。 |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | 设置 Exif 数据。 |
| [getJpegExifData()](#getJpegExifData--) | 获取 Exif 数据容器。 |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | 获取或设置 exif 数据容器 |
| [getCompressionType()](#getCompressionType--) | 获取压缩类型。 |
| [setCompressionType(int value)](#setCompressionType-int-) | 设置压缩类型。 |
| [getColorType()](#getColorType--) | 获取 jpeg 图像的颜色类型。 |
| [setColorType(int value)](#setColorType-int-) | 设置 jpeg 图像的颜色类型。 |
| [getBitsPerChannel()](#getBitsPerChannel--) | 获取无损 jpeg 图像每通道位数。 |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | 设置无损 jpeg 图像每通道位数。 |
| [getQuality()](#getQuality--) | 获取图像质量。 |
| [setQuality(int value)](#setQuality-int-) | 设置图像质量。 |
| [getScaledQuality()](#getScaledQuality--) | 缩放后的质量。 |
| [getRdOptSettings()](#getRdOptSettings--) | 获取 RD 优化器设置。 |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-) | 设置 RD 优化器设置。 |
| [getRgbColorProfile()](#getRgbColorProfile--) | CMYK jpeg 图像的目标 RGB 色彩配置文件。 |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | CMYK jpeg 图像的目标 RGB 色彩配置文件。 |
| [getCmykColorProfile()](#getCmykColorProfile--) | CMYK jpeg 图像的目标 CMYK 色彩配置文件。 |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | CMYK jpeg 图像的目标 CMYK 色彩配置文件。 |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | 获取 JPEG-LS 近无损编码的差值界限（JPEG-LS 规范中的 NEAR 参数）。 |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | 设置 JPEG-LS 近无损编码的差值界限（JPEG-LS 规范中的 NEAR 参数）。 |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | 获取 JPEG-LS 交错模式。 |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | 设置 JPEG-LS 交错模式。 |
| [getJpegLsPreset()](#getJpegLsPreset--) | 获取 JPEG-LS 预设参数。 |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-) | 设置 JPEG-LS 预设参数。 |
| [getHorizontalSampling()](#getHorizontalSampling--) | 获取每个组件的水平子采样。 |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | 设置每个组件的水平子采样。 |
| [getVerticalSampling()](#getVerticalSampling--) | 获取每个组件的垂直子采样。 |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | 设置每个组件的垂直子采样。 |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | 获取将 8 位值适配为 n 位值的样本四舍五入模式。 |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | 设置将 8 位值适配为 n 位值的样本四舍五入模式。 |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | 获取一个值，指示在存在 alpha 通道时是否应将红、绿、蓝组件与背景颜色混合。 |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | 设置一个值，指示在存在 alpha 通道时是否应将红、绿、蓝组件与背景颜色混合。 |
| [getResolutionUnit()](#getResolutionUnit--) | 获取分辨率单位。 |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | 设置分辨率单位。 |

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


## Example: The following example shows how to convert a multipage vector image to JPEG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.jpeg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.JpegOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // 仅导出前两页。实际上，由于 JPEG 不是多页格式，只会光栅化一页。
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

### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


初始化 `JpegOptions` 类的新实例。

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.imaging.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


初始化 `JpegOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | JPEG 选项。 |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


获取默认的内存分配限制。

**Returns:**
int - 默认内存分配限制。
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


设置默认内存分配限制。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 默认内存分配限制。 |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


获取 jfif。

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


设置 jfif。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getComment() {#getComment--}
```
public String getComment()
```


获取 jpeg 文件注释。

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


设置 jpeg 文件注释。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


获取 Exif 数据容器。

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data container.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public final void setExifData(ExifData value)
```


设置 Exif 数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif 数据。 |

### getJpegExifData() {#getJpegExifData--}
```
public final JpegExifData getJpegExifData()
```


获取 Exif 数据容器。

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data container.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


获取或设置 exif 数据容器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


获取压缩类型。

**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


设置压缩类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// 创建 100x100 像素的 JPEG 图像。
// 使用其他选项来指定所需的图像参数。
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// 各通道的位数分别为 Y、Cr、Cb 组件的 8、8、8 位。
createOptions.setBitsPerChannel((byte) 8);

// 设置渐进式压缩类型。
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// 设置图像质量。取值范围为 1 到 100。
createOptions.setQuality(100);

// 将水平/垂直分辨率设置为每英寸 96 点。
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// 这是 JPEG 图像的标准选项。
// 两个色度分量（Cb 和 Cr）可以进行带宽降低、子采样和压缩。
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // 用灰度渐变填充图像
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // 保存到文件。
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getColorType() {#getColorType--}
```
public int getColorType()
```


获取 jpeg 图像的颜色类型。

**Returns:**
int

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// 创建 100x100 像素的 JPEG 图像。
// 使用其他选项来指定所需的图像参数。
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// 各通道的位数分别为 Y、Cr、Cb 组件的 8、8、8 位。
createOptions.setBitsPerChannel((byte) 8);

// 设置渐进式压缩类型。
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// 设置图像质量。取值范围为 1 到 100。
createOptions.setQuality(100);

// 将水平/垂直分辨率设置为每英寸 96 点。
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// 这是 JPEG 图像的标准选项。
// 两个色度分量（Cb 和 Cr）可以进行带宽降低、子采样和压缩。
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // 用灰度渐变填充图像
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // 保存到文件。
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


设置 jpeg 图像的颜色类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// 从文件加载 BMP 图像。
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // 进行一些图像处理。

    // 使用其他选项来指定所需的图像参数。
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // 每个通道的位数为 8。
    // 使用调色板时，颜色索引存储在图像数据中，而不是颜色本身。
    saveOptions.setBitsPerChannel((byte) 8);

    // 设置渐进式压缩类型。
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // 设置图像质量。取值范围为 1 到 100。
    saveOptions.setQuality(100);

    // 将水平/垂直分辨率设置为每英寸 96 点。
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // 如果源图像为彩色，则会转换为灰度。
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // 使用调色板来减小输出大小。
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


获取无损 JPEG 图像的每通道位数。当前支持每通道 2 到 8 位。

**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


设置无损 JPEG 图像的每通道位数。当前支持每通道 2 到 8 位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// 创建 100x100 像素的 JPEG 图像。
// 使用其他选项来指定所需的图像参数。
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// 各通道的位数分别为 Y、Cr、Cb 组件的 8、8、8 位。
createOptions.setBitsPerChannel((byte) 8);

// 设置渐进式压缩类型。
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// 设置图像质量。取值范围为 1 到 100。
createOptions.setQuality(100);

// 将水平/垂直分辨率设置为每英寸 96 点。
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// 这是 JPEG 图像的标准选项。
// 两个色度分量（Cb 和 Cr）可以进行带宽降低、子采样和压缩。
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // 用灰度渐变填充图像
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // 保存到文件。
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getQuality() {#getQuality--}
```
public int getQuality()
```


获取图像质量。

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


设置图像质量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |


**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// 创建 100x100 像素的 JPEG 图像。
// 使用其他选项来指定所需的图像参数。
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// 各通道的位数分别为 Y、Cr、Cb 组件的 8、8、8 位。
createOptions.setBitsPerChannel((byte) 8);

// 设置渐进式压缩类型。
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// 设置图像质量。取值范围为 1 到 100。
createOptions.setQuality(100);

// 将水平/垂直分辨率设置为每英寸 96 点。
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// 这是 JPEG 图像的标准选项。
// 两个色度分量（Cb 和 Cr）可以进行带宽降低、子采样和压缩。
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // 用灰度渐变填充图像
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // 保存到文件。
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


缩放后的质量。

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


获取 RD 优化器设置。

**Returns:**
[RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.imaging.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


设置 RD 优化器设置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.imaging.imageoptions/rdoptimizersettings) | RD 优化器设置。 |

### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


CMYK JPEG 图像的目标 RGB 颜色配置文件。用于保存图像。必须与 CMYKColorProfile 配对以实现正确的颜色转换。

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


CMYK JPEG 图像的目标 RGB 颜色配置文件。用于保存图像。必须与 CMYKColorProfile 配对以实现正确的颜色转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
以下示例加载 PNG 并使用自定义 ICC 配置文件将其保存为 CMYK JPEG。然后加载 CMYK JPEG 并将其保存回 PNG。RGB 到 CMYK 以及 CMYK 到 RGB 的颜色转换均使用自定义 ICC 配置文件执行。
``` java
String dir = "c:\\temp\\";

// 加载 PNG 并保存为 CMYK JPEG
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // 使用自定义 ICC 配置文件
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// 加载 CMYK JPEG 并保存为 PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // 使用自定义 ICC 配置文件
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


CMYK JPEG 图像的目标 CMYK 颜色配置文件。用于保存图像。必须与 RGBColorProfile 配对以实现正确的颜色转换。

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


CMYK JPEG 图像的目标 CMYK 颜色配置文件。用于保存图像。必须与 RGBColorProfile 配对以实现正确的颜色转换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
以下示例加载 PNG 并使用自定义 ICC 配置文件将其保存为 CMYK JPEG。然后加载 CMYK JPEG 并将其保存回 PNG。RGB 到 CMYK 以及 CMYK 到 RGB 的颜色转换均使用自定义 ICC 配置文件执行。
``` java
String dir = "c:\\temp\\";

// 加载 PNG 并保存为 CMYK JPEG
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // 使用自定义 ICC 配置文件
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// 加载 CMYK JPEG 并保存为 PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // 使用自定义 ICC 配置文件
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


获取 JPEG-LS 近无损编码的差值界限（JPEG-LS 规范中的 NEAR 参数）。

**Returns:**
int
### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


设置 JPEG-LS 近无损编码的差值界限（JPEG-LS 规范中的 NEAR 参数）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


获取 JPEG-LS 交错模式。

**Returns:**
int
### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


设置 JPEG-LS 交错模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


获取 JPEG-LS 预设参数。

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters)
### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


设置 JPEG-LS 预设参数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


获取每个组件的水平子采样。

**Returns:**
byte[]
### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


设置每个组件的水平子采样。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


获取每个组件的垂直子采样。

**Returns:**
byte[]
### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


设置每个组件的垂直子采样。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte[] |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


获取将 8 位值适配为 n 位值的示例四舍五入模式。 `P:JpegOptions.BitsPerChannel`

**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


设置将 8 位值适配为 n 位值的示例四舍五入模式。 `P:JpegOptions.BitsPerChannel`

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


获取一个值，指示在存在 alpha 通道时是否应将红、绿、蓝组件与背景颜色混合。

**Returns:**
boolean
### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


设置一个值，指示在存在 alpha 通道时是否应将红、绿、蓝组件与背景颜色混合。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


获取分辨率单位。

**Returns:**
byte - 分辨率单位。

**Example: The following example shows how to create JPEG image of the specified size with the specified parameters.**

``` java
String dir = "c:\\temp\\";

// 创建 100x100 像素的 JPEG 图像。
// 使用其他选项来指定所需的图像参数。
com.aspose.imaging.imageoptions.JpegOptions createOptions = new com.aspose.imaging.imageoptions.JpegOptions();

// 各通道的位数分别为 Y、Cr、Cb 组件的 8、8、8 位。
createOptions.setBitsPerChannel((byte) 8);

// 设置渐进式压缩类型。
createOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

// 设置图像质量。取值范围为 1 到 100。
createOptions.setQuality(100);

// 将水平/垂直分辨率设置为每英寸 96 点。
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
createOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

// 这是 JPEG 图像的标准选项。
// 两个色度分量（Cb 和 Cr）可以进行带宽降低、子采样和压缩。
createOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.YCbCr);

com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(jpegImage);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(jpegImage.getWidth(), jpegImage.getHeight()),
            com.aspose.imaging.Color.getYellow(),
            com.aspose.imaging.Color.getBlue());

    // 用灰度渐变填充图像
    graphics.fillRectangle(gradientBrush, jpegImage.getBounds());

    // 保存到文件。
    jpegImage.save(dir + "output.explicitoptions.jpg");
} finally {
    jpegImage.dispose();
}
```

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


设置分辨率单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte | 分辨率单位。 |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// 从文件加载 BMP 图像。
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // 进行一些图像处理。

    // 使用其他选项来指定所需的图像参数。
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // 每个通道的位数为 8。
    // 使用调色板时，颜色索引存储在图像数据中，而不是颜色本身。
    saveOptions.setBitsPerChannel((byte) 8);

    // 设置渐进式压缩类型。
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // 设置图像质量。取值范围为 1 到 100。
    saveOptions.setQuality(100);

    // 将水平/垂直分辨率设置为每英寸 96 点。
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // 如果源图像为彩色，则会转换为灰度。
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // 使用调色板来减小输出大小。
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

