---
title: "DicomOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "用于医学数字成像与通信（DICOM）光栅图像格式创建的 API 是为医疗设备应用量身定制的专用工具。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.imageoptions/dicomoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class DicomOptions extends ImageOptionsBase
```

用于医学数字成像与通信 (DICOM) 光栅图像格式创建的 API 是为医疗设备应用量身定制的专用工具。它实现了 DICOM 图像的无缝生成，这对于存储医学数据并包含重要的识别信息至关重要。通过设置压缩、定义颜色类型以及嵌入 XMP 元数据等功能，开发者可以确保在医学成像场景中对 DICOM 图像的合规性和灵活性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DicomOptions()](#DicomOptions--) | 初始化 [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) 类的新实例。 |
| [DicomOptions(DicomOptions options)](#DicomOptions-com.aspose.imaging.imageoptions.DicomOptions-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompression()](#getCompression--) | 获取压缩。 |
| [setCompression(Compression value)](#setCompression-com.aspose.imaging.fileformats.dicom.Compression-) | 设置压缩。 |
| [getColorType()](#getColorType--) | 获取颜色的类型。 |
| [setColorType(int value)](#setColorType-int-) | 设置颜色的类型。 |

## Example: The following example shows export to DICOM file format (single and multipage).

``` java
String fileName = "sample.jpg";
String inputFileNameSingle = fileName;
String inputFileNameMultipage = "multipage.tif";
String outputFileNameSingleDcm = "output.dcm";
String outputFileNameMultipageDcm = "outputMultipage.dcm";

// 下面的代码示例将 JPEG 图像转换为 DICOM 文件格式。
try(com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileNameSingle))
{
    image.save(outputFileNameSingleDcm, new com.aspose.imaging.imageoptions.DicomOptions());
}

// DICOM 格式支持多页图像。您可以像转换 JPEG 图像一样，将 GIF 或 TIFF 图像转换为 DICOM。
try(com.aspose.imaging.Image imageMultiple = com.aspose.imaging.Image.load(inputFileNameMultipage))
{
    imageMultiple.save(outputFileNameMultipageDcm, new com.aspose.imaging.imageoptions.DicomOptions());
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // 使用矢量图形绘制内容。
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // 保存绘制图像的像素。它们现在位于 Dicom 图像的第一页。
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // 在后面添加几页，使其更暗。
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // 在主页前面添加几页，使其更亮。
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // 将创建的多页图像保存到输出文件。
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomOptions() {#DicomOptions--}
```
public DicomOptions()
```


初始化 [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) 类的新实例。

### DicomOptions(DicomOptions options) {#DicomOptions-com.aspose.imaging.imageoptions.DicomOptions-}
```
public DicomOptions(DicomOptions options)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) |  |

### getCompression() {#getCompression--}
```
public final Compression getCompression()
```


获取压缩。

值：压缩。

**Returns:**
[Compression](../../com.aspose.imaging.fileformats.dicom/compression) - the compression.
### setCompression(Compression value) {#setCompression-com.aspose.imaging.fileformats.dicom.Compression-}
```
public final void setCompression(Compression value)
```


设置压缩。

值：压缩。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Compression](../../com.aspose.imaging.fileformats.dicom/compression) | 压缩。 |

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
| 值 | int | 颜色的类型。 |


**Example: Use JPEG compression in DICOM image.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


**Example: Use JPEG 2000 compression in DICOM image.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


**Example: Use RLE compression in DICOM image.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


**Example: Change Color Type in DICOM compression.**

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

