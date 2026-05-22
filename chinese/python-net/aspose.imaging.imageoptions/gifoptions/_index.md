---
title: "GifOptions 类"
type: docs
weight: 120
url: /zh/python-net/aspose.imaging.imageoptions/gifoptions/
---

**Summary:** The API for Graphical Interchange Format (GIF) raster image file creation offers<br/>            developers comprehensive options for generating GIF images with precise<br/>            control. With features to set background color, color palette, resolution,<br/>            interlaced type, transparent color, XMP metadata container, and image<br/>            compression, this API ensures flexibility and efficiency in creating optimized<br/>            and visually appealing GIFs tailored to specific application requirements.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.GifOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | 初始化 [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) 类的新实例。 |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | 初始化 [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置背景颜色。 |
| background_color_index | System.Byte | r/w | 获取或设置 GIF 背景颜色索引。 |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| color_resolution | System.Byte | r/w | 获取或设置 GIF 颜色分辨率。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| do_palette_correction | bool | r/w | 获取或设置一个值，指示是否应用调色板校正。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 数据。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| has_trailer | bool | r/w | 获取或设置一个值，指示 GIF 是否具有尾部。 |
| has_transparent_color | System.Nullable`1[[System.Boolean]] | r/w | 获取或设置一个值，指示 GIF 图像是否具有透明颜色。 <br/>            如果返回值为 **None**，则此属性会被源图像上下文覆盖。 |
| interlaced | bool | r/w | 如果图像应交错，则为 True。 |
| is_palette_sorted | bool | r/w | 获取或设置一个值，指示调色板条目是否已排序。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| loops_count | int | r/w | 获取或设置循环计数（默认 1 次循环） |
| max_diff | int | r/w | 获取或设置允许的最大像素差异。如果大于零，将使用有损压缩。<br/>            推荐的最佳有损压缩值为 80。30 为轻度压缩，200 为重度压缩。<br/>            当仅引入少量损失时效果最佳，由于压缩算法的限制，非常高的损失水平不会带来太多收益。<br/>            允许值的范围是 [0, 1000]。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| pixel_aspect_ratio | System.Byte | r/w | 获取或设置 GIF 像素宽高比。 |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建此实例的成员逐个克隆。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

初始化 [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) 类的新实例。

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

初始化 [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| gif_options | [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) | GIF 选项。 |

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
### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# 创建 MemoryStream 的实例
with strm_ext.create_memory_stream() as stream:
	#创建 GifOptions 的实例并设置其各种属性，包括 Source 属性
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# 创建 Image 的实例
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# 通过将区域指定为图像边界来获取图像的像素
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#遍历数组并设置交替索引像素的颜色
			for index in range(pixel.length):
				if index % 2 == 0:
					#将索引像素颜色设置为黄色
					pixels[index] = yellow_color
				else:
					#将索引像素颜色设置为蓝色
					pixels[index] = blue_color

			#将像素更改应用于图像
			image.save_pixels(image.bounds, pixels)

			# 保存所有更改。
			image.save()

	# 将 MemoryStream 写入文件
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

```

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

