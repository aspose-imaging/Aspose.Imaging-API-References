---
title: "PsdOptions 类"
type: docs
weight: 260
url: /zh/python-net/aspose.imaging.imageoptions/psdoptions/
---

**Summary:** Create Photoshop Document (PSD) images with our API, offering versatile options<br/>            with different format versions, compression methods, color modes, and<br/>            bits counts per color channel. Seamlessly handle XMP metadata containers,<br/>            ensuring comprehensive image processing with the power of PSD format features<br/>            like image layers, layer masks, and file information for customization<br/>            and creativity in your designs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PsdOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | 初始化 [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) 类的新实例。 |
| [PsdOptions(options)](#PsdOptions_options_2) | 初始化 [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| channel_bits_count | int | r/w | 获取或设置每个颜色通道的位计数。 |
| channels_count | int | r/w | 获取或设置颜色通道的数量。 |
| [color_mode](#color_mode1) | [ColorModes](/imaging/python-net/aspose.imaging.fileformats.psd/colormodes/) | r/w | 获取或设置 PSD 颜色模式。 |
| [compression_method](#compression_method2) | [CompressionMethod](/imaging/python-net/aspose.imaging.fileformats.psd/compressionmethod/) | r/w | 获取或设置 PSD 压缩方法。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 数据。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| psd_version | [PsdVersion](/imaging/python-net/aspose.imaging.fileformats.psd/psdversion/) | r/w | 获取或设置文件格式版本。它可以是 PSD 或 PSB。 |
| refresh_image_preview_data | bool | r/w | 获取或设置一个值，指示是否 [refresh image preview data] - 该选项用于最大化与其他 PSD 图像查看器的兼容性。<br/>            请注意，文本图层绘制到最终布局在 Compact Framework 平台上不受支持。 |
| remove_global_text_engine_resource | bool | r/w | 获取或设置一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本层的 psd 文件，仅在处理后无法在 Adobe Photoshop 中打开时（主要与缺失字体的文本层相关）。<br/>            使用此选项后，用户需要在 Photoshop 打开的文件中执行以下操作：Menu "Text" -&gt; "Process absent fonts"。该操作后所有文本将再次出现。<br/>            请注意，此操作可能导致一些最终布局的更改。 |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| vectorization_options | [PsdVectorizationOptions](/imaging/python-net/aspose.imaging.imageoptions/psdvectorizationoptions/) | r/w | 获取或设置 PSD 矢量化选项。 |
| 版本 | int | r/w | 获取或设置 PSD 文件版本。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 数据容器 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建此实例的成员逐个克隆。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

初始化 [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) 类的新实例。

### Constructor: PsdOptions(options) {#PsdOptions_options_2}


```
 PsdOptions(options) 
```

初始化 [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| options | [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) | 选项。 |

### Property: color_mode {#color_mode1}

获取或设置 PSD 颜色模式。

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


### Property: compression_method {#compression_method2}

获取或设置 PSD 压缩方法。

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


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
### This example demonstrates the use of `aspose.imaging` API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format. {#example_11}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from os.path import join as path_join

directory = "c:\\temp\\"

#创建图像类的实例，并通过文件路径使用现有文件进行初始化
with Image.load(path_join(directory, "sample.bmp")) as image:
	#创建 PsdOptions 类的实例
	psdOptions = PsdOptions()
	#将 CompressionMethod 设置为 RLE
	#注意：其他受支持的 CompressionMethod 为 CompressionMethod.RAW [无压缩]
	psdOptions.compression_method = CompressionMethod.RLE
	#将 ColorMode 设置为 GRAYSCALE
	#注意：其他受支持的 ColorModes 包括 ColorModes.BITMAP 和 ColorModes.RGB
	psdOptions.color_mode = ColorModes.GRAYSCALE
	#使用提供的 PsdOptions 设置将图像保存到磁盘位置
	image.save(path_join(directory, "output.psd"), psdOptions)
}

```

