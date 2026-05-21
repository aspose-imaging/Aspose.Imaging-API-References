---
title: "BmpOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "BMP 和 DIB 栅格图像格式创建选项的 API 为开发人员提供了一个多功能工具集，用于生成自定义的位图 BMP 和设备无关位图 DIB 图像。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.imageoptions/bmpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class BmpOptions extends ImageOptionsBase
```

BMP 和 DIB 栅格图像格式创建选项的 API 为开发人员提供了一个多功能工具集，用于生成自定义的位图 (BMP) 和设备无关位图 (DIB) 图像。使用此 API，您可以精确定义图像特性，例如每像素位数、压缩级别和压缩类型，以满足特定需求。功能丰富的 API 使开发人员能够轻松且灵活地创建高质量、定制化的栅格图像，以适用于各种应用。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BmpOptions()](#BmpOptions--) | 初始化 `BmpOptions` 类的新实例。 |
| [BmpOptions(BmpOptions bmpOptions)](#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-) | 初始化 `BmpOptions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | 获取或设置图像每像素位数。 |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | 获取或设置图像每像素位数。 |
| [getCompression()](#getCompression--) | 获取压缩类型。 |
| [setCompression(long value)](#setCompression-long-) | 设置压缩类型。 |

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


## Example: The following example shows how to convert a multipage vector image to BMP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.bmp");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.BmpOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // 仅导出前两页。实际上，由于 BMP 不是多页格式，只会光栅化一页。
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

### BmpOptions() {#BmpOptions--}
```
public BmpOptions()
```


初始化 `BmpOptions` 类的新实例。

### BmpOptions(BmpOptions bmpOptions) {#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-}
```
public BmpOptions(BmpOptions bmpOptions)
```


初始化 `BmpOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bmpOptions | [BmpOptions](../../com.aspose.imaging.imageoptions/bmpoptions) | BMP 选项。 |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


获取或设置图像每像素位数。

**Returns:**
int - 图像每像素位数。
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


获取或设置图像每像素位数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 图像每像素位数。 |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 创建 BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // 使用每像素 8 位以减小输出图像的大小。
    saveOptions.setBitsPerPixel(8);

    // 设置最接近的 8 位颜色调色板，以覆盖最大数量的图像像素，从而得到调色板图像
    // 几乎在视觉上与非调色板图像无法区分。
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // 不使用压缩保存。
    // 您也可以使用 RLE-8 压缩来减小输出图像的大小。
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // 将水平和垂直分辨率设置为 96 dpi。
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


获取压缩类型。默认的压缩类型是 [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields)，它允许保存具有透明度的 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage)。

值：压缩类型。

**Returns:**
long - 压缩类型。

**Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.**

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```

### setCompression(long value) {#setCompression-long-}
```
public void setCompression(long value)
```


设置压缩类型。默认的压缩类型是 [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields)，它允许保存带透明度的 [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage)。

值：压缩类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long | 压缩类型。 |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 创建 BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // 使用每像素 8 位以减小输出图像的大小。
    saveOptions.setBitsPerPixel(8);

    // 设置最接近的 8 位颜色调色板，以覆盖最大数量的图像像素，从而得到调色板图像
    // 几乎在视觉上与非调色板图像无法区分。
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // 不使用压缩保存。
    // 您也可以使用 RLE-8 压缩来减小输出图像的大小。
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // 将水平和垂直分辨率设置为 96 dpi。
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```


**Example: Compress BMP image using DXT1 compression algorithm.**

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


**Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.**

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// 从文件加载 PNG 图像。
try (Image pngImage = Image.load(sourcePath))
{
    // 默认情况下，BMP 图像以支持透明度的方式保存。
    // 如果您想显式指定此模式，应将 BmpOptions 的 Compression 属性设置为 BitmapCompression.Bitfields。
    // BitmapCompression.Bitfields 压缩方法是 BmpOptions 中的默认压缩方法。
    // 因此，通过以下任一方式都可以实现导出带透明度的 Bmp 图像的相同结果。
    // 使用隐式默认选项：
    pngImage.save(outputPathPng);
    // 使用显式默认选项：
    pngImage.save(outputPathBmp, new BmpOptions());
    // 指定 BitmapCompression.Bitfields 压缩方法：
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


**Example: The example shows how to export a BmpImage with the Rgb compression type.**

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// 从文件加载 PNG 图像。
try (Image pngImage = Image.load(sourcePath))
{
    // 默认情况下，BMP 图像以支持透明度的方式保存，这是通过使用 BitmapCompression.Bitfields 压缩方法实现的。
    // 要使用 Rgb 压缩方法保存 BMP 图像，应指定 Compression 属性设置为 BitmapCompression.Rgb 的 BmpOptions。
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```

