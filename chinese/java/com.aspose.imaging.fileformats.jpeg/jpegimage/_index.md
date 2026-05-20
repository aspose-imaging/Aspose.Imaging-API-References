---
title: "JpegImage"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "使用我们的 API 高效操作 JPEG 栅格图像，支持多种颜色配置文件，如 RGB 和 CMYK，可自定义每像素位数分辨率，并处理 EXIF、JFIF 和 XMP 元数据容器。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.fileformats.jpeg/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public final class JpegImage extends RasterCachedImage implements IHasJpegExifData
```

使用我们的 API 高效操作 JPEG 栅格图像，提供对多种颜色配置文件（如 RGB 和 CMYK）的支持，可自定义每像素位数分辨率，并处理 EXIF、JFIF 和 XMP 元数据容器。享受基于方向数据的自动旋转，并可在包括无损 JPEG 在内的不同压缩级别中进行选择，以实现项目的最佳图像质量和文件大小平衡。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [JpegImage(String path)](#JpegImage-java.lang.String-) | 通过使用指定的路径参数调用构造函数，[JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) 类可以轻松初始化。 |
| [JpegImage(InputStream stream)](#JpegImage-java.io.InputStream-) | 使用流参数，通过 [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) 类初始化 JPEG 图像对象。 |
| [JpegImage(RasterImage rasterImage)](#JpegImage-com.aspose.imaging.RasterImage-) | 使用栅格图像参数初始化 [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) 类的新实例。 |
| [JpegImage(int width, int height)](#JpegImage-int-int-) | 使用指定的宽度和高度参数创建 [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) 类的新实例。 |
| [JpegImage(JpegOptions jpegOptions, int width, int height)](#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-) | 使用提供的 JPEG 选项初始化新的 [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 使用此属性即可轻松检索图像的格式。 |
| [getJpegOptions()](#getJpegOptions--) | 轻松获取在创建或加载此 [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) 实例时使用的 JPEG 选项。 |
| [getBitsPerPixel()](#getBitsPerPixel--) | 使用此属性即可轻松检索图像的像素深度，提供对颜色或灰度表示丰富程度的洞察。 |
| [getComment()](#getComment--) | 使用此属性管理 JPEG 文件注释，允许您添加或检索与图像关联的描述性标注。 |
| [setComment(String value)](#setComment-java.lang.String-) | 使用此属性管理 JPEG 文件注释，允许您添加或检索与图像关联的描述性标注。 |
| [getJpegExifData()](#getJpegExifData--) | 获取 Exif 实例。 |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | 使用此属性管理 EXIF 数据，允许您添加或检索与图像关联的元数据。 |
| [getExifData()](#getExifData--) | 获取 Exif 数据； |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | 设置 Exif 数据； |
| [getHeight()](#getHeight--) | 使用此属性轻松检索图像的高度。 |
| [getHorizontalResolution()](#getHorizontalResolution--) | 此属性提供对 [RasterImage](../../com.aspose.imaging/rasterimage) 的水平分辨率（以每英寸像素为单位）的访问。 |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | 此属性提供对 [RasterImage](../../com.aspose.imaging/rasterimage) 的水平分辨率（以每英寸像素为单位）的访问。 |
| [getJfif()](#getJfif--) | 此属性允许您访问或修改与 JPEG 图像关联的 JFIF（JPEG 文件交换格式）数据。 |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | 此属性允许您访问或修改与 JPEG 图像关联的 JFIF（JPEG 文件交换格式）数据。 |
| [getRawDataFormat()](#getRawDataFormat--) | 此属性检索图像的原始数据格式，指示图像数据的结构和编码方式。 |
| [getVerticalResolution()](#getVerticalResolution--) | 此属性管理关联的 [RasterImage](../../com.aspose.imaging/rasterimage) 的垂直分辨率（以每英寸像素为单位）。 |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | 此属性管理关联的 [RasterImage](../../com.aspose.imaging/rasterimage) 的垂直分辨率（以每英寸像素为单位）。 |
| [getWidth()](#getWidth--) | 此属性检索图像的宽度（以像素为单位）。 |
| [getRgbColorProfile()](#getRgbColorProfile--) | CMYK 和 YCCK JPEG 图像的 RGB 颜色配置文件确保准确的颜色转换和呈现。 |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | CMYK 和 YCCK JPEG 图像的 RGB 颜色配置文件确保准确的颜色转换和呈现。 |
| [getCmykColorProfile()](#getCmykColorProfile--) | 与 CMYK 和 YCCK JPEG 图像关联的 CMYK 颜色配置文件确保精确的颜色转换和保真度。 |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | 与 CMYK 和 YCCK JPEG 图像关联的 CMYK 颜色配置文件确保精确的颜色转换和保真度。 |
| [getDestinationRgbColorProfile()](#getDestinationRgbColorProfile--) | 在保存过程中，RGBColorProfile 对 CMYK 和 YCCK JPEG 图像的准确颜色转换至关重要。 |
| [setDestinationRgbColorProfile(StreamSource value)](#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | 在保存过程中，RGBColorProfile 对 CMYK 和 YCCK JPEG 图像的准确颜色转换至关重要。 |
| [getDestinationCmykColorProfile()](#getDestinationCmykColorProfile--) | 在保存过程中，CMYK 颜色配置文件对 CMYK 和 YCCK JPEG 图像的准确颜色转换至关重要。 |
| [setDestinationCmykColorProfile(StreamSource value)](#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | 在保存过程中，CMYK 颜色配置文件对 CMYK 和 YCCK JPEG 图像的准确颜色转换至关重要。 |
| [getIgnoreEmbeddedColorProfile()](#getIgnoreEmbeddedColorProfile--) | 检索或修改指示是否忽略嵌入式颜色配置文件的标志。 |
| [setIgnoreEmbeddedColorProfile(boolean value)](#setIgnoreEmbeddedColorProfile-boolean-) | 检索或修改指示是否忽略嵌入式颜色配置文件的标志。 |
| [getOriginalOptions()](#getOriginalOptions--) | 获取此 [Image](../../com.aspose.imaging/image) 实例的原始图像选项。 |
| [removeMetadata()](#removeMetadata--) | 通过将此 `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) 和 `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) 的值设为 `null`，以移除此图像实例的元数据。 |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | 为指定的 [RasterImage](../../com.aspose.imaging/rasterimage) 设置分辨率，确保精确的缩放和打印能力。 |

## Example: The example shows how to load a JpegImage from a file.

``` java
String dir = "c:\\temp\\";

