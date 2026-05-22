---
title: "JpegOptions 类"
type: docs
weight: 160
url: /zh/python-net/aspose.imaging.imageoptions/jpegoptions/
---

**Summary:** Create high-quality JPEG images effortlessly with our API, offering adjustable<br/>            levels of compression to optimize storage size without compromising image quality.<br/>            Benefit from support for various compression types, near lossless coding,<br/>            RGB and CMYK color profiles, as well as EXIF, JFIF image data, and XMP<br/>            containers, ensuring versatile and customizable options for your image creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.JpegOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IHasJpegExifData, ImageOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | 初始化一个新的 [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) 类的实例。 |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | 初始化一个新的 [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bits_per_channel | System.Byte | r/w | 获取或设置无损 jpeg 图像的每通道位数。现在我们支持每通道 2 到 8 位。 |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | CMYK jpeg 图像的目标 CMYK 颜色配置文件。用于保存图像。必须与 RGBColorProfile 配对，以实现正确的颜色转换。 |
| color_type | [JpegCompressionColorMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressioncolormode/) | r/w | 获取或设置 jpeg 图像的颜色类型。 |
| 评论 | string | r/w | 获取或设置 jpeg 文件注释。 |
| compression_type | [JpegCompressionMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressionmode/) | r/w | 获取或设置压缩类型。 |
| default_memory_allocation_limit | int | r/w | 获取或设置默认内存分配限制。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) | r/w | 获取或设置 Exif 数据容器。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| horizontal_sampling | System.Byte | r/w | 获取或设置每个组件的水平子采样。 |
| jfif | [JFIFData](/imaging/python-net/aspose.imaging.fileformats.jpeg/jfifdata/) | r/w | 获取或设置 jfif。 |
| jpeg_ls_allowed_lossy_error | int | r/w | 获取或设置 JPEG-LS 的近无损编码差值界限（来自 JPEG-LS 规范的 NEAR 参数）。 |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/) | r/w | 获取或设置 JPEG-LS 的交错模式。 |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | 获取或设置 JPEG-LS 的预设参数。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| preblend_alpha_if_present | bool | r/w | 获取或设置一个值，指示在存在 alpha 通道时是否应将红、绿、蓝组件与背景颜色混合。 |
| quality | int | r/w | 获取或设置图像质量。 |
| rd_opt_settings | [RdOptimizerSettings](/imaging/python-net/aspose.imaging.imageoptions/rdoptimizersettings/) | r/w | 获取或设置 RD 优化器设置。 |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| resolution_unit | [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | r/w | 获取或设置分辨率单位。 |
| rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | CMYK jpeg 图像的目标 RGB 颜色配置文件。用于保存图像。必须与 CMYKColorProfile 配对，以实现正确的颜色转换。 |
| sample_rounding_mode | [SampleRoundingMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/) | r/w | 获取或设置采样四舍五入模式，以将 8 位值适配为 n 位值。_JpegOptions.BitsPerChannel_ |
| scaled_quality | int | r | 缩放质量。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| vertical_sampling | System.Byte | r/w | 获取或设置每个组件的垂直子采样。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建此实例的成员逐个克隆。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

初始化一个新的 [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) 类的实例。

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

初始化一个新的 [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) | JPEG 选项。 |

### Method: clone() {#clone__1}


```
 clone() 
```

创建此实例的成员逐个克隆。

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 此实例的成员逐个克隆。 |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | 元数据。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果 [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) 实例支持和/或实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例，则为 true；否则为 false。 |


## **Examples**
### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#将现有的 gif 图像加载为 Image 类的实例
with Image.load(path_join(directory, "sample.gif")) as image:
	# 使用默认选项导出为 BMP 文件格式
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# 使用默认选项导出为 JPEG 文件格式
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# 使用默认选项导出为 PNG 文件格式
	image.save(path_join(directory, "output.png"), PngOptions())
	# 使用默认选项导出为 TIFF 文件格式
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

