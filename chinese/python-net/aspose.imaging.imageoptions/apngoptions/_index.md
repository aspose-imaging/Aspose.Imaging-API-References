---
title: "ApngOptions 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.imageoptions/apngoptions/
---

**Summary:** The API for Animated PNG (Animated Portable Network Graphics) image file format<br/>            creation is a dynamic tool for developers seeking to generate captivating<br/>            animated images. With customizable options such as frame duration and the<br/>            number of times to loop, this API allows for fine-tuning animated content<br/>            according to specific needs. Whether creating engaging web graphics or<br/>            interactive visuals, you can leverage this API to seamlessly incorporate<br/>            APNG images with precise control over animation parameters.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.ApngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, PngOptions

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [ApngOptions()](#ApngOptions__1) | 初始化 [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | 默认压缩级别。 |
| bit_depth | System.Byte | r/w | 获取或设置位深度值，范围为 1、2、4、8、16。<br/>            <br/><br/>            请注意以下限制：<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) 支持位深度为 1、2、4、8。<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) 支持位深度为 8。<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) 支持位深度为 8、16。<br/>            <br/> |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | 获取或设置颜色的类型。 |
| compression_level | int | r/w | 获取或设置 [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) 的压缩级别。 |
| [default_frame_time](#default_frame_time1) | int | r/w | 获取或设置默认帧持续时间。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 实例。 |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | 获取或设置在 png 文件保存过程中使用的过滤器类型。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| [num_plays](#num_plays2) | int | r/w | 获取或设置动画循环的次数。<br/>            0 表示无限循环。 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | 获取或设置 [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) 的压缩级别。 |
| progressive | bool | r/w | 获取或设置一个值，以指示 [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) 是否为渐进式。 |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 Xmp 数据。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建此实例的成员逐个克隆。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |


### Constructor: ApngOptions() {#ApngOptions__1}


```
 ApngOptions() 
```

初始化 [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/) 类的新实例。

### Property: default_frame_time {#default_frame_time1}

获取或设置默认帧持续时间。

**See also:**

**[Example # 1](#example_198)**: The following example shows how to export apng APNG file format from other no...


### Property: num_plays {#num_plays2}

获取或设置动画循环的次数。<br/>            0 表示无限循环。

**See also:**

**[Example # 1](#example_197)**: The following example shows how to export to APNG file format.


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
| bool | 如果 _metadata_ 不为 null 且 [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) 实例 <br/>            支持和/或实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例，则为 true；否则为 false。 |


## **Examples**
### The following example shows how to export to APNG file format. {#example_197}
``` python

import aspose.pycore as aspycore
from aspose.imaging import *
from aspose.imaging.imageoptions import *

with Image.load("Animation1.webp") as image:
	# 导出为 APNG 动画，默认使用无限动画循环
	image.save("Animation1.webp.png", ApngOptions())
	# 设置动画循环
	obj_init = ApngOptions()
	# 5 次循环
	obj_init.num_plays = 5
	image.save("Animation2.webp.png", obj_init)


```

### The following example shows how to export apng APNG file format from other non-animated multi-page format. {#example_198}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import ApngOptions

with Image.load("img4.tif") as image:
	# 设置默认帧持续时间
	obj_init = ApngOptions()
	# 500 毫秒
	obj_init.default_frame_time = 500
	image.save("img4.tif.500ms.png", obj_init)
	obj_init2 = ApngOptions()
	# 250 毫秒
	obj_init2.default_frame_time = 250
	image.save("img4.tif.250ms.png", obj_init2)


```

