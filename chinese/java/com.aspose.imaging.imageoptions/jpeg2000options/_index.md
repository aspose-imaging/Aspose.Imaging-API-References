---
title: "Jpeg2000Options"
second_title: "Aspose.Imaging for Java API 参考"
description: "使用我们的 API 创建 JPEG2000 JP2 图像文件，利用先进的小波技术对无损内容进行编码。"
type: docs
weight: 25
url: /zh/java/com.aspose.imaging.imageoptions/jpeg2000options/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

使用我们的 API 创建 JPEG2000 (JP2) 图像文件，利用先进的小波技术对无损内容进行编码。受益于对多种编解码器的支持，包括有损和无损压缩，以及 XMP 元数据容器，确保多功能性和高质量的图像创建，以满足您的需求。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | 初始化 `Jpeg2000Options` 类的新实例。 |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-) | 初始化 `Jpeg2000Options` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getComments()](#getComments--) | 获取或设置 Jpeg 注释标记。 |
| [setComments(String[] value)](#setComments-java.lang.String---) | 获取或设置 Jpeg 注释标记。 |
| [getCodec()](#getCodec--) | 获取或设置 JPEG2000 编解码器 |
| [setCodec(int value)](#setCodec-int-) | 获取或设置 JPEG2000 编解码器 |
| [getCompressionRatios()](#getCompressionRatios--) | 获取或设置压缩比数组。 |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | 获取或设置压缩比数组。 |
| [getIrreversible()](#getIrreversible--) | 获取一个值，指示是使用不可逆 DWT 9-7（true）还是使用无损 DWT 5-3 压缩（默认）。 |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | 设置一个值，指示是使用不可逆 DWT 9-7（true）还是使用无损 DWT 5-3 压缩（默认）。 |

## Example: The following example shows how to convert a multipage vector image to JPEG 2000 format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.j2k");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // 仅导出前两页。实际上，由于 JPEG 2000 不是多页格式，只会光栅化一页。
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

### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


初始化 `Jpeg2000Options` 类的新实例。

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


初始化 `Jpeg2000Options` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | 要从中复制设置的 Jpeg2000 文件格式选项。 |

### getComments() {#getComments--}
```
public String[] getComments()
```


获取或设置 Jpeg 注释标记。

**Returns:**
java.lang.String[] - Jpeg 注释标记。
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


获取或设置 Jpeg 注释标记。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String[] | Jpeg 注释标记。 |

### getCodec() {#getCodec--}
```
public int getCodec()
```


获取或设置 JPEG2000 编解码器

**Returns:**
int - JPEG2000 编解码器
### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


获取或设置 JPEG2000 编解码器

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | JPEG2000 编解码器 |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // 将整个图像填充为红色。
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // 使用不可逆离散小波变换 9-7
    saveOptions.setIrreversible(true);

    // JP2 是 JPEG 2000 码流的 “容器” 格式。
    // J2K 是原始压缩数据，没有封装。
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // 保存到文件
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


获取或设置压缩比数组。连续层的压缩比不同。为每个质量级别指定的比率是期望的压缩因子。需要降低比率。

**Returns:**
int[] - 压缩比。
### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


获取或设置压缩比数组。连续层的压缩比不同。为每个质量级别指定的比率是期望的压缩因子。需要降低比率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int[] | 压缩比。 |

### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


获取一个值，指示是使用不可逆 DWT 9-7（true）还是使用无损 DWT 5-3 压缩（默认）。

**Returns:**
boolean - 一个值，指示是使用不可逆 DWT 9-7（true）还是使用无损 DWT 5-3 压缩
### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


设置一个值，指示是使用不可逆 DWT 9-7（true）还是使用无损 DWT 5-3 压缩（默认）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 一个值，指示是使用不可逆 DWT 9-7（true）还是使用无损 DWT 5-3 压缩 |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// 创建一个 100x100 像素的 PNG 图像。
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // 将整个图像填充为红色。
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // 使用不可逆离散小波变换 9-7
    saveOptions.setIrreversible(true);

    // JP2 是 JPEG 2000 码流的 “容器” 格式。
    // J2K 是原始压缩数据，没有封装。
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // 保存到文件
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