// 从文件加载 JPEG 图像。
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(dir + "sample.jpg");
try {
    // 进行一些图像处理。
    // 保存为另一个 JPEG 文件。
    jpegImage.save(dir + "sample.output.jpg");
} finally {
    jpegImage.dispose();
}
```


## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### JpegImage(String path) {#JpegImage-java.lang.String-}
```
public JpegImage(String path)
```


通过使用指定的路径参数调用其构造函数，[JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) 类即可轻松初始化。此构造函数实现了 JPEG 图像的无缝创建，确保轻松快速地将其集成到您的项目中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 路径 | java.lang.String | 加载图像的路径以及用于初始化像素和调色板数据的路径。 |

### JpegImage(InputStream stream) {#JpegImage-java.io.InputStream-}
```
public JpegImage(InputStream stream)
```


使用流参数，通过 [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) 类初始化 JPEG 图像对象。此构造函数简化了 JPEG 图像的使用过程，提供了一种直接的方式，轻松将其集成到您的项目中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.InputStream | 用于加载图像的流以及用于初始化像素和调色板数据的流。 |

### JpegImage(RasterImage rasterImage) {#JpegImage-com.aspose.imaging.RasterImage-}
```
public JpegImage(RasterImage rasterImage)
```


使用光栅图像参数初始化 [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) 类的新实例。此构造函数提供了一种便捷方式，可直接从光栅图像创建 JPEG 图像，简化了在应用程序中处理 JPEG 图像的工作流程。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | 用于初始化像素和调色板数据的图像。 |

### JpegImage(int width, int height) {#JpegImage-int-int-}
```
public JpegImage(int width, int height)
```


使用指定的宽度和高度参数创建 [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) 类的新实例。此构造函数允许您创建具有自定义尺寸的 JPEG 图像，为在应用程序中管理图像大小提供灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 图像宽度。 |
| 高度 | int | 图像高度。 |

### JpegImage(JpegOptions jpegOptions, int width, int height) {#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-}
```
public JpegImage(JpegOptions jpegOptions, int width, int height)
```


使用提供的 JPEG 选项初始化新的 [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) 对象。此构造函数使您能够定制 JPEG 图像的各种设置，如压缩级别、质量和其他参数，从而对生成的图像格式进行精确控制。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | JPEG 选项。 |
| 宽度 | int | 图像宽度。 |
| 高度 | int | 图像高度。 |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


使用此属性轻松获取图像的格式。它提供了有关文件格式的有价值信息，有助于在各种平台和应用程序之间实现无缝集成和兼容性检查。

**Returns:**
long
### getJpegOptions() {#getJpegOptions--}
```
public JpegOptions getJpegOptions()
```


轻松获取在创建或加载此 [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) 实例时使用的 JPEG 选项。此属性提供了有关所使用的具体设置的有价值细节，使用户能够有效地理解和复现图像处理工作流。无论是压缩级别、质量设置还是其他参数，此属性都提供了实现无缝图像操作的关键洞察。

**Returns:**
[JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) - The JPEG options.

**Example: The following example shows how to extract the header information from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = image.getJpegOptions();

    System.out.println("The number of bits per channel: " + jpegOptions.getBitsPerChannel());
    System.out.println("The max allowed size for all internal buffers: " + jpegOptions.getBufferSizeHint());
    System.out.println("The color type: " + jpegOptions.getColorType());
    System.out.println("The compression type: " + jpegOptions.getCompressionType());
    System.out.println("The image quality: " + jpegOptions.getQuality());

    if (jpegOptions.getResolutionSettings() != null) {
        System.out.println("The horizontal resolution: " + jpegOptions.getResolutionSettings().getHorizontalResolution());
        System.out.println("The vertical resolution: " + jpegOptions.getResolutionSettings().getVerticalResolution());
    }

    for (int i = 0; i < jpegOptions.getHorizontalSampling().length; i++) {
        System.out.printf("The sampling for component %s: %sx%s\r\n", i, jpegOptions.getHorizontalSampling()[i], jpegOptions.getVerticalSampling()[i]);
    }
} finally {
    image.dispose();
}

//输出如下：
//每通道位数：8
//所有内部缓冲区允许的最大大小：0
//颜色类型：YCbCr
//压缩类型：Baseline
//图像质量：75
//组件 0 的采样：1x1
//组件 1 的采样：1x1
//组件 2 的采样：1x1
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


使用此属性轻松获取图像的像素深度，提供对颜色或灰度表现丰富度的洞察。无论是鲜艳的照片还是单色插图，此属性都提供了关于图像视觉复杂性的关键信息。

**Returns:**
int - 图像每像素位数。
### getComment() {#getComment--}
```
public String getComment()
```


使用此属性管理 JPEG 文件注释，允许您添加或检索与图像关联的描述性标注。无论是为图像添加元数据标签还是附加额外上下文，此属性都提供了组织和分类 JPEG 文件的灵活性。

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


使用此属性管理 JPEG 文件注释，允许您添加或检索与图像关联的描述性标注。无论是为图像添加元数据标签还是附加额外上下文，此属性都提供了组织和分类 JPEG 文件的灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegExifData() {#getJpegExifData--}
```
public JpegExifData getJpegExifData()
```


获取 Exif 实例。

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif instance.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


使用此属性管理 EXIF 数据，允许您添加或检索与图像关联的元数据。无论是提取相机设置信息还是修改现有元数据，此属性都提供了管理 EXIF 数据容器的灵活性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


获取 Exif 数据；

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data;

**Example: The following example shows how to extract EXIF tags from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.exif.ExifData exifData = image.getExifData();

    System.out.println("The general EXIF data");
    System.out.println("------------------------------------------");
    if (exifData != null) {
        System.out.println("The EXIF version: " + exifData.getExifVersion());
        System.out.println("The camera serial number: " + exifData.getBodySerialNumber());
        System.out.println("The color space: " + exifData.getColorSpace());
        System.out.println("The brightness: " + exifData.getBrightnessValue());
        System.out.println("The contrast: " + exifData.getContrast());
        System.out.println("The gamma: " + exifData.getGamma());
        System.out.println("The sharpness: " + exifData.getSharpness());
        System.out.println("The aperture: " + exifData.getApertureValue());
        System.out.println("The exposure mode: " + exifData.getExposureMode());
        System.out.println("The exposure bias: " + exifData.getExposureBiasValue());
        System.out.println("The exposure time: " + exifData.getExposureTime());
        System.out.println("The focal length: " + exifData.getFocalLength());
        System.out.println("The focal plane resolution unit: " + exifData.getFocalPlaneResolutionUnit());
        System.out.println("The lens model: " + exifData.getLensModel());
        System.out.println("The shutter speed: " + exifData.getShutterSpeedValue());
    }

    System.out.println("The JPEG EXIF data");
    System.out.println("------------------------------------------");
    if (exifData instanceof com.aspose.imaging.exif.JpegExifData) {
        com.aspose.imaging.exif.JpegExifData jpegExifData = (com.aspose.imaging.exif.JpegExifData) exifData;

        System.out.println("The camera manufacturer: " + jpegExifData.getMake());
        System.out.println("The camera model: " + jpegExifData.getModel());
        System.out.println("The photometric interpretation: " + jpegExifData.getPhotometricInterpretation());
        System.out.println("The artist: " + jpegExifData.getArtist());
        System.out.println("The copyright: " + jpegExifData.getCopyright());
        System.out.println("The image description: " + jpegExifData.getImageDescription());
        System.out.println("The orientation: " + jpegExifData.getOrientation());
        System.out.println("The software: " + jpegExifData.getSoftware());
    }
} finally {
    image.dispose();
}

//输出如下：
//通用 EXIF 数据
//------------------------------------------
//EXIF 版本： [B@163e4e87
//相机序列号：7100536
//颜色空间：SRgb
//亮度：
//对比度：Normal
//伽马：
//锐度: 0
//光圈: 4.64(4643856 / 1000000)
//曝光模式: 手动
//曝光补偿: 0.67(4 / 6)
//曝光时间: 0.01(1 / 160)
//焦距: 145.00(1450 / 10)
//焦平面分辨率单位: Cm
//镜头型号: 70.0 - 200.0 mm f/ 4.0
//快门速度: 7.32(7321928 / 1000000)
//JPEG EXIF 数据
//------------------------------------------
//相机制造商: NIKON CORPORATION
//相机型号: NIKON D5
//光度解释: 0
//艺术家:
//版权:
//图像描述:
//方向: TopLeft
//软件: Adobe Photoshop Camera Raw 9.9(Macintosh)
```

### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


设置 Exif 数据；

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif 数据; |

### getHeight() {#getHeight--}
```
public int getHeight()
```


使用此属性轻松检索图像的高度。它提供对图像垂直尺寸的快速访问，使您能够高效地确定其大小和宽高比，而无需复杂的计算或额外的方法。

**Returns:**
int - 图像高度（像素）。
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


此属性授予您访问 [RasterImage](../../com.aspose.imaging/rasterimage) 的水平分辨率的权限，单位为每英寸像素。通过设置或获取此值，您可以精确控制图像的分辨率，确保其满足您对质量和清晰度的特定要求。

**Returns:**
double - 水平分辨率。

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // 获取 BmpImage 的水平和垂直分辨率
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// 输出可能如下所示：
// 水平分辨率（每英寸像素数）：300.0
// 垂直分辨率（每英寸像素数）：300.0
// 将分辨率设置为 96 dpi
// 水平分辨率（每英寸像素数）：96.0
// 垂直分辨率（每英寸像素数）：96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


此属性授予您访问 [RasterImage](../../com.aspose.imaging/rasterimage) 的水平分辨率的权限，单位为每英寸像素。通过设置或获取此值，您可以精确控制图像的分辨率，确保其满足您对质量和清晰度的特定要求。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 水平分辨率。 |

