---
title: "PngOptions 类"
type: docs
weight: 250
url: /zh/python-net/aspose.imaging.imageoptions/pngoptions/
---

**Summary:** Create high-quality Portable Network Graphics (PNG) raster images effortlessly<br/>            with our API, offering customizable options for compression levels,<br/>            bits per pixel depths, and alpha bits. Seamlessly process XMP metadata containers,<br/>            ensuring comprehensive image metadata management, and empowering you to tailor<br/>            PNG images to your exact specifications with ease.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | 初始化一个新的 [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) 类实例。 |
| [PngOptions(png_options)](#PngOptions_png_options_2) | 初始化一个新的 [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | 默认压缩级别。 |
| bit_depth | System.Byte | r/w | 获取或设置位深度值，范围为 1、2、4、8、16。<br/>            <br/><br/>            请注意以下限制：<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) 支持位深度为 1、2、4、8。<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) 支持位深度为 8。<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) 支持位深度为 8、16。<br/>            <br/> |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [color_type](#color_type1) | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | 获取或设置颜色的类型。 |
| [compression_level](#compression_level2) | int | r/w | 获取或设置 [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) 的压缩级别。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 数据。 |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | 获取或设置在 png 文件保存过程中使用的过滤器类型。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | 获取或设置 [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) 的压缩级别。 |
| [progressive](#progressive3) | bool | r/w | 获取或设置一个值，以指示 [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) 是否为渐进式。 |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建此实例的成员逐个克隆。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

初始化一个新的 [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) 类实例。

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

初始化一个新的 [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) | PNG 选项。 |

### Property: color_type {#color_type1}

获取或设置颜色的类型。

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: compression_level {#compression_level2}

获取或设置 [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) 的压缩级别。

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: progressive {#progressive3}

获取或设置一个值，以指示 [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) 是否为渐进式。

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


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
### This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class {#example_12}
``` python

from aspose.imaging import Image, RotateFlipType, Graphics, Color, Pen, Rectangle, Point, Size,\
	Font, PointF
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from aspose.imaging.sources import StreamSource

from os.path import join as path_join

#创建文件流的实例
with open(r"C:\temp\output.png", "w+b") as stream:
	#创建 PngOptions 实例并设置其各种属性
	pngOptions = PngOptions()
	#设置 PngOptions 的 Source
	pngOptions.source = StreamSource(stream)
	#创建 Image 实例
	with Image.create(pngOptions, 500, 500) as image:
		#创建并初始化 Graphics 类的实例
		graphics = Graphics(image)
		#清除 Graphics 表面
		graphics.clear(Color.wheat);
		#通过指定具有黑色的 Pen 对象来绘制弧线，
		#一个围绕弧线的矩形、起始角度和扫掠角度
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#通过指定具有蓝色的 Pen 对象和坐标点来绘制贝塞尔曲线。
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#通过指定具有绿色颜色的 Pen 对象和一个点数组来绘制曲线
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#使用 Pen 对象和一个包围的矩形绘制椭圆
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#绘制直线
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#绘制饼图扇形
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#通过指定具有红色颜色的 Pen 对象和一个点数组来绘制多边形
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#绘制矩形
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#创建 SolidBrush 对象并设置其各种属性
		brush = SolidBrush()
		brush.color = Color.purple
		#使用 SolidBrush 对象和 Font 在特定点绘制字符串
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# 保存所有更改。
		image.save();

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

