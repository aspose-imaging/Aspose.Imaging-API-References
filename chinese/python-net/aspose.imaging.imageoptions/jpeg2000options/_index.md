---
title: "Jpeg2000Options 类"
type: docs
weight: 150
url: /zh/python-net/aspose.imaging.imageoptions/jpeg2000options/
---

**Summary:** Create JPEG2000 (JP2) image files with our API, utilizing advanced wavelet technology<br/>            for coding lossless content. Benefit from support for various codecs, including<br/>            irreversible and lossless compression, as well as XMP metadata containers, ensuring<br/>            versatility and high-quality image creation tailored to your needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.Jpeg2000Options

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | 初始化一个新的 [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) 类实例。 |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | 初始化一个新的 [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [codec](#codec1) | [Jpeg2000Codec](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000codec/) | r/w | 获取或设置 JPEG2000 编解码器 |
| 注释 | string[] | r/w | 获取或设置 Jpeg 注释标记。 |
| compression_ratios | int[] | r/w | 获取或设置压缩比数组。<br/>            不同层的压缩比。<br/>            为每个质量级别指定的比率是期望的<br/>            压缩因子。<br/>            需要递减的比率。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 数据。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| [irreversible](#irreversible2) | bool | r/w | 获取或设置一个值，指示是使用不可逆 DWT 9-7（true）还是使用无损 DWT 5-3 压缩（默认）。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建此实例的成员逐个克隆。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

初始化一个新的 [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) 类实例。

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

初始化一个新的 [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) | 要从中复制设置的 Jpeg2000 文件格式选项。 |

### Property: codec {#codec1}

获取或设置 JPEG2000 编解码器

**See also:**

**[Example # 1](#example_161)**: This example shows how to create a JPEG2000 image with the desired options an...

**[Example # 2](#example_163)**: This example shows how to create a PNG image and save it to JPEG2000 with the...


### Property: irreversible {#irreversible2}

获取或设置一个值，指示是使用不可逆 DWT 9-7（true）还是使用无损 DWT 5-3 压缩（默认）。

**See also:**

**[Example # 1](#example_161)**: This example shows how to create a JPEG2000 image with the desired options an...

**[Example # 2](#example_163)**: This example shows how to create a PNG image and save it to JPEG2000 with the...


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
### This example shows how to create a JPEG2000 image with the desired options and save it to a file. {#example_161}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec, Jpeg2000Image
from os.path import join as path_join     


dir_ = "c:\\temp"
create_options = Jpeg2000Options()
# 使用不可逆离散小波变换 9-7
create_options.irreversible = True
# JP2 是 JPEG 2000 码流的“容器”格式。
# J2K 是未包装的原始压缩数据。
create_options.codec = Jpeg2000Codec.J2K
# 创建 100x100 像素的 JPEG2000 图像。
with Jpeg2000Image(100, 100, create_options) as jpeg2000_image:
	graphics = Graphics(jpeg2000_image)
	# 将整幅图像填充为红色。
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, jpeg2000_image.bounds)
	# 保存到文件
	jpeg2000_image.save(path_join(dir_, "sample.output.j2k"))


```

### This example shows how to create a PNG image and save it to JPEG2000 with the desired options. {#example_163}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec
from aspose.imaging.fileformats.png import PngImage
from os.path import join as path_join


dir_ = "c:\\temp"
# 创建一个 100x100 像素的 PNG 图像。
with PngImage(100, 100) as png_image:
	graphics = Graphics(png_image)
	# 将整幅图像填充为红色。
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	save_options = Jpeg2000Options()
	# 使用不可逆离散小波变换 9-7
	save_options.irreversible = True
	# JP2 是 JPEG 2000 码流的“容器”格式。
	# J2K 是未包装的原始压缩数据。
	save_options.codec = Jpeg2000Codec.J2K
	# 保存到文件
	png_image.save(path_join(dir_, "output.j2k"), save_options)


```