注意，默认情况下此值始终为 96，因为不同平台无法返回屏幕分辨率。您可以考虑使用 `setResolution` 方法在一次调用中更新两个分辨率值。 |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


此属性允许您访问或修改与 JPEG 图像关联的 JFIF（JPEG 文件交换格式）数据。JFIF 是在计算机和其他设备之间交换 JPEG 压缩图像的标准格式。通过获取或设置此属性，您可以与 JFIF 数据交互，可能包括图像分辨率、宽高比和缩略图等信息。

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


此属性允许您访问或修改与 JPEG 图像关联的 JFIF（JPEG 文件交换格式）数据。JFIF 是在计算机和其他设备之间交换 JPEG 压缩图像的标准格式。通过获取或设置此属性，您可以与 JFIF 数据交互，可能包括图像分辨率、宽高比和缩略图等信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


此属性检索图像的原始数据格式，指示图像数据的结构和编码方式。了解原始数据格式对于有效处理或操作图像数据至关重要。它提供对图像底层表示的洞察，例如是否已压缩、是否采用特定色彩空间编码，或是否存储在特定文件格式中。访问此属性可让您获取有关图像数据结构的有价值信息，从而能够执行针对其特定格式的各种操作或优化。

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


此属性管理关联的 [RasterImage](../../com.aspose.imaging/rasterimage) 的垂直分辨率，单位为每英寸像素。调整此分辨率会影响图像在固定物理尺寸下打印或显示时的大小和质量。通过设置此属性，您可以控制图像像素在垂直方向上的密集程度，从而影响其整体清晰度和锐度。

