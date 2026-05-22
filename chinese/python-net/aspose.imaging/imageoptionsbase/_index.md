---
title: "ImageOptionsBase 类"
type: docs
weight: 5760
url: /zh/python-net/aspose.imaging/imageoptionsbase/
---

**Summary:** The image base options.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageOptionsBase

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| [buffer_size_hint](#buffer_size_hint1) | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 数据。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| [palette](#palette2) | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| [resolution_settings](#resolution_settings3) | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建此实例的成员逐个克隆。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |


### Property: buffer_size_hint {#buffer_size_hint1}

获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。

**See also:**

**[Example # 1](#example_180)**: The following example shows how to set a memory limit when creating a new JPE...


### Property: palette {#palette2}

获取或设置颜色调色板。

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...

**[Example # 3](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...


### Property: resolution_settings {#resolution_settings3}

获取或设置分辨率设置。

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


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
### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# 创建一个 100 x 100 像素的 BMP 图像。
with BmpImage(100, 100) as bmpImage:
	# 图像左上角到右下角的线性渐变。
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# 使用线性渐变画刷填充整个图像。
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# 获取最接近的 8 位颜色调色板，覆盖尽可能多的像素，以便调色板图像
	# 在视觉上几乎与没有调色板的 bmp 无法区分
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# 8 位调色板最多包含 256 种颜色。
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# 输出如下：
# 带调色板的图像大小为 11078 字节。
# 不带调色板的图像大小为 40054 字节。

```

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# 加载 png 图像
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# 使用索引颜色类型
	png_options.color_type = PngColorType.INDEXED_COLOR
	# 使用最大压缩
	png_options.compression_level = 9
	# 获取最接近的 8 位颜色调色板，覆盖尽可能多的像素，以便图像
	# 带调色板的图像在视觉上几乎与没有调色板的图像无法区分。
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# 输出文件大小应显著减小

```

### The following example loads a BMP image and saves it back to BMP using various save options. {#example_91}
``` python
from aspose.imaging import Image, RasterImage, ColorPaletteHelper, ResolutionSetting
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
import os
import aspose.pycore as aspycore

directory = "c:\\temp\\"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	
	rasterImage = aspycore.as_of(image, RasterImage)

	# 创建 BmpOptions
	saveOptions = BmpOptions()

	# 使用每像素 8 位来减小输出图像的大小。
	saveOptions.bits_per_pixel = 8

	# 设置最接近的 8 位颜色调色板，覆盖最多的图像像素，以便调色板图像
	# 几乎在视觉上与非调色板图像无异。
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# 保存时不使用压缩。
	# 您也可以使用 RLE-8 压缩来减小输出图像的大小。
	saveOptions.compression = BitmapCompression.RGB

	# 将水平和垂直分辨率设置为 96 dpi。
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

### The following example creates a palettized grayscale BMP image and then saves it to a file. {#example_92}
``` python

from os.path import join as path_join
from aspose.imaging import Image, ColorPaletteHelper, ResolutionSetting, Graphics, Point, Color
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.brushes import LinearGradientBrush

directory = "c:\\temp\\"
createOptions = BmpOptions()

# 保存到文件
createOptions.source = FileCreateSource(path_join(directory, "output.palette8bit.bmp"), False)
	
# 使用每像素 8 位来减小输出图像的大小。
createOptions.bits_per_pixel = 8

# 设置标准的 8 位灰度颜色调色板，覆盖所有灰度颜色。
# 如果处理后的图像仅包含灰度颜色，则其调色板化版本
# 在视觉上与非调色板图像无异。
createOptions.palette = ColorPaletteHelper.create_8_bit_grayscale(False)

# 保存时不使用压缩。
# 您也可以使用 RLE-8 压缩来减小输出图像的大小。
createOptions.compression = BitmapCompression.RGB

# 将水平和垂直分辨率设置为 96 dpi。
createOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

# 创建一个 100 x 100 像素的 BMP 图像并保存到文件。
with Image.create(createOptions, 100, 100) as image:
	graphics = Graphics(image)
	gradientBrush = LinearGradientBrush(Point(0, 0), Point(image.width, image.height), Color.black, Color.white)
	# 用灰度渐变填充图像
	graphics.fill_rectangle(gradientBrush, image.bounds)
	image.save()


```

### The following example shows how to set a memory limit when creating a new JPEG image. The memory limit is the maximum allowed size (in megabytes) for all internal buffers. {#example_180}
``` python
from os.path import join
from aspose.imaging import Image
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import JpegOptions
from aspose.imaging.fileformats.jpeg import JpegCompressionMode

dir_: str = "c:\\aspose.imaging\\issues\\net\\3404\\"
# 为目标创建的图像设置 50 兆字节的内存限制
create_options = JpegOptions()
create_options.compression_type = JpegCompressionMode.PROGRESSIVE
create_options.buffer_size_hint = 50
create_options.source = FileCreateSource(join(dir_, "createdFile.jpg"), False)
with Aspose.Imaging.Image.create(create_options, 1000, 1000) as image:
	# 保存到相同位置
	image.save()


```

