---
title: "BmpOptions 类"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.imageoptions/bmpoptions/
---

**Summary:** The API for BMP and DIB raster image format creation options provides developers<br/>            with a versatile toolset for generating custom Bitmap (BMP) and Device<br/>            Independent Bitmap (DIB) images. With this API, you can precisely define<br/>            image characteristics such as bits per pixel, compression level and compression<br/>            type, tailoring the output to meet specific requirements. This feature-rich<br/>            API empowers developers to create high-quality, customized raster images<br/>            with ease and flexibility for diverse applications.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BmpOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | 初始化一个新的 [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) 类的实例。 |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | 初始化一个新的 [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| [bits_per_pixel](#bits_per_pixel1) | int | r/w | 获取或设置图像的每像素位数。 |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [compression](#compression2) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r/w | 获取或设置压缩类型。默认压缩类型是 [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/)，它允许保存带有透明度的 [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/)。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 数据。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
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


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

初始化一个新的 [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) 类的实例。


**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

初始化一个新的 [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| bmp_options | [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) | BMP 选项。 |

### Property: bits_per_pixel {#bits_per_pixel1}

获取或设置图像的每像素位数。

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 3](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Property: compression {#compression2}

获取或设置压缩类型。默认压缩类型是 [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/)，它允许保存带有透明度的 [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/)。

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...

**[Example # 3](#example_208)**: Decompress BMP image which was previously compressed using DXT1 compression a...

**[Example # 4](#example_225)**: The example shows how to export a BMP from a PNG file while keeping the alpha...

**[Example # 5](#example_226)**: The example shows how to export a BMP with the RGB compression type.


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
### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#创建 `BmpOptions` 实例并设置其各种属性
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#创建 `FileCreateSource` 实例并将其分配为 `BmpOptions` 实例的 `source`
	#第二个 `Boolean` 参数决定要创建的文件是否为_temporal
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#创建 Image 实例并通过调用 Create 方法使用 BmpOptions 实例进行初始化
	with Image.create(bmp_options, 500, 500) as image:
		#进行一些图像处理
		# 保存所有更改
		image.save()


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

### Decompress BMP image which was previously compressed using DXT1 compression algorithm. {#example_208}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions

with Image.load("CompressedTiger.bmp") as image:
	image.save("DecompressedTiger.bmp", BmpOptions())


```

### The example shows how to export a BMP from a PNG file while keeping the alpha channel, save a BMP file with transparency. {#example_225}
``` python
from aspose.imaging import Image
from aspose.imaging.fileformats.png import BmpOptions

source_path = "input.png"
output_path_def = "result_def.bmp"
output_path_def_2 = "result_def-2.bmp"
output_path_bitfields = "result_bitfields.bmp"
# 从文件加载 PNG 图像。
with Image.load(source_path) as pngImage:
	# 默认情况下，BMP 图像会以支持透明度的方式保存。
	# 如果您想显式指定此模式，BmpOptions 的 `compression` 属性应设置为 BitmapCompression.BITFIELDS。
	# BitmapCompression.BITFIELDS 压缩方法是 BmpOptions 中的默认压缩方法。
	# 因此，通过以下任一方式都可以实现导出带有透明度的 Bmp 图像的相同结果。
	# 使用隐式默认选项：
	pngImage.save(output_path_def)
	# 使用显式默认选项：
	pngImage.save(output_path_def_2, BmpOptions())
	# 指定 BitmapCompression.BITFIELDS 压缩方法：
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.BITFIELDS
	pngImage.save(output_path_bitfields, bmp_options)


```

### The example shows how to export a BMP with the RGB compression type. {#example_226}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.imageoptions import BmpOptions

source_path = "input.png"
output_path = "output.png"
# 从文件加载 PNG 图像。
with Image.load(source_path) as pngImage:
	# 默认情况下，BMP 图像会以支持透明度的方式保存，这是通过使用 BitmapCompression.BITFIELDS 压缩方法实现的。
	# 要使用 RGB 压缩方法保存 BMP 图像，应指定 `compression` 属性设置为 BitmapCompression.RGB 的 BmpOptions。
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.RGB
	pngImage.save(output_path, bmp_options)


```