**Returns:**
double - 垂直分辨率。

注意，默认情况下此值始终为 72，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // 获取 BmpImage 的水平和垂直分辨率
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// 输出可能如下所示：
// 水平分辨率（每英寸像素数）：300.0
// 垂直分辨率（每英寸像素数）：300.0
// 将分辨率设置为 96 dpi
// 水平分辨率（每英寸像素数）：96.0
// 垂直分辨率（每英寸像素数）：96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


此属性管理关联的 [RasterImage](../../com.aspose.imaging/rasterimage) 的垂直分辨率，单位为每英寸像素。调整此分辨率会影响图像在固定物理尺寸下打印或显示时的大小和质量。通过设置此属性，您可以控制图像像素在垂直方向上的密集程度，从而影响其整体清晰度和锐度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 垂直分辨率。 |

注意，默认情况下此值始终为 72，因为不同平台无法返回屏幕分辨率。您可以考虑使用 SetResolution 方法在一次调用中更新两个分辨率值。 |

### getWidth() {#getWidth--}
```
public int getWidth()
```


此属性检索图像的宽度，单位为像素。它提供有关图像尺寸的关键信息，使图像数据能够准确渲染、操作或显示。

**Returns:**
int - 图像宽度（像素）。
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


CMYK 和 YCCK JPEG 图像的 RGB 颜色配置文件确保准确的颜色转换和呈现。它必须与 CMYKColorProfile 配对，以保持颜色渲染的一致性和保真度。此配对对于需要精确颜色管理和图像再现的应用程序至关重要，确保 RGB 数据被正确解释和显示。

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


CMYK 和 YCCK JPEG 图像的 RGB 颜色配置文件确保准确的颜色转换和呈现。它必须与 CMYKColorProfile 配对，以保持颜色渲染的一致性和保真度。此配对对于需要精确颜色管理和图像再现的应用程序至关重要，确保 RGB 数据被正确解释和显示。

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


与 CMYK 和 YCCK JPEG 图像关联的 CMYK 颜色配置文件确保精确的颜色转换和保真度。它与 RGBColorProfile 协同工作，以保证在各种设备和应用程序中的准确颜色呈现。此配对对于保持颜色渲染的一致性并实现最佳图像质量至关重要。

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


与 CMYK 和 YCCK JPEG 图像关联的 CMYK 颜色配置文件确保精确的颜色转换和保真度。它与 RGBColorProfile 协同工作，以保证在各种设备和应用程序中的准确颜色呈现。此配对对于保持颜色渲染的一致性并实现最佳图像质量至关重要。

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

### getDestinationRgbColorProfile() {#getDestinationRgbColorProfile--}
```
public StreamSource getDestinationRgbColorProfile()
```


RGBColorProfile 对于在保存过程中对 CMYK 和 YCCK JPEG 图像进行准确颜色转换至关重要。当与 CMYKColorProfile 配对时，它确保颜色正确渲染，并在不同设备和应用程序之间保持一致性。此组合对于保留预期的颜色表现并实现高质量图像输出至关重要。

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationRgbColorProfile(StreamSource value) {#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationRgbColorProfile(StreamSource value)
```


RGBColorProfile 对于在保存过程中对 CMYK 和 YCCK JPEG 图像进行准确颜色转换至关重要。当与 CMYKColorProfile 配对时，它确保颜色正确渲染，并在不同设备和应用程序之间保持一致性。此组合对于保留预期的颜色表现并实现高质量图像输出至关重要。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getDestinationCmykColorProfile() {#getDestinationCmykColorProfile--}
```
public StreamSource getDestinationCmykColorProfile()
```


CMYK 颜色配置文件对于在保存过程中对 CMYK 和 YCCK JPEG 图像进行准确颜色转换至关重要。它与 RGBColorProfile 协同工作，以确保正确的颜色呈现，在不同设备和软件之间保持一致性和质量。此同步对于在最终保存的图像中实现准确可靠的颜色渲染至关重要。

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationCmykColorProfile(StreamSource value) {#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationCmykColorProfile(StreamSource value)
```


CMYK 颜色配置文件对于在保存过程中对 CMYK 和 YCCK JPEG 图像进行准确颜色转换至关重要。它与 RGBColorProfile 协同工作，以确保正确的颜色呈现，在不同设备和软件之间保持一致性和质量。此同步对于在最终保存的图像中实现准确可靠的颜色渲染至关重要。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getIgnoreEmbeddedColorProfile() {#getIgnoreEmbeddedColorProfile--}
```
public boolean getIgnoreEmbeddedColorProfile()
```


检索或修改标记嵌入颜色配置文件是否被忽略的标志。通过设置此标志，用户可以指定是否使用默认颜色配置文件而非嵌入的配置文件。此选项确保对颜色管理有更大的控制，便于在各种平台和应用程序之间实现一致性和兼容性的调整。

**Returns:**
boolean
### setIgnoreEmbeddedColorProfile(boolean value) {#setIgnoreEmbeddedColorProfile-boolean-}
```
public void setIgnoreEmbeddedColorProfile(boolean value)
```


检索或修改标记嵌入颜色配置文件是否被忽略的标志。通过设置此标志，用户可以指定是否使用默认颜色配置文件而非嵌入的配置文件。此选项确保对颜色管理有更大的控制，便于在各种平台和应用程序之间实现一致性和兼容性的调整。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


获取此 [Image](../../com.aspose.imaging/image) 实例的原始图像选项。

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - A clone of original image options.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


通过将此 `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) 和 `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) 的值设为 `null`，以移除此图像实例的元数据。

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


为指定的 [RasterImage](../../com.aspose.imaging/rasterimage) 建立分辨率，确保准确的缩放和打印功能。此方法使用户能够根据其特定需求定制图像分辨率，无论是用于数字显示还是实体复制。通过设置分辨率，用户可以优化图像质量并确保与各种输出设备和介质的兼容性，提升整体视觉体验和图像的可用性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dpiX | double | `RasterImage` 的水平分辨率（每英寸点数）。 |
| dpiY | double | `RasterImage` 的垂直分辨率（每英寸点数）。 |


**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // 获取 BmpImage 的水平和垂直分辨率
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // 使用 SetResolution 方法在一次调用中更新两个分辨率值。
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// 输出可能如下所示：
// 水平分辨率（每英寸像素数）：300.0
// 垂直分辨率（每英寸像素数）：300.0
// 将分辨率设置为 96 dpi
// 水平分辨率（每英寸像素数）：96.0
// 垂直分辨率（每英寸像素数）：96.0
```

